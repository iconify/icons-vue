<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#if8rD6c)" class="lxdxtcbtx"/><path fill="url(#isQW0rb)" class="lxdxtcbtx"/><path fill="url(#ird4zbd)" class="lxdxtcbtx"/><path fill="url(#iHReM6W)" class="lxdxtcbtx"/><path fill="url(#ilbtxHc)" class="lxdxtcbtx"/><path fill="url(#iOFPbDd)" class="lxdxtcbtx"/><path fill="url(#iKmv6Xb)" class="lxdxtcbtx"/><path fill="url(#irSOtNd)" class="lxdxtcbtx"/><path fill="url(#iEcD6MG)" class="lxdxtcbtx"/><path fill="url(#iLkg9Fe)" class="lxdxtcbtx"/><path fill="url(#i2Js74b)" class="lxdxtcbtx"/><path fill="url(#iM9oofc)" class="lxdxtcbtx"/><path fill="url(#iJghhAe)" class="g3thww8ea"/><path fill="url(#iCSDOwb)" class="g3thww8ea"/><path class="zqok-4bbq"/><path fill="url(#iD4w90w)" class="kp53xom0f"/><path fill="url(#i5X7Aad)" class="kp53xom0f"/><path fill="url(#iR82pdF)" class="xt6dbf0mg"/><path fill="url(#ixaY9jb)" class="xt6dbf0mg"/><path fill="url(#is84Iud)" class="xt6dbf0mg"/><path fill="url(#if8Z4pd)" class="xt6dbf0mg"/><path fill="url(#iksUKBb)" class="uobrm5bpa"/><path fill="url(#iQ91vjc)" class="uobrm5bpa"/><g filter="url(#i6aB6Jb)"><path stroke="url(#inbqt7b)" class="w0i76lbel"/></g><g filter="url(#iREiYAd)"><path stroke="url(#i8XnkxJ)" class="h5vgl6ble"/></g><g filter="url(#iIahrRc)"><path stroke="url(#iNbLMkb)" class="a2yxrbcnp"/></g><g filter="url(#iV1qwPc)"><path stroke="url(#itH2Yfe)" class="rhzxhcb9q"/></g><g filter="url(#iwP77re)"><path stroke="url(#i2fvSge)" class="yex-seb2n"/></g><g filter="url(#i1GoNIb)"><path stroke="url(#iv8jDgV)" class="s19y_6x4x"/></g><g filter="url(#iVBHQFd)"><path stroke="url(#icjAShd)" class="e-97r7b8r"/></g><g filter="url(#iJ45TBe)"><path stroke="url(#iGLYY3d)" class="yq4ddmbqj"/></g><g filter="url(#i5Grjqe)"><path stroke="url(#id5uIgc)" class="mowm7igbc"/></g><g filter="url(#iN7W2ee)"><path stroke="url(#iUmFrcd)" class="s--dwhbpn"/></g><g filter="url(#itT1Nab)"><path stroke="url(#iLyZIBc)" class="e5e1oqb4v"/></g><path fill="url(#i1aFsvc)" class="g5xzner-y"/><path fill="url(#i7yUoUc)" class="gexq180zt"/><path fill="url(#il6P9He)" class="gexq180zt"/><g filter="url(#itOqFHc)"><path fill="url(#iEx5COc)" class="s5gc2st4o"/></g><path fill="url(#iubFBGf)" class="s5gc2st4o"/><path fill="url(#iDzNQqt)" class="s5gc2st4o"/><path fill="url(#iMtLqdb)" class="s5gc2st4o"/><path fill="url(#ioARq8d)" class="s5gc2st4o"/><path fill="url(#iuosthd)" class="s5gc2st4o"/><path fill="url(#i8upWDc)" class="s5gc2st4o"/><path fill="url(#iY3xhle)" class="s5gc2st4o"/><path fill="url(#iTx17Vb)" class="s5gc2st4o"/><g filter="url(#iZTCg3c)"><path class="mpvdrgbne"/></g><g filter="url(#inCLvAd)"><path fill="url(#iHejbkc)" class="lk7vvcbjo"/><path fill="url(#iyoDf8d)" class="lk7vvcbjo"/><path fill="url(#iaapYqe)" class="lk7vvcbjo"/><path fill="url(#iV55iFi)" class="lk7vvcbjo"/></g><path fill="url(#iuYHHrY)" class="lk7vvcbjo"/><path fill="url(#iEwxFOd)" class="lk7vvcbjo"/><g filter="url(#i8i7yab)"><path stroke="url(#iAjNtPe)" class="i_9ytqbml"/></g><path fill="url(#iYkgqqd)" class="t5hbkzb4g"/><g filter="url(#iXyjvNd)"><path fill="url(#iFbIj7b)" class="xcim5_bmb"/><path fill="url(#itx4KZb)" class="xcim5_bmb"/><path fill="url(#iyLlfsb)" class="xcim5_bmb"/><path fill="url(#iIpccvc)" class="xcim5_bmb"/><path fill="url(#iaOWVCb)" class="xcim5_bmb"/></g><g filter="url(#iSljPBb)"><path class="hsomt7l9z"/></g><g filter="url(#iEPXJze)"><path class="ea93wnbez"/></g><g filter="url(#iraj0GY)"><path fill="url(#i2SkmPE)" class="qzdrvygsm"/><path fill="url(#i2tfY1t)" class="qzdrvygsm"/></g><g filter="url(#iZZLtfc)"><path fill="url(#iMdRksc)" class="cp4pa-bea"/><path fill="url(#i3sFocx)" class="cp4pa-bea"/><path fill="url(#iseAYEb)" class="cp4pa-bea"/><path fill="url(#iwCaBjc)" class="cp4pa-bea"/><path fill="url(#iinda0c)" class="cp4pa-bea"/><path fill="url(#id9dvpb)" class="cp4pa-bea"/></g><path class="zuhxuz4qt"/><path fill="url(#iitwOhd)" class="zhpqmeb3l"/><path class="b19l7zkzs"/><g filter="url(#iwb8Mmk)"><path class="c1zg__2xl"/><path fill="url(#iHk4Sbh)" class="ajio91v-p"/></g><g filter="url(#i0pOW6L)"><path fill="url(#iarZAnd)" class="saxhiws8v"/></g><path class="xj7qjs5ot"/><path fill="url(#iKqw4gc)" class="iqe-ww4fx"/><path class="oixt-4bjr"/><g filter="url(#iIk6P4d)"><path fill="url(#ieeBKxc)" class="osegdx6co"/></g><g filter="url(#iGAZzCb)"><ellipse transform="rotate(-27.914 16.097 13.035)" class="ed6-g6b7r"/><ellipse fill="url(#iyhDYhb)" transform="rotate(-27.914 16.097 13.035)" class="v4p6mcdlh"/></g><path fill="url(#iWMeWhc)" class="wucuu23mt"/><path fill="url(#iaN3Ssc)" class="wucuu23mt"/><path fill="url(#i59HfId)" class="wucuu23mt"/><path fill="url(#iUfBc7b)" class="euot6-6oo"/><path fill="url(#iKmWnLe)" class="euot6-6oo"/><g filter="url(#izFEpNd)"><path class="m_9zaubli"/></g><g filter="url(#igEmiMb)"><path class="inrx2vbla"/></g><g filter="url(#iXD6Zec)"><path class="srwcxdbvw"/></g><g filter="url(#iCaAZQb)"><path class="ftgn_sxwr"/></g><defs><radialGradient id="if8rD6c" cx="0" cy="0" r="1" gradientTransform="matrix(2.33335 -6.04232 7.22855 2.79144 5.873 11.866)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="vpa8ubcez"/><stop offset="1" class="nick4i1gd"/></radialGradient><radialGradient id="isQW0rb" cx="0" cy="0" r="1" gradientTransform="rotate(130.764 2.782 7.313)scale(9.5721 2.30417)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="tvy-4obul"/><stop offset="1" class="rlvwxbcbx"/></radialGradient><radialGradient id="iHReM6W" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 2.2578 -.27074 .02342 4.598 5.054)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="i1fbwbbit"/><stop offset="1" class="lc7szmbjn"/></radialGradient><radialGradient id="ilbtxHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.04685 3.40625 -.266 -.00366 6.247 3.89)" gradientUnits="userSpaceOnUse"><stop class="i1fbwbbit"/><stop offset="1" class="lc7szmbjn"/></radialGradient><radialGradient id="iOFPbDd" cx="0" cy="0" r="1" gradientTransform="rotate(99.609 2.788 5.033)scale(4.02522 .49917)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="i1fbwbbit"/><stop offset="1" class="lc7szmbjn"/></radialGradient><radialGradient id="iKmv6Xb" cx="0" cy="0" r="1" gradientTransform="matrix(-.6629 .73793 -.64825 -.58233 9.714 3.484)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="irSOtNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6504 1.06501 -.658 -.40183 7.788 2.457)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="iEcD6MG" cx="0" cy="0" r="1" gradientTransform="rotate(99.841 1.58 3.932)scale(1.24402 .95461)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="iLkg9Fe" cx="0" cy="0" r="1" gradientTransform="matrix(-.13758 .96306 -.68465 -.0978 3.974 4.273)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="i2Js74b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09125 1.09125 -.85394 -.85394 12.01 6.754)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="iD4w90w" cx="0" cy="0" r="1" gradientTransform="matrix(-8.71543 2.79839 -2.98394 -9.29332 26.186 27.185)" gradientUnits="userSpaceOnUse"><stop class="ip469ff8c"/><stop offset="1" class="v0q_-i93u"/></radialGradient><radialGradient id="i5X7Aad" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.62502 2.66619 0 10.919 29.983)" gradientUnits="userSpaceOnUse"><stop class="xjv40os-m"/><stop offset="1" class="yrxkt-bta"/></radialGradient><radialGradient id="ixaY9jb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -5.4375 0 2.981 12.983)" gradientUnits="userSpaceOnUse"><stop class="ya78f26qa"/><stop offset="1" class="jfma4ebms"/></radialGradient><radialGradient id="is84Iud" cx="0" cy="0" r="1" gradientTransform="matrix(-7.94466 -1.83797 .619 -2.67566 16.996 21.286)" gradientUnits="userSpaceOnUse"><stop class="q2kyq2xrt"/><stop offset="1" class="wogt4ot2h"/></radialGradient><radialGradient id="iQ91vjc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.53834 -2.74595 0 19.014 20.483)" gradientUnits="userSpaceOnUse"><stop class="ueuebt_sv"/><stop offset="1" class="kyf2fxbmx"/><stop offset="1" class="bkt1vxl5k"/></radialGradient><radialGradient id="i1aFsvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.51528 3.35664 -3.98743 -.6121 25.505 15.16)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="i7yUoUc" cx="0" cy="0" r="1" gradientTransform="rotate(64.592 -6.05 17.57)scale(3.53038 1.60472)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="il6P9He" cx="0" cy="0" r="1" gradientTransform="matrix(.21321 1.41934 -1.24505 .18703 13.369 15.253)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iEx5COc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.21639 0 0 -10.9967 22.353 14.238)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iDzNQqt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35914 15.4142 -12.76477 -1.12553 20.895 7.206)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="zgchiqbcj"/><stop offset="1" class="qz-t25gyz"/></radialGradient><radialGradient id="iMtLqdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.59446 1.97314 0 21.924 12.906)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="ioARq8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.06904 -1.31204 1.4278 -.07514 16.353 12.743)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iuosthd" cx="0" cy="0" r="1" gradientTransform="matrix(1.43501 0 0 7.29384 13.21 14.695)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="i8upWDc" cx="0" cy="0" r="1" gradientTransform="matrix(3.1092 -4.3449 .98412 .70423 12.054 10.67)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iY3xhle" cx="0" cy="0" r="1" gradientTransform="matrix(-2.86999 -12.17983 13.41647 -3.16138 18.83 19.08)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iTx17Vb" cx="0" cy="0" r="1" gradientTransform="matrix(2.43155 .857 -.5141 1.45867 21.342 7.839)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iEwxFOd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1874 2.17743 -1.38398 -1.39032 20.226 14.147)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="iAjNtPe" cx="0" cy="0" r="1" gradientTransform="matrix(.4128 -.73658 2.14347 1.20128 17.674 18.149)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="iYkgqqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.85702 3.44801 0 19.014 18.446)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="itx4KZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.31955 7.65339 0 12.796 12.357)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="iyLlfsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.31955 7.65339 0 24.794 12.357)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iIpccvc" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 12.4 .245)scale(4.1383 2.20392)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="iaOWVCb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07626 1.7539 -4.06122 2.49211 17.938 3)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="i2SkmPE" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 9.245 4.047)scale(4.81241 1.33941)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="i2tfY1t" cx="0" cy="0" r="1" gradientTransform="matrix(3.82673 -6.05891 6.71265 4.23963 12.556 10.375)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iMdRksc" cx="0" cy="0" r="1" gradientTransform="matrix(4.026 .95226 -.53257 2.25161 23.319 6.095)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="i3sFocx" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 15.888 -1.447)scale(5.09146 2.83947)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="iseAYEb" cx="0" cy="0" r="1" gradientTransform="rotate(-120.695 15.38 -1.332)scale(3.04539 2.18129)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iwCaBjc" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 12.005 4.44)scale(5.86767 6.34318)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="iinda0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.13952 .45629 -2.0861 -.63786 23.12 5.807)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="id9dvpb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.37172 4.4645 -11.5127 -6.116 23.116 4.83)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iitwOhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96473 -1.53451 0 21.609 13.149)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iHk4Sbh" cx="0" cy="0" r="1" gradientTransform="matrix(-.27577 -.35537 .48926 -.37967 21.337 13.248)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKqw4gc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96478 -1.53459 0 16.42 13.148)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iyhDYhb" cx="0" cy="0" r="1" gradientTransform="matrix(-.0092 -.5875 .70621 -.01106 16.079 13.41)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iaN3Ssc" cx="0" cy="0" r="1" gradientTransform="matrix(.7474 2.66746 -2.54496 .71308 24.505 13.165)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="i59HfId" cx="0" cy="0" r="1" gradientTransform="matrix(.93674 -1.28553 1.07753 .78518 24.933 13.813)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iKmWnLe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99174 -.29127 .28635 -1.95806 13.169 13.93)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><linearGradient id="ird4zbd" x1="6.356" x2="6.356" y1="12.527" y2="10.824" gradientUnits="userSpaceOnUse"><stop class="mwk8f57wh"/><stop offset="1" class="ily2h4rfo"/></linearGradient><linearGradient id="iM9oofc" x1="2.958" x2="3.768" y1="9.411" y2="9.333" gradientUnits="userSpaceOnUse"><stop class="qe0h-qt8x"/><stop offset="1" class="je3tjybua"/></linearGradient><linearGradient id="iJghhAe" x1="4.2" x2="8.575" y1="12.546" y2="12.546" gradientUnits="userSpaceOnUse"><stop class="zmcsd8b9p"/><stop offset=".743" class="zdo6gqojl"/></linearGradient><linearGradient id="iCSDOwb" x1="6.47" x2="6.47" y1="11.96" y2="12.218" gradientUnits="userSpaceOnUse"><stop class="p4ezwj49r"/><stop offset="1" class="q3td6tqwm"/></linearGradient><linearGradient id="iR82pdF" x1="9.466" x2="11.423" y1="26.651" y2="20.367" gradientUnits="userSpaceOnUse"><stop class="b05_udben"/><stop offset="1" class="a91fxs_hx"/></linearGradient><linearGradient id="if8Z4pd" x1="13.559" x2="12.997" y1="24.343" y2="23.28" gradientUnits="userSpaceOnUse"><stop offset=".133" class="b2wdmyb-l"/><stop offset="1" class="pmtca2xis"/></linearGradient><linearGradient id="iksUKBb" x1="17.284" x2="21.059" y1="21.068" y2="24.175" gradientUnits="userSpaceOnUse"><stop class="en8iis40e"/><stop offset="1" class="po440651d"/></linearGradient><linearGradient id="inbqt7b" x1="7.013" x2="12.763" y1="15.265" y2="23.546" gradientUnits="userSpaceOnUse"><stop class="gokcfhb1a"/><stop offset="1" class="sq9q63bos"/></linearGradient><linearGradient id="i8XnkxJ" x1="4.846" x2="3.895" y1="5.221" y2="7.007" gradientUnits="userSpaceOnUse"><stop class="zhwoeykns"/><stop offset="1" class="vrs9uvb1p"/></linearGradient><linearGradient id="iNbLMkb" x1="6.266" x2="4.966" y1="4.792" y2="5.771" gradientUnits="userSpaceOnUse"><stop class="zhwoeykns"/><stop offset="1" class="vrs9uvb1p"/></linearGradient><linearGradient id="itH2Yfe" x1="8.026" x2="7.644" y1="5.392" y2="6.956" gradientUnits="userSpaceOnUse"><stop class="zhwoeykns"/><stop offset="1" class="vrs9uvb1p"/></linearGradient><linearGradient id="i2fvSge" x1="3.612" x2="4.032" y1="5.334" y2="7.941" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="iv8jDgV" x1="4.756" x2="4.968" y1="4.46" y2="7.584" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="icjAShd" x1="6.906" x2="8.008" y1="3.704" y2="7.38" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="iGLYY3d" x1="7.861" x2="8.177" y1="4.653" y2="8.085" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="id5uIgc" x1="4.907" x2="3.815" y1="7.201" y2="7.133" gradientUnits="userSpaceOnUse"><stop class="qnynbebrn"/><stop offset="1" class="ogs4x8_bh"/></linearGradient><linearGradient id="iUmFrcd" x1="6.179" x2="5.614" y1="7.029" y2="6.888" gradientUnits="userSpaceOnUse"><stop class="qnynbebrn"/><stop offset="1" class="ogs4x8_bh"/></linearGradient><linearGradient id="iLyZIBc" x1="7.68" x2="6.877" y1="6.842" y2="6.629" gradientUnits="userSpaceOnUse"><stop class="qnynbebrn"/><stop offset="1" class="ogs4x8_bh"/></linearGradient><linearGradient id="iubFBGf" x1="25.146" x2="19.971" y1="16.242" y2="16.242" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iHejbkc" x1="19.014" x2="20.03" y1="15.223" y2="15.223" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iyoDf8d" x1="17.738" x2="19.016" y1="15.038" y2="15.109" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="iaapYqe" x1="19.014" x2="19.014" y1="15.697" y2="16.71" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iV55iFi" x1="19.014" x2="19.014" y1="13.025" y2="13.524" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iuYHHrY" x1="19.169" x2="19.169" y1="16.499" y2="16.429" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="iFbIj7b" x1="25.392" x2="13.354" y1="7.504" y2="7.504" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iarZAnd" x1="22.534" x2="22.161" y1="13.213" y2="13.443" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ieeBKxc" x1="17.304" x2="16.931" y1="13.213" y2="13.443" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWMeWhc" x1="26.667" x2="25.232" y1="13.245" y2="15.832" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iUfBc7b" x1="12.058" x2="13.792" y1="14.082" y2="13.93" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><filter id="i6aB6Jb" width="9.217" height="12.757" x="5.356" y="12.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".75"/></filter><filter id="iREiYAd" width=".423" height="2.22" x="4.453" y="5.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".05"/></filter><filter id="iIahrRc" width=".345" height="2.572" x="6.008" y="4.651" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".05"/></filter><filter id="iV1qwPc" width=".509" height="1.681" x="7.484" y="5.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".05"/></filter><filter id="iwP77re" width="1.556" height="3.487" x="3.319" y="4.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".2"/></filter><filter id="i1GoNIb" width="1.2" height="3.889" x="5.004" y="3.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".2"/></filter><filter id="iVBHQFd" width="1.488" height="4.773" x="6.552" y="2.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".2"/></filter><filter id="iJ45TBe" width="2.002" height="4.299" x="7.955" y="3.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".2"/></filter><filter id="i5Grjqe" width="1.413" height="1.358" x="3.609" y="6.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".1"/></filter><filter id="iN7W2ee" width="1.118" height=".999" x="5.258" y="6.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".1"/></filter><filter id="itT1Nab" width="1.312" height="1.023" x="6.523" y="6.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".1"/></filter><filter id="itOqFHc" width="12.903" height="14.875" x="12.993" y="6.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3871"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3871" result="effect2_innerShadow_4002_3871"/></filter><filter id="iZTCg3c" width="4.086" height="5.358" x="16.651" y="12.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".5"/></filter><filter id="inCLvAd" width="2.432" height="3.648" x="17.798" y="12.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".05"/></filter><filter id="i8i7yab" width="4.327" height="1.776" x="16.851" y="17.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".05"/></filter><filter id="iXyjvNd" width="15.307" height="9.842" x="11.361" y="3.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3871"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3871" result="effect2_innerShadow_4002_3871"/></filter><filter id="iSljPBb" width="2.762" height="1.378" x="20.904" y="9.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3871"/></filter><filter id="iEPXJze" width="2.762" height="1.36" x="14.653" y="9.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3871"/></filter><filter id="iraj0GY" width="8.235" height="7.53" x="11.581" y="4.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".25"/></filter><filter id="iZZLtfc" width="8.017" height="7.275" x="18.575" y="4.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".25"/></filter><filter id="iwb8Mmk" width=".898" height=".79" x="20.755" y="12.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".05"/></filter><filter id="i0pOW6L" width=".984" height="1.01" x="21.772" y="12.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".1"/></filter><filter id="iIk6P4d" width="1.097" height="1.161" x="16.489" y="12.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".1"/></filter><filter id="iGAZzCb" width="1.048" height=".8" x="15.573" y="12.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".05"/></filter><filter id="izFEpNd" width="1.486" height="2.735" x="11.888" y="12.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".125"/></filter><filter id="igEmiMb" width="1.625" height="2.763" x="24.664" y="12.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".125"/></filter><filter id="iXD6Zec" width="2.718" height="1.238" x="14.628" y="10.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".125"/></filter><filter id="iCaAZQb" width="2.718" height="1.238" x="20.905" y="9.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3871" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-raising-hand-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a2yxrbcnp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m6.216 4.788l-.07 2.297");
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.a91fxs_hx {
  stop-color: var(--svg-color--ff4b54, #FF4B54);
  stop-opacity: 0;
}

.ajio91v-p {
  d: path("M21.533 12.806c.076.1-.082.224-.262.358c-.18.135-.313.23-.389.128c-.075-.101.01-.292.189-.426c.18-.135.386-.162.462-.06");
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.b05_udben {
  stop-color: var(--svg-color--ff4b54, #FF4B54);
}

.b19l7zkzs {
  fill: var(--svg-color--000, #000);
  d: path("M21.003 13.642c0-.337.27-.607.608-.607a.605.605 0 0 1 .54.887h-1.075a.55.55 0 0 1-.073-.28");
}

.b2wdmyb-l {
  stop-color: var(--svg-color--ff611d, #FF611D);
}

.bkt1vxl5k {
  stop-color: var(--svg-color--bd6d6d, #BD6D6D);
  stop-opacity: 0;
}

.c1zg__2xl {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M21.533 12.806c.076.1-.082.224-.262.358c-.18.135-.313.23-.389.128c-.075-.101.01-.292.189-.426c.18-.135.386-.162.462-.06");
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cp4pa-bea {
  d: path("m25.212 11.57l-.034-.75c-.013-.908-.763-1.657-1.671-1.695h-1.665a2.88 2.88 0 0 1-2.526-1.498s-.125-.291-.216-.76c-.19-.986.728-1.717 1.716-1.547c1.23.212 2.71.614 3.777 1.31c2.074 1.354 1.711 3.792.62 4.94");
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dm6t8mbjz {
  stop-color: var(--svg-color--c27b78, #C27B78);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e-97r7b8r {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m7.44 2.99l-.289 3.944");
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e5e1oqb4v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.535 6.849c-.13.164-.501.36-.712.422");
}

.ea93wnbez {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M14.958 10.565a3.3 3.3 0 0 1 2.068-.427a.33.33 0 1 1-.08.654a2.64 2.64 0 0 0-1.65.339a2 2 0 0 0-.108.071l-.003.003a.33.33 0 0 1-.404-.522z");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.ed6-g6b7r {
  cx: 16.097px;
  cy: 13.035px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.463px;
  ry: 0.234px;
}

.en8iis40e {
  stop-color: var(--svg-color--b56860, #B56860);
}

.euot6-6oo {
  d: path("M13.004 12.028a1.914 1.914 0 0 0 .165 3.805a93 93 0 0 1-.165-3.805");
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftgn_sxwr {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.248 10.843c-.305-.22-1.067-.605-1.968-.453");
}

.g3thww8ea {
  d: path("M4.364 12.16c0-.11.09-.2.2-.2h3.811c.11 0 .2.09.2.2v1.714h-4.21z");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g5xzner-y {
  d: path("M24.794 15.724a1.95 1.95 0 0 0 1.076-.367v1.107a2.58 2.58 0 0 1-1.594 2.401a4.9 4.9 0 0 0 .41-1.403z");
}

.gexq180zt {
  d: path("M13.234 15.724a1.95 1.95 0 0 1-1.076-.367v1.107c0 1.062.633 2.008 1.594 2.401a4.9 4.9 0 0 1-.411-1.403z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gokcfhb1a {
  stop-color: var(--svg-color--ff7636, #FF7636);
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h5vgl6ble {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m4.59 5.218l.15 1.945");
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hsomt7l9z {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M23.453 10.695c-.209-.182-.45-.374-.818-.49c-.362-.113-.815-.144-1.442-.067a.33.33 0 0 0 .08.654c.573-.07.923-.033 1.164.043c.236.074.395.194.582.357a.33.33 0 0 0 .434-.497");
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i_9ytqbml {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.401 17.225a.26.26 0 0 0-.306.053a.24.24 0 0 0-.026.304a2.33 2.33 0 0 0 1.945 1.04c.816 0 1.534-.416 1.945-1.04a.24.24 0 0 0-.026-.307a.26.26 0 0 0-.306-.05a3.5 3.5 0 0 1-1.613.382c-.592 0-1.147-.14-1.613-.382Z");
}

.i1fbwbbit {
  stop-color: var(--svg-color--cd8d5e, #CD8D5E);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.ily2h4rfo {
  stop-color: var(--svg-color--cf8a62, #CF8A62);
  stop-opacity: 0;
}

.inrx2vbla {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M24.914 15.058q.069-1.132.132-2.263a1.136 1.136 0 0 1-.132 2.263");
}

.ip469ff8c {
  stop-color: var(--svg-color--ff8045, #FF8045);
}

.iqe-ww4fx {
  d: path("M16.417 12.581a1.06 1.06 0 0 0-1.023 1.341h2.05q.039-.136.04-.28a1.07 1.07 0 0 0-1.067-1.06");
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.je3tjybua {
  stop-color: var(--svg-color--ffc3a0, #FFC3A0);
  stop-opacity: 0;
}

.jfma4ebms {
  stop-color: var(--svg-color--ff7c1f, #FF7C1F);
  stop-opacity: 0;
}

.jfno0m0sa {
  stop-color: var(--svg-color--f2c4a1, #F2C4A1);
  stop-opacity: 0;
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kp53xom0f {
  d: path("M20.04 20.983h.974c2.5 0 7.5 3.5 7.5 9h-18v-3.5a.67.67 0 0 0-.416-.625l-3.084-1.375c-2.5-1-3.5-3.5-3.5-5.198v-5.287c0-.564.425-1.015.935-1.015h4.13c.52 0 .935.461.935 1.015v3.985c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.kyf2fxbmx {
  stop-color: var(--svg-color--894d5b, #894D5B);
  stop-opacity: 0;
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.lc7szmbjn {
  stop-color: var(--svg-color--cd8d5e, #CD8D5E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk7vvcbjo {
  d: path("m18.56 13.388l-.633 2.186c-.129.45.18.9.62.9h.934c.439 0 .749-.457.62-.9l-.632-2.186c-.136-.484-.768-.484-.91 0");
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.lxdxtcbtx {
  d: path("M3.294 9.23c-.125-1.921-.281-2.958-.328-3.64c-.035-.512.023-1.066.71-1.191c.598-.075.884.451.907.66c-.003-.2 0-.68 0-.805c0-.21.008-.976.86-.976c.6 0 .816.587.8.863c.01-.102.023-.413.035-.707c.019-.433.252-.99.946-.977c.597.04.793.614.765.977L7.872 5.3c.024-.188.102-.665.277-1.34s.702-.72.958-.683c.325.046.88.36.648 1.273c-.275 1.156-.462 2.645-.527 3.285c.324-.133.642-.412 1.001-.787c.36-.375.887-.383 1.184-.16c.34.292.522.967.12 1.369c-.463.425-2.13 2.405-2.958 3.395c-.229.291-.997.874-2.234.874c-2.203-.093-2.942-1.676-3.047-3.296");
}

.m_9zaubli {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M13.024 12.814a1.137 1.137 0 0 0 .1 2.234a92 92 0 0 1-.1-2.234");
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mowm7igbc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M3.909 8.006c.11-.063.617-.38.813-.758");
}

.mpvdrgbne {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m18.502 13.838l-.823 1.969c-.12.45.169.9.579.9h.873c.41 0 .7-.457.579-.9l-.59-2.186c-.127-.484-.486-.267-.618.217");
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.mwk8f57wh {
  stop-color: var(--svg-color--cf8a62, #CF8A62);
}

.n2lghubug {
  stop-color: var(--svg-color--f1bea1, #F1BEA1);
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.nick4i1gd {
  stop-color: var(--svg-color--e5b38f, #E5B38F);
}

.nkqxn1-bm {
  stop-color: var(--svg-color--f2c4a1, #F2C4A1);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.o-9gnobjq {
  stop-color: var(--svg-color--f1bea1, #F1BEA1);
  stop-opacity: 0;
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.ogs4x8_bh {
  stop-color: var(--svg-color--efb99b, #EFB99B);
  stop-opacity: 0;
}

.oixt-4bjr {
  fill: var(--svg-color--000, #000);
  d: path("M17.025 13.643a.605.605 0 0 0-.608-.608a.605.605 0 0 0-.54.887h1.075a.6.6 0 0 0 .073-.28");
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.osegdx6co {
  d: path("M17.387 13.518c0-.343-.28-.572-.355-.64l-.343.33l.211.43z");
}

.p4ezwj49r {
  stop-color: var(--svg-color--dd6422, #DD6422);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmtca2xis {
  stop-color: var(--svg-color--ff611d, #FF611D);
  stop-opacity: 0;
}

.po440651d {
  stop-color: var(--svg-color--f3ae8e, #F3AE8E);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q2kyq2xrt {
  stop-color: var(--svg-color--d93f13, #D93F13);
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q3td6tqwm {
  stop-color: var(--svg-color--dd6422, #DD6422);
  stop-opacity: 0;
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qe0h-qt8x {
  stop-color: var(--svg-color--ffc3a0, #FFC3A0);
}

.qnynbebrn {
  stop-color: var(--svg-color--efb99b, #EFB99B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qz-t25gyz {
  stop-color: var(--svg-color--b36e91, #B36E91);
}

.qzdrvygsm {
  d: path("M19.29 7.56a3 3 0 0 1-.078-.162a.79.79 0 0 0-.732-.498h-1.514c-2.194 0-3.973 1.799-3.973 4.018v.328c-.404-.308-.912-.957-.912-2.007c0-1.275.93-1.92 1.522-2.33c.167-.116.308-.213.393-.301l.119-.125c.415-.44 1.156-1.226 2.45-1.57a6.6 6.6 0 0 1 1.945-.19c.473.021.805.43.805.902v1.92z");
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.rhzxhcb9q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m7.856 5.39l-.234 1.406");
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rlvwxbcbx {
  stop-color: var(--svg-color--cf9271, #CF9271);
  stop-opacity: 0;
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.s--dwhbpn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.076 7.04c-.13.165-.333.3-.518.4");
}

.s19y_6x4x {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.604 3.901V6.99");
}

.s5gc2st4o {
  d: path("M13.277 17.526a4.66 4.66 0 0 0 4.62 4.05h2.244a4.656 4.656 0 0 0 4.62-4.05c.14-2.24.281-4.471.385-6.71a1.723 1.723 0 0 0-1.64-1.703h-1.664a2.88 2.88 0 0 1-2.63-1.715a.79.79 0 0 0-.732-.498h-1.513c-2.195 0-3.974 1.799-3.974 4.018c0 2.213.139 4.39.284 6.608");
}

.saxhiws8v {
  d: path("M22.556 13.503a1 1 0 0 0-.275-.55l-.309.339l.14.271z");
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.sq9q63bos {
  stop-color: var(--svg-color--ff7636, #FF7636);
  stop-opacity: 0;
}

.srwcxdbvw {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.003 10.898c.306-.22 1.067-.605 1.968-.454");
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.t5hbkzb4g {
  d: path("M19.014 17.682c-.604 0-1.17-.142-1.647-.39c-.163-.083-.338.1-.236.248a2.25 2.25 0 0 0 1.883 1.006c.79 0 1.485-.402 1.883-1.006c.102-.154-.073-.331-.236-.248a3.56 3.56 0 0 1-1.647.39");
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tvy-4obul {
  stop-color: var(--svg-color--c3806d, #C3806D);
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.ueuebt_sv {
  stop-color: var(--svg-color--bd6d6d, #BD6D6D);
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uobrm5bpa {
  d: path("M19.014 23.983c-1.268 0-2.296-.985-2.296-2.2v-2.6c0-1.214 1.028-2.2 2.296-2.2s2.296.986 2.296 2.2v2.6c0 1.215-1.028 2.2-2.296 2.2");
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v0q_-i93u {
  stop-color: var(--svg-color--ff8045, #FF8045);
  stop-opacity: 0;
}

.v4p6mcdlh {
  cx: 16.097px;
  cy: 13.035px;
  rx: 0.463px;
  ry: 0.234px;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vpa8ubcez {
  stop-color: var(--svg-color--e1a88d, #E1A88D);
}

.vrs9uvb1p {
  stop-color: var(--svg-color--ca895a, #CA895A);
  stop-opacity: 0;
}

.w0i76lbel {
  d: path("M7.356 13.64v6.017a2 2 0 0 0 1.38 1.901l4.183 1.363");
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wogt4ot2h {
  stop-color: var(--svg-color--d93f13, #D93F13);
  stop-opacity: 0;
}

.wucuu23mt {
  d: path("M24.867 15.832q.118-1.897.22-3.794a1.914 1.914 0 0 1-.22 3.794");
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.xcim5_bmb {
  d: path("M24.787 6.339a2.76 2.76 0 0 1 1.507 1.25a2.82 2.82 0 0 1-.126 3.004c-.208.306-.322.67-.322 1.04v1.412a2.1 2.1 0 0 0-.793-.319l.093-1.91a1.724 1.724 0 0 0-1.64-1.703h-1.664a2.88 2.88 0 0 1-2.63-1.715a.79.79 0 0 0-.732-.498h-1.514c-2.194 0-3.973 1.799-3.973 4.018l.037 1.828c-.302.045-.618.146-.857.314v-1.428c0-.37-.113-.733-.321-1.04a2.84 2.84 0 0 1-.17-2.907a2.8 2.8 0 0 1 1.545-1.34a3.2 3.2 0 0 0 1.646-1.32a2.765 2.765 0 0 1 3.437-1.084a1.77 1.77 0 0 0 1.419 0c.334-.14.7-.223 1.085-.223c1.002 0 1.879.542 2.365 1.345a3 3 0 0 0 1.608 1.276");
}

.xj7qjs5ot {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.17 12.258a1.66 1.66 0 0 0-1.61 1.26a.326.326 0 0 0 .318.404h2.653a.274.274 0 0 0 .27-.323a1.666 1.666 0 0 0-1.63-1.34");
}

.xjv40os-m {
  stop-color: var(--svg-color--ff6e45, #FF6E45);
}

.xt6dbf0mg {
  d: path("m18.372 21.093l-7.874 5.245a.66.66 0 0 0-.4-.48l-3.084-1.375c-2.5-1-3.5-3.5-3.5-5.198v-5.287c0-.564.425-1.015.935-1.015h4.13c.52 0 .935.461.935 1.015v3.985c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.ya78f26qa {
  stop-color: var(--svg-color--ff7c1f, #FF7C1F);
}

.yex-seb2n {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m3.917 4.857l.36 2.633");
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yq4ddmbqj {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M9.362 4.037L8.55 7.443");
}

.yrxkt-bta {
  stop-color: var(--svg-color--ff6e45, #FF6E45);
  stop-opacity: 0;
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.zdo6gqojl {
  stop-color: var(--svg-color--d64d18, #D64D18);
}

.zgchiqbcj {
  stop-color: var(--svg-color--b36e91, #B36E91);
  stop-opacity: 0;
}

.zhpqmeb3l {
  d: path("M21.611 12.581a1.06 1.06 0 0 1 1.023 1.341h-2.05a1.065 1.065 0 0 1 1.027-1.341");
}

.zhwoeykns {
  stop-color: var(--svg-color--ca895a, #CA895A);
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmcsd8b9p {
  stop-color: var(--svg-color--e6724b, #E6724B);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zqok-4bbq {
  fill: var(--svg-color--ff611d, #FF611D);
  d: path("M20.04 20.983h.974c2.5 0 7.5 3.5 7.5 9h-18v-3.5a.67.67 0 0 0-.416-.625l-3.084-1.375c-2.5-1-3.5-3.5-3.5-5.198v-5.287c0-.564.425-1.015.935-1.015h4.13c.52 0 .935.461.935 1.015v3.985c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.zuhxuz4qt {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.857 12.258a1.66 1.66 0 0 1 1.611 1.259a.326.326 0 0 1-.318.405h-2.653a.274.274 0 0 1-.27-.323c.15-.762.82-1.34 1.63-1.34");
}

</style>
