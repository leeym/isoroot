isoroot
=======

Create FreeBSD chroot(8) environment from ISO-IMAGES

<pre>
Usage:
	isoroot [options(s)] [command [argument(s)]]

Options:
	--verbose
	--debug

Common commands:
	--help
	--list
	--images
	--create <root> <image>
	--remove <root>
	<root> <command> [<arguments> ...]

Advanced commands:
	--dump
	--install <image>
	--deinstall <image>
	--mount <root>
	--umount <root>
	--set <root> <key1>=<value1> [<key2>=<value2> ...]
	--unset <root> <key1> [<key2> ...]

</pre>
