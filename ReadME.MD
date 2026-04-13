#node affinity
 
 Required: The Pod must land in us-east-1d or us-east-1c. If your nodes are in us-east-1a, this Pod will stay "Pending."
 Preferred: It will look for a node with project=roboshop first. If it can't find one, it will try to find your node with project=amazon.