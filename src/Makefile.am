
AM_CPPFLAGS = \
    $(COMEDI_CFLAGS) \
    $(FFTW_CFLAGS)

bin_PROGRAMS = laser_stimulation
laser_stimulation_SOURCES = main.c \
    comedi_code.c \
    timespec_functions.c \
    fftw_functions.c \
    data_file_si.c \
    main.h \
    ../config.h

laser_stimulation_LDADD = \
    $(COMEDI_LIBS) \
    $(FFTW3_LIBS)
