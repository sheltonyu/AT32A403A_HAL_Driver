from building import *
import os

cwd = GetCurrentDir()
path = [os.path.join(cwd, 'inc')]
src_path = os.path.join(cwd, 'src')

CPPDEFINES = ['USE_STDPERIPH_DRIVER']

src = [
os.path.join(src_path, 'at32a403a_acc.c'),
os.path.join(src_path, 'at32a403a_adc.c'),
os.path.join(src_path, 'at32a403a_bpr.c'),
os.path.join(src_path, 'at32a403a_can.c'),
os.path.join(src_path, 'at32a403a_crc.c'),
os.path.join(src_path, 'at32a403a_crm.c'),
os.path.join(src_path, 'at32a403a_dac.c'),
os.path.join(src_path, 'at32a403a_debug.c'),
os.path.join(src_path, 'at32a403a_dma.c'),
os.path.join(src_path, 'at32a403a_emac.c'),
os.path.join(src_path, 'at32a403a_exint.c'),
os.path.join(src_path, 'at32a403a_flash.c'),
os.path.join(src_path, 'at32a403a_gpio.c'),
os.path.join(src_path, 'at32a403a_i2c.c'),
os.path.join(src_path, 'at32a403a_misc.c'),
os.path.join(src_path, 'at32a403a_pwc.c'),
os.path.join(src_path, 'at32a403a_rtc.c'),
os.path.join(src_path, 'at32a403a_sdio.c'),
os.path.join(src_path, 'at32a403a_spi.c'),
os.path.join(src_path, 'at32a403a_tmr.c'),
os.path.join(src_path, 'at32a403a_usart.c'),
os.path.join(src_path, 'at32a403a_usb.c'),
os.path.join(src_path, 'at32a403a_wdt.c'),
os.path.join(src_path, 'at32a403a_wwdt.c'),
os.path.join(src_path, 'at32a403a_xmc.c'),
]

group = DefineGroup('libraries', src, depend = ['PKG_USING_AT32A403A_HAL_DRIVER'], CPPPATH = path, CPPDEFINES = CPPDEFINES)

Return('group')
