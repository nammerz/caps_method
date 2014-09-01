caps_method
===========
def caps (string)
	if string.length >10
		string.upcase
	else
		string
	end
end

puts caps ("joe smith")
puts caps ("joe robertson")
