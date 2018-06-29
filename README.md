# atp-top10
A small app written in Go to drive Chrome browser to visit the official [ATP website](https://www.atpworldtour.com/) and capture a screenshot of the top 10 men singles tennis players in the world.\
This is an implementation of the screenshot fuctionality of the [chromedp package](https://github.com/chromedp) which implements the Chrome Debugging Protocol to drive chrome based browsers. Part of the code has been taken and then modified from https://github.com/chromedp/examples which is under the MIT License.

### Installation
Use the `go get` command to get and build the code.
>go get -u github.com/nishchayp/atp-top10

### Run
Simply execute the binary `atp-top10`.
>./$GOPATH/bin/atp-top10
