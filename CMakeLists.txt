cmake_minimum_required(VERSION 3.5)
project(heera-default-settings)

set(CONFIGFILES
	dock.conf
    dock_pinned.conf
    theme.conf
)

install(FILES ${CONFIGFILES} DESTINATION ~/.config/heeraos/)
install(FILES ${CONFIGFILES} DESTINATION /etc/skell/.config/heeraos/)
