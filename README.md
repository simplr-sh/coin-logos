# Coin Logos



Free Open Source collection of 16,119 cryptocurrency logos tracked and active on Coingecko in 4 use-case optimised sizes.

Production-ready logo image URLs courtesy of `jsDelivr` CDN & `Cloudflare`. No bandwidth or request limits. Completely free for anyone to use.


![About Coin Logos](/readme-assets//image.jpg)


### Available Sizes
1. Large - 250px x 250px
2. Standard - 64px x 64px
3. Small - 50px x 50px
4. Thumb - 25px x 25px

### Available Image Formats
1. PNG

### Empowered by [jsDelivr](https://jsdelivr.com) & [Cloudflare](https://cloudflare.com)
```
https://cdn.jsdelivr.net/gh/simplr-sh/coin-logos/images/<coingecko_coin_id>/<large|standard|small|thumb>.png
```
```
https://coin-logos.simplr.sh/images/<coingecko_coin_id>/<large|standard|small|thumb>.png
```

### Last Updated - 20 December 2024

***

## Get Full list of Coingecko coins using Coingecko APIs

https://api.coingecko.com/api/v3/coins/list?include_platform=false&status=active


## Finding list of Coingecko Coins being tracked by us

Checkout [coingecko-active-coins-list.csv](/coingecko-active-coins-list.csv) file.


## How do I search for Coingecko ID using coin `name` or `symbol`

1. Open the [coingecko-active-coins-list.csv](https://github.com/simplr-sh/coin-logos/blob/d257503bfed5fa4662e1cf9847ea034e1919acc1/coingecko-active-coins-list.csv)

![Tracked Coins](</readme-assets/view-csv.png>)

2. Enter the name or symbol of the coin you want to find the Coingecko coin id for.

![Filted Coins](/readme-assets//filtered-csv.png)

3. The `id` column refers to the Coingecko coin id & it's value is used in the URLs mentioned below & in their respective examples.


## How to use

1. Download the individual files and use it in our project as appropriate.

2. use either of the 2 URLs to directly use the image assets anywhere required. Production ready, no bandwidth or rate-limits, ever!.

```
https://coin-logos.simplr.sh/images/<coingecko_coin_id>/<large|standard|small|thumb>.png
```
> The above URL is just a pretty URL. Slightly shorter & more memorable than the original which redirects to the original jsDelivr URL with a 302 code.

Examples:

* https://coin-logos.simplr.sh/images/bitcoin/large.png
* https://coin-logos.simplr.sh/images/solana/standard.png
* https://coin-logos.simplr.sh/images/ethereum/small.png
* https://coin-logos.simplr.sh/images/sui/thumb.png


> For production, use the below `preferred method` of directly using the `cdn.jsDelivr.net` asset URLs.

***

## or (Preferred method)

```
https://cdn.jsdelivr.net/gh/simplr-sh/coin-logos/images/<coingecko_coin_id>/<large|standard|small|thumb>.png
```

Examples:

* https://cdn.jsdelivr.net/gh/simplr-sh/coin-logos/images/bitcoin/large.png
* https://cdn.jsdelivr.net/gh/simplr-sh/coin-logos/images/solana/standard.png
* https://cdn.jsdelivr.net/gh/simplr-sh/coin-logos/images/ethereum/small.png
* https://cdn.jsdelivr.net/gh/simplr-sh/coin-logos/images/sui/thumb.png




