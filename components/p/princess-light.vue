<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ivVZbqb)"><path fill="url(#i93E6Rd)" clip-rule="evenodd" class="vqzrhj3rz"/><path fill="url(#io8dnbc)" clip-rule="evenodd" class="vqzrhj3rz"/><path fill="url(#iwjkdQb)" clip-rule="evenodd" class="vqzrhj3rz"/><path fill="url(#iM1Vz2c)" clip-rule="evenodd" class="vqzrhj3rz"/><path fill="url(#iCZZN0c)" clip-rule="evenodd" class="vqzrhj3rz"/><path fill="url(#iS1CTHb)" clip-rule="evenodd" class="vqzrhj3rz"/><path fill="url(#iIXquHb)" clip-rule="evenodd" class="vqzrhj3rz"/><path fill="url(#ibHH2Rc)" clip-rule="evenodd" class="vqzrhj3rz"/><path fill="url(#iFDk0ic)" clip-rule="evenodd" class="vqzrhj3rz"/><path fill="url(#im5iLlb)" clip-rule="evenodd" class="vqzrhj3rz"/><path fill="url(#i9CUWEd)" clip-rule="evenodd" class="vqzrhj3rz"/></g><path fill="url(#ihQi12b)" class="n6d_jnr9j"/><path fill="url(#ikQH8cb)" class="n6d_jnr9j"/><path fill="url(#iNUvqbF)" class="kcmmk5bxb"/><path fill="url(#iZIIgrd)" class="kcmmk5bxb"/><path fill="url(#iLkQkbd)" class="kcmmk5bxb"/><path fill="url(#iecRI9d)" class="w78c_mbga"/><path fill="url(#iDsAFBc)" class="w78c_mbga"/><path fill="url(#iSPlgje)" class="w78c_mbga"/><path fill="url(#ic2fKLc)" class="w78c_mbga"/><path fill="url(#ijG4gop)" class="e304mibzr"/><path fill="url(#ir2U4mb)" class="e304mibzr"/><path fill="url(#i0MLaVu)" class="e304mibzr"/><path fill="url(#iFO9tQd)" class="e304mibzr"/><path fill="url(#iyormFc)" class="pyjhqsreq"/><path fill="url(#ipazNNu)" class="pyjhqsreq"/><path fill="url(#iDczi2Q)" class="vl7hh0bdy"/><path fill="url(#iNI3hFF)" class="vl7hh0bdy"/><path fill="url(#iieMYre)" class="vl7hh0bdy"/><path fill="url(#i00GMMe)" class="vl7hh0bdy"/><path fill="url(#ipANa1b)" class="vl7hh0bdy"/><path fill="url(#ia8sqld)" class="vl7hh0bdy"/><g filter="url(#iXrRStc)"><path clip-rule="evenodd" class="ovkwvebhl"/></g><g filter="url(#iiG6n5c)"><path fill="url(#iAhj8Hn)" clip-rule="evenodd" class="inuz7fbaa"/></g><path fill="url(#iB6tLsc)" clip-rule="evenodd" class="inuz7fbaa"/><path fill="url(#ifi30ue)" clip-rule="evenodd" class="inuz7fbaa"/><path fill="url(#iRI4m7h)" clip-rule="evenodd" class="inuz7fbaa"/><path fill="url(#iolaald)" clip-rule="evenodd" class="inuz7fbaa"/><g filter="url(#izBx3fd)"><path fill="url(#iHUwowc)" clip-rule="evenodd" class="r04kwie6j"/><path fill="url(#ifGDHuc)" clip-rule="evenodd" class="r04kwie6j"/></g><circle fill="url(#iPmHRmc)" transform="matrix(-1 0 0 1 19.557 19.986)" class="ean9ofhjo"/><circle fill="url(#ianTTFc)" transform="matrix(-1 0 0 1 19.557 19.986)" class="ean9ofhjo"/><circle fill="url(#ihF3OKd)" transform="matrix(-1 0 0 1 19.057 21.744)" class="ean9ofhjo"/><circle fill="url(#iUtrbGD)" transform="matrix(-1 0 0 1 19.057 21.744)" class="ean9ofhjo"/><circle fill="url(#ixjPQUb)" transform="matrix(-1 0 0 1 17.792 23.111)" class="ean9ofhjo"/><circle fill="url(#ikD1Ide)" transform="matrix(-1 0 0 1 17.792 23.111)" class="ean9ofhjo"/><circle fill="url(#isuVgPF)" transform="matrix(-1 0 0 1 17.792 23.111)" class="ean9ofhjo"/><g filter="url(#ipBEphd)"><circle fill="url(#iuTMqgc)" class="g6hzctbpu"/><circle fill="url(#iMTto5b)" class="g6hzctbpu"/><circle fill="url(#ibKaeAo)" class="g6hzctbpu"/></g><g filter="url(#iFGJULh)"><circle fill="url(#izwboXE)" class="oo7p4ebqa"/><circle fill="url(#ijSHste)" class="oo7p4ebqa"/><circle fill="url(#iqdo5md)" class="oo7p4ebqa"/><circle fill="url(#iRxLk5d)" class="oo7p4ebqa"/></g><g filter="url(#iwCw5Kc)"><circle fill="url(#iY7ZVWc)" class="n0x7ebc8c"/><circle fill="url(#ibnwHYt)" class="n0x7ebc8c"/><circle fill="url(#iMGUs4b)" class="n0x7ebc8c"/><circle fill="url(#ie2nM2s)" class="n0x7ebc8c"/></g><g filter="url(#iYglVZb)"><circle fill="url(#iHzkxde)" class="dvuac4bxb"/><circle fill="url(#i7dGJyb)" class="dvuac4bxb"/><circle fill="url(#iR45lBb)" class="dvuac4bxb"/></g><rect fill="url(#iLPP77c)" class="na-ss_5-a"/><rect fill="url(#iRlr9qc)" class="na-ss_5-a"/><rect fill="url(#i3ByHib)" class="na-ss_5-a"/><rect fill="url(#itzezLd)" class="na-ss_5-a"/><path fill="url(#ilABBKc)" class="n261g_b5l"/><path fill="url(#i30rZSc)" class="gfzgh5bel"/><g filter="url(#iZvJUwd)"><path fill="url(#ifsmvKb)" class="k0t4ahufu"/></g><g filter="url(#iEfAtRc)"><path fill="url(#iyvU48c)" class="o2l5d5bss"/><path fill="url(#iszy3Td)" class="o2l5d5bss"/></g><g filter="url(#i9p7MBc)"><path class="x6eb0fbok"/><path fill="url(#iD0ouLb)" class="ighfy72rq"/></g><g filter="url(#is4hknd)"><path class="n2v6nbcyb"/><path fill="url(#iB8Kj9c)" class="pw1338b2k"/></g><g filter="url(#i6mkuZc)"><path fill="url(#i3H80vd)" class="tohqxz6rz"/><path fill="url(#iZJzQqF)" class="tohqxz6rz"/><path fill="url(#iKb2ejV)" class="tohqxz6rz"/><path fill="url(#id9ci0d)" class="tohqxz6rz"/><path fill="url(#ieQFuNb)" class="tohqxz6rz"/><path fill="url(#i0QmVcg)" class="tohqxz6rz"/><path fill="url(#iLBFlse)" class="tohqxz6rz"/></g><path fill="url(#iiJLsjd)" class="tohqxz6rz"/><path fill="url(#iP4Xfje)" class="tohqxz6rz"/><g filter="url(#ippQuFe)"><path class="dvd_3xbng"/></g><g filter="url(#iG4Q01c)"><path class="uj42qvbww"/><path fill="url(#iLetnwb)" class="uzgzp1byj"/><path fill="url(#iH7iAbe)" class="uzgzp1byj"/><path fill="url(#i12toIb)" class="uzgzp1byj"/><path fill="url(#ibsX0qc)" class="uzgzp1byj"/></g><g filter="url(#irfgRle)"><path fill="url(#izxUd1H)" class="bg-hvbbga"/></g><g filter="url(#ifvIqae)"><path stroke="url(#iqA2n8d)" class="xa-8pmq2w"/></g><path class="miowekbgu"/><g filter="url(#iAqZned)"><path class="cu6bo-a-n"/></g><g filter="url(#iavnGve)"><path class="gutnx8b0t"/></g><g filter="url(#imKzlve)"><path class="iljlxyb3g"/></g><g filter="url(#iw4SZNd)"><path clip-rule="evenodd" class="tsa08abfi"/></g><path class="zpxfvu-uq"/><path fill="url(#idDALsc)" class="ubtc8c7br"/><path class="aszcv_87a"/><g filter="url(#iHS9uUR)"><path class="q172lj3mg"/><path fill="url(#iWTvJoe)" class="a8s6nf2ic"/></g><g filter="url(#iIbuRDb)"><path fill="url(#iI5SCYP)" class="t1po3obiw"/></g><path class="ptxyeebxb"/><path fill="url(#iBthudd)" class="fjtps8bgo"/><path class="ig99y4b1u"/><g filter="url(#iDTB0AS)"><path fill="url(#ibJtQUd)" class="r-d41foqz"/></g><g filter="url(#ilRxLOl)"><ellipse transform="rotate(-27.914 13.595 13.88)" class="o5nkmlb_j"/><ellipse fill="url(#ifgUU9d)" transform="rotate(-27.914 13.595 13.88)" class="mgz8cwb4o"/></g><g filter="url(#ipWbRle)"><path class="fyucgebtp"/></g><g filter="url(#inNF1Nd)"><path class="ocqu7f-1v"/></g><g filter="url(#iPUkNcc)"><path class="yi0nku-_h"/><path fill="url(#iDNf9iv)" class="o6q5k3k5k"/></g><g filter="url(#igzM4zd)"><path class="se2t1ybto"/><path fill="url(#iLVVDFG)" class="lt5s5v7qd"/><path fill="url(#iwahn7j)" class="lt5s5v7qd"/></g><g filter="url(#iykDy5d)"><path stroke="url(#iJcWXlu)" class="snp7jbbjy"/></g><g filter="url(#iZIKAGt)"><path class="jvmoe0w6d"/></g><g filter="url(#iRjkJEb)"><path class="c38snlpyv"/></g><circle fill="url(#icRhpDc)" class="q8l1y6b0l"/><circle fill="url(#iQREtnd)" class="q8l1y6b0l"/><circle fill="url(#iBRKmve)" class="o6_n3pbob"/><g filter="url(#ihmJlQa)"><path fill="url(#iUZ7Ske)" class="fus8l7b8h"/><path fill="url(#iVERpqe)" class="fus8l7b8h"/></g><path fill="url(#iw9QqUc)" class="cm8_bn2mq"/><path fill="url(#iBqn1xd)" class="cm8_bn2mq"/><path fill="url(#iwacREz)" class="cm8_bn2mq"/><g filter="url(#iYlKzLb)"><circle fill="url(#ic9SDUc)" class="mxq0h6ljd"/><circle fill="url(#iQiXRXd)" class="mxq0h6ljd"/></g><g filter="url(#izpqlFb)"><circle fill="url(#iDI5g0V)" class="uegyi0cvz"/><circle fill="url(#i53KubP)" class="uegyi0cvz"/></g><g filter="url(#iagPdXd)"><path fill="url(#iEEEWSb)" class="huvog8bmh"/><path fill="url(#iWRW5Zd)" class="huvog8bmh"/><path fill="url(#ieWHizW)" class="huvog8bmh"/><path fill="url(#iS293Ii)" class="huvog8bmh"/><path fill="url(#ihSSm7d)" class="huvog8bmh"/><path fill="url(#iBw0BYb)" class="huvog8bmh"/><path fill="url(#ifeMfDb)" class="huvog8bmh"/><path fill="url(#izm3X0b)" class="huvog8bmh"/></g><g filter="url(#i0hWzfT)"><circle fill="url(#iZzVw3c)" class="q0597ob7u"/><circle fill="url(#ilaTEnd)" class="q0597ob7u"/></g><g filter="url(#i18e53I)"><circle fill="url(#i0wBymb)" class="tobb-5f3c"/><circle fill="url(#i5B04wi)" class="tobb-5f3c"/></g><g filter="url(#izYXbVb)"><circle class="h88_-5b3g"/></g><g filter="url(#ij4Avgc)"><circle class="lbkb08b7q"/></g><g filter="url(#iww2Lbc)"><circle class="a6mi8bcxq"/></g><g filter="url(#ihPjklD)"><circle fill="url(#igxjaic)" class="rqzct4dku"/><circle fill="url(#iH9PggR)" class="rqzct4dku"/></g><g filter="url(#ix66lWb)"><circle fill="url(#iHcrFqe)" class="rg4_m7b_n"/></g><g filter="url(#inc1Sed)"><circle fill="url(#iNmQTwe)" class="lvm1e4qso"/></g><g filter="url(#i4p30Pc)"><path stroke="url(#iYpqpOA)" class="re4dv2b7j"/></g><g filter="url(#ijvYAgc)"><circle fill="url(#iAOwdSb)" class="vzna2gbis"/><circle fill="url(#iRCoLZs)" class="vzna2gbis"/></g><defs><radialGradient id="io8dnbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6034 4.55907 -5.6952 -.75377 15.746 17.073)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iwjkdQb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.93 17.341)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iM1Vz2c" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.947 10.165)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iCZZN0c" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 2.249 9.651)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iS1CTHb" cx="0" cy="0" r="1" gradientTransform="matrix(1.37443 2.61477 -3.62969 1.90792 12.528 6.513)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iIXquHb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.161 8.828)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="ibHH2Rc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.8448 23.557 13.72)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iFDk0ic" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.422 9.983)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="im5iLlb" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.427 -1.79)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i9CUWEd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.906 13.684)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ihQi12b" cx="0" cy="0" r="1" gradientTransform="matrix(.41273 -1.93102 2.1235 .45387 5.646 29.99)" gradientUnits="userSpaceOnUse"><stop class="g049h7flb"/><stop offset="1" class="hoqi9e01c"/></radialGradient><radialGradient id="iNUvqbF" cx="0" cy="0" r="1" gradientTransform="matrix(.40626 2.08282 -3.53623 .68974 25.776 28.73)" gradientUnits="userSpaceOnUse"><stop class="k5zu23s6k"/><stop offset="0" class="bp0jotlxe"/><stop offset="1" class="z54rox6ux"/></radialGradient><radialGradient id="iZIIgrd" cx="0" cy="0" r="1" gradientTransform="matrix(.153 1.2035 -2.47782 .31501 25.009 28.28)" gradientUnits="userSpaceOnUse"><stop offset=".812" class="cunr-1bwb"/><stop offset=".95" class="yind2xb3b"/></radialGradient><radialGradient id="iecRI9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.41638 0 8.4 28.49)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="jypakik4k"/><stop offset="1" class="spc75r5za"/></radialGradient><radialGradient id="iDsAFBc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65087 -5.32423 3.75234 -1.16348 7.152 27.94)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="z_f48dbjf"/><stop offset="1" class="mjrstybho"/></radialGradient><radialGradient id="iSPlgje" cx="0" cy="0" r="1" gradientTransform="matrix(-.31987 0 0 -6.06796 8.41 25.857)" gradientUnits="userSpaceOnUse"><stop offset=".323" class="kf6yzhcxx"/><stop offset="1" class="if8ggt7lg"/></radialGradient><radialGradient id="ic2fKLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.37502 3.78125 -4.19096 -.41565 7.463 25.52)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="jhbwcacjr"/><stop offset="1" class="lxwln9mzq"/></radialGradient><radialGradient id="ijG4gop" cx="0" cy="0" r="1" gradientTransform="matrix(4.71875 -5.90625 1.33451 1.0662 23.995 28.584)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="lkxhe0bym"/><stop offset="1" class="zn9diyb1a"/></radialGradient><radialGradient id="ir2U4mb" cx="0" cy="0" r="1" gradientTransform="matrix(2.6562 6.25003 -5.11847 2.1753 23.495 23.052)" gradientUnits="userSpaceOnUse"><stop class="k3jt88b8m"/><stop offset=".783" class="k3jt88b8m"/><stop offset="1" class="t70q9k_cc"/></radialGradient><radialGradient id="i0MLaVu" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 0 0 8.2125 23.37 27.709)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="lqhq5vk7o"/><stop offset="1" class="axbh60bsz"/></radialGradient><radialGradient id="iFO9tQd" cx="0" cy="0" r="1" gradientTransform="matrix(4.625 -4.96875 2.03088 1.89038 22.65 23.74)" gradientUnits="userSpaceOnUse"><stop class="rlxb2vbdo"/><stop offset="1" class="h55xk6bmz"/></radialGradient><radialGradient id="ipazNNu" cx="0" cy="0" r="1" gradientTransform="matrix(-3.51563 0 0 -10.7812 23.635 26.459)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="toy3i-56q"/><stop offset="1" class="a3n886b5x"/></radialGradient><radialGradient id="iDczi2Q" cx="0" cy="0" r="1" gradientTransform="matrix(-6.28125 0 0 -5.36523 21.588 22.521)" gradientUnits="userSpaceOnUse"><stop class="dos8-9u_k"/><stop offset="1" class="pl5e650bo"/></radialGradient><radialGradient id="iNI3hFF" cx="0" cy="0" r="1" gradientTransform="rotate(-137.291 13.972 10.311)scale(6.08156 10.1177)" gradientUnits="userSpaceOnUse"><stop class="kn91wbcgn"/><stop offset="1" class="pp-9_rbxu"/></radialGradient><radialGradient id="iieMYre" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.71875 -2.14693 0 16.048 21.084)" gradientUnits="userSpaceOnUse"><stop offset=".345" class="nrtpelbiw"/><stop offset="1" class="e94hoibvo"/></radialGradient><radialGradient id="i00GMMe" cx="0" cy="0" r="1" gradientTransform="rotate(147.829 4.211 11.914)scale(2.28894 1.32268)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="qum1lbccv"/><stop offset="1" class="mdtcyh1ih"/></radialGradient><radialGradient id="ipANa1b" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 .42188 -.21565 .65493 18.23 20.146)" gradientUnits="userSpaceOnUse"><stop class="pufhr-bjg"/><stop offset="1" class="in90z0bot"/></radialGradient><radialGradient id="ia8sqld" cx="0" cy="0" r="1" gradientTransform="matrix(2.01827 2.87604 -4.28662 3.00815 10.289 19.897)" gradientUnits="userSpaceOnUse"><stop class="zmea0ybye"/><stop offset="1" class="ldjgmybhi"/></radialGradient><radialGradient id="ifi30ue" cx="0" cy="0" r="1" gradientTransform="matrix(4.55232 5.22072 -.2143 .18687 10.393 21.734)" gradientUnits="userSpaceOnUse"><stop class="bmln26pap"/><stop offset="1" class="yb1xaiemt"/></radialGradient><radialGradient id="iRI4m7h" cx="0" cy="0" r="1" gradientTransform="rotate(122.137 5.436 17.063)scale(.71964 .79411)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="vfe9g3b6u"/><stop offset="1" class="kth1ncger"/></radialGradient><radialGradient id="iolaald" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.62442 -16.4807 0 15.992 22.99)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="uzx-du17j"/><stop offset="1" class="sbez_4byf"/></radialGradient><radialGradient id="iHUwowc" cx="0" cy="0" r="1" gradientTransform="rotate(-128.685 14.192 8.127)scale(6.16923 8.90183)" gradientUnits="userSpaceOnUse"><stop class="yq-enfbyo"/><stop offset="1" class="vnj030ucl"/></radialGradient><radialGradient id="iPmHRmc" cx="0" cy="0" r="1" gradientTransform="rotate(24.193 -1.558 .6)scale(1.18194)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="pmg10qb6b"/><stop offset="1" class="q-wkihbps"/></radialGradient><radialGradient id="ianTTFc" cx="0" cy="0" r="1" gradientTransform="rotate(26.328 -1.599 1.184)scale(1.69104)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="fkfx3o27i"/><stop offset="1" class="voqk07baz"/></radialGradient><radialGradient id="ihF3OKd" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 .59375 -.52749 .58302 .469 .637)" gradientUnits="userSpaceOnUse"><stop class="ls12e09pb"/><stop offset="1" class="tfsbwvbnl"/></radialGradient><radialGradient id="iUtrbGD" cx="0" cy="0" r="1" gradientTransform="rotate(17.956 -3.342 1.542)scale(1.7739 2.2924)" gradientUnits="userSpaceOnUse"><stop offset=".485" class="ceou1rsni"/><stop offset="1" class="tknr5ybzo"/></radialGradient><radialGradient id="ixjPQUb" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .57812 -.5501 .66904 .563 .832)" gradientUnits="userSpaceOnUse"><stop class="z9cu3vbra"/><stop offset="1" class="t2krvpb6g"/></radialGradient><radialGradient id="ikD1Ide" cx="0" cy="0" r="1" gradientTransform="rotate(-124.498 1.26 .614)scale(1.07592)" gradientUnits="userSpaceOnUse"><stop class="biu9whxny"/><stop offset="1" class="eh1sqyczn"/></radialGradient><radialGradient id="isuVgPF" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 -.0625 .06517 1.79228 .39 1.254)" gradientUnits="userSpaceOnUse"><stop offset=".541" class="kr7xbubfl"/><stop offset=".978" class="ftn-nj88l"/></radialGradient><radialGradient id="iuTMqgc" cx="0" cy="0" r="1" gradientTransform="rotate(150.945 4.004 11.562)scale(1.93043)" gradientUnits="userSpaceOnUse"><stop offset=".105" class="oj0sgcj4p"/><stop offset="1" class="eapmb-b-r"/></radialGradient><radialGradient id="iMTto5b" cx="0" cy="0" r="1" gradientTransform="matrix(1.08593 -.28907 .36133 1.35742 11.784 20.201)" gradientUnits="userSpaceOnUse"><stop class="vavjlxdpa"/><stop offset="1" class="o8dw4p7vp"/></radialGradient><radialGradient id="ibKaeAo" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.58594 1.12396 -.38964 12.745 21.03)" gradientUnits="userSpaceOnUse"><stop class="n6j5avbvg"/><stop offset="1" class="pj5su6bsv"/></radialGradient><radialGradient id="izwboXE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03125 .53906 -.49728 -.95134 13.245 21.584)" gradientUnits="userSpaceOnUse"><stop class="rr9pqccyi"/><stop offset="1" class="j-hgq5bil"/></radialGradient><radialGradient id="ijSHste" cx="0" cy="0" r="1" gradientTransform="rotate(-90 17.69 5.054)scale(1.30078)" gradientUnits="userSpaceOnUse"><stop class="xjhzw6b4m"/><stop offset="1" class="vlr1jy-qw"/></radialGradient><radialGradient id="iqdo5md" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 -.32812 .45767 -.741 13.659 22.81)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="da38a73_c"/><stop offset="1" class="kijt7rb5s"/></radialGradient><radialGradient id="iRxLk5d" cx="0" cy="0" r="1" gradientTransform="rotate(16.869 -67.097 54.03)scale(1.26538)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="d7gnwkbua"/><stop offset="1" class="xg0mdnbqj"/></radialGradient><radialGradient id="iY7ZVWc" cx="0" cy="0" r="1" gradientTransform="rotate(144.31 3.603 13.786)scale(1.36591)" gradientUnits="userSpaceOnUse"><stop class="fg8vwkbfq"/><stop offset="1" class="kqlr11b-y"/><stop offset="1" class="gsgx-m-kb"/></radialGradient><radialGradient id="ibnwHYt" cx="0" cy="0" r="1" gradientTransform="matrix(2 -.98437 1.00596 2.04386 13.573 23.443)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="fga1l482e"/><stop offset="1" class="owyqbq1bg"/></radialGradient><radialGradient id="iMGUs4b" cx="0" cy="0" r="1" gradientTransform="rotate(69.444 -9.015 21.41)scale(2.0025 1.86717)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="cy4ujdbiq"/><stop offset=".942" class="esixkvbpd"/></radialGradient><radialGradient id="ie2nM2s" cx="0" cy="0" r="1" gradientTransform="matrix(-.48437 -.0547 .10997 -.97398 15.159 23.49)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="u-wvucrhg"/><stop offset="1" class="yidq71bjl"/></radialGradient><radialGradient id="iHzkxde" cx="0" cy="0" r="1" gradientTransform="rotate(144.31 4.424 14.318)scale(1.36591)" gradientUnits="userSpaceOnUse"><stop class="xf3nhjbpw"/><stop offset="1" class="kqlr11b-y"/></radialGradient><radialGradient id="i7dGJyb" cx="0" cy="0" r="1" gradientTransform="rotate(-142.172 12.357 9.09)scale(1.68149 1.71836)" gradientUnits="userSpaceOnUse"><stop offset=".472" class="xpqto8b3q"/><stop offset="1" class="gag6ovb3k"/></radialGradient><radialGradient id="iR45lBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.64062 1.9375 -1.79684 -.5941 16.276 22.85)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="fr4aurb9m"/><stop offset=".904" class="fpyoctiow"/></radialGradient><radialGradient id="i3ByHib" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.95218 4.0625 0 15.916 21.928)" gradientUnits="userSpaceOnUse"><stop class="lwf2kfb4z"/><stop offset="1" class="vje6nvbee"/></radialGradient><radialGradient id="itzezLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.10937 -2.08655 0 16.003 20.088)" gradientUnits="userSpaceOnUse"><stop class="wcds6xmsi"/><stop offset="1" class="uiuchnbor"/></radialGradient><radialGradient id="iyvU48c" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 27.696 -15.255)scale(2.73591 3.34042)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iszy3Td" cx="0" cy="0" r="1" gradientTransform="matrix(1.31576 .7375 -.2085 .37199 21.118 12.891)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iD0ouLb" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.44 14.684)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iB8Kj9c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.447 14.572)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="i3H80vd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50357 2.99901 -4.01413 -8.70492 18.907 14.035)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iZJzQqF" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46116 .45112 -.49796 -3.82051 19.3 15.397)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iKb2ejV" cx="0" cy="0" r="1" gradientTransform="matrix(1.30737 -3.78806 4.80634 1.6588 13.668 21.364)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="id9ci0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.72467 -7.78405 0 16.048 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="vrhnsgvqh"/><stop offset="1" class="iuch0hb0l"/></radialGradient><radialGradient id="ieQFuNb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.163 8.75)scale(7.03738 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="i0QmVcg" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.35 13.616)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iLBFlse" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.971 13.388)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="iiJLsjd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.143 15.104)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="iP4Xfje" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 4 -6.96848 2.28654 13.863 8.036)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="iLetnwb" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.833 15.83)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="ibsX0qc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.593 16.042)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="idDALsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.23 13.975)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iWTvJoe" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18.002 14.06)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iBthudd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.866 13.975)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ifgUU9d" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.777 .413)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iDNf9iv" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 14.43 -2.166)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iLVVDFG" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.89 8.97)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iwahn7j" cx="0" cy="0" r="1" gradientTransform="matrix(-.21034 1.3672 -2.94144 -.45253 16.258 7.017)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="icRhpDc" cx="0" cy="0" r="1" gradientTransform="rotate(117.967 9.13 10.283)scale(1.06405 1.3957)" gradientUnits="userSpaceOnUse"><stop offset=".265" class="dakdtmo8r"/><stop offset="1" class="arn54kl4j"/></radialGradient><radialGradient id="iQREtnd" cx="0" cy="0" r="1" gradientTransform="matrix(.33234 -.2841 .1844 .21572 22.489 7.084)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="n-7gz4alz"/><stop offset="1" class="v8gtn-b7b"/></radialGradient><radialGradient id="iBRKmve" cx="0" cy="0" r="1" gradientTransform="matrix(.69557 .35875 -.43597 .8453 9.317 7.265)" gradientUnits="userSpaceOnUse"><stop class="sti3oxbeq"/><stop offset="1" class="x5-3y6xrq"/></radialGradient><radialGradient id="iVERpqe" cx="0" cy="0" r="1" gradientTransform="matrix(.07422 .35146 -.52397 .11065 12.276 5.217)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="itk3z-5ip"/><stop offset="1" class="j8q5y3jei"/></radialGradient><radialGradient id="iw9QqUc" cx="0" cy="0" r="1" gradientTransform="rotate(-80.737 13.6 -8.133)scale(1.02905 .94206)" gradientUnits="userSpaceOnUse"><stop class="nj0s1tj2o"/><stop offset="1" class="z1-7jowoz"/></radialGradient><radialGradient id="iBqn1xd" cx="0" cy="0" r="1" gradientTransform="matrix(-.4922 -1.07031 .2266 -.1042 20.526 6.217)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="o9ez09qax"/><stop offset="1" class="qrzlg2j4q"/></radialGradient><radialGradient id="iwacREz" cx="0" cy="0" r="1" gradientTransform="matrix(.10156 .3749 -.50936 .138 19.854 5.217)" gradientUnits="userSpaceOnUse"><stop offset=".299" class="hv46-obcm"/><stop offset="1" class="g7x6q-lxe"/></radialGradient><radialGradient id="ic9SDUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.97508 .53473 -.2619 -.47757 20.426 4.355)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="byw-t0bic"/></radialGradient><radialGradient id="iQiXRXd" cx="0" cy="0" r="1" gradientTransform="matrix(.62908 -.93084 .84184 .56893 19.403 5.412)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><radialGradient id="iDI5g0V" cx="0" cy="0" r="1" gradientTransform="matrix(-.97508 .53473 -.2619 -.47757 12.8 4.355)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="t36lxpgxn"/></radialGradient><radialGradient id="i53KubP" cx="0" cy="0" r="1" gradientTransform="matrix(.62908 -.93084 .84184 .56893 11.778 5.412)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><radialGradient id="iEEEWSb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.01175 4.40623 -6.6297 -3.02692 18.026 4.74)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="aet_92b8f"/><stop offset="1" class="rfjsk2b_a"/></radialGradient><radialGradient id="iWRW5Zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.67579 8.23047 0 16.014 8.74)" gradientUnits="userSpaceOnUse"><stop class="yexd1o2nx"/><stop offset="1" class="ue47neksc"/></radialGradient><radialGradient id="ieWHizW" cx="0" cy="0" r="1" gradientTransform="rotate(154.043 10.593 5.217)scale(3.62333 .22378)" gradientUnits="userSpaceOnUse"><stop offset=".097" class="m7zijhbgc"/><stop offset="1" class="lkpz06t1a"/></radialGradient><radialGradient id="ihSSm7d" cx="0" cy="0" r="1" gradientTransform="rotate(61.663 .03 10.263)scale(2.48532 2.58254)" gradientUnits="userSpaceOnUse"><stop class="l4i7jj__c"/><stop offset="1" class="z2xtp70hc"/></radialGradient><radialGradient id="iBw0BYb" cx="0" cy="0" r="1" gradientTransform="matrix(2.95313 1.56248 -.1016 .19204 9.338 5.084)" gradientUnits="userSpaceOnUse"><stop offset=".387" class="pmc291bsf"/><stop offset="1" class="tjgrrcbfz"/></radialGradient><radialGradient id="ifeMfDb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 1.375 -.42997 -.36157 22.62 5.24)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="vb43as5rm"/><stop offset="1" class="kvxx5e97u"/></radialGradient><radialGradient id="izm3X0b" cx="0" cy="0" r="1" gradientTransform="rotate(175.929 7.948 1.952)scale(1.10043 .71838)" gradientUnits="userSpaceOnUse"><stop class="bfog00mit"/><stop offset="1" class="tk7r3ryjq"/></radialGradient><radialGradient id="iZzVw3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.96874 .53125 -.2602 -.47447 9.645 4.834)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="t36lxpgxn"/></radialGradient><radialGradient id="ilaTEnd" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.9248 .83637 .56524 8.629 5.884)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><radialGradient id="i0wBymb" cx="0" cy="0" r="1" gradientTransform="matrix(-.96874 .53125 -.2602 -.47447 23.573 4.834)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="t36lxpgxn"/></radialGradient><radialGradient id="i5B04wi" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.9248 .83637 .56524 22.557 5.884)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><radialGradient id="igxjaic" cx="0" cy="0" r="1" gradientTransform="rotate(-90 11.776 -4.218)scale(1.36805)" gradientUnits="userSpaceOnUse"><stop class="m8_9xackt"/><stop offset="1" class="sblhzud6f"/></radialGradient><radialGradient id="iH9PggR" cx="0" cy="0" r="1" gradientTransform="matrix(.88821 -.82696 .53708 .57686 16.426 6.66)" gradientUnits="userSpaceOnUse"><stop class="jxvb9w84e"/><stop offset="1" class="a-oylkk7f"/></radialGradient><radialGradient id="iHcrFqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.72788 .60361 -.58534 -.70585 19.74 7.24)" gradientUnits="userSpaceOnUse"><stop class="wmixudboe"/><stop offset="1" class="bzekojbcn"/></radialGradient><radialGradient id="iNmQTwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.72788 .60361 -.58534 -.70585 12.986 7.24)" gradientUnits="userSpaceOnUse"><stop class="wmixudboe"/><stop offset="1" class="bzekojbcn"/></radialGradient><radialGradient id="iAOwdSb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10171 .60417 -.29591 -.5396 16.692 2.515)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="t36lxpgxn"/></radialGradient><radialGradient id="iRCoLZs" cx="0" cy="0" r="1" gradientTransform="matrix(.71079 -1.05173 .95117 .64282 15.538 3.709)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><filter id="ivVZbqb" width="15.268" height="15.768" x="8.539" y="5.294" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="iXrRStc" width="13.918" height="7.56" x="8.979" y="21.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".075"/></filter><filter id="iiG6n5c" width="14.05" height="7.692" x="8.967" y="21.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.364706 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.498039 0 0 0 0 0.890196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3073" result="effect2_innerShadow_4002_3073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.345098 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3073" result="effect3_innerShadow_4002_3073"/></filter><filter id="izBx3fd" width="10.238" height="6.794" x="10.485" y="18.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".325"/></filter><filter id="ipBEphd" width="2.05" height="2.05" x="11.382" y="18.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.478431 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="iFGJULh" width="2.1" height="2.1" x="11.932" y="20.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.698039 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="iwCw5Kc" width="2.05" height="2.05" x="13.198" y="22.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.72549 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="iYglVZb" width="2.05" height="2.05" x="14.995" y="22.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.72549 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="iZvJUwd" width="3.368" height="3.218" x="9.753" y="12.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="iEfAtRc" width="3.218" height="3.468" x="19.266" y="12.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="i9p7MBc" width="3.148" height="3.148" x="19.301" y="12.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".25"/></filter><filter id="is4hknd" width="2.948" height="2.948" x="9.907" y="13.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".2"/></filter><filter id="i6mkuZc" width="10.191" height="11.277" x="10.953" y="9.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="ippQuFe" width="2.877" height="3.682" x="14.447" y="13.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".25"/></filter><filter id="iG4Q01c" width="2.377" height="3.182" x="14.859" y="13.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".125"/></filter><filter id="irfgRle" width="2.377" height="3.182" x="14.859" y="13.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".125"/></filter><filter id="ifvIqae" width="3.702" height="1.526" x="14.197" y="16.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".05"/></filter><filter id="iAqZned" width="3.001" height="1.285" x="16.99" y="13.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="iavnGve" width="3.001" height="1.285" x="12.105" y="13.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="imKzlve" width="2.453" height="1.091" x="12.24" y="11.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="iw4SZNd" width="2.453" height="1.091" x="17.657" y="11.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="iHS9uUR" width=".787" height=".696" x="17.496" y="13.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".05"/></filter><filter id="iIbuRDb" width=".891" height=".913" x="18.336" y="13.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".1"/></filter><filter id="iDTB0AS" width=".986" height="1.04" x="13.893" y="13.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".1"/></filter><filter id="ilRxLOl" width=".913" height=".705" x="13.138" y="13.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".05"/></filter><filter id="ipWbRle" width="2.261" height=".978" x="17.688" y="11.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".1"/></filter><filter id="inNF1Nd" width="2.261" height=".978" x="12.236" y="11.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".1"/></filter><filter id="iPUkNcc" width="4.212" height="4.513" x="9.794" y="7.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/><feGaussianBlur result="effect2_foregroundBlur_4002_3073" stdDeviation=".15"/></filter><filter id="igzM4zd" width="8.767" height="5.782" x="12.878" y="6.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/><feGaussianBlur result="effect2_foregroundBlur_4002_3073" stdDeviation=".125"/></filter><filter id="iykDy5d" width="1.145" height="2.31" x="12.857" y="7.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".1"/></filter><filter id="iZIKAGt" width="6.427" height="3.372" x="15.466" y="8.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".375"/></filter><filter id="iRjkJEb" width="10.911" height="1.365" x="10.492" y="7.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".2"/></filter><filter id="ihmJlQa" width="2.517" height="1.953" x="11.339" y="5.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.619608 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="iYlKzLb" width="1.604" height="1.554" x="19.053" y="3.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.639216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="izpqlFb" width="1.604" height="1.554" x="11.428" y="3.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.639216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="iagPdXd" width="13.93" height="5.045" x="9.049" y="3.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.619608 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="i0hWzfT" width="1.594" height="1.544" x="8.282" y="4.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.639216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="i18e53I" width="1.544" height="1.544" x="22.21" y="4.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.611765 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="izYXbVb" width="3.152" height="3.152" x="14.222" y="5.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".25"/></filter><filter id="ij4Avgc" width="2.116" height="2.116" x="18.116" y="6.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".25"/></filter><filter id="iww2Lbc" width="2.116" height="2.116" x="11.363" y="6.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".25"/></filter><filter id="ihPjklD" width="2.152" height="2.152" x="14.917" y="6.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.168627 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="ix66lWb" width="1.116" height="1.166" x="18.812" y="6.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.619608 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="inc1Sed" width="1.116" height="1.166" x="12.058" y="6.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.619608 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><filter id="i4p30Pc" width="6.248" height="3.259" x="15.987" y="3.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3073" stdDeviation=".025"/></filter><filter id="ijvYAgc" width="1.799" height="1.749" x="15.143" y="1.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.639216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3073"/></filter><linearGradient id="i93E6Rd" x1="20.741" x2="13.936" y1="7.62" y2="20.224" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="ikQH8cb" x1="8.354" x2="8.104" y1="29.819" y2="29.819" gradientUnits="userSpaceOnUse"><stop class="x8dk6bl6o"/><stop offset="1" class="g-8u40lzl"/></linearGradient><linearGradient id="iLkQkbd" x1="23.635" x2="23.842" y1="29.99" y2="29.99" gradientUnits="userSpaceOnUse"><stop class="qrto2_zpw"/><stop offset="1" class="z2_l0sbav"/></linearGradient><linearGradient id="iyormFc" x1="23.932" x2="11.557" y1="29.99" y2="29.99" gradientUnits="userSpaceOnUse"><stop class="k_ugj6bqp"/><stop offset="1" class="etwgthjom"/></linearGradient><linearGradient id="iAhj8Hn" x1="18.463" x2="13.276" y1="27.646" y2="20.99" gradientUnits="userSpaceOnUse"><stop class="y-c-j769e"/><stop offset="1" class="t9knx544b"/></linearGradient><linearGradient id="iB6tLsc" x1="9.682" x2="13.727" y1="21.713" y2="28.005" gradientUnits="userSpaceOnUse"><stop class="odnc1cb0i"/><stop offset="1" class="foqmp2bms"/></linearGradient><linearGradient id="ifGDHuc" x1="19.422" x2="17.302" y1="20.2" y2="24.136" gradientUnits="userSpaceOnUse"><stop class="p3p7o2c-x"/><stop offset="1" class="ix1r05d7h"/></linearGradient><linearGradient id="iLPP77c" x1="17.516" x2="13.823" y1="21.115" y2="21.115" gradientUnits="userSpaceOnUse"><stop class="b3foffbqy"/><stop offset="1" class="d2lyakdiu"/></linearGradient><linearGradient id="iRlr9qc" x1="13.87" x2="14.604" y1="20.318" y2="20.389" gradientUnits="userSpaceOnUse"><stop class="l6yh11bhx"/><stop offset="1" class="y5c3ymb4e"/></linearGradient><linearGradient id="ilABBKc" x1="8.808" x2="23.184" y1="19.402" y2="19.402" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i30rZSc" x1="8.808" x2="23.184" y1="19.372" y2="19.372" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ifsmvKb" x1="9.753" x2="12.713" y1="14.66" y2="14.66" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iH7iAbe" x1="15.109" x2="16.048" y1="15.904" y2="15.904" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="i12toIb" x1="16.048" x2="16.048" y1="16.703" y2="16.092" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="izxUd1H" x1="16.048" x2="16.048" y1="13.747" y2="15.278" gradientUnits="userSpaceOnUse"><stop class="y2qr1gb4g"/><stop offset="1" class="vunpjbdrs"/></linearGradient><linearGradient id="iqA2n8d" x1="14.984" x2="15.445" y1="18.112" y2="17.4" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient><linearGradient id="iI5SCYP" x1="19.008" x2="18.694" y1="14.029" y2="14.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibJtQUd" x1="14.61" x2="14.296" y1="14.029" y2="14.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJcWXlu" x1="13.157" x2="13.701" y1="8.374" y2="9.648" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iUZ7Ske" x1="11.885" x2="13.229" y1="5.959" y2="5.912" gradientUnits="userSpaceOnUse"><stop class="pd0xkfcwk"/><stop offset="1" class="mjtjw9d9u"/></linearGradient><linearGradient id="iS293Ii" x1="16.745" x2="16.745" y1="8.709" y2="8.334" gradientUnits="userSpaceOnUse"><stop class="sc708_bbk"/><stop offset="1" class="i_l5iobrn"/></linearGradient><linearGradient id="iYpqpOA" x1="16.042" x2="22.167" y1="3.803" y2="5.631" gradientUnits="userSpaceOnUse"><stop class="rapvxtblm"/><stop offset=".144" class="phj38-blk"/><stop offset=".842" class="zxi6lwb9j"/><stop offset="1" class="nu4sh_bsg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:princess-light" /></template>
<style>
.a-oylkk7f {
  stop-color: var(--svg-color--fc586e, #FC586E);
  stop-opacity: 0;
}

.a3n886b5x {
  stop-color: var(--svg-color--907bd1, #907BD1);
  stop-opacity: 0;
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
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

.a8s6nf2ic {
  d: path("M18.166 13.687c.064.085-.069.188-.22.301s-.263.193-.327.108s.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.aet_92b8f {
  stop-color: var(--svg-color--edad5e, #EDAD5E);
}

.arn54kl4j {
  stop-color: var(--svg-color--3293cc, #3293CC);
}

.aszcv_87a {
  fill: var(--svg-color--000, #000);
  d: path("M17.72 14.39a.51.51 0 0 1 .512-.51a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.236");
}

.axbh60bsz {
  stop-color: var(--svg-color--6d4bc2, #6D4BC2);
  stop-opacity: 0;
}

.b3foffbqy {
  stop-color: var(--svg-color--e1ac9c, #E1AC9C);
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.bfog00mit {
  stop-color: var(--svg-color--d79747, #D79747);
}

.bg-hvbbga {
  d: path("m15.666 14.03l-.532 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.biu9whxny {
  stop-color: var(--svg-color--d69fd3, #D69FD3);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bmln26pap {
  stop-color: var(--svg-color--7a5298, #7A5298);
}

.bp0jotlxe {
  stop-color: var(--svg-color--9c76eb, #9C76EB);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.byw-t0bic {
  stop-color: var(--svg-color--d9a83d, #D9A83D);
}

.bzekojbcn {
  stop-color: var(--svg-color--3caef0, #3CAEF0);
}

.c38snlpyv {
  fill: var(--svg-color--271612, #271612);
  d: path("M10.898 8.34h10.105v.566s-3.685-.565-10.105 0c-.013-.22 0-.565 0-.565");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.ceou1rsni {
  stop-color: var(--svg-color--d3b0a8, #D3B0A8);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm8_bn2mq {
  d: path("M20.256 5.712c.1.175.302.541.391.703l-1.515.755l-.902-.903l.902-.785c.114-.104.36-.294.582-.261c.248.036.417.272.542.49");
}

.cu6bo-a-n {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.19 14.004c.265-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.269.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.079-.45");
}

.cunr-1bwb {
  stop-color: var(--svg-color--7d48de, #7D48DE);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cy4ujdbiq {
  stop-color: var(--svg-color--e7c7ff, #E7C7FF);
  stop-opacity: 0;
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d2lyakdiu {
  stop-color: var(--svg-color--c58b7a, #C58B7A);
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

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dos8-9u_k {
  stop-color: var(--svg-color--ffd1b9, #FFD1B9);
}

.dvd_3xbng {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.655 14.35l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.493-.377-.613 0");
}

.dvuac4bxb {
  cx: 15.995px;
  cy: 23.596px;
  r: 1px;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.e304mibzr {
  d: path("M21.187 25.801a3.502 3.502 0 1 0 7.004 0c0-1.934-1.568-3.389-3.502-3.389c-3.782 0-3.502 1.455-3.502 3.389");
}

.e94hoibvo {
  stop-color: var(--svg-color--e8b49f, #E8B49F);
  stop-opacity: 0;
}

.ean9ofhjo {
  r: 1px;
}

.eapmb-b-r {
  stop-color: var(--svg-color--c0abb3, #C0ABB3);
}

.eh1sqyczn {
  stop-color: var(--svg-color--d69fd3, #D69FD3);
  stop-opacity: 0;
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.esixkvbpd {
  stop-color: var(--svg-color--cc9dd5, #CC9DD5);
}

.etwgthjom {
  stop-color: var(--svg-color--755cc0, #755CC0);
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.fg8vwkbfq {
  stop-color: var(--svg-color--fce9ff, #FCE9FF);
}

.fga1l482e {
  stop-color: var(--svg-color--efd2c5, #EFD2C5);
  stop-opacity: 0;
}

.fjtps8bgo {
  d: path("M13.864 13.498a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
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

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fyucgebtp {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.988 12.2c.322-.079 1.124-.04 1.66.344");
}

.g-8u40lzl {
  stop-color: var(--svg-color--7045c9, #7045C9);
  stop-opacity: 0;
}

.g049h7flb {
  stop-color: var(--svg-color--8461d2, #8461D2);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
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

.gfzgh5bel {
  d: path("M16.018 19.373h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gsgx-m-kb {
  stop-color: var(--svg-color--e0ccec, #E0CCEC);
}

.gutnx8b0t {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.906 14.004c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.08-.45");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h55xk6bmz {
  stop-color: var(--svg-color--7a5fc2, #7A5FC2);
  stop-opacity: 0;
}

.h88_-5b3g {
  cx: 15.798px;
  cy: 7.269px;
  r: 1.076px;
  fill: var(--svg-color--d37b55, #D37B55);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hoqi9e01c {
  stop-color: var(--svg-color--845bd7, #845BD7);
}

.huvog8bmh {
  d: path("m9.05 5.572l1.272 2.876a.15.15 0 0 0 .138.09h11.056a.15.15 0 0 0 .136-.088l1.327-2.878l-.187-.437c-.438.19-1.124.521-1.736.816c-.43.207-.824.397-1.07.508c-.403.183-.857.087-1.046-.125c-.25-.28-.711-.81-1.14-1.305c-.35-.402-.677-.779-.852-.976c-.342-.386-.722-.453-.914-.46l-.02-.001h-.02c-.192.007-.571.075-.913.46c-.175.198-.503.575-.852.977c-.43.494-.89 1.025-1.14 1.305c-.19.212-.643.308-1.047.125a64 64 0 0 1-1.07-.508a62 62 0 0 0-1.735-.816z");
}

.hv46-obcm {
  stop-color: var(--svg-color--c98b19, #C98B19);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i_l5iobrn {
  stop-color: var(--svg-color--f9711e, #F9711E);
  stop-opacity: 0;
}

.if8ggt7lg {
  stop-color: var(--svg-color--6046a6, #6046A6);
  stop-opacity: 0;
}

.ig99y4b1u {
  fill: var(--svg-color--000, #000);
  d: path("M14.375 14.39a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .061-.236");
}

.ighfy72rq {
  d: path("M20.875 15.646a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.iljlxyb3g {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.65 12.795l-.004.002a.268.268 0 0 1-.276-.46h.002l.003-.003l.01-.005l.032-.018q.04-.023.116-.059c.098-.047.239-.107.41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a2.7 2.7 0 0 0-.456.194");
}

.in90z0bot {
  stop-color: var(--svg-color--b57a5b, #B57A5B);
  stop-opacity: 0;
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.inuz7fbaa {
  fill-rule: evenodd;
  d: path("m14.07 27.625l-4.954-5.688a.2.2 0 0 1 .025-.286l.536-.434a.2.2 0 0 1 .276.024l4.949 5.664c.558.566 1.784.464 2.19.002l4.939-5.657a.2.2 0 0 1 .273-.026l.537.418a.2.2 0 0 1 .027.289l-4.946 5.697c-1.032 1.26-2.673 1.37-3.852-.003");
}

.itk3z-5ip {
  stop-color: var(--svg-color--d59b33, #D59B33);
}

.iuch0hb0l {
  stop-color: var(--svg-color--b4807e, #B4807E);
}

.ix1r05d7h {
  stop-color: var(--svg-color--bc7e5f, #BC7E5F);
  stop-opacity: 0;
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j-hgq5bil {
  stop-color: var(--svg-color--d5c2e3, #D5C2E3);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j8q5y3jei {
  stop-color: var(--svg-color--d59b33, #D59B33);
  stop-opacity: 0;
}

.jhbwcacjr {
  stop-color: var(--svg-color--7143c9, #7143C9);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jvmoe0w6d {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.454 10.391l-1.425.262a.688.688 0 1 1-.125-1.364h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
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

.k0t4ahufu {
  d: path("M11.362 16.182a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k3jt88b8m {
  stop-color: var(--svg-color--866bca, #866BCA);
  stop-opacity: 0;
}

.k5zu23s6k {
  stop-color: var(--svg-color--9c78ec, #9C78EC);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
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

.kn91wbcgn {
  stop-color: var(--svg-color--f5bfb6, #F5BFB6);
}

.kqlr11b-y {
  stop-color: var(--svg-color--d4c1d3, #D4C1D3);
}

.kr7xbubfl {
  stop-color: var(--svg-color--dcc4d2, #DCC4D2);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kth1ncger {
  stop-color: var(--svg-color--9376c4, #9376C4);
  stop-opacity: 0;
}

.kvxx5e97u {
  stop-color: var(--svg-color--ce8f45, #CE8F45);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l4i7jj__c {
  stop-color: var(--svg-color--daa24e, #DAA24E);
}

.l6yh11bhx {
  stop-color: var(--svg-color--a86e5a, #A86E5A);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lbkb08b7q {
  cx: 19.175px;
  cy: 7.589px;
  r: 0.558px;
  fill: var(--svg-color--d37b55, #D37B55);
}

.ldjgmybhi {
  stop-color: var(--svg-color--ae836d, #AE836D);
  stop-opacity: 0;
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
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

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lqhq5vk7o {
  stop-color: var(--svg-color--6d4bc2, #6D4BC2);
}

.ls12e09pb {
  stop-color: var(--svg-color--fff8ff, #FFF8FF);
}

.lt5s5v7qd {
  d: path("M15.445 6.782c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.lvm1e4qso {
  cx: 12.616px;
  cy: 7.399px;
  r: 0.558px;
}

.lwf2kfb4z {
  stop-color: var(--svg-color--e7b39f, #E7B39F);
}

.lxwln9mzq {
  stop-color: var(--svg-color--7143c9, #7143C9);
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

.mdtcyh1ih {
  stop-color: var(--svg-color--996047, #996047);
  stop-opacity: 0;
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mgz8cwb4o {
  cx: 13.595px;
  cy: 13.88px;
  rx: 0.39px;
  ry: 0.197px;
}

.miowekbgu {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.048 17.484c-.52 0-1.01-.125-1.422-.345c-.14-.073-.291.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.mjrstybho {
  stop-color: var(--svg-color--635385, #635385);
}

.mjtjw9d9u {
  stop-color: var(--svg-color--f2bd5c, #F2BD5C);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mxq0h6ljd {
  cx: 19.805px;
  cy: 4.66px;
  r: 0.752px;
}

.n-7gz4alz {
  stop-color: var(--svg-color--53d8f2, #53D8F2);
}

.n0x7ebc8c {
  cx: 14.198px;
  cy: 23.111px;
  r: 1px;
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n261g_b5l {
  d: path("M16.348 19.373c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.n2v6nbcyb {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.382 15.646a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
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

.nj0s1tj2o {
  stop-color: var(--svg-color--c88c35, #C88C35);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nrtpelbiw {
  stop-color: var(--svg-color--e8b49f, #E8B49F);
}

.nu4sh_bsg {
  stop-color: var(--svg-color--f2bb64, #F2BB64);
  stop-opacity: 0;
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o2l5d5bss {
  d: path("M20.875 16.182a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.o5nkmlb_j {
  cx: 13.595px;
  cy: 13.88px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.o6_n3pbob {
  cx: 9.905px;
  cy: 7.313px;
  r: 0.558px;
}

.o6q5k3k5k {
  d: path("M10.979 8.584c.566-.6 1.636-.6 2.13-.511l.396 1.29c-.252-.039-.478.05-.667.235c-.449 1.26-1.99 1.956-2.704 2.146c-.149-1.492.109-2.38.845-3.16");
}

.o8dw4p7vp {
  stop-color: var(--svg-color--ba93b0, #BA93B0);
  stop-opacity: 0;
}

.o9ez09qax {
  stop-color: var(--svg-color--d3a150, #D3A150);
}

.ocqu7f-1v {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.197 12.2c-.323-.079-1.125-.04-1.661.344");
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

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ovkwvebhl {
  fill: var(--svg-color--7359bc, #7359BC);
  fill-rule: evenodd;
  d: path("m14.049 27.743l-4.871-5.548a.194.194 0 0 1 .024-.28l.527-.423a.2.2 0 0 1 .272.023l4.865 5.525c.549.552 2.02.666 2.418.215l4.782-5.522a.2.2 0 0 1 .27-.026l.336.2a.194.194 0 0 1 .027.281l-4.864 5.558c-1.014 1.229-2.627 1.336-3.786-.003");
}

.owyqbq1bg {
  stop-color: var(--svg-color--efd2c5, #EFD2C5);
}

.p3p7o2c-x {
  stop-color: var(--svg-color--bc7e5f, #BC7E5F);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
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

.pl5e650bo {
  stop-color: var(--svg-color--d7a49b, #D7A49B);
}

.pmc291bsf {
  stop-color: var(--svg-color--e3b560, #E3B560);
}

.pmg10qb6b {
  stop-color: var(--svg-color--fffaff, #FFFAFF);
}

.pp-9_rbxu {
  stop-color: var(--svg-color--f5bfb6, #F5BFB6);
  stop-opacity: 0;
}

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.ptxyeebxb {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.657 13.227c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.pufhr-bjg {
  stop-color: var(--svg-color--b57a5b, #B57A5B);
}

.pw1338b2k {
  d: path("M11.382 15.646a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.pyjhqsreq {
  d: path("M8.338 22.428c1.11-1.089 4.193-3.219 7.649-3.219s6.539 2.13 7.648 3.219v7.562H8.338z");
}

.q-wkihbps {
  stop-color: var(--svg-color--e5c8e2, #E5C8E2);
}

.q0597ob7u {
  cx: 9.029px;
  cy: 5.137px;
  r: 0.747px;
}

.q172lj3mg {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.166 13.687c.064.085-.069.188-.22.301s-.263.193-.327.108s.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.q8l1y6b0l {
  cx: 22.089px;
  cy: 7.324px;
  r: 0.558px;
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qrto2_zpw {
  stop-color: var(--svg-color--814fe0, #814FE0);
}

.qrzlg2j4q {
  stop-color: var(--svg-color--d3a150, #D3A150);
  stop-opacity: 0;
}

.qum1lbccv {
  stop-color: var(--svg-color--996047, #996047);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r-d41foqz {
  d: path("M14.68 14.286c0-.289-.235-.48-.299-.539l-.288.279l.177.361z");
}

.r04kwie6j {
  fill-rule: evenodd;
  d: path("M12.743 21.2a.98.98 0 1 0-.766.218a.98.98 0 0 0 .986 1.664a.98.98 0 0 0 1.668 1.01a.98.98 0 0 0 1.947 0a.978.978 0 0 0 1.766-.583a1 1 0 0 0-.098-.427q.167.066.358.067a.98.98 0 0 0 .628-1.73a.98.98 0 1 0-.766-.219a.98.98 0 0 0-.744 1.397a.98.98 0 0 0-1.331.803a.978.978 0 0 0-1.573 0a.98.98 0 0 0-1.332-.803a.98.98 0 0 0-.744-1.397");
}

.rapvxtblm {
  stop-color: var(--svg-color--efb65d, #EFB65D);
  stop-opacity: 0;
}

.re4dv2b7j {
  stroke-width: var(--svg-stroke-width--0-08px, 0.08px);
  d: path("M16.042 3.615c.098.01.432.13.664.348c.23.219 1.53 1.71 2.144 2.383c.207.226.568.502 1.2.246c.63-.256 1.674-.774 2.117-1");
}

.rfjsk2b_a {
  stop-color: var(--svg-color--e59e51, #E59E51);
}

.rg4_m7b_n {
  cx: 19.37px;
  cy: 7.399px;
  r: 0.558px;
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

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
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

.se2t1ybto {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.445 6.782c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.snp7jbbjy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.157 8.03c.023.243.234 1.157.544 1.71");
}

.spc75r5za {
  stop-color: var(--svg-color--805fc9, #805FC9);
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.sti3oxbeq {
  stop-color: var(--svg-color--33a6c5, #33A6C5);
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.t1po3obiw {
  d: path("M19.027 14.273a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
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

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tfsbwvbnl {
  stop-color: var(--svg-color--ebccff, #EBCCFF);
}

.tjgrrcbfz {
  stop-color: var(--svg-color--e3b560, #E3B560);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tk7r3ryjq {
  stop-color: var(--svg-color--d79747, #D79747);
  stop-opacity: 0;
}

.tknr5ybzo {
  stop-color: var(--svg-color--bd9b8f, #BD9B8F);
}

.tobb-5f3c {
  cx: 22.957px;
  cy: 5.137px;
  r: 0.747px;
}

.tohqxz6rz {
  d: path("M10.96 13.31h.013l-.01-.266l-.01-.306c.02-.949.574-1.316.81-1.438l.05-.02l.052-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.118 3.073c-.124 2.802-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.882-4.983-4.684z");
}

.toy3i-56q {
  stop-color: var(--svg-color--907bd1, #907BD1);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tsa08abfi {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.78 12.337l-.138.23za.268.268 0 0 1-.275.46l-.005-.002l-.021-.012l-.092-.047a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.093-.528c.513-.09.988.001 1.328.11a3.3 3.3 0 0 1 .558.238l.01.005l.003.002z");
}

.u-wvucrhg {
  stop-color: var(--svg-color--c3a8aa, #C3A8AA);
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ubtc8c7br {
  d: path("M18.232 13.498a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
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

.uiuchnbor {
  stop-color: var(--svg-color--d59b90, #D59B90);
  stop-opacity: 0;
}

.uj42qvbww {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.666 14.211l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.uzgzp1byj {
  d: path("m15.666 14.211l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.uzx-du17j {
  stop-color: var(--svg-color--945cee, #945CEE);
  stop-opacity: 0;
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v8gtn-b7b {
  stop-color: var(--svg-color--53d8f2, #53D8F2);
  stop-opacity: 0;
}

.vavjlxdpa {
  stop-color: var(--svg-color--cfbadc, #CFBADC);
}

.vb43as5rm {
  stop-color: var(--svg-color--ce8f45, #CE8F45);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vfe9g3b6u {
  stop-color: var(--svg-color--9376c4, #9376C4);
}

.vje6nvbee {
  stop-color: var(--svg-color--e7b39f, #E7B39F);
  stop-opacity: 0;
}

.vl7hh0bdy {
  d: path("m9.539 21.45l5.55 6.493h2.015l5.453-6.407c-1.49-1.075-3.92-2.327-6.57-2.327c-2.579 0-4.95 1.186-6.448 2.24");
}

.vlr1jy-qw {
  stop-color: var(--svg-color--ce9fd2, #CE9FD2);
  stop-opacity: 0;
}

.vnj030ucl {
  stop-color: var(--svg-color--ce8988, #CE8988);
  stop-opacity: 0;
}

.voqk07baz {
  stop-color: var(--svg-color--b89174, #B89174);
}

.vqzrhj3rz {
  fill-rule: evenodd;
  d: path("M23.233 15.982c.213-.435.324-.921.324-1.427a3.3 3.3 0 0 0-.268-1.306h.005a3 3 0 0 0-.281-.513l-.003-.003a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.215 3.298v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.121-.982-.324-1.407a.51.51 0 0 1 0-.455m-12.26-2.673h-.012l1.198 2.356c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.955-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.189-1.674a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.19 1.235l-.051.02l-.051.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.vrhnsgvqh {
  stop-color: var(--svg-color--cd9897, #CD9897);
  stop-opacity: 0;
}

.vunpjbdrs {
  stop-color: var(--svg-color--efc1b0, #EFC1B0);
  stop-opacity: 0;
}

.vzna2gbis {
  cx: 15.993px;
  cy: 2.859px;
  r: 0.85px;
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w78c_mbga {
  d: path("M10.813 25.801a3.502 3.502 0 1 1-7.004 0c0-1.934 1.568-3.389 3.502-3.389c3.781 0 3.502 1.455 3.502 3.389");
}

.wcds6xmsi {
  stop-color: var(--svg-color--d59b90, #D59B90);
}

.wmixudboe {
  stop-color: var(--svg-color--50d5fe, #50D5FE);
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.x5-3y6xrq {
  stop-color: var(--svg-color--2783b8, #2783B8);
}

.x6eb0fbok {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M20.875 15.646a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.x8dk6bl6o {
  stop-color: var(--svg-color--7045c9, #7045C9);
}

.xa-8pmq2w {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.048 17.484c-.52 0-1.01-.125-1.422-.345c-.14-.073-.291.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345Z");
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xf3nhjbpw {
  stop-color: var(--svg-color--fff6ff, #FFF6FF);
}

.xg0mdnbqj {
  stop-color: var(--svg-color--e2c0ab, #E2C0AB);
}

.xjhzw6b4m {
  stop-color: var(--svg-color--ce9fd2, #CE9FD2);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xpqto8b3q {
  stop-color: var(--svg-color--e8d9e7, #E8D9E7);
  stop-opacity: 0;
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y-c-j769e {
  stop-color: var(--svg-color--9869eb, #9869EB);
}

.y2qr1gb4g {
  stop-color: var(--svg-color--efc1b0, #EFC1B0);
}

.y5c3ymb4e {
  stop-color: var(--svg-color--b87d6d, #B87D6D);
  stop-opacity: 0;
}

.yb1xaiemt {
  stop-color: var(--svg-color--7a5298, #7A5298);
  stop-opacity: 0;
}

.yexd1o2nx {
  stop-color: var(--svg-color--e77953, #E77953);
}

.yi0nku-_h {
  fill: var(--svg-color--232121, #232121);
  d: path("M10.979 8.584c.566-.6 1.636-.6 2.13-.511l.396 1.29c-.252-.039-.478.05-.667.235c-.449 1.26-1.99 1.956-2.704 2.146c-.149-1.492.109-2.38.845-3.16");
}

.yidq71bjl {
  stop-color: var(--svg-color--c3a8aa, #C3A8AA);
  stop-opacity: 0;
}

.yind2xb3b {
  stop-color: var(--svg-color--7d48de, #7D48DE);
  stop-opacity: 0;
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.yq-enfbyo {
  stop-color: var(--svg-color--ce8988, #CE8988);
}

.z_f48dbjf {
  stop-color: var(--svg-color--735fab, #735FAB);
  stop-opacity: 0;
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
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

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z9cu3vbra {
  stop-color: var(--svg-color--fff7ff, #FFF7FF);
}

.zmea0ybye {
  stop-color: var(--svg-color--ae836d, #AE836D);
}

.zn9diyb1a {
  stop-color: var(--svg-color--8569c9, #8569C9);
}

.zpxfvu-uq {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.439 13.227c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.127 1.37-1.127");
}

.zxi6lwb9j {
  stop-color: var(--svg-color--f2bb64, #F2BB64);
}

</style>
