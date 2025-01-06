// Flash Loan function with arbitrage logic
    function flashLoan(uint256 loanAmount) external {
        // Asegúrese de que el contrato tenga suficiente USDT para prestar
        require(usdtToken.balanceOf(address(this)) >= loanAmount, "No hay suficiente USDT en el contrato");

// Función Flash Loan con lógica de estrategia clonada
    function flashLoan(uint256 loanAmount) external {
        // Asegúrese de que el contrato tenga suficiente USDT para prestar
        require(usdtToken.balanceOf(address(this)) >= loanAmount, "No hay suficiente USDT en el contrato");
