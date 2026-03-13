async function scanMarket(){

let asset = document.getElementById("asset").value

let response = await fetch(
"https://api.binance.com/api/v3/ticker/price?symbol="+asset
)

let data = await response.json()

let trend
let rsi
let call
let put

let random = Math.random()

if(random > 0.5){
trend = "Alta 📈"
}else{
trend = "Baixa 📉"
}

rsi = Math.floor(Math.random()*100)

if(trend == "Alta 📈"){
call = 70 + Math.floor(Math.random()*20)
put = 100 - call
}else{
put = 70 + Math.floor(Math.random()*20)
call = 100 - put
}

document.getElementById("trend").innerHTML = trend
document.getElementById("rsi").innerHTML = rsi
document.getElementById("prob").innerHTML =
"CALL "+call+"% | PUT "+put+"%"
}
