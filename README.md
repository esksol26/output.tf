# output.tf
output "virtual_network_id" {
  value = azurerm_virtual_network.example.id
}
