# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Model II regression Use lmodel2 With (In) R Software
install.packages("lmodel2")
library("lmodel2")
lmodel2 = read.csv("https://raw.githubusercontent.com/timbulwidodostp/lmodel2/main/lmodel2/lmodel2.csv",sep = ";")
# Estimation Model II regression Use lmodel2 With (In) R Software
lmodel2 <- lmodel2(Predicted_by_model ~ Survival, data=lmodel2, nperm=99)
lmodel2
# Model II regression Use lmodel2 With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished