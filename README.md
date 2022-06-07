To add new type edit "src/mime/packages/rustruct.xml" 
To update the database : 

    cd src/mime
    run 'update-mime-databse .'
    cp magic subclasses ../fdo_magic/builtin

then re-run cargo build as the file 'magic' is embeded in the final binaries
