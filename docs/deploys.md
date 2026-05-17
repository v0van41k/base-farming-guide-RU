# Деплой контрактов на Base — пошагово

Деплой — один из самых сильных сигналов для Builder Score.

## Самый простой способ: Remix (без кода)

1. Открой [remix.ethereum.org](https://remix.ethereum.org)
2. Создай новый файл `HelloBase.sol`:

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract HelloBase {
    string public greeting = "Hello from Base Builder!";
    
    function setGreeting(string memory _greeting) public {
        greeting = _greeting;
    }
}
