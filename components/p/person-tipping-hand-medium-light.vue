<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iSCzAxe)" class="vyskir3mj"/><path fill="url(#iNbgQ3c)" class="vyskir3mj"/><path fill="url(#ivDaoDb)" class="vyskir3mj"/><rect fill="url(#iS9s1wW)" class="kpd_v_kpc"/><path class="i7r9bibkr"/><path fill="url(#imUx0ye)" class="p1tkbdc7x"/><path fill="url(#iU6ZDuK)" class="p1tkbdc7x"/><path clip-rule="evenodd" class="vkd3e57mf"/><path fill="url(#iaVMkQc)" clip-rule="evenodd" class="j78powgnr"/><path fill="url(#iILq7ce)" clip-rule="evenodd" class="j78powgnr"/><path fill="url(#irzREtc)" clip-rule="evenodd" class="j78powgnr"/><path clip-rule="evenodd" class="dmn-kbo5b"/><path fill="url(#iHJS7Ae)" clip-rule="evenodd" class="q193a4dvw"/><path fill="url(#iA6T7jc)" clip-rule="evenodd" class="q193a4dvw"/><path fill="url(#iOUm2rc)" clip-rule="evenodd" class="q193a4dvw"/><path clip-rule="evenodd" class="fhkn6ac8t"/><path fill="url(#iTrGeGQ)" clip-rule="evenodd" class="th6javbzw"/><path fill="url(#ii7gLFc)" clip-rule="evenodd" class="th6javbzw"/><path fill="url(#itYRtWc)" clip-rule="evenodd" class="th6javbzw"/><g filter="url(#ias4ZJd)"><path class="e54s435pn"/><path fill="url(#i7zabld)" class="tcipjiklf"/><path fill="url(#im8yqPb)" class="tcipjiklf"/><path fill="url(#iDAOf7c)" class="tcipjiklf"/></g><path fill="url(#i1wyfFd)" class="jeropmbwt"/><path fill="url(#ieExTmf)" class="jeropmbwt"/><path fill="url(#ia3ejdc)" class="mzm9np9od"/><path fill="url(#i7ACIFe)" class="mzm9np9od"/><path fill="url(#i8xog4d)" class="mzm9np9od"/><path fill="url(#iPr0IdQ)" class="u0um7jyqb"/><path fill="url(#i9wl4Wi)" class="tf666ibuh"/><path fill="url(#iN8gxpe)" class="tf666ibuh"/><g filter="url(#i2URDYb)"><path fill="url(#idRcyXc)" class="y8051nbsf"/></g><path fill="url(#iv753Yb)" class="y8051nbsf"/><path fill="url(#iinJhEb)" class="y8051nbsf"/><path fill="url(#iSiT4SO)" class="y8051nbsf"/><path fill="url(#ikjbVmd)" class="y8051nbsf"/><path fill="url(#iFOlObb)" class="y8051nbsf"/><path fill="url(#iTL7g3d)" class="y8051nbsf"/><path fill="url(#i43jH9l)" class="y8051nbsf"/><path fill="url(#iHvcGLb)" class="y8051nbsf"/><g filter="url(#iTOYqZk)"><path class="mjbsyxpyz"/></g><g filter="url(#icgWjCb)"><path fill="url(#i6YhoDc)" class="wu4kupumw"/><path fill="url(#iSaaCae)" class="wu4kupumw"/><path fill="url(#id5tlec)" class="wu4kupumw"/><path fill="url(#iPSRSZb)" class="wu4kupumw"/></g><path fill="url(#iGnV5Hb)" class="wu4kupumw"/><path fill="url(#imRC1Kx)" class="wu4kupumw"/><g filter="url(#iVxZZ6c)"><path stroke="url(#iqjVSsc)" class="ww4pjbyqz"/></g><path fill="url(#i9rrOEb)" class="elzaa-bhj"/><g filter="url(#iu3ryrT)"><path fill="url(#i0E1rWK)" class="f12m74bbt"/><path fill="url(#i1C4Rmc)" class="f12m74bbt"/><path fill="url(#iQ51Sfc)" class="f12m74bbt"/><path fill="url(#i4e1KQd)" class="f12m74bbt"/><path fill="url(#i0QVeWb)" class="f12m74bbt"/></g><g filter="url(#i0WwgFd)"><path class="i-gw1lbsh"/></g><g filter="url(#iUfIZlc)"><path class="oxbuj3bww"/></g><g filter="url(#i1QFLOe)"><path fill="url(#iQiPEGe)" class="mfj_lacee"/><path fill="url(#ifpkXMe)" class="mfj_lacee"/></g><g filter="url(#i1qQRvc)"><path fill="url(#iJcnGBb)" class="s0vylfk_j"/><path fill="url(#inXjKzb)" class="s0vylfk_j"/><path fill="url(#iNztZ7b)" class="s0vylfk_j"/><path fill="url(#iPoUIoc)" class="s0vylfk_j"/><path fill="url(#ikpOUfc)" class="s0vylfk_j"/><path fill="url(#i2Orxyc)" class="s0vylfk_j"/></g><path class="txb2lgqjd"/><path fill="url(#i8Hb2PF)" class="y8l6mwiaq"/><path class="conzewb8o"/><g filter="url(#iE1M8ab)"><path class="fjk838b3k"/><path fill="url(#iovu1te)" class="haqmxcbaw"/></g><g filter="url(#iSCuu3c)"><path fill="url(#iTwGX4i)" class="ldbcmjzbz"/></g><path class="dt8seubxt"/><path fill="url(#iICXGEh)" class="p_klg4igl"/><path class="lk1y2ebls"/><g filter="url(#iGNLh9r)"><path fill="url(#i2srlQc)" class="g37rieffp"/></g><g filter="url(#iiSBkue)"><ellipse transform="rotate(-27.914 9.468 11.993)" class="vvojwccjz"/><ellipse fill="url(#iWNWUjc)" transform="rotate(-27.914 9.468 11.993)" class="lgnzo2b-x"/></g><path fill="url(#i6hUJXc)" class="fadrn4pnd"/><path fill="url(#iyrbUfd)" class="fadrn4pnd"/><path fill="url(#i08PIVd)" class="fadrn4pnd"/><path fill="url(#ihIte9c)" class="i8avvj25g"/><path fill="url(#irzCo6v)" class="i8avvj25g"/><g filter="url(#iyBoa9G)"><path class="qyd_7k__u"/></g><g filter="url(#iakvlUb)"><path class="u2znpdquz"/></g><g filter="url(#iaMeQhb)"><path class="ay-1tf10r"/></g><g filter="url(#iPVYuhc)"><path class="xtau7k-zo"/></g><defs><radialGradient id="iNbgQ3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.33523 -6.23448 0 12.564 19.926)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="zg4a17b1f"/><stop offset="1" class="c2hsbpb1i"/></radialGradient><radialGradient id="ivDaoDb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89737 -6.66767 3.24499 -1.89675 21.322 29.365)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="xaavtj_gl"/><stop offset="1" class="ig4trablp"/></radialGradient><radialGradient id="iS9s1wW" cx="0" cy="0" r="1" gradientTransform="rotate(61.706 -10.783 20.425)scale(4.09945 6.60646)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="pwf_-dn4s"/><stop offset=".826" class="cj0fpcchy"/></radialGradient><radialGradient id="imUx0ye" cx="0" cy="0" r="1" gradientTransform="rotate(131.424 9.028 12.008)scale(2.12546 1.04757)" gradientUnits="userSpaceOnUse"><stop class="d47_3hb-i"/><stop offset=".836" class="a3oso8z0y"/></radialGradient><radialGradient id="iU6ZDuK" cx="0" cy="0" r="1" gradientTransform="rotate(-70.927 22.338 -8.76)scale(3.10812 1.58159)" gradientUnits="userSpaceOnUse"><stop offset=".854" class="f7n3i4bhd"/><stop offset="1" class="szdg8rbev"/></radialGradient><radialGradient id="iaVMkQc" cx="0" cy="0" r="1" gradientTransform="matrix(-.89575 .18001 -.22857 -1.13739 29.82 14.053)" gradientUnits="userSpaceOnUse"><stop class="xzb70-bgi"/><stop offset="1" class="ciwrelrrj"/></radialGradient><radialGradient id="irzREtc" cx="0" cy="0" r="1" gradientTransform="rotate(83.723 6.162 22.02)scale(.39776 3.06956)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="lknsjyjnn"/><stop offset="1" class="lno0m-9jy"/></radialGradient><radialGradient id="iHJS7Ae" cx="0" cy="0" r="1" gradientTransform="matrix(-.89138 .1756 -.21889 -1.11118 30.4 14.364)" gradientUnits="userSpaceOnUse"><stop class="xzb70-bgi"/><stop offset="1" class="ciwrelrrj"/></radialGradient><radialGradient id="iOUm2rc" cx="0" cy="0" r="1" gradientTransform="matrix(.04834 .30469 -2.39683 .38026 27.96 13.913)" gradientUnits="userSpaceOnUse"><stop offset=".431" class="lknsjyjnn"/><stop offset="1" class="lno0m-9jy"/></radialGradient><radialGradient id="iTrGeGQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.89428 .16927 -.20335 -1.07433 30.117 14.824)" gradientUnits="userSpaceOnUse"><stop class="xzb70-bgi"/><stop offset="1" class="ciwrelrrj"/></radialGradient><radialGradient id="itYRtWc" cx="0" cy="0" r="1" gradientTransform="matrix(.0434 .28906 -2.36234 .35465 27.677 14.292)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="lknsjyjnn"/><stop offset="1" class="lno0m-9jy"/></radialGradient><radialGradient id="i7zabld" cx="0" cy="0" r="1" gradientTransform="rotate(169.423 13.939 9.141)scale(.90027 1.06791)" gradientUnits="userSpaceOnUse"><stop class="apy9n4beb"/><stop offset="1" class="nmfv5s6hy"/></radialGradient><radialGradient id="im8yqPb" cx="0" cy="0" r="1" gradientTransform="rotate(81.573 4.995 23.488)scale(.21324 1.76543)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="zgnc2ob4f"/><stop offset="1" class="ql8ba7bmn"/></radialGradient><radialGradient id="i1wyfFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .95313 -3.31428 0 24.286 17.276)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="buivx-bne"/><stop offset="1" class="v3bk_f4rq"/></radialGradient><radialGradient id="i7ACIFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.75 -3.6875 0 25.849 17.605)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="p69mofo0i"/><stop offset="1" class="x-u3yxwuj"/></radialGradient><radialGradient id="iPr0IdQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.54686 3.5625 -4.23198 -.64963 19.453 14.25)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="i9wl4Wi" cx="0" cy="0" r="1" gradientTransform="rotate(64.592 -8.773 11.703)scale(3.7469 1.70313)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iN8gxpe" cx="0" cy="0" r="1" gradientTransform="matrix(.22628 1.50638 -1.3214 .1985 6.574 14.348)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="idRcyXc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.59763 0 0 -11.6711 16.107 13.27)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iinJhEb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44247 16.35953 -13.54764 -1.19453 14.56 5.807)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="zgchiqbcj"/><stop offset="1" class="qz-t25gyz"/></radialGradient><radialGradient id="iSiT4SO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.69224 2.09415 0 15.652 11.856)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="ikjbVmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.07327 -1.3925 1.51537 -.07974 9.739 11.684)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iFOlObb" cx="0" cy="0" r="1" gradientTransform="matrix(1.52302 0 0 7.74116 6.404 13.755)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iTL7g3d" cx="0" cy="0" r="1" gradientTransform="rotate(-54.413 11.812 -.295)scale(5.67044 1.28436)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="i43jH9l" cx="0" cy="0" r="1" gradientTransform="matrix(-3.046 -12.92678 14.23923 -3.35526 12.37 18.41)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iHvcGLb" cx="0" cy="0" r="1" gradientTransform="matrix(2.58067 .90958 -.54565 1.54812 15.035 6.479)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="imRC1Kx" cx="0" cy="0" r="1" gradientTransform="matrix(-2.32155 2.31096 -1.46885 -1.47559 13.85 13.174)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="iqjVSsc" cx="0" cy="0" r="1" gradientTransform="matrix(.43812 -.78175 2.27492 1.27496 11.142 17.421)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="i9rrOEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.90958 3.65948 0 12.564 17.737)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i1C4Rmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58447 8.12277 0 5.964 11.274)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="iQ51Sfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58447 8.12277 0 18.698 11.274)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="i4e1KQd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1037 -1.56532 .83364 -2.18548 17.746 3.353)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="i0QVeWb" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 4.51 10.876)scale(2.18399 5.0571)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="iQiPEGe" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 6.165 2.708)scale(5.10755 1.42155)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="ifpkXMe" cx="0" cy="0" r="1" gradientTransform="matrix(4.06138 -6.43053 7.12436 4.49959 5.71 9.17)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iJcnGBb" cx="0" cy="0" r="1" gradientTransform="matrix(4.27292 1.01063 -.56521 2.3897 17.133 4.627)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="inXjKzb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71157 -4.67413 2.60673 -1.51222 19.037 10.439)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="iNztZ7b" cx="0" cy="0" r="1" gradientTransform="rotate(-120.695 11.99 -.166)scale(3.23216 2.31506)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iPoUIoc" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 9.042 3.34)scale(6.22753 6.7322)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="ikpOUfc" cx="0" cy="0" r="1" gradientTransform="matrix(-.14808 .48427 -2.21403 -.67698 16.922 4.322)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="i2Orxyc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.51717 4.7383 -12.21875 -6.49108 16.917 3.285)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="i8Hb2PF" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.0239 -1.62862 0 15.318 12.114)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iovu1te" cx="0" cy="0" r="1" gradientTransform="matrix(-.29269 -.37717 .51926 -.40295 15.029 12.22)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iICXGEh" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02395 -1.62871 0 9.81 12.114)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iWNWUjc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00976 -.62354 .74952 -.01174 9.449 12.39)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iyrbUfd" cx="0" cy="0" r="1" gradientTransform="matrix(.79322 2.83106 -2.70104 .75679 18.391 12.131)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="i08PIVd" cx="0" cy="0" r="1" gradientTransform="matrix(.9942 -1.36437 1.14361 .83333 18.846 12.819)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="irzCo6v" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1139 -.30914 .30391 -2.07816 6.36 12.944)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><linearGradient id="iSCzAxe" x1="12.564" x2="12.564" y1="29.977" y2="24.951" gradientUnits="userSpaceOnUse"><stop class="zazrfkbck"/><stop offset="1" class="lnx-x012h"/></linearGradient><linearGradient id="iILq7ce" x1="28.305" x2="27.694" y1="15.39" y2="14.18" gradientUnits="userSpaceOnUse"><stop offset=".217" class="ocrnwfbjy"/><stop offset="1" class="hc6nasj2l"/></linearGradient><linearGradient id="iA6T7jc" x1="28.719" x2="28.283" y1="15.944" y2="14.651" gradientUnits="userSpaceOnUse"><stop offset=".217" class="ocrnwfbjy"/><stop offset="1" class="hc6nasj2l"/></linearGradient><linearGradient id="ii7gLFc" x1="28.123" x2="28.005" y1="16.28" y2="15.097" gradientUnits="userSpaceOnUse"><stop offset=".217" class="ocrnwfbjy"/><stop offset="1" class="hc6nasj2l"/></linearGradient><linearGradient id="iDAOf7c" x1="20.938" x2="25.379" y1="16.702" y2="16.358" gradientUnits="userSpaceOnUse"><stop class="rmvak_xfq"/><stop offset="1" class="kzyqjmbts"/></linearGradient><linearGradient id="ieExTmf" x1="23.665" x2="23.665" y1="18.228" y2="17.968" gradientUnits="userSpaceOnUse"><stop offset=".316" class="qpac9rbcm"/><stop offset="1" class="rm84xebof"/></linearGradient><linearGradient id="ia3ejdc" x1="24.536" x2="24.536" y1="19.292" y2="38.605" gradientUnits="userSpaceOnUse"><stop class="pvy3eqxuo"/><stop offset=".621" class="l7mlu3-3a"/></linearGradient><linearGradient id="i8xog4d" x1="23.494" x2="23.494" y1="18.133" y2="19.167" gradientUnits="userSpaceOnUse"><stop offset=".366" class="kyz4h9b7r"/><stop offset="1" class="vsqt-vb2z"/></linearGradient><linearGradient id="iv753Yb" x1="19.073" x2="13.579" y1="15.397" y2="15.397" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="i6YhoDc" x1="12.564" x2="13.643" y1="14.316" y2="14.316" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iSaaCae" x1="11.21" x2="12.566" y1="14.12" y2="14.194" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="id5tlec" x1="12.564" x2="12.564" y1="14.819" y2="15.894" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iPSRSZb" x1="12.564" x2="12.564" y1="11.983" y2="12.512" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iGnV5Hb" x1="12.729" x2="12.729" y1="15.67" y2="15.596" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="i0E1rWK" x1="19.333" x2="6.556" y1="6.124" y2="6.124" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iTwGX4i" x1="16.3" x2="15.904" y1="12.182" y2="12.426" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i2srlQc" x1="10.749" x2="10.353" y1="12.182" y2="12.426" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6hUJXc" x1="20.687" x2="19.164" y1="12.216" y2="14.962" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="ihIte9c" x1="5.182" x2="7.022" y1="13.104" y2="12.944" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><filter id="ias4ZJd" width="7.879" height="3.847" x="21.44" y="13.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.545098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3798"/></filter><filter id="i2URDYb" width="13.648" height="15.775" x="6.174" y="5.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3798"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3798" result="effect2_innerShadow_4002_3798"/></filter><filter id="iTOYqZk" width="4.214" height="5.563" x="10.118" y="11.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3798" stdDeviation=".5"/></filter><filter id="icgWjCb" width="2.569" height="3.86" x="11.279" y="11.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3798" stdDeviation=".05"/></filter><filter id="iVxZZ6c" width="4.562" height="1.854" x="10.283" y="16.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3798" stdDeviation=".05"/></filter><filter id="iu3ryrT" width="16.245" height="10.415" x="4.441" y="1.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3798"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3798" result="effect2_innerShadow_4002_3798"/></filter><filter id="i0WwgFd" width="2.925" height="1.45" x="14.57" y="8.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3798"/></filter><filter id="iUfIZlc" width="2.925" height="1.431" x="7.936" y="8.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3798"/></filter><filter id="i1QFLOe" width="8.679" height="7.931" x="4.705" y="2.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3798" stdDeviation=".25"/></filter><filter id="i1qQRvc" width="8.461" height="7.674" x="12.115" y="3.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3798" stdDeviation=".25"/></filter><filter id="iE1M8ab" width=".941" height=".826" x="14.418" y="11.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3798" stdDeviation=".05"/></filter><filter id="iSCuu3c" width="1.02" height="1.048" x="15.504" y="11.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3798" stdDeviation=".1"/></filter><filter id="iGNLh9r" width="1.14" height="1.208" x="9.897" y="11.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3798" stdDeviation=".1"/></filter><filter id="iiSBkue" width="1.1" height=".837" x="8.918" y="11.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3798" stdDeviation=".05"/></filter><filter id="iyBoa9G" width="1.546" height="2.872" x="5.016" y="11.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3798" stdDeviation=".125"/></filter><filter id="iakvlUb" width="1.695" height="2.902" x="18.576" y="11.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3798" stdDeviation=".125"/></filter><filter id="iaMeQhb" width="2.839" height="1.268" x="7.932" y="8.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3798" stdDeviation=".125"/></filter><filter id="iPVYuhc" width="2.839" height="1.268" x="14.594" y="8.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3798" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-tipping-hand-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a3oso8z0y {
  stop-color: var(--svg-color--e6b086, #E6B086);
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.apy9n4beb {
  stop-color: var(--svg-color--f0c2a7, #F0C2A7);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.ay-1tf10r {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M8.307 9.725c.324-.233 1.133-.642 2.089-.481");
}

.buivx-bne {
  stop-color: var(--svg-color--ff7849, #FF7849);
}

.c2hsbpb1i {
  stop-color: var(--svg-color--c95513, #C95513);
  stop-opacity: 0;
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.ciwrelrrj {
  stop-color: var(--svg-color--f0c4a6, #F0C4A6);
  stop-opacity: 0;
}

.cj0fpcchy {
  stop-color: var(--svg-color--e59e81, #E59E81);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.conzewb8o {
  fill: var(--svg-color--000, #000);
  d: path("M14.675 12.638c0-.358.287-.645.645-.645a.642.642 0 0 1 .574.942h-1.142a.6.6 0 0 1-.077-.297");
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d47_3hb-i {
  stop-color: var(--svg-color--f2c29d, #F2C29D);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dm6t8mbjz {
  stop-color: var(--svg-color--c27b78, #C27B78);
}

.dmn-kbo5b {
  fill: var(--svg-color--eeb992, #EEB992);
  fill-rule: evenodd;
  d: path("M30.385 14.4a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693c1.02-.096 1.89-.259 2.552-.383q.25-.047.459-.084a.85.85 0 0 1 .984.69");
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dt8seubxt {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.547 11.169c-.825 0-1.521.568-1.71 1.336c-.057.22.112.43.338.43h2.815a.29.29 0 0 0 .287-.343a1.77 1.77 0 0 0-1.73-1.423");
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e54s435pn {
  fill: var(--svg-color--f0be97, #F0BE97);
  d: path("M25.752 13.906c-.33.037-.77.086-1.598.155l-.229.019c-1.06.082-2.273.177-2.466 1.345c-.2 1.203 1.183 2.141 2.832 1.954c.593-.068.866-.154 1.174-.251c.243-.076.508-.16.967-.247c.917-.102 1.759-.207 2.235-.309a.825.825 0 0 0-.346-1.613c-.37.079-1.053.167-1.874.26l-.203-1.364c-.161.014-.31.03-.492.051");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.elzaa-bhj {
  d: path("M12.564 16.926a3.8 3.8 0 0 1-1.748-.415c-.173-.088-.36.107-.25.264a2.39 2.39 0 0 0 1.998 1.068a2.39 2.39 0 0 0 1.998-1.068c.11-.163-.077-.352-.25-.264a3.8 3.8 0 0 1-1.748.415");
}

.f12m74bbt {
  d: path("M18.69 4.887a2.93 2.93 0 0 1 1.6 1.326a2.99 2.99 0 0 1-.133 3.189c-.221.325-.342.71-.342 1.103v1.5a2.2 2.2 0 0 0-.842-.34l.1-2.026a1.83 1.83 0 0 0-1.74-1.808h-1.768a3.06 3.06 0 0 1-2.791-1.82a.84.84 0 0 0-.777-.529h-1.606c-2.33 0-4.217 1.91-4.217 4.265l.039 1.94c-.32.047-.656.154-.91.333v-1.515c0-.393-.12-.778-.34-1.103a3.02 3.02 0 0 1-.181-3.087a2.96 2.96 0 0 1 1.64-1.422a3.4 3.4 0 0 0 1.747-1.4a2.935 2.935 0 0 1 3.648-1.151a1.88 1.88 0 0 0 1.506 0a3 3 0 0 1 1.151-.237c1.064 0 1.995.575 2.51 1.428c.388.643.997 1.11 1.707 1.354");
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

.f7n3i4bhd {
  stop-color: var(--svg-color--dfa377, #DFA377);
  stop-opacity: 0;
}

.fadrn4pnd {
  d: path("M18.776 14.962q.126-2.013.233-4.027a2.031 2.031 0 0 1-.233 4.027");
}

.fhkn6ac8t {
  fill: var(--svg-color--eeb992, #EEB992);
  fill-rule: evenodd;
  d: path("M30.114 14.957a.85.85 0 0 1-.773.921c-.32.028-.739.088-1.26.162l-.03.004a53 53 0 0 1-1.786.23a.85.85 0 1 1-.183-1.69c.622-.066 1.205-.149 1.73-.223l.064-.01c.491-.07.949-.134 1.317-.167a.85.85 0 0 1 .92.773");
}

.fjk838b3k {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.238 11.75c.08.107-.088.238-.279.38c-.19.143-.332.243-.412.136s.01-.31.2-.452s.41-.171.49-.064");
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g37rieffp {
  d: path("M10.837 12.506c0-.364-.296-.607-.376-.68l-.364.352l.224.456z");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
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

.haqmxcbaw {
  d: path("M15.238 11.75c.08.107-.088.238-.279.38c-.19.143-.332.243-.412.136s.01-.31.2-.452s.41-.171.49-.064");
}

.hc6nasj2l {
  stop-color: var(--svg-color--c58780, #C58780);
  stop-opacity: 0;
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
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

.i-gw1lbsh {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M17.275 9.51c-.221-.193-.478-.397-.868-.52c-.384-.12-.865-.153-1.53-.072a.35.35 0 1 0 .085.695c.607-.074.98-.035 1.235.045c.25.079.42.207.618.38a.35.35 0 0 0 .46-.528");
}

.i7r9bibkr {
  fill: var(--svg-color--d7927e, #D7927E);
  d: path("M21.44 15.679h4.015v2.016H21.44z");
}

.i8avvj25g {
  d: path("M6.186 10.924a2.031 2.031 0 0 0 .175 4.039a99 99 0 0 1-.175-4.039");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig4trablp {
  stop-color: var(--svg-color--bb2c0d, #BB2C0D);
  stop-opacity: 0;
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j78powgnr {
  fill-rule: evenodd;
  d: path("M29.807 14.071a.85.85 0 0 1-.69.985c-.147.026-.337.066-.562.112c-.653.136-1.594.332-2.606.428a.85.85 0 1 1-.16-1.692c.909-.086 1.678-.247 2.318-.38q.39-.083.716-.142a.85.85 0 0 1 .984.689");
}

.jeropmbwt {
  d: path("M21.197 17.438a.25.25 0 0 1 .25-.25h4.094a.25.25 0 0 1 .25.25v1.64h-4.594z");
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kpd_v_kpc {
  width: 4.898px;
  height: 6.68px;
  x: 10.127px;
  y: 16.898px;
  rx: 2.449px;
}

.kyz4h9b7r {
  stop-color: var(--svg-color--ff9c1d, #FF9C1D);
}

.kzyqjmbts {
  stop-color: var(--svg-color--e39e77, #E39E77);
  stop-opacity: 0;
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l7mlu3-3a {
  stop-color: var(--svg-color--ea6033, #EA6033);
}

.ldbcmjzbz {
  d: path("M16.324 12.49a1.06 1.06 0 0 0-.292-.584l-.328.36l.148.288z");
}

.lgnzo2b-x {
  cx: 9.468px;
  cy: 11.993px;
  rx: 0.492px;
  ry: 0.249px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk1y2ebls {
  fill: var(--svg-color--000, #000);
  d: path("M10.453 12.638a.64.64 0 0 0-.645-.645a.642.642 0 0 0-.574.942h1.142a.64.64 0 0 0 .077-.297");
}

.lknsjyjnn {
  stop-color: var(--svg-color--dcb18d, #DCB18D);
}

.lno0m-9jy {
  stop-color: var(--svg-color--dcb18d, #DCB18D);
  stop-opacity: 0;
}

.lnx-x012h {
  stop-color: var(--svg-color--ff732c, #FF732C);
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfj_lacee {
  d: path("M12.857 6.183a3 3 0 0 1-.083-.173a.84.84 0 0 0-.777-.528h-1.606c-2.33 0-4.217 1.91-4.217 4.265v.347c-.429-.326-.969-1.015-.969-2.13c0-1.353.987-2.036 1.616-2.472c.178-.124.327-.227.418-.32l.125-.132c.441-.468 1.227-1.302 2.6-1.666c.76-.202 1.53-.23 2.115-.2c.472.024.805.433.805.905v2.087z");
}

.mjbsyxpyz {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m12.02 12.846l-.873 2.09c-.128.476.18.954.614.954h.928c.435 0 .742-.485.614-.955l-.627-2.32c-.135-.514-.515-.283-.656.23");
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.mzm9np9od {
  d: path("M20.298 18.933a.8.8 0 0 1 .8-.8h4.791a.8.8 0 0 1 .8.8v11.044h-6.39z");
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.nmfv5s6hy {
  stop-color: var(--svg-color--f0c2a7, #F0C2A7);
  stop-opacity: 0;
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
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

.ocrnwfbjy {
  stop-color: var(--svg-color--c58780, #C58780);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.oxbuj3bww {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M8.26 9.372a3.5 3.5 0 0 1 2.195-.454a.35.35 0 1 1-.086.695a2.8 2.8 0 0 0-1.75.36a2 2 0 0 0-.116.075l-.003.003a.35.35 0 0 1-.429-.554z");
}

.p_klg4igl {
  d: path("M9.808 11.512a1.126 1.126 0 0 0-1.086 1.423h2.176q.04-.144.041-.297a1.134 1.134 0 0 0-1.131-1.126");
}

.p1tkbdc7x {
  d: path("M22.212 13.766c-.554.648-.74 1.416-.761 1.757l1.847-.101l.887-1.184c.29-.383.54-1.02-.035-1.441c-.466-.342-.945-.067-1.102.105c-.062.058-.248.245-.836.864");
}

.p69mofo0i {
  stop-color: var(--svg-color--ff9f3b, #FF9F3B);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pvy3eqxuo {
  stop-color: var(--svg-color--ff872c, #FF872C);
}

.pwf_-dn4s {
  stop-color: var(--svg-color--bf7173, #BF7173);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q193a4dvw {
  fill-rule: evenodd;
  d: path("M30.385 14.4a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693c1.02-.096 1.89-.259 2.552-.383q.25-.047.459-.084a.85.85 0 0 1 .984.69");
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.ql8ba7bmn {
  stop-color: var(--svg-color--f1bf98, #F1BF98);
  stop-opacity: 0;
}

.qpac9rbcm {
  stop-color: var(--svg-color--f05918, #F05918);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyd_7k__u {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M6.207 11.759a1.206 1.206 0 0 0 .105 2.371q-.067-1.184-.105-2.372");
}

.qz-t25gyz {
  stop-color: var(--svg-color--b36e91, #B36E91);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rm84xebof {
  stop-color: var(--svg-color--f05918, #F05918);
  stop-opacity: 0;
}

.rmvak_xfq {
  stop-color: var(--svg-color--e39e77, #E39E77);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.s0vylfk_j {
  d: path("m19.142 10.439l-.036-.797c-.014-.963-.81-1.758-1.774-1.799h-1.767a3.06 3.06 0 0 1-2.68-1.59s-.153-.352-.25-.913c-.17-.988.746-1.717 1.736-1.552c1.324.22 2.95.649 4.114 1.408c2.202 1.436 1.816 4.024.657 5.243");
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.szdg8rbev {
  stop-color: var(--svg-color--dfa377, #DFA377);
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.tcipjiklf {
  d: path("M25.752 13.906c-.33.037-.77.086-1.598.155l-.229.019c-1.06.082-2.273.177-2.466 1.345c-.2 1.203 1.183 2.141 2.832 1.954c.593-.068.866-.154 1.174-.251c.243-.076.508-.16.967-.247c.917-.102 1.759-.207 2.235-.309a.825.825 0 0 0-.346-1.613c-.37.079-1.053.167-1.874.26l-.203-1.364c-.161.014-.31.03-.492.051");
}

.tf666ibuh {
  d: path("M6.429 14.847a2.07 2.07 0 0 1-1.142-.389v1.175c0 1.127.672 2.131 1.693 2.548a5.2 5.2 0 0 1-.437-1.49z");
}

.th6javbzw {
  fill-rule: evenodd;
  d: path("M30.114 14.957a.85.85 0 0 1-.773.921c-.32.028-.739.088-1.26.162l-.03.004a53 53 0 0 1-1.786.23a.85.85 0 1 1-.183-1.69c.622-.066 1.205-.149 1.73-.223l.064-.01c.491-.07.949-.134 1.317-.167a.85.85 0 0 1 .92.773");
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.txb2lgqjd {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.582 11.169c.824 0 1.52.568 1.71 1.336a.346.346 0 0 1-.339.43h-2.815a.29.29 0 0 1-.287-.343a1.764 1.764 0 0 1 1.73-1.423");
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u0um7jyqb {
  d: path("M18.699 14.847a2.07 2.07 0 0 0 1.142-.389v1.175a2.74 2.74 0 0 1-1.693 2.548q.324-.688.437-1.49z");
}

.u2znpdquz {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M18.826 14.14q.074-1.2.14-2.401a1.206 1.206 0 0 1-.14 2.402");
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

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v3bk_f4rq {
  stop-color: var(--svg-color--f3632f, #F3632F);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vkd3e57mf {
  fill: var(--svg-color--eeb992, #EEB992);
  fill-rule: evenodd;
  d: path("M29.807 14.071a.85.85 0 0 1-.69.985c-.147.026-.337.066-.562.112c-.653.136-1.594.332-2.606.428a.85.85 0 1 1-.16-1.692c.909-.086 1.678-.247 2.318-.38q.39-.083.716-.142a.85.85 0 0 1 .984.689");
}

.vsqt-vb2z {
  stop-color: var(--svg-color--ff9c1d, #FF9C1D);
  stop-opacity: 0;
}

.vvojwccjz {
  cx: 9.468px;
  cy: 11.993px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.492px;
  ry: 0.249px;
}

.vyskir3mj {
  d: path("M12.564 19.926c-5.523 0-10 4.477-10 10v.05h20v-.05c0-5.523-4.477-10-10-10");
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wu4kupumw {
  d: path("m12.082 12.368l-.671 2.32c-.137.477.191.955.657.955h.992c.466 0 .794-.485.657-.955l-.67-2.32c-.144-.514-.815-.514-.966 0");
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.ww4pjbyqz {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M10.85 16.445a3.7 3.7 0 0 0 1.714.406a3.7 3.7 0 0 0 1.714-.406a.27.27 0 0 1 .319.052a.25.25 0 0 1 .028.32l-.063-.042a2.39 2.39 0 0 1-1.998 1.068a2.39 2.39 0 0 1-1.998-1.068zm0 0a.27.27 0 0 0-.32.055a.25.25 0 0 0-.026.317z");
}

.x-u3yxwuj {
  stop-color: var(--svg-color--ff9f3b, #FF9F3B);
  stop-opacity: 0;
}

.xaavtj_gl {
  stop-color: var(--svg-color--bb2c0d, #BB2C0D);
}

.xtau7k-zo {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.058 9.667c-.324-.233-1.133-.642-2.089-.481");
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.xzb70-bgi {
  stop-color: var(--svg-color--f0c4a6, #F0C4A6);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y8051nbsf {
  d: path("M6.475 16.76a4.94 4.94 0 0 0 4.904 4.298h2.38a4.94 4.94 0 0 0 4.904-4.299c.15-2.377.299-4.744.41-7.12a1.83 1.83 0 0 0-1.74-1.808h-1.768a3.06 3.06 0 0 1-2.791-1.82a.84.84 0 0 0-.776-.529H10.39c-2.33 0-4.217 1.91-4.217 4.265c0 2.348.147 4.658.3 7.012");
}

.y8l6mwiaq {
  d: path("M15.32 11.512a1.126 1.126 0 0 1 1.086 1.423H14.23a1.13 1.13 0 0 1 1.09-1.423");
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
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

.zazrfkbck {
  stop-color: var(--svg-color--f6563d, #F6563D);
}

.zg4a17b1f {
  stop-color: var(--svg-color--c95513, #C95513);
}

.zgchiqbcj {
  stop-color: var(--svg-color--b36e91, #B36E91);
  stop-opacity: 0;
}

.zgnc2ob4f {
  stop-color: var(--svg-color--d8a983, #D8A983);
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

</style>
