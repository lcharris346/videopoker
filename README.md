# vp.py
usage: python vp.py [-h] [-c CREDIT] [-d DENOM] [-g ACTIVITY] [-n NUM_SETS] [-b ADDITION_TYPE] [-i ITERATIONS] [-a] [-v] [-p] [-t] [-th THRESHOLD] [-o ODDS]

vp

options:
  -h, --help            show this help message and exit
  -c CREDIT, --credit CREDIT
                        credit
  -d DENOM, --denom DENOM
                        denom
  -g ACTIVITY, --activity ACTIVITY
                        activity:cl,sptrp,stp,dstp,sstk,pstk,php,ultx,fhpw,majm,drmcd
  -n NUM_SETS, --num_sets NUM_SETS
                        num_sets:1,3,5,10
  -b ADDITION_TYPE, --addition_type ADDITION_TYPE
                        addition_type:job,b,bd,db,ddb,tdb,dw
  -i ITERATIONS, --iterations ITERATIONS
                        iterations
  -a, --automate        automate
  -v, --verbose         verbose
  -p, --plot            plot
  -t, --test            test
  -th THRESHOLD, --threshold THRESHOLD
  -o ODDS, --odds ODDS

# calc_target_bankroll
1. Prompt: 
"Enter Game's Max_Credit, Bonus-Type(0:b,1:ddb,2:tdb,3:dw), Denom, N-Hands, Target-Odds: "

2. Enter above for example
5 0 5 1 1200

1. Output: 
========================================
          VIDEO POKER REPORT            
========================================
Bet:               $    25.00
Number of Rounds:  $  3480.00
Expected Loss:     $   783.00
Volatility Buffer: $ 11093.60
Required Bankroll: $ 11876.60
========================================


