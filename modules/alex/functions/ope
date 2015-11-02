
xcode_exe(){ echo "${$(xcode-select -p):h:h}" }

openx(){

	X="${1:-.}/**/*\.(xcworkspace|xcodeproj)(/[1])"
	echo "fgound project $X"
	
	# [[ -a ${X=$(ls ./*.xcworkspace(/[1]))} ]] || X=( *.xcodepr*(/[1]) )
	# [[ -e "$X" ]] && open -a "$X""
# } = ";
}

openx "$@"