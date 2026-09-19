<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ibphygP)"><rect fill="url(#iIk56Pc)" transform="rotate(-45 12.963 13.403)" class="etm0labvf"/></g><g filter="url(#irAaUce)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/><g filter="url(#iiFlfgd)"><path fill="url(#i5I72Pc)" class="pb1pwib-r"/><path fill="url(#iX1BTZW)" class="pb1pwib-r"/></g><g filter="url(#iMmQgOg)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 6.585 29.734)" class="z_5s59bdn"/></g><g filter="url(#i2vVA2c)"><path class="g11vnob-s"/></g><g filter="url(#iZqY2vd)"><path class="yn_cprukr"/></g><g filter="url(#iYCtiVB)"><path class="w2mg53b0k"/></g><g filter="url(#iEeOpUc)"><path class="tn00ksbky"/></g><g filter="url(#iqHhyoe)"><rect class="r9m8_svvg"/><rect fill="url(#i3VDVVb)" class="nl4f7twra"/></g><g filter="url(#ijwzUve)"><path fill="url(#ioitlCc)" class="t16p7zajb"/></g><path fill="url(#i5Ao9Gd)" class="t16p7zajb"/><path fill="url(#i8KfH3d)" class="t16p7zajb"/><path fill="url(#iEdEbnd)" class="t16p7zajb"/><path class="n-gofxbqk"/><path fill="url(#iGgZmQl)" class="qqobt5tvr"/><path fill="url(#iVakvLc)" class="qqobt5tvr"/><path fill="url(#i3gy0Bb)" class="qqobt5tvr"/><path fill="url(#iuPT4Kc)" class="qqobt5tvr"/><path fill="url(#iHyYx2b)" class="qqobt5tvr"/><path class="e593k4bfv"/><path fill="url(#i7QnpSd)" class="xhtzkfsjn"/><path fill="url(#iJU4nte)" class="xhtzkfsjn"/><path fill="url(#ir07lqp)" class="fwk98bb0c"/><path fill="url(#is9Nicg)" class="fwk98bb0c"/><path fill="url(#iVXCTAc)" class="fwk98bb0c"/><path fill="url(#iZTxnje)" class="fwk98bb0c"/><path fill="url(#iR15onA)" class="wke8dtqov"/><path fill="url(#iDv7Hjb)" class="wke8dtqov"/><g filter="url(#iR8ja9c)"><path class="chi-gop6f"/><path fill="url(#iC59Lpc)" class="ajsjeuojy"/><path fill="url(#iznQ8ib)" class="ajsjeuojy"/></g><path fill="url(#iFc3g8a)" class="z45oacyxz"/><path fill="url(#ihvNS4d)" class="z45oacyxz"/><circle fill="url(#iLjKZQG)" class="z30kudb-o"/><g filter="url(#iY43ird)"><path class="f6xfjgb1y"/><path fill="url(#ihNl5mc)" class="k-27-x9ja"/></g><g filter="url(#iSjobOe)"><path class="s-zkbnh5r"/><path fill="url(#iXb4XGc)" class="dixb6cljt"/><path fill="url(#iQj6ttd)" class="dixb6cljt"/></g><g filter="url(#izFm8ob)"><path class="v0z-w2_2p"/></g><path fill="url(#iFc0eqy)" class="u5zvm6bcl"/><path fill="url(#iZeEFzX)" class="u5zvm6bcl"/><path fill="url(#i7zEfhH)" class="u5zvm6bcl"/><path fill="url(#iVRHTBe)" class="u5zvm6bcl"/><path fill="url(#iK804bd)" class="u5zvm6bcl"/><path fill="url(#iaW1cmd)" class="u5zvm6bcl"/><path fill="url(#iqcIBfc)" class="u5zvm6bcl"/><path fill="url(#iixF0Db)" class="gdfj27b8p"/><path fill="url(#ihyddKX)" class="gdfj27b8p"/><g filter="url(#iP2JAgd)"><path stroke="url(#iAyTcBl)" class="saunobcmg"/></g><g filter="url(#iF9nled)"><path stroke="url(#iVusaPe)" class="ikgkim2qs"/></g><g filter="url(#iQHCZ3b)"><path stroke="url(#iSuyLse)" class="zh46g387g"/></g><g filter="url(#iMcQOme)"><circle fill="url(#icmKkJc)" class="vay8lb24j"/></g><g filter="url(#ilpZVRc)"><circle fill="url(#iC5GCBd)" class="uz3bdgq_h"/></g><g filter="url(#ivUvOHw)"><circle fill="url(#ijX938c)" class="l-seuvb9h"/><circle fill="url(#iCxdtkd)" class="l-seuvb9h"/></g><g filter="url(#iTqJcfw)"><circle class="lddts_u7e"/><circle fill="url(#inLsMHe)" class="rb5txoune"/><circle fill="url(#iWVyhod)" class="rb5txoune"/></g><g filter="url(#i0rsj6d)"><path fill="url(#i1CMcBd)" class="ljdb3lbun"/><path fill="url(#iAe2mAe)" class="ljdb3lbun"/><path fill="url(#iAsYwDc)" class="ljdb3lbun"/></g><path fill="url(#iPMyrLd)" class="nksnhbxca"/><path fill="url(#iKtBXAc)" class="nksnhbxca"/><path fill="url(#ippoFnW)" class="nksnhbxca"/><g filter="url(#i5VOw0c)"><path fill="url(#iTeWnsc)" class="af8l42ixw"/></g><g filter="url(#iS1CSpc)"><path class="k6eh8sa8g"/><path fill="url(#ikn5CFb)" class="trg-8lb8c"/><path fill="url(#iiH16Be)" class="trg-8lb8c"/><path fill="url(#illSokc)" class="trg-8lb8c"/><path fill="url(#ig00VGe)" class="trg-8lb8c"/></g><g filter="url(#iMhRprb)"><path class="m2zv96lqd"/></g><g filter="url(#iNsTMec)"><path class="rlg1rjm1z"/><path fill="url(#iYvzWAc)" class="n3s1d6bxt"/><path fill="url(#iv0JmQe)" class="n3s1d6bxt"/><path fill="url(#igQSlGV)" class="n3s1d6bxt"/><path fill="url(#iRJDCNb)" class="n3s1d6bxt"/></g><g filter="url(#ic3lL2b)"><path stroke="url(#ivyQlyd)" class="j5zucu-dk"/></g><path class="gn7bkpbzs"/><g filter="url(#i2jxGbd)"><path class="peb5whbhc"/><path fill="url(#ipEq5cb)" class="hg90fgbwu"/></g><g filter="url(#iyCJxge)"><path class="r5hq7ubfs"/><path fill="url(#iee7Yfd)" class="rtu_2itkc"/></g><path class="g3v1hdccb"/><path fill="url(#iKB69xs)" class="mmk9fjb2s"/><path class="faxw7_bwn"/><g filter="url(#i6siWRE)"><path class="ohlh5_bva"/><path fill="url(#iMPZCzd)" class="zpi-n7hqe"/></g><g filter="url(#i2ukljc)"><path fill="url(#ip0bsYc)" class="leh6e5bwb"/></g><path class="nbr_qbcht"/><path fill="url(#i40LDAe)" class="ismbxv5ei"/><path class="rxhnfs2-v"/><g filter="url(#iO0wcjd)"><path fill="url(#iyHpprb)" class="g12da0auc"/></g><g filter="url(#iawaMne)"><ellipse transform="rotate(-27.914 14.986 7.594)" class="fld9nuwsm"/><ellipse fill="url(#ijLaZxc)" transform="rotate(-27.914 14.986 7.594)" class="fzbry4bml"/></g><g filter="url(#i0Mlymb)"><path stroke="url(#i6GODCc)" class="kiabxac4n"/></g><g filter="url(#i7lrj4M)"><path stroke="url(#ie7el0c)" class="na4a0krid"/></g><g filter="url(#iDE8kvd)"><path stroke="url(#i8YAIne)" class="uuisxbb1y"/></g><defs><radialGradient id="iIk56Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 21.301)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="ioitlCc" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.379 5.864)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="i5Ao9Gd" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.216 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="i8KfH3d" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.915 17.107)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iEdEbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 3.528)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iVakvLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.68754 -5.0625 2.53124 -.34377 16.78 21.98)" gradientUnits="userSpaceOnUse"><stop class="uvyxh01-z"/><stop offset="1" class="u2p7zvbzn"/></radialGradient><radialGradient id="i3gy0Bb" cx="0" cy="0" r="1" gradientTransform="rotate(-100.125 15.9 2.484)scale(.88884 .66004)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="kcor2lvvo"/><stop offset="1" class="t0dfidbsh"/></radialGradient><radialGradient id="iHyYx2b" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 -4.56052 .72812 .03493 14.75 21.79)" gradientUnits="userSpaceOnUse"><stop class="ywk-_ln5y"/><stop offset="1" class="quxai4aum"/></radialGradient><radialGradient id="iVXCTAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.26562 3.09375 -.85026 -.073 15.348 26.277)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="j7smtkbjw"/><stop offset="1" class="xgtw6wrae"/></radialGradient><radialGradient id="iDv7Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 29.465)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="iznQ8ib" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.80469 -.96535 .25074 19.32 20.568)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="fgis5qzvv"/><stop offset="1" class="blsn939-n"/></radialGradient><radialGradient id="ihvNS4d" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 27.216)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="iLjKZQG" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .1914 -.31978 .73092 6.135 15.73)" gradientUnits="userSpaceOnUse"><stop class="qya8vwbkf"/><stop offset="1" class="d0qi1-blu"/></radialGradient><radialGradient id="ihNl5mc" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 27.876 -1.302)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="tj824objr"/><stop offset="1" class="lz6zpisqv"/></radialGradient><radialGradient id="iXb4XGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16876 .9375 -.156 -.19448 8.314 14.542)" gradientUnits="userSpaceOnUse"><stop class="gbuovhboa"/><stop offset="1" class="yq1j9wb8r"/></radialGradient><radialGradient id="iQj6ttd" cx="0" cy="0" r="1" gradientTransform="matrix(.8047 -.67969 .45175 .53484 7.442 15.269)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="scofoabvh"/><stop offset="1" class="b4zzki-mx"/></radialGradient><radialGradient id="i7zEfhH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92712 .2574 -.06658 -.49847 15.194 10.709)" gradientUnits="userSpaceOnUse"><stop class="ptfvfcbrt"/><stop offset="1" class="c9v8_hpvm"/></radialGradient><radialGradient id="iVRHTBe" cx="0" cy="0" r="1" gradientTransform="rotate(142.326 7.147 8.847)scale(1.55953 .89404)" gradientUnits="userSpaceOnUse"><stop class="y39x50mqx"/><stop offset="1" class="gmn2w47zp"/></radialGradient><radialGradient id="iK804bd" cx="0" cy="0" r="1" gradientTransform="matrix(1.67188 0 0 .4274 16.843 10.709)" gradientUnits="userSpaceOnUse"><stop class="nkm4r8_8f"/><stop offset="1" class="e2kf81bwk"/></radialGradient><radialGradient id="iixF0Db" cx="0" cy="0" r="1" gradientTransform="matrix(.13999 .90814 -2.78555 .42938 15.555 10.62)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="qggerob2g"/><stop offset="1" class="pn9klvbrs"/></radialGradient><radialGradient id="ihyddKX" cx="0" cy="0" r="1" gradientTransform="rotate(160.1 7.47 6.92)scale(.87221 .42588)" gradientUnits="userSpaceOnUse"><stop class="wfj08-bsk"/><stop offset="1" class="k9wpgpx3v"/></radialGradient><radialGradient id="icmKkJc" cx="0" cy="0" r="1" gradientTransform="matrix(.76116 0 0 1.33204 13.267 7.931)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iCxdtkd" cx="0" cy="0" r="1" gradientTransform="matrix(.35858 -.2611 .29801 .40927 18.279 7.816)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="inLsMHe" cx="0" cy="0" r="1" gradientTransform="matrix(.35622 -.65518 .38348 .2085 18.1 8.287)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iWVyhod" cx="0" cy="0" r="1" gradientTransform="matrix(.11247 .11132 -.1435 .14499 18.117 7.93)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iAe2mAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56694 .69777 0 17.068 7.38)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iAsYwDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59601 .7412 0 15.091 7.438)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="ippoFnW" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.63065 -4.92841 0 15.92 7.162)" gradientUnits="userSpaceOnUse"><stop offset=".669" class="rko8b-bmk"/><stop offset="1" class="umwk0nbod"/></radialGradient><radialGradient id="ikn5CFb" cx="0" cy="0" r="1" gradientTransform="matrix(.34605 -1.28242 .61748 .16662 17.935 6.15)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="iiH16Be" cx="0" cy="0" r="1" gradientTransform="matrix(1.659 .15267 -.08209 .89203 17.222 5.387)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="illSokc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .72833 -1.12798 0 16.05 4.2)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="ig00VGe" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 17.565 -16.674)scale(1.653 2.5897)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iRJDCNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .0854 -.27438 0 16.193 8.628)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="ipEq5cb" cx="0" cy="0" r="1" gradientTransform="matrix(.0452 -.26166 .77411 .1337 17.11 7.027)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iee7Yfd" cx="0" cy="0" r="1" gradientTransform="matrix(.0452 -.26166 .77415 .13372 14.877 7.027)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iKB69xs" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35182 -.55961 0 16.996 7.635)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iMPZCzd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.813 10.327 -.302)scale(.16404 .22585)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i40LDAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35184 -.55964 0 15.103 7.635)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ijLaZxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00335 -.21426 .25755 -.00403 14.979 7.73)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="ibphygP" width="7.335" height="7.37" x="13.891" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1149" result="effect2_innerShadow_4002_1149"/></filter><filter id="irAaUce" width="10.517" height="10.517" x="14.14" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1149" result="effect2_innerShadow_4002_1149"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1149" result="effect3_innerShadow_4002_1149"/></filter><filter id="iiFlfgd" width="9.391" height="10.922" x="7.466" y="4.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1149" result="effect2_innerShadow_4002_1149"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1149" result="effect3_innerShadow_4002_1149"/></filter><filter id="iMmQgOg" width="7.298" height="7.298" x="10.845" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/></filter><filter id="i2vVA2c" width="3.908" height="3.642" x="9.545" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1149"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1149" result="effect2_dropShadow_4002_1149"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1149" result="shape"/></filter><filter id="iZqY2vd" width="6.45" height="6.548" x="9.619" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1149"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1149" result="effect2_dropShadow_4002_1149"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1149" result="shape"/></filter><filter id="iYCtiVB" width="3.908" height="3.642" x="18.631" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1149"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1149" result="effect2_dropShadow_4002_1149"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1149" result="shape"/></filter><filter id="iEeOpUc" width="6.45" height="6.548" x="16.014" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1149"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1149" result="effect2_dropShadow_4002_1149"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1149" result="shape"/></filter><filter id="iqHhyoe" width="1.003" height="4.833" x="22.341" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/></filter><filter id="ijwzUve" width="4.084" height="3.799" x="20.732" y="2.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/></filter><filter id="iR8ja9c" width="5.091" height="7.247" x="15.749" y="20.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/></filter><filter id="iY43ird" width="7.578" height="5.434" x="6.015" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.270588 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.286275 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1149" result="effect2_innerShadow_4002_1149"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.435294 0 0 0 0 0.309804 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1149" result="effect3_innerShadow_4002_1149"/></filter><filter id="iSjobOe" width="1.692" height="1.561" x="6.723" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.266667 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/></filter><filter id="izFm8ob" width="5.398" height="7.21" x="18.218" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.235294 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/></filter><filter id="iP2JAgd" width="4.609" height="5.161" x="19.13" y="9.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".25"/></filter><filter id="iF9nled" width="1.248" height="2.077" x="21.759" y="8.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".1"/></filter><filter id="iQHCZ3b" width=".822" height="1.445" x="22.798" y="8.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".1"/></filter><filter id="iMcQOme" width="1.648" height="1.448" x="13.267" y="7.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/></filter><filter id="ilpZVRc" width="1.863" height="1.863" x="13.06" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".25"/></filter><filter id="ivUvOHw" width="1.698" height="1.698" x="17.393" y="6.957" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/></filter><filter id="iTqJcfw" width="1.863" height="1.863" x="17.186" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".25"/></filter><filter id="i0rsj6d" width="4.5" height="5.267" x="13.813" y="5.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/></filter><filter id="i5VOw0c" width="3.342" height="2.83" x="15.374" y="4.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".375"/></filter><filter id="iS1CSpc" width="5.466" height="3.589" x="13.317" y="4.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/></filter><filter id="iMhRprb" width="2.263" height="2.663" x="14.815" y="7.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".375"/></filter><filter id="iNsTMec" width=".914" height="1.263" x="15.594" y="7.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".025"/></filter><filter id="ic3lL2b" width="1.596" height=".665" x="15.253" y="9.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".025"/></filter><filter id="i2jxGbd" width="1.434" height="1.039" x="16.563" y="6.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/></filter><filter id="iyCJxge" width="1.434" height="1.039" x="14.331" y="6.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1149"/></filter><filter id="i6siWRE" width=".454" height=".415" x="16.621" y="7.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".05"/></filter><filter id="i2ukljc" width=".613" height=".623" x="16.928" y="7.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".1"/></filter><filter id="iO0wcjd" width=".654" height=".678" x="15.002" y="7.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".1"/></filter><filter id="iawaMne" width=".509" height=".419" x="14.731" y="7.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".05"/></filter><filter id="i0Mlymb" width="1.252" height=".637" x="16.546" y="6.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".075"/></filter><filter id="i7lrj4M" width="1.286" height=".662" x="14.282" y="6.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".075"/></filter><filter id="iDE8kvd" width=".862" height="1.409" x="13.598" y="5.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1149" stdDeviation=".125"/></filter><linearGradient id="i5I72Pc" x1="8.528" x2="12.668" y1="5.843" y2="9.982" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="iX1BTZW" x1="11.132" x2="10.694" y1="12.966" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="i3VDVVb" x1="22.919" x2="22.549" y1="5.345" y2="6.133" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="iGgZmQl" x1="13.264" x2="15.031" y1="19.026" y2="19.026" gradientUnits="userSpaceOnUse"><stop class="i7ccoc8qs"/><stop offset="1" class="waah2bcle"/></linearGradient><linearGradient id="iuPT4Kc" x1="19.343" x2="17.937" y1="18.573" y2="19.026" gradientUnits="userSpaceOnUse"><stop class="hnwux9dcc"/><stop offset="1" class="xsno6rw2t"/></linearGradient><linearGradient id="i7QnpSd" x1="18.792" x2="16.991" y1="16.247" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="iJU4nte" x1="13.267" x2="15.007" y1="16.431" y2="16.431" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="ir07lqp" x1="15.288" x2="13.817" y1="25.263" y2="25.263" gradientUnits="userSpaceOnUse"><stop offset=".267" class="jnedts9qu"/><stop offset=".945" class="jjvamgr7p"/></linearGradient><linearGradient id="is9Nicg" x1="15.46" x2="14.96" y1="26.669" y2="26.638" gradientUnits="userSpaceOnUse"><stop class="uj9y6sbjo"/><stop offset="1" class="pnh1u2g5u"/></linearGradient><linearGradient id="iZTxnje" x1="13.261" x2="13.692" y1="25.667" y2="25.667" gradientUnits="userSpaceOnUse"><stop class="o5s4dcbqc"/><stop offset="1" class="migaloo2k"/></linearGradient><linearGradient id="iR15onA" x1="15.197" x2="13.71" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="htqsm-l2e"/><stop offset=".159" class="zd1r_u8ze"/><stop offset=".453" class="x09-01b7i"/><stop offset="1" class="s_f01nb2h"/></linearGradient><linearGradient id="iC59Lpc" x1="18.825" x2="18.351" y1="24.378" y2="24.091" gradientUnits="userSpaceOnUse"><stop class="s5lr0-bjd"/><stop offset="1" class="p4dvxyhsv"/></linearGradient><linearGradient id="iFc3g8a" x1="15.749" x2="17.116" y1="25.981" y2="27.044" gradientUnits="userSpaceOnUse"><stop class="ilfb1o36w"/><stop offset="1" class="q6qjg9bpc"/></linearGradient><linearGradient id="iFc0eqy" x1="16.03" x2="16.03" y1="10.709" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="rlgwf126s"/><stop offset="1" class="l-4shobes"/></linearGradient><linearGradient id="iZeEFzX" x1="13.267" x2="15.457" y1="14.741" y2="14.741" gradientUnits="userSpaceOnUse"><stop offset=".01" class="jv6lqw6zm"/><stop offset="1" class="r3o1jnbex"/></linearGradient><linearGradient id="iaW1cmd" x1="18.593" x2="16.593" y1="15.23" y2="15.23" gradientUnits="userSpaceOnUse"><stop class="xxjj5obiq"/><stop offset="1" class="teavi7b3d"/></linearGradient><linearGradient id="iqcIBfc" x1="18.906" x2="18.453" y1="15.544" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="ma_coc6av"/><stop offset="1" class="g9j7gtogb"/></linearGradient><linearGradient id="iAyTcBl" x1="22.63" x2="20.036" y1="11.605" y2="13.448" gradientUnits="userSpaceOnUse"><stop offset=".453" class="a3_z2xhkr"/><stop offset="1" class="k5r_gj7_l"/></linearGradient><linearGradient id="iVusaPe" x1="22.059" x2="21.755" y1="8.558" y2="10.249" gradientUnits="userSpaceOnUse"><stop class="ml_vtmq0l"/><stop offset="1" class="k3wixebqv"/></linearGradient><linearGradient id="iSuyLse" x1="23.372" x2="22.865" y1="9.113" y2="9.957" gradientUnits="userSpaceOnUse"><stop class="c16cce_hn"/><stop offset="1" class="zozno708c"/></linearGradient><linearGradient id="iC5GCBd" x1="13.991" x2="13.713" y1="8.052" y2="8.052" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="ijX938c" x1="18.589" x2="18.234" y1="7.458" y2="8.558" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="i1CMcBd" x1="17.801" x2="14.489" y1="8.1" y2="8.594" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iPMyrLd" x1="13.71" x2="14.526" y1="9.269" y2="9.24" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iKtBXAc" x1="18.16" x2="17.703" y1="8.906" y2="8.862" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iTeWnsc" x1="15.82" x2="19.353" y1="6.805" y2="5.541" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iYvzWAc" x1="15.676" x2="16.083" y1="8.386" y2="8.386" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iv0JmQe" x1="16.458" x2="16.013" y1="8.526" y2="8.52" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="igQSlGV" x1="16.135" x2="16.135" y1="8.848" y2="8.599" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="ivyQlyd" x1="15.601" x2="15.79" y1="9.548" y2="9.25" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="ip0bsYc" x1="17.333" x2="17.197" y1="7.659" y2="7.742" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyHpprb" x1="15.426" x2="15.29" y1="7.659" y2="7.743" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6GODCc" x1="17.34" x2="17.158" y1="6.731" y2="6.358" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="ie7el0c" x1="15.039" x2="14.523" y1="6.675" y2="6.459" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="i8YAIne" x1="14.028" x2="14.028" y1="5.801" y2="6.737" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-fairy-medium-dark" /></template>
<style>
.a3_z2xhkr {
  stop-color: var(--svg-color--a17e73, #A17E73);
}

.af8l42ixw {
  d: path("m17.77 5.492l-1.335.445a.454.454 0 0 0 .204.88l1.327-.177z");
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ajsjeuojy {
  d: path("m17.672 21.275l-.082-.227l2.33-.48c.022.062.095.292.22.71c.125.42-.01.774-.094.899l-3.27 5.344c-.07.116-.232.128-.31.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.b4zzki-mx {
  stop-color: var(--svg-color--7d534e, #7D534E);
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.blsn939-n {
  stop-color: var(--svg-color--a37b73, #A37B73);
  stop-opacity: 0;
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c16cce_hn {
  stop-color: var(--svg-color--9d7d72, #9D7D72);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9v8_hpvm {
  stop-color: var(--svg-color--3f76a9, #3F76A9);
  stop-opacity: 0;
}

.chi-gop6f {
  fill: var(--svg-color--8f6263, #8F6263);
  d: path("m17.672 21.275l-.082-.227l2.33-.48c.022.062.095.292.22.71c.125.42-.01.774-.094.899l-3.27 5.344c-.07.116-.232.128-.31.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d0qi1-blu {
  stop-color: var(--svg-color--703d57, #703D57);
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dixb6cljt {
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.638-.217.724-.129c.1.103.144.418-.094.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.013-.561.257-.764");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2kf81bwk {
  stop-color: var(--svg-color--4794c5, #4794C5);
  stop-opacity: 0;
}

.e593k4bfv {
  fill: var(--svg-color--aed62f, #AED62F);
  d: path("M13.267 16.349v-.82h5.525v.82c-2.337.148-4.276.062-5.525 0");
}

.edfwaihfg {
  stop-color: var(--svg-color--bff332, #BFF332);
  stop-opacity: 0;
}

.etm0labvf {
  width: 4.843px;
  height: 8.191px;
  x: 12.963px;
  y: 13.403px;
  rx: 2.422px;
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f6xfjgb1y {
  fill: var(--svg-color--7d534e, #7D534E);
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.faxw7_bwn {
  fill: var(--svg-color--000, #000);
  d: path("M16.775 7.816a.22.22 0 0 1 .222-.222a.22.22 0 0 1 .197.324H16.8a.2.2 0 0 1-.026-.102");
}

.ffese-y7m {
  width: 6.894px;
  height: 11.735px;
  rx: 3.447px;
}

.fgis5qzvv {
  stop-color: var(--svg-color--a37b73, #A37B73);
}

.fld9nuwsm {
  cx: 14.986px;
  cy: 7.594px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.086px;
}

.ft5dv1b6b {
  fill: none;
}

.fwk98bb0c {
  d: path("m13.318 29.589l-.057-7.861l2.32.062l-.439 7.053a.47.47 0 0 1-.215.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.fzbry4bml {
  cx: 14.986px;
  cy: 7.594px;
  rx: 0.169px;
  ry: 0.086px;
}

.g11vnob-s {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 9.264a.21.21 0 1 0-.284.31l1.82 1.667l-.84.086a.21.21 0 1 0 .043.418l1.21-.124l.955.875a.21.21 0 1 0 .284-.31z");
}

.g12da0auc {
  d: path("M15.456 7.77c0-.125-.102-.208-.13-.234l-.124.121l.077.157z");
}

.g3v1hdccb {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.086 7.31c.284 0 .523.196.588.46a.12.12 0 0 1-.116.147h-.968a.1.1 0 0 1-.098-.117a.606.606 0 0 1 .594-.49");
}

.g9j7gtogb {
  stop-color: var(--svg-color--4db5ff, #4DB5FF);
  stop-opacity: 0;
}

.gbuovhboa {
  stop-color: var(--svg-color--95726c, #95726C);
}

.gdfj27b8p {
  d: path("M15.07 10.486v.349a.24.24 0 0 0 .065.157c.134.147.326.443.456.87c.06.195.232.342.437.342a.47.47 0 0 0 .437-.342c.13-.427.322-.723.456-.87a.24.24 0 0 0 .066-.157v-.35z");
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gmn2w47zp {
  stop-color: var(--svg-color--56c3ff, #56C3FF);
  stop-opacity: 0;
}

.gn7bkpbzs {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M16.05 9.289c-.22 0-.426-.052-.6-.143c-.06-.03-.123.037-.086.09a.82.82 0 0 0 .687.368a.82.82 0 0 0 .686-.367c.038-.056-.026-.121-.085-.09a1.3 1.3 0 0 1-.601.142");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.hg90fgbwu {
  d: path("M17.664 6.751h-.001l-.002-.002l-.006-.004l-.067-.047a1.23 1.23 0 0 0-.83-.16a.232.232 0 0 0 .073.457a.77.77 0 0 1 .512.095l.027.019a.231.231 0 0 0 .294-.358");
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hnwux9dcc {
  stop-color: var(--svg-color--57a7fb, #57A7FB);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.htqsm-l2e {
  stop-color: var(--svg-color--664e86, #664E86);
}

.i7ccoc8qs {
  stop-color: var(--svg-color--3968ab, #3968AB);
}

.ikgkim2qs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M22.06 8.558v.505a1 1 0 0 0 .433.824l.215.147");
}

.ilfb1o36w {
  stop-color: var(--svg-color--352b41, #352B41);
}

.ismbxv5ei {
  d: path("M15.103 7.428a.387.387 0 0 0-.373.49h.747a.39.39 0 0 0-.375-.49");
}

.j5zucu-dk {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.05 9.289c-.22 0-.426-.052-.6-.143c-.06-.03-.123.037-.086.09a.82.82 0 0 0 .687.368a.82.82 0 0 0 .686-.367c.038-.056-.026-.121-.085-.09a1.3 1.3 0 0 1-.601.142Z");
}

.j7smtkbjw {
  stop-color: var(--svg-color--6d494d, #6D494D);
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jnedts9qu {
  stop-color: var(--svg-color--976e6a, #976E6A);
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jv6lqw6zm {
  stop-color: var(--svg-color--4f6fa1, #4F6FA1);
}

.k-27-x9ja {
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.k356i5yuc {
  stop-color: var(--svg-color--91deff, #91DEFF);
}

.k3wixebqv {
  stop-color: var(--svg-color--846763, #846763);
  stop-opacity: 0;
}

.k5r_gj7_l {
  stop-color: var(--svg-color--a17e73, #A17E73);
  stop-opacity: 0;
}

.k6eh8sa8g {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m18.14 5.121l.186.093a.85.85 0 0 1 .442.925l-.256 1.319c-.023.136-.113.228-.248.231h-.008s.024-.393.047-.624c.019-.188-.014-.245-.186-.417a.54.54 0 0 1-.163-.37v-.37a.25.25 0 0 0-.186-.231c-.28-.07-.861-.185-1.698-.185c-.838 0-1.42.115-1.699.185a.226.226 0 0 0-.186.231v.37a.46.46 0 0 1-.163.37l-.07.07c-.093.07-.14.208-.14.324c.024.254.047.624.047.624h-.021a.275.275 0 0 1-.258-.231l-.256-1.319a.89.89 0 0 1 .465-.902l.187-.093c.116-.069.232-.161.348-.254l.42-.44a.85.85 0 0 1 .953-.138c.233.07.489.07.721 0a1.05 1.05 0 0 1 1.024.231l.35.347a.95.95 0 0 0 .348.254");
}

.k9wpgpx3v {
  stop-color: var(--svg-color--855c58, #855C58);
  stop-opacity: 0;
}

.kcor2lvvo {
  stop-color: var(--svg-color--3f63e1, #3F63E1);
}

.kiabxac4n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16.77 6.689c.187-.033.551-.024.803.172");
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l-4shobes {
  stop-color: var(--svg-color--358dea, #358DEA);
}

.l-seuvb9h {
  cx: 18.118px;
  cy: 7.931px;
  r: 0.724px;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lddts_u7e {
  cx: 18.118px;
  cy: 7.931px;
  r: 0.432px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.leh6e5bwb {
  d: path("M17.341 7.764a.36.36 0 0 0-.1-.2l-.113.124l.051.098z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljdb3lbun {
  d: path("m13.839 7.665l.02.001s-.022-.37-.046-.624c0-.116.047-.255.14-.324l.07-.07a.46.46 0 0 0 .163-.37v-.37c0-.116.07-.208.186-.231c.279-.07.86-.185 1.698-.185s1.42.115 1.698.185a.25.25 0 0 1 .187.231v.37c0 .139.07.278.163.37c.217.153.204.237.186.417c-.024.231-.047.624-.047.624h.008l-.115 1.717c-.07.768-.673 1.303-1.393 1.303h-1.392c-.743 0-1.323-.535-1.393-1.303z");
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lz6zpisqv {
  stop-color: var(--svg-color--6b4440, #6B4440);
}

.m2zv96lqd {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.931 7.878l-.356.737c-.044.152.062.304.212.304h.32c.15 0 .256-.154.212-.304l-.216-.737c-.047-.163-.123-.163-.172 0");
}

.ma_coc6av {
  stop-color: var(--svg-color--51a3e8, #51A3E8);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.migaloo2k {
  stop-color: var(--svg-color--89625c, #89625C);
  stop-opacity: 0;
}

.ml_vtmq0l {
  stop-color: var(--svg-color--846763, #846763);
}

.mmk9fjb2s {
  d: path("M16.997 7.428a.387.387 0 0 1 .372.49h-.747a.388.388 0 0 1 .375-.489");
}

.n-gofxbqk {
  fill: var(--svg-color--3c8aea, #3C8AEA);
  d: path("M13.264 21.733V16.26l5.528.057c0 .347.063.665.09.764l1.042 3.486l-2.33.484l-.864-2.223c-.133-.336-.286-.64-.505-.64c-.25 0-.356.391-.361.59l-.279 3.011z");
}

.n3s1d6bxt {
  d: path("m15.885 7.807l-.23.738a.234.234 0 0 0 .225.303h.341c.16 0 .273-.154.226-.303l-.23-.738c-.05-.163-.28-.163-.332 0");
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.na4a0krid {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.507 6.914c.142-.126.452-.258.836-.197");
}

.nbr_qbcht {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.013 7.31a.606.606 0 0 0-.588.46a.12.12 0 0 0 .116.147h.968a.1.1 0 0 0 .098-.117a.61.61 0 0 0-.594-.49");
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nkm4r8_8f {
  stop-color: var(--svg-color--4780ac, #4780AC);
}

.nksnhbxca {
  d: path("M13.813 7.042c0-.116.047-.255.14-.324l.07-.07a.46.46 0 0 0 .163-.37v-.37c0-.116.07-.208.186-.231c.279-.07.86-.185 1.698-.185s1.42.115 1.698.185a.25.25 0 0 1 .187.231v.37c0 .139.07.278.163.37c.217.153.204.237.186.417c-.024.231-.047.624-.047.624h.008l-.115 1.717c-.07.768-.673 1.303-1.393 1.303h-1.392c-.743 0-1.323-.535-1.393-1.303c-.06-.788-.087-1.578-.159-2.364");
}

.nl4f7twra {
  width: 0.703px;
  height: 4.633px;
  x: 22.341px;
  y: 4.997px;
  rx: 0.352px;
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o5s4dcbqc {
  stop-color: var(--svg-color--89625c, #89625C);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohlh5_bva {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.968 7.51c.028.037-.03.082-.095.131c-.066.05-.114.084-.142.047s.003-.107.069-.156c.065-.049.14-.059.168-.022");
}

.p4dvxyhsv {
  stop-color: var(--svg-color--91676d, #91676D);
  stop-opacity: 0;
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.pb1pwib-r {
  d: path("M8.523 10.723a3.454 3.454 0 0 1 .005-4.88a3.454 3.454 0 0 1 4.881-.006l1.19 1.19c.337.337.601.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.249v.56a2.443 2.443 0 0 1-4.17 1.727z");
}

.peb5whbhc {
  fill: var(--svg-color--352827, #352827);
  d: path("M17.664 6.751h-.001l-.002-.002l-.006-.004l-.067-.047a1.23 1.23 0 0 0-.83-.16a.232.232 0 0 0 .073.457a.77.77 0 0 1 .512.095l.027.019a.231.231 0 0 0 .294-.358");
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn9klvbrs {
  stop-color: var(--svg-color--885d55, #885D55);
}

.pnh1u2g5u {
  stop-color: var(--svg-color--896057, #896057);
  stop-opacity: 0;
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.ptfvfcbrt {
  stop-color: var(--svg-color--435e8c, #435E8C);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q6qjg9bpc {
  stop-color: var(--svg-color--64468a, #64468A);
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qggerob2g {
  stop-color: var(--svg-color--6e3f3c, #6E3F3C);
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
  stop-opacity: 0;
}

.qqobt5tvr {
  d: path("M13.264 21.733V16.26l5.528.057c0 .347.063.665.09.764l1.042 3.486l-2.33.484l-.864-2.223c-.133-.336-.286-.64-.505-.64c-.25 0-.356.391-.361.59l-.279 3.011z");
}

.quxai4aum {
  stop-color: var(--svg-color--4b90ea, #4B90EA);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qya8vwbkf {
  stop-color: var(--svg-color--86605c, #86605C);
}

.r3o1jnbex {
  stop-color: var(--svg-color--3391ee, #3391EE);
  stop-opacity: 0;
}

.r5hq7ubfs {
  fill: var(--svg-color--352827, #352827);
  d: path("M14.414 6.752V6.75h.002l.001-.002l.006-.004l.067-.047a1.23 1.23 0 0 1 .83-.16a.232.232 0 0 1-.073.457a.77.77 0 0 0-.511.095l-.024.016l-.004.003a.232.232 0 0 1-.294-.357");
}

.r9m8_svvg {
  width: 0.703px;
  height: 4.633px;
  x: 22.341px;
  y: 4.997px;
  fill: var(--svg-color--9a6159, #9A6159);
  rx: 0.352px;
}

.rb5txoune {
  cx: 18.118px;
  cy: 7.931px;
  r: 0.432px;
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.redus_bqs {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
  stop-opacity: 0;
}

.rivz2obdn {
  stop-color: var(--svg-color--91e5ff, #91E5FF);
}

.rko8b-bmk {
  stop-color: var(--svg-color--714250, #714250);
  stop-opacity: 0;
}

.rlg1rjm1z {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.885 7.807l-.23.738a.234.234 0 0 0 .225.303h.341c.16 0 .273-.154.226-.303l-.23-.738c-.05-.163-.28-.163-.332 0");
}

.rlgwf126s {
  stop-color: var(--svg-color--43abff, #43ABFF);
}

.rtu_2itkc {
  d: path("M14.414 6.752V6.75h.002l.001-.002l.006-.004l.067-.047a1.23 1.23 0 0 1 .83-.16a.232.232 0 0 1-.073.457a.77.77 0 0 0-.511.095l-.024.016l-.004.003a.232.232 0 0 1-.294-.357");
}

.rxhnfs2-v {
  fill: var(--svg-color--000, #000);
  d: path("M15.324 7.815a.22.22 0 0 0-.222-.221a.22.22 0 0 0-.197.323h.393a.2.2 0 0 0 .026-.102");
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s_f01nb2h {
  stop-color: var(--svg-color--4b3866, #4B3866);
}

.s-zkbnh5r {
  fill: var(--svg-color--7e5a4e, #7E5A4E);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.638-.217.724-.129c.1.103.144.418-.094.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.013-.561.257-.764");
}

.s2ceddo5o {
  stop-color: var(--svg-color--80caf3, #80CAF3);
}

.s3hklabia {
  stop-color: var(--svg-color--593569, #593569);
}

.s5lr0-bjd {
  stop-color: var(--svg-color--91676d, #91676D);
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.saunobcmg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m19.88 12.667l2.672 1.045a.1.1 0 0 0 .136-.085l.301-3.57");
}

.scofoabvh {
  stop-color: var(--svg-color--7d534e, #7D534E);
  stop-opacity: 0;
}

.t0dfidbsh {
  stop-color: var(--svg-color--3f63e1, #3F63E1);
  stop-opacity: 0;
}

.t16p7zajb {
  d: path("M22.5 2.293a.22.22 0 0 1 .4.001l.414.896a.22.22 0 0 0 .174.126l.983.115a.22.22 0 0 1 .128.376l-.734.716a.22.22 0 0 0-.062.2l.185.926a.22.22 0 0 1-.32.237l-.863-.459a.22.22 0 0 0-.207 0l-.87.462a.22.22 0 0 1-.319-.235l.177-.932a.22.22 0 0 0-.062-.198l-.726-.718a.22.22 0 0 1 .129-.375l.98-.115a.22.22 0 0 0 .174-.125z");
}

.teavi7b3d {
  stop-color: var(--svg-color--3b9bf4, #3B9BF4);
  stop-opacity: 0;
}

.tj824objr {
  stop-color: var(--svg-color--6b4440, #6B4440);
  stop-opacity: 0;
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tn00ksbky {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 6.325a.21.21 0 0 1 .418.048l-.159 1.385l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 0 1-.282-.312l4.235-3.836z");
}

.trg-8lb8c {
  d: path("m18.14 5.121l.186.093a.85.85 0 0 1 .442.925l-.256 1.319c-.023.136-.113.228-.248.231h-.008s.024-.393.047-.624c.019-.188-.014-.245-.186-.417a.54.54 0 0 1-.163-.37v-.37a.25.25 0 0 0-.186-.231c-.28-.07-.861-.185-1.698-.185c-.838 0-1.42.115-1.699.185a.226.226 0 0 0-.186.231v.37a.46.46 0 0 1-.163.37l-.07.07c-.093.07-.14.208-.14.324c.024.254.047.624.047.624h-.021a.275.275 0 0 1-.258-.231l-.256-1.319a.89.89 0 0 1 .465-.902l.187-.093c.116-.069.232-.161.348-.254l.42-.44a.85.85 0 0 1 .953-.138c.233.07.489.07.721 0a1.05 1.05 0 0 1 1.024.231l.35.347a.95.95 0 0 0 .348.254");
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tx327ubjh {
  stop-color: var(--svg-color--8eefff, #8EEFFF);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u2p7zvbzn {
  stop-color: var(--svg-color--2851b6, #2851B6);
  stop-opacity: 0;
}

.u5zvm6bcl {
  d: path("M16.017 10.71a24 24 0 0 0-1.985.162c-.722.102-.765.711-.765.992v3.68h5.525v-3.68c0-.28-.043-.89-.764-.992a24 24 0 0 0-1.985-.163h-.027");
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.uj9y6sbjo {
  stop-color: var(--svg-color--896057, #896057);
}

.umwk0nbod {
  stop-color: var(--svg-color--6e4365, #6E4365);
}

.uodqeubaz {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
}

.uowu7rarb {
  stop-color: var(--svg-color--603b8b, #603B8B);
  stop-opacity: 0;
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.uuisxbb1y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M14.085 5.844v.39c-.004.064-.031.208-.113.27");
}

.uvyxh01-z {
  stop-color: var(--svg-color--2851b6, #2851B6);
}

.uz3bdgq_h {
  cx: 13.991px;
  cy: 7.931px;
  r: 0.432px;
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
}

.v0z-w2_2p {
  fill: var(--svg-color--855954, #855954);
  d: path("m21.499 12.27l-3.145-1.206l-.136 2.175l3.578 1.368c.185.083.651.2 1.039 0s.515-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0v-.744a.404.404 0 0 0-.805-.036c-.013.162-.03.366-.047.6c-.038.494.276.836.437.961z");
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vay8lb24j {
  cx: 13.991px;
  cy: 7.931px;
  r: 0.724px;
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vvvf-bx0b {
  stop-color: var(--svg-color--93efff, #93EFFF);
}

.vw5e4lbve {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
}

.vxhtc9kgk {
  stop-color: var(--svg-color--8bd2ff, #8BD2FF);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w2mg53b0k {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 9.264a.21.21 0 1 1 .284.31L20.5 11.24l.84.086a.21.21 0 0 1-.043.418l-1.21-.124l-.955.875a.21.21 0 1 1-.284-.31z");
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.waah2bcle {
  stop-color: var(--svg-color--3968ab, #3968AB);
  stop-opacity: 0;
}

.wfj08-bsk {
  stop-color: var(--svg-color--855c58, #855C58);
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wke8dtqov {
  d: path("m13.312 28.098l.006 1.49c0 .169.164.288.322.231a7 7 0 0 0 1.287-.603a.47.47 0 0 0 .216-.373l.054-.894z");
}

.x09-01b7i {
  stop-color: var(--svg-color--634689, #634689);
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
}

.xgtw6wrae {
  stop-color: var(--svg-color--8d615b, #8D615B);
  stop-opacity: 0;
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xhtzkfsjn {
  d: path("M13.267 16.349v-.82h5.525v.82c-2.337.148-4.276.062-5.525 0");
}

.xsno6rw2t {
  stop-color: var(--svg-color--57a7fb, #57A7FB);
  stop-opacity: 0;
}

.xxjj5obiq {
  stop-color: var(--svg-color--4db6ff, #4DB6FF);
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y39x50mqx {
  stop-color: var(--svg-color--56c3ff, #56C3FF);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yn_cprukr {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.403 6.325a.21.21 0 0 0-.417.048l.159 1.385l-1.025-.928a.21.21 0 1 0-.282.311l5.73 5.192a.21.21 0 0 0 .283-.312l-4.235-3.836z");
}

.yq1j9wb8r {
  stop-color: var(--svg-color--95726c, #95726C);
  stop-opacity: 0;
}

.ywk-_ln5y {
  stop-color: var(--svg-color--4b90ea, #4B90EA);
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_5s59bdn {
  width: 4.843px;
  height: 8.244px;
  rx: 2.422px;
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z0_tnl66g {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
  stop-opacity: 0;
}

.z30kudb-o {
  cx: 6.572px;
  cy: 15.685px;
  r: 0.438px;
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z45oacyxz {
  d: path("m17.397 26.507l-.62 1.014c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l.466-1.017z");
}

.zd1r_u8ze {
  stop-color: var(--svg-color--6a4e8f, #6A4E8F);
}

.zh46g387g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M23.32 8.935v.258a.9.9 0 0 1-.25.617v0");
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zozno708c {
  stop-color: var(--svg-color--9d7d72, #9D7D72);
  stop-opacity: 0;
}

.zpi-n7hqe {
  d: path("M16.968 7.51c.028.037-.03.082-.095.131c-.066.05-.114.084-.142.047s.003-.107.069-.156c.065-.049.14-.059.168-.022");
}

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

</style>
