# mtsdi
Multivariate Time Series Data Imputation

This is an EM algorithm based method for imputation of missing values in multivariate normal time series. The imputation algorithm accounts for both spatial and temporal correlation structures. Temporal patterns can be modeled using an ARIMA(p,d,q), optionally with seasonal components, a non-parametric cubic spline or generalized additive models with exogenous covariates. This algorithm is specially tailored for climate data with missing measurements from several monitors along a given region.


## Installation

```r
install.packages("remotes")
remotes::install_github("wjunger/mtsdi")
```

or

```r
install.packages("remotes")
remotes::install_github("NPEA/mtsdi")
```

Check further instruction on how to install R packages from GitHub repositories at the [remotes package repository](https://github.com/r-lib/remotes).

## Notice

The repository [NPEA/mtsdi](https://github.com/NPEA/mtsdi) is an updated fork and it is ready to use. However, if you wish to fork this project, fork the upstream [wjunger/mtsdi](https://github.com/wjunger/mtsdi).

## License

GPL (>= 2)

## Disclaimer

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.