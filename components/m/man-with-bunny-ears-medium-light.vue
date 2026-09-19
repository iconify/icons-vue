<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#svgIDa)"><path fill="url(#svgIDb)" class="qut0ht_ps"/><path fill="url(#svgIDc)" class="qut0ht_ps"/></g><g filter="url(#svgIDd)"><path fill="url(#svgIDe)" class="a_yyribev"/></g><g filter="url(#svgIDf)"><path class="fo88tnb-w"/></g><path fill="url(#svgIDg)" class="xbx983bqi"/><path fill="url(#svgIDh)" class="xbx983bqi"/><path fill="url(#svgIDi)" class="c65lz4_ey"/><path fill="url(#svgIDj)" class="c65lz4_ey"/><circle fill="url(#svgIDk)" class="dhdllmbnv"/><g filter="url(#svgIDl)"><path clip-rule="evenodd" class="t1ntswj6u"/></g><circle fill="url(#svgIDm)" transform="matrix(-1 0 0 1 12.14 16.739)" class="kr_eiac3t"/><g filter="url(#svgIDn)"><path clip-rule="evenodd" class="n489s2btv"/></g><path fill="url(#svgIDo)" class="hbe-jrbql"/><path fill="url(#svgIDp)" class="hbe-jrbql"/><g filter="url(#svgIDq)"><path class="mx9t77bqt"/></g><path class="y_jvuobbm"/><path fill="url(#svgIDr)" class="qy5kkb6yn"/><g filter="url(#svgIDs)"><path class="yrn5k97fg"/></g><path fill="url(#svgIDt)" class="zdbmkmbsu"/><path fill="url(#svgIDu)" class="zdbmkmbsu"/><path fill="url(#svgIDv)" class="zdbmkmbsu"/><path fill="url(#svgIDw)" class="zdbmkmbsu"/><path fill="url(#svgIDx)" class="zdbmkmbsu"/><path fill="url(#svgIDy)" class="mh1m83zfh"/><g filter="url(#svgIDz)"><path class="l7c3yp58h"/></g><g filter="url(#svgIDA)"><circle fill="url(#svgIDB)" class="t0x-dcc9g"/></g><g filter="url(#svgIDC)"><circle fill="url(#svgIDD)" class="kwagndbcm"/></g><g filter="url(#svgIDE)"><circle fill="url(#svgIDF)" class="tg4omdvxq"/><circle fill="url(#svgIDG)" class="tg4omdvxq"/></g><g filter="url(#svgIDH)"><circle class="t44n40b_f"/><circle fill="url(#svgIDI)" class="v87yutb1f"/><circle fill="url(#svgIDJ)" class="v87yutb1f"/></g><g filter="url(#svgIDK)"><path fill="url(#svgIDL)" class="u55otrb6g"/><path fill="url(#svgIDM)" class="u55otrb6g"/><path fill="url(#svgIDN)" class="u55otrb6g"/><path fill="url(#svgIDO)" class="u55otrb6g"/><path fill="url(#svgIDP)" class="u55otrb6g"/></g><g filter="url(#svgIDQ)"><path class="dnvuxin2k"/><path fill="url(#svgIDR)" class="pxbbyib6z"/><path fill="url(#svgIDS)" class="pxbbyib6z"/><path fill="url(#svgIDT)" class="pxbbyib6z"/><path fill="url(#svgIDU)" class="pxbbyib6z"/><path fill="url(#svgIDV)" class="pxbbyib6z"/></g><path fill="url(#svgIDW)" class="pxbbyib6z"/><path fill="url(#svgIDX)" class="pxbbyib6z"/><g filter="url(#svgIDY)"><path class="cklhy6cnt"/></g><g filter="url(#svgIDZ)"><path class="ivmd-9blv"/><path fill="url(#svgIDaa)" class="qj_3ddd-s"/><path fill="url(#svgIDab)" class="qj_3ddd-s"/><path fill="url(#svgIDac)" class="qj_3ddd-s"/></g><path stroke="url(#svgIDad)" class="f3y5maclf"/><g filter="url(#svgIDae)"><path class="p7aimrv6w"/></g><g filter="url(#svgIDaf)"><path class="byc5086im"/></g><path class="d90k_8b0j"/><path fill="url(#svgIDag)" class="zzb9a2ech"/><path class="xn850bc4v"/><g filter="url(#svgIDah)"><path class="symqq6bhh"/><path fill="url(#svgIDai)" class="kll_m5w7x"/></g><g filter="url(#svgIDaj)"><path fill="url(#svgIDak)" class="w8eug1bek"/></g><path class="d7-yaxb3d"/><path fill="url(#svgIDal)" class="zhw4pu32q"/><path class="aj0-ohbmj"/><g filter="url(#svgIDam)"><path fill="url(#svgIDan)" class="ll5ssutgp"/></g><g filter="url(#svgIDao)" transform="rotate(-27.914 7.75 7.494)"><ellipse class="z_92l_b3i"/><ellipse fill="url(#svgIDap)" class="sw8gkqp7f"/></g><g filter="url(#svgIDaq)"><path stroke="url(#svgIDar)" class="e9g1vqb3t"/></g><g filter="url(#svgIDas)"><path stroke="url(#svgIDat)" class="aq07u_bpz"/></g><g filter="url(#svgIDau)"><path class="q2g11qxsp"/></g><g filter="url(#svgIDav)"><path class="mddk40bcp"/></g><g filter="url(#svgIDaw)"><path fill="url(#svgIDax)" class="ttdjgmu-w"/></g><g filter="url(#svgIDay)"><path fill="url(#svgIDaz)" class="skdh8c8wf"/><path fill="url(#svgIDaA)" class="skdh8c8wf"/></g><g filter="url(#svgIDaB)"><path fill="url(#svgIDaC)" class="b0c6xjbyb"/></g><g filter="url(#svgIDaD)"><path class="bzysl74xl"/></g><path fill="url(#svgIDaE)" class="g1-cakgjb"/><path fill="url(#svgIDaF)" class="g1-cakgjb"/><path fill="url(#svgIDaG)" class="tjubatb2f"/><path fill="url(#svgIDaH)" class="tjubatb2f"/><circle fill="url(#svgIDaI)" class="rdymgqtsv"/><g filter="url(#svgIDaJ)"><path clip-rule="evenodd" class="ddt7btjgy"/></g><circle fill="url(#svgIDaK)" transform="matrix(-1 0 0 1 25.185 16.739)" class="kr_eiac3t"/><g filter="url(#svgIDaL)"><path clip-rule="evenodd" class="t_5jwlbpn"/></g><path fill="url(#svgIDaM)" class="o3ld2rb-v"/><path fill="url(#svgIDaN)" class="o3ld2rb-v"/><g filter="url(#svgIDaO)"><path class="arpzqfbir"/></g><path class="mngobgbzy"/><path fill="url(#svgIDaP)" class="j7sojhblo"/><g filter="url(#svgIDaQ)"><path class="g6a574b3m"/></g><path fill="url(#svgIDaR)" class="nykqrqb8m"/><path fill="url(#svgIDaS)" class="nykqrqb8m"/><path fill="url(#svgIDaT)" class="nykqrqb8m"/><path fill="url(#svgIDaU)" class="nykqrqb8m"/><path fill="url(#svgIDaV)" class="nykqrqb8m"/><path fill="url(#svgIDaW)" class="jaeg0gihu"/><g filter="url(#svgIDaX)"><path class="xeyh-54_r"/></g><g filter="url(#svgIDaY)"><circle fill="url(#svgIDaZ)" class="ejwljo50e"/></g><g filter="url(#svgIDba)"><circle fill="url(#svgIDbb)" class="tb9b8jh3b"/></g><g filter="url(#svgIDbc)"><circle fill="url(#svgIDbd)" class="f0f7je5lp"/><circle fill="url(#svgIDbe)" class="f0f7je5lp"/></g><g filter="url(#svgIDbf)"><circle class="a7i48abqd"/><circle fill="url(#svgIDbg)" class="cqx29zukw"/><circle fill="url(#svgIDbh)" class="cqx29zukw"/></g><g filter="url(#svgIDbi)"><path fill="url(#svgIDbj)" class="iug6k8fid"/><path fill="url(#svgIDbk)" class="iug6k8fid"/><path fill="url(#svgIDbl)" class="iug6k8fid"/><path fill="url(#svgIDbm)" class="iug6k8fid"/><path fill="url(#svgIDbn)" class="iug6k8fid"/></g><g filter="url(#svgIDbo)"><path class="koj5atb9o"/><path fill="url(#svgIDbp)" class="cyht8acqr"/><path fill="url(#svgIDbq)" class="cyht8acqr"/><path fill="url(#svgIDbr)" class="cyht8acqr"/><path fill="url(#svgIDbs)" class="cyht8acqr"/><path fill="url(#svgIDbt)" class="cyht8acqr"/></g><path fill="url(#svgIDbu)" class="cyht8acqr"/><path fill="url(#svgIDbv)" class="cyht8acqr"/><g filter="url(#svgIDbw)"><path class="flws9f18g"/></g><g filter="url(#svgIDbx)"><path class="gabygzbij"/><path fill="url(#svgIDby)" class="fp1_lm8nr"/><path fill="url(#svgIDbz)" class="fp1_lm8nr"/><path fill="url(#svgIDbA)" class="fp1_lm8nr"/></g><path stroke="url(#svgIDbB)" class="kg89mfbox"/><g filter="url(#svgIDbC)"><path class="l1obigbil"/></g><g filter="url(#svgIDbD)"><path class="prz9s83tm"/></g><path class="fudy_ib2a"/><path fill="url(#svgIDbE)" class="fx-2bhbgc"/><path class="bk7-_7buu"/><g filter="url(#svgIDbF)"><path class="ocicbxbwm"/><path fill="url(#svgIDbG)" class="sqg61sugf"/></g><g filter="url(#svgIDbH)"><path fill="url(#svgIDbI)" class="xc6h88bkf"/></g><path class="sftg-8lig"/><path fill="url(#svgIDbJ)" class="bpz3xzbxe"/><path class="vb-du7big"/><g filter="url(#svgIDbK)"><path fill="url(#svgIDbL)" class="d-fha_big"/></g><g filter="url(#svgIDbM)" transform="rotate(-27.914 20.796 7.494)"><ellipse class="v-ohbwmyi"/><ellipse fill="url(#svgIDbN)" class="mhskdxb3h"/></g><g filter="url(#svgIDbO)"><path stroke="url(#svgIDbP)" class="z70afe-9v"/></g><g filter="url(#svgIDbQ)"><path stroke="url(#svgIDbR)" class="py7cvw-1m"/></g><g filter="url(#svgIDbS)"><path class="mguvbdcsc"/></g><g filter="url(#svgIDbT)"><path class="r8c-l-bmo"/></g><g filter="url(#svgIDbU)"><path fill="url(#svgIDbV)" class="ks3ta5xvf"/></g><defs><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 7.541 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -26.585 21.054) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 16.203 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDj" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 15.494 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDm" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="z1jcmx5ye"/><stop offset="1" class="m3ryu8bkj"/></radialGradient><radialGradient id="svgIDt" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 9.51 21.848)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDv" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 11.97 7.278) scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDw" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 3.762 7.838) scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDx" cx="0" cy="0" r="1" gradientTransform="matrix(.45766 -2.68928 1.12443 .19135 8.12 21)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDy" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 8.334 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="mlu7b2msx"/><stop offset="1" class="lfbydbh6e"/></radialGradient><radialGradient id="svgIDB" cx="0" cy="0" r="1" gradientTransform="matrix(.75756 0 0 1.32574 6.04 7.83)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="svgIDG" cx="0" cy="0" r="1" gradientTransform="matrix(.35688 -.25986 .2966 .40733 11.029 7.715)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="svgIDI" cx="0" cy="0" r="1" gradientTransform="matrix(.35453 -.65208 .38167 .2075 10.85 8.184)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="svgIDJ" cx="0" cy="0" r="1" gradientTransform="matrix(.11193 .1108 -.14283 .1443 10.868 7.83)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="svgIDM" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.60624 -4.40082 0 9.014 6.387)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="vpd4dcexx"/><stop offset="1" class="upbi0xbpg"/></radialGradient><radialGradient id="svgIDO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56426 .69447 0 9.824 7.28)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="svgIDP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60043 .74668 0 7.856 7.266)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="svgIDR" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 4.1 4.798) scale(2.42014 4.11567)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="svgIDT" cx="0" cy="0" r="1" gradientTransform="matrix(-.02885 -.80358 .39466 -.01417 7.001 6.338)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="svgIDU" cx="0" cy="0" r="1" gradientTransform="matrix(.37089 -.84891 .69235 .30249 10.636 7.08)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="svgIDV" cx="0" cy="0" r="1" gradientTransform="matrix(.42858 .53179 -.46953 .3784 8.476 4.116)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="svgIDW" cx="0" cy="0" r="1" gradientTransform="matrix(.0783 .3381 -.55584 .12872 9.111 4.116)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="svgIDX" cx="0" cy="0" r="1" gradientTransform="matrix(.3132 .38737 -.86795 .70175 6.935 4.862)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="svgIDag" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38988 -.46133 0 9.752 7.679)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="svgIDai" cx="0" cy="0" r="1" gradientTransform="matrix(-.1001 -.12898 .17758 -.1378 9.653 7.571)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDal" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3899 -.46136 0 7.868 7.679)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="svgIDap" cx="0" cy="0" r="1" gradientTransform="matrix(-.00334 -.21324 .25633 -.00401 7.744 7.63)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDaE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 20.586 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDaF" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -20.062 34.625) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDaG" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 29.249 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDaH" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 28.54 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDaK" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="z1jcmx5ye"/><stop offset="1" class="m3ryu8bkj"/></radialGradient><radialGradient id="svgIDaR" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 22.556 21.848)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 18.493 3.115) scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDaU" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 10.284 10.168) scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDaV" cx="0" cy="0" r="1" gradientTransform="rotate(-80.342 23.02 -2.037) scale(2.72794 1.1406)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDaW" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 21.38 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="mlu7b2msx"/><stop offset="1" class="lfbydbh6e"/></radialGradient><radialGradient id="svgIDaZ" cx="0" cy="0" r="1" gradientTransform="matrix(.75756 0 0 1.32574 19.086 7.83)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="svgIDbe" cx="0" cy="0" r="1" gradientTransform="matrix(.35688 -.25986 .2966 .40733 24.074 7.715)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="svgIDbg" cx="0" cy="0" r="1" gradientTransform="matrix(.35453 -.65208 .38167 .2075 23.896 8.184)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="svgIDbh" cx="0" cy="0" r="1" gradientTransform="matrix(.11193 .1108 -.14283 .1443 23.913 7.83)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="svgIDbk" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.60624 -4.40082 0 22.06 6.387)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="vpd4dcexx"/><stop offset="1" class="upbi0xbpg"/></radialGradient><radialGradient id="svgIDbm" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56426 .69447 0 22.869 7.28)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="svgIDbn" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60043 .74668 0 20.901 7.266)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="svgIDbp" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48355 1.9121 -3.2517 -2.52292 23.45 4.5)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="svgIDbr" cx="0" cy="0" r="1" gradientTransform="matrix(-.02885 -.80358 .39466 -.01417 20.046 6.338)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="svgIDbs" cx="0" cy="0" r="1" gradientTransform="matrix(.37089 -.84891 .69235 .30249 23.68 7.08)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="svgIDbt" cx="0" cy="0" r="1" gradientTransform="matrix(.42858 .53179 -.46953 .3784 21.521 4.116)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="svgIDbu" cx="0" cy="0" r="1" gradientTransform="matrix(.0783 .3381 -.55584 .12872 22.156 4.116)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="svgIDbv" cx="0" cy="0" r="1" gradientTransform="matrix(.3132 .38737 -.86795 .70175 19.98 4.862)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="svgIDbE" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38988 -.46133 0 22.797 7.679)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="svgIDbG" cx="0" cy="0" r="1" gradientTransform="matrix(-.1001 -.12898 .17758 -.1378 22.698 7.571)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDbJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3899 -.46136 0 20.913 7.679)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="svgIDbN" cx="0" cy="0" r="1" gradientTransform="matrix(-.00334 -.21324 .25633 -.00401 20.79 7.629)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="svgIDa" width="3.097" height="9.794" x="5.815" y="20.239" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.647059 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDd" width="6.578" height="10.091" x="10.026" y="19.942" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDf" width="4.976" height="9.579" x="10.996" y="19.362" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".25"/></filter><filter id="svgIDl" width="5.896" height="7.109" x="2.601" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.498039 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.501961 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_717" result="effect2_innerShadow_4002_717"/></filter><filter id="svgIDn" width="5.996" height="7.109" x="9.267" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.533333 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.443137 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_717" result="effect2_innerShadow_4002_717"/></filter><filter id="svgIDq" width="2.703" height="2.68" x="12.199" y="11.784" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".2"/></filter><filter id="svgIDs" width="9.692" height="11.056" x="4.665" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_717" result="effect2_innerShadow_4002_717"/></filter><filter id="svgIDz" width="2.793" height="3.034" x="3.321" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".2"/></filter><filter id="svgIDA" width="1.641" height="1.441" x="6.041" y="7.109" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDC" width="1.859" height="1.859" x="5.832" y="6.9" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".25"/></filter><filter id="svgIDE" width="1.691" height="1.691" x="10.148" y="6.859" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDH" width="1.859" height="1.859" x="9.939" y="6.9" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".25"/></filter><filter id="svgIDK" width="4.478" height="5.342" x="6.584" y="5.401" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDQ" width="5.44" height="3.572" x="6.091" y="4.016" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDY" width="2.26" height="2.657" x="7.578" y="6.905" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".375"/></filter><filter id="svgIDZ" width=".91" height="1.257" x="8.356" y="7.534" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".025"/></filter><filter id="svgIDae" width="1.428" height="1.036" x="9.321" y="6.027" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDaf" width="1.428" height="1.036" x="7.099" y="6.027" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDah" width=".453" height=".414" x="9.378" y="7.288" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".05"/></filter><filter id="svgIDaj" width=".612" height=".622" x="9.684" y="7.264" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".1"/></filter><filter id="svgIDam" width=".653" height=".676" x="7.766" y="7.236" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".1"/></filter><filter id="svgIDao" width=".508" height=".418" x="7.497" y="7.285" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".05"/></filter><filter id="svgIDaq" width="1.148" height=".536" x="9.353" y="6.404" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".05"/></filter><filter id="svgIDas" width="1.182" height=".561" x="7.1" y="6.431" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".05"/></filter><filter id="svgIDau" width="1.73" height="2.911" x="6.683" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_717" result="effect2_innerShadow_4002_717"/></filter><filter id="svgIDav" width="1.73" height="2.911" x="9.394" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_717" result="effect2_innerShadow_4002_717"/></filter><filter id="svgIDaw" width="4.792" height="2.36" x="6.658" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_717" result="effect2_innerShadow_4002_717"/></filter><filter id="svgIDay" width="3.097" height="9.794" x="18.86" y="20.239" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.647059 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDaB" width="6.578" height="10.091" x="23.071" y="19.942" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDaD" width="4.976" height="9.579" x="24.041" y="19.362" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".25"/></filter><filter id="svgIDaJ" width="5.896" height="7.109" x="15.646" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.498039 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.501961 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_717" result="effect2_innerShadow_4002_717"/></filter><filter id="svgIDaL" width="5.996" height="7.109" x="22.312" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.533333 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.443137 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_717" result="effect2_innerShadow_4002_717"/></filter><filter id="svgIDaO" width="2.703" height="2.68" x="25.244" y="11.784" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".2"/></filter><filter id="svgIDaQ" width="9.692" height="11.056" x="17.71" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_717" result="effect2_innerShadow_4002_717"/></filter><filter id="svgIDaX" width="2.793" height="3.034" x="16.367" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".2"/></filter><filter id="svgIDaY" width="1.641" height="1.441" x="19.086" y="7.109" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDba" width="1.859" height="1.859" x="18.877" y="6.9" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".25"/></filter><filter id="svgIDbc" width="1.691" height="1.691" x="23.193" y="6.859" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDbf" width="1.859" height="1.859" x="22.984" y="6.9" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".25"/></filter><filter id="svgIDbi" width="4.478" height="5.342" x="19.629" y="5.401" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDbo" width="5.44" height="3.572" x="19.136" y="4.016" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDbw" width="2.26" height="2.657" x="20.623" y="6.905" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".375"/></filter><filter id="svgIDbx" width=".91" height="1.257" x="21.401" y="7.534" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".025"/></filter><filter id="svgIDbC" width="1.428" height="1.036" x="22.367" y="6.027" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDbD" width="1.428" height="1.036" x="20.144" y="6.027" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/></filter><filter id="svgIDbF" width=".453" height=".414" x="22.423" y="7.288" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".05"/></filter><filter id="svgIDbH" width=".612" height=".622" x="22.729" y="7.264" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".1"/></filter><filter id="svgIDbK" width=".653" height=".676" x="20.811" y="7.236" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".1"/></filter><filter id="svgIDbM" width=".508" height=".418" x="20.543" y="7.285" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".05"/></filter><filter id="svgIDbO" width="1.148" height=".536" x="22.398" y="6.404" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".05"/></filter><filter id="svgIDbQ" width="1.182" height=".561" x="20.145" y="6.431" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_717" stdDeviation=".05"/></filter><filter id="svgIDbS" width="1.73" height="2.911" x="19.728" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_717" result="effect2_innerShadow_4002_717"/></filter><filter id="svgIDbT" width="1.73" height="2.911" x="22.439" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_717" result="effect2_innerShadow_4002_717"/></filter><filter id="svgIDbU" width="4.792" height="2.36" x="19.703" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_717"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_717" result="effect2_innerShadow_4002_717"/></filter><linearGradient id="svgIDb" x1="5.915" x2="7.815" y1="24.13" y2="24.279" gradientUnits="userSpaceOnUse"><stop class="bwozy4alw"/><stop offset="1" class="f_dhcccjh"/></linearGradient><linearGradient id="svgIDc" x1="5.807" x2="6.354" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="nkxbn2utu"/><stop offset="1" class="e1uycobvz"/></linearGradient><linearGradient id="svgIDe" x1="12.128" x2="14.315" y1="24.154" y2="23.31" gradientUnits="userSpaceOnUse"><stop class="zza335bnn"/><stop offset="1" class="ejuz-lbzc"/></linearGradient><linearGradient id="svgIDk" x1="4.972" x2="5.831" y1="16.711" y2="17.376" gradientUnits="userSpaceOnUse"><stop class="yagcj_i0u"/><stop offset="1" class="fvyz5ac7u"/></linearGradient><linearGradient id="svgIDo" x1="5.338" x2="6.26" y1="11.458" y2="13.39" gradientUnits="userSpaceOnUse"><stop class="jum30v1nu"/><stop offset=".527" class="zoz3lmrqj"/></linearGradient><linearGradient id="svgIDp" x1="5.854" x2="5.494" y1="13.177" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="b1pd8upnt"/><stop offset="1" class="n366y7b2s"/></linearGradient><linearGradient id="svgIDr" x1="12.088" x2="12.526" y1="13.176" y2="12.083" gradientUnits="userSpaceOnUse"><stop class="bqhl8ltyr"/><stop offset="1" class="qhg47wyku"/></linearGradient><linearGradient id="svgIDu" x1="5.729" x2="6.401" y1="19.255" y2="19.239" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDD" x1="6.762" x2="6.485" y1="7.95" y2="7.95" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="svgIDF" x1="11.337" x2="10.984" y1="7.358" y2="8.453" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="svgIDL" x1="10.553" x2="7.257" y1="7.997" y2="8.489" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="svgIDN" x1="6.482" x2="7.48" y1="9.161" y2="9.031" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="svgIDS" x1="6.713" x2="7.965" y1="7.714" y2="5.489" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="svgIDaa" x1="8.438" x2="8.843" y1="8.282" y2="8.282" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="svgIDab" x1="9.216" x2="8.773" y1="8.421" y2="8.415" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="svgIDac" x1="8.895" x2="8.895" y1="8.742" y2="8.494" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="svgIDad" x1="8.363" x2="8.551" y1="9.439" y2="9.142" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="svgIDak" x1="10.088" x2="9.952" y1="7.558" y2="7.642" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDan" x1="8.189" x2="8.054" y1="7.558" y2="7.642" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDar" x1="10.094" x2="9.913" y1="6.635" y2="6.264" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="svgIDat" x1="7.804" x2="7.291" y1="6.579" y2="6.364" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="svgIDax" x1="10.697" x2="7.197" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient><linearGradient id="svgIDaz" x1="18.96" x2="20.861" y1="24.13" y2="24.279" gradientUnits="userSpaceOnUse"><stop class="bwozy4alw"/><stop offset="1" class="f_dhcccjh"/></linearGradient><linearGradient id="svgIDaA" x1="18.852" x2="19.399" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="nkxbn2utu"/><stop offset="1" class="e1uycobvz"/></linearGradient><linearGradient id="svgIDaC" x1="25.173" x2="27.361" y1="24.154" y2="23.31" gradientUnits="userSpaceOnUse"><stop class="zza335bnn"/><stop offset="1" class="ejuz-lbzc"/></linearGradient><linearGradient id="svgIDaI" x1="18.017" x2="18.876" y1="16.711" y2="17.376" gradientUnits="userSpaceOnUse"><stop class="yagcj_i0u"/><stop offset="1" class="fvyz5ac7u"/></linearGradient><linearGradient id="svgIDaM" x1="18.383" x2="19.305" y1="11.458" y2="13.39" gradientUnits="userSpaceOnUse"><stop class="jum30v1nu"/><stop offset=".527" class="zoz3lmrqj"/></linearGradient><linearGradient id="svgIDaN" x1="18.899" x2="18.54" y1="13.177" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="b1pd8upnt"/><stop offset="1" class="n366y7b2s"/></linearGradient><linearGradient id="svgIDaP" x1="25.133" x2="25.571" y1="13.176" y2="12.083" gradientUnits="userSpaceOnUse"><stop class="bqhl8ltyr"/><stop offset="1" class="qhg47wyku"/></linearGradient><linearGradient id="svgIDaS" x1="18.774" x2="19.446" y1="19.255" y2="19.239" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDbb" x1="19.806" x2="19.53" y1="7.95" y2="7.95" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="svgIDbd" x1="24.383" x2="24.029" y1="7.358" y2="8.453" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="svgIDbj" x1="23.598" x2="20.302" y1="7.997" y2="8.489" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="svgIDbl" x1="19.527" x2="20.525" y1="9.161" y2="9.031" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="svgIDbq" x1="19.758" x2="21.011" y1="7.714" y2="5.489" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="svgIDby" x1="21.483" x2="21.888" y1="8.282" y2="8.282" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="svgIDbz" x1="22.261" x2="21.819" y1="8.421" y2="8.415" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="svgIDbA" x1="21.94" x2="21.94" y1="8.742" y2="8.494" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="svgIDbB" x1="21.408" x2="21.596" y1="9.439" y2="9.142" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="svgIDbI" x1="23.133" x2="22.997" y1="7.558" y2="7.642" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDbL" x1="21.235" x2="21.099" y1="7.558" y2="7.642" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDbP" x1="23.14" x2="22.958" y1="6.635" y2="6.264" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="svgIDbR" x1="20.85" x2="20.336" y1="6.579" y2="6.364" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="svgIDbV" x1="23.743" x2="20.243" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-with-bunny-ears-medium-light" /></template>
<style>
.a_yyribev {
  d: path("m12.729 19.942l-2.703.719l3.604 7.838a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.167-.234l-3.465-9.857Z");
}

.a3709fbcn {
  stop-color: var(--svg-color--6f597b, #6F597B);
  stop-opacity: 0;
}

.a7i48abqd {
  cx: 23.913px;
  cy: 7.829px;
  r: 0.43px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.aj0-ohbmj {
  fill: var(--svg-color--000, #000);
  d: path("M8.088 7.714a.22.22 0 0 0-.22-.22a.22.22 0 0 0-.197.322h.39a.219.219 0 0 0 .027-.102Z");
}

.aq07u_bpz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M7.275 6.817c.14-.125.45-.257.832-.196");
}

.arpzqfbir {
  stroke: var(--svg-color--ebb89a, #EBB89A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m25.77 12.31l1.083.627c.193.1.578.44.569 1.002");
}

.atfd_nb4o {
  stop-color: var(--svg-color--4c266b, #4C266B);
}

.b0c6xjbyb {
  d: path("m25.774 19.942l-2.703.719l3.604 7.838a2.64 2.64 0 0 0 2.398 1.534c.121 0 .206-.12.166-.234l-3.465-9.857Z");
}

.b1pd8upnt {
  stop-color: var(--svg-color--2c1c3e, #2C1C3E);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bk7-_7buu {
  fill: var(--svg-color--000, #000);
  d: path("M22.577 7.714a.22.22 0 0 1 .22-.22a.22.22 0 0 1 .197.322h-.39a.2.2 0 0 1-.027-.102Z");
}

.boon_rjzq {
  stop-color: var(--svg-color--4c2d62, #4C2D62);
}

.bpz3xzbxe {
  d: path("M20.913 7.329a.385.385 0 0 0-.372.487h.744a.388.388 0 0 0-.373-.487Z");
}

.bqhl8ltyr {
  stop-color: var(--svg-color--2d1b3f, #2D1B3F);
}

.bwozy4alw {
  stop-color: var(--svg-color--cd937c, #CD937C);
}

.byc5086im {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M7.182 6.655h.002l.001-.002l.006-.005a.597.597 0 0 1 .066-.046a1.223 1.223 0 0 1 .826-.16a.23.23 0 1 1-.072.456a.762.762 0 0 0-.509.094a.402.402 0 0 0-.024.016l-.003.003a.23.23 0 0 1-.293-.356Z");
}

.bzysl74xl {
  fill: var(--svg-color--fbc5a7, #FBC5A7);
  d: path("m24.54 20.164l.824-.302l3.153 8.579h-.758l-3.218-8.277Z");
}

.c65lz4_ey {
  d: path("M15.63 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.166-.234l-.563-1.607Z");
}

.cklhy6cnt {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m8.692 7.777l-.354.733c-.044.151.062.302.21.302h.32c.148 0 .254-.153.21-.302l-.215-.733c-.046-.163-.122-.163-.17 0Z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqx29zukw {
  cx: 23.913px;
  cy: 7.829px;
  r: 0.43px;
}

.cyht8acqr {
  d: path("m23.936 5.033l.186.092c.324.161.51.53.44.921l-.255 1.312c-.023.136-.112.227-.247.23h-.008s.023-.39.047-.621c.018-.187-.014-.244-.186-.414a.542.542 0 0 1-.162-.369v-.368a.248.248 0 0 0-.185-.23a7.073 7.073 0 0 0-1.69-.185c-.834 0-1.413.116-1.69.185a.225.225 0 0 0-.186.23v.368a.457.457 0 0 1-.162.369l-.07.069c-.092.069-.139.207-.139.322c.024.253.047.622.047.622l-.021-.001a.273.273 0 0 1-.257-.23l-.255-1.312a.881.881 0 0 1 .463-.898l.186-.092c.115-.069.231-.161.347-.253l.417-.438a.848.848 0 0 1 .95-.138c.23.07.485.07.717 0a1.04 1.04 0 0 1 1.019.23l.347.346a.967.967 0 0 0 .348.253Z");
}

.d-fha_big {
  d: path("M21.265 7.669c0-.125-.102-.208-.129-.233l-.124.12l.076.157l.177-.044Z");
}

.d7-yaxb3d {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.778 7.212a.603.603 0 0 0-.585.457a.118.118 0 0 0 .116.147h.963a.1.1 0 0 0 .098-.117a.605.605 0 0 0-.592-.487Z");
}

.d90k_8b0j {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.842 7.212c.282 0 .52.194.585.457a.118.118 0 0 1-.116.147h-.963a.1.1 0 0 1-.098-.117a.603.603 0 0 1 .592-.487Z");
}

.ddt7btjgy {
  fill: var(--svg-color--d3a082, #D3A082);
  fill-rule: evenodd;
  d: path("M21.44 10.716a.8.8 0 0 1-.307 1.088l-3.527 1.978a.2.2 0 0 0-.034.325l1.9 1.763a.8.8 0 1 1-1.069 1.19l-1.973-1.72c-.93-.82-.855-2.148.348-2.917l3.574-2.015a.8.8 0 0 1 1.089.308Z");
}

.dhdllmbnv {
  cx: 5.514px;
  cy: 16.61px;
  r: 0.766px;
}

.dnvuxin2k {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m10.891 5.033l.186.092a.85.85 0 0 1 .44.921l-.255 1.312c-.023.136-.113.227-.247.23h-.008s.023-.39.046-.621c.02-.187-.013-.244-.185-.414a.542.542 0 0 1-.162-.369v-.368a.248.248 0 0 0-.185-.23A7.075 7.075 0 0 0 8.83 5.4c-.834 0-1.413.116-1.69.185a.225.225 0 0 0-.186.23v.368a.457.457 0 0 1-.162.369l-.07.069c-.092.069-.139.207-.139.322c.024.253.047.622.047.622a.273.273 0 0 1-.278-.23l-.255-1.313a.881.881 0 0 1 .463-.898l.185-.092c.116-.069.232-.161.348-.253l.417-.438a.847.847 0 0 1 .949-.138c.232.07.486.07.718 0a1.041 1.041 0 0 1 1.019.23l.347.346a.967.967 0 0 0 .347.253Z");
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.e1uycobvz {
  stop-color: var(--svg-color--cd937d, #CD937D);
  stop-opacity: 0;
}

.e9g1vqb3t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M9.528 6.593c.185-.033.548-.023.798.172");
}

.ejuz-lbzc {
  stop-color: var(--svg-color--f2bf9d, #F2BF9D);
}

.ejwljo50e {
  cx: 19.807px;
  cy: 7.829px;
  r: 0.721px;
}

.enwi01lgk {
  stop-color: var(--svg-color--522e71, #522E71);
  stop-opacity: 0;
}

.eox5rpbuq {
  stop-color: var(--svg-color--463049, #463049);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f_dhcccjh {
  stop-color: var(--svg-color--f4baa0, #F4BAA0);
}

.f0f7je5lp {
  cx: 23.914px;
  cy: 7.829px;
  r: 0.721px;
}

.f3y5maclf {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M8.236 8.994c.166.087.364.137.575.137c.214 0 .41-.05.575-.137a.116.116 0 0 1 .138.023a.11.11 0 0 1 .012.14m-1.3-.163l1.259.135m-1.259-.135a.116.116 0 0 0-.138.024a.11.11 0 0 0-.012.139m.15-.163l-.108.135m1.408.028l-.041-.028m.041.028l-.041-.028m.041.028a.867.867 0 0 1-.725.387a.867.867 0 0 1-.725-.387m1.409-.028a.817.817 0 0 1-.684.365a.817.817 0 0 1-.683-.365m-.042.028l.042-.028m-.042.028l.042-.028");
}

.f97z0ccja {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
  stop-opacity: 0;
}

.flws9f18g {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m21.738 7.777l-.355.733c-.044.151.062.302.211.302h.318c.15 0 .255-.153.211-.302l-.215-.733c-.046-.163-.122-.163-.17 0Z");
}

.fo88tnb-w {
  fill: var(--svg-color--fbc5a7, #FBC5A7);
  d: path("m11.496 20.164l.823-.302l3.153 8.579h-.758l-3.218-8.277Z");
}

.fp1_lm8nr {
  d: path("m21.691 7.706l-.23.734a.233.233 0 0 0 .226.302h.339c.16 0 .271-.153.225-.302l-.23-.734c-.049-.162-.278-.162-.33 0Z");
}

.ft5dv1b6b {
  fill: none;
}

.fudy_ib2a {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.887 7.212c.282 0 .52.194.585.457a.118.118 0 0 1-.116.147h-.963a.1.1 0 0 1-.098-.117a.603.603 0 0 1 .592-.487Z");
}

.fvyz5ac7u {
  stop-color: var(--svg-color--a26174, #A26174);
}

.fx-2bhbgc {
  d: path("M22.798 7.329a.385.385 0 0 1 .37.487h-.743a.387.387 0 0 1 .373-.487Z");
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

.g6a574b3m {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M21.832 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055L23.22 21h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gabygzbij {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m21.691 7.706l-.23.734a.233.233 0 0 0 .226.302h.339c.16 0 .271-.153.225-.302l-.23-.734c-.049-.162-.278-.162-.33 0Z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.hbe-jrbql {
  d: path("m5.26 13.39l2.828-1.586a.8.8 0 0 0-.781-1.396l-2.86 1.612l.813 1.37Z");
}

.hi3bu5i6r {
  stop-color: var(--svg-color--4c266b, #4C266B);
  stop-opacity: 0;
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i7j8_4zgt {
  stop-color: var(--svg-color--59436a, #59436A);
}

.iug6k8fid {
  d: path("M19.654 7.565a.31.31 0 0 0 .022 0s-.023-.368-.047-.621c0-.115.047-.253.14-.322l.069-.07A.457.457 0 0 0 20 6.184v-.368c0-.115.07-.208.185-.23c.278-.07.857-.185 1.69-.185c.834 0 1.413.115 1.69.184a.248.248 0 0 1 .186.23v.37c0 .137.07.275.162.367c.217.152.203.236.186.415c-.024.23-.047.622-.047.622h.008l-.115 1.708c-.07.764-.67 1.297-1.386 1.297h-1.386c-.739 0-1.316-.533-1.385-1.297l-.134-1.732Z");
}

.ivmd-9blv {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m8.646 7.706l-.23.734a.233.233 0 0 0 .225.302h.34a.234.234 0 0 0 .225-.302l-.23-.734c-.049-.162-.278-.162-.33 0Z");
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j7sojhblo {
  d: path("m25.549 13.39l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.jaeg0gihu {
  d: path("m21.662 11.775l-.865-1.505h2.125l-.824 1.5a.25.25 0 0 1-.436.005Z");
}

.jdxsh3blt {
  stop-color: var(--svg-color--221630, #221630);
}

.jj65vhdzq {
  stop-color: var(--svg-color--635a6d, #635A6D);
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jum30v1nu {
  stop-color: var(--svg-color--42384b, #42384B);
}

.k0aq2sbpu {
  stop-color: var(--svg-color--6f597b, #6F597B);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.kg89mfbox {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M21.281 8.994c.166.087.364.137.575.137c.213 0 .41-.05.575-.137a.116.116 0 0 1 .138.023a.11.11 0 0 1 .012.14m-1.3-.163l1.259.135m-1.259-.135a.116.116 0 0 0-.138.024a.11.11 0 0 0-.012.139m.15-.163l-.108.135m1.408.028l-.041-.028m.041.028l-.041-.028m.041.028a.867.867 0 0 1-.725.387a.867.867 0 0 1-.725-.387m1.409-.028a.817.817 0 0 1-.684.365a.817.817 0 0 1-.683-.365m-.042.028l.042-.028m-.042.028l.042-.028");
}

.kll_m5w7x {
  d: path("M9.724 7.41c.028.037-.03.082-.095.13c-.065.05-.113.084-.14.047c-.028-.037.002-.106.068-.155c.065-.048.14-.058.167-.022Z");
}

.koj5atb9o {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m23.936 5.033l.186.092c.324.161.51.53.44.921l-.255 1.312c-.023.136-.112.227-.247.23h-.008s.023-.39.047-.621c.018-.187-.014-.244-.186-.414a.542.542 0 0 1-.162-.369v-.368a.248.248 0 0 0-.185-.23a7.073 7.073 0 0 0-1.69-.185c-.834 0-1.413.116-1.69.185a.225.225 0 0 0-.186.23v.368a.457.457 0 0 1-.162.369l-.07.069c-.092.069-.139.207-.139.322c.024.253.047.622.047.622l-.021-.001a.273.273 0 0 1-.257-.23l-.255-1.312a.881.881 0 0 1 .463-.898l.186-.092c.115-.069.231-.161.347-.253l.417-.438a.848.848 0 0 1 .95-.138c.23.07.485.07.717 0a1.04 1.04 0 0 1 1.019.23l.347.346a.967.967 0 0 0 .348.253Z");
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

.kwagndbcm {
  cx: 6.762px;
  cy: 7.829px;
  r: 0.43px;
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.l1obigbil {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M23.462 6.655h-.001l-.002-.002l-.005-.005a.577.577 0 0 0-.067-.046a1.223 1.223 0 0 0-.826-.16a.23.23 0 1 0 .072.456a.762.762 0 0 1 .51.094l.023.016l.003.003a.23.23 0 0 0 .293-.356Z");
}

.l7c3yp58h {
  stroke: var(--svg-color--deac96, #DEAC96);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M3.94 13.917c-.088.073-.193.29.094.57a70.98 70.98 0 0 0 1.555 1.415");
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lfbydbh6e {
  stop-color: var(--svg-color--e4ae91, #E4AE91);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll5ssutgp {
  d: path("M8.22 7.669c0-.125-.102-.208-.13-.233l-.124.12l.077.157l.176-.044Z");
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.m3ryu8bkj {
  stop-color: var(--svg-color--a66c74, #A66C74);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mddk40bcp {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M10.771 3.273c-.222.71-.522 1.166-.644 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.211.086.356.403.078 1.29Z");
}

.mguvbdcsc {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M19.981 3.273c.222.71.522 1.166.645 1.305l.633-.242c-.014-.183-.097-.709-.325-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29Z");
}

.mh1m83zfh {
  d: path("m8.617 11.775l-.865-1.505h2.125l-.825 1.5a.25.25 0 0 1-.435.005Z");
}

.mhskdxb3h {
  cx: 20.796px;
  cy: 7.494px;
  rx: 0.168px;
  ry: 0.085px;
}

.mlh1k8r8i {
  stop-color: var(--svg-color--656069, #656069);
}

.mlu7b2msx {
  stop-color: var(--svg-color--a5624e, #A5624E);
}

.mngobgbzy {
  fill: var(--svg-color--605071, #605071);
  d: path("m25.549 13.39l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.mta_69bbu {
  stop-color: var(--svg-color--522e71, #522E71);
}

.mx9t77bqt {
  stroke: var(--svg-color--ebb89a, #EBB89A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m12.724 12.31l1.083.627c.194.1.579.44.57 1.002");
}

.n366y7b2s {
  stop-color: var(--svg-color--2c1c3e, #2C1C3E);
  stop-opacity: 0;
}

.n489s2btv {
  fill: var(--svg-color--dba78f, #DBA78F);
  fill-rule: evenodd;
  d: path("M9.369 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-3.574-2.015a.8.8 0 0 0-1.089.308Z");
}

.nkxbn2utu {
  stop-color: var(--svg-color--cd937d, #CD937D);
}

.nykqrqb8m {
  d: path("M21.832 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055L23.22 21h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.o3ld2rb-v {
  d: path("m18.306 13.39l2.827-1.586a.8.8 0 0 0-.781-1.396l-2.86 1.612l.814 1.37Z");
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.ocicbxbwm {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.77 7.41c.027.037-.03.082-.096.13c-.065.05-.113.084-.14.047c-.028-.037.002-.106.068-.155c.065-.048.14-.058.167-.022Z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.p7aimrv6w {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M10.417 6.655h-.002l-.002-.002l-.005-.005a.577.577 0 0 0-.067-.046a1.223 1.223 0 0 0-.826-.16a.23.23 0 0 0 .073.456a.762.762 0 0 1 .509.094l.023.016l.004.003a.23.23 0 0 0 .293-.356Z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.prz9s83tm {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M20.227 6.655h.002l.002-.002l.005-.005a.577.577 0 0 1 .067-.046a1.222 1.222 0 0 1 .825-.16a.23.23 0 0 1-.072.456a.762.762 0 0 0-.509.094a.401.401 0 0 0-.023.016l-.004.003a.23.23 0 0 1-.293-.356Z");
}

.pxbbyib6z {
  d: path("m10.891 5.033l.186.092a.85.85 0 0 1 .44.921l-.255 1.312c-.023.136-.113.227-.247.23h-.008s.023-.39.046-.621c.02-.187-.013-.244-.185-.414a.542.542 0 0 1-.162-.369v-.368a.248.248 0 0 0-.185-.23A7.075 7.075 0 0 0 8.83 5.4c-.834 0-1.413.116-1.69.185a.225.225 0 0 0-.186.23v.368a.457.457 0 0 1-.162.369l-.07.069c-.092.069-.139.207-.139.322c.024.253.047.622.047.622a.273.273 0 0 1-.278-.23l-.255-1.313a.881.881 0 0 1 .463-.898l.185-.092c.116-.069.232-.161.348-.253l.417-.438a.847.847 0 0 1 .949-.138c.232.07.486.07.718 0a1.041 1.041 0 0 1 1.019.23l.347.346a.967.967 0 0 0 .347.253Z");
}

.py7cvw-1m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M20.32 6.817c.141-.125.45-.257.832-.196");
}

.q2g11qxsp {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M6.936 3.273c.222.71.522 1.166.645 1.305l.633-.242c-.013-.183-.096-.709-.325-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29Z");
}

.qgz62l2ld {
  stop-color: var(--svg-color--443553, #443553);
}

.qhg47wyku {
  stop-color: var(--svg-color--2d1b3f, #2D1B3F);
  stop-opacity: 0;
}

.qj_3ddd-s {
  d: path("m8.646 7.706l-.23.734a.233.233 0 0 0 .225.302h.34a.234.234 0 0 0 .225-.302l-.23-.734c-.049-.162-.278-.162-.33 0Z");
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

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r8c-l-bmo {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M23.817 3.273c-.222.71-.523 1.166-.645 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.286-.808.579-1.09.875-.996c.212.086.356.403.079 1.29Z");
}

.rdymgqtsv {
  cx: 18.559px;
  cy: 16.61px;
  r: 0.766px;
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sftg-8lig {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.823 7.212a.603.603 0 0 0-.584.457a.118.118 0 0 0 .115.147h.963a.1.1 0 0 0 .098-.117a.605.605 0 0 0-.592-.487Z");
}

.skdh8c8wf {
  d: path("m18.96 20.239l2.997.27l-1.063 7.94a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122V20.24Z");
}

.sqg61sugf {
  d: path("M22.77 7.41c.027.037-.03.082-.096.13c-.065.05-.113.084-.14.047c-.028-.037.002-.106.068-.155c.065-.048.14-.058.167-.022Z");
}

.sw8gkqp7f {
  cx: 7.751px;
  cy: 7.494px;
  rx: 0.168px;
  ry: 0.085px;
}

.symqq6bhh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M9.724 7.41c.028.037-.03.082-.095.13c-.065.05-.113.084-.14.047c-.028-.037.002-.106.068-.155c.065-.048.14-.058.167-.022Z");
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t_5jwlbpn {
  fill: var(--svg-color--dba78f, #DBA78F);
  fill-rule: evenodd;
  d: path("M22.414 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-3.574-2.015a.8.8 0 0 0-1.09.308Z");
}

.t0x-dcc9g {
  cx: 6.761px;
  cy: 7.829px;
  r: 0.721px;
}

.t1ntswj6u {
  fill: var(--svg-color--d3a082, #D3A082);
  fill-rule: evenodd;
  d: path("M8.395 10.716a.8.8 0 0 1-.307 1.088L4.56 13.782a.2.2 0 0 0-.035.325l1.9 1.763a.8.8 0 1 1-1.068 1.19l-1.973-1.72c-.93-.82-.855-2.148.347-2.917l3.575-2.015a.8.8 0 0 1 1.088.308Z");
}

.t44n40b_f {
  cx: 10.868px;
  cy: 7.829px;
  r: 0.43px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.tb9b8jh3b {
  cx: 19.806px;
  cy: 7.829px;
  r: 0.43px;
}

.tg4omdvxq {
  cx: 10.868px;
  cy: 7.829px;
  r: 0.721px;
}

.tigrkbwnp {
  stop-color: var(--svg-color--47364e, #47364E);
  stop-opacity: 0;
}

.tjubatb2f {
  d: path("M28.675 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.398 1.534c.12 0 .206-.12.166-.234l-.564-1.607Z");
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.ttdjgmu-w {
  d: path("M11.048 5.75c.018.097-.102.145-.167.071c-.453-.513-1.133-1.01-2.023-1.01c-.838 0-1.553.532-2.033 1.063c-.064.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.389-.053Z");
}

.u55otrb6g {
  d: path("M6.61 7.565h.02s-.022-.368-.046-.621c0-.115.047-.253.14-.322l.069-.07a.457.457 0 0 0 .162-.368v-.368c0-.115.07-.208.185-.23c.278-.07.857-.185 1.69-.185c.834 0 1.413.115 1.69.184a.248.248 0 0 1 .186.23v.37c0 .137.07.275.162.367c.217.152.204.236.185.415c-.023.23-.046.622-.046.622a.29.29 0 0 0 .008 0L10.9 9.296c-.069.764-.67 1.297-1.386 1.297H8.128c-.739 0-1.316-.533-1.385-1.297L6.61 7.565Z");
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.upbi0xbpg {
  stop-color: var(--svg-color--9f6e75, #9F6E75);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v-ohbwmyi {
  cx: 20.796px;
  cy: 7.494px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.168px;
  ry: 0.085px;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v87yutb1f {
  cx: 10.868px;
  cy: 7.829px;
  r: 0.43px;
}

.vb-du7big {
  fill: var(--svg-color--000, #000);
  d: path("M21.133 7.714a.22.22 0 0 0-.22-.22a.22.22 0 0 0-.197.322h.39a.22.22 0 0 0 .027-.102Z");
}

.vobictbgt {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
}

.vpd4dcexx {
  stop-color: var(--svg-color--c88d87, #C88D87);
  stop-opacity: 0;
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w8eug1bek {
  d: path("M10.096 7.663a.362.362 0 0 0-.1-.2l-.112.124l.05.098l.162-.022Z");
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.xbx983bqi {
  d: path("m7.883 28.192l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
}

.xc6h88bkf {
  d: path("M23.14 7.663a.363.363 0 0 0-.1-.2l-.111.124l.05.098l.162-.022Z");
}

.xeyh-54_r {
  stroke: var(--svg-color--deac96, #DEAC96);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.986 13.917c-.089.073-.194.29.093.57a70.77 70.77 0 0 0 1.555 1.415");
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xn850bc4v {
  fill: var(--svg-color--000, #000);
  d: path("M9.532 7.714a.22.22 0 0 1 .22-.22a.22.22 0 0 1 .196.322h-.39a.2.2 0 0 1-.026-.102Z");
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y_jvuobbm {
  fill: var(--svg-color--605071, #605071);
  d: path("m12.504 13.39l-2.828-1.586a.8.8 0 0 1-.307-1.088c.216-.386.36-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.yagcj_i0u {
  stop-color: var(--svg-color--c88973, #C88973);
}

.yrn5k97fg {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M8.787 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.79 1.605h2.933l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.z_92l_b3i {
  cx: 7.751px;
  cy: 7.494px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.168px;
  ry: 0.085px;
}

.z1jcmx5ye {
  stop-color: var(--svg-color--d4a691, #D4A691);
}

.z70afe-9v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M22.573 6.593c.186-.033.548-.023.799.172");
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.zdbmkmbsu {
  d: path("M8.787 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.79 1.605h2.933l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zhw4pu32q {
  d: path("M7.867 7.329a.385.385 0 0 0-.371.487h.744a.388.388 0 0 0-.373-.487Z");
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zoz3lmrqj {
  stop-color: var(--svg-color--453457, #453457);
}

.zza335bnn {
  stop-color: var(--svg-color--d29688, #D29688);
}

.zzb9a2ech {
  d: path("M9.753 7.329a.385.385 0 0 1 .37.487H9.38a.387.387 0 0 1 .373-.487Z");
}

</style>
