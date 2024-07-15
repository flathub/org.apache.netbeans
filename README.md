# org.apache.netbeans
Flatpak for Apache NetBeans (https://netbeans.apache.org/)

## How to build Apache NetBeans

```
flatpak-builder --repo=repo flatpakbuildir org.apache.netbeans.yaml --force-clean
```

## Add Apache NetBeans repo to remote

```
flatpak remote-add --user mynetbeans repo
```

## How to install Apache NetBeans from flatpak

```
flatpak install --user mynetbeans org.apache.netbeans
```

## How to run Apache NetBeans

```
flatpak run org.apache.netbeans
```

## How to uninstall Apache NetBeans

```
flatpak uninstall --user org.apache.netbeans
```
