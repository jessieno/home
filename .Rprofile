.First <- function(){
    if(interactive()){
        library(dataview)
        ev <- entry.view
        tv <- tree.view
    }

    options(repos="http://ftp.sunet.se/pub/lang/CRAN/")

	local.repo <- "file:/data/projects/ALL_450k_methylation/R_packages"
	options(repos=c(getOption("repos"), local.repo))
	if(interactive()){
	    utils::update.packages(repo=local.repo, ask=FALSE)
	}
	rm(local.repo)

}

