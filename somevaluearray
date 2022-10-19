let array = [1,2,3,4,5,6,7,1,2,3,2];
let findDuplicates = arr => arr.filter((item, index) => arr.indexOf(item) != index)

let unique = [...new Set(findDuplicates(array))]
console.log("nilai unik = ", unique)

let hasil = 0

for (let i = 0; i < unique.length; i++){
	for (let j = 0; j < array.length; j++){		
		if (unique[i] == array[j]) {
			hasil++
		} 
	}
}

console.log("jumlah total nilai yg sama = ", hasil)
