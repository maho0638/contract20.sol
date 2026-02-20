# contract20.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

// Solidity Web3 data setter
contract Contract20 {
    uint public data;

    function setData(uint _data) public {
        data = _data;
    }
}
