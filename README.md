# Tema de GRUB Modificado

Este tema es una modificación del proyecto [HyperFluent-Grub-Theme](https://github.com/Coopydood/HyperFluent-GRUB-Theme/tree/main).  
Se cambió el fondo y algunos colores para uso personal.

## Cambios realizados
- Fondo personalizado

## Guía de instalación

1. Copiar la carpeta del tema a `/boot/grub/themes/`:

   Ejecutar en terminal:

   ```bash
   sudo cp -r skeleton-Grub-theme /boot/grub/themes/
   
2. Editar /etc/default/grub y agregue o modificar la línea:

    GRUB_THEME="/boot/grub/themes/skeleton-Grub-theme/theme.txt"

3. Actualizar GRUB:
 
    sudo update-grub        # En Debian/Ubuntu
    sudo grub2-mkconfig -o /boot/grub2/grub.cfg  # En Fedora
 
4. Reiniciar y disfrutar del nuevo tema.
