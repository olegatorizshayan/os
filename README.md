# os
my os labs
# Tree:
apr4(/ apr2/ apr5)(/ apr3/apr6)(/ apr1)
# Place of creation
apr5
# Place of path choosing
apr3
# Place of call
apr1
# Exersize 2
49
# Exersize 3
84
# Code
# 1.
  537  cd ~
  538  mkdir Zadorozhnyi
  539  cd Zadorozhnyi/
  540  mkdir bin
  541  mkdir -p apr4/apr2/apr5 apr4/apr3/apr6 /apr4/apr1
  542  sudo mkdir -p apr4/apr2/apr5 apr4/apr3/apr6 /apr4/apr1
# 2.
  544  ls
  545  cd apr4/
  546  ls
  547  cd apr2/apr5/
  548  vim ../../../bin/cmd1
# 3.
  550  cd ..
  551  ls
  552  cd ..
  553  ls
  554  cd apr3
  555  chmod a+x ../../bin/cmd1
# 4.
  557  ls
  558  cd ..
  559  ls
  560  cd ..
  561  ls
  562  cd apr4/
  563  ls
  564  du
  565  cd ..
  566  ls
  567  du
  568  ls
  569  cd apr4/
  570  mkdir apr1
  571  cd apr1
  572  ls
  573  ./../../bin/cmd1 1 2 3 4 5 6
  574  ./../../bin/cmd1 2 3 4 5 6 7
  575  ./../../bin/cmd1 3 4 5 6 7 8
  576  ls
  577  du
# 5.
  579  ls
  580  cd ..
  581  ls
  582  du
  583  ls -l /bin > apr3/apr6/f1
  584  cd ..
  585  cd bin/
  586  vim cmd2
  587  chmod a+x cmd2
  588  ./cmd2
  589  cat ../apr4/apr2/f2 
  590  vim cmd2
  591  ./cmd2
  592  vim cmd2
  593  ./cmd2
  594  vim cmd2
  595  ./cmd2
  596  cat ../apr4/apr2/f2
# 6.
  598  vim cmd2
  599  ./cmd2
  600  vim cmd2
  601  ./cmd2
  602  vim cmd2
  603  ./cmd2
  604  cat ../apr4/apr2/f2 
  605  vim cmd2
  606  ./cmd2
  607  vim cmd2
  608  ./cmd2
  609  vim cmd2
  610  ./cmd2
  611  cat ../apr4/apr2/f2 
  612  vim cmd2
  613  ./cmd2
  614  cat ../apr4/apr2/f2 
  615  cd ..
  616  cd apr4/
  617  ls
  618  cd apr3
  619  ps -elF > f1
  620  cd ..
  621  cd bin/
  622  vim cmd3
  623  chmod a+x cmd3
  624  ./cmd3
  625  vim cmd3
  626  ./cmd3
  627  cd ..
  628  ls
  629  cd apr4/
  630  ls
  631  du
  632  cd apr2
  633  cd apr5/
  634  ls
  635  cat f13
# bin
# cmd1
mkdir -p $4/$2/$5 $4/$3/$6 $4/$1
# cmd2
sed -n '10,20 p' ../apr4/apr3/apr6/f1 > ../apr4/apr2/f2
# cmd3
awk '{print length($5) " " length($14) " " length($9) " " length($11) " " NF}' ../apr4/apr3/f1  > ../apr4/apr2/apr5/f13
