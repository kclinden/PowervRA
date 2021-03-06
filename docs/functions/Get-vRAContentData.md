# Get-vRAContentData

## SYNOPSIS
Get the raw data associated with vRA content

## SYNTAX

```
Get-vRAContentData [-Id] <String[]> [[-SecureValueFormat] <String>]
```

## DESCRIPTION
Get the raw data associated with vRA content

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```
Get-vRAContent -Name "Some Content" | Get-vRAContentData
```

### -------------------------- EXAMPLE 2 --------------------------
```
Get-vRAContent -Name "Some Content" | Get-vRAContentData | Out-File SomeContent.yml
```

## PARAMETERS

### -Id
The id of the content

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -SecureValueFormat
How secure data will be represented in the export

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 2
Default value: BLANKOUT
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

### System.String

## OUTPUTS

### System.String

## NOTES

## RELATED LINKS

