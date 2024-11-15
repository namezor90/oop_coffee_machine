# ☕ Virtuális Kávéfőző Program

Ez egy egyszerű, konzolalapú kávéfőző szimuláció, amely lehetővé teszi a felhasználók számára különböző kávéitalok "készítését", nyomon követi az erőforrásokat és kezeli a fizetéseket.

## 🌟 Funkciók

- Több különböző kávéital készítése (espresso, latte, cappuccino)
- Erőforrások kezelése (víz, tej, kávé)
- Érmekkel történő fizetés feldolgozása
- Részletes jelentések az erőforrásokról és bevételekről
- Visszajáró számítás

## 🛠️ Program Szerkezete

A program négy fő osztályból áll:

### CoffeeMaker
- Kezeli az erőforrásokat (víz, tej, kávé)
- Ellenőrzi, hogy van-e elegendő hozzávaló
- Elkészíti a kívánt italt

### MoneyMachine
- Kezeli a pénzügyeket
- Feldolgozza az érméket
- Számítja a visszajárót
- Nyilvántartja a profitot

### Menu
- Tárolja az elérhető italok listáját
- Lehetővé teszi az italok keresését
- Visszaadja az elérhető italok listáját

### MenuItem
- Az egyes italok modellje
- Tárolja az italok nevét, árát és hozzávalóit

## 💫 Használat

1. Indítsd el a programot a `main.py` futtatásával
2. Válassz az elérhető italok közül:
   - espresso (1.5$)
   - latte (2.5$)
   - cappuccino (3.0$)
3. Kövesd az utasításokat az érmék behelyezéséhez
4. A program elkészíti az italt, ha van elegendő hozzávaló és a fizetés sikeres

### Speciális parancsok
- `report`: Kilistázza az aktuális erőforrásokat és a bevételt
- `off`: Kikapcsolja a gépet

## 🔧 Erőforrások kezdeti mennyisége

- Víz: 300ml
- Tej: 200ml
- Kávé: 100g

## 💰 Elfogadott érmék

- Quarter (0.25$)
- Dime (0.10$)
- Nickle (0.05$)
- Penny (0.01$)

## 🎯 Példa használat

```
What would you like? (espresso/latte/cappuccino): latte
Please insert coins.
How many quarters?: 10
How many dimes?: 5
How many nickles?: 5
How many pennies?: 5
Here is $0.3 in change.
Here is your latte ☕️. Enjoy!
```
