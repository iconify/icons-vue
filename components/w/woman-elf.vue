<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="e4tar7-ra"/><path fill="url(#iUY80Pe)" class="ei-zmixku"/><path fill="url(#iDbYoEd)" class="ei-zmixku"/><path fill="url(#iCYhEcc)" class="ei-zmixku"/><path fill="url(#i82oxbd)" class="ei-zmixku"/><path fill="url(#ixxOx8b)" class="ei-zmixku"/><path fill="url(#irDlLPc)" class="ei-zmixku"/><path fill="url(#iA95z6d)" class="ei-zmixku"/><path fill="url(#ivHOYle)" class="ei-zmixku"/><path class="auoirjbmm"/><path fill="url(#ineK6Cd)" class="x-171ccrl"/><path fill="url(#ijnexbb)" class="x-171ccrl"/><path fill="url(#iDGT1hJ)" class="x-171ccrl"/><path class="ecbjgibqi"/><path fill="url(#inZ0nhg)" class="vgwnw8h0u"/><path fill="url(#iv1Hcvb)" class="vgwnw8h0u"/><path fill="url(#iXhtQee)" class="vgwnw8h0u"/><path fill="url(#iIhOjRc)" class="i1ujs7one"/><path fill="url(#iSrLw0d)" class="i1ujs7one"/><path fill="url(#ihFs7mi)" class="i1ujs7one"/><path fill="url(#ixDw5Zd)" class="i1ujs7one"/><path fill="url(#idq1mHc)" class="i1ujs7one"/><path fill="url(#iepOgvc)" class="i1ujs7one"/><path fill="url(#igkqS7c)" class="i1ujs7one"/><g filter="url(#izggeBc)"><path class="dht7arbom"/></g><g filter="url(#i95eijc)"><path fill="url(#iNDCJ9m)" class="rk0wsibbd"/></g><g filter="url(#i3DRqmC)"><path fill="url(#iCXyOHc)" class="u_k1hctwr"/></g><path fill="url(#iSfEs8d)" class="pgd4nu3yt"/><path fill="url(#iizdQoc)" class="pgd4nu3yt"/><g filter="url(#if1UkId)"><path fill="url(#iM9gcse)" class="ldj72pb6e"/></g><g filter="url(#ihRQEac)"><path fill="url(#iQzg4we)" class="bu7es_a0d"/><path fill="url(#iNxgUoh)" class="bu7es_a0d"/></g><g filter="url(#i7jjXKd)"><path fill="url(#ixvQGHb)" class="wctf3ibkb"/><path fill="url(#iQQDPpc)" class="wctf3ibkb"/></g><path fill="url(#ii5Q8ne)" class="e_0vl3o1i"/><path fill="url(#iU7bEed)" class="e_0vl3o1i"/><g filter="url(#iM41fme)"><path fill="url(#ilEmGFd)" class="xlqlhebaa"/><path fill="url(#izzmTpc)" class="xlqlhebaa"/><path fill="url(#ige5GHc)" class="xlqlhebaa"/><path fill="url(#iJSnMNe)" class="xlqlhebaa"/><path fill="url(#ie7foAb)" class="xlqlhebaa"/><path fill="url(#ibVTnRd)" class="xlqlhebaa"/></g><g filter="url(#iJ0KBAc)"><path class="h9fd_uu9c"/><path fill="url(#ihTOScd)" class="iethn661e"/><path fill="url(#imCJWkd)" class="iethn661e"/></g><g filter="url(#iBrZdRc)"><path fill="url(#iJYyf0q)" class="w3laegbtn"/><path fill="url(#ijwftPb)" class="w3laegbtn"/><path fill="url(#i6L2Rgd)" class="w3laegbtn"/><path fill="url(#iGIfbYK)" class="w3laegbtn"/></g><path fill="url(#iM9DKAc)" class="w3laegbtn"/><path fill="url(#iK20bKb)" class="hcc4fhb5v"/><path fill="url(#itewnwe)" class="hcc4fhb5v"/><path fill="url(#i3x5hGI)" class="hcc4fhb5v"/><path fill="url(#idNHggb)" class="hcc4fhb5v"/><path fill="url(#iErRqQc)" class="hcc4fhb5v"/><g filter="url(#izIMRPd)"><path fill="url(#ispNR2b)" class="pmem73b8u"/><path fill="url(#iUcMOab)" class="pmem73b8u"/><path fill="url(#izNMB7c)" class="pmem73b8u"/><path fill="url(#iu76TLj)" class="pmem73b8u"/></g><g filter="url(#icvIUyc)"><path fill="url(#iI7pbLa)" class="ghfy1iray"/><path fill="url(#iYeBzkS)" class="ghfy1iray"/></g><path fill="url(#iayided)" class="g0xvfdbyw"/><path fill="url(#ii1Wi8d)" class="g0xvfdbyw"/><path fill="url(#i1nkGac)" class="g0xvfdbyw"/><path fill="url(#iGdWf9I)" class="g0xvfdbyw"/><path fill="url(#ihhsmPe)" class="g0xvfdbyw"/><path fill="url(#iswZV0c)" class="g0xvfdbyw"/><path fill="url(#ilTtifc)" class="qneer9b8q"/><g filter="url(#iyIpHLT)"><path class="k60t-0b2x"/></g><g filter="url(#iR8ypYd)"><path class="pt5wpmbyr"/></g><g filter="url(#iAP036M)"><path class="lnczwubdj"/></g><path class="vyz233ddk"/><path fill="url(#iyAaxuJ)" class="i9lr1p25m"/><path fill="url(#idAGM6c)" class="i9lr1p25m"/><path fill="url(#ibZBOlb)" class="i9lr1p25m"/><path stroke="url(#iAiujPc)" class="n4-d2tb8s"/><path class="buyndmbdh"/><path class="sytb8pb3p"/><path class="hoq7d6bfq"/><path fill="url(#ipA0jjb)" class="m00e_ufro"/><path class="nnydhdb8x"/><g filter="url(#iGFzuox)"><path class="vlizw1ypl"/><path fill="url(#iVaJgyd)" class="hby5gbc-p"/></g><g filter="url(#iUGg41b)"><path fill="url(#irlfuVD)" class="jxgek8btz"/></g><path class="r0rrpvpum"/><path fill="url(#iWwcOYc)" class="q2nms2n3q"/><path class="zhtqcybuc"/><g filter="url(#iRVntxc)"><path fill="url(#i0raRjd)" class="uwyi2hzqu"/></g><g filter="url(#iqk18Vb)"><ellipse transform="rotate(-27.914 13.561 9.976)" class="lu3j7bbpk"/><ellipse fill="url(#igUPrxc)" transform="rotate(-27.914 13.561 9.976)" class="npvlux_im"/></g><defs><radialGradient id="iDbYoEd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -14.3438 23.142 20.686)" gradientUnits="userSpaceOnUse"><stop class="szuqc-bjo"/><stop offset="1" class="in53vxbzi"/></radialGradient><radialGradient id="iCYhEcc" cx="0" cy="0" r="1" gradientTransform="rotate(-110.347 20.477 5.184)scale(3.59496 4.80694)" gradientUnits="userSpaceOnUse"><stop class="iy200zbbi"/><stop offset="1" class="ox6ngqb6d"/></radialGradient><radialGradient id="i82oxbd" cx="0" cy="0" r="1" gradientTransform="rotate(77.471 -3.564 20.737)scale(2.88111 5.07754)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="utz8l-hjj"/><stop offset="1" class="ssj6asr2b"/></radialGradient><radialGradient id="ixxOx8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.57813 .51562 -7.1646 -8.03319 14.554 27.46)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="im7yg7aog"/><stop offset="1" class="nz4t17rpu"/></radialGradient><radialGradient id="irDlLPc" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 .3125 -2.8125 16.87503 8.952 23.999)" gradientUnits="userSpaceOnUse"><stop class="fupnc-bzv"/><stop offset="1" class="fux90lb8s"/></radialGradient><radialGradient id="iA95z6d" cx="0" cy="0" r="1" gradientTransform="matrix(.313 0 0 13.5898 8.827 27.552)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="u7qedx64x"/><stop offset="1" class="l-im3ccrf"/></radialGradient><radialGradient id="ivHOYle" cx="0" cy="0" r="1" gradientTransform="matrix(-.50581 0 0 -8.83067 23.25 26.076)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="frtpxb2_e"/><stop offset="1" class="r_hbeqgkw"/></radialGradient><radialGradient id="ineK6Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-.59707 0 0 -12.1778 9.033 29.939)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="bu_chtytz"/><stop offset="1" class="n1msxeybk"/></radialGradient><radialGradient id="ijnexbb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69302 6.8777 -1.92029 -.4727 6.992 23.061)" gradientUnits="userSpaceOnUse"><stop class="tf7ikua9d"/><stop offset="1" class="xodttob3f"/></radialGradient><radialGradient id="inZ0nhg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 -10.40629 1.38016 -.21552 25.58 28.374)" gradientUnits="userSpaceOnUse"><stop offset=".455" class="f_vyractb"/><stop offset="1" class="av_zubbsw"/></radialGradient><radialGradient id="iXhtQee" cx="0" cy="0" r="1" gradientTransform="matrix(.49206 0 0 10.875 23.088 26.467)" gradientUnits="userSpaceOnUse"><stop class="mzy3c3d_u"/><stop offset="1" class="lpdsa84op"/></radialGradient><radialGradient id="ihFs7mi" cx="0" cy="0" r="1" gradientTransform="matrix(1.62231 -1.625 9.061 9.04602 15.736 29.78)" gradientUnits="userSpaceOnUse"><stop class="rbi44vm-m"/><stop offset="1" class="k-1w4_syq"/></radialGradient><radialGradient id="ixDw5Zd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.42 17.248 11.374)scale(18.1601 26.3733)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="pc9y3hbhd"/><stop offset="1" class="vhxxajp3a"/></radialGradient><radialGradient id="idq1mHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.53125 -8.40625 0 15.986 18.155)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="lm4m34bzz"/><stop offset="1" class="y78euyjzo"/></radialGradient><radialGradient id="iNDCJ9m" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.63279 -.8125 0 16.517 22.751)" gradientUnits="userSpaceOnUse"><stop class="o5xzi4bgi"/><stop offset="1" class="ui8xaew_b"/></radialGradient><radialGradient id="iCXyOHc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.34377 1.74998 -2.39636 -3.20947 11.765 12.967)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="h0yb7bbrn"/><stop offset="1" class="uqqizachy"/><stop offset="1" class="p0hjq828d"/></radialGradient><radialGradient id="iSfEs8d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25 .8711 -.92998 -2.40211 23.858 12.686)" gradientUnits="userSpaceOnUse"><stop class="lg7v73bam"/><stop offset=".858" class="uwic7ybdl"/></radialGradient><radialGradient id="iizdQoc" cx="0" cy="0" r="1" gradientTransform="matrix(1.82812 .51173 -1.43377 5.12206 20.562 13.046)" gradientUnits="userSpaceOnUse"><stop class="j9z2gfbkw"/><stop offset="1" class="yh6vtccym"/></radialGradient><radialGradient id="iQzg4we" cx="0" cy="0" r="1" gradientTransform="matrix(1.4697 -1.59165 3.40232 3.14166 8.664 10.211)" gradientUnits="userSpaceOnUse"><stop class="fgp762gdr"/><stop offset="1" class="e4garxz9p"/></radialGradient><radialGradient id="iNxgUoh" cx="0" cy="0" r="1" gradientTransform="rotate(71.741 -.52 9.97)scale(5.60855 3.99461)" gradientUnits="userSpaceOnUse"><stop offset=".707" class="i2gy70vof"/><stop offset="1" class="uqzcd-flf"/></radialGradient><radialGradient id="ixvQGHb" cx="0" cy="0" r="1" gradientTransform="matrix(3.42178 -4.2491 3.0025 2.4179 20.599 11.99)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="r7mg8accg"/><stop offset=".774" class="y4t-2eloy"/></radialGradient><radialGradient id="iQQDPpc" cx="0" cy="0" r="1" gradientTransform="rotate(-140.86 13.36 1.275)scale(1.81729 6.21142)" gradientUnits="userSpaceOnUse"><stop offset=".654" class="khqd-3jrz"/><stop offset="1" class="g38u58vho"/></radialGradient><radialGradient id="ii5Q8ne" cx="0" cy="0" r="1" gradientTransform="rotate(-143.844 7.216 3.795)scale(3.06704 1.99268)" gradientUnits="userSpaceOnUse"><stop class="tdmcedchx"/><stop offset="1" class="sv77bgb6j"/></radialGradient><radialGradient id="iU7bEed" cx="0" cy="0" r="1" gradientTransform="matrix(1.14395 -1.05015 3.68181 4.01068 9.353 10.762)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="ob_nqzbct"/><stop offset="1" class="ut_l7ccde"/></radialGradient><radialGradient id="ilEmGFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.50781 13.8508 0 16 21.34)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="ob9xa4oph"/><stop offset="1" class="u9vkkub5w"/></radialGradient><radialGradient id="izzmTpc" cx="0" cy="0" r="1" gradientTransform="rotate(152.259 7.559 9.702)scale(9.53325 15.1141)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="ngc6h6bst"/><stop offset="1" class="o5llqtbdv"/></radialGradient><radialGradient id="ige5GHc" cx="0" cy="0" r="1" gradientTransform="matrix(6.06254 6.31246 -7.41731 7.12364 14.453 14.217)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="s1jm76o_g"/><stop offset="1" class="a0ve6ibhs"/></radialGradient><radialGradient id="iJSnMNe" cx="0" cy="0" r="1" gradientTransform="rotate(-158.513 8.323 6.627)scale(4.24838 2.76793)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="u9m-38uic"/><stop offset="1" class="dgp6vzbgz"/></radialGradient><radialGradient id="ie7foAb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.20237 6.09373 -1.19654 -.82516 20.202 14.092)" gradientUnits="userSpaceOnUse"><stop offset=".447" class="hgv4-zm2k"/><stop offset="1" class="wpf0olbav"/></radialGradient><radialGradient id="ibVTnRd" cx="0" cy="0" r="1" gradientTransform="matrix(1.03906 -1.52344 .33915 .23132 18.398 16.702)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="wj7x2ubbg"/><stop offset="1" class="jq6-sgbpj"/></radialGradient><radialGradient id="ihTOScd" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 2.60938 -4.67763 .95233 14.609 15.577)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="rw730-4us"/><stop offset="1" class="ue1ou_b9r"/></radialGradient><radialGradient id="imCJWkd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.86275 1.28759 -4.0032 -12.00957 17.243 16.343)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="fisms_b6b"/><stop offset="1" class="ev9w4sb1n"/></radialGradient><radialGradient id="iJYyf0q" cx="0" cy="0" r="1" gradientTransform="rotate(167.196 9.611 6.204)scale(7.05032 8.72135)" gradientUnits="userSpaceOnUse"><stop class="kfwilqo7s"/><stop offset="1" class="eyv067r5m"/></radialGradient><radialGradient id="ijwftPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.78126 -1 .8108 -.63344 13.937 9.452)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="p1i4l-2xr"/><stop offset="1" class="pm20wdikx"/></radialGradient><radialGradient id="i6L2Rgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45312 1.84375 0 18.421 9.436)" gradientUnits="userSpaceOnUse"><stop class="w0-uzrbog"/><stop offset="1" class="erxqmfypp"/></radialGradient><radialGradient id="iGIfbYK" cx="0" cy="0" r="1" gradientTransform="rotate(26.954 -2.675 30.526)scale(6.34556 4.25079)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="n0nbs1_lf"/><stop offset="1" class="een_-ybfe"/></radialGradient><radialGradient id="iM9DKAc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0772 7.57444 -8.03074 -1.14209 17.077 9.092)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="cncl56oym"/><stop offset="1" class="i_u_7nb3k"/></radialGradient><radialGradient id="iK20bKb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 4.65625 -10.56138 -2.33908 19.015 3.249)" gradientUnits="userSpaceOnUse"><stop class="m_kdo_bhg"/><stop offset="1" class="bgmaoc9ef"/></radialGradient><radialGradient id="itewnwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.6875 8.71466 -.10133 15.608 8.53)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="te6-97gvd"/><stop offset="1" class="cwm4-i50i"/></radialGradient><radialGradient id="i3x5hGI" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 -1.09578 1.67303 .8111 13.733 6.686)" gradientUnits="userSpaceOnUse"><stop class="t4e3sn74w"/><stop offset="1" class="gt4worbah"/></radialGradient><radialGradient id="idNHggb" cx="0" cy="0" r="1" gradientTransform="matrix(.73438 -2.17187 4.12982 1.39642 20.827 9.873)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="w5pplabgz"/><stop offset="1" class="eh769jb3m"/></radialGradient><radialGradient id="iErRqQc" cx="0" cy="0" r="1" gradientTransform="matrix(6 3.75 -15.78004 25.24804 9.515 3.467)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="urkav0bvx"/><stop offset="1" class="obp_ujbwu"/></radialGradient><radialGradient id="ispNR2b" cx="0" cy="0" r="1" gradientTransform="rotate(48.247 -.634 14.575)scale(2.89035 5.54362)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="fqelt7o-r"/><stop offset="1" class="mwmpt8y3b"/></radialGradient><radialGradient id="iUcMOab" cx="0" cy="0" r="1" gradientTransform="rotate(140.826 5.916 4.621)scale(3.26514 1.54868)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="dkudkx8wp"/><stop offset="1" class="b1omo3bdl"/></radialGradient><radialGradient id="izNMB7c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75002 -2.875 7.34404 -4.47034 12.327 7.374)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="qah4ncc_b"/><stop offset="1" class="nzbe5xbze"/></radialGradient><radialGradient id="iu76TLj" cx="0" cy="0" r="1" gradientTransform="matrix(-.62501 -1.625 2.27596 -.87539 11.03 9.296)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="oqsc6ib4z"/><stop offset="1" class="h91_zc3nb"/></radialGradient><radialGradient id="iI7pbLa" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03113 3.06466 -5.29387 -1.78117 18.983 3.965)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="sufsclgbu"/><stop offset="1" class="f2xhcsb6x"/></radialGradient><radialGradient id="iYeBzkS" cx="0" cy="0" r="1" gradientTransform="rotate(121.752 8.27 7.041)scale(4.86941 8.82412)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="g2iiu-bfl"/><stop offset="1" class="t_wwcbcrg"/></radialGradient><radialGradient id="iGdWf9I" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09375 0 0 -.60938 21.768 5.499)" gradientUnits="userSpaceOnUse"><stop class="ekarirbxr"/><stop offset="1" class="n81djoa0z"/></radialGradient><radialGradient id="ihhsmPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .54688 -8.71875 0 11.174 4.967)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="b4qr-wvfv"/><stop offset="1" class="yyik5z8lx"/></radialGradient><radialGradient id="iswZV0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92969 -.45312 0 15.229 5.186)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="h6i96qjvc"/><stop offset="1" class="d31bklhyx"/></radialGradient><radialGradient id="ilTtifc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.90625 2.05457 0 15.979 6.764)" gradientUnits="userSpaceOnUse"><stop class="rkzp1hbvm"/><stop offset="1" class="j5zu11bke"/></radialGradient><radialGradient id="iyAaxuJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.65625 -4.11719 1.50689 -.24019 17.155 12.374)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="di1h-reoj"/><stop offset="1" class="bcmqo-b2d"/></radialGradient><radialGradient id="idAGM6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6545 2.30377 0 16 12.692)" gradientUnits="userSpaceOnUse"><stop class="h3rdn1bsz"/><stop offset="1" class="uvs4gu6ep"/></radialGradient><radialGradient id="iAiujPc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.417 19.61 -5.633)scale(.34815 1.6378)" gradientUnits="userSpaceOnUse"><stop offset=".062" class="c6fuokb_j"/><stop offset="1" class="uexiu3oxm"/></radialGradient><radialGradient id="ipA0jjb" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 6.735 9.596)scale(1.10543 1.21398)" gradientUnits="userSpaceOnUse"><stop class="sne73nbas"/><stop offset="1" class="zw17tcbyg"/></radialGradient><radialGradient id="iVaJgyd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.471 .678)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWwcOYc" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 4.553 8.527)scale(1.10548 1.21404)" gradientUnits="userSpaceOnUse"><stop class="sne73nbas"/><stop offset="1" class="zw17tcbyg"/></radialGradient><radialGradient id="igUPrxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.546 10.292)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="izggeBc" width="2.581" height="5.008" x="14.415" y="20.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1361" stdDeviation=".25"/></filter><filter id="i95eijc" width="1.681" height="4.077" x="15.197" y="21.244" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.843137 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1361"/></filter><filter id="i3DRqmC" width="6.499" height="6.992" x="8.438" y="10.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.545098 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1361"/></filter><filter id="if1UkId" width="4.108" height="5.161" x="20.376" y="7.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.721569 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1361"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.607843 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1361" result="effect2_innerShadow_4002_1361"/></filter><filter id="ihRQEac" width="3.958" height="5.111" x="7.666" y="7.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.576471 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1361"/></filter><filter id="i7jjXKd" width="3.174" height="3.27" x="20.499" y="8.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.796078 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1361"/></filter><filter id="iM41fme" width="13.191" height="7.279" x="9.404" y="14.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.243137 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1361"/></filter><filter id="iJ0KBAc" width="6.278" height="4.65" x="12.723" y="15.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.490196 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1361"/></filter><filter id="iBrZdRc" width="10.85" height="12.138" x="10.825" y="4.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.611765 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1361"/></filter><filter id="izIMRPd" width="4.148" height="5.475" x="9.651" y="3.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1361" stdDeviation=".05"/></filter><filter id="icvIUyc" width="9.815" height="5.825" x="12.74" y="2.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1361" stdDeviation=".1"/></filter><filter id="iyIpHLT" width="2.288" height="1.093" x="17.531" y="7.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.384314 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1361"/></filter><filter id="iR8ypYd" width="2.288" height="1.093" x="12.21" y="7.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.356863 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1361"/></filter><filter id="iAP036M" width="2.687" height="3.9" x="14.354" y="9.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1361" stdDeviation=".25"/></filter><filter id="iGFzuox" width=".787" height=".696" x="17.463" y="9.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1361" stdDeviation=".05"/></filter><filter id="iUGg41b" width=".891" height=".913" x="18.303" y="9.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1361" stdDeviation=".1"/></filter><filter id="iRVntxc" width=".986" height="1.04" x="13.86" y="9.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1361" stdDeviation=".1"/></filter><filter id="iqk18Vb" width=".913" height=".705" x="13.105" y="9.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1361" stdDeviation=".05"/></filter><linearGradient id="iUY80Pe" x1="15.049" x2="15.049" y1="29.939" y2="20.53" gradientUnits="userSpaceOnUse"><stop class="ifj7fvbjw"/><stop offset="1" class="wz09qdb4r"/></linearGradient><linearGradient id="iDGT1hJ" x1="8.912" x2="8.912" y1="29.939" y2="26.655" gradientUnits="userSpaceOnUse"><stop class="trl24wm4t"/><stop offset="1" class="xg491tydm"/></linearGradient><linearGradient id="iv1Hcvb" x1="24.142" x2="27.327" y1="29.311" y2="21.436" gradientUnits="userSpaceOnUse"><stop offset=".116" class="bdhnfsb4c"/><stop offset=".679" class="ya66usbax"/></linearGradient><linearGradient id="iIhOjRc" x1="12.518" x2="22.705" y1="21.28" y2="30.936" gradientUnits="userSpaceOnUse"><stop class="e8j2tsbtw"/><stop offset="1" class="e6nk6fapd"/></linearGradient><linearGradient id="iSrLw0d" x1="27.198" x2="19.296" y1="30.793" y2="28.026" gradientUnits="userSpaceOnUse"><stop class="xa_7m3b4l"/><stop offset="1" class="c4ry2c6jv"/></linearGradient><linearGradient id="iepOgvc" x1="15.015" x2="15.229" y1="28.674" y2="28.469" gradientUnits="userSpaceOnUse"><stop class="xcq_ambdy"/><stop offset="1" class="zh35wab0s"/></linearGradient><linearGradient id="igkqS7c" x1="19.002" x2="18.65" y1="21.983" y2="22.342" gradientUnits="userSpaceOnUse"><stop class="i-kbbcb4w"/><stop offset="1" class="k1jzsjbfs"/></linearGradient><linearGradient id="iM9gcse" x1="22.046" x2="23.357" y1="9.342" y2="11.358" gradientUnits="userSpaceOnUse"><stop class="hnpa3ubhc"/><stop offset="1" class="lycph8bhz"/></linearGradient><linearGradient id="iayided" x1="15.58" x2="17.299" y1="5.672" y2="5.672" gradientUnits="userSpaceOnUse"><stop class="z5duhrbsp"/><stop offset="1" class="qjga9kbjc"/></linearGradient><linearGradient id="ii1Wi8d" x1="15.644" x2="15.644" y1="6.329" y2="5.672" gradientUnits="userSpaceOnUse"><stop class="i4sxbdchy"/><stop offset="1" class="gpxsxqdnb"/></linearGradient><linearGradient id="i1nkGac" x1="15.969" x2="15.969" y1="4.756" y2="5.342" gradientUnits="userSpaceOnUse"><stop class="p59cvi4fc"/><stop offset="1" class="nr_-dacny"/></linearGradient><linearGradient id="ibZBOlb" x1="15.804" x2="16" y1="9.702" y2="10.444" gradientUnits="userSpaceOnUse"><stop class="vs-md1g6l"/><stop offset="1" class="c4k4l7qbc"/></linearGradient><linearGradient id="irlfuVD" x1="18.975" x2="18.661" y1="10.126" y2="10.319" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0raRjd" x1="14.576" x2="14.263" y1="10.126" y2="10.319" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-elf" /></template>
<style>
.a0ve6ibhs {
  stop-color: var(--svg-color--9f6c64, #9F6C64);
}

.auoirjbmm {
  fill: var(--svg-color--755bba, #755BBA);
  d: path("M8.912 18.302a10.9 10.9 0 0 0-3.84 8.319v3.318h3.84z");
}

.av_zubbsw {
  stop-color: var(--svg-color--9079d5, #9079D5);
  stop-opacity: 0;
}

.b1omo3bdl {
  stop-color: var(--svg-color--ffc326, #FFC326);
  stop-opacity: 0;
}

.b4qr-wvfv {
  stop-color: var(--svg-color--949393, #949393);
}

.bcmqo-b2d {
  stop-color: var(--svg-color--ffdf43, #FFDF43);
  stop-opacity: 0;
}

.bdhnfsb4c {
  stop-color: var(--svg-color--7566b5, #7566B5);
}

.bgmaoc9ef {
  stop-color: var(--svg-color--f8ab1b, #F8AB1B);
}

.bu_chtytz {
  stop-color: var(--svg-color--5742a1, #5742A1);
}

.bu7es_a0d {
  d: path("M8.487 7.779c1.524.44 2.582 1.437 2.928 1.89l.209 2.95c-.399.018-.94.243-1.934-.467c-1.165-1.041-1.72-2.576-1.999-3.545a.67.67 0 0 1 .135-.615a.64.64 0 0 1 .66-.213");
}

.buyndmbdh {
  fill: var(--svg-color--8b024f, #8B024F);
  d: path("M16 13.709c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.087-.129-.06-.278-.198-.209a3 3 0 0 1-1.385.33");
}

.c4k4l7qbc {
  stop-color: var(--svg-color--fabf2b, #FABF2B);
  stop-opacity: 0;
}

.c4ry2c6jv {
  stop-color: var(--svg-color--b3776e, #B3776E);
  stop-opacity: 0;
}

.c6fuokb_j {
  stop-color: var(--svg-color--f1a834, #F1A834);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cncl56oym {
  stop-color: var(--svg-color--e0922d, #E0922D);
  stop-opacity: 0;
}

.cwm4-i50i {
  stop-color: var(--svg-color--ce7916, #CE7916);
  stop-opacity: 0;
}

.d31bklhyx {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
  stop-opacity: 0;
}

.dgp6vzbgz {
  stop-color: var(--svg-color--613528, #613528);
  stop-opacity: 0;
}

.dht7arbom {
  fill: var(--svg-color--673c37, #673C37);
  d: path("M15.706 21.132c.264.22.79.923.79 1.906c0 1.053-.358 1.646-.701 2.06a.115.115 0 0 1-.178 0c-.343-.414-.702-1.007-.702-2.06c0-.983.527-1.685.79-1.907");
}

.di1h-reoj {
  stop-color: var(--svg-color--ffdf43, #FFDF43);
}

.dkudkx8wp {
  stop-color: var(--svg-color--ffc326, #FFC326);
}

.e_0vl3o1i {
  d: path("M11.401 11.165c-.904-1.684-2.446-2.402-3.074-2.56c.598 1.662 1.19 2.452 1.6 2.81c.44.384 1.057.369 1.293.355z");
}

.e4garxz9p {
  stop-color: var(--svg-color--d58521, #D58521);
}

.e4tar7-ra {
  fill: var(--svg-color--8868c9, #8868C9);
  d: path("M5.071 26.62c0-6.035 4.893-10.928 10.929-10.928s10.929 4.893 10.929 10.929v3.318H5.07z");
}

.e6nk6fapd {
  stop-color: var(--svg-color--a16162, #A16162);
}

.e8j2tsbtw {
  stop-color: var(--svg-color--714743, #714743);
}

.ecbjgibqi {
  fill: var(--svg-color--9172d5, #9172D5);
  d: path("M23.088 18.302a10.9 10.9 0 0 1 3.84 8.319v3.318h-3.84z");
}

.een_-ybfe {
  stop-color: var(--svg-color--e78519, #E78519);
  stop-opacity: 0;
}

.eh769jb3m {
  stop-color: var(--svg-color--954a15, #954A15);
  stop-opacity: 0;
}

.ei-zmixku {
  d: path("M5.071 26.62c0-6.035 4.893-10.928 10.929-10.928s10.929 4.893 10.929 10.929v3.318H5.07z");
}

.ekarirbxr {
  stop-color: var(--svg-color--ede5f4, #EDE5F4);
}

.erxqmfypp {
  stop-color: var(--svg-color--ffbe20, #FFBE20);
  stop-opacity: 0;
}

.ev9w4sb1n {
  stop-color: var(--svg-color--894606, #894606);
}

.eyv067r5m {
  stop-color: var(--svg-color--f8a82a, #F8A82A);
}

.f_vyractb {
  stop-color: var(--svg-color--9079d5, #9079D5);
}

.f2xhcsb6x {
  stop-color: var(--svg-color--ffe236, #FFE236);
  stop-opacity: 0;
}

.fgp762gdr {
  stop-color: var(--svg-color--dd9328, #DD9328);
}

.fisms_b6b {
  stop-color: var(--svg-color--c98913, #C98913);
  stop-opacity: 0;
}

.fqelt7o-r {
  stop-color: var(--svg-color--d68b33, #D68B33);
  stop-opacity: 0;
}

.frtpxb2_e {
  stop-color: var(--svg-color--795dc2, #795DC2);
}

.ft5dv1b6b {
  fill: none;
}

.fupnc-bzv {
  stop-color: var(--svg-color--8066bd, #8066BD);
}

.fux90lb8s {
  stop-color: var(--svg-color--715cb9, #715CB9);
  stop-opacity: 0;
}

.g0xvfdbyw {
  d: path("M8.85 5.672a.53.53 0 0 1 .529-.529h13.18a.53.53 0 0 1 0 1.059H9.379a.53.53 0 0 1-.53-.53");
}

.g2iiu-bfl {
  stop-color: var(--svg-color--ffb92b, #FFB92B);
  stop-opacity: 0;
}

.g38u58vho {
  stop-color: var(--svg-color--ecb624, #ECB624);
}

.ghfy1iray {
  d: path("m21.093 7.466l1.215.39c.137-.747.062-2.563-1.383-3.227c-1.729-.73-2.453-1.127-3.292-1.586l-.372-.203c-1.024-.554-2.588-.628-3.438.297c-.437.477-.617.617-.883.617c.163 1.19.458 1.866 1.674 2.696a3.3 3.3 0 0 0 1.917.578h3.266c.656 0 1.126.204 1.296.438");
}

.gpxsxqdnb {
  stop-color: var(--svg-color--b688b9, #B688B9);
  stop-opacity: 0;
}

.gt4worbah {
  stop-color: var(--svg-color--cc781b, #CC781B);
  stop-opacity: 0;
}

.h0yb7bbrn {
  stop-color: var(--svg-color--c2651f, #C2651F);
}

.h3rdn1bsz {
  stop-color: var(--svg-color--e29330, #E29330);
}

.h6i96qjvc {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
}

.h91_zc3nb {
  stop-color: var(--svg-color--c5731f, #C5731F);
  stop-opacity: 0;
}

.h9fd_uu9c {
  fill: var(--svg-color--e9b12e, #E9B12E);
  d: path("m12.924 15.577l.232 1c.03.107.117.372.232.578c.136.243 1.342 2.067 2.336 2.997a.27.27 0 0 0 .37.003c.991-.897 2.221-2.758 2.357-3c.115-.206.263-.471.293-.578l.258-1z");
}

.hby5gbc-p {
  d: path("M18.133 9.784c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.135.39-.05");
}

.hcc4fhb5v {
  d: path("M9.304 8.083A6.4 6.4 0 0 1 10.89 9.12v-.903c0-.412.314-.59.916-.934l.006-.003q.19-.107.418-.242c.653-.39.952-1.315 1.004-1.727c.969 1.59 2.113 2.11 3.297 2.11h3.266c.975 0 1.312.449 1.312.78l.014.907c.386-.344.93-.735 1.602-1.038c-.207-.523-.256-1.047-.295-1.478l-.008-.09c-.052-.544-.25-1.343-1.145-2.078c-.633-.484-1.16-.687-1.91-.812c-.472-.079-.778-.361-1.015-.579l-.071-.066c-.287-.302-1.23-.906-2.187-.906c-1.329 0-1.934.469-2.387.906c-.186.18-.353.328-.488.44c-.18.15-.404.226-.635.262c-1.018.158-1.634.527-2.21 1.127c-.698.727-.812 1.718-.874 2.5a2.2 2.2 0 0 1-.196.787");
}

.hgv4-zm2k {
  stop-color: var(--svg-color--783c25, #783C25);
}

.hnpa3ubhc {
  stop-color: var(--svg-color--fec938, #FEC938);
}

.hoq7d6bfq {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.406 9.323c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.i_u_7nb3k {
  stop-color: var(--svg-color--c07517, #C07517);
}

.i-kbbcb4w {
  stop-color: var(--svg-color--906550, #906550);
}

.i1ujs7one {
  d: path("m16.274 29.939l-9.221-9.595a10.95 10.95 0 0 1 5.854-4.208L26.69 29.94z");
}

.i2gy70vof {
  stop-color: var(--svg-color--c27b29, #C27B29);
  stop-opacity: 0;
}

.i4sxbdchy {
  stop-color: var(--svg-color--b688b9, #B688B9);
}

.i9lr1p25m {
  d: path("m15.618 10.098l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.114-.408-.646-.408-.765 0");
}

.iethn661e {
  d: path("m12.924 15.577l.232 1c.03.107.117.372.232.578c.136.243 1.342 2.067 2.336 2.997a.27.27 0 0 0 .37.003c.991-.897 2.221-2.758 2.357-3c.115-.206.263-.471.293-.578l.258-1z");
}

.ifj7fvbjw {
  stop-color: var(--svg-color--6651aa, #6651AA);
}

.im7yg7aog {
  stop-color: var(--svg-color--5e45a4, #5E45A4);
}

.in53vxbzi {
  stop-color: var(--svg-color--8666c7, #8666C7);
  stop-opacity: 0;
}

.iy200zbbi {
  stop-color: var(--svg-color--846fc5, #846FC5);
}

.j5zu11bke {
  stop-color: var(--svg-color--c2ffff, #C2FFFF);
}

.j9z2gfbkw {
  stop-color: var(--svg-color--e08e23, #E08E23);
}

.jq6-sgbpj {
  stop-color: var(--svg-color--804f24, #804F24);
  stop-opacity: 0;
}

.jxgek8btz {
  d: path("M18.994 10.37a.84.84 0 0 0-.232-.463l-.26.285l.118.229z");
}

.k-1w4_syq {
  stop-color: var(--svg-color--915959, #915959);
  stop-opacity: 0;
}

.k1jzsjbfs {
  stop-color: var(--svg-color--7f4b4c, #7F4B4C);
  stop-opacity: 0;
}

.k60t-0b2x {
  stroke: var(--svg-color--ff8935, #FF8935);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.544 8.526a2.35 2.35 0 0 0-1.738-.283");
}

.kfwilqo7s {
  stop-color: var(--svg-color--ffe42e, #FFE42E);
}

.khqd-3jrz {
  stop-color: var(--svg-color--ecb624, #ECB624);
  stop-opacity: 0;
}

.l-im3ccrf {
  stop-color: var(--svg-color--624ca8, #624CA8);
  stop-opacity: 0;
}

.ldj72pb6e {
  d: path("M23.513 7.779c-1.523.44-2.582 1.437-2.928 1.89l-.209 2.95c.4.018.94.243 1.934-.467c1.165-1.041 1.72-2.576 2-3.545a.67.67 0 0 0-.136-.615a.64.64 0 0 0-.66-.213");
}

.lg7v73bam {
  stop-color: var(--svg-color--ffca37, #FFCA37);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lm4m34bzz {
  stop-color: var(--svg-color--421d1e, #421D1E);
}

.lnczwubdj {
  fill: var(--svg-color--e39024, #E39024);
  d: path("m15.447 10.293l-.57 1.839c-.098.378.136.756.467.756h.707c.331 0 .565-.384.468-.756l-.478-1.839c-.102-.407-.487-.407-.594 0");
}

.lpdsa84op {
  stop-color: var(--svg-color--6951ad, #6951AD);
  stop-opacity: 0;
}

.lu3j7bbpk {
  cx: 13.561px;
  cy: 9.976px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.lycph8bhz {
  stop-color: var(--svg-color--ffd345, #FFD345);
}

.m_kdo_bhg {
  stop-color: var(--svg-color--ffd83e, #FFD83E);
}

.m00e_ufro {
  d: path("M18.199 9.595a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.mwmpt8y3b {
  stop-color: var(--svg-color--cd7721, #CD7721);
}

.mzy3c3d_u {
  stop-color: var(--svg-color--664dad, #664DAD);
}

.n0nbs1_lf {
  stop-color: var(--svg-color--e78519, #E78519);
}

.n1msxeybk {
  stop-color: var(--svg-color--5b4a9b, #5B4A9B);
  stop-opacity: 0;
}

.n4-d2tb8s {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16 13.709c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.087-.129-.06-.278-.198-.209a3 3 0 0 1-1.385.33Z");
}

.n81djoa0z {
  stop-color: var(--svg-color--cfc9e2, #CFC9E2);
  stop-opacity: 0;
}

.ngc6h6bst {
  stop-color: var(--svg-color--8d625b, #8D625B);
  stop-opacity: 0;
}

.nnydhdb8x {
  fill: var(--svg-color--000, #000);
  d: path("M17.688 10.488a.51.51 0 0 1 .51-.512a.51.51 0 0 1 .455.747h-.904a.46.46 0 0 1-.061-.235");
}

.npvlux_im {
  cx: 13.561px;
  cy: 9.976px;
  rx: 0.39px;
  ry: 0.197px;
}

.nr_-dacny {
  stop-color: var(--svg-color--a29b98, #A29B98);
  stop-opacity: 0;
}

.nz4t17rpu {
  stop-color: var(--svg-color--5e45a4, #5E45A4);
  stop-opacity: 0;
}

.nzbe5xbze {
  stop-color: var(--svg-color--ca993f, #CA993F);
}

.o5llqtbdv {
  stop-color: var(--svg-color--8d625b, #8D625B);
}

.o5xzi4bgi {
  stop-color: var(--svg-color--fffcc0, #FFFCC0);
}

.ob_nqzbct {
  stop-color: var(--svg-color--c9842e, #C9842E);
  stop-opacity: 0;
}

.ob9xa4oph {
  stop-color: var(--svg-color--975d5c, #975D5C);
}

.obp_ujbwu {
  stop-color: var(--svg-color--cc9839, #CC9839);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oqsc6ib4z {
  stop-color: var(--svg-color--80350d, #80350D);
}

.ox6ngqb6d {
  stop-color: var(--svg-color--846fc5, #846FC5);
  stop-opacity: 0;
}

.p0hjq828d {
  stop-color: var(--svg-color--d57022, #D57022);
}

.p1i4l-2xr {
  stop-color: var(--svg-color--ea9721, #EA9721);
}

.p59cvi4fc {
  stop-color: var(--svg-color--a29b98, #A29B98);
}

.pc9y3hbhd {
  stop-color: var(--svg-color--6e4641, #6E4641);
  stop-opacity: 0;
}

.pgd4nu3yt {
  d: path("M23.391 11.64c.213-.676.183-1.334.141-1.579h-6.219v6.992l4.277-.066c2.382-1.426 2.005-3.621 1.801-4.121c-.157-.389-.148-.774 0-1.227");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pm20wdikx {
  stop-color: var(--svg-color--ea9721, #EA9721);
  stop-opacity: 0;
}

.pmem73b8u {
  d: path("m13.698 5.67l-.011-.028c-.186-.447-.464-1.118-.553-1.878c-.669.078-2.173.547-2.837 1.797c-.482.909-.573 1.988-.54 2.752c.489.258.81.466 1.119.726v-.902c0-.412.333-.59.973-.934l.005-.003q.202-.107.445-.243c.693-.389 1.096-1.234 1.151-1.646q.123.19.248.359");
}

.pt5wpmbyr {
  stroke: var(--svg-color--ea752d, #EA752D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.486 8.526a2.35 2.35 0 0 1 1.737-.283");
}

.q2nms2n3q {
  d: path("M13.83 9.595a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.qah4ncc_b {
  stop-color: var(--svg-color--ca993f, #CA993F);
  stop-opacity: 0;
}

.qjga9kbjc {
  stop-color: var(--svg-color--cdc7e1, #CDC7E1);
}

.qneer9b8q {
  d: path("M15.907 3.644a.104.104 0 0 1 .144 0c.268.257.693.872.693 1.702c0 .974-.346 1.524-.678 1.907a.115.115 0 0 1-.174 0c-.332-.383-.679-.933-.679-1.907c0-.83.425-1.445.694-1.702");
}

.r_hbeqgkw {
  stop-color: var(--svg-color--795dc2, #795DC2);
  stop-opacity: 0;
}

.r0rrpvpum {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.624 9.323c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.r7mg8accg {
  stop-color: var(--svg-color--f3c137, #F3C137);
}

.rbi44vm-m {
  stop-color: var(--svg-color--a85d71, #A85D71);
}

.rk0wsibbd {
  d: path("M15.926 21.37a.09.09 0 0 1 .124 0c.276.27.729.94.729 1.85c0 1.053-.359 1.646-.702 2.06a.115.115 0 0 1-.178 0c-.343-.414-.702-1.007-.702-2.06c0-.91.453-1.58.73-1.85");
}

.rkzp1hbvm {
  stop-color: var(--svg-color--6fe9ff, #6FE9FF);
}

.rw730-4us {
  stop-color: var(--svg-color--ba7019, #BA7019);
}

.s1jm76o_g {
  stop-color: var(--svg-color--8b5548, #8B5548);
  stop-opacity: 0;
}

.sne73nbas {
  stop-color: var(--svg-color--8f5c4e, #8F5C4E);
}

.ssj6asr2b {
  stop-color: var(--svg-color--6d499b, #6D499B);
  stop-opacity: 0;
}

.sufsclgbu {
  stop-color: var(--svg-color--ffe236, #FFE236);
}

.sv77bgb6j {
  stop-color: var(--svg-color--c4812e, #C4812E);
  stop-opacity: 0;
}

.sytb8pb3p {
  fill: var(--svg-color--352e31, #352E31);
  d: path("M18.345 9.28c-.397.05-.74.302-.863.422l1.777.848l.527-.317c.194-.117.256-.378.088-.531c-.48-.44-1.116-.474-1.53-.422m-4.689 0c.398.05.741.302.863.422l-1.777.848l-.527-.317c-.194-.117-.255-.378-.088-.531c.48-.44 1.116-.474 1.53-.422");
}

.szuqc-bjo {
  stop-color: var(--svg-color--987cdc, #987CDC);
}

.t_wwcbcrg {
  stop-color: var(--svg-color--e4821e, #E4821E);
}

.t4e3sn74w {
  stop-color: var(--svg-color--cc781b, #CC781B);
}

.tdmcedchx {
  stop-color: var(--svg-color--c4812e, #C4812E);
}

.te6-97gvd {
  stop-color: var(--svg-color--ce7916, #CE7916);
}

.tf7ikua9d {
  stop-color: var(--svg-color--8a73c8, #8A73C8);
}

.trl24wm4t {
  stop-color: var(--svg-color--6655a7, #6655A7);
}

.u_k1hctwr {
  d: path("M8.609 11.64c-.213-.676-.182-1.334-.14-1.579h6.218v6.992l-4.312-.039c-2.39-1.406-1.97-3.648-1.766-4.148c.158-.389.148-.774 0-1.227");
}

.u7qedx64x {
  stop-color: var(--svg-color--624ca8, #624CA8);
}

.u9m-38uic {
  stop-color: var(--svg-color--4c200c, #4C200C);
}

.u9vkkub5w {
  stop-color: var(--svg-color--7c442f, #7C442F);
}

.ue1ou_b9r {
  stop-color: var(--svg-color--ba7019, #BA7019);
  stop-opacity: 0;
}

.uexiu3oxm {
  stop-color: var(--svg-color--f1a834, #F1A834);
  stop-opacity: 0;
}

.ui8xaew_b {
  stop-color: var(--svg-color--fee9b4, #FEE9B4);
}

.uqqizachy {
  stop-color: var(--svg-color--d56e20, #D56E20);
}

.uqzcd-flf {
  stop-color: var(--svg-color--c27b29, #C27B29);
}

.urkav0bvx {
  stop-color: var(--svg-color--cc9839, #CC9839);
}

.ut_l7ccde {
  stop-color: var(--svg-color--c9842e, #C9842E);
}

.utz8l-hjj {
  stop-color: var(--svg-color--6d499b, #6D499B);
}

.uvs4gu6ep {
  stop-color: var(--svg-color--f5a828, #F5A828);
  stop-opacity: 0;
}

.uwic7ybdl {
  stop-color: var(--svg-color--f29a26, #F29A26);
}

.uwyi2hzqu {
  d: path("M14.646 10.383c0-.289-.235-.481-.298-.54l-.288.28l.177.361z");
}

.vgwnw8h0u {
  d: path("M23.088 18.302a10.9 10.9 0 0 1 3.84 8.319v3.318h-3.84z");
}

.vhxxajp3a {
  stop-color: var(--svg-color--6e4641, #6E4641);
}

.vlizw1ypl {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.133 9.784c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.135.39-.05");
}

.vs-md1g6l {
  stop-color: var(--svg-color--fbbc2d, #FBBC2D);
}

.vyz233ddk {
  fill: var(--svg-color--f3a426, #F3A426);
  d: path("m15.618 10.098l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.114-.408-.646-.408-.765 0");
}

.w0-uzrbog {
  stop-color: var(--svg-color--ffbe20, #FFBE20);
}

.w3laegbtn {
  d: path("M10.827 7.622a3 3 0 0 1 2.998-3.093h4.35a3 3 0 0 1 2.999 3.085l-.118 4.144a5.052 5.052 0 0 1-10.1.014z");
}

.w5pplabgz {
  stop-color: var(--svg-color--954a15, #954A15);
}

.wctf3ibkb {
  d: path("M20.599 11.165c.904-1.684 2.446-2.402 3.074-2.56c-.598 1.662-1.19 2.452-1.6 2.81c-.44.384-1.057.369-1.293.355z");
}

.wj7x2ubbg {
  stop-color: var(--svg-color--804f24, #804F24);
}

.wpf0olbav {
  stop-color: var(--svg-color--783c25, #783C25);
  stop-opacity: 0;
}

.wz09qdb4r {
  stop-color: var(--svg-color--6651aa, #6651AA);
  stop-opacity: 0;
}

.x-171ccrl {
  d: path("M8.912 18.302a10.9 10.9 0 0 0-3.84 8.319v3.318h3.84z");
}

.xa_7m3b4l {
  stop-color: var(--svg-color--bb8274, #BB8274);
}

.xcq_ambdy {
  stop-color: var(--svg-color--7b4b52, #7B4B52);
}

.xg491tydm {
  stop-color: var(--svg-color--6655a7, #6655A7);
  stop-opacity: 0;
}

.xlqlhebaa {
  d: path("M12.127 14.599c-.289-.031-.859-.05-1.402.312c-.703.547-1.16 1.196-1.301 2.25c-.198 1.482 1.045 3.944 6.574 4.18h.004c5.529-.236 6.772-2.698 6.574-4.18c-.14-1.054-.598-1.703-1.3-2.25c-.606-.47-1.103-.468-1.392-.437L16 14.91z");
}

.xodttob3f {
  stop-color: var(--svg-color--7f70bc, #7F70BC);
  stop-opacity: 0;
}

.y4t-2eloy {
  stop-color: var(--svg-color--f3c137, #F3C137);
  stop-opacity: 0;
}

.y78euyjzo {
  stop-color: var(--svg-color--603739, #603739);
  stop-opacity: 0;
}

.ya66usbax {
  stop-color: var(--svg-color--7566b5, #7566B5);
  stop-opacity: 0;
}

.yh6vtccym {
  stop-color: var(--svg-color--fea828, #FEA828);
  stop-opacity: 0;
}

.yyik5z8lx {
  stop-color: var(--svg-color--949393, #949393);
  stop-opacity: 0;
}

.z5duhrbsp {
  stop-color: var(--svg-color--aba5ae, #ABA5AE);
}

.zh35wab0s {
  stop-color: var(--svg-color--7b4b52, #7B4B52);
  stop-opacity: 0;
}

.zhtqcybuc {
  fill: var(--svg-color--000, #000);
  d: path("M14.342 10.487a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.zw17tcbyg {
  stop-color: var(--svg-color--794c46, #794C46);
}

</style>
