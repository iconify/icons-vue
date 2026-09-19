<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#svgIDa)" class="qut0ht_ps"/><path fill="url(#svgIDb)" class="qut0ht_ps"/><g filter="url(#svgIDc)"><path class="z78u0tbjp"/></g><g filter="url(#svgIDd)"><path class="jcp6wzblx"/></g><path fill="url(#svgIDe)" class="xbx983bqi"/><path fill="url(#svgIDf)" class="xbx983bqi"/><path fill="url(#svgIDg)" class="c65lz4_ey"/><path fill="url(#svgIDh)" class="c65lz4_ey"/><circle class="v2km0iban"/><g filter="url(#svgIDi)"><path clip-rule="evenodd" class="s6sao6bdm"/></g><circle fill="url(#svgIDj)" transform="matrix(-1 0 0 1 12.14 16.739)" class="kr_eiac3t"/><g clip-rule="evenodd" filter="url(#svgIDk)" class="d2kvgvbvc"><path class="cttd0vqiy"/><path fill="url(#svgIDl)" class="wi6lfh0ov"/></g><path fill="url(#svgIDm)" class="hbe-jrbql"/><path fill="url(#svgIDn)" class="hbe-jrbql"/><g filter="url(#svgIDo)"><path class="nrrx0s8-f"/></g><path class="y_jvuobbm"/><path fill="url(#svgIDp)" class="qy5kkb6yn"/><g filter="url(#svgIDq)"><path class="yrn5k97fg"/></g><path fill="url(#svgIDr)" class="zdbmkmbsu"/><path fill="url(#svgIDs)" class="zdbmkmbsu"/><path fill="url(#svgIDt)" class="zdbmkmbsu"/><path fill="url(#svgIDu)" class="zdbmkmbsu"/><path fill="url(#svgIDv)" class="zdbmkmbsu"/><path fill="url(#svgIDw)" class="mh1m83zfh"/><g filter="url(#svgIDx)"><path class="mr7mtsbfo"/></g><g filter="url(#svgIDy)"><circle fill="url(#svgIDz)" class="ip3z8ac5u"/></g><g filter="url(#svgIDA)"><circle fill="url(#svgIDB)" class="vnhotb5ff"/></g><g filter="url(#svgIDC)"><circle fill="url(#svgIDD)" class="g8u4mfjba"/><circle fill="url(#svgIDE)" class="g8u4mfjba"/></g><g filter="url(#svgIDF)"><circle class="jjabv6bmv"/><circle fill="url(#svgIDG)" class="juie4_buk"/><circle fill="url(#svgIDH)" class="juie4_buk"/></g><g filter="url(#svgIDI)"><path fill="url(#svgIDJ)" class="h89calbho"/><path fill="url(#svgIDK)" class="h89calbho"/><path fill="url(#svgIDL)" class="h89calbho"/><path fill="url(#svgIDM)" class="h89calbho"/><path fill="url(#svgIDN)" class="h89calbho"/><path fill="url(#svgIDO)" class="h89calbho"/></g><g filter="url(#svgIDP)"><path fill="url(#svgIDQ)" class="xa712tbza"/></g><g filter="url(#svgIDR)"><path class="ug6cdac2s"/><path fill="url(#svgIDS)" class="eincf4brz"/><path fill="url(#svgIDT)" class="eincf4brz"/><path fill="url(#svgIDU)" class="eincf4brz"/><path fill="url(#svgIDV)" class="eincf4brz"/></g><g filter="url(#svgIDW)"><path class="nfx3vfb7t"/></g><g filter="url(#svgIDX)"><path class="duvuxfoss"/><path fill="url(#svgIDY)" class="o36si5bjx"/><path fill="url(#svgIDZ)" class="o36si5bjx"/><path fill="url(#svgIDaa)" class="o36si5bjx"/><path fill="url(#svgIDab)" class="o36si5bjx"/></g><path stroke="url(#svgIDac)" class="nr2haubga"/><g filter="url(#svgIDad)"><path class="y1wva1b8d"/></g><g filter="url(#svgIDae)"><path class="cu_5lxbsd"/></g><path class="asqafxbsr"/><path fill="url(#svgIDaf)" class="xexis_b4b"/><path class="dsfgl5m-k"/><g filter="url(#svgIDag)"><path class="ey475tggo"/><path fill="url(#svgIDah)" class="rz7crhb7k"/></g><g filter="url(#svgIDai)"><path fill="url(#svgIDaj)" class="gh88kyb7c"/></g><path class="xz5bs-box"/><path fill="url(#svgIDak)" class="y2hx4frna"/><path class="c7a6l0b5a"/><g filter="url(#svgIDal)"><path fill="url(#svgIDam)" class="w4ytb6bgb"/></g><g filter="url(#svgIDan)" transform="rotate(-27.914 7.77 7.612)"><ellipse class="b4vw36bgh"/><ellipse fill="url(#svgIDao)" class="wz0fo3usk"/></g><g filter="url(#svgIDap)"><path stroke="url(#svgIDaq)" class="xzduepb8t"/></g><g filter="url(#svgIDar)"><path stroke="url(#svgIDas)" class="enkekwbzp"/></g><g filter="url(#svgIDat)"><path stroke="url(#svgIDau)" class="wzs083b9c"/></g><g filter="url(#svgIDav)"><path class="q2g11qxsp"/></g><g filter="url(#svgIDaw)"><path class="mddk40bcp"/></g><g filter="url(#svgIDax)"><path fill="url(#svgIDay)" class="ttdjgmu-w"/></g><path fill="url(#svgIDaz)" class="skdh8c8wf"/><path fill="url(#svgIDaA)" class="skdh8c8wf"/><g filter="url(#svgIDaB)"><path class="jaasi8b4f"/></g><g filter="url(#svgIDaC)"><path class="ocjhgybgx"/></g><path fill="url(#svgIDaD)" class="g1-cakgjb"/><path fill="url(#svgIDaE)" class="g1-cakgjb"/><path fill="url(#svgIDaF)" class="tjubatb2f"/><path fill="url(#svgIDaG)" class="tjubatb2f"/><circle class="f5qs1xbvv"/><g filter="url(#svgIDaH)"><path clip-rule="evenodd" class="rvhaf89mo"/></g><circle fill="url(#svgIDaI)" transform="matrix(-1 0 0 1 25.185 16.739)" class="kr_eiac3t"/><g clip-rule="evenodd" filter="url(#svgIDaJ)" class="d2kvgvbvc"><path class="elae_ccjw"/><path fill="url(#svgIDaK)" class="wzc2yekot"/></g><path fill="url(#svgIDaL)" class="o3ld2rb-v"/><path fill="url(#svgIDaM)" class="o3ld2rb-v"/><g filter="url(#svgIDaN)"><path class="fx5kzlbgl"/></g><path class="mngobgbzy"/><path fill="url(#svgIDaO)" class="j7sojhblo"/><g filter="url(#svgIDaP)"><path class="g6a574b3m"/></g><path fill="url(#svgIDaQ)" class="nykqrqb8m"/><path fill="url(#svgIDaR)" class="nykqrqb8m"/><path fill="url(#svgIDaS)" class="nykqrqb8m"/><path fill="url(#svgIDaT)" class="nykqrqb8m"/><path fill="url(#svgIDaU)" class="nykqrqb8m"/><path fill="url(#svgIDaV)" class="jaeg0gihu"/><g filter="url(#svgIDaW)"><path class="htg2i4b9s"/></g><g filter="url(#svgIDaX)"><circle fill="url(#svgIDaY)" class="znq4zxb8i"/></g><g filter="url(#svgIDaZ)"><circle fill="url(#svgIDba)" class="g5_lm1btg"/></g><g filter="url(#svgIDbb)"><circle fill="url(#svgIDbc)" class="sujcsrb0x"/><circle fill="url(#svgIDbd)" class="sujcsrb0x"/></g><g filter="url(#svgIDbe)"><circle class="soogndbqj"/><circle fill="url(#svgIDbf)" class="euum4881d"/><circle fill="url(#svgIDbg)" class="euum4881d"/></g><g filter="url(#svgIDbh)"><path fill="url(#svgIDbi)" class="l5ux1zbca"/><path fill="url(#svgIDbj)" class="l5ux1zbca"/><path fill="url(#svgIDbk)" class="l5ux1zbca"/><path fill="url(#svgIDbl)" class="l5ux1zbca"/><path fill="url(#svgIDbm)" class="l5ux1zbca"/><path fill="url(#svgIDbn)" class="l5ux1zbca"/></g><g filter="url(#svgIDbo)"><path fill="url(#svgIDbp)" class="p5cm9kb5c"/></g><g filter="url(#svgIDbq)"><path class="rkyo55bnz"/><path fill="url(#svgIDbr)" class="t6e5mdbiw"/><path fill="url(#svgIDbs)" class="t6e5mdbiw"/><path fill="url(#svgIDbt)" class="t6e5mdbiw"/><path fill="url(#svgIDbu)" class="t6e5mdbiw"/></g><g filter="url(#svgIDbv)"><path class="l998yxb7o"/></g><g filter="url(#svgIDbw)"><path class="hrdqtczmx"/><path fill="url(#svgIDbx)" class="malayvgwv"/><path fill="url(#svgIDby)" class="malayvgwv"/><path fill="url(#svgIDbz)" class="malayvgwv"/><path fill="url(#svgIDbA)" class="malayvgwv"/></g><path stroke="url(#svgIDbB)" class="dx7vebcfr"/><g filter="url(#svgIDbC)"><path class="bi4592nco"/></g><g filter="url(#svgIDbD)"><path class="f1jfk8obn"/></g><path class="ng9x6tbze"/><path fill="url(#svgIDbE)" class="yo91qy_oj"/><path class="ne8gjgifp"/><g filter="url(#svgIDbF)"><path class="i6bc9d3zb"/><path fill="url(#svgIDbG)" class="pt7ppjbll"/></g><g filter="url(#svgIDbH)"><path fill="url(#svgIDbI)" class="f9vnpk6yx"/></g><path class="e3fjfibyx"/><path fill="url(#svgIDbJ)" class="tyxtbubbe"/><path class="fjnbe8xlq"/><g filter="url(#svgIDbK)"><path fill="url(#svgIDbL)" class="pbhi61i5p"/></g><g filter="url(#svgIDbM)" transform="rotate(-27.914 20.816 7.612)"><ellipse class="eskd0b1uv"/><ellipse fill="url(#svgIDbN)" class="oygygkboe"/></g><g filter="url(#svgIDbO)"><path stroke="url(#svgIDbP)" class="udwkkpblr"/></g><g filter="url(#svgIDbQ)"><path stroke="url(#svgIDbR)" class="ryw9-bb8r"/></g><g filter="url(#svgIDbS)"><path stroke="url(#svgIDbT)" class="twz1je0id"/></g><g filter="url(#svgIDbU)"><path class="mguvbdcsc"/></g><g filter="url(#svgIDbV)"><path class="r8c-l-bmo"/></g><g filter="url(#svgIDbW)"><path fill="url(#svgIDbX)" class="ks3ta5xvf"/></g><defs><radialGradient id="svgIDe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 7.541 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDf" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -26.585 21.054) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 16.203 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 15.494 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDj" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="yrxal2b8w"/><stop offset="1" class="iks-j-9-l"/></radialGradient><radialGradient id="svgIDl" cx="0" cy="0" r="1" gradientTransform="rotate(157.797 6.31 8.29) scale(1.65389 2.1298)" gradientUnits="userSpaceOnUse"><stop class="kibsqob-j"/><stop offset="1" class="izaac2bev"/></radialGradient><radialGradient id="svgIDr" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 9.51 21.848)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDt" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 11.97 7.278) scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDu" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 3.762 7.838) scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDv" cx="0" cy="0" r="1" gradientTransform="matrix(.45766 -2.68928 1.12443 .19135 8.12 21)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDw" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 8.334 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="u0gzasb1f"/><stop offset=".902" class="mtb7t9jlr"/></radialGradient><radialGradient id="svgIDz" cx="0" cy="0" r="1" gradientTransform="matrix(.74335 0 0 1.30087 6.093 7.941)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="svgIDE" cx="0" cy="0" r="1" gradientTransform="matrix(.35019 -.255 .29104 .3997 10.987 7.83)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="svgIDG" cx="0" cy="0" r="1" gradientTransform="matrix(.34788 -.63985 .3745 .20362 10.812 8.29)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="svgIDH" cx="0" cy="0" r="1" gradientTransform="matrix(.10983 .10872 -.14015 .1416 10.83 7.941)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="svgIDL" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.00971 -4.08553 0 8.683 7.857)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="svgIDM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.55367 .68144 0 9.805 7.403)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="svgIDN" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.58917 .73268 0 7.874 7.389)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="svgIDO" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20346 -.29095 .17095 -.70711 10.62 10.55)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="svgIDS" cx="0" cy="0" r="1" gradientTransform="matrix(.33795 -1.25241 .46443 .12532 10.652 6.202)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="svgIDT" cx="0" cy="0" r="1" gradientTransform="matrix(1.62018 .1491 -.08017 .87116 9.956 5.457)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="svgIDU" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7113 -1.10159 0 8.811 4.298)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="svgIDV" cx="0" cy="0" r="1" gradientTransform="matrix(1.30211 -.95422 1.49495 2.03998 6.08 7.186)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="svgIDab" cx="0" cy="0" r="1" gradientTransform="matrix(0 .0834 -.26796 0 8.95 8.622)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="svgIDaf" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3436 -.54652 0 9.734 7.652)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDah" cx="0" cy="0" r="1" gradientTransform="matrix(-.09822 -.12656 .17425 -.13523 9.637 7.688)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDak" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34361 -.54655 0 7.886 7.652)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDao" cx="0" cy="0" r="1" gradientTransform="matrix(-.00328 -.20924 .25152 -.00394 7.764 7.745)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDaD" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 20.586 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDaE" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -20.062 34.625) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDaF" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 29.249 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDaG" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 28.54 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDaI" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="yrxal2b8w"/><stop offset="1" class="iks-j-9-l"/></radialGradient><radialGradient id="svgIDaK" cx="0" cy="0" r="1" gradientTransform="rotate(157.797 12.832 9.57) scale(1.65389 2.1298)" gradientUnits="userSpaceOnUse"><stop class="kibsqob-j"/><stop offset="1" class="izaac2bev"/></radialGradient><radialGradient id="svgIDaQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 22.556 21.848)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDaS" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 18.493 3.115) scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 10.284 10.168) scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDaU" cx="0" cy="0" r="1" gradientTransform="rotate(-80.342 23.02 -2.037) scale(2.72794 1.1406)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDaV" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 21.38 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="u0gzasb1f"/><stop offset=".902" class="mtb7t9jlr"/></radialGradient><radialGradient id="svgIDaY" cx="0" cy="0" r="1" gradientTransform="matrix(.74335 0 0 1.30087 19.138 7.941)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="svgIDbd" cx="0" cy="0" r="1" gradientTransform="matrix(.35019 -.255 .29104 .3997 24.032 7.83)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="svgIDbf" cx="0" cy="0" r="1" gradientTransform="matrix(.34788 -.63985 .3745 .20362 23.857 8.29)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="svgIDbg" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 2.281 33) scale(.15454 .19923)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="svgIDbk" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.00971 -4.08553 0 21.729 7.857)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="svgIDbl" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.55367 .68144 0 22.85 7.403)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="svgIDbm" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.58917 .73268 0 20.92 7.389)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="svgIDbn" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20346 -.29095 .17095 -.70711 23.664 10.55)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="svgIDbr" cx="0" cy="0" r="1" gradientTransform="matrix(.33795 -1.25241 .46443 .12532 23.697 6.202)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="svgIDbs" cx="0" cy="0" r="1" gradientTransform="matrix(1.62018 .1491 -.08017 .87116 23 5.457)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="svgIDbt" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7113 -1.10159 0 21.856 4.298)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="svgIDbu" cx="0" cy="0" r="1" gradientTransform="matrix(1.30211 -.95422 1.49495 2.03998 19.124 7.186)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="svgIDbA" cx="0" cy="0" r="1" gradientTransform="matrix(0 .0834 -.26796 0 21.995 8.622)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="svgIDbE" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3436 -.54652 0 22.78 7.652)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDbG" cx="0" cy="0" r="1" gradientTransform="matrix(-.09822 -.12656 .17425 -.13523 22.682 7.689)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDbJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34361 -.54655 0 20.931 7.652)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDbN" cx="0" cy="0" r="1" gradientTransform="matrix(-.00328 -.20924 .25152 -.00394 20.81 7.745)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="svgIDc" width="6.578" height="10.091" x="10.026" y="19.942" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.121569 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDd" width="4.976" height="9.579" x="10.996" y="19.362" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".25"/></filter><filter id="svgIDi" width="5.896" height="7.11" x="2.751" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.160784 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.176471 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_708" result="effect2_innerShadow_4002_708"/></filter><filter id="svgIDk" width="5.996" height="6.96" x="9.267" y="10.306" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.105882 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDo" width="2.703" height="2.68" x="12.199" y="11.784" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".2"/></filter><filter id="svgIDq" width="9.692" height="11.056" x="4.665" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_708" result="effect2_innerShadow_4002_708"/></filter><filter id="svgIDx" width="2.793" height="3.034" x="3.321" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".2"/></filter><filter id="svgIDy" width="1.614" height="1.414" x="6.093" y="7.234" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDA" width="1.843" height="1.843" x="5.878" y="7.02" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".25"/></filter><filter id="svgIDC" width="1.664" height="1.664" x="10.123" y="6.984" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDF" width="1.843" height="1.843" x="9.908" y="7.02" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".25"/></filter><filter id="svgIDI" width="4.394" height="5.245" x="6.626" y="5.559" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDP" width="3.799" height="3.299" x="7.883" y="4.559" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".5"/></filter><filter id="svgIDR" width="5.338" height="3.507" x="6.142" y="4.198" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDW" width="2.246" height="2.636" x="7.587" y="7.02" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".375"/></filter><filter id="svgIDX" width=".895" height="1.236" x="8.364" y="7.651" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".025"/></filter><filter id="svgIDad" width="1.406" height="1.024" x="9.312" y="6.165" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDae" width="1.406" height="1.024" x="7.131" y="6.165" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDag" width=".449" height=".41" x="9.366" y="7.408" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".05"/></filter><filter id="svgIDai" width=".608" height=".617" x="9.664" y="7.383" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".1"/></filter><filter id="svgIDal" width=".648" height=".671" x="7.782" y="7.356" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".1"/></filter><filter id="svgIDan" width=".502" height=".414" x="7.52" y="7.405" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".05"/></filter><filter id="svgIDap" width="1.133" height=".533" x="9.34" y="6.539" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".05"/></filter><filter id="svgIDar" width="1.166" height=".557" x="7.128" y="6.566" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".05"/></filter><filter id="svgIDat" width=".859" height="1.394" x="6.407" y="5.528" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".125"/></filter><filter id="svgIDav" width="1.73" height="2.911" x="6.683" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_708" result="effect2_innerShadow_4002_708"/></filter><filter id="svgIDaw" width="1.73" height="2.911" x="9.394" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_708" result="effect2_innerShadow_4002_708"/></filter><filter id="svgIDax" width="4.792" height="2.36" x="6.658" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_708" result="effect2_innerShadow_4002_708"/></filter><filter id="svgIDaB" width="6.578" height="10.091" x="23.071" y="19.942" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.121569 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDaC" width="4.976" height="9.579" x="24.041" y="19.362" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".25"/></filter><filter id="svgIDaH" width="5.896" height="7.11" x="15.796" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.160784 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.176471 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_708" result="effect2_innerShadow_4002_708"/></filter><filter id="svgIDaJ" width="5.996" height="6.96" x="22.312" y="10.306" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.105882 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDaN" width="2.703" height="2.68" x="25.244" y="11.784" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".2"/></filter><filter id="svgIDaP" width="9.692" height="11.056" x="17.71" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_708" result="effect2_innerShadow_4002_708"/></filter><filter id="svgIDaW" width="2.793" height="3.034" x="16.367" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".2"/></filter><filter id="svgIDaX" width="1.614" height="1.414" x="19.138" y="7.234" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDaZ" width="1.843" height="1.843" x="18.924" y="7.02" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".25"/></filter><filter id="svgIDbb" width="1.664" height="1.664" x="23.168" y="6.984" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDbe" width="1.843" height="1.843" x="22.953" y="7.02" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".25"/></filter><filter id="svgIDbh" width="4.394" height="5.245" x="19.671" y="5.559" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDbo" width="3.799" height="3.299" x="20.928" y="4.559" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".5"/></filter><filter id="svgIDbq" width="5.338" height="3.507" x="19.187" y="4.198" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDbv" width="2.246" height="2.636" x="20.632" y="7.02" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".375"/></filter><filter id="svgIDbw" width=".895" height="1.236" x="21.409" y="7.651" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".025"/></filter><filter id="svgIDbC" width="1.406" height="1.024" x="22.357" y="6.165" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDbD" width="1.406" height="1.024" x="20.176" y="6.165" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/></filter><filter id="svgIDbF" width=".449" height=".41" x="22.411" y="7.408" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".05"/></filter><filter id="svgIDbH" width=".608" height=".617" x="22.709" y="7.383" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".1"/></filter><filter id="svgIDbK" width=".648" height=".671" x="20.827" y="7.356" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".1"/></filter><filter id="svgIDbM" width=".502" height=".414" x="20.565" y="7.405" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".05"/></filter><filter id="svgIDbO" width="1.133" height=".533" x="22.385" y="6.539" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".05"/></filter><filter id="svgIDbQ" width="1.166" height=".557" x="20.174" y="6.566" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".05"/></filter><filter id="svgIDbS" width=".859" height="1.394" x="19.452" y="5.528" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_708" stdDeviation=".125"/></filter><filter id="svgIDbU" width="1.73" height="2.911" x="19.728" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_708" result="effect2_innerShadow_4002_708"/></filter><filter id="svgIDbV" width="1.73" height="2.911" x="22.439" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_708" result="effect2_innerShadow_4002_708"/></filter><filter id="svgIDbW" width="4.792" height="2.36" x="19.703" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_708"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_708" result="effect2_innerShadow_4002_708"/></filter><linearGradient id="svgIDa" x1="5.915" x2="8.034" y1="24.13" y2="24.269" gradientUnits="userSpaceOnUse"><stop class="lenvnubyg"/><stop offset="1" class="jufkgjxmt"/></linearGradient><linearGradient id="svgIDb" x1="5.807" x2="6.354" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="vnco_-oam"/><stop offset="1" class="ily885bgj"/></linearGradient><linearGradient id="svgIDm" x1="5.338" x2="6.26" y1="11.458" y2="13.39" gradientUnits="userSpaceOnUse"><stop class="jum30v1nu"/><stop offset=".527" class="zoz3lmrqj"/></linearGradient><linearGradient id="svgIDn" x1="5.854" x2="5.494" y1="13.177" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="b1pd8upnt"/><stop offset="1" class="n366y7b2s"/></linearGradient><linearGradient id="svgIDp" x1="12.088" x2="12.526" y1="13.176" y2="12.083" gradientUnits="userSpaceOnUse"><stop class="bqhl8ltyr"/><stop offset="1" class="qhg47wyku"/></linearGradient><linearGradient id="svgIDs" x1="5.729" x2="6.401" y1="19.255" y2="19.239" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDB" x1="6.8" x2="6.529" y1="8.059" y2="8.059" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="svgIDD" x1="11.29" x2="10.943" y1="7.479" y2="8.553" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="svgIDJ" x1="10.521" x2="7.286" y1="8.106" y2="8.588" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="svgIDK" x1="6.525" x2="7.485" y1="9.248" y2="9.188" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="svgIDQ" x1="9.217" x2="12.867" y1="6.676" y2="5.419" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="svgIDY" x1="8.445" x2="8.842" y1="8.386" y2="8.386" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="svgIDZ" x1="9.209" x2="8.774" y1="8.522" y2="8.516" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="svgIDaa" x1="8.893" x2="8.893" y1="8.837" y2="8.594" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="svgIDac" x1="8.372" x2="8.556" y1="9.521" y2="9.229" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="svgIDaj" x1="10.064" x2="9.931" y1="7.675" y2="7.757" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDam" x1="8.201" x2="8.068" y1="7.675" y2="7.757" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDaq" x1="10.07" x2="9.892" y1="6.769" y2="6.405" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="svgIDas" x1="7.823" x2="7.319" y1="6.715" y2="6.503" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="svgIDau" x1="6.836" x2="6.836" y1="5.861" y2="6.775" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="svgIDay" x1="10.697" x2="7.197" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient><linearGradient id="svgIDaz" x1="18.96" x2="21.079" y1="24.13" y2="24.269" gradientUnits="userSpaceOnUse"><stop class="lenvnubyg"/><stop offset="1" class="jufkgjxmt"/></linearGradient><linearGradient id="svgIDaA" x1="18.852" x2="19.399" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="vnco_-oam"/><stop offset="1" class="ily885bgj"/></linearGradient><linearGradient id="svgIDaL" x1="18.383" x2="19.305" y1="11.458" y2="13.39" gradientUnits="userSpaceOnUse"><stop class="jum30v1nu"/><stop offset=".527" class="zoz3lmrqj"/></linearGradient><linearGradient id="svgIDaM" x1="18.899" x2="18.54" y1="13.177" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="b1pd8upnt"/><stop offset="1" class="n366y7b2s"/></linearGradient><linearGradient id="svgIDaO" x1="25.133" x2="25.571" y1="13.176" y2="12.083" gradientUnits="userSpaceOnUse"><stop class="bqhl8ltyr"/><stop offset="1" class="qhg47wyku"/></linearGradient><linearGradient id="svgIDaR" x1="18.774" x2="19.446" y1="19.255" y2="19.239" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDba" x1="19.845" x2="19.574" y1="8.059" y2="8.059" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="svgIDbc" x1="24.335" x2="23.988" y1="7.479" y2="8.553" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="svgIDbi" x1="23.566" x2="20.331" y1="8.106" y2="8.588" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="svgIDbj" x1="19.571" x2="20.53" y1="9.248" y2="9.188" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="svgIDbp" x1="22.262" x2="25.913" y1="6.676" y2="5.419" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="svgIDbx" x1="21.49" x2="21.888" y1="8.386" y2="8.386" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="svgIDby" x1="22.254" x2="21.819" y1="8.522" y2="8.516" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="svgIDbz" x1="21.939" x2="21.939" y1="8.837" y2="8.594" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="svgIDbB" x1="21.417" x2="21.601" y1="9.521" y2="9.229" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="svgIDbI" x1="23.109" x2="22.976" y1="7.675" y2="7.757" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDbL" x1="21.246" x2="21.113" y1="7.675" y2="7.757" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDbP" x1="23.115" x2="22.937" y1="6.769" y2="6.405" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="svgIDbR" x1="20.868" x2="20.365" y1="6.715" y2="6.503" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="svgIDbT" x1="19.882" x2="19.882" y1="5.861" y2="6.775" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="svgIDbX" x1="23.743" x2="20.243" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-with-bunny-ears-dark" /></template>
<style>
.a3709fbcn {
  stop-color: var(--svg-color--6f597b, #6F597B);
  stop-opacity: 0;
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.asqafxbsr {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.823 7.335c.276 0 .51.191.574.449a.116.116 0 0 1-.114.144h-.945a.097.097 0 0 1-.096-.115a.592.592 0 0 1 .58-.478Z");
}

.atfd_nb4o {
  stop-color: var(--svg-color--4c266b, #4C266B);
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.b1pd8upnt {
  stop-color: var(--svg-color--2c1c3e, #2C1C3E);
}

.b4vw36bgh {
  cx: 7.771px;
  cy: 7.612px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.165px;
  ry: 0.084px;
}

.bi4592nco {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M23.432 6.79v-.001l-.002-.001l-.002-.002l-.005-.004a.704.704 0 0 0-.065-.045a1.2 1.2 0 0 0-.81-.156a.226.226 0 0 0 .07.446a.748.748 0 0 1 .5.093a.396.396 0 0 1 .023.016a.226.226 0 1 0 .29-.347Z");
}

.boon_rjzq {
  stop-color: var(--svg-color--4c2d62, #4C2D62);
}

.bqhl8ltyr {
  stop-color: var(--svg-color--2d1b3f, #2D1B3F);
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.c65lz4_ey {
  d: path("M15.63 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.166-.234l-.563-1.607Z");
}

.c7a6l0b5a {
  fill: var(--svg-color--000, #000);
  d: path("M8.101 7.828a.216.216 0 0 0-.216-.216a.216.216 0 0 0-.192.316h.383a.215.215 0 0 0 .025-.1Z");
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cttd0vqiy {
  fill: var(--svg-color--432a2f, #432A2F);
  d: path("M9.369 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-3.574-2.015a.8.8 0 0 0-1.089.308Z");
}

.cu_5lxbsd {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M7.213 6.79v-.001l.001-.001l.002-.002l.005-.004a.593.593 0 0 1 .066-.045a1.2 1.2 0 0 1 .81-.156a.226.226 0 1 1-.07.446a.748.748 0 0 0-.5.093a.391.391 0 0 0-.027.018a.226.226 0 0 1-.287-.349Z");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.dsfgl5m-k {
  fill: var(--svg-color--000, #000);
  d: path("M9.519 7.828c0-.12.096-.216.216-.216a.216.216 0 0 1 .192.316h-.383a.196.196 0 0 1-.025-.1Z");
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.duvuxfoss {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m8.65 7.82l-.226.72a.228.228 0 0 0 .22.297h.334a.23.23 0 0 0 .22-.297l-.225-.72c-.048-.16-.273-.16-.324 0Z");
}

.dx7vebcfr {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.569 9.244a.109.109 0 0 0-.013-.138a.115.115 0 0 0-.136-.023a1.217 1.217 0 0 1-.564.134c-.207 0-.401-.049-.563-.133a.115.115 0 0 0-.137.023a.108.108 0 0 0-.012.137m1.425 0l-.042-.027l.041.027Zm0 0a.852.852 0 0 1-.713.38a.852.852 0 0 1-.712-.38m0 0v.001l.042-.028m-.042.027l.042-.027m0 0a.802.802 0 0 0 .67.358a.802.802 0 0 0 .67-.358c.037-.055-.025-.119-.083-.089c-.17.089-.37.14-.587.14c-.215 0-.417-.051-.587-.14c-.057-.03-.12.036-.083.089Z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3fjfibyx {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.843 7.335a.592.592 0 0 0-.574.449a.116.116 0 0 0 .113.144h.945c.06 0 .108-.055.096-.115a.593.593 0 0 0-.58-.478Z");
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.eincf4brz {
  d: path("m10.852 5.197l.182.09c.318.159.5.52.432.905l-.25 1.287c-.022.133-.11.223-.242.226h-.008s.023-.384.045-.61c.019-.183-.013-.24-.181-.406a.532.532 0 0 1-.16-.362v-.361a.244.244 0 0 0-.181-.226a6.942 6.942 0 0 0-1.659-.181c-.818 0-1.386.113-1.659.18a.22.22 0 0 0-.181.227v.361a.448.448 0 0 1-.16.362l-.068.067c-.09.068-.136.204-.136.317c.023.248.046.61.046.61l-.021-.001a.268.268 0 0 1-.252-.225l-.25-1.288a.865.865 0 0 1 .454-.881l.182-.09a3.25 3.25 0 0 0 .341-.249l.409-.43a.83.83 0 0 1 .932-.135c.227.068.477.068.704 0c.34-.113.727-.022 1 .226l.34.339a.95.95 0 0 0 .341.248Z");
}

.elae_ccjw {
  fill: var(--svg-color--432a2f, #432A2F);
  d: path("M22.414 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-3.574-2.015a.8.8 0 0 0-1.09.308Z");
}

.enkekwbzp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M7.303 6.947c.139-.122.442-.251.817-.191");
}

.enwi01lgk {
  stop-color: var(--svg-color--522e71, #522E71);
  stop-opacity: 0;
}

.eox5rpbuq {
  stop-color: var(--svg-color--463049, #463049);
}

.eskd0b1uv {
  cx: 20.816px;
  cy: 7.612px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.165px;
  ry: 0.084px;
}

.euum4881d {
  cx: 23.875px;
  cy: 7.941px;
  r: 0.421px;
}

.ey475tggo {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M9.707 7.53c.027.036-.03.08-.093.128c-.064.048-.112.082-.138.046c-.027-.036.003-.104.067-.152s.137-.058.164-.022Z");
}

.f1jfk8obn {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M20.258 6.79v-.001l.001-.001l.002-.002l.005-.004a.498.498 0 0 1 .066-.045c.042-.027.102-.06.177-.09a1.2 1.2 0 0 1 .633-.066a.226.226 0 1 1-.07.446a.748.748 0 0 0-.5.093a.374.374 0 0 0-.027.018a.226.226 0 0 1-.287-.349Z");
}

.f5qs1xbvv {
  cx: 18.559px;
  cy: 16.61px;
  r: 0.766px;
  fill: var(--svg-color--2d151b, #2D151B);
}

.f97z0ccja {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
  stop-opacity: 0;
}

.f9vnpk6yx {
  d: path("M23.117 7.779a.355.355 0 0 0-.098-.196l-.11.12l.05.097l.158-.021Z");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fjnbe8xlq {
  fill: var(--svg-color--000, #000);
  d: path("M21.147 7.828a.216.216 0 0 0-.217-.216a.216.216 0 0 0-.192.316h.383a.214.214 0 0 0 .026-.1Z");
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx5kzlbgl {
  stroke: var(--svg-color--5c4a49, #5C4A49);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m25.77 12.31l1.083.627c.193.1.578.44.569 1.002");
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g1-cakgjb {
  d: path("m20.928 28.192l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
}

.g1mnylbkn {
  stop-color: var(--svg-color--463049, #463049);
  stop-opacity: 0;
}

.g4nv9obue {
  stop-color: var(--svg-color--44384d, #44384D);
}

.g5_lm1btg {
  cx: 19.845px;
  cy: 7.941px;
  r: 0.421px;
}

.g6a574b3m {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M21.832 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055L23.22 21h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.g8u4mfjba {
  cx: 10.83px;
  cy: 7.941px;
  r: 0.707px;
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gh88kyb7c {
  d: path("M10.072 7.779a.356.356 0 0 0-.098-.196l-.11.12l.05.097l.158-.021Z");
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.h89calbho {
  d: path("M6.65 7.682h.022s-.023-.36-.046-.61c0-.112.046-.248.137-.316l.068-.067a.448.448 0 0 0 .159-.362v-.361a.22.22 0 0 1 .182-.226a6.94 6.94 0 0 1 1.658-.181c.818 0 1.386.113 1.659.18c.09.023.182.114.182.227v.361c0 .136.068.271.159.362c.212.149.2.23.181.406c-.022.226-.045.61-.045.61h.008l-.113 1.677c-.068.75-.657 1.272-1.36 1.272h-1.36c-.725 0-1.292-.522-1.36-1.272l-.13-1.7Z");
}

.hbe-jrbql {
  d: path("m5.26 13.39l2.828-1.586a.8.8 0 0 0-.781-1.396l-2.86 1.612l.813 1.37Z");
}

.hi3bu5i6r {
  stop-color: var(--svg-color--4c266b, #4C266B);
  stop-opacity: 0;
}

.hrdqtczmx {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m21.694 7.82l-.225.72a.228.228 0 0 0 .22.297h.334a.23.23 0 0 0 .22-.297l-.225-.72c-.048-.16-.273-.16-.324 0Z");
}

.htg2i4b9s {
  stroke: var(--svg-color--5c4a49, #5C4A49);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.986 13.917c-.089.073-.194.29.093.57a70.77 70.77 0 0 0 1.555 1.415");
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.i6bc9d3zb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.752 7.53c.027.036-.03.08-.093.128c-.064.048-.112.082-.139.046c-.026-.036.004-.104.068-.152s.137-.058.164-.022Z");
}

.i7j8_4zgt {
  stop-color: var(--svg-color--59436a, #59436A);
}

.iks-j-9-l {
  stop-color: var(--svg-color--382032, #382032);
}

.ily885bgj {
  stop-color: var(--svg-color--55423e, #55423E);
  stop-opacity: 0;
}

.ip3z8ac5u {
  cx: 6.8px;
  cy: 7.941px;
  r: 0.707px;
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.izaac2bev {
  stop-color: var(--svg-color--6a5654, #6A5654);
  stop-opacity: 0;
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.j7sojhblo {
  d: path("m25.549 13.39l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.jaasi8b4f {
  fill: var(--svg-color--442a2e, #442A2E);
  d: path("m25.774 19.942l-2.703.719l3.604 7.838a2.64 2.64 0 0 0 2.398 1.534c.121 0 .206-.12.166-.234l-3.465-9.857Z");
}

.jaeg0gihu {
  d: path("m21.662 11.775l-.865-1.505h2.125l-.824 1.5a.25.25 0 0 1-.436.005Z");
}

.jcp6wzblx {
  fill: var(--svg-color--655251, #655251);
  d: path("m11.496 20.164l.823-.302l3.153 8.579h-.758l-3.218-8.277Z");
}

.jdxsh3blt {
  stop-color: var(--svg-color--221630, #221630);
}

.jj65vhdzq {
  stop-color: var(--svg-color--635a6d, #635A6D);
}

.jjabv6bmv {
  cx: 10.83px;
  cy: 7.941px;
  r: 0.421px;
  fill: var(--svg-color--463133, #463133);
}

.jufkgjxmt {
  stop-color: var(--svg-color--533a3b, #533A3B);
}

.juie4_buk {
  cx: 10.83px;
  cy: 7.941px;
  r: 0.421px;
}

.jum30v1nu {
  stop-color: var(--svg-color--42384b, #42384B);
}

.k0aq2sbpu {
  stop-color: var(--svg-color--6f597b, #6F597B);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kibsqob-j {
  stop-color: var(--svg-color--6a5654, #6A5654);
}

.kr_eiac3t {
  r: 0.766px;
}

.ks3ta5xvf {
  d: path("M24.093 5.75c.019.097-.101.145-.166.071c-.454-.513-1.133-1.01-2.023-1.01c-.839 0-1.554.532-2.033 1.063c-.065.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.388-.053Z");
}

.kuw77jfnz {
  stop-color: var(--svg-color--645a6f, #645A6F);
}

.l5ux1zbca {
  d: path("M19.696 7.682h.02s-.022-.36-.045-.61c0-.112.046-.248.137-.316l.068-.067a.448.448 0 0 0 .159-.362v-.361a.22.22 0 0 1 .182-.226c.272-.068.84-.181 1.658-.181a6.94 6.94 0 0 1 1.659.18c.09.023.182.114.182.227v.361c0 .136.068.271.159.362c.212.149.2.23.182.406c-.023.226-.046.61-.046.61a.33.33 0 0 0 .008 0l-.113 1.677c-.068.75-.657 1.272-1.36 1.272h-1.36c-.725 0-1.291-.522-1.36-1.272l-.13-1.7Z");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l998yxb7o {
  fill: var(--svg-color--332024, #332024);
  d: path("m21.74 7.89l-.348.72c-.043.148.06.296.207.296h.312c.147 0 .25-.15.207-.297l-.211-.72c-.045-.159-.12-.159-.167 0Z");
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lenvnubyg {
  stop-color: var(--svg-color--3d2728, #3D2728);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.malayvgwv {
  d: path("m21.694 7.82l-.225.72a.228.228 0 0 0 .22.297h.334a.23.23 0 0 0 .22-.297l-.225-.72c-.048-.16-.273-.16-.324 0Z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mddk40bcp {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M10.771 3.273c-.222.71-.522 1.166-.644 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.211.086.356.403.078 1.29Z");
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mguvbdcsc {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M19.981 3.273c.222.71.522 1.166.645 1.305l.633-.242c-.014-.183-.097-.709-.325-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29Z");
}

.mh1m83zfh {
  d: path("m8.617 11.775l-.865-1.505h2.125l-.825 1.5a.25.25 0 0 1-.435.005Z");
}

.mlh1k8r8i {
  stop-color: var(--svg-color--656069, #656069);
}

.mngobgbzy {
  fill: var(--svg-color--605071, #605071);
  d: path("m25.549 13.39l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.mr7mtsbfo {
  stroke: var(--svg-color--5c4a49, #5C4A49);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M3.94 13.917c-.088.073-.193.29.094.57a70.98 70.98 0 0 0 1.555 1.415");
}

.mta_69bbu {
  stop-color: var(--svg-color--522e71, #522E71);
}

.mtb7t9jlr {
  stop-color: var(--svg-color--4c3534, #4C3534);
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n366y7b2s {
  stop-color: var(--svg-color--2c1c3e, #2C1C3E);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ne8gjgifp {
  fill: var(--svg-color--000, #000);
  d: path("M22.564 7.828c0-.12.096-.216.216-.216a.216.216 0 0 1 .193.316h-.383a.196.196 0 0 1-.026-.1Z");
}

.nfx3vfb7t {
  fill: var(--svg-color--332024, #332024);
  d: path("m8.695 7.89l-.348.72c-.043.148.06.296.207.296h.312c.147 0 .25-.15.207-.297l-.211-.72c-.045-.159-.12-.159-.167 0Z");
}

.ng9x6tbze {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.868 7.335c.276 0 .51.191.574.449a.116.116 0 0 1-.114.144h-.945a.097.097 0 0 1-.096-.115a.592.592 0 0 1 .58-.478Z");
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nr2haubga {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M9.523 9.244a.109.109 0 0 0-.012-.138a.115.115 0 0 0-.136-.023a1.216 1.216 0 0 1-.564.134c-.207 0-.401-.049-.564-.133a.115.115 0 0 0-.136.023a.108.108 0 0 0-.012.137m1.424 0l-.041-.027l.041.027Zm0 0a.852.852 0 0 1-.712.38a.852.852 0 0 1-.712-.38m0 0v.001l.042-.028m-.042.027l.042-.027m0 0a.802.802 0 0 0 .67.358a.802.802 0 0 0 .67-.358c.037-.055-.025-.119-.083-.089c-.17.089-.37.14-.587.14c-.215 0-.417-.051-.587-.14c-.058-.03-.12.036-.083.089Z");
}

.nrrx0s8-f {
  stroke: var(--svg-color--5c4a49, #5C4A49);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m12.724 12.31l1.083.627c.194.1.579.44.57 1.002");
}

.nykqrqb8m {
  d: path("M21.832 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055L23.22 21h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o36si5bjx {
  d: path("m8.65 7.82l-.226.72a.228.228 0 0 0 .22.297h.334a.23.23 0 0 0 .22-.297l-.225-.72c-.048-.16-.273-.16-.324 0Z");
}

.o3ld2rb-v {
  d: path("m18.306 13.39l2.827-1.586a.8.8 0 0 0-.781-1.396l-2.86 1.612l.814 1.37Z");
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.ocjhgybgx {
  fill: var(--svg-color--655251, #655251);
  d: path("m24.54 20.164l.824-.302l3.153 8.579h-.758l-3.218-8.277Z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oygygkboe {
  cx: 20.816px;
  cy: 7.612px;
  rx: 0.165px;
  ry: 0.084px;
}

.p5cm9kb5c {
  d: path("m23.535 5.559l-1.303.435a.444.444 0 0 0 .199.86l1.296-.173l-.192-1.122Z");
}

.pbhi61i5p {
  d: path("M21.275 7.784c0-.122-.099-.204-.126-.228l-.122.118l.075.153l.173-.043Z");
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pt7ppjbll {
  d: path("M22.752 7.53c.027.036-.03.08-.093.128c-.064.048-.112.082-.139.046c-.026-.036.004-.104.068-.152s.137-.058.164-.022Z");
}

.q2g11qxsp {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M6.936 3.273c.222.71.522 1.166.645 1.305l.633-.242c-.013-.183-.096-.709-.325-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29Z");
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qgz62l2ld {
  stop-color: var(--svg-color--443553, #443553);
}

.qhg47wyku {
  stop-color: var(--svg-color--2d1b3f, #2D1B3F);
  stop-opacity: 0;
}

.qut0ht_ps {
  d: path("m5.915 20.239l2.997.27l-1.063 7.94a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122V20.24Z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qy5kkb6yn {
  d: path("m12.504 13.39l-2.828-1.586a.8.8 0 0 1-.307-1.088c.216-.386.36-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.r8c-l-bmo {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M23.817 3.273c-.222.71-.523 1.166-.645 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.286-.808.579-1.09.875-.996c.212.086.356.403.079 1.29Z");
}

.rkyo55bnz {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m23.897 5.197l.182.09c.318.159.5.52.432.905l-.25 1.287c-.023.133-.11.223-.242.226h-.008s.023-.384.045-.61c.019-.183-.013-.24-.181-.406a.532.532 0 0 1-.16-.362v-.361a.244.244 0 0 0-.181-.226a6.941 6.941 0 0 0-1.659-.181c-.818 0-1.386.113-1.659.18a.22.22 0 0 0-.181.227v.361a.448.448 0 0 1-.16.362l-.068.067c-.09.068-.136.204-.136.317c.023.248.046.61.046.61l-.021-.001a.268.268 0 0 1-.252-.225l-.25-1.288a.865.865 0 0 1 .454-.881l.182-.09a3.25 3.25 0 0 0 .34-.249l.41-.43a.83.83 0 0 1 .932-.135c.227.068.477.068.704 0c.34-.113.727-.022 1 .226l.34.339c.091.113.205.18.341.248Z");
}

.rvhaf89mo {
  fill: var(--svg-color--462f33, #462F33);
  fill-rule: evenodd;
  d: path("M21.44 10.716a.8.8 0 0 1-.307 1.088l-3.527 1.978a.2.2 0 0 0-.034.325l1.9 1.763a.8.8 0 1 1-1.069 1.19l-1.973-1.72c-.93-.82-.855-2.148.348-2.917l3.574-2.015a.8.8 0 0 1 1.089.308Z");
}

.ryw9-bb8r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M20.349 6.947c.138-.122.441-.251.816-.191");
}

.rz7crhb7k {
  d: path("M9.707 7.53c.027.036-.03.08-.093.128c-.064.048-.112.082-.138.046c-.027-.036.003-.104.067-.152s.137-.058.164-.022Z");
}

.s6sao6bdm {
  fill: var(--svg-color--462f33, #462F33);
  fill-rule: evenodd;
  d: path("M8.395 10.716a.8.8 0 0 1-.307 1.088L4.56 13.782a.2.2 0 0 0-.035.325l1.9 1.763a.8.8 0 1 1-1.068 1.19l-1.973-1.72c-.93-.82-.855-2.148.347-2.917l3.575-2.015a.8.8 0 0 1 1.088.308Z");
}

.skdh8c8wf {
  d: path("m18.96 20.239l2.997.27l-1.063 7.94a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122V20.24Z");
}

.soogndbqj {
  cx: 23.875px;
  cy: 7.941px;
  r: 0.421px;
  fill: var(--svg-color--463133, #463133);
}

.sujcsrb0x {
  cx: 23.875px;
  cy: 7.941px;
  r: 0.707px;
}

.t6e5mdbiw {
  d: path("m23.897 5.197l.182.09c.318.159.5.52.432.905l-.25 1.287c-.023.133-.11.223-.242.226h-.008s.023-.384.045-.61c.019-.183-.013-.24-.181-.406a.532.532 0 0 1-.16-.362v-.361a.244.244 0 0 0-.181-.226a6.941 6.941 0 0 0-1.659-.181c-.818 0-1.386.113-1.659.18a.22.22 0 0 0-.181.227v.361a.448.448 0 0 1-.16.362l-.068.067c-.09.068-.136.204-.136.317c.023.248.046.61.046.61l-.021-.001a.268.268 0 0 1-.252-.225l-.25-1.288a.865.865 0 0 1 .454-.881l.182-.09a3.25 3.25 0 0 0 .34-.249l.41-.43a.83.83 0 0 1 .932-.135c.227.068.477.068.704 0c.34-.113.727-.022 1 .226l.34.339c.091.113.205.18.341.248Z");
}

.tigrkbwnp {
  stop-color: var(--svg-color--47364e, #47364E);
  stop-opacity: 0;
}

.tjubatb2f {
  d: path("M28.675 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.398 1.534c.12 0 .206-.12.166-.234l-.564-1.607Z");
}

.ttdjgmu-w {
  d: path("M11.048 5.75c.018.097-.102.145-.167.071c-.453-.513-1.133-1.01-2.023-1.01c-.838 0-1.553.532-2.033 1.063c-.064.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.389-.053Z");
}

.twz1je0id {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.936 5.903v.38c-.003.063-.03.204-.11.264");
}

.tyxtbubbe {
  d: path("M20.93 7.45a.378.378 0 0 0-.364.478h.73a.38.38 0 0 0-.366-.478Z");
}

.u0gzasb1f {
  stop-color: var(--svg-color--231011, #231011);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.udwkkpblr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M22.56 6.728c.182-.032.537-.023.783.168");
}

.ug6cdac2s {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m10.852 5.197l.182.09c.318.159.5.52.432.905l-.25 1.287c-.022.133-.11.223-.242.226h-.008s.023-.384.045-.61c.019-.183-.013-.24-.181-.406a.532.532 0 0 1-.16-.362v-.361a.244.244 0 0 0-.181-.226a6.942 6.942 0 0 0-1.659-.181c-.818 0-1.386.113-1.659.18a.22.22 0 0 0-.181.227v.361a.448.448 0 0 1-.16.362l-.068.067c-.09.068-.136.204-.136.317c.023.248.046.61.046.61l-.021-.001a.268.268 0 0 1-.252-.225l-.25-1.288a.865.865 0 0 1 .454-.881l.182-.09a3.25 3.25 0 0 0 .341-.249l.409-.43a.83.83 0 0 1 .932-.135c.227.068.477.068.704 0c.34-.113.727-.022 1 .226l.34.339a.95.95 0 0 0 .341.248Z");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.v2km0iban {
  cx: 5.514px;
  cy: 16.61px;
  r: 0.766px;
  fill: var(--svg-color--2d151b, #2D151B);
}

.vnco_-oam {
  stop-color: var(--svg-color--55423e, #55423E);
}

.vnhotb5ff {
  cx: 6.8px;
  cy: 7.941px;
  r: 0.421px;
}

.vobictbgt {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w4ytb6bgb {
  d: path("M8.23 7.784c0-.122-.1-.204-.126-.228l-.122.118l.075.153l.173-.043Z");
}

.wi6lfh0ov {
  d: path("M9.369 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-3.574-2.015a.8.8 0 0 0-1.089.308Z");
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wz0fo3usk {
  cx: 7.771px;
  cy: 7.612px;
  rx: 0.165px;
  ry: 0.084px;
}

.wzc2yekot {
  d: path("M22.414 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-3.574-2.015a.8.8 0 0 0-1.09.308Z");
}

.wzs083b9c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M6.891 5.903v.38c-.003.063-.03.204-.11.264");
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xa712tbza {
  d: path("m10.49 5.559l-1.304.435a.444.444 0 0 0 .2.86l1.296-.173l-.192-1.122Z");
}

.xbx983bqi {
  d: path("m7.883 28.192l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
}

.xexis_b4b {
  d: path("M9.735 7.45a.378.378 0 0 1 .364.478h-.73a.38.38 0 0 1 .366-.478Z");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xz5bs-box {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.797 7.335a.593.593 0 0 0-.574.449a.116.116 0 0 0 .114.144h.945c.06 0 .108-.055.096-.115a.593.593 0 0 0-.58-.478Z");
}

.xzduepb8t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M9.515 6.728c.182-.032.537-.023.783.168");
}

.y_jvuobbm {
  fill: var(--svg-color--605071, #605071);
  d: path("m12.504 13.39l-2.828-1.586a.8.8 0 0 1-.307-1.088c.216-.386.36-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.y1wva1b8d {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M10.387 6.79v-.001l-.002-.001l-.002-.002l-.005-.004a.498.498 0 0 0-.065-.045a1.2 1.2 0 0 0-.81-.156a.226.226 0 1 0 .07.446a.748.748 0 0 1 .5.093a.45.45 0 0 1 .023.016a.226.226 0 1 0 .29-.347Z");
}

.y2hx4frna {
  d: path("M7.885 7.45a.378.378 0 0 0-.364.478h.73a.38.38 0 0 0-.366-.478Z");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yo91qy_oj {
  d: path("M22.78 7.45a.378.378 0 0 1 .364.478h-.73a.38.38 0 0 1 .366-.478Z");
}

.yrn5k97fg {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M8.787 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.79 1.605h2.933l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.yrxal2b8w {
  stop-color: var(--svg-color--4c3735, #4C3735);
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z78u0tbjp {
  fill: var(--svg-color--442a2e, #442A2E);
  d: path("m12.729 19.942l-2.703.719l3.604 7.838a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.167-.234l-3.465-9.857Z");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zdbmkmbsu {
  d: path("M8.787 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.79 1.605h2.933l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.znq4zxb8i {
  cx: 19.845px;
  cy: 7.941px;
  r: 0.707px;
}

.zoz3lmrqj {
  stop-color: var(--svg-color--453457, #453457);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
