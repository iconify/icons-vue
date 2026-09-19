<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#isHCR3b)"><path fill="url(#i5TOwQc)" clip-rule="evenodd" class="bc9553qxg"/><path fill="url(#iyR1Xoe)" clip-rule="evenodd" class="bc9553qxg"/><path fill="url(#iaHzZDd)" clip-rule="evenodd" class="bc9553qxg"/><path fill="url(#irAo9ne)" clip-rule="evenodd" class="bc9553qxg"/><path fill="url(#iwtQA0c)" clip-rule="evenodd" class="bc9553qxg"/><path fill="url(#iQ9FW8b)" clip-rule="evenodd" class="bc9553qxg"/><path fill="url(#iRlcK8b)" clip-rule="evenodd" class="bc9553qxg"/><path fill="url(#id8Cdbc)" clip-rule="evenodd" class="bc9553qxg"/><path fill="url(#iFVZyFc)" clip-rule="evenodd" class="bc9553qxg"/><path fill="url(#i89avlc)" clip-rule="evenodd" class="bc9553qxg"/><path fill="url(#iedwNMe)" clip-rule="evenodd" class="bc9553qxg"/></g><path fill="url(#iOkOgyA)" clip-rule="evenodd" class="bc9553qxg"/><path fill="url(#ihQi12b)" class="n6d_jnr9j"/><path fill="url(#ikQH8cb)" class="n6d_jnr9j"/><path fill="url(#iNUvqbF)" class="kcmmk5bxb"/><path fill="url(#iZIIgrd)" class="kcmmk5bxb"/><path fill="url(#iLkQkbd)" class="kcmmk5bxb"/><path fill="url(#iecRI9d)" class="w78c_mbga"/><path fill="url(#iDsAFBc)" class="w78c_mbga"/><path fill="url(#iSPlgje)" class="w78c_mbga"/><path fill="url(#ic2fKLc)" class="w78c_mbga"/><path fill="url(#ijG4gop)" class="e304mibzr"/><path fill="url(#ir2U4mb)" class="e304mibzr"/><path fill="url(#i0MLaVu)" class="e304mibzr"/><path fill="url(#iFO9tQd)" class="e304mibzr"/><path fill="url(#iyormFc)" class="pyjhqsreq"/><path fill="url(#ipazNNu)" class="pyjhqsreq"/><path fill="url(#ilpixmr)" class="vl7hh0bdy"/><path fill="url(#iGSKt5b)" class="vl7hh0bdy"/><path fill="url(#i6ChNFc)" class="vl7hh0bdy"/><path fill="url(#iHkgS9c)" class="vl7hh0bdy"/><path fill="url(#iirUCfe)" class="vl7hh0bdy"/><g filter="url(#ipawIYQ)"><path clip-rule="evenodd" class="ndc_njleh"/></g><g filter="url(#iMDKlDd)"><path fill="url(#iAhj8Hn)" clip-rule="evenodd" class="lnf03fndg"/></g><path fill="url(#iB6tLsc)" clip-rule="evenodd" class="lnf03fndg"/><path fill="url(#ifi30ue)" clip-rule="evenodd" class="lnf03fndg"/><path fill="url(#iRI4m7h)" clip-rule="evenodd" class="lnf03fndg"/><path fill="url(#iolaald)" clip-rule="evenodd" class="lnf03fndg"/><g filter="url(#ifGNdKt)"><path fill="url(#i6Drnqr)" clip-rule="evenodd" class="xdencea7s"/><path fill="url(#iGD15Bd)" clip-rule="evenodd" class="xdencea7s"/></g><circle fill="url(#iPmHRmc)" transform="matrix(-1 0 0 1 19.557 19.986)" class="ean9ofhjo"/><circle fill="url(#ianTTFc)" transform="matrix(-1 0 0 1 19.557 19.986)" class="ean9ofhjo"/><circle fill="url(#ihF3OKd)" transform="matrix(-1 0 0 1 19.057 21.744)" class="ean9ofhjo"/><circle fill="url(#iUtrbGD)" transform="matrix(-1 0 0 1 19.057 21.744)" class="ean9ofhjo"/><circle fill="url(#ixjPQUb)" transform="matrix(-1 0 0 1 17.792 23.111)" class="ean9ofhjo"/><circle fill="url(#ikD1Ide)" transform="matrix(-1 0 0 1 17.792 23.111)" class="ean9ofhjo"/><circle fill="url(#isuVgPF)" transform="matrix(-1 0 0 1 17.792 23.111)" class="ean9ofhjo"/><g filter="url(#ixDoI8d)"><circle fill="url(#iuTMqgc)" class="g6hzctbpu"/><circle fill="url(#iMTto5b)" class="g6hzctbpu"/><circle fill="url(#ibKaeAo)" class="g6hzctbpu"/></g><g filter="url(#i65FLeb)"><circle fill="url(#izwboXE)" class="oo7p4ebqa"/><circle fill="url(#ijSHste)" class="oo7p4ebqa"/><circle fill="url(#iqdo5md)" class="oo7p4ebqa"/><circle fill="url(#iRxLk5d)" class="oo7p4ebqa"/></g><g filter="url(#i7RXP8o)"><circle fill="url(#iY7ZVWc)" class="n0x7ebc8c"/><circle fill="url(#ibnwHYt)" class="n0x7ebc8c"/><circle fill="url(#iMGUs4b)" class="n0x7ebc8c"/><circle fill="url(#ie2nM2s)" class="n0x7ebc8c"/></g><g filter="url(#iTeIzMe)"><circle fill="url(#iHzkxde)" class="dvuac4bxb"/><circle fill="url(#i7dGJyb)" class="dvuac4bxb"/><circle fill="url(#iR45lBb)" class="dvuac4bxb"/></g><rect fill="url(#iGml8od)" class="na-ss_5-a"/><rect fill="url(#iCV6YQc)" class="na-ss_5-a"/><rect fill="url(#inVVc6c)" class="na-ss_5-a"/><rect fill="url(#iVpFDhc)" class="na-ss_5-a"/><g filter="url(#irdT0yb)"><path fill="url(#iJ4hJwd)" class="crmkq1bkv"/></g><g filter="url(#iPRqU5b)"><path fill="url(#i8DtAQb)" class="mdrb42i-j"/></g><g filter="url(#ipYujAa)"><path class="nwobqib-i"/><path fill="url(#iFOsRlc)" class="nm_1c1iwo"/></g><g filter="url(#iCrpM6T)"><path class="wb_af7khf"/><path fill="url(#ijYP2sE)" class="cvioaxb2i"/></g><g filter="url(#iArAeLc)"><path fill="url(#iBfpkub)" class="ntwcd8zlo"/><path fill="url(#i9YKxTd)" class="ntwcd8zlo"/><path fill="url(#idpssln)" class="ntwcd8zlo"/><path fill="url(#iI4Zfke)" class="ntwcd8zlo"/><path fill="url(#iWClMse)" class="ntwcd8zlo"/><path fill="url(#iVYItod)" class="ntwcd8zlo"/><path fill="url(#iOtVtzb)" class="ntwcd8zlo"/></g><path fill="url(#isftNyE)" class="ntwcd8zlo"/><g filter="url(#iEHJT3d)"><path class="d4jxbbblw"/></g><g filter="url(#iOSMQFd)"><path fill="url(#iSNacab)" class="s89mhhmgh"/><path fill="url(#iAFxLQb)" class="s89mhhmgh"/><path fill="url(#ixlHEyd)" class="s89mhhmgh"/><path fill="url(#imCI9Le)" class="s89mhhmgh"/></g><g filter="url(#itn41Zc)"><path fill="url(#i1WgKKd)" class="n-b8_boqs"/></g><g filter="url(#iNzdj7d)"><path stroke="url(#isHtdud)" class="ocxer-jqp"/></g><path class="n_afmtc4c"/><g filter="url(#i06gUYc)"><path class="seaqufnpd"/></g><g filter="url(#iQvs1Kj)"><path class="sj2nsghkd"/></g><g filter="url(#iwv095u)"><path class="m_5d6hb0c"/></g><g filter="url(#ip3jckn)"><path clip-rule="evenodd" class="m_skw-bxy"/></g><path class="uf34-63ve"/><path fill="url(#iIbaHtd)" class="l33ghubim"/><path class="sof-msbva"/><g filter="url(#i05t7rc)"><path class="vfm2rzgjx"/><path fill="url(#iOiMnYc)" class="m3myxqzyl"/></g><g filter="url(#i7cgtle)"><path fill="url(#i9gBkmd)" class="lcvm_qpfm"/></g><path class="bzq8zz4vu"/><path fill="url(#iLpQvee)" class="n38djt95v"/><path class="bii2ynb3s"/><g filter="url(#ix9xGJc)"><path fill="url(#ijiCYrl)" class="f82r22d5b"/></g><g filter="url(#ijs3eUd)"><ellipse transform="rotate(-27.914 13.533 13.9)" class="rz5s1rb1a"/><ellipse fill="url(#ig1Y6LD)" transform="rotate(-27.914 13.533 13.9)" class="as-4qhbhd"/></g><g filter="url(#i2Jb4Ne)"><path stroke="url(#iDQp3ve)" class="vdftvkb9c"/></g><g filter="url(#icLU91y)"><path stroke="url(#i9VXaue)" class="pyzsv8yjt"/></g><g filter="url(#imQuFwd)"><path fill="url(#i82t0Uc)" class="u4-2g8brb"/><path fill="url(#iPCSHub)" class="u4-2g8brb"/></g><g filter="url(#iK2SM5c)"><path fill="url(#ibSc8Jd)" class="z5oaikbwd"/><path fill="url(#imiOLHc)" class="z5oaikbwd"/><path fill="url(#iB5WdUb)" class="z5oaikbwd"/></g><g filter="url(#iwToAIe)"><path stroke="url(#i4KufPG)" class="sdv8mxbuo"/></g><g filter="url(#iU1A1Ac)"><path fill="url(#iYxXJcd)" class="kqli1w19h"/></g><circle fill="url(#icRhpDc)" class="q8l1y6b0l"/><circle fill="url(#iHrU68c)" class="q8l1y6b0l"/><circle fill="url(#iNlnbTb)" class="eb4-yylgr"/><g filter="url(#iuO7tAe)"><path fill="url(#iUZ7Ske)" class="fus8l7b8h"/><path fill="url(#iVERpqe)" class="fus8l7b8h"/></g><path fill="url(#iw9QqUc)" class="cm8_bn2mq"/><path fill="url(#iBqn1xd)" class="cm8_bn2mq"/><path fill="url(#iwacREz)" class="cm8_bn2mq"/><g filter="url(#iyCBHNQ)"><circle fill="url(#ic9SDUc)" class="mxq0h6ljd"/><circle fill="url(#iQiXRXd)" class="mxq0h6ljd"/></g><g filter="url(#iMao5Pd)"><circle fill="url(#iDI5g0V)" class="uegyi0cvz"/><circle fill="url(#i53KubP)" class="uegyi0cvz"/></g><g filter="url(#i8w3UBc)"><path fill="url(#iEEEWSb)" class="ork4wvyzn"/><path fill="url(#iWRW5Zd)" class="ork4wvyzn"/><path fill="url(#ieWHizW)" class="ork4wvyzn"/><path fill="url(#iS293Ii)" class="ork4wvyzn"/><path fill="url(#ihSSm7d)" class="ork4wvyzn"/><path fill="url(#iBw0BYb)" class="ork4wvyzn"/><path fill="url(#ifeMfDb)" class="ork4wvyzn"/><path fill="url(#i2zYdYc)" class="ork4wvyzn"/></g><g filter="url(#iFjOMnb)"><circle fill="url(#iLXcHqh)" class="p_2ayxqss"/><circle fill="url(#igkdmBc)" class="p_2ayxqss"/></g><g filter="url(#iumELri)"><circle fill="url(#ifS1TEd)" class="rdlsi4esi"/><circle fill="url(#iJksjXb)" class="rdlsi4esi"/></g><g filter="url(#iZzqEUc)"><circle class="h88_-5b3g"/></g><g filter="url(#iCC4SCc)"><circle class="lbkb08b7q"/></g><g filter="url(#imYChWb)"><circle class="a6mi8bcxq"/></g><g filter="url(#id1p5uG)"><circle fill="url(#iXdhh3D)" class="rqzct4dku"/><circle fill="url(#iH9PggR)" class="rqzct4dku"/></g><g filter="url(#icTm1Ct)"><circle fill="url(#iHcrFqe)" class="b6nn4d4lh"/></g><g filter="url(#iH7Odpb)"><circle fill="url(#iNmQTwe)" class="xruj5pnln"/></g><g filter="url(#iGKXWtc)"><path stroke="url(#iYpqpOA)" class="re4dv2b7j"/></g><g filter="url(#imMgy4c)"><circle fill="url(#iD4RU4b)" class="uo29cubui"/><circle fill="url(#iEeNFte)" class="uo29cubui"/></g><defs><radialGradient id="iyR1Xoe" cx="0" cy="0" r="1" gradientTransform="rotate(28.301 -25.576 48.232)scale(3.18955 4.51784)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="iaHzZDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.45645 -2.68487 0 11.41 16.623)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="irAo9ne" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.57099 -5.8032 0 15.987 16.718)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="iwtQA0c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24075 1.61016 -1.56338 -1.2047 11.076 14.913)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iQ9FW8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.46758 2.51377 -2.61762 -.4869 11.667 12.476)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="iRlcK8b" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 .216 14.117)scale(2.38097 4.53569)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="id8Cdbc" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 8.797 9.149)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="iFVZyFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.496 13.74)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="i89avlc" cx="0" cy="0" r="1" gradientTransform="rotate(-133.315 15.452 6.092)scale(4.66215 6.69539)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="iedwNMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00843 -1.37436 .45061 -.00276 13.282 9.924)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="iOkOgyA" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.54172 -11.4922 0 15.987 13.573)" gradientUnits="userSpaceOnUse"><stop offset=".854" class="p3t2yk0_n"/><stop offset=".967" class="g27slhbqh"/></radialGradient><radialGradient id="ihQi12b" cx="0" cy="0" r="1" gradientTransform="matrix(.41273 -1.93102 2.1235 .45387 5.646 29.99)" gradientUnits="userSpaceOnUse"><stop class="g049h7flb"/><stop offset="1" class="hoqi9e01c"/></radialGradient><radialGradient id="iNUvqbF" cx="0" cy="0" r="1" gradientTransform="matrix(.40626 2.08282 -3.53623 .68974 25.776 28.73)" gradientUnits="userSpaceOnUse"><stop class="k5zu23s6k"/><stop offset="0" class="bp0jotlxe"/><stop offset="1" class="z54rox6ux"/></radialGradient><radialGradient id="iZIIgrd" cx="0" cy="0" r="1" gradientTransform="matrix(.153 1.2035 -2.47782 .31501 25.009 28.28)" gradientUnits="userSpaceOnUse"><stop offset=".812" class="cunr-1bwb"/><stop offset=".95" class="yind2xb3b"/></radialGradient><radialGradient id="iecRI9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.41638 0 8.4 28.49)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="jypakik4k"/><stop offset="1" class="spc75r5za"/></radialGradient><radialGradient id="iDsAFBc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65087 -5.32423 3.75234 -1.16348 7.152 27.94)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="z_f48dbjf"/><stop offset="1" class="mjrstybho"/></radialGradient><radialGradient id="iSPlgje" cx="0" cy="0" r="1" gradientTransform="matrix(-.31987 0 0 -6.06796 8.41 25.857)" gradientUnits="userSpaceOnUse"><stop offset=".323" class="kf6yzhcxx"/><stop offset="1" class="if8ggt7lg"/></radialGradient><radialGradient id="ic2fKLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.37502 3.78125 -4.19096 -.41565 7.463 25.52)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="jhbwcacjr"/><stop offset="1" class="lxwln9mzq"/></radialGradient><radialGradient id="ijG4gop" cx="0" cy="0" r="1" gradientTransform="matrix(4.71875 -5.90625 1.33451 1.0662 23.995 28.584)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="lkxhe0bym"/><stop offset="1" class="zn9diyb1a"/></radialGradient><radialGradient id="ir2U4mb" cx="0" cy="0" r="1" gradientTransform="matrix(2.6562 6.25003 -5.11847 2.1753 23.495 23.052)" gradientUnits="userSpaceOnUse"><stop class="k3jt88b8m"/><stop offset=".783" class="k3jt88b8m"/><stop offset="1" class="t70q9k_cc"/></radialGradient><radialGradient id="i0MLaVu" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 0 0 8.2125 23.37 27.709)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="lqhq5vk7o"/><stop offset="1" class="axbh60bsz"/></radialGradient><radialGradient id="iFO9tQd" cx="0" cy="0" r="1" gradientTransform="matrix(4.625 -4.96875 2.03088 1.89038 22.65 23.74)" gradientUnits="userSpaceOnUse"><stop class="rlxb2vbdo"/><stop offset="1" class="h55xk6bmz"/></radialGradient><radialGradient id="ipazNNu" cx="0" cy="0" r="1" gradientTransform="matrix(-3.51563 0 0 -10.7812 23.635 26.459)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="toy3i-56q"/><stop offset="1" class="a3n886b5x"/></radialGradient><radialGradient id="ilpixmr" cx="0" cy="0" r="1" gradientTransform="matrix(-6.28125 0 0 -5.36523 21.588 22.521)" gradientUnits="userSpaceOnUse"><stop class="xhgokzbln"/><stop offset="1" class="myoa1jb6u"/></radialGradient><radialGradient id="iGSKt5b" cx="0" cy="0" r="1" gradientTransform="rotate(-137.291 13.972 10.311)scale(6.08156 10.1177)" gradientUnits="userSpaceOnUse"><stop class="sm9o6zbbb"/><stop offset="1" class="hqnr5ybwo"/></radialGradient><radialGradient id="i6ChNFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.71875 -2.14693 0 16.048 21.084)" gradientUnits="userSpaceOnUse"><stop offset=".345" class="g-wnk0-1g"/><stop offset="1" class="xqubvtkdv"/></radialGradient><radialGradient id="iHkgS9c" cx="0" cy="0" r="1" gradientTransform="rotate(147.829 4.211 11.914)scale(2.28894 1.32268)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="mlgod1b5x"/><stop offset="1" class="yws01behm"/></radialGradient><radialGradient id="iirUCfe" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 .42188 -.21565 .65493 18.23 20.146)" gradientUnits="userSpaceOnUse"><stop class="p6-ozrb_x"/><stop offset="1" class="kol_e4bkv"/></radialGradient><radialGradient id="ifi30ue" cx="0" cy="0" r="1" gradientTransform="matrix(4.55232 5.22072 -.2143 .18687 10.393 21.734)" gradientUnits="userSpaceOnUse"><stop class="bmln26pap"/><stop offset="1" class="yb1xaiemt"/></radialGradient><radialGradient id="iRI4m7h" cx="0" cy="0" r="1" gradientTransform="rotate(122.137 5.436 17.063)scale(.71964 .79411)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="vfe9g3b6u"/><stop offset="1" class="kth1ncger"/></radialGradient><radialGradient id="iolaald" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.62442 -16.4807 0 15.992 22.99)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="uzx-du17j"/><stop offset="1" class="sbez_4byf"/></radialGradient><radialGradient id="i6Drnqr" cx="0" cy="0" r="1" gradientTransform="rotate(-114.094 15.95 6.338)scale(5.39834 13.3444)" gradientUnits="userSpaceOnUse"><stop class="imiwjlbuv"/><stop offset="1" class="q8k_nsb5l"/></radialGradient><radialGradient id="iPmHRmc" cx="0" cy="0" r="1" gradientTransform="rotate(24.193 -1.558 .6)scale(1.18194)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="pmg10qb6b"/><stop offset="1" class="q-wkihbps"/></radialGradient><radialGradient id="ianTTFc" cx="0" cy="0" r="1" gradientTransform="rotate(26.328 -1.599 1.184)scale(1.69104)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="fkfx3o27i"/><stop offset="1" class="voqk07baz"/></radialGradient><radialGradient id="ihF3OKd" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 .59375 -.52749 .58302 .469 .637)" gradientUnits="userSpaceOnUse"><stop class="ls12e09pb"/><stop offset="1" class="tfsbwvbnl"/></radialGradient><radialGradient id="iUtrbGD" cx="0" cy="0" r="1" gradientTransform="rotate(17.956 -3.342 1.542)scale(1.7739 2.2924)" gradientUnits="userSpaceOnUse"><stop offset=".485" class="ceou1rsni"/><stop offset="1" class="tknr5ybzo"/></radialGradient><radialGradient id="ixjPQUb" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .57812 -.5501 .66904 .563 .832)" gradientUnits="userSpaceOnUse"><stop class="z9cu3vbra"/><stop offset="1" class="t2krvpb6g"/></radialGradient><radialGradient id="ikD1Ide" cx="0" cy="0" r="1" gradientTransform="rotate(-124.498 1.26 .614)scale(1.07592)" gradientUnits="userSpaceOnUse"><stop class="biu9whxny"/><stop offset="1" class="eh1sqyczn"/></radialGradient><radialGradient id="isuVgPF" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 -.0625 .06517 1.79228 .39 1.254)" gradientUnits="userSpaceOnUse"><stop offset=".541" class="kr7xbubfl"/><stop offset=".978" class="ftn-nj88l"/></radialGradient><radialGradient id="iuTMqgc" cx="0" cy="0" r="1" gradientTransform="rotate(150.945 4.004 11.562)scale(1.93043)" gradientUnits="userSpaceOnUse"><stop offset=".105" class="oj0sgcj4p"/><stop offset="1" class="eapmb-b-r"/></radialGradient><radialGradient id="iMTto5b" cx="0" cy="0" r="1" gradientTransform="matrix(1.08593 -.28907 .36133 1.35742 11.784 20.201)" gradientUnits="userSpaceOnUse"><stop class="vavjlxdpa"/><stop offset="1" class="o8dw4p7vp"/></radialGradient><radialGradient id="ibKaeAo" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.58594 1.12396 -.38964 12.745 21.03)" gradientUnits="userSpaceOnUse"><stop class="n6j5avbvg"/><stop offset="1" class="pj5su6bsv"/></radialGradient><radialGradient id="izwboXE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03125 .53906 -.49728 -.95134 13.245 21.584)" gradientUnits="userSpaceOnUse"><stop class="rr9pqccyi"/><stop offset="1" class="j-hgq5bil"/></radialGradient><radialGradient id="ijSHste" cx="0" cy="0" r="1" gradientTransform="rotate(-90 17.69 5.054)scale(1.30078)" gradientUnits="userSpaceOnUse"><stop class="xjhzw6b4m"/><stop offset="1" class="vlr1jy-qw"/></radialGradient><radialGradient id="iqdo5md" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 -.32812 .45767 -.741 13.659 22.81)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="da38a73_c"/><stop offset="1" class="kijt7rb5s"/></radialGradient><radialGradient id="iRxLk5d" cx="0" cy="0" r="1" gradientTransform="rotate(16.869 -67.097 54.03)scale(1.26538)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="d7gnwkbua"/><stop offset="1" class="xg0mdnbqj"/></radialGradient><radialGradient id="iY7ZVWc" cx="0" cy="0" r="1" gradientTransform="rotate(144.31 3.603 13.786)scale(1.36591)" gradientUnits="userSpaceOnUse"><stop class="fg8vwkbfq"/><stop offset="1" class="kqlr11b-y"/><stop offset="1" class="gsgx-m-kb"/></radialGradient><radialGradient id="ibnwHYt" cx="0" cy="0" r="1" gradientTransform="matrix(2 -.98437 1.00596 2.04386 13.573 23.443)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="fga1l482e"/><stop offset="1" class="owyqbq1bg"/></radialGradient><radialGradient id="iMGUs4b" cx="0" cy="0" r="1" gradientTransform="rotate(69.444 -9.015 21.41)scale(2.0025 1.86717)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="cy4ujdbiq"/><stop offset=".942" class="esixkvbpd"/></radialGradient><radialGradient id="ie2nM2s" cx="0" cy="0" r="1" gradientTransform="matrix(-.48437 -.0547 .10997 -.97398 15.159 23.49)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="u-wvucrhg"/><stop offset="1" class="yidq71bjl"/></radialGradient><radialGradient id="iHzkxde" cx="0" cy="0" r="1" gradientTransform="rotate(144.31 4.424 14.318)scale(1.36591)" gradientUnits="userSpaceOnUse"><stop class="xf3nhjbpw"/><stop offset="1" class="kqlr11b-y"/></radialGradient><radialGradient id="i7dGJyb" cx="0" cy="0" r="1" gradientTransform="rotate(-142.172 12.357 9.09)scale(1.68149 1.71836)" gradientUnits="userSpaceOnUse"><stop offset=".472" class="xpqto8b3q"/><stop offset="1" class="gag6ovb3k"/></radialGradient><radialGradient id="iR45lBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.64062 1.9375 -1.79684 -.5941 16.276 22.85)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="fr4aurb9m"/><stop offset=".904" class="fpyoctiow"/></radialGradient><radialGradient id="iVpFDhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.07812 -2.78906 0 16.003 19.936)" gradientUnits="userSpaceOnUse"><stop offset=".823" class="fxwj7ynbm"/><stop offset=".963" class="lt46jsbwc"/></radialGradient><radialGradient id="i8DtAQb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.026 15.032)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iFOsRlc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 51.714 -50.068)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="ijYP2sE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07411 0 0 -1.02745 11.32 14.592)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iBfpkub" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.88 9.095)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="i9YKxTd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.887 14.752)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="idpssln" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.808 20.837)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iI4Zfke" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.17887 -11.402 0 15.725 13.571)" gradientUnits="userSpaceOnUse"><stop offset=".696" class="ajxs5ri3z"/><stop offset="1" class="dswnxcbqg"/></radialGradient><radialGradient id="iWClMse" cx="0" cy="0" r="1" gradientTransform="matrix(-5.42256 1.49953 -2.58173 -9.33598 16.614 15.711)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="iVYItod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.288 13.636)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iOtVtzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.069 13.724)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="isftNyE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.082 15.124)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iAFxLQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.771 15.85)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iIbaHtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.169 13.995)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iOiMnYc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.418 2.646)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLpQvee" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.805 13.995)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ig1Y6LD" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.518 14.214)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i82t0Uc" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 4.836 6.946)scale(5.36951 2.34181)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="iPCSHub" cx="0" cy="0" r="1" gradientTransform="rotate(144.458 5.254 6.198)scale(3.81321 1.88454)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="ibSc8Jd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18534 4.55504 -6.4674 -3.10282 17.778 6.467)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="imiOLHc" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 6.334 10.84)scale(3.44004 7.20923)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iB5WdUb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.41682 -6.46744 5.78149 -3.05443 17.136 13.352)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><radialGradient id="icRhpDc" cx="0" cy="0" r="1" gradientTransform="rotate(117.967 9.13 10.283)scale(1.06405 1.3957)" gradientUnits="userSpaceOnUse"><stop offset=".265" class="dakdtmo8r"/><stop offset="1" class="arn54kl4j"/></radialGradient><radialGradient id="iHrU68c" cx="0" cy="0" r="1" gradientTransform="matrix(.33234 -.2841 .1844 .21572 22.489 7.083)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="n-7gz4alz"/><stop offset="1" class="v8gtn-b7b"/></radialGradient><radialGradient id="iNlnbTb" cx="0" cy="0" r="1" gradientTransform="matrix(.69557 .35875 -.43597 .8453 9.317 7.264)" gradientUnits="userSpaceOnUse"><stop class="sti3oxbeq"/><stop offset="1" class="x5-3y6xrq"/></radialGradient><radialGradient id="iVERpqe" cx="0" cy="0" r="1" gradientTransform="matrix(.07422 .35146 -.52397 .11065 12.276 5.217)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="itk3z-5ip"/><stop offset="1" class="j8q5y3jei"/></radialGradient><radialGradient id="iw9QqUc" cx="0" cy="0" r="1" gradientTransform="rotate(-80.737 13.6 -8.133)scale(1.02905 .94206)" gradientUnits="userSpaceOnUse"><stop class="nj0s1tj2o"/><stop offset="1" class="z1-7jowoz"/></radialGradient><radialGradient id="iBqn1xd" cx="0" cy="0" r="1" gradientTransform="matrix(-.4922 -1.07031 .2266 -.1042 20.526 6.217)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="o9ez09qax"/><stop offset="1" class="qrzlg2j4q"/></radialGradient><radialGradient id="iwacREz" cx="0" cy="0" r="1" gradientTransform="matrix(.10156 .3749 -.50936 .138 19.854 5.217)" gradientUnits="userSpaceOnUse"><stop offset=".299" class="hv46-obcm"/><stop offset="1" class="g7x6q-lxe"/></radialGradient><radialGradient id="ic9SDUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.97508 .53473 -.2619 -.47757 20.426 4.355)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="byw-t0bic"/></radialGradient><radialGradient id="iQiXRXd" cx="0" cy="0" r="1" gradientTransform="matrix(.62908 -.93084 .84184 .56893 19.403 5.412)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><radialGradient id="iDI5g0V" cx="0" cy="0" r="1" gradientTransform="matrix(-.97508 .53473 -.2619 -.47757 12.8 4.355)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="t36lxpgxn"/></radialGradient><radialGradient id="i53KubP" cx="0" cy="0" r="1" gradientTransform="matrix(.62908 -.93084 .84184 .56893 11.778 5.412)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><radialGradient id="iEEEWSb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.01175 4.40623 -6.6297 -3.02692 18.026 4.74)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="aet_92b8f"/><stop offset="1" class="rfjsk2b_a"/></radialGradient><radialGradient id="iWRW5Zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.67579 8.23047 0 16.014 8.74)" gradientUnits="userSpaceOnUse"><stop class="yexd1o2nx"/><stop offset="1" class="ue47neksc"/></radialGradient><radialGradient id="ieWHizW" cx="0" cy="0" r="1" gradientTransform="rotate(154.043 10.593 5.217)scale(3.62333 .22378)" gradientUnits="userSpaceOnUse"><stop offset=".097" class="m7zijhbgc"/><stop offset="1" class="lkpz06t1a"/></radialGradient><radialGradient id="ihSSm7d" cx="0" cy="0" r="1" gradientTransform="rotate(61.663 .03 10.263)scale(2.48532 2.58254)" gradientUnits="userSpaceOnUse"><stop class="l4i7jj__c"/><stop offset="1" class="z2xtp70hc"/></radialGradient><radialGradient id="iBw0BYb" cx="0" cy="0" r="1" gradientTransform="matrix(2.95313 1.56248 -.1016 .19204 9.338 5.084)" gradientUnits="userSpaceOnUse"><stop offset=".387" class="pmc291bsf"/><stop offset="1" class="tjgrrcbfz"/></radialGradient><radialGradient id="ifeMfDb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 1.375 -.42997 -.36157 22.62 5.24)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="vb43as5rm"/><stop offset="1" class="kvxx5e97u"/></radialGradient><radialGradient id="i2zYdYc" cx="0" cy="0" r="1" gradientTransform="rotate(175.929 7.948 1.951)scale(1.10043 .71838)" gradientUnits="userSpaceOnUse"><stop class="bfog00mit"/><stop offset="1" class="tk7r3ryjq"/></radialGradient><radialGradient id="iLXcHqh" cx="0" cy="0" r="1" gradientTransform="matrix(-.96874 .53125 -.2602 -.47447 9.645 4.833)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="t36lxpgxn"/></radialGradient><radialGradient id="igkdmBc" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.9248 .83637 .56524 8.629 5.883)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><radialGradient id="ifS1TEd" cx="0" cy="0" r="1" gradientTransform="matrix(-.96874 .53125 -.2602 -.47447 23.573 4.833)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="t36lxpgxn"/></radialGradient><radialGradient id="iJksjXb" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.9248 .83637 .56524 22.557 5.883)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><radialGradient id="iXdhh3D" cx="0" cy="0" r="1" gradientTransform="rotate(-90 11.775 -4.218)scale(1.36805)" gradientUnits="userSpaceOnUse"><stop class="m8_9xackt"/><stop offset="1" class="sblhzud6f"/></radialGradient><radialGradient id="iH9PggR" cx="0" cy="0" r="1" gradientTransform="matrix(.88821 -.82696 .53708 .57686 16.426 6.66)" gradientUnits="userSpaceOnUse"><stop class="jxvb9w84e"/><stop offset="1" class="a-oylkk7f"/></radialGradient><radialGradient id="iHcrFqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.72788 .60361 -.58534 -.70585 19.74 7.24)" gradientUnits="userSpaceOnUse"><stop class="wmixudboe"/><stop offset="1" class="bzekojbcn"/></radialGradient><radialGradient id="iNmQTwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.72788 .60361 -.58534 -.70585 12.986 7.24)" gradientUnits="userSpaceOnUse"><stop class="wmixudboe"/><stop offset="1" class="bzekojbcn"/></radialGradient><radialGradient id="iD4RU4b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10171 .60417 -.29591 -.5396 16.777 2.516)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="t36lxpgxn"/></radialGradient><radialGradient id="iEeNFte" cx="0" cy="0" r="1" gradientTransform="matrix(.71079 -1.05173 .95117 .64282 15.621 3.709)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><filter id="isHCR3b" width="15.268" height="15.268" x="8.478" y="5.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="ipawIYQ" width="13.918" height="7.56" x="8.979" y="21.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".075"/></filter><filter id="iMDKlDd" width="14.05" height="7.692" x="8.967" y="21.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.364706 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.498039 0 0 0 0 0.890196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3068" result="effect2_innerShadow_4002_3068"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.345098 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3068" result="effect3_innerShadow_4002_3068"/></filter><filter id="ifGNdKt" width="10.238" height="6.794" x="10.485" y="18.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".325"/></filter><filter id="ixDoI8d" width="2.05" height="2.05" x="11.382" y="18.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.478431 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="i65FLeb" width="2.1" height="2.1" x="11.932" y="20.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.698039 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="i7RXP8o" width="2.05" height="2.05" x="13.198" y="22.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.72549 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="iTeIzMe" width="2.05" height="2.05" x="14.995" y="22.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.72549 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="irdT0yb" width="3.318" height="3.218" x="9.692" y="12.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="iPRqU5b" width="3.218" height="3.468" x="19.205" y="12.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="ipYujAa" width="3.148" height="3.148" x="19.24" y="13.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".25"/></filter><filter id="iCrpM6T" width="2.648" height="2.648" x="9.996" y="13.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".125"/></filter><filter id="iArAeLc" width="10.191" height="11.077" x="10.891" y="9.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="iEHJT3d" width="2.877" height="3.682" x="14.386" y="13.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".25"/></filter><filter id="iOSMQFd" width="2.377" height="3.182" x="14.798" y="13.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".125"/></filter><filter id="itn41Zc" width="2.377" height="3.182" x="14.798" y="13.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".125"/></filter><filter id="iNzdj7d" width="3.702" height="1.526" x="14.136" y="17.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".05"/></filter><filter id="i06gUYc" width="3.001" height="1.285" x="16.929" y="13.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="iQvs1Kj" width="3.001" height="1.285" x="12.043" y="13.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="iwv095u" width="2.453" height="1.091" x="12.179" y="11.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.180392 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="ip3jckn" width="2.453" height="1.091" x="17.596" y="11.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.180392 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="i05t7rc" width=".786" height=".696" x="17.435" y="13.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".05"/></filter><filter id="i7cgtle" width=".891" height=".913" x="18.275" y="13.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".1"/></filter><filter id="ix9xGJc" width=".986" height="1.04" x="13.832" y="13.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".1"/></filter><filter id="ijs3eUd" width=".912" height=".704" x="13.077" y="13.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".05"/></filter><filter id="i2Jb4Ne" width="2.261" height=".978" x="17.626" y="11.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".1"/></filter><filter id="icLU91y" width="2.261" height=".978" x="12.175" y="11.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".1"/></filter><filter id="imQuFwd" width="4.985" height="5.214" x="9.279" y="7.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".375"/></filter><filter id="iK2SM5c" width="8.914" height="5.78" x="12.669" y="6.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".125"/></filter><filter id="iwToAIe" width="1.145" height="2.31" x="12.796" y="7.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".125"/></filter><filter id="iU1A1Ac" width="10.911" height="1.365" x="10.492" y="7.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".2"/></filter><filter id="iuO7tAe" width="2.517" height="1.953" x="11.339" y="5.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.619608 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="iyCBHNQ" width="1.604" height="1.554" x="19.053" y="3.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.639216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="iMao5Pd" width="1.604" height="1.554" x="11.428" y="3.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.639216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="i8w3UBc" width="13.93" height="5.045" x="9.049" y="3.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.619608 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="iFjOMnb" width="1.594" height="1.544" x="8.282" y="4.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.639216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="iumELri" width="1.544" height="1.544" x="22.21" y="4.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.611765 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="iZzqEUc" width="3.152" height="3.152" x="14.222" y="5.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".25"/></filter><filter id="iCC4SCc" width="2.116" height="2.116" x="18.116" y="6.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".25"/></filter><filter id="imYChWb" width="2.116" height="2.116" x="11.363" y="6.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".25"/></filter><filter id="id1p5uG" width="2.152" height="2.152" x="14.917" y="6.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.168627 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="icTm1Ct" width="1.116" height="1.166" x="18.812" y="6.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.619608 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="iH7Odpb" width="1.116" height="1.166" x="12.058" y="6.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.619608 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><filter id="iGKXWtc" width="6.248" height="3.259" x="15.987" y="3.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3068" stdDeviation=".025"/></filter><filter id="imMgy4c" width="1.799" height="1.749" x="15.226" y="1.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.639216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3068"/></filter><linearGradient id="i5TOwQc" x1="20.68" x2="13.439" y1="7.64" y2="21.082" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="ikQH8cb" x1="8.354" x2="8.104" y1="29.819" y2="29.819" gradientUnits="userSpaceOnUse"><stop class="x8dk6bl6o"/><stop offset="1" class="g-8u40lzl"/></linearGradient><linearGradient id="iLkQkbd" x1="23.635" x2="23.842" y1="29.99" y2="29.99" gradientUnits="userSpaceOnUse"><stop class="qrto2_zpw"/><stop offset="1" class="z2_l0sbav"/></linearGradient><linearGradient id="iyormFc" x1="23.932" x2="11.557" y1="29.99" y2="29.99" gradientUnits="userSpaceOnUse"><stop class="k_ugj6bqp"/><stop offset="1" class="etwgthjom"/></linearGradient><linearGradient id="iAhj8Hn" x1="18.463" x2="13.276" y1="27.646" y2="20.99" gradientUnits="userSpaceOnUse"><stop class="y-c-j769e"/><stop offset="1" class="t9knx544b"/></linearGradient><linearGradient id="iB6tLsc" x1="9.682" x2="13.727" y1="21.713" y2="28.005" gradientUnits="userSpaceOnUse"><stop class="odnc1cb0i"/><stop offset="1" class="foqmp2bms"/></linearGradient><linearGradient id="iGD15Bd" x1="19.42" x2="18.469" y1="20.58" y2="22.215" gradientUnits="userSpaceOnUse"><stop class="mv_c9zsjb"/><stop offset="1" class="cdd1ckbyi"/></linearGradient><linearGradient id="iGml8od" x1="17.516" x2="14.656" y1="21.115" y2="21.115" gradientUnits="userSpaceOnUse"><stop class="hjwbnqdui"/><stop offset="1" class="mz60q43tk"/></linearGradient><linearGradient id="iCV6YQc" x1="13.87" x2="14.604" y1="20.318" y2="20.389" gradientUnits="userSpaceOnUse"><stop class="pltquxbsd"/><stop offset="1" class="h6zt7fbge"/></linearGradient><linearGradient id="inVVc6c" x1="18.182" x2="17.588" y1="20.381" y2="20.381" gradientUnits="userSpaceOnUse"><stop class="wzg93nbjo"/><stop offset="1" class="c65l3ibcy"/></linearGradient><linearGradient id="iJ4hJwd" x1="9.692" x2="12.651" y1="14.68" y2="14.68" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iSNacab" x1="15.987" x2="15.987" y1="16.631" y2="13.949" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="ixlHEyd" x1="14.94" x2="15.795" y1="15.868" y2="15.973" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="imCI9Le" x1="15.987" x2="15.987" y1="16.723" y2="16.112" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="i1WgKKd" x1="15.987" x2="15.987" y1="13.831" y2="14.95" gradientUnits="userSpaceOnUse"><stop class="xdpxw8b3v"/><stop offset="1" class="wuv71nbvk"/></linearGradient><linearGradient id="isHtdud" x1="15.258" x2="15.71" y1="18.512" y2="17.64" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="i9gBkmd" x1="18.947" x2="18.633" y1="14.049" y2="14.242" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ijiCYrl" x1="14.548" x2="14.235" y1="14.049" y2="14.242" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDQp3ve" x1="18.005" x2="19.927" y1="12.187" y2="12.564" gradientUnits="userSpaceOnUse"><stop offset=".51" class="yb81_kbwu"/><stop offset="1" class="j5jquqwih"/></linearGradient><linearGradient id="i9VXaue" x1="14.057" x2="12.135" y1="12.187" y2="12.564" gradientUnits="userSpaceOnUse"><stop offset=".51" class="yb81_kbwu"/><stop offset="1" class="j5jquqwih"/></linearGradient><linearGradient id="i4KufPG" x1="13.095" x2="13.64" y1="8.394" y2="9.668" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="iYxXJcd" x1="14.277" x2="20.677" y1="8.818" y2="8.818" gradientUnits="userSpaceOnUse"><stop class="xgdg7_2ee"/><stop offset="1" class="dbwslloej"/></linearGradient><linearGradient id="iUZ7Ske" x1="11.885" x2="13.229" y1="5.959" y2="5.912" gradientUnits="userSpaceOnUse"><stop class="pd0xkfcwk"/><stop offset="1" class="mjtjw9d9u"/></linearGradient><linearGradient id="iS293Ii" x1="16.745" x2="16.745" y1="8.709" y2="8.334" gradientUnits="userSpaceOnUse"><stop class="sc708_bbk"/><stop offset="1" class="i_l5iobrn"/></linearGradient><linearGradient id="iYpqpOA" x1="16.042" x2="22.167" y1="3.803" y2="5.631" gradientUnits="userSpaceOnUse"><stop class="rapvxtblm"/><stop offset=".144" class="phj38-blk"/><stop offset=".842" class="zxi6lwb9j"/><stop offset="1" class="nu4sh_bsg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:princess" /></template>
<style>
.a-oylkk7f {
  stop-color: var(--svg-color--fc586e, #FC586E);
  stop-opacity: 0;
}

.a3n886b5x {
  stop-color: var(--svg-color--907bd1, #907BD1);
  stop-opacity: 0;
}

.a6mi8bcxq {
  cx: 12.421px;
  cy: 7.589px;
  r: 0.558px;
  fill: var(--svg-color--d37b55, #D37B55);
}

.a7hrg2b7m {
  stop-color: var(--svg-color--dc9640, #DC9640);
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.aet_92b8f {
  stop-color: var(--svg-color--edad5e, #EDAD5E);
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.arn54kl4j {
  stop-color: var(--svg-color--3293cc, #3293CC);
}

.as-4qhbhd {
  cx: 13.533px;
  cy: 13.9px;
  rx: 0.389px;
  ry: 0.197px;
}

.axbh60bsz {
  stop-color: var(--svg-color--6d4bc2, #6D4BC2);
  stop-opacity: 0;
}

.b6nn4d4lh {
  cx: 19.37px;
  cy: 7.398px;
  r: 0.558px;
}

.bc9553qxg {
  fill-rule: evenodd;
  d: path("M23.172 16.002c.213-.435.324-.921.324-1.427c0-.467-.096-.906-.269-1.306h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.215 3.298v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455c-.203.425-.324.9-.324 1.407a3.213 3.213 0 0 0 3.218 3.218h8.582a3.213 3.213 0 0 0 2.894-4.625a.52.52 0 0 1 0-.455m-12.26-2.673H10.9l1.198 2.356c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.189-1.674a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.241 1.255l-.051.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.bfog00mit {
  stop-color: var(--svg-color--d79747, #D79747);
}

.bii2ynb3s {
  fill: var(--svg-color--000, #000);
  d: path("M14.314 14.41a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.biu9whxny {
  stop-color: var(--svg-color--d69fd3, #D69FD3);
}

.bmln26pap {
  stop-color: var(--svg-color--7a5298, #7A5298);
}

.bp0jotlxe {
  stop-color: var(--svg-color--9c76eb, #9C76EB);
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.byw-t0bic {
  stop-color: var(--svg-color--d9a83d, #D9A83D);
}

.bzekojbcn {
  stop-color: var(--svg-color--3caef0, #3CAEF0);
}

.bzq8zz4vu {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.596 13.247c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.c65l3ibcy {
  stop-color: var(--svg-color--ffbb36, #FFBB36);
  stop-opacity: 0;
}

.cdd1ckbyi {
  stop-color: var(--svg-color--b26803, #B26803);
  stop-opacity: 0;
}

.ceou1rsni {
  stop-color: var(--svg-color--d3b0a8, #D3B0A8);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm8_bn2mq {
  d: path("M20.256 5.712c.1.175.302.541.391.703l-1.515.755l-.902-.903l.902-.785c.114-.104.36-.294.582-.261c.248.036.417.272.542.49");
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.crmkq1bkv {
  d: path("M11.301 16.202a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.cunr-1bwb {
  stop-color: var(--svg-color--7d48de, #7D48DE);
}

.cvioaxb2i {
  d: path("M11.32 15.666a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.cy4ujdbiq {
  stop-color: var(--svg-color--e7c7ff, #E7C7FF);
  stop-opacity: 0;
}

.d4jxbbblw {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.594 14.37l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.494-.377-.613 0");
}

.d7gnwkbua {
  stop-color: var(--svg-color--e2c0ab, #E2C0AB);
  stop-opacity: 0;
}

.da38a73_c {
  stop-color: var(--svg-color--b99bb6, #B99BB6);
}

.dakdtmo8r {
  stop-color: var(--svg-color--37cbf4, #37CBF4);
}

.dbwslloej {
  stop-color: var(--svg-color--c15c06, #C15C06);
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.dswnxcbqg {
  stop-color: var(--svg-color--e18d0e, #E18D0E);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.dvuac4bxb {
  cx: 15.995px;
  cy: 23.596px;
  r: 1px;
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e304mibzr {
  d: path("M21.187 25.801a3.502 3.502 0 1 0 7.004 0c0-1.934-1.568-3.389-3.502-3.389c-3.782 0-3.502 1.455-3.502 3.389");
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.ean9ofhjo {
  r: 1px;
}

.eapmb-b-r {
  stop-color: var(--svg-color--c0abb3, #C0ABB3);
}

.eb4-yylgr {
  cx: 9.905px;
  cy: 7.312px;
  r: 0.558px;
}

.eh1sqyczn {
  stop-color: var(--svg-color--d69fd3, #D69FD3);
  stop-opacity: 0;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esixkvbpd {
  stop-color: var(--svg-color--cc9dd5, #CC9DD5);
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.etwgthjom {
  stop-color: var(--svg-color--755cc0, #755CC0);
}

.f82r22d5b {
  d: path("M14.618 14.305c0-.288-.235-.48-.298-.538l-.288.279l.177.36z");
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fg8vwkbfq {
  stop-color: var(--svg-color--fce9ff, #FCE9FF);
}

.fga1l482e {
  stop-color: var(--svg-color--efd2c5, #EFD2C5);
  stop-opacity: 0;
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fkfx3o27i {
  stop-color: var(--svg-color--cfacbc, #CFACBC);
  stop-opacity: 0;
}

.foqmp2bms {
  stop-color: var(--svg-color--705693, #705693);
  stop-opacity: 0;
}

.fpyoctiow {
  stop-color: var(--svg-color--dbaaf7, #DBAAF7);
}

.fr4aurb9m {
  stop-color: var(--svg-color--e6d7e6, #E6D7E6);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftn-nj88l {
  stop-color: var(--svg-color--cca389, #CCA389);
}

.fus8l7b8h {
  d: path("M11.73 5.712c-.1.175-.302.541-.39.703l1.514.755l.902-.903l-.902-.785c-.114-.104-.359-.294-.582-.261c-.247.036-.417.272-.542.49");
}

.fxwj7ynbm {
  stop-color: var(--svg-color--fabb2d, #FABB2D);
  stop-opacity: 0;
}

.g-8u40lzl {
  stop-color: var(--svg-color--7045c9, #7045C9);
  stop-opacity: 0;
}

.g-wnk0-1g {
  stop-color: var(--svg-color--ffc22e, #FFC22E);
}

.g049h7flb {
  stop-color: var(--svg-color--8461d2, #8461D2);
}

.g27slhbqh {
  stop-color: var(--svg-color--b06259, #B06259);
}

.g6hzctbpu {
  cx: 12.432px;
  cy: 19.986px;
  r: 1px;
}

.g7x6q-lxe {
  stop-color: var(--svg-color--c98b19, #C98B19);
  stop-opacity: 0;
}

.gag6ovb3k {
  stop-color: var(--svg-color--d0b5b2, #D0B5B2);
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gsgx-m-kb {
  stop-color: var(--svg-color--e0ccec, #E0CCEC);
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.h55xk6bmz {
  stop-color: var(--svg-color--7a5fc2, #7A5FC2);
  stop-opacity: 0;
}

.h6zt7fbge {
  stop-color: var(--svg-color--f19f2d, #F19F2D);
  stop-opacity: 0;
}

.h88_-5b3g {
  cx: 15.798px;
  cy: 7.269px;
  r: 1.076px;
  fill: var(--svg-color--d37b55, #D37B55);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hjwbnqdui {
  stop-color: var(--svg-color--fdb934, #FDB934);
}

.hoqi9e01c {
  stop-color: var(--svg-color--845bd7, #845BD7);
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hqnr5ybwo {
  stop-color: var(--svg-color--ffc73d, #FFC73D);
  stop-opacity: 0;
}

.hv46-obcm {
  stop-color: var(--svg-color--c98b19, #C98B19);
}

.i_l5iobrn {
  stop-color: var(--svg-color--f9711e, #F9711E);
  stop-opacity: 0;
}

.if8ggt7lg {
  stop-color: var(--svg-color--6046a6, #6046A6);
  stop-opacity: 0;
}

.imiwjlbuv {
  stop-color: var(--svg-color--d17724, #D17724);
}

.itk3z-5ip {
  stop-color: var(--svg-color--d59b33, #D59B33);
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j-hgq5bil {
  stop-color: var(--svg-color--d5c2e3, #D5C2E3);
}

.j5jquqwih {
  stop-color: var(--svg-color--b55f4c, #B55F4C);
  stop-opacity: 0;
}

.j8q5y3jei {
  stop-color: var(--svg-color--d59b33, #D59B33);
  stop-opacity: 0;
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jhbwcacjr {
  stop-color: var(--svg-color--7143c9, #7143C9);
  stop-opacity: 0;
}

.jxvb9w84e {
  stop-color: var(--svg-color--fc586e, #FC586E);
}

.jypakik4k {
  stop-color: var(--svg-color--8c69d4, #8C69D4);
}

.k_ugj6bqp {
  stop-color: var(--svg-color--876ecd, #876ECD);
}

.k3jt88b8m {
  stop-color: var(--svg-color--866bca, #866BCA);
  stop-opacity: 0;
}

.k5zu23s6k {
  stop-color: var(--svg-color--9c78ec, #9C78EC);
}

.kcmmk5bxb {
  d: path("M26.833 27.014c.388.97.698 2.388.805 2.976h-4.953v-2.976z");
}

.kf6yzhcxx {
  stop-color: var(--svg-color--6046a6, #6046A6);
}

.kgfm8cpgt {
  stop-color: var(--svg-color--dc9640, #DC9640);
  stop-opacity: 0;
}

.kijt7rb5s {
  stop-color: var(--svg-color--b99bb6, #B99BB6);
  stop-opacity: 0;
}

.kol_e4bkv {
  stop-color: var(--svg-color--b06604, #B06604);
  stop-opacity: 0;
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kqli1w19h {
  d: path("M10.898 8.34h10.105v.565s-3.685-.565-10.105 0c-.013-.22 0-.565 0-.565");
}

.kqlr11b-y {
  stop-color: var(--svg-color--d4c1d3, #D4C1D3);
}

.kr7xbubfl {
  stop-color: var(--svg-color--dcc4d2, #DCC4D2);
  stop-opacity: 0;
}

.kth1ncger {
  stop-color: var(--svg-color--9376c4, #9376C4);
  stop-opacity: 0;
}

.kvxx5e97u {
  stop-color: var(--svg-color--ce8f45, #CE8F45);
  stop-opacity: 0;
}

.l33ghubim {
  d: path("M18.171 13.518a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.l4i7jj__c {
  stop-color: var(--svg-color--daa24e, #DAA24E);
}

.lbkb08b7q {
  cx: 19.175px;
  cy: 7.589px;
  r: 0.558px;
  fill: var(--svg-color--d37b55, #D37B55);
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lcvm_qpfm {
  d: path("M18.966 14.293a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkpz06t1a {
  stop-color: var(--svg-color--c89751, #C89751);
  stop-opacity: 0;
}

.lkxhe0bym {
  stop-color: var(--svg-color--987ae1, #987AE1);
}

.lnf03fndg {
  fill-rule: evenodd;
  d: path("m14.07 27.625l-4.954-5.688a.2.2 0 0 1 .025-.287l.536-.434a.2.2 0 0 1 .276.024l4.949 5.665c.558.565 1.784.464 2.19.001l4.939-5.656a.2.2 0 0 1 .273-.027l.537.418a.2.2 0 0 1 .027.29l-4.946 5.697c-1.032 1.26-2.673 1.37-3.852-.003");
}

.lqhq5vk7o {
  stop-color: var(--svg-color--6d4bc2, #6D4BC2);
}

.ls12e09pb {
  stop-color: var(--svg-color--fff8ff, #FFF8FF);
}

.lt46jsbwc {
  stop-color: var(--svg-color--fabb2d, #FABB2D);
}

.lxwln9mzq {
  stop-color: var(--svg-color--7143c9, #7143C9);
}

.m_5d6hb0c {
  fill: var(--svg-color--ab4523, #AB4523);
  d: path("m12.59 12.815l-.005.002a.268.268 0 0 1-.276-.46h.002l.003-.003l.01-.005l.031-.018q.042-.023.117-.059a3 3 0 0 1 .41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 1 1-.093.529a2.3 2.3 0 0 0-1.072.091a3 3 0 0 0-.456.194");
}

.m_skw-bxy {
  fill: var(--svg-color--ab4523, #AB4523);
  fill-rule: evenodd;
  d: path("m19.718 12.357l-.137.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.059a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.091a.268.268 0 0 1-.093-.529c.513-.09.988.001 1.328.11a3.3 3.3 0 0 1 .558.238l.01.005z");
}

.m3myxqzyl {
  d: path("M18.105 13.707c.063.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.358c.151-.113.325-.136.389-.051");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m7zijhbgc {
  stop-color: var(--svg-color--c89751, #C89751);
}

.m8_9xackt {
  stop-color: var(--svg-color--e7175a, #E7175A);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdrb42i-j {
  d: path("M20.814 16.202a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mjrstybho {
  stop-color: var(--svg-color--635385, #635385);
}

.mjtjw9d9u {
  stop-color: var(--svg-color--f2bd5c, #F2BD5C);
}

.mlgod1b5x {
  stop-color: var(--svg-color--914c01, #914C01);
}

.mv_c9zsjb {
  stop-color: var(--svg-color--b26803, #B26803);
}

.mxq0h6ljd {
  cx: 19.805px;
  cy: 4.66px;
  r: 0.752px;
}

.myoa1jb6u {
  stop-color: var(--svg-color--e69f21, #E69F21);
}

.mz60q43tk {
  stop-color: var(--svg-color--ef9d2b, #EF9D2B);
}

.n_afmtc4c {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.987 17.816c-.52 0-1.01-.125-1.422-.344c-.14-.073-.291.088-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.204-.22c-.41.22-.895.344-1.421.344");
}

.n-7gz4alz {
  stop-color: var(--svg-color--53d8f2, #53D8F2);
}

.n-b8_boqs {
  d: path("m15.605 14.113l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.766 0");
}

.n0x7ebc8c {
  cx: 14.198px;
  cy: 23.111px;
  r: 1px;
}

.n38djt95v {
  d: path("M13.803 13.518a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.n6d_jnr9j {
  d: path("M5.167 27.014c-.388.97-.698 2.388-.805 2.976h4.953v-2.976z");
}

.n6j5avbvg {
  stop-color: var(--svg-color--ab877b, #AB877B);
}

.na-ss_5-a {
  width: 4.359px;
  height: 4.703px;
  x: 13.823px;
  y: 17.225px;
  rx: 2px;
}

.ndc_njleh {
  fill: var(--svg-color--7359bc, #7359BC);
  fill-rule: evenodd;
  d: path("m14.049 27.742l-4.871-5.548a.194.194 0 0 1 .024-.28l.527-.423a.2.2 0 0 1 .272.024l4.865 5.525c.549.551 2.02.665 2.418.214l4.782-5.521a.2.2 0 0 1 .27-.026l.336.199a.194.194 0 0 1 .027.282l-4.864 5.557c-1.014 1.23-2.627 1.336-3.786-.003");
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nj0s1tj2o {
  stop-color: var(--svg-color--c88c35, #C88C35);
}

.nm_1c1iwo {
  d: path("M20.814 15.666a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.ntwcd8zlo {
  d: path("M10.9 13.33h.012l-.01-.266l-.01-.306c.02-.948.574-1.316.81-1.438l.05-.02l.052-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.119 3.073c-.123 2.802-2.311 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.nu4sh_bsg {
  stop-color: var(--svg-color--f2bb64, #F2BB64);
  stop-opacity: 0;
}

.nwobqib-i {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.814 15.666a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o8dw4p7vp {
  stop-color: var(--svg-color--ba93b0, #BA93B0);
  stop-opacity: 0;
}

.o9ez09qax {
  stop-color: var(--svg-color--d3a150, #D3A150);
}

.oaxszm67z {
  stop-color: var(--svg-color--cb6325, #CB6325);
  stop-opacity: 0;
}

.ocxer-jqp {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.987 17.816c-.52 0-1.01-.125-1.422-.344c-.14-.073-.291.088-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.204-.22c-.41.22-.895.344-1.421.344Z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odnc1cb0i {
  stop-color: var(--svg-color--705693, #705693);
}

.oj0sgcj4p {
  stop-color: var(--svg-color--b78eae, #B78EAE);
}

.oo7p4ebqa {
  cx: 12.932px;
  cy: 21.744px;
  r: 1px;
}

.ork4wvyzn {
  d: path("m9.05 5.572l1.272 2.875a.15.15 0 0 0 .138.09h11.056a.15.15 0 0 0 .136-.088l1.327-2.877l-.187-.438a63 63 0 0 0-1.736.816c-.43.208-.824.397-1.07.508c-.403.184-.857.087-1.046-.125c-.25-.28-.711-.81-1.14-1.304c-.35-.402-.677-.78-.852-.977c-.342-.386-.722-.453-.914-.46h-.04c-.192.007-.571.074-.913.46c-.175.198-.503.575-.852.977c-.43.494-.89 1.025-1.14 1.304c-.19.212-.643.309-1.047.125c-.245-.11-.64-.3-1.07-.508a63 63 0 0 0-1.735-.816z");
}

.owyqbq1bg {
  stop-color: var(--svg-color--efd2c5, #EFD2C5);
}

.p_2ayxqss {
  cx: 9.029px;
  cy: 5.136px;
  r: 0.747px;
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p3t2yk0_n {
  stop-color: var(--svg-color--d86b1c, #D86B1C);
  stop-opacity: 0;
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p6-ozrb_x {
  stop-color: var(--svg-color--b06604, #B06604);
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pd0xkfcwk {
  stop-color: var(--svg-color--f1ba66, #F1BA66);
}

.phj38-blk {
  stop-color: var(--svg-color--efb65d, #EFB65D);
}

.pj5su6bsv {
  stop-color: var(--svg-color--ab877b, #AB877B);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pltquxbsd {
  stop-color: var(--svg-color--ac630c, #AC630C);
}

.pmc291bsf {
  stop-color: var(--svg-color--e3b560, #E3B560);
}

.pmg10qb6b {
  stop-color: var(--svg-color--fffaff, #FFFAFF);
}

.pyjhqsreq {
  d: path("M8.338 22.428c1.11-1.089 4.193-3.219 7.649-3.219s6.539 2.13 7.648 3.219v7.562H8.338z");
}

.pyzsv8yjt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.136 12.22c-.323-.079-1.125-.04-1.661.344");
}

.q-wkihbps {
  stop-color: var(--svg-color--e5c8e2, #E5C8E2);
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q8k_nsb5l {
  stop-color: var(--svg-color--d17724, #D17724);
  stop-opacity: 0;
}

.q8l1y6b0l {
  cx: 22.089px;
  cy: 7.324px;
  r: 0.558px;
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qrto2_zpw {
  stop-color: var(--svg-color--814fe0, #814FE0);
}

.qrzlg2j4q {
  stop-color: var(--svg-color--d3a150, #D3A150);
  stop-opacity: 0;
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.rapvxtblm {
  stop-color: var(--svg-color--efb65d, #EFB65D);
  stop-opacity: 0;
}

.rdlsi4esi {
  cx: 22.957px;
  cy: 5.136px;
  r: 0.747px;
}

.re4dv2b7j {
  stroke-width: var(--svg-stroke-width--0-08px, 0.08px);
  d: path("M16.042 3.615c.098.01.432.13.664.348c.23.219 1.53 1.71 2.144 2.383c.207.226.568.502 1.2.246c.63-.256 1.674-.774 2.117-1");
}

.rfjsk2b_a {
  stop-color: var(--svg-color--e59e51, #E59E51);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rlxb2vbdo {
  stop-color: var(--svg-color--7a5fc2, #7A5FC2);
}

.rqzct4dku {
  cx: 15.993px;
  cy: 7.078px;
  r: 1.076px;
}

.rr9pqccyi {
  stop-color: var(--svg-color--f5dff7, #F5DFF7);
}

.rz5s1rb1a {
  cx: 13.533px;
  cy: 13.9px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s89mhhmgh {
  d: path("m15.605 14.231l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.766 0");
}

.sbez_4byf {
  stop-color: var(--svg-color--945cee, #945CEE);
}

.sblhzud6f {
  stop-color: var(--svg-color--e11f40, #E11F40);
}

.sc708_bbk {
  stop-color: var(--svg-color--f9711e, #F9711E);
}

.sdv8mxbuo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.096 8.05c.023.243.234 1.157.544 1.71");
}

.seaqufnpd {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.129 14.024c.265-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.269.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.08-.45");
}

.sj2nsghkd {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.845 14.024c-.266-.467-.669-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.27.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.sm9o6zbbb {
  stop-color: var(--svg-color--ffc73d, #FFC73D);
}

.sof-msbva {
  fill: var(--svg-color--000, #000);
  d: path("M17.66 14.41a.51.51 0 0 1 .51-.51a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.236");
}

.spc75r5za {
  stop-color: var(--svg-color--805fc9, #805FC9);
}

.sti3oxbeq {
  stop-color: var(--svg-color--33a6c5, #33A6C5);
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t2krvpb6g {
  stop-color: var(--svg-color--e3cde6, #E3CDE6);
}

.t36lxpgxn {
  stop-color: var(--svg-color--e5ba4b, #E5BA4B);
}

.t70q9k_cc {
  stop-color: var(--svg-color--814fdf, #814FDF);
}

.t9knx544b {
  stop-color: var(--svg-color--835fc6, #835FC6);
}

.td2tyjbuq {
  stop-color: var(--svg-color--fdd172, #FDD172);
}

.tfsbwvbnl {
  stop-color: var(--svg-color--ebccff, #EBCCFF);
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tjgrrcbfz {
  stop-color: var(--svg-color--e3b560, #E3B560);
  stop-opacity: 0;
}

.tk7r3ryjq {
  stop-color: var(--svg-color--d79747, #D79747);
  stop-opacity: 0;
}

.tknr5ybzo {
  stop-color: var(--svg-color--bd9b8f, #BD9B8F);
}

.toy3i-56q {
  stop-color: var(--svg-color--907bd1, #907BD1);
}

.u-wvucrhg {
  stop-color: var(--svg-color--c3a8aa, #C3A8AA);
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u4-2g8brb {
  d: path("M11.093 8.579c.62-.554 1.517-.56 2.02-.47l.402 1.29c-.257-.038-.486.051-.68.236c-.455 1.26-2.022 1.955-2.748 2.145c-.15-1.492-.067-2.246 1.006-3.201");
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.ue47neksc {
  stop-color: var(--svg-color--e77953, #E77953);
  stop-opacity: 0;
}

.uegyi0cvz {
  cx: 12.18px;
  cy: 4.66px;
  r: 0.752px;
}

.uf34-63ve {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.378 13.247c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.127 1.37-1.127");
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.uo29cubui {
  cx: 16.076px;
  cy: 2.859px;
  r: 0.85px;
}

.uzx-du17j {
  stop-color: var(--svg-color--945cee, #945CEE);
  stop-opacity: 0;
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v8gtn-b7b {
  stop-color: var(--svg-color--53d8f2, #53D8F2);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vavjlxdpa {
  stop-color: var(--svg-color--cfbadc, #CFBADC);
}

.vb43as5rm {
  stop-color: var(--svg-color--ce8f45, #CE8F45);
}

.vdftvkb9c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.926 12.22c.323-.079 1.125-.04 1.661.344");
}

.vfe9g3b6u {
  stop-color: var(--svg-color--9376c4, #9376C4);
}

.vfm2rzgjx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.105 13.707c.063.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.358c.151-.113.325-.136.389-.051");
}

.vl7hh0bdy {
  d: path("m9.539 21.45l5.55 6.493h2.015l5.453-6.407c-1.49-1.075-3.92-2.327-6.57-2.327c-2.579 0-4.95 1.186-6.448 2.24");
}

.vlr1jy-qw {
  stop-color: var(--svg-color--ce9fd2, #CE9FD2);
  stop-opacity: 0;
}

.voqk07baz {
  stop-color: var(--svg-color--b89174, #B89174);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w3-vy4c8j {
  stop-color: var(--svg-color--e38923, #E38923);
}

.w72oynbwi {
  stop-color: var(--svg-color--e38923, #E38923);
  stop-opacity: 0;
}

.w78c_mbga {
  d: path("M10.813 25.801a3.502 3.502 0 1 1-7.004 0c0-1.934 1.568-3.389 3.502-3.389c3.781 0 3.502 1.455 3.502 3.389");
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wb_af7khf {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.32 15.666a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.wmixudboe {
  stop-color: var(--svg-color--50d5fe, #50D5FE);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wuv71nbvk {
  stop-color: var(--svg-color--f8c841, #F8C841);
  stop-opacity: 0;
}

.wzg93nbjo {
  stop-color: var(--svg-color--c7880c, #C7880C);
}

.x5-3y6xrq {
  stop-color: var(--svg-color--2783b8, #2783B8);
}

.x8dk6bl6o {
  stop-color: var(--svg-color--7045c9, #7045C9);
}

.xdencea7s {
  fill-rule: evenodd;
  d: path("M12.743 21.2a.98.98 0 1 0-.766.218a.98.98 0 0 0 .986 1.664a.98.98 0 0 0 1.668 1.01a.98.98 0 0 0 1.947 0a.978.978 0 0 0 1.766-.583a1 1 0 0 0-.098-.428a.978.978 0 0 0 1.337-.912a.98.98 0 0 0-.351-.751a.98.98 0 1 0-.766-.218a.98.98 0 0 0-.744 1.397a.98.98 0 0 0-1.331.803a.978.978 0 0 0-1.573 0a.98.98 0 0 0-1.332-.803a.98.98 0 0 0-.744-1.397");
}

.xdpxw8b3v {
  stop-color: var(--svg-color--f8c841, #F8C841);
}

.xf3nhjbpw {
  stop-color: var(--svg-color--fff6ff, #FFF6FF);
}

.xg0mdnbqj {
  stop-color: var(--svg-color--e2c0ab, #E2C0AB);
}

.xgdg7_2ee {
  stop-color: var(--svg-color--eb7412, #EB7412);
}

.xhgokzbln {
  stop-color: var(--svg-color--ffe13c, #FFE13C);
}

.xjhzw6b4m {
  stop-color: var(--svg-color--ce9fd2, #CE9FD2);
}

.xpqto8b3q {
  stop-color: var(--svg-color--e8d9e7, #E8D9E7);
  stop-opacity: 0;
}

.xqubvtkdv {
  stop-color: var(--svg-color--ffc22e, #FFC22E);
  stop-opacity: 0;
}

.xruj5pnln {
  cx: 12.616px;
  cy: 7.398px;
  r: 0.558px;
}

.y-c-j769e {
  stop-color: var(--svg-color--9869eb, #9869EB);
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.yb1xaiemt {
  stop-color: var(--svg-color--7a5298, #7A5298);
  stop-opacity: 0;
}

.yb81_kbwu {
  stop-color: var(--svg-color--b55f4c, #B55F4C);
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yexd1o2nx {
  stop-color: var(--svg-color--e77953, #E77953);
}

.yidq71bjl {
  stop-color: var(--svg-color--c3a8aa, #C3A8AA);
  stop-opacity: 0;
}

.yind2xb3b {
  stop-color: var(--svg-color--7d48de, #7D48DE);
  stop-opacity: 0;
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yqk-2gbyp {
  stop-color: var(--svg-color--cb6325, #CB6325);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.yws01behm {
  stop-color: var(--svg-color--b76d0a, #B76D0A);
  stop-opacity: 0;
}

.z_f48dbjf {
  stop-color: var(--svg-color--735fab, #735FAB);
  stop-opacity: 0;
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z1-7jowoz {
  stop-color: var(--svg-color--d09731, #D09731);
}

.z2_l0sbav {
  stop-color: var(--svg-color--814fe0, #814FE0);
  stop-opacity: 0;
}

.z2xtp70hc {
  stop-color: var(--svg-color--daa24e, #DAA24E);
  stop-opacity: 0;
}

.z54rox6ux {
  stop-color: var(--svg-color--8a5ee4, #8A5EE4);
}

.z5oaikbwd {
  d: path("M15.383 6.802c-1.132-.25-2.346.955-2.463 1.374c1.541 3.62 3.91 3.276 6.536 2.984c1.573-.175 1.744.542 1.878.888c-.436-4.056-3.37-4.676-5.95-5.246");
}

.z9cu3vbra {
  stop-color: var(--svg-color--fff7ff, #FFF7FF);
}

.zn9diyb1a {
  stop-color: var(--svg-color--8569c9, #8569C9);
}

.zxi6lwb9j {
  stop-color: var(--svg-color--f2bb64, #F2BB64);
}

</style>
