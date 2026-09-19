<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iRsaLse)" class="zxoqqmbad"/><path fill="url(#iF4vpdV)" class="zxoqqmbad"/><path fill="url(#iqkXhdS)" class="ummr5wb5z"/><g filter="url(#i19H4wd)"><path stroke="url(#iRAwDJc)" class="k2y_xo6cx"/><path stroke="url(#itmlMhc)" class="k2y_xo6cx"/></g><g filter="url(#iexVHne)"><circle fill="url(#iqdtoUc)" transform="rotate(-9.544 10.24 11.877)" class="x394jo79s"/></g><g filter="url(#iWYxlBe)"><circle fill="url(#iVcafQd)" transform="rotate(-9.544 10.24 11.878)" class="u0ewsbaiw"/></g><g filter="url(#ibGMKLX)"><circle fill="url(#iuMz2se)" transform="rotate(-9.544 19.621 10.3)" class="c66fti_tx"/><circle fill="url(#ixPWW5c)" transform="rotate(-9.544 19.621 10.3)" class="c66fti_tx"/></g><g filter="url(#iuwHOkc)"><circle transform="rotate(-9.544 19.621 10.3)" class="me931pbqn"/><circle fill="url(#iqUOP3b)" transform="rotate(-9.544 19.621 10.3)" class="hp8fkrkuv"/><circle fill="url(#iNzFmod)" transform="rotate(-9.544 19.621 10.3)" class="hp8fkrkuv"/></g><g filter="url(#iCLRElr)"><path fill="url(#iF7KP0c)" class="i1flhr9nm"/><path fill="url(#iQCjHec)" class="i1flhr9nm"/><path fill="url(#insNmve)" class="i1flhr9nm"/></g><path fill="url(#ihMENOd)" class="i1flhr9nm"/><path fill="url(#imL0GGr)" class="i1flhr9nm"/><path fill="url(#i9E4ixD)" class="i1flhr9nm"/><g filter="url(#iD7Djob)"><path fill="url(#inuDghc)" class="uhvrr0c3r"/></g><g filter="url(#iZ3ANue)"><path class="rwovh8nbt"/><path fill="url(#i4JI8mw)" class="zmss2kjet"/><path fill="url(#i5Q6j1b)" class="zmss2kjet"/><path fill="url(#iCNUsld)" class="zmss2kjet"/><path fill="url(#iWWT5Kc)" class="zmss2kjet"/></g><g filter="url(#iMF2hBd)"><path class="ifyeyyb0t"/></g><g filter="url(#itEhq6R)"><path class="e4g2pjboj"/><path fill="url(#iR388Lc)" class="zcb4dvb_t"/><path fill="url(#i3En8Pd)" class="zcb4dvb_t"/><path fill="url(#ipSvhfd)" class="zcb4dvb_t"/><path fill="url(#iJHOXMe)" class="zcb4dvb_t"/></g><path stroke="url(#iFZyIXc)" class="stq7_g_1w"/><g filter="url(#iAiobOe)"><circle fill="url(#igAOxGc)" class="q18dxshha"/></g><g filter="url(#igp1dyc)"><circle fill="url(#i1HB8tc)" class="j3arcccoa"/></g><path fill="url(#iIbdJkc)" class="l74pnkbeg"/><path fill="url(#ism95Qd)" class="mw3nyjb0v"/><g filter="url(#iS94RUd)"><path stroke="url(#i0b0uWd)" class="by9641b6h"/><path stroke="url(#iSJcI1c)" class="by9641b6h"/></g><g filter="url(#i7octqd)"><path class="h7rr8xbwz"/></g><g filter="url(#iAysoQc)"><path class="oe-g13bcz"/></g><g filter="url(#isbALPF)"><path stroke="url(#iaDbVLi)" class="terqfpzem"/></g><g filter="url(#iazEA8c)"><path stroke="url(#i0GrGhd)" class="q8ua5dbty"/></g><path class="a2ewz5bve"/><path fill="url(#ius6VZc)" class="zqzxfyfzq"/><path fill="url(#iQNUe4d)" class="zqzxfyfzq"/><path fill="url(#iMYCd4F)" class="zqzxfyfzq"/><path fill="url(#igZvGDc)" class="zqzxfyfzq"/><path fill="url(#iHssEOd)" class="zqzxfyfzq"/><path fill="url(#itMepcc)" class="zqzxfyfzq"/><path fill="url(#idCD1vH)" class="zqzxfyfzq"/><g filter="url(#iqlt6id)"><path fill="url(#inCvMRc)" class="s70a_6--r"/><path fill="url(#iMqMNdu)" class="s70a_6--r"/><path fill="url(#iz19Hid)" class="s70a_6--r"/></g><path fill="url(#i6nUV6q)" class="uhuo09bel"/><g filter="url(#i2P0d0t)"><path fill="url(#iT5GPkd)" class="pw4jobb4w"/><path fill="url(#itJq9Nb)" class="pw4jobb4w"/></g><g filter="url(#ixZQtDd)"><path class="piconqw9n"/><path fill="url(#iihZXEe)" class="qxtg_kbar"/><path fill="url(#iCq9Ole)" class="qxtg_kbar"/><path fill="url(#iYDU0Jc)" class="qxtg_kbar"/><path fill="url(#iUcF0qb)" class="qxtg_kbar"/></g><path fill="url(#i7UWelZ)" class="pmmaor-cy"/><path fill="url(#iMFlkyu)" class="pmmaor-cy"/><path fill="url(#is1bnNd)" class="l6pp-zb-b"/><path fill="url(#iuo3iLi)" class="l6pp-zb-b"/><path fill="url(#iu8PSAc)" class="mrc2ij01v"/><path fill="url(#iJt44vb)" class="mrc2ij01v"/><path fill="url(#iVyHyrw)" class="mrc2ij01v"/><path fill="url(#ihvyEce)" class="pwwj4yddk"/><path fill="url(#ila3hkc)" class="m0hklob7d"/><path fill="url(#i5hfy9y)" class="rko8nnbpk"/><path fill="url(#iUQ8Pob)" class="rko8nnbpk"/><path fill="url(#ix7uwWd)" class="rko8nnbpk"/><g filter="url(#i5aqjKd)"><path stroke="url(#iVT279b)" class="tgx80-lnn"/></g><path fill="url(#iWZHcnc)" class="s6g1m3bqa"/><path fill="url(#i7JNYQb)" class="s6g1m3bqa"/><path fill="url(#iSPBjoe)" class="et21kbczi"/><g filter="url(#iDQ9d3G)"><path fill="url(#ii0l6pb)" class="nte5epk6x"/><path fill="url(#iX7DdmB)" class="nte5epk6x"/><path fill="url(#i9pDCcc)" class="nte5epk6x"/></g><path fill="url(#in7ekoe)" class="o6lrt1dyr"/><path fill="url(#iYttgbc)" class="o6lrt1dyr"/><path fill="url(#i1PG9Db)" class="o6lrt1dyr"/><path fill="url(#iSzMfXd)" class="o6lrt1dyr"/><path fill="url(#iy5gM6N)" class="o6lrt1dyr"/><path class="lim8ssbos"/><path fill="url(#iyD1I6c)" class="hkrkx9b4l"/><path fill="url(#iQoDdYd)" class="hkrkx9b4l"/><path class="fet_-zbab"/><path fill="url(#i6A2HTc)" class="n9ay672dy"/><path fill="url(#ipKELyb)" class="n9ay672dy"/><path fill="url(#ivW6H3J)" class="m74kej29h"/><path fill="url(#iYIxGuZ)" class="m74kej29h"/><path fill="url(#iMFd1qc)" class="m74kej29h"/><path fill="url(#iHzJJsc)" class="m74kej29h"/><path fill="url(#iJL3gFe)" class="a6zjvcblk"/><path fill="url(#iMqrkKe)" class="a6zjvcblk"/><path fill="url(#ihSfoIe)" class="a6zjvcblk"/><path fill="url(#iI0MplL)" class="a6zjvcblk"/><path fill="url(#ikCFiXd)" class="otf22y-qd"/><path fill="url(#iJlHXEd)" class="otf22y-qd"/><path fill="url(#ih9oeIe)" class="otf22y-qd"/><path fill="url(#iLPiQhc)" class="otf22y-qd"/><g filter="url(#iadbxZd)"><path stroke="url(#iL8CZTc)" class="hbf_le2de"/></g><g filter="url(#iPn35ZU)" class="mc2zb0bvp"><path class="dvv_ety0t"/></g><g filter="url(#iUjAife)" class="mc2zb0bvp"><path class="xrvk8b8jp"/></g><defs><radialGradient id="iF4vpdV" cx="0" cy="0" r="1" gradientTransform="rotate(63.107 -6.074 21.72)scale(2.97834 5.11643)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="hb881329x"/><stop offset="1" class="ma7f6291s"/></radialGradient><radialGradient id="itmlMhc" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 13.479 11.224)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="g7xtertqj"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="eovkc4nhj"/></radialGradient><radialGradient id="iqdtoUc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07077 8.571 11.877)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="ixPWW5c" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 19.993 10.035)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="iqUOP3b" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 19.58 11.122)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iNzFmod" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.714 29.007)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iF7KP0c" cx="0" cy="0" r="1" gradientTransform="rotate(165.849 8.872 7.386)scale(7.54136 15.8323)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="z-rzt8b_f"/><stop offset=".676" class="pybvwgb5y"/></radialGradient><radialGradient id="imL0GGr" cx="0" cy="0" r="1" gradientTransform="rotate(104.296 4.07 10.66)scale(8.35241 11.3379)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="ogmaocbxv"/><stop offset="1" class="mf1uyebos"/></radialGradient><radialGradient id="i4JI8mw" cx="0" cy="0" r="1" gradientTransform="matrix(.29651 -3.04772 1.1302 .10996 18.526 6.32)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="i5Q6j1b" cx="0" cy="0" r="1" gradientTransform="matrix(3.82993 -.28707 .15435 2.05932 16.615 4.858)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iCNUsld" cx="0" cy="0" r="1" gradientTransform="matrix(.2784 1.65579 -2.56436 .43116 13.496 2.609)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iWWT5Kc" cx="0" cy="0" r="1" gradientTransform="matrix(2.65766 -2.73095 4.27849 4.16367 8.268 10.401)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iJHOXMe" cx="0" cy="0" r="1" gradientTransform="matrix(.03264 .19415 -.6238 .10488 15.512 12.62)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="igAOxGc" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 15.233 -4.512)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="nf9sr9sil"/><stop offset=".876" class="jvndtwuhh"/></radialGradient><radialGradient id="i1HB8tc" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 16.928 -8.648)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="qyqcudh-i"/><stop offset=".886" class="v_jz0vies"/></radialGradient><radialGradient id="iIbdJkc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 11.307 11.588)" gradientUnits="userSpaceOnUse"><stop class="fdm2y6x_j"/><stop offset="1" class="h1ie4dmkz"/></radialGradient><radialGradient id="ism95Qd" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 15.937 10.778)" gradientUnits="userSpaceOnUse"><stop class="fdm2y6x_j"/><stop offset="1" class="h1ie4dmkz"/></radialGradient><radialGradient id="iSJcI1c" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 18.109 10.416)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="g7xtertqj"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="eovkc4nhj"/></radialGradient><radialGradient id="iMYCd4F" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 .78125 -.62684 2.50735 8.236 21.375)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="wla505bqs"/><stop offset="1" class="rvju2rlnj"/></radialGradient><radialGradient id="igZvGDc" cx="0" cy="0" r="1" gradientTransform="rotate(129.369 -1.272 11.579)scale(2.35689 2.29948)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="eb47hsvqu"/><stop offset="1" class="jqpapdb1m"/></radialGradient><radialGradient id="iHssEOd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 2.01874 -6.68469 8.598 30.435)" gradientUnits="userSpaceOnUse"><stop class="hk7wqt7lq"/><stop offset="1" class="g3kr4nmzl"/></radialGradient><radialGradient id="idCD1vH" cx="0" cy="0" r="1" gradientTransform="matrix(1.82811 2.45314 -3.10932 2.3171 8.846 21.376)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="t1ofhibdm"/><stop offset="1" class="imlvuhvwp"/></radialGradient><radialGradient id="inCvMRc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0785 6 -4.46735 -1.54757 16.937 25.216)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="iMqMNdu" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.956 10.363)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="iz19Hid" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.109 26.154)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="i6nUV6q" cx="0" cy="0" r="1" gradientTransform="matrix(-6.038 1.01561 -1.51165 -8.987 27.271 23.265)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="iT5GPkd" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.03 12.94)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="itJq9Nb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.802 25.935)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="iihZXEe" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -38.546 40.65)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="xohjverxe"/><stop offset="1" class="sghoc4brb"/></radialGradient><radialGradient id="iCq9Ole" cx="0" cy="0" r="1" gradientTransform="matrix(6.57813 0 0 1.16319 12.924 30.435)" gradientUnits="userSpaceOnUse"><stop class="hmgh32r7m"/><stop offset="1" class="ib26drc1k"/></radialGradient><radialGradient id="iUcF0qb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02913 0 0 -3.40472 19.265 29.372)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="at1_k3rsw"/><stop offset="1" class="frn5ss_le"/></radialGradient><radialGradient id="i7UWelZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.70313 -.62842 0 19.627 28.626)" gradientUnits="userSpaceOnUse"><stop offset=".431" class="hdo03nb1p"/><stop offset="1" class="b26wppbkf"/></radialGradient><radialGradient id="iuo3iLi" cx="0" cy="0" r="1" gradientTransform="rotate(168.154 12.81 14.973)scale(6.54566 1.70736)" gradientUnits="userSpaceOnUse"><stop class="s231-6bjz"/><stop offset="1" class="s6qjzwjgb"/></radialGradient><radialGradient id="iu8PSAc" cx="0" cy="0" r="1" gradientTransform="matrix(.84204 2.73001 -2.93117 .90409 6.765 20.31)" gradientUnits="userSpaceOnUse"><stop class="ol95frboa"/><stop offset="1" class="i5qbulbys"/></radialGradient><radialGradient id="iJt44vb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.906 21.282)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="py7fiqzvo"/><stop offset="1" class="rkoscyb2g"/></radialGradient><radialGradient id="iVyHyrw" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.163 20.92)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="yassptbsb"/><stop offset="1" class="g6isq_a6x"/></radialGradient><radialGradient id="ix7uwWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.01 18.91)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="iVT279b" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.312 23.451)" gradientUnits="userSpaceOnUse"><stop class="rihdlqb3v"/><stop offset="1" class="x7yh0i-6p"/></radialGradient><radialGradient id="i7JNYQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.822 18.251)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="iX7DdmB" cx="0" cy="0" r="1" gradientTransform="rotate(25.805 -35.61 34.473)scale(1.57936 1.44294)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="iYttgbc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 3.18752 -2.63101 -1.6637 9.455 18.898)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="u2k5px3jq"/><stop offset="1" class="dmm5ewwwm"/></radialGradient><radialGradient id="i1PG9Db" cx="0" cy="0" r="1" gradientTransform="rotate(117.711 -.042 11.773)scale(4.44066 1.93651)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="oh8on9brk"/><stop offset="1" class="f1r2vnb5a"/></radialGradient><radialGradient id="iSzMfXd" cx="0" cy="0" r="1" gradientTransform="matrix(-.1359 3.04807 -.73147 -.03261 7.274 18.553)" gradientUnits="userSpaceOnUse"><stop class="n0p5sxbec"/><stop offset="1" class="q4weiw-ee"/></radialGradient><radialGradient id="iy5gM6N" cx="0" cy="0" r="1" gradientTransform="matrix(.15625 1.04772 -1.07633 .16051 9.01 21.076)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="z6zfulbza"/><stop offset="1" class="v3ok2mbfm"/></radialGradient><radialGradient id="iyD1I6c" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -.93275 3.89243 .13041 12.72 17.96)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="tv0y_es3w"/><stop offset="1" class="b84ow2m2e"/></radialGradient><radialGradient id="iQoDdYd" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 5.216 10.034)scale(.78612 .35637)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="jj_i0ybwk"/></radialGradient><radialGradient id="i6A2HTc" cx="0" cy="0" r="1" gradientTransform="rotate(-80.715 17.471 2.502)scale(.83681 3.75171)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="y-w2tsblc"/><stop offset="1" class="xdt63zb6q"/></radialGradient><radialGradient id="ipKELyb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .41406 -.20022 -.51377 13.815 17.957)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="c6e6dvbgn"/><stop offset="1" class="ph2kohtod"/></radialGradient><radialGradient id="ivW6H3J" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.51562 -5.32458 -2.85442 11.143 19.209)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="b-w3yacim"/><stop offset="1" class="f9l-1bcqi"/></radialGradient><radialGradient id="iYIxGuZ" cx="0" cy="0" r="1" gradientTransform="matrix(2.29688 1.78687 -.45885 .58982 11.518 19.48)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="u9db7sbld"/><stop offset="1" class="cbv0v1bug"/></radialGradient><radialGradient id="iMFd1qc" cx="0" cy="0" r="1" gradientTransform="rotate(136.002 2.34 12.048)scale(.96996 1.97716)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="e9ied_q8k"/><stop offset="1" class="r3idh6bhh"/></radialGradient><radialGradient id="iHzJJsc" cx="0" cy="0" r="1" gradientTransform="matrix(.48047 -.3496 .60677 .83392 8.94 19.287)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="urjmhobql"/><stop offset="1" class="lrbywkbvr"/></radialGradient><radialGradient id="iJL3gFe" cx="0" cy="0" r="1" gradientTransform="matrix(1.09945 -1.69165 1.88005 1.2219 8.869 21.905)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="i6m3xbfso"/><stop offset="1" class="ulc1d0bsf"/></radialGradient><radialGradient id="iMqrkKe" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 .84935 -.34383 .46806 10.767 20.46)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="mql7c3hze"/><stop offset="1" class="m1_omrdxn"/></radialGradient><radialGradient id="ihSfoIe" cx="0" cy="0" r="1" gradientTransform="rotate(97.522 -3.849 14.676)scale(2.32995 4.84987)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="t5ovicbrp"/><stop offset=".962" class="i2e83jb8g"/></radialGradient><radialGradient id="iI0MplL" cx="0" cy="0" r="1" gradientTransform="matrix(.54646 -.48802 1.62742 1.82231 7.87 21.222)" gradientUnits="userSpaceOnUse"><stop class="wdwsowbvt"/><stop offset="1" class="iy8y9zu4h"/></radialGradient><radialGradient id="iJlHXEd" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 .867 16.016)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="ih9oeIe" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .748 16.491)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iLPiQhc" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.344 10.509)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="iL8CZTc" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.768 22.25)" gradientUnits="userSpaceOnUse"><stop class="zxch6_gap"/><stop offset="1" class="upwmevb9h"/></radialGradient><linearGradient id="iRsaLse" x1="19.224" x2="12.336" y1="19.039" y2="30.716" gradientUnits="userSpaceOnUse"><stop class="hvtvasx8l"/><stop offset="1" class="sdatcx1hi"/></linearGradient><linearGradient id="iqkXhdS" x1="15.685" x2="17.093" y1="17.691" y2="18.253" gradientUnits="userSpaceOnUse"><stop offset=".177" class="y-9_teb5q"/><stop offset="1" class="u358bdlso"/></linearGradient><linearGradient id="iRAwDJc" x1="11.4" x2="13.682" y1="11.631" y2="11.786" gradientUnits="userSpaceOnUse"><stop class="d3bth9bgz"/><stop offset="1" class="pvzvrjbje"/></linearGradient><linearGradient id="iVcafQd" x1="10.24" x2="9.6" y1="12.156" y2="12.156" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iuMz2se" x1="20.708" x2="19.889" y1="9.209" y2="11.745" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iQCjHec" x1="9.676" x2="13.006" y1="13.916" y2="13.472" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="insNmve" x1="10.113" x2="11.957" y1="15.027" y2="14.649" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="ihMENOd" x1="20.468" x2="18.28" y1="13.254" y2="13.629" gradientUnits="userSpaceOnUse"><stop class="mzl_h2r6k"/><stop offset="1" class="mz-7uabeh"/><stop offset="1" class="nu9tlkpfz"/></linearGradient><linearGradient id="i9E4ixD" x1="10.655" x2="11.905" y1="14.629" y2="14.223" gradientUnits="userSpaceOnUse"><stop class="uac0vhb3t"/><stop offset="1" class="gykt-7bpd"/></linearGradient><linearGradient id="inuDghc" x1="14.687" x2="21.515" y1="8.129" y2="4.394" gradientUnits="userSpaceOnUse"><stop class="mla4tgzzc"/><stop offset="1" class="ms07w1btv"/></linearGradient><linearGradient id="iR388Lc" x1="14.244" x2="15.169" y1="12.268" y2="12.113" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="i3En8Pd" x1="16.075" x2="15.061" y1="12.287" y2="12.443" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="ipSvhfd" x1="15.464" x2="15.37" y1="13.143" y2="12.578" gradientUnits="userSpaceOnUse"><stop class="jc7_i91hg"/><stop offset="1" class="bn7g6cc3v"/></linearGradient><linearGradient id="iFZyIXc" x1="14.518" x2="14.833" y1="14.939" y2="14.189" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="i0b0uWd" x1="16.031" x2="18.312" y1="10.823" y2="10.979" gradientUnits="userSpaceOnUse"><stop class="d3bth9bgz"/><stop offset="1" class="pvzvrjbje"/></linearGradient><linearGradient id="iaDbVLi" x1="17.394" x2="16.837" y1="7.869" y2="7.092" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="i0GrGhd" x1="12.142" x2="10.887" y1="8.622" y2="8.327" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ius6VZc" x1="9.109" x2="3.64" y1="26.747" y2="25.279" gradientUnits="userSpaceOnUse"><stop class="ena81bblx"/><stop offset="1" class="hjax-mb0n"/></linearGradient><linearGradient id="iQNUe4d" x1="3.515" x2="5.486" y1="26.372" y2="26.938" gradientUnits="userSpaceOnUse"><stop class="eyx6dtigb"/><stop offset="1" class="uels9hbwx"/></linearGradient><linearGradient id="itMepcc" x1="9.229" x2="8.837" y1="28.765" y2="28.64" gradientUnits="userSpaceOnUse"><stop class="hkmz0xbqe"/><stop offset="1" class="s03vqlghs"/></linearGradient><linearGradient id="iYDU0Jc" x1="18.227" x2="17.566" y1="26.71" y2="27.605" gradientUnits="userSpaceOnUse"><stop offset=".175" class="pbsapybex"/><stop offset="1" class="vvwmaab9t"/></linearGradient><linearGradient id="iMFlkyu" x1="19.523" x2="19.437" y1="26.998" y2="27.506" gradientUnits="userSpaceOnUse"><stop class="byw39cbfh"/><stop offset="1" class="uvoxmwj8v"/></linearGradient><linearGradient id="is1bnNd" x1="26.546" x2="26.984" y1="27.216" y2="30.935" gradientUnits="userSpaceOnUse"><stop class="gf4r80b0w"/><stop offset="1" class="jd4hd8b4a"/></linearGradient><linearGradient id="ihvyEce" x1="11.144" x2="10.997" y1="22.507" y2="19.864" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="ila3hkc" x1="12.351" x2="11.964" y1="20.698" y2="18.716" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="i5hfy9y" x1="16.078" x2="15.296" y1="18.498" y2="21.484" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="iUQ8Pob" x1="15.205" x2="15.428" y1="21.704" y2="20.813" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="iWZHcnc" x1="14.952" x2="13.827" y1="17.733" y2="22.061" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="iSPBjoe" x1="15.265" x2="14.156" y1="18.108" y2="17.748" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="ii0l6pb" x1="14.453" x2="13.223" y1="17.623" y2="22.373" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="i9pDCcc" x1="12.549" x2="12.768" y1="21.439" y2="20.36" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="in7ekoe" x1="8.421" x2="8.964" y1="17.123" y2="21.623" gradientUnits="userSpaceOnUse"><stop class="fa6dpirps"/><stop offset="1" class="jplxqgtye"/></linearGradient><linearGradient id="ikCFiXd" x1="16.521" x2="15.937" y1="18.997" y2="21.497" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><filter id="i19H4wd" width="2.323" height=".964" x="11.305" y="11.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation=".05"/></filter><filter id="iexVHne" width="3.539" height="3.339" x="8.571" y="10.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3546"/></filter><filter id="iWYxlBe" width="2.99" height="2.99" x="8.745" y="10.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation=".25"/></filter><filter id="ibGMKLX" width="3.589" height="3.589" x="17.952" y="8.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3546"/></filter><filter id="iuwHOkc" width="2.99" height="2.99" x="18.126" y="8.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation=".25"/></filter><filter id="iCLRElr" width="10.787" height="12.691" x="9.481" y="5.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3546"/></filter><filter id="iD7Djob" width="8.306" height="7.494" x="12.478" y="2.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation="1"/></filter><filter id="iZ3ANue" width="12.474" height="9.429" x="7.943" y="1.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3546"/></filter><filter id="iMF2hBd" width="3.251" height="4.24" x="13.349" y="9.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation=".375"/></filter><filter id="itEhq6R" width="2.365" height="3.223" x="14.001" y="10.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation=".125"/></filter><filter id="iAiobOe" width="3.987" height="3.987" x="10.4" y="8.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation=".325"/></filter><filter id="igp1dyc" width="3.987" height="3.987" x="14.989" y="7.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation=".325"/></filter><filter id="iS94RUd" width="2.323" height=".964" x="15.935" y="10.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation=".05"/></filter><filter id="i7octqd" width="3.019" height="1.687" x="15.635" y="7.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3546"/></filter><filter id="iAysoQc" width="2.894" height="2.113" x="10.621" y="7.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3546"/></filter><filter id="isbALPF" width="3.14" height="1.479" x="15.46" y="7.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation=".25"/></filter><filter id="iazEA8c" width="3.075" height="2.016" x="10.399" y="7.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation=".25"/></filter><filter id="iqlt6id" width="11.192" height="8.359" x="11.466" y="22.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3546"/></filter><filter id="i2P0d0t" width="7.407" height="8.444" x="19.048" y="19.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3546"/></filter><filter id="ixZQtDd" width="8.208" height="4.667" x="12.416" y="25.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.678431 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3546"/></filter><filter id="i5aqjKd" width="3.456" height="1.701" x="7.381" y="22.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation=".1"/></filter><filter id="iDQ9d3G" width="4.309" height="4.662" x="11.043" y="16.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3546"/></filter><filter id="iadbxZd" width="3.647" height="2.753" x="6.263" y="19.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation=".05"/></filter><filter id="iPn35ZU" width="2.634" height="2.141" x="16.374" y="26.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation=".125"/></filter><filter id="iUjAife" width="4.536" height="1" x="12.746" y="29.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3546" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-feeding-baby-light" /></template>
<style>
.a2ewz5bve {
  fill: var(--svg-color--58b2ec, #58B2EC);
  d: path("m29.145 25.775l-4.94-6.05l-3.16 8.57z");
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.a6zjvcblk {
  d: path("M8.857 21.365c-.315.22-.723.211-.906-.11c-.392-.947.72-1.579 1.5-1.597c1.167-.027 1.75.629 1.937 1.121s.227 1.477-.672 1.54c-.804.055-.847-.5-.98-.743c-.133-.242-.594-.41-.88-.21");
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.at1_k3rsw {
  stop-color: var(--svg-color--cf9085, #CF9085);
}

.b-w3yacim {
  stop-color: var(--svg-color--f1c0a9, #F1C0A9);
}

.b26wppbkf {
  stop-color: var(--svg-color--286ad9, #286AD9);
}

.b84ow2m2e {
  stop-color: var(--svg-color--d8ab96, #D8AB96);
  stop-opacity: 0;
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bn7g6cc3v {
  stop-color: var(--svg-color--e5b39d, #E5B39D);
  stop-opacity: 0;
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.by9641b6h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.085 10.815c.151.14.548.37 1.063.273c.562-.106.888-.458.96-.64");
}

.byw39cbfh {
  stop-color: var(--svg-color--0e6996, #0E6996);
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c66fti_tx {
  cx: 19.621px;
  cy: 10.3px;
  r: 1.669px;
}

.c6e6dvbgn {
  stop-color: var(--svg-color--fdd3be, #FDD3BE);
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.cbv0v1bug {
  stop-color: var(--svg-color--eab8a3, #EAB8A3);
  stop-opacity: 0;
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.d3bth9bgz {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dmm5ewwwm {
  stop-color: var(--svg-color--bf7875, #BF7875);
}

.dvv_ety0t {
  stroke: var(--svg-color--efc6b6, #EFC6B6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m16.874 26.726l1.634 1.14");
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e4g2pjboj {
  fill: var(--svg-color--f1bea3, #F1BEA3);
  d: path("m14.498 10.873l-.242 1.764a.54.54 0 0 0 .63.603l.774-.13a.54.54 0 0 0 .398-.776l-.806-1.588c-.175-.352-.699-.264-.754.127");
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.e9ied_q8k {
  stop-color: var(--svg-color--d9a38b, #D9A38B);
}

.eb47hsvqu {
  stop-color: var(--svg-color--2170a2, #2170A2);
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.ena81bblx {
  stop-color: var(--svg-color--2f71f9, #2F71F9);
}

.eovkc4nhj {
  stop-color: var(--svg-color--303030, #303030);
  stop-opacity: 0;
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.et21kbczi {
  d: path("M14.826 17.533L12.19 16.8l-1.073 3.895l2.6.734c.408.11.755-.065.85-.394l.78-2.703c.123-.391-.164-.694-.521-.798");
}

.eyx6dtigb {
  stop-color: var(--svg-color--4e83c4, #4E83C4);
}

.f1r2vnb5a {
  stop-color: var(--svg-color--dead92, #DEAD92);
  stop-opacity: 0;
}

.f9l-1bcqi {
  stop-color: var(--svg-color--daa695, #DAA695);
}

.fa6dpirps {
  stop-color: var(--svg-color--dbaa8f, #DBAA8F);
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fdm2y6x_j {
  stop-color: var(--svg-color--070509, #070509);
}

.fet_-zbab {
  fill: var(--svg-color--eabaa2, #EABAA2);
  d: path("M9.67 17.818c.243.25.33.526.343.633l.485.469l2.34.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.774-1.079c-1.09-.132-2.42-.305-2.779-.346c-.613-.07-.945.297-.64.61");
}

.fo4qq4q_b {
  stop-color: var(--svg-color--289d47, #289D47);
}

.frn5ss_le {
  stop-color: var(--svg-color--cf9085, #CF9085);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fu3c0cblo {
  stop-color: var(--svg-color--f38820, #F38820);
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g3kr4nmzl {
  stop-color: var(--svg-color--317ff4, #317FF4);
  stop-opacity: 0;
}

.g6isq_a6x {
  stop-color: var(--svg-color--1a3f75, #1A3F75);
  stop-opacity: 0;
}

.g7xtertqj {
  stop-color: var(--svg-color--303030, #303030);
}

.gf4r80b0w {
  stop-color: var(--svg-color--27a9f1, #27A9F1);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.gykt-7bpd {
  stop-color: var(--svg-color--e3ab96, #E3AB96);
  stop-opacity: 0;
}

.h1ie4dmkz {
  stop-color: var(--svg-color--131212, #131212);
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.h7rr8xbwz {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M18.14 7.791h-.002l-.002-.002l-.005-.003l-.014-.007a1.4 1.4 0 0 0-.17-.08a2.6 2.6 0 0 0-.45-.139A2.83 2.83 0 0 0 16 7.652a.534.534 0 1 0 .339 1.012a1.77 1.77 0 0 1 .936-.06a1.5 1.5 0 0 1 .332.112a.534.534 0 0 0 .532-.925");
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.hb881329x {
  stop-color: var(--svg-color--1c8ec9, #1C8EC9);
}

.hbf_le2de {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.593 20.186c-.206.432-.319 1.448.875 2.054c1.194.607 1.992.149 2.242-.156");
}

.hdo03nb1p {
  stop-color: var(--svg-color--2176c7, #2176C7);
}

.hjax-mb0n {
  stop-color: var(--svg-color--246bda, #246BDA);
}

.hk7wqt7lq {
  stop-color: var(--svg-color--5289f2, #5289F2);
}

.hkmz0xbqe {
  stop-color: var(--svg-color--1e7eee, #1E7EEE);
}

.hkrkx9b4l {
  d: path("M10.1 16.897c.355.125.48.33.515.453l.445.39l2.292.362a.92.92 0 0 0 1.061-.871a.913.913 0 0 0-.922-.95c-1.174.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.hmgh32r7m {
  stop-color: var(--svg-color--cc9098, #CC9098);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hp8fkrkuv {
  cx: 19.621px;
  cy: 10.3px;
  r: 0.995px;
}

.hvtvasx8l {
  stop-color: var(--svg-color--2ba6ec, #2BA6EC);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i1flhr9nm {
  d: path("M9.496 9.923c-.044-.263.008-.596.193-.79l.132-.184c.23-.255.282-.588.23-.904l-.142-.841a.52.52 0 0 1 .334-.597c.609-.265 1.887-.75 3.79-1.07c1.905-.32 3.272-.28 3.933-.229c.22.017.467.192.511.455l.142.842c.053.315.265.604.512.779c.553.263.554.46.582.875c.035.535.133 1.438.133 1.438l.018-.003l.394 3.947c.135 1.772-1.032 3.219-2.668 3.494l-3.166.532c-1.688.284-3.211-.71-3.663-2.429c-.439-1.768-.801-3.554-1.265-5.315");
}

.i2e83jb8g {
  stop-color: var(--svg-color--c28485, #C28485);
}

.i5qbulbys {
  stop-color: var(--svg-color--1f70cf, #1F70CF);
}

.i6m3xbfso {
  stop-color: var(--svg-color--c58788, #C58788);
}

.ib26drc1k {
  stop-color: var(--svg-color--cc9098, #CC9098);
  stop-opacity: 0;
}

.ifyeyyb0t {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m14.63 11.016l-.527 1.812c-.042.361.256.665.597.608l.727-.122c.341-.057.523-.448.366-.77l-.773-1.594c-.168-.353-.342-.324-.39.066");
}

.imlvuhvwp {
  stop-color: var(--svg-color--2e71f4, #2E71F4);
  stop-opacity: 0;
}

.iy8y9zu4h {
  stop-color: var(--svg-color--c68882, #C68882);
  stop-opacity: 0;
}

.j3arcccoa {
  cx: 16.983px;
  cy: 9.957px;
  r: 1.344px;
}

.jc7_i91hg {
  stop-color: var(--svg-color--e5b39d, #E5B39D);
}

.jd4hd8b4a {
  stop-color: var(--svg-color--297eff, #297EFF);
}

.jj_i0ybwk {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
  stop-opacity: 0;
}

.jplxqgtye {
  stop-color: var(--svg-color--c98e84, #C98E84);
}

.jqpapdb1m {
  stop-color: var(--svg-color--2374a5, #2374A5);
  stop-opacity: 0;
}

.jvndtwuhh {
  stop-color: var(--svg-color--d29d8a, #D29D8A);
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.k2y_xo6cx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.455 11.622c.151.14.548.37 1.063.274c.562-.107.888-.459.96-.641");
}

.kloinabmx {
  stop-color: var(--svg-color--c26f5c, #C26F5C);
  stop-opacity: 0;
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.l6pp-zb-b {
  d: path("M20.615 26.212c1.598-.23 4.567-.808 6.543-1.27c1.522-.262 2.64 1.204 2.64 2.782c0 1.371-1.022 2.236-1.746 2.618a.86.86 0 0 1-.403.093h-8.014V27.35c0-.797.281-1 .98-1.137");
}

.l74pnkbeg {
  d: path("M11.413 11.354c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34c-.19-.14-.11-.43.11-.47");
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.lim8ssbos {
  fill: var(--svg-color--eabba1, #EABBA1);
  d: path("M10.1 16.897c.355.125.48.33.515.453l.445.39l2.292.362a.92.92 0 0 0 1.061-.871a.913.913 0 0 0-.922-.95c-1.174.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.lrbywkbvr {
  stop-color: var(--svg-color--e0ae97, #E0AE97);
  stop-opacity: 0;
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m0hklob7d {
  d: path("M10.565 19.004c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.m1_omrdxn {
  stop-color: var(--svg-color--fccfbe, #FCCFBE);
  stop-opacity: 0;
}

.m74kej29h {
  d: path("M8.521 18.916a.28.28 0 0 1 .133-.27c.981-.69 2.005-.305 2.383 0c.304.236 1 .79 1.363 1.082c.446.36.372.961.043 1.317c-.276.297-.751.24-.93.148l-2.097-1.312c-.055-.313-.235-.563-.48-.637c-.247-.074-.403-.133-.415-.328");
}

.ma7f6291s {
  stop-color: var(--svg-color--1c8ec9, #1C8EC9);
  stop-opacity: 0;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.me931pbqn {
  cx: 19.621px;
  cy: 10.3px;
  r: 0.995px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.mf1uyebos {
  stop-color: var(--svg-color--a3818a, #A3818A);
}

.mla4tgzzc {
  stop-color: var(--svg-color--ffe3c8, #FFE3C8);
}

.mql7c3hze {
  stop-color: var(--svg-color--fccfbe, #FCCFBE);
}

.mrc2ij01v {
  d: path("M10.214 22.122c-.284.88-1.448 1.292-2.6.92c-1.152-.37-1.793-1.177-1.573-2.265c.18-.888.883-1.75 2.738-1.24c1.153.372 1.719 1.705 1.435 2.585");
}

.ms07w1btv {
  stop-color: var(--svg-color--ffe3c8, #FFE3C8);
  stop-opacity: 0;
}

.mw3nyjb0v {
  d: path("M16.043 10.544c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34a.263.263 0 0 1 .11-.47");
}

.mz-7uabeh {
  stop-color: var(--svg-color--ffddbf, #FFDDBF);
  stop-opacity: 0;
}

.mzl_h2r6k {
  stop-color: var(--svg-color--ffddbf, #FFDDBF);
}

.n0p5sxbec {
  stop-color: var(--svg-color--dda891, #DDA891);
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.n9ay672dy {
  d: path("M9.67 17.818c.243.25.33.526.343.633l.485.469l2.34.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.774-1.079c-1.09-.132-2.42-.305-2.779-.346c-.613-.07-.945.297-.64.61");
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.nf9sr9sil {
  stop-color: var(--svg-color--ddaa96, #DDAA96);
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.nte5epk6x {
  d: path("m12.167 16.9l2.635.735c.357.104.645.406.521.797l-.779 2.704c-.095.329-.442.504-.851.393l-2.6-.734z");
}

.nu9tlkpfz {
  stop-color: var(--svg-color--ffd2b7, #FFD2B7);
  stop-opacity: 0;
}

.o6lrt1dyr {
  d: path("M8.13 17.678c1.032-1.086 1.92-1.37 2.32-1.375l.798.867l-.93 3.515c-.18.316-.564.997-.695 1.153c-.164.195-.735.63-1.766.238c-.888-.337-1.15-.898-1.176-1.148c.234-1.168.65-2.358 1.45-3.25");
}

.oe-g13bcz {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m10.75 9.034l.002-.002l.001-.001l.004-.005l.01-.011l.031-.033q.038-.04.104-.099a2.6 2.6 0 0 1 .38-.277c.33-.2.816-.398 1.445-.404a.534.534 0 1 1 .01 1.067c-.402.004-.704.13-.904.25a1.5 1.5 0 0 0-.277.215a.534.534 0 0 1-.806-.7");
}

.ogmaocbxv {
  stop-color: var(--svg-color--d3a99b, #D3A99B);
  stop-opacity: 0;
}

.oh8on9brk {
  stop-color: var(--svg-color--eebfa5, #EEBFA5);
}

.ol95frboa {
  stop-color: var(--svg-color--277aa9, #277AA9);
}

.otf22y-qd {
  d: path("m15.454 21.2l.227.069a.5.5 0 0 0 .492-.12l.363-.353a.13.13 0 0 1 .128-.033l.315.084a.484.484 0 0 0 .253-.936l-.304-.082a.13.13 0 0 1-.097-.109l-.069-.44a.5.5 0 0 0-.36-.404l-.26-.071z");
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.pbsapybex {
  stop-color: var(--svg-color--e4c0a9, #E4C0A9);
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.ph2kohtod {
  stop-color: var(--svg-color--ebbba3, #EBBBA3);
  stop-opacity: 0;
}

.piconqw9n {
  fill: var(--svg-color--e1b0a4, #E1B0A4);
  d: path("M17.18 26.117a.937.937 0 0 0-1.12 1.498l.93.802a.1.1 0 0 1-.062.175l-3.644.072a.886.886 0 0 0 .018 1.771h6.06v-1l1.062-1.227z");
}

.pmmaor-cy {
  d: path("M18.998 27.218a.15.15 0 0 1 .15-.15h.643v3.368h-.793z");
}

.pvzvrjbje {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
  stop-opacity: 0;
}

.pw4jobb4w {
  d: path("M21.575 24.374a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.pwwj4yddk {
  d: path("m11.845 21.034l-.46-.5c-.28-.3-.68-.48-1.09-.49c-.42-.01-.82.16-1.11.46l-.17.18l.53-.95c.22-.39.59-.66 1.02-.74s.88.03 1.23.3l.99.8c.33.27.38.75.12 1.09c-.21.26-.56.35-.85.24a.9.9 0 0 0-.21-.39");
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.py7fiqzvo {
  stop-color: var(--svg-color--052e6b, #052E6B);
}

.pybvwgb5y {
  stop-color: var(--svg-color--d7a893, #D7A893);
}

.q18dxshha {
  cx: 12.394px;
  cy: 10.685px;
  r: 1.344px;
}

.q4weiw-ee {
  stop-color: var(--svg-color--dda891, #DDA891);
  stop-opacity: 0;
}

.q8ua5dbty {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.024 9.367c.275-.34.928-.758 1.825-.766");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.qxtg_kbar {
  d: path("M17.18 26.117a.937.937 0 0 0-1.12 1.498l.93.802a.1.1 0 0 1-.062.175l-3.644.072a.886.886 0 0 0 .018 1.771h6.06v-1l1.062-1.227z");
}

.qyqcudh-i {
  stop-color: var(--svg-color--ffd9bb, #FFD9BB);
}

.r3idh6bhh {
  stop-color: var(--svg-color--d9a38b, #D9A38B);
  stop-opacity: 0;
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.rihdlqb3v {
  stop-color: var(--svg-color--429ce6, #429CE6);
}

.rko8nnbpk {
  d: path("m15.53 18.3l.554.16a.15.15 0 0 1 .103.186l-.784 2.73a.15.15 0 0 1-.185.102l-.555-.16z");
}

.rkoscyb2g {
  stop-color: var(--svg-color--124ea0, #124EA0);
  stop-opacity: 0;
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.rvju2rlnj {
  stop-color: var(--svg-color--1972ba, #1972BA);
  stop-opacity: 0;
}

.rwovh8nbt {
  fill: var(--svg-color--242324, #242324);
  d: path("m18.6 3.904l.459.139c.802.243 1.367 1.014 1.358 1.935l-.078 3.095c0 .318-.169.561-.475.62l-.018.004s-.097-.903-.133-1.438c-.029-.434-.125-.552-.582-.875c-.247-.175-.459-.464-.512-.78l-.141-.841c-.045-.263-.292-.438-.512-.455c-.661-.051-2.028-.092-3.932.229c-1.904.32-3.182.805-3.79 1.07a.52.52 0 0 0-.335.597l.141.841c.054.316 0 .649-.228.904l-.132.184c-.185.194-.238.527-.194.79c.15.57.345 1.402.345 1.402l-.05.007a.63.63 0 0 1-.674-.426l-1.085-2.9c-.248-.824.034-1.736.713-2.229l.387-.281c.238-.203.467-.458.696-.712l.785-1.16c.493-.623 1.313-.923 2.115-.68a2.94 2.94 0 0 0 1.64-.276c.749-.396 1.683-.337 2.415.135l.926.656c.256.227.547.34.891.445");
}

.s03vqlghs {
  stop-color: var(--svg-color--1e7eee, #1E7EEE);
  stop-opacity: 0;
}

.s231-6bjz {
  stop-color: var(--svg-color--48b6ff, #48B6FF);
}

.s6g1m3bqa {
  d: path("m11.939 16.47l3.172.884c.43.125.744.558.627.96l-.9 3.085c-.115.396-.532.607-1.024.474l-3.129-.883z");
}

.s6qjzwjgb {
  stop-color: var(--svg-color--48b6ff, #48B6FF);
  stop-opacity: 0;
}

.s70a_6--r {
  d: path("M21.835 24.455c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.sdatcx1hi {
  stop-color: var(--svg-color--1577e2, #1577E2);
}

.sghoc4brb {
  stop-color: var(--svg-color--ce9989, #CE9989);
  stop-opacity: 0;
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.stq7_g_1w {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.036 14.035c.422.137.904.176 1.397.093a2.94 2.94 0 0 0 1.29-.544a.2.2 0 0 1 .244-.001a.19.19 0 0 1 .06.234m-2.99.218l2.945-.238m-2.946.238a.2.2 0 0 0-.231.082a.19.19 0 0 0 .02.24m.211-.322l-.176.287m3.168-.505l-.046-.02m.046.02l-.046-.02m.046.02a1.94 1.94 0 0 1-1.458 1.126a1.94 1.94 0 0 1-1.746-.587m3.158-.56a1.9 1.9 0 0 1-1.42 1.097a1.9 1.9 0 0 1-1.702-.571m-.036.034l.036-.034m-.036.034l.036-.034");
}

.t1ofhibdm {
  stop-color: var(--svg-color--3395d2, #3395D2);
}

.t5ovicbrp {
  stop-color: var(--svg-color--c28485, #C28485);
  stop-opacity: 0;
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.terqfpzem {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.085 7.99c.411-.145 1.242-.263 1.89.086");
}

.tgx80-lnn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.78 23.467c.579.14 1.92.172 2.657-.828");
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.tv0y_es3w {
  stop-color: var(--svg-color--d8ab96, #D8AB96);
}

.tzj34xnjq {
  stop-color: var(--svg-color--ffd267, #FFD267);
}

.u0ewsbaiw {
  cx: 10.24px;
  cy: 11.878px;
  r: 0.995px;
}

.u2k5px3jq {
  stop-color: var(--svg-color--c38486, #C38486);
  stop-opacity: 0;
}

.u358bdlso {
  stop-color: var(--svg-color--c4aaa7, #C4AAA7);
}

.u9db7sbld {
  stop-color: var(--svg-color--f5c8b4, #F5C8B4);
}

.uac0vhb3t {
  stop-color: var(--svg-color--e3ab96, #E3AB96);
}

.uels9hbwx {
  stop-color: var(--svg-color--5082c1, #5082C1);
  stop-opacity: 0;
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.uhuo09bel {
  d: path("M23.695 27.565a4.3 4.3 0 1 0 0-8.6a4.3 4.3 0 0 0 0 8.6");
}

.uhvrr0c3r {
  d: path("M17.898 4.887L15.034 6.41a1.047 1.047 0 0 0 .8 1.925l2.95-.911z");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.ulc1d0bsf {
  stop-color: var(--svg-color--e9b8a1, #E9B8A1);
}

.ummr5wb5z {
  d: path("M15.685 18.965c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.upwmevb9h {
  stop-color: var(--svg-color--377dcb, #377DCB);
  stop-opacity: 0;
}

.urjmhobql {
  stop-color: var(--svg-color--e0ae97, #E0AE97);
}

.uvoxmwj8v {
  stop-color: var(--svg-color--0e6996, #0E6996);
  stop-opacity: 0;
}

.v_jz0vies {
  stop-color: var(--svg-color--ffc8ac, #FFC8AC);
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.v3ok2mbfm {
  stop-color: var(--svg-color--c07e7e, #C07E7E);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vvwmaab9t {
  stop-color: var(--svg-color--e4c0a9, #E4C0A9);
  stop-opacity: 0;
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wdwsowbvt {
  stop-color: var(--svg-color--c68882, #C68882);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wla505bqs {
  stop-color: var(--svg-color--1972ba, #1972BA);
}

.x394jo79s {
  cx: 10.24px;
  cy: 11.877px;
  r: 1.669px;
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x7yh0i-6p {
  stop-color: var(--svg-color--429ce6, #429CE6);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xdt63zb6q {
  stop-color: var(--svg-color--dba48c, #DBA48C);
  stop-opacity: 0;
}

.xohjverxe {
  stop-color: var(--svg-color--ce9989, #CE9989);
}

.xrvk8b8jp {
  stroke: var(--svg-color--eebdb1, #EEBDB1);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.246 29.531h3.536");
}

.y-9_teb5q {
  stop-color: var(--svg-color--9f808a, #9F808A);
}

.y-w2tsblc {
  stop-color: var(--svg-color--dba48c, #DBA48C);
}

.yassptbsb {
  stop-color: var(--svg-color--1a3f75, #1A3F75);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z6zfulbza {
  stop-color: var(--svg-color--c07e7e, #C07E7E);
}

.zcb4dvb_t {
  d: path("m14.498 10.873l-.242 1.764a.54.54 0 0 0 .63.603l.774-.13a.54.54 0 0 0 .398-.776l-.806-1.588c-.175-.352-.699-.264-.754.127");
}

.zmss2kjet {
  d: path("m18.6 3.904l.459.139c.802.243 1.367 1.014 1.358 1.935l-.078 3.095c0 .318-.169.561-.475.62l-.018.004s-.097-.903-.133-1.438c-.029-.434-.125-.552-.582-.875c-.247-.175-.459-.464-.512-.78l-.141-.841c-.045-.263-.292-.438-.512-.455c-.661-.051-2.028-.092-3.932.229c-1.904.32-3.182.805-3.79 1.07a.52.52 0 0 0-.335.597l.141.841c.054.316 0 .649-.228.904l-.132.184c-.185.194-.238.527-.194.79c.15.57.345 1.402.345 1.402l-.05.007a.63.63 0 0 1-.674-.426l-1.085-2.9c-.248-.824.034-1.736.713-2.229l.387-.281c.238-.203.467-.458.696-.712l.785-1.16c.493-.623 1.313-.923 2.115-.68a2.94 2.94 0 0 0 1.64-.276c.749-.396 1.683-.337 2.415.135l.926.656c.256.227.547.34.891.445");
}

.zqzxfyfzq {
  d: path("m2.201 30.435l2.93-9.156c.351-1.415 2.07-2.104 3.65-1.614s2.49 2.332 2.006 3.692l-2.216 7.078z");
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zxch6_gap {
  stop-color: var(--svg-color--377dcb, #377DCB);
}

.zxoqqmbad {
  d: path("M7.155 30.434c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

</style>
