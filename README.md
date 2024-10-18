CORPUS OF LATE MODERN ENGLISH TEXTS (CLMET)

CLMET3.1 is an improved and linguistically enhanced version of CLMET3.0.
While there are no changes to the textual base, several additions have been
made in terms of usability. Please refer to the accompanying manual for details
of the cleaning and conversion processes. 

This version of CLMET comes with a CQP version that is ready for use in
CWB -- both in CQP and CQPweb environments. Please refer to
the respective manuals for these programs, available from http://cwb.sourceforge.net/.

The txt versions can be used with other concordancing and text manipulation
software as usual. Please note the issues with tokenization; otherwise the plain files
are comparable with the plain files of CLMET3.0

FOLDER structure for this version:

corpus/
   
   clmet.vrt      # file used in cqp encoding process (not required to use corpus in CQP)
                  # but can be used to convert to CWB-3.4.x or CQPweb
   cqp/           # Data files of cqp version
      clmet/      # clmet folder to be added to cqp data library
        .info     # .info file (provide path to the .info file in registry file
        clmet     # registry file (save this to your cqp registry folder)
        data/     # compressed data for use in cqp (see CQP tutorials)
   
   txt/           # Corpus files, one-sentence-per-line, with these annotation levels:
     classed/     # with CLASS values (separated by underscore)
     plain/       # plain text, but tokenized
     pos/         # with POS values (separated by underscore)

doc/
     CLMET3_1_ComparingFreqs  # comparison of frequencies between versions
     CLMET3_1_metainfo        # metainfo for all 333 texts (included in CQP and headers)
     CLMET3_1_manual.pdf      # manual for CLMET3.1 describing annotation and conversion
