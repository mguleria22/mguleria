// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract GoldskyPin {
    mapping(address => bool) public completed;

    function complete() external {
        completed[msg.sender] = true;
    }
}
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract AlliumPin {
    mapping(address => bool) public completed;

    function complete() external {
        completed[msg.sender] = true;
    }
}
