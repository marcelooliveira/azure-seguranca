```bash
az network vnet create --name rede-criada-por-cli  --resource-group curso_alura --address-prefix 10.0.0.0/16
```

```powershell
$vnet = @{
    Name = 'rede-criada-por-comando-powershell'
    ResourceGroupName = 'curso_alura'
    Location = 'eastus'
    AddressPrefix = '10.0.0.0/16'
}
$virtualNetwork = New-AzVirtualNetwork @vnet
```