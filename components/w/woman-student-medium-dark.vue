<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ixKJTpc)"><path fill="url(#i8I8FQa)" clip-rule="evenodd" class="eegosnvzs"/><path fill="url(#imbBHNA)" clip-rule="evenodd" class="eegosnvzs"/><path fill="url(#imb5Xlf)" clip-rule="evenodd" class="eegosnvzs"/><path fill="url(#iUXy3we)" clip-rule="evenodd" class="eegosnvzs"/><path fill="url(#iBbL7lb)" clip-rule="evenodd" class="eegosnvzs"/><path fill="url(#idyu6He)" clip-rule="evenodd" class="eegosnvzs"/><path fill="url(#iyVRmId)" clip-rule="evenodd" class="eegosnvzs"/><path fill="url(#inWyNtc)" clip-rule="evenodd" class="eegosnvzs"/><path fill="url(#ipzSQSc)" clip-rule="evenodd" class="eegosnvzs"/><path fill="url(#iWcEDvc)" clip-rule="evenodd" class="eegosnvzs"/><path fill="url(#iioSBQe)" clip-rule="evenodd" class="eegosnvzs"/></g><path class="ziupmvs4c"/><path fill="url(#iO0gFwA)" class="jhkgglbjb"/><path fill="url(#ixdoJZc)" class="jhkgglbjb"/><path fill="url(#iIlKuoj)" class="wktcbebgy"/><path fill="url(#iK4aaJd)" class="wktcbebgy"/><path fill="url(#ipAhZWb)" class="wktcbebgy"/><path fill="url(#iApBLmc)" class="wktcbebgy"/><path fill="url(#ipJehJb)" class="wktcbebgy"/><path fill="url(#isAnhsc)" class="wktcbebgy"/><g filter="url(#iGxQyve)"><path class="zih98ybws"/></g><path fill="url(#i7YQVEe)" class="pxnc7tbps"/><path fill="url(#icg4kmb)" class="pxnc7tbps"/><path fill="url(#izfAWBe)" class="pxnc7tbps"/><path fill="url(#iDynBed)" class="ci7ih6m3p"/><path fill="url(#i4BvFph)" class="ci7ih6m3p"/><path fill="url(#iNVcP3d)" class="s9wrpn8gs"/><path fill="url(#id9Aw6i)" class="s9wrpn8gs"/><g filter="url(#ifMiy5b)"><path stroke="url(#ihl1jBN)" class="t483lu3vu"/></g><path fill="url(#i2787Pb)" class="v4ibyebyv"/><path fill="url(#iUgHI4c)" class="v4ibyebyv"/><path fill="url(#iIep1Ab)" class="v4ibyebyv"/><path fill="url(#iBkD9qb)" class="v4ibyebyv"/><path fill="url(#iZGwOYy)" class="v4ibyebyv"/><path fill="url(#iF6FEDe)" class="g6oprmb2u"/><path fill="url(#iwQBnuc)" class="g6oprmb2u"/><path fill="url(#ivrs4dc)" class="g6oprmb2u"/><path fill="url(#ijv9JYd)" class="qyk7h_b4b"/><path fill="url(#iTwfjyc)" class="qyk7h_b4b"/><g filter="url(#i6l7Mnc)"><path fill="url(#ipTHJMc)" class="df4a3u0pu"/><path fill="url(#ipTHJMc)" class="nmzhv-k6p"/><path fill="url(#ipTHJMc)" class="o7212rbuo"/></g><g filter="url(#i3bjgxd)"><path stroke="url(#iRAtKFd)" class="mup5fmbmx"/></g><g filter="url(#iGGHAqd)"><path fill="url(#i5qavOR)" class="rk6fry6yk"/></g><g filter="url(#iK4Dhwb)"><path fill="url(#iQIku0c)" class="qz8bps8mw"/><path fill="url(#iUmpN9c)" class="qz8bps8mw"/></g><g filter="url(#is8SC0c)"><path class="fjzt4xbni"/><path fill="url(#iZQDBim)" class="pfapn4txr"/></g><g filter="url(#iBtVBfc)"><path class="b9h3klt4n"/><path fill="url(#iJXKIJc)" class="y3arqr1oy"/></g><g filter="url(#i1aLEge)"><path fill="url(#i9y9PSc)" class="iadk84bnt"/><path fill="url(#iWpIOde)" class="iadk84bnt"/><path fill="url(#iV6nt6b)" class="iadk84bnt"/><path fill="url(#iF73IVc)" class="iadk84bnt"/><path fill="url(#iiYq9fb)" class="iadk84bnt"/><path fill="url(#iYb4jFb)" class="iadk84bnt"/><path fill="url(#iSOdVje)" class="iadk84bnt"/><path fill="url(#ikEwJVb)" class="iadk84bnt"/></g><path fill="url(#i81562p)" class="iadk84bnt"/><g filter="url(#i4KEuAt)"><path class="k978n-7rf"/></g><g filter="url(#iATGUZb)"><path class="w-8l0wvxz"/><path fill="url(#iO21R7I)" class="h5j0dmbxj"/><path fill="url(#i8jOkBd)" class="h5j0dmbxj"/><path fill="url(#ihhugkd)" class="h5j0dmbxj"/><path fill="url(#iCvZL3b)" class="h5j0dmbxj"/></g><path fill="url(#iiTM8qd)" class="h5j0dmbxj"/><path fill="url(#iYfFd0b)" class="h5j0dmbxj"/><path stroke="url(#ixjXD9c)" class="fykrdyk2a"/><g filter="url(#i5bjy8d)"><path class="pp0bb32bq"/></g><g filter="url(#ipfHg1b)"><path class="dkiekehrz"/></g><g filter="url(#i5M2SNu)"><path class="g8b_xac5c"/></g><g filter="url(#iPqlkUc)"><path clip-rule="evenodd" class="qsb1jn3cl"/></g><path class="yu4ceub9o"/><path fill="url(#iynv1nc)" class="i2y5w5kwc"/><path class="moblz6ber"/><g filter="url(#ixcUH6c)"><path class="u14re5b_e"/><path fill="url(#iZ5xV6b)" class="u-bth2v1q"/></g><g filter="url(#iF903yc)"><path fill="url(#i6FydGb)" class="i8cqoo3sk"/></g><path class="i0to01bsp"/><path fill="url(#iKdsKvR)" class="edq1t4hqe"/><path class="s3rcurxgt"/><g filter="url(#ihheMwb)"><path fill="url(#iCuc4ke)" class="o31x6c1tf"/></g><g filter="url(#iQKUrId)"><ellipse transform="rotate(-27.938 27.529 -22.629)skewX(-.048)" class="svd-svbkr"/><ellipse fill="url(#iOjuaVn)" transform="rotate(-27.938 27.529 -22.629)skewX(-.048)" class="g4ank-byy"/></g><g filter="url(#ilEc4sb)"><path class="g91gg_b3r"/></g><g filter="url(#ivS90Qb)"><path class="x-mfarbqq"/></g><g filter="url(#iJNoFFe)"><path class="s-w09o_mq"/><path fill="url(#iO6G6Rd)" class="tk6od-bso"/></g><g filter="url(#iV11Vld)"><path class="k-6z1mbdg"/><path fill="url(#iyOGaqb)" class="ew0clacwg"/><path fill="url(#iGmbqIc)" class="ew0clacwg"/></g><g filter="url(#iSeS7RH)"><path stroke="url(#ixLLCXd)" class="fwi5vccgp"/></g><g filter="url(#iKIt0kb)"><path class="lc8cl1vop"/></g><g filter="url(#i7hCiCd)"><path fill="url(#iIBxmkc)" class="zmopp1b_s"/><path fill="url(#iQ3Iete)" class="zmopp1b_s"/></g><path fill="url(#iCFYvFZ)" class="c4gs6sabh"/><path fill="url(#idRkhGe)" class="c4gs6sabh"/><path fill="url(#ifEyoAe)" class="c4gs6sabh"/><defs><radialGradient id="imbBHNA" cx="0" cy="0" r="1" gradientTransform="matrix(-.6328 4.78117 -5.97265 -.7905 16.067 13.61)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="imb5Xlf" cx="0" cy="0" r="1" gradientTransform="matrix(-3.02346 2.03904 -2.67914 -3.97259 13.114 13.89)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iUXy3we" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37106 1.79295 -1.37673 -1.05278 11.303 11.219)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iBbL7lb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3535 2.2148 -1.56012 -.95343 11.778 9.092)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="idyu6He" cx="0" cy="0" r="1" gradientTransform="matrix(1.44138 2.74214 -3.8065 2.00086 12.692 2.535)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iyVRmId" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5116 1.5117 -2.11258 -2.11243 22.5 4.715)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="inWyNtc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93347 .5625 -1.17304 -4.0321 24.258 10.094)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="ipzSQSc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.97 8.294)scale(3.04387 3.87744)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iWcEDvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.9485 -2.77936 2.19831 -.7502 21.346 7.541)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iioSBQe" cx="0" cy="0" r="1" gradientTransform="matrix(1.57718 .16544 -.26806 2.55549 9.942 10.056)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iO0gFwA" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.737 23.145)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="ixdoJZc" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 9.143 21.488)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="iIlKuoj" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 13.6527 0 16.443 21.38)" gradientUnits="userSpaceOnUse"><stop class="xxaet9bhw"/><stop offset="1" class="zvl8nq86d"/></radialGradient><radialGradient id="iK4aaJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.435 16.926)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="ipAhZWb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 16.018 15.582)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="iApBLmc" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.768 15.348)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="cxkgc8uxn"/><stop offset="1" class="e8o_wr2lc"/></radialGradient><radialGradient id="ipJehJb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.136 21.118 2.76)scale(9.65407 14.837)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="isAnhsc" cx="0" cy="0" r="1" gradientTransform="rotate(91.544 .332 14.352)scale(4.63875 7.3062)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="q8_1e9bvu"/><stop offset="1" class="bh-nd0_an"/></radialGradient><radialGradient id="i7YQVEe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96875 -1.42188 1.19716 -2.49957 17.739 18.25)" gradientUnits="userSpaceOnUse"><stop class="qt57fac7h"/><stop offset="1" class="apl04vbcc"/></radialGradient><radialGradient id="icg4kmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -2.06 0 16.421 17.016)" gradientUnits="userSpaceOnUse"><stop class="ujwfa7bzq"/><stop offset="1" class="ocm7e7kpi"/></radialGradient><radialGradient id="izfAWBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5407 -4.26182 0 16.421 14.574)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="xr7te0bkm"/><stop offset="1" class="nkvvdv5bj"/></radialGradient><radialGradient id="i4BvFph" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 25.01 11.698)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="iNVcP3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.268 12.07)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="id9Aw6i" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.93 12.461)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="iUgHI4c" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.328 8.573)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iIep1Ab" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.768 13.137)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="iZGwOYy" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.768 16.926)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="irf74zkjs"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="iF6FEDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.44 30.026)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iwQBnuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.205 30.026)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="ijv9JYd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.547 30.026)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="iTwfjyc" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.496 23.187)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iQIku0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.6103 -1.1865 1.44866 3.18706 20.62 11.446)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iUmpN9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.37986 .77342 -.21866 .3901 21.7 9.223)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iZQDBim" cx="0" cy="0" r="1" gradientTransform="matrix(1.58345 -.11779 .09207 1.23781 20.989 11.104)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iJXKIJc" cx="0" cy="0" r="1" gradientTransform="rotate(-180 5.779 5.493)scale(1.1074)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="i9y9PSc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.82039 3.1451 -4.20966 -9.12894 19.382 10.423)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iWpIOde" cx="0" cy="0" r="1" gradientTransform="matrix(-2.28649 1.00613 -.70065 -1.59227 18.45 11.319)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iV6nt6b" cx="0" cy="0" r="1" gradientTransform="matrix(1.35195 -4.11972 5.22716 1.71537 14.116 17.247)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iF73IVc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8614 7.86032 -9.8253 -1.07674 17.245 9.387)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="f880vgbmi"/><stop offset="1" class="fhw_2qchl"/></radialGradient><radialGradient id="iiYq9fb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.24206 1.42123 -2.44691 -12.46857 18.282 12.238)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iYb4jFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.20683 1.48111 0 18.797 9.984)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iSOdVje" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37645 1.5775 0 14.206 9.744)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="ikEwJVb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91255 3.38393 -2.7077 -.73019 17.834 7.555)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="i81562p" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34789 0 0 -6.75955 21.727 11.544)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="iO21R7I" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 13.536 -.743)scale(2.19617 .67684)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iCvZL3b" cx="0" cy="0" r="1" gradientTransform="matrix(-.81737 0 0 -.22851 16.954 12.529)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iYfFd0b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.438 .98724 -1.18652 -1.72827 16.779 11.905)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="iynv1nc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85084 -1.35335 0 18.672 10.36)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iZ5xV6b" cx="0" cy="0" r="1" gradientTransform="matrix(-.24321 -.31373 .43182 -.33476 18.432 10.45)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKdsKvR" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85084 -1.35336 0 14.095 10.36)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iOjuaVn" cx="0" cy="0" r="1" gradientTransform="matrix(-.00811 -.51854 .62295 -.00975 .393 .537)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iO6G6Rd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3235 -2.88966 1.47827 .67707 10.45 8.137)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iyOGaqb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.21483 4.60537 -7.52951 -3.62112 18.387 2.676)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iGmbqIc" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 6.988 8.654)scale(1.45067 3.12103)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iIBxmkc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6722 -3.65216 4.02251 -.74037 18.968 5.975)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="l382wkm5r"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="iQ3Iete" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.02116 -7.18676 0 16.352 2.893)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="idRkhGe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.174 2.426)" gradientUnits="userSpaceOnUse"><stop class="g_-uv52uc"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="ifEyoAe" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.205 3.051)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><filter id="ixKJTpc" width="16" height="16.5" x="8.508" y="1.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1586"/></filter><filter id="iGxQyve" width="5.32" height="9.565" x="13.761" y="10.015" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".2"/></filter><filter id="ifMiy5b" width=".65" height="8.268" x="24.546" y="3.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".125"/></filter><filter id="i6l7Mnc" width="8.964" height="6.734" x="11.953" y="23.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".075"/></filter><filter id="i3bjgxd" width="1.172" height="2.394" x="13.087" y="3.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".125"/></filter><filter id="iGGHAqd" width="3.525" height="3.375" x="9.782" y="9.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1586"/></filter><filter id="iK4Dhwb" width="3.375" height="3.625" x="19.758" y="9.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1586"/></filter><filter id="is8SC0c" width="3.253" height="3.253" x="19.819" y="9.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".25"/></filter><filter id="iBtVBfc" width="2.753" height="2.753" x="10.113" y="9.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".125"/></filter><filter id="i1aLEge" width="10.687" height="11.507" x="11.04" y="5.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1586"/></filter><filter id="i4KEuAt" width="2.969" height="3.813" x="14.729" y="9.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".25"/></filter><filter id="iATGUZb" width="2.469" height="3.313" x="15.149" y="10.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".125"/></filter><filter id="i5bjy8d" width="3.138" height="1.348" x="17.381" y="9.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1586"/></filter><filter id="ipfHg1b" width="3.138" height="1.348" x="12.248" y="9.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1586"/></filter><filter id="i5M2SNu" width="2.562" height="1.136" x="12.39" y="8.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1586"/></filter><filter id="iPqlkUc" width="2.562" height="1.136" x="18.071" y="8.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1586"/></filter><filter id="ixcUH6c" width=".815" height=".721" x="17.907" y="9.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".05"/></filter><filter id="iF903yc" width=".915" height=".939" x="18.792" y="9.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".1"/></filter><filter id="ihheMwb" width="1.015" height="1.072" x="14.133" y="9.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".1"/></filter><filter id="iQKUrId" width=".948" height=".73" x="13.336" y="9.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".05"/></filter><filter id="ilEc4sb" width="2.742" height="1.397" x="17.917" y="7.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".2"/></filter><filter id="ivS90Qb" width="2.742" height="1.397" x="12.2" y="7.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".2"/></filter><filter id="iJNoFFe" width="4.478" height="4.795" x="9.739" y="3.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1586"/><feGaussianBlur result="effect2_foregroundBlur_4002_1586" stdDeviation=".2"/></filter><filter id="iV11Vld" width="9.168" height="6.04" x="13.073" y="2.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1586"/><feGaussianBlur result="effect2_foregroundBlur_4002_1586" stdDeviation=".125"/></filter><filter id="iSeS7RH" width="1.171" height="2.393" x="13.051" y="3.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".1"/></filter><filter id="iKIt0kb" width="7.167" height="3.963" x="15.56" y="4.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1586" stdDeviation=".5"/></filter><filter id="i7hCiCd" width="12.363" height="3.035" x="10.201" y="3.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1586"/></filter><linearGradient id="i8I8FQa" x1="21.305" x2="14.168" y1="3.695" y2="16.914" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="iDynBed" x1="24.125" x2="25.311" y1="8.972" y2="8.972" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="ihl1jBN" x1="25.371" x2="25.371" y1="3.739" y2="11.507" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="i2787Pb" x1="25.919" x2="23.6" y1="14.837" y2="14.837" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="iBkD9qb" x1="23.719" x2="24.594" y1="14.516" y2="14.696" gradientUnits="userSpaceOnUse"><stop class="ud98q8dic"/><stop offset="1" class="yn026ikmt"/></linearGradient><linearGradient id="ivrs4dc" x1="9.35" x2="8.924" y1="28.094" y2="28.094" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="ipTHJMc" x1="16.435" x2="16.435" y1="29.895" y2="23.461" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="iRAtKFd" x1="13.387" x2="13.959" y1="4.477" y2="5.814" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="i5qavOR" x1="9.835" x2="11.136" y1="11.077" y2="11.077" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="i8jOkBd" x1="15.399" x2="16.383" y1="12.383" y2="12.383" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="ihhugkd" x1="16.383" x2="16.383" y1="13.221" y2="12.581" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iiTM8qd" x1="16.465" x2="16.465" y1="13.194" y2="13.047" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="ixjXD9c" x1="15.267" x2="15.75" y1="14.699" y2="13.952" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="i6FydGb" x1="19.487" x2="19.158" y1="10.418" y2="10.62" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iCuc4ke" x1="14.875" x2="14.546" y1="10.417" y2="10.62" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixLLCXd" x1="13.351" x2="13.922" y1="4.486" y2="5.822" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iCFYvFZ" x1="18.205" x2="16.924" y1="3.989" y2="-.386" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-student-medium-dark" /></template>
<style>
.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.apl04vbcc {
  stop-color: var(--svg-color--5a3126, #5A3126);
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b9h3klt4n {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.49 12.113a1.126 1.126 0 1 0 0-2.253a1.126 1.126 0 0 0 0 2.253");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bh-nd0_an {
  stop-color: var(--svg-color--1c0e20, #1C0E20);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c4gs6sabh {
  d: path("M24.378 3.636H8.408c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.ci7ih6m3p {
  d: path("M25.168 11.698V2.835h-.8v8.863z");
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clg68gimn {
  stop-color: var(--svg-color--f9b72a, #F9B72A);
}

.codehtz3g {
  stop-color: var(--svg-color--db9820, #DB9820);
  stop-opacity: 0;
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.df4a3u0pu {
  d: path("M12.103 23.802c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.691z");
}

.dkiekehrz {
  fill: var(--svg-color--272528, #272528);
  d: path("M15.186 10.39c-.279-.49-.702-.877-1.613-.877c-.398 0-.783.11-1.125.387c-.282.228-.244.52-.026.628l.584.333c.683-.22 1.44-.25 2.18-.472");
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7yn8_bej {
  stop-color: var(--svg-color--57525d, #57525D);
}

.e8o_wr2lc {
  stop-color: var(--svg-color--615b67, #615B67);
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.edq1t4hqe {
  d: path("M14.093 9.86a.936.936 0 0 0-.902 1.183h1.808a1 1 0 0 0 .034-.247a.94.94 0 0 0-.94-.936");
}

.eegosnvzs {
  fill-rule: evenodd;
  d: path("M23.918 12.465a3.4 3.4 0 0 0 .34-1.496c0-.49-.1-.95-.282-1.37h.006q-.124-.285-.295-.538l-.002-.003a3.4 3.4 0 0 1-.552-1.857v-.01a3.46 3.46 0 0 0-3.46-3.46a.57.57 0 0 1-.477-.245a3.47 3.47 0 0 0-2.813-1.443a3.47 3.47 0 0 0-2.812 1.443a.6.6 0 0 1-.478.244l-.09.002a3.46 3.46 0 0 0-3.37 3.458v.01c0 .659-.19 1.306-.552 1.858l-.002.004a3.46 3.46 0 0 0-.231 3.403a.54.54 0 0 1 0 .478a3.37 3.37 0 0 0 3.035 4.85h9a3.37 3.37 0 0 0 3.375-3.375c0-.53-.127-1.03-.34-1.475a.54.54 0 0 1 0-.478M11.061 9.662h-.013l1.257 2.47c.13 2.94 1.277 0 4.078 0s4.023 3.272 4.153.333l1.19-3.353c-.055-1.305-1.001-1.397-1.19-1.397h-3.377a4.05 4.05 0 0 1-3.345-1.755a.277.277 0 0 0-.484.054l-.086.203a2.42 2.42 0 0 1-1.301 1.316q-.03.013-.054.021c-.247.129-.828.514-.85 1.51l.011.32z");
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.ew0clacwg {
  d: path("M15.75 2.816c-1.187-.262-2.254.923-2.377 1.363c1.103 3.717 3.894 3.514 6.649 3.207c1.65-.183 1.828.569 1.969.932c0-4.124-3.508-4.898-6.21-5.495z");
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f880vgbmi {
  stop-color: var(--svg-color--754456, #754456);
  stop-opacity: 0;
}

.fhw_2qchl {
  stop-color: var(--svg-color--603240, #603240);
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.fjzt4xbni {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M21.446 12.113a1.126 1.126 0 1 0 0-2.253a1.126 1.126 0 0 0 0 2.253");
}

.ft5dv1b6b {
  fill: none;
}

.fwi5vccgp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.351 4.126c.024.255.246 1.213.571 1.793");
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.fykrdyk2a {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.916 13.634c.424.226.929.356 1.467.356c.544 0 1.044-.13 1.468-.356a.21.21 0 0 1 .256.043c.06.064.082.166.022.258m-3.213-.3l3.171.273m-3.171-.274a.21.21 0 0 0-.257.045a.2.2 0 0 0-.021.257m.278-.302l-.237.274m3.45.027l-.042-.027m.042.027l-.042-.027m.042.027a2.076 2.076 0 0 1-3.491 0m3.449-.027a2.026 2.026 0 0 1-3.408 0m-.041.028l.041-.028m-.041.028l.041-.028");
}

.g_-uv52uc {
  stop-color: var(--svg-color--696070, #696070);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g4ank-byy {
  rx: 0.409px;
  ry: 0.207px;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g6oprmb2u {
  d: path("M9.205 30.026V18.239a10.97 10.97 0 0 0-3.765 8.287v3.5z");
}

.g8b_xac5c {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.82 9.123l-.005.003a.281.281 0 0 1-.289-.483l.002-.001l.003-.002l.01-.006a2 2 0 0 1 .156-.08c.103-.05.25-.113.43-.17c.356-.114.855-.21 1.393-.115a.281.281 0 0 1-.098.555a2.4 2.4 0 0 0-1.124.096a3 3 0 0 0-.478.203");
}

.g91gg_b3r {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.417 8.498c.338-.082 1.18-.04 1.742.362");
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.h5j0dmbxj {
  d: path("m15.982 10.608l-.557 1.783a.566.566 0 0 0 .546.733h.825c.386 0 .66-.372.546-.733l-.558-1.783c-.12-.395-.677-.395-.802 0");
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i0to01bsp {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.876 9.575c-.685 0-1.264.472-1.421 1.11a.287.287 0 0 0 .28.357h2.34a.24.24 0 0 0 .239-.285a1.47 1.47 0 0 0-1.438-1.182");
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.i2y5w5kwc {
  d: path("M18.674 9.86a.936.936 0 0 1 .902 1.183h-1.808a.94.94 0 0 1 .906-1.183");
}

.i8cqoo3sk {
  d: path("M19.507 10.674a.9.9 0 0 0-.242-.486l-.273.3l.123.239z");
}

.iadk84bnt {
  d: path("M11.048 9.663h.013l-.01-.279l-.011-.32c.021-.996.602-1.381.85-1.51l.053-.02l.054-.022a2.42 2.42 0 0 0 1.247-1.295l.086-.203a.277.277 0 0 1 .484-.054a4.05 4.05 0 0 0 3.345 1.755h3.377c.188 0 1.134.092 1.19 1.397l-.124 3.223c-.129 2.939-2.424 4.912-5.226 4.912s-5.096-1.973-5.226-4.912z");
}

.irf74zkjs {
  stop-color: var(--svg-color--a16739, #A16739);
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jhkgglbjb {
  d: path("M16.44 15.525c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.k-6z1mbdg {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M15.75 2.816c-1.187-.262-2.254.923-2.377 1.363c1.103 3.717 3.894 3.514 6.649 3.207c1.65-.183 1.828.569 1.969.932c0-4.124-3.508-4.898-6.21-5.495z");
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.k978n-7rf {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.972 10.754l-.717 1.783a.566.566 0 0 0 .546.733h.824c.387 0 .66-.372.546-.733l-.557-1.783c-.12-.395-.517-.395-.643 0");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l382wkm5r {
  stop-color: var(--svg-color--595260, #595260);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lc8cl1vop {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.907 6.602l-1.495.275a.722.722 0 1 1-.131-1.432h2.455c1.451 0 1.932 1.464 1.99 1.964a3.3 3.3 0 0 0-2.82-.807");
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.moblz6ber {
  fill: var(--svg-color--000, #000);
  d: path("M18.138 10.797c0-.298.238-.537.536-.537a.534.534 0 0 1 .476.784h-.949a.5.5 0 0 1-.063-.247");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mup5fmbmx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.387 4.116c.024.255.246 1.214.572 1.794");
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nkvvdv5bj {
  stop-color: var(--svg-color--582f25, #582F25);
}

.nmzhv-k6p {
  d: path("M16.09 23.802c0-.188.154-.34.345-.34s.346.152.346.34v6.093h-.692z");
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o31x6c1tf {
  d: path("M14.948 10.687c0-.303-.246-.505-.313-.566l-.302.293l.186.38z");
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o7212rbuo {
  d: path("M20.076 23.802c0-.188.154-.34.345-.34s.346.152.346.34v6.093h-.691z");
}

.ocm7e7kpi {
  stop-color: var(--svg-color--643548, #643548);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pfapn4txr {
  d: path("M21.446 12.113a1.126 1.126 0 1 0 0-2.253a1.126 1.126 0 0 0 0 2.253");
}

.pk_j5sfiy {
  stop-color: var(--svg-color--33203c, #33203C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnxjkfbgy {
  stop-color: var(--svg-color--6a656f, #6A656F);
}

.pp0bb32bq {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.58 10.39c.28-.49.702-.877 1.613-.877c.399 0 .784.11 1.125.387c.282.228.244.52.026.628l-.583.333c-.684-.22-1.44-.25-2.18-.472");
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pxnc7tbps {
  d: path("M16.141 18.896c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.197.763 1.89 1.78 2.587");
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q8_1e9bvu {
  stop-color: var(--svg-color--1c0e20, #1C0E20);
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qsb1jn3cl {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m20.297 8.643l-.145.241za.282.282 0 0 1-.29.483l-.004-.003l-.023-.013l-.096-.048a3 3 0 0 0-.359-.142a2.4 2.4 0 0 0-1.124-.096a.281.281 0 0 1-.098-.555a2.94 2.94 0 0 1 1.393.115a3.4 3.4 0 0 1 .586.25l.01.006l.003.002z");
}

.qt57fac7h {
  stop-color: var(--svg-color--714a4b, #714A4B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qyk7h_b4b {
  d: path("M23.665 30.026V18.239a10.97 10.97 0 0 1 3.765 8.287v3.5z");
}

.qz8bps8mw {
  d: path("M21.446 12.673a1.687 1.687 0 1 0 0-3.375a1.687 1.687 0 0 0 0 3.375");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rk6fry6yk {
  d: path("M11.47 12.673a1.687 1.687 0 1 0 0-3.375a1.687 1.687 0 0 0 0 3.375");
}

.s-w09o_mq {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M11.067 4.706c.593-.628 1.716-.629 2.235-.535l.415 1.353c-.265-.04-.502.053-.7.246c-.47 1.322-2.087 2.051-2.836 2.25c-.156-1.564.114-2.496.886-3.314");
}

.s3rcurxgt {
  fill: var(--svg-color--000, #000);
  d: path("M14.629 10.797a.534.534 0 0 0-.536-.537a.534.534 0 0 0-.477.784h.949a.5.5 0 0 0 .064-.247");
}

.s9wrpn8gs {
  d: path("M24.368 11.675a.838.838 0 1 0 .8 0z");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.svd-svbkr {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.409px;
  ry: 0.207px;
}

.t483lu3vu {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.871 3.74v7.767");
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tk6od-bso {
  d: path("M11.067 4.706c.593-.628 1.716-.629 2.235-.535l.415 1.353c-.265-.04-.502.053-.7.246c-.47 1.322-2.087 2.051-2.836 2.25c-.156-1.564.114-2.496.886-3.314");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u-bth2v1q {
  d: path("M18.605 10.058c.067.09-.073.198-.231.317s-.276.202-.343.113s.008-.258.166-.377c.159-.118.341-.142.408-.053");
}

.u14re5b_e {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.605 10.058c.067.09-.073.198-.231.317s-.276.202-.343.113s.008-.258.166-.377c.159-.118.341-.142.408-.053");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.ud98q8dic {
  stop-color: var(--svg-color--c57e10, #C57E10);
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.ujwfa7bzq {
  stop-color: var(--svg-color--643548, #643548);
}

.uo2hv248r {
  stop-color: var(--svg-color--75707b, #75707B);
  stop-opacity: 0;
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.uuiv6bbmv {
  stop-color: var(--svg-color--3f3748, #3F3748);
  stop-opacity: 0;
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.v4ibyebyv {
  d: path("m23.915 13.636l-.517 2.238a.45.45 0 0 0 .445.551h1.863a.45.45 0 0 0 .43-.557l-.542-2.239a.5.5 0 0 0-.485-.381h-.707a.5.5 0 0 0-.488.388");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.w-8l0wvxz {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.982 10.608l-.557 1.783a.566.566 0 0 0 .546.733h.825c.386 0 .66-.372.546-.733l-.558-1.783c-.12-.395-.677-.395-.802 0");
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wktcbebgy {
  d: path("M23.456 18.125a.24.24 0 0 0-.059-.29c-1.856-1.603-4.346-2.487-6.954-2.487s-5.113.894-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.614 7.03 4.614s5.73-2.015 7.013-4.614");
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x-mfarbqq {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.442 8.498c-.339-.082-1.18-.04-1.742.362");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xr7te0bkm {
  stop-color: var(--svg-color--582f25, #582F25);
  stop-opacity: 0;
}

.xxaet9bhw {
  stop-color: var(--svg-color--47404d, #47404D);
}

.y3arqr1oy {
  d: path("M11.49 12.113a1.126 1.126 0 1 0 0-2.253a1.126 1.126 0 0 0 0 2.253");
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.ym5q1xkkz {
  stop-color: var(--svg-color--372e41, #372E41);
}

.yn026ikmt {
  stop-color: var(--svg-color--df8f14, #DF8F14);
  stop-opacity: 0;
}

.yu4ceub9o {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.89 9.575c.686 0 1.264.472 1.421 1.11a.288.288 0 0 1-.28.357h-2.34a.24.24 0 0 1-.238-.285a1.466 1.466 0 0 1 1.438-1.182");
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.zih98ybws {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.141 18.896c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.197.763 1.89 1.78 2.587Z");
}

.ziupmvs4c {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.44 15.525c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.zmopp1b_s {
  d: path("m10.202 5.278l1.253-1.992l9.75-.11l1.36 2.063c-4.664 1.61-10.274.773-12.364.039");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zvl8nq86d {
  stop-color: var(--svg-color--3b2d3a, #3B2D3A);
}

</style>
