#!/bin/bash

#Author: Jonathan
echo "Wait command" &
process_id=$!
wait $process_id
echo "Exited with status $?"
