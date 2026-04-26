# EvenCheck.sol
EvenCheck.sol
pragma solidity ^0.8.20;
contract EvenCheck {
    function isEven(uint x) public pure returns(bool) {
        return x % 2 == 0;
    }
}
