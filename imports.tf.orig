##################################################################################
# IMPORTS
##################################################################################

import {
  to = module.main.aws_vpc.this[0]
  id = "vpc-0c3bb08c1ba50b11d" #VPC
}

import {
  to = module.main.aws_subnet.public[0]
  id = "subnet-07641ffa5fee29d98" #PublicSubnet1
}

import {
  to = module.main.aws_subnet.public[1]
  id = "subnet-07a215424a9af20b6" #PublicSubnet2
}

import {
  to = module.main.aws_internet_gateway.this[0]
  id = "igw-0b77b8cb8c339947d" #InternetGateway
}

import {
  to = module.main.aws_route.public_internet_gateway[0]
  id = "rtb-081c0dc2510dd056f_0.0.0.0/0" #DefaultPublicRoute
}

import {
  to = module.main.aws_route_table.public[0]
  id = "rtb-081c0dc2510dd056f" #PublicRouteTable
}

import {
  to = module.main.aws_route_table_association.public[0]
  id = "subnet-07641ffa5fee29d98/rtb-081c0dc2510dd056f" #PublicSubnet1/PublicRouteTable
}

import {
  to = module.main.aws_route_table_association.public[1]
  id = "subnet-07a215424a9af20b6/rtb-081c0dc2510dd056f" #PublicSubnet2/PublicRouteTable
}

import {
  to = aws_security_group.ingress
  id = "sg-0646ebdbad84da939" #NoIngressSecurityGroup
}
