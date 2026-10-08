# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fast generalized linear model fitting Use fastglm With (In) R Software
install.packages("fastglm")
library("fastglm")
# Estimate Fast generalized linear model fitting Use fastglm With (In) R Software
fastglm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/fastglm/main/fastglm/fastglm.csv",sep = ";")
x <- cbind(fastglm$Independen_1, fastglm$Independen_2, fastglm$Independen_3)
y <- fastglm$Dependen
fastglm <- fastglm(x, y, family = binomial())
summary(fastglm)
# Fast generalized linear model fitting Use fastglm With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished