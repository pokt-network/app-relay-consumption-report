# App Relay Consumption Report

A tool for understanding each POKT Protocol Application's Relay Consumption.

## How To Use
Run the `gateway-report` tool locally in your terminal and specify the starting block, the ending block for your query, and a valid RPC URL for the Pocket Network. 

The tool will output a `.csv` file to your directory that illustrates each application and its utilization of cumulative relays across the blocks specified.

Need an endpoint? Mint one: https://portal.pokt.network

## Dependencies

This tool requires two packages
	1. `sed` ( https://www.gnu.org/software/sed/ ) 
	2. `jq` ( https://jqlang.github.io/jq/ )
