<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smart Expense Tracker</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Smart Expense Tracker</h1>
    </header>

    <main>
        <div class="tracker">
            <h2>Add Expense</h2>
            <input type="text" id="expenseName" placeholder="Expense Name">
            <input type="number" id="expenseAmount" placeholder="Amount">
            <button id="addExpense">Add</button>

            <h3>Expenses:</h3>
            <ul id="expenseList"></ul>

            <h3>Total: ₹<span id="total">0</span></h3>
        </div>
    </main>

    <script src="script.js"></script>
</body>
</html>
