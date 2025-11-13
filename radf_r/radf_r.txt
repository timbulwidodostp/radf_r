# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Recursive Augmented Dickey-Fuller Test Use radf (exuber) With (In) R Software
install.packages("exuber")
library("exuber")
radf_r = read.csv("https://raw.githubusercontent.com/timbulwidodostp/radf_r/main/radf_r/radf_r.csv",sep = ";")
# Estimation Recursive Augmented Dickey-Fuller Test Use radf (exuber) With (In) R Software
rfd1 <- radf(radf_r)
rfd1
rfd2 <- radf(radf_r, minw = 20, lag = 1)
rfd2
# Recursive Augmented Dickey-Fuller Test Use radf (exuber) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished