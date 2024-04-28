# Walk-Application


Update Database

Add-Migration -Context "WalksDbContext"

Add-Migration -Context "WalksAuthDbContext"

Update-Database -Context "WalksDbContext"

Update-Database -Context "WalksAuthDbContext"