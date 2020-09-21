# .Rprofile
#
# This script is automatically executed on startup
# ==============================================================================

# DO NOT uncomment, unless you know exactly why, or have been instructed to
# do so:
# options(stringsAsFactors = FALSE)

init <- function() {

  # Create a local copy of myScript.R if not done yet.
  if (! file.exists("myScript.R") && file.exists(".tmp.R")) {
    file.copy(".tmp.R", "myScript.R")
    cat("A new file \"myScript.R\" was created. You can use it for\n")
    cat("notes and code experiments.\n\n")
  }

  cat("\n\n")
  cat("Please open the file \".myProfile.R\" (click on the file-name in the\n")
  cat("\"files\" pane), edit it, and save it into the \"myScripts\" folder.\n\n")

  file.edit("ABC-units.R")
  return(invisible(NULL))
}

if (! file.exists("./myScripts/.myProfile.R")) {
  cat("\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n")
  cat("    =================")
  cat("\n\n")
  cat("        WELCOME !\n")
  cat("\n")
  cat("  Type  'init()'  to begin\n\n")
  cat("\n")
  cat("    =================")
  cat("\n\n")

} else {
  cat("\n\nLoading local functions ...")
  source("./myScripts/.myProfile.R")
  source(".utilities.R")
  cat("... done.\n\n")
}

if (default.stringsAsFactors()) {
  cat("WARNING.\n")
  cat("========\n")
  cat("Your default \"stringsAsFactors\" parameter is set to \"TRUE\".\n")
  cat("This will break some of the code.\n")
  cat("Please contact your instructor to troubleshoot and fix this issue.\n")
  cat("\n")
}

# [END]
