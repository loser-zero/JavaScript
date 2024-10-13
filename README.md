/* Это мои решения задач от Трепачева Дмитрия с его сайта https://code.mu/ru/javascript/tasker/stager/ (по запросу "javascript задачи" его сайт был первым).
Я решал их в онлайн компиляторе а потом сохранял в тг (daily), сейчас здесь неаккуратно, больше как факт хочется показать что я делал что-то. 
Любое можно скопировать, проверить, что-то выдает.
Собрал, сейчас сохраняю на Уровень 3.10 задачника JavaScript №3 */

> daily:
let num = 5

if (num >= 0) {
    console.log(true)
} else {
    console.log(false)
}



let str = "wanna beef for me?"

console.log(str.length)



let str = "wanna beef for me?"

console.log(str[str.length - 1])



let num = 433

if(num % 2 == 0) {
    console.log(true)
} else {
    console.log(false)
}



let str = "wanna beef for me?"
let str2 = "wanna beef for me?"

if (str[0] === str2[0]) {
    console.log(true)
} else {
    console.log(false)
}



let word = "Zero"

if (word[word.length - 1] == "ъ") {
    console.log(word[word.length - 2])
} else {
    console.log(word[word.length - 1])
}

> daily:
let num = 55435346354
let stringNum = String(num)
console.log(parseInt(stringNum[0]))



let num = 55435346354
let stringNum = String(num)
console.log(parseInt(stringNum[stringNum.length - 1]))



let num = 55435346354
let stringNum = String(num)
console.log(parseInt(stringNum[0]) + parseInt(stringNum[stringNum.length - 1]))



let num = 55435346354
let stringNum = String(num)
console.log(parseInt(stringNum.length))



let num = 55435346354
let num2 = 55435346354
let stringNum = String(num)
let stringNum2 = String(num2)

if (parseInt(stringNum[0]) === parseInt(stringNum2[0])) {
    console.log(true)
} else {
    console.log(false)
}

> daily:
let str = "iloveniki"

if (str.length > 1) {
    console.log(str[str.length - 2])
} else {
    console.log(str)
}


let num = 10
let num2 = 5

if(num % num2 === 0) {
    console.log(true)
} else {
    console.log(false)
}

> daily:
for (let i = 0; i < 100; i++) {
    console.log(i)
}

for (let i = -100; i < 0; i++) {
    console.log(i)
}

for (let i = 100; i > 0; i--) {
    console.log(i)
}

for (let i = 1; i <= 100; i++) {
  if (i % 2 == 0) {
    console.log(i);
  }
}

for (let i = 1; i <= 100; i++) {
  if (i % 3 == 0) {
    console.log(i);
  }
}

> daily:
let sum = 0
for (let i = 0; i <= 100; i++) {
    sum = sum + i
}
console.log(sum)

let sum = 0
for (let i = 0; i <= 100; i++) {
    if (i % 2 == 0) {
        sum += i   
    }
}
console.log(sum)

let sum = 0
for (let i = 0; i <= 100; i++) {
    if (i % 2 != 0) {
        sum += i   
    }
}
console.log(sum)

let num = 4
let num2 = 5
console.log(num % num2)


> daily:
let str = "hoe stop breathing"
for (let i = str.length; i > 0; i--) {
    symbol = str[i - 1]
    console.log(symbol)
}
for (let i = 0; i < str.length; i++) {
    symbol = str[i]
    console.log(symbol)
}

> daily:
let array = [1, 2, 3, 4, 5]
let sum = 0
array.forEach(function(item) {
    sum += item * item
})
console.log(sum)\

let array = [1, 2, 3, 4, 5]
let sum = 0
array.forEach(function(item) {
    sum += Math.sqrt((item * item))
})
console.log(sum)

let array = [1, -2, 3, -4, 5, -6, 7, -8]
let sum = 0
for (let i = 0; i < array.length; i++) {
    if (array[i] > 0) {
        sum += array[i]
    }
}
console.log(sum)

let array = [1, -2, 8]
let sum = 0
for (let i = 0; i < array.length; i++) {
    if (array[i] > 0 && array[i] < 10) {
        sum += array[i]
    }
}
console.log(sum)

> daily:
let str = 'abcde'
console.log(str.split(''))

> daily:
let num = 12345
let symbols = num.toString().split('')
console.log(symbols)

> daily:
let num = 12345
let reverse = num
.toString()
.split('')
.reverse()
console.log(reverse)

> daily:
let num = 12345
let result = 0
let sum = num
.toString()
.split('')
for (let i = 0; i < sum.length; i++) {
    result = result + Number(sum[i])
}
console.log(result)

> daily:
let array = []
for (let i = 0; i <= 10; i++) {
    array.push(i)
}
console.log(array)

> daily:
let array = []
for (let i = 0; i <= 10; i++) {
    array.push(i)
}
console.log(array)

> daily:
let array = [1.456, 2.125, 3.32, 4.1, 5.34]
for (let i = 0; i < array.length; i++) {
   number = array[i]
   console.log(number.toFixed(0))
}


> daily:
let array = ['http://google.com', 'niki', 'http://bbbbb']
let newArray = array.filter(item => 
    item.startsWith("http://")
)
console.log(newArray)

> daily:
let array = ['http://google.com', 'niki', 'http://bbbbb.html']
let newArray = array.filter(item => 
    item.endsWith(".html")
)
console.log(newArray)

> daily:
let array = [1, 2, 3, 4, 5]
let newArray = array.map(item => item * 1.1)
console.log(newArray)

> daily:
let array = []

function getRandomInt(min, max) {
    return Math.round(Math.random() * (max - min) + min)
}
for (let i = 0; i <= 10; i++) {
    array.push(getRandomInt(0,100))
}
console.log(array)

> daily:
let num = 12345;
let numStr = num.toString();
for (let i = 0; i < 1; i++) {
    let newNum = numStr.split('').reverse()
    console.log(newNum);
}

> daily:
let array = [1, 2, 3, 4, 5, 6]
console.log(array.splice(0,2))
console.log(array.splice(0,2))
console.log(array.splice(0,2))

> daily:
let arr1 = [1, 2, 3]
let arr2 = [4, 5, 6]
console.log(arr1.concat(arr2))

> daily:
let str = 'g30tgerghdfhk043'
console.log(str.indexOf('0'))

> daily:
for (let i = 0; i <= 1000; i++) {
    let newI = i.toString()
    if (parseInt(newI[0]) + parseInt(newI[1]) === 5) {
        console.log(newI)
    }
}

> daily:
let array = [1, 2 ,3 ,4, 5, 6]
let newArray = array.filter(item => item > 3)
console.log(newArray)

> daily:
let array = [1, 2 ,3 ,4, 5, 6]
let polovina = array.length / 2
let sum = 0
array.splice(polovina)
array.map(item => sum += item)
console.log(sum)

> daily:
let array = [1, 2 ,3 ,4, 5, 6]
let polovina = array.length / 2
let sum = 0
for (let i = 0; i < polovina; i++) {
    sum += array[i]
}
console.log(sum)

> daily:
let array = [1, 2, 3, 4, 5, 6,-2, -5, -7]
let result = 0
for(let i = 0; i < array.length; i++) {
    if(array[i] < 0) {
        console.log(array[i])
        array.find(item => result += item)
    }
}
console.log(result)

> daily:
let array = [1, 2, 3, 4, 5, 6,-2, -5, -7]
for(let i = 0; i < array.length; i++) {
    if(array[i] > 0) {
        console.log(array[i])
    }
}

> daily:
let array = [1, 2, 3, 4, 5, 6,-2, -5, -7, 8]
for(let i = array.length - 1; i >= 0; i--) {
    if(array[i] <= 0) {
        array.splice(i, 1)
    }
}
console.log(array)

> daily:
let str = 'Ники я тебя люблю'
function pizdec(string) {
    let part1 = string.slice(0,-2)
    let part2 = string.slice(-1)
    let newString = part1 + part2
    return newString
}
console.log(pizdec(str))

> daily:
let array = [1, 2, 3, 4, 5, 6, 7]
let half = Math.floor(array.length / 2)
let firstHalf = array.slice(0, half)
let secondHalf = array.slice(half)
let sum = 0
let sum2 = 0
for (let i = 0; i < half; i++) {
    sum += firstHalf[i]
    sum2 += secondHalf[i]
}
let result = sum / sum2
console.log(result)

> daily:
let firstWord = 'NikiC'
let secondWord = 'Clouddy'
if (firstWord.endsWith(secondWord[0])) {
    console.log(secondWord[0])
} else {
    console.log('Буквы разные')
}

> daily:
let string = '12034056078'
let position = 0
let i = []
while(true) {
    let foundPosition = string.indexOf('0', position)
    if (foundPosition === -1) break
    i.push(foundPosition)
    position = foundPosition + 1
}
console.log(i[2])

> daily:
let string = '12,34,56'
let sum = 0
let two = string.split(',').forEach(item => {
    let num = parseInt(item)
    sum += num
})
console.log(sum)

> daily:
let string = '2024-6-19'
let date = string.split('-')
let obj = {
    year: date[0],
    month: date[1],
    day: date[2]
}
console.log(obj)

> daily:
let stringsAndNums = 'N1k1'
let firstNum = stringsAndNums.search(/\d/)
console.log(firstNum)

> daily:
let obj = {
    name: 'Niki',
    age: 21,
    sheIsTheBest: true
}
for (key in obj) {
    let keysArray = []
    keysArray.push(key)
    console.log(keysArray)
    let propsArray = []
    propsArray.push(obj[key])
    console.log(propsArray)
}

> daily:
let num = 123456789
let newNum = num.toString().split('')
for (let i = 0; i < newNum.length; i++) {
    if (parseInt(newNum[i]) % 2 === 0) {
        console.log(newNum[i])
    }
}

> daily:
let string = 'abcde'
let newString = ''
for (let i = 0; i < string.length; i++) {
    if (i % 2 === 0) {
        newString += string[i].toUpperCase()
    } else {
        newString += string[i]
    }
}
console.log(newString)

> daily:
let string = 'aaa bbb ccc'
let newString = string.split(' ').map(word => {
    return word[0].toUpperCase() + word.slice(1)
}).join(' ')
console.log(newString)


> daily:
let str = '023m0df0dfg0'
let array = []
for (let i = 0; i < str.length; i++) {
    if (str[i] === '0') {
        i = i + 1
        array.push(i)
    }
}
console.log(array)

> daily:
let str = 'abcdefg'
let newStr = ''
for (let i = 0; i < str.length; i++) {
    if ((i + 1) % 3 !== 0) {
        newStr += str[i]
    }
}
console.log(newStr)

> daily:
let array = [1, 2, 3, 4, 5, 6];
let sumEven = 0;
let sumOdd = 0;
for (let i = 0; i < array.length; i++) {
  if (i % 2 === 0) { // четные позиции (0, 2, 4, ...)
    sumEven += array[i];
  } else { // нечетные позиции (1, 3, 5, ...)
    sumOdd += array[i];
  }
}
let result = sumEven / sumOdd;
console.log(result);

> daily:
let str = 'young00cloudd2002'
let everyNums = /\d/g
let array = []
for (let i = 0; i < str.length; i++) {
    if (!isNaN(str[i]) && str[i] !== ' ') {
        array.push(i)
    }
}
console.log(array)

> daily:
let array = [123, 456, 789]
let newArray = []
for (let i = 0; i < array.length; i++) {
    let reversedNum = array[i]
    reversedNum = parseInt(reversedNum.toString().split('').reverse().join(''), 10)
    newArray.push(reversedNum)
}
console.log(newArray)

> daily:
let str = '1234567';
let result = '';

for (let i = str.length - 1; i >= 0; i--) {
    result = str[i] + result;
    if ((str.length - i) % 3 === 0 && i !== 0) {
        result = ' ' + result;
    }
}

console.log(result);

> daily:
let str = 'AbCdE'
let newStr = ''
for (let i = 0; i < str.length; i++) {
    if (str[i] === str[i].toUpperCase()) {
        newStr += str[i].toLowerCase()
    } else {
        newStr += str[i].toUpperCase()
    }
}
console.log(newStr)

> daily:
let array = [1, 2, 3, 4, 5, 6]
let result = []
    for (let i = 0; i < array.length; i += 2) {
        let combined = String(array[i]) + String(array[i + 1])
        result.push(Number(combined))
    }
console.log(result)

> daily:
let str = 'aaa bbb ccc eee fff'
let words = str.split(' ')
for (let i = 1; i < words.length; i += 2) {
    words[i] = words[i][0].toUpperCase() + words[i].slice(1)
}
let result = words.join(' ')
console.log(result)

> daily:
let str = 'a bc def ghij'
let newStr = str.split(' ')
for (let i = 0; i < newStr.length; i++) {
    if (newStr[i].length <= 3) {
        newStr[i] = newStr[i].toUpperCase()
    }
}
console.log(newStr.join(' '))

> daily:
let symbol = 'P'
if (symbol.toUpperCase() === symbol) {
    console.log('В верхнем')
} else {
    console.log('В нижнем')
}

> daily:
let num = 123789
let str = String(num).split('')
newNum = ''
for (let i = 0; i < str.length; i++) {
    if (parseInt(str[i]) % 2 == 0) {
        newNum = newNum + str[i]
    }
}
console.log(newNum)

> daily:
let str = 'Young Cloudd';
let uppercaseCount = 0;

for (let i = 0; i < str.length; i++) {
    if (str[i] === str[i].toUpperCase() && str[i] !== str[i].toLowerCase()) {
        uppercaseCount++;
    }
}

if (uppercaseCount >= 2) {
    console.log('в строке больше двух или две заглавные буквы');
} else {
    console.log('в строке меньше двух заглавных букв');
}

> daily:
let str = '1 22 333 4444 22 5555 1'
let newStr = str.split(' ')
let result = []
for (let i = 0; i < newStr.length; i++) {
    if (newStr[i].length <= 3) {
        result.push(newStr[i]) 
    }
}
console.log(result.join(' '))

> daily:
let arr1 = [1, 2, 3]
let arr2 = ['a', 'b', 'c']

let newArr = [...arr1]
newArr.splice(2, 0, ...arr2)

console.log(newArr)

> daily:
let num = 123456
let str = String(num).split('')
let result = 0
for(let i = 0; i < str.length; i += 2) {
    let combined = String(str[i]) + String(str[i + 1])
    result += Number(combined)
}
console.log(result)

> daily:
let array = [1, 2, 3, 4, 5]
array.reverse()
for (let i = 0; i < array.length; i++) {
    console.log(array[i])
}

> daily:
let str = 'youngcloudd2002'
let numbers = str.match(/\d+/g).join('')
    if (numbers.length > 3) {
        console.log('в строке больше трёх цифр')
    } else {
        console.log('в строке меньше трёх цифр или три')
    }

> daily:
let number = 123456789;
let evenDigit = String(number).split('').reverse().find(item => item % 2 === 0);
if (evenDigit !== undefined) {
    console.log('Первая четная цифра с конца: ' + evenDigit);
} else {
    console.log('Четных цифр нет');
}

> daily:
let str = 'abcde abcde abcde'
let words = str.split(' ')
for (let i = 0; i < words.length; i++) {
    words[i] = '!' + words[i].slice(1)
}
let result = words.join(' ')
console.log(result)

> daily:
let array = [1, 2, 3, 3, 4, 5]
let yesOrNo = false
for (let i = 0; i < array.length; i++) {
    if (array[i] === array[i + 1]) {
        yesOrNo = true
        break
    } else {
        yesOrNo = false
    }
}
console.log(yesOrNo)

> daily:
let num = 123456789
let numStr = String(num)
let result = true
for (let i = 1; i < numStr.length; i++) {
    if (numStr[i] <= numStr[i - 1]) {
        result = false
        break
    }
}
console.log(result)

> daily:
let array = [
 [2, 1, 4, 3, 5],
 [3, 5, 2, 4, 1],
 [4, 3, 1, 5, 2],
].map((item) => {
    item.sort()
    return item
})
console.log(array)

> daily:
let array = [1, '', 2, 3, '', 5]
for (let i = 0; i < array.length; i++) {
    if(array[i] === '') {
        array.splice(i, 1)
    }
}
console.log(array)

> daily:
let arr1 = [1, 2, 3];
let arr2 = [1, 2, 3, 4, 5];

for (let i = 0; i < arr2.length; i++) {
    if(arr1.length < arr2.length) {
        arr2.splice(arr1[arr1.length - 1])
    }
}
console.log(arr1)
console.log(arr2)

> daily:
for (let i = 10; i < 1000; i++) {
    let str = String(i)
    if(Number(str[str.length - 2]) % 2 == 0) {    
        console.log(i)
    }
}

> daily:
let array = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20]
for (let i = array.length - 1; i >= 4; i -= 5) {
    array.splice(i, 1)   
}
console.log(array)

> daily:
let num = 5
let str = ''
for (let i = 0; i < num; i++) {
    str += '0'
}
console.log(str)

> daily:
let str = 'aaa bbb ccc eee fff'.split(' ')
let newStr = ''
let array = str.map((item, index) => {
    if (index % 2 == 0) {
        newStr += item + ' '
    }
})
console.log(newStr.trim())

> daily:
let array = [
 [1, 2, 3],
 [4, 5, 6],
 [7, 8, 9],
]
let result = 0
array.forEach((item) => {
      for (let i = 0; i < item.length; i++)
     {
        result += item[i]
     }
})
console.log(result)

> daily:
let array = ['youngcloudd', 'YC', 'Sex']
let filteredArray = array.filter(item => item.length < 3)
console.log(filteredArray)

> daily:
let num = 1357
let str = num.toString()
let result = false
for (let i = 0; i < str.length; i++) {
    if (Number(str[i]) % 2 == 0) {
            console.log('Чётное')
            result = false
            break
    } else {
        console.log('Нечётное')
        result = true
    }
}
console.log(result)

> daily:
let str = 'abcba6'
let newStr = ''
for (let i = 0; i < str.length; i++) {
    newStr += str[i] 
}
if (str == newStr.split('').reverse().join('')) {
        console.log('Это слово читается одинаково с любой стороны.')
    } else {
        console.log('Это слово не читается одинаково с любой стороны.')
}

> daily:
let array = [
 [
  [11, 12, 13],
  [14, 15, 16],
  [17, 17, 19],
 ],
 [
  [21, 22, 23],
  [24, 25, 26],
  [27, 27, 29],
 ],
 [
  [31, 32, 33],
  [34, 35, 36],
  [37, 37, 39],
 ],
]
let result = array.flat(2).reduce((sum, num) => sum + num, 0)
console.log(result)

> daily:
for (let i = 10; i < 1000; i++) {
    let str = String(i)
    if(Number(str[0]) % 2 == 0) {    
        console.log(i)
    }
}

> daily:
let array = [1, 2, 3, 4, 5, 6].join('')
let newArray = []
for(let i = 0; i < array.length; i+=2) {
    let two = array[i] + array[i + 1]
    let twotwo = two.split('').reverse().join('')
    newArray.push(twotwo)
}
console.log(newArray.join('').split(''))

> daily:
let obj = {
 1: {
  1: 11,
  2: 12,
  3: 13,
 },
 2: {
  1: 21,
  2: 22,
  3: 23,
 },
 3: {
  1: 24,
  2: 25,
  3: 26,
 },
}
let sum = 0
for (let key in obj) {
    for (let key2 in obj[key]) {
        sum += obj[key][key2]
    }
}
console.log(sum)

> daily:
let array = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
let filteredArray = array.filter(num => num % 5 === 0)
console.log(filteredArray)

> daily:
let newArray = []
let array = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10].forEach((item, index) => {
    stringItem = item.toString()
    for (let i = 0; i < stringItem.length; i++) {
        if (stringItem[i] === '0') {
            newArray.push(item)
        }
    }
})
console.log(newArray)

> daily:
let result = ''
let array = [1, 2, 4, 5, 6, 7, 8, 9, 10, 3].forEach((item, index) => {
    stringItem = item.toString()
    for (let i = 0; i < stringItem.length; i++) {
        if (stringItem[i] === '3') {
            result = 3 есть в массиве
            break
        }
    }
})
console.log(result)

> daily:
let number = 35142
let filteredNumber = number.toString().split('')
console.log(filteredNumber.sort((a, b) => a - b))

> daily:
let str = ''
for (let i = 1; i <= 5; i++) {
    str += i
}
str = '-' + str.split('').join('-') + '-'
console.log(str)

> daily:
let obj = {
 1: {
  1: {
   1: 111,
   2: 112,
   3: 113,
  },
  2: {
   1: 121,
   2: 122,
   3: 123,
  },
 },
 2: {
  1: {
   1: 211,
   2: 212,
   3: 213,
  },
  2: {
   1: 221,
   2: 222,
   3: 223,
  },
 },
 3: {
  1: {
   1: 311,
   2: 312,
   3: 313,
  },
  2: {
   1: 321,
   2: 322,
   3: 323,
  },
 },
}
for (let key in obj) {
    for (let key2 in obj[key]) {
        for (let key3 in obj[key2]) {
            console.log(obj[key][key2][key3])
        }
    }
}

> daily:
let array = [1, 10, 100, 1000].filter(item => item.toString().length >= 3)
console.log(array)

> daily:
let result = true
let num = 12345
let numStr = num.toString()
for (let i = 0; i < numStr.length; i++) {
    if (numStr[i] <= '0') {
        result = false
        break
    }
}
console.log(result)

> daily:
let array = [123, 456, 789]
array = array.flatMap(item => item.toString().split(''))
console.log(array)

> daily:
let sum = 0
let data = [
 {
  1: 11,
  2: 12,
  3: 13,
 },
 {
  1: 21,
  2: 22,
  3: 23,
 },
 {
  1: 24,
  2: 25,
  3: 26,
 },
].forEach(item => {
    for (let key in item) {
        sum += item[key]
}
})
console.log(sum)

> daily:
let string = 'Я понимаю что между альбомами есть связь, но он застрял в 80-х, творческая деградация. Уже звучит не интересно'.split(' ').sort()
console.log(string)

> daily:
let num = 12
for(let i = 1; i < num; i++) {
    if (num % i === 0) {
        console.log(i)
    }
}

> daily:
let num = 12
let num2 = 6
let array = []
if (num > num2) {
    for(let i = 1; i < num; i++) {
       if (num % i === 0 && num2 % i === 0) {
        array.push(i)
        }
    }
} else {
        for(let i = 1; i < num2; i++) {
       if (num % i === 0 && num2 % i === 0) {
        array.push(i)
        }
    }
}
console.log(array)

> daily:
let num = 12
let array = []
for (let i = 0; i <= num; i++) {
    if (num % i === 0) {
        array.push(i)
    }
}
if (array.length === 3) {
    array.splice(0, 1)
    array.splice(array.length - 1, 1)
    console.log('У этого числа есть только один делитель, кроме него самого и единицы.')
} else {
    console.log(array)
}

> daily:
let str = '1,2,3,4,5,6,7,8,9,10'.split(',').sort((a, b) => b - a).splice(0, 1).join('')
console.log(Number(str))

> daily:
let array = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
let newArray = []
array.forEach(num => {
    newArray.push(num)
    if (num >= 0 && num <= 9) {
        newArray.push(num)
    }
})
console.log(newArray)



> daily:
let newStr = ''const vowels = ['А', 'Е', 'Ё', 'И', 'О', 'У', 'ы', 'Э', 'Ю', 'Я']
let str = 'Исследуйте все возможности нейросети Chat GPT. Чат-бот ГПТ на русском языке даст ответы на все ваши вопросы. Если Вам нужно больше общения или чат GPT нужен для работы, на нашем сайте есть 4 варианта бесплатных чата GPT:'
str.split(' ').forEach(item => {    let newWord = ''
    item.split('').forEach(letter => {        if (!vowels.includes(letter.toUpperCase())) {
            newWord += letter        }
    })    newStr += newWord + ' '
})console.log(newStr.trim())

> daily:
let newStr = ''let str = 'Исследуйте все возможности нейросети Chat GPT. Чат-бот ГПТ на русском языке даст ответы на все ваши вопросы. Если Вам нужно больше общения или чат GPT нужен для работы, на нашем сайте есть 4 варианта бесплатных чата GPT:'
str.split(' ').forEach(item => {
    let newWord = item.substring(0, item.length - 1) + item[item.length - 1].toUpperCase();    newStr += newWord + ' ';
});console.log(newStr)

> daily:
let data = [ {
  1: [1, 2, 3],  2: [1, 2, 3],
  3: [1, 2, 3], },
 {  1: [1, 2, 3],
  2: [1, 2, 3],  3: [1, 2, 3],
 }, {
  1: [1, 2, 3],  2: [1, 2, 3],
  3: [1, 2, 3], },
];let sum = 0
for (let key in data) {    for (let key2 in data[key]) {
        for (let i = 0; i < data[key][key2].length; i++) {            sum += data[key][key2][i]     
        }    }
}console.log(sum)

> daily:
let result = false
let array = [1, 2, 3, 11, 12, 13]

for(let i = 0; i < array.length; i++) {
    let num = array[i].toString();
    for (let j = 0; j < num.length; j++) {
        if (num[j] === '3') {
            result = true;
            break // Выход из внутреннего цикла, как только найдена цифра '3'
        }
    }
    if (!result) {
        break // Если ни одно число не содержит '3', выход из внешнего цикла
    }
    result = false // Сброс результата для следующего числа
}
console.log(result)

> daily:
let str = 'kebab-case'.split('-')
let newStr = ''
for (let i = 0; i < str.length; i++) {
newStr += str[i] + '_'
}
console.log(newStr.slice(0, -1)

> daily:
let str = '28464642'
for (let i = 0; i < str.length; i++) {
    if (str[i] === '2'  str[i] === '4'  str[i] === '6' || str[i] === '8') {
        result = true
    } else {
        result = false
        break
    }
}
console.log(result)

> daily:
let array = []
let str = ''
for (let i = 0; i < 5; i++) {
let newArray = []
for(let j = 1; j <= 3; j++) {
newArray.push(str =+ j.toString())
}
array.push(newArray)
}
console.log(array)

> daily:
let array = []
for (let i = 1; i < 100; i++) {
    let strI = i.toString()
    let sum = 0
    for (let j = 0; j < strI.length; j++) {
        let sum2 = ''
        sum2 = Number(strI[j])
        sum += sum2
    }
    if (sum == 13) {
        array.push(i)
    }
}
console.log(array)

> daily:
let array = []
for (let i = 0; i < 3; i++) {
    let array2 = []
    for (let j = 0; j < 3; j++) {
        array2.push(3 * i + j + 1)
    }
    array.push(array2)
}
console.log(array)

> daily:
let array = [1, 2, 3]
for (let i = array.length - 1; i >= 0; i--) {
    array.splice(i, 0, array[i])
}
console.log(array)

> daily:
let array = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
let number = 2
let newArray = array.filter(elem => elem % number == 0)
console.log(newArray)

> daily:
let num1 = 253
let num2 = 3524
let strNum1 = num1.toString().split('').sort((a, b) => a - b)
let strNum2 = num2.toString().split('').sort((a, b) => a - b)

let commonDigits  = []

for (let i = 0; i < strNum1.length; i++) {
    if (strNum2.includes(strNum1[i])) {
        commonDigits.push(parseInt(strNum1[i]));
    }
}

console.log(commonDigits)

> daily:
let num1 = 253
let num2 = 3524
let strNum1 = num1.toString().split('').sort((a, b) => a - b)
let strNum2 = num2.toString().split('').sort((a, b) => a - b)

let commonDigits = strNum1.filter(digit => strNum2.includes(digit))

console.log(commonDigits)

> daily:
let num = 748632536323
let strNum = num.toString()
findarray = strNum.split('').forEach((item, index) => {
    if (item === '3') {
        console.log(index)
    }
})
