# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finite Mixtures of Beta Regression for Rates and Proportions Use betamix (betareg) With (In) R Software
install.packages("betareg")
library("betareg")
betamix_r = read.csv("https://raw.githubusercontent.com/timbulwidodostp/betamix_r/main/betamix_r/betamix_r.csv",sep = ";")
# Estimation Finite Mixtures of Beta Regression for Rates and Proportions Use betamix (betareg) With (In) R Software
options(digits = 4)
betamix <- betamix(accuracy ~ iq, data = betamix_r, k = 3, nstart = 10, extra_components = extraComponent(type = "uniform", coef = 0.99, delta = 0.01))
summary(betamix)
# Finite Mixtures of Beta Regression for Rates and Proportions Use betamix (betareg) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished