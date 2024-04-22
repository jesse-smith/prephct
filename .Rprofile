options(renv.config.pak.enabled = TRUE)
source("renv/activate.R")

options(repos = c(
  jesse_smith = "https://jesse-smith.r-universe.dev",
  extendr = "https://extendr.r-universe.dev",
  rpolars = "https://rpolars.r-universe.dev",
  mc_stan = "https://mc-stan.org/r-packages",
  getOption("repos")
))

options(
  warnPartialMatchArgs = TRUE,
  warnPartialMatchDollar = TRUE,
  warnPartialMatchAttr = TRUE
)

if (interactive()) {
  suppressMessages(require(conflicted))
  suppressMessages(require(devtools))
  suppressMessages(require(pak))
  suppressMessages(require(reprex))
  suppressMessages(require(usethis))
}


