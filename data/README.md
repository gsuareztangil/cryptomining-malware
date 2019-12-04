# Data

The file [miners_dataset.csv](miners_dataset.csv.tar.gz) contains a snapshot of our malware dataset. Note that not all samples used in our study are provided. In particular, we are not sharing samples discovered by any of our collaborators _alone_ and that are protected by an NDA. The CSV file contains the following columns: 

 * SHA256
 * POOL
 * URLPOOL
 * USER (wallet, email, etc.)
 * PASS
 * NTHREADS
 * AGENT
 * DSTIP
 * DSTPORT
 * DNSRR
 * SOURCE
 * FS
 * ITW_URLS
 * PACKERS
 * TYPE

The file [info_wallets_with_usd.csv](info_wallets_with_usd.csv) contains a snapshot of the data used to compute the profit analysis with the following columns: 

 * POOL
 * USER
 * HASHES
 * HASHRATE
 * LAST_SHARE
 * BALANCE
 * TOTAL_PAID
 * NUM_PAYMENTS
 * DATE_QUERY
 * USD

The file [campaigns.csv](campaigns.csv) contains the captures the samples and wallets found per campaign and it has the following columns: 
 
 * campaign
 * samples
 * wallets