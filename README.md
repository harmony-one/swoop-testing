# swoop-testing

This repo is intended to track the testing process of Swoop.

## Testing environments

| Domain     | Environment | Objective                    | Factory | Router | Deployed                |
| -----------| ----------- | --------------------------   | ------- | ------ | ----------------------- |
| P-OPS #1    | Testnet    | Liquidity provider testing   | 0xCaD2a40d311c8587dbbDfc8BC34391B0470c6a65 | 0x22c77c52BEa009c0C1B42b0D61bA338765a38eFB | 2020-10-24 09:50 UTC |
| P-OPS #2    | Testnet    | Repeat trade testing         | 0x95fcb04Afd86d1956e7574E52Ae2cb15450E2818 | 0x5d878C48cFF640bc3E83fB9d537B5080856c20a6 | 2020-10-24 11:30 UTC |
| Swoop demo  | Testnet    | Free testing/no restrictions | 0xC4dacF41Ba6B40bB2F280892D402C788136dCD4F | 0xbE39452A9FB4Bfa1EcfA38ac1Cd9191fBB6362e4 | 2020-10-23 20:20 UTC |

### P-OPS #1

P-OPS #1 is a testing environment dedicated for P-OPS to test liquidity provider features.

#### Prerequisites:

- No initial pools will be set up by the deployer.
- Testnet 10,000 ONE and 10,000 of each testnet token will be distributed by the deployer.

### P-OPS #2

P-OPS #2 is a testing environment dedicated for P-OPS to test repeated trading outcomes.

#### Prerequisites:

- Pool will be setup for all test token pairings by the deployer. Each pair will consist of 1,000,000 token x and 1,000,000 token y to simulate a similar pricing situation.
- 10,000 of testnet ONE and 10,000 of each testnet token will be distributed by the deployer.

### Swoop demo

Swoop demo is the general testing environment Harmony utilizes.

#### Prerequisites:

- Pool will be setup for all test token pairings by the deployer. Each pair will consist of 1,000,000 token x and 1,000,000 token y to simulate a similar pricing situation.
- 10,000 of testnet ONE and 10,000 of each testnet token will be distributed by the deployer.

## Bugs & issues

Please report any issues you run into while testing in this repository.

## Common issues/troubleshooting

If you happen to have issues loading the Swoop token list you can try to do what's detailed in the video below:
[Cache & Local storage reset](http://tools.harmony.one.s3.amazonaws.com/swoop-reset.mov)
