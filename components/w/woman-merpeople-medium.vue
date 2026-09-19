<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iID5Xce)"><path fill="url(#is7igMb)" class="qxbkqy2mr"/><path fill="url(#iRCWc8c)" class="qxbkqy2mr"/><path fill="url(#igD31Fd)" class="qxbkqy2mr"/></g><g filter="url(#ijHydib)"><path class="l85u8ibfx"/></g><path fill="url(#imdrOid)" class="d804zky3u"/><g filter="url(#i6XTmfY)"><path fill="url(#iOxYU2b)" class="m4pcayl4x"/></g><path fill="url(#iAJhgdb)" class="lby3v6ati"/><path fill="url(#isl3lXd)" class="lby3v6ati"/><g filter="url(#iMuyefc)"><path fill="url(#ikXGgPe)" class="qdgeq05dx"/><path fill="url(#iBug4xd)" class="qdgeq05dx"/></g><g filter="url(#i3rG0Oc)"><path fill="url(#ifUuRab)" class="rvgjtg4fi"/><path fill="url(#iWpOkBe)" class="rvgjtg4fi"/><path fill="url(#idJDvJb)" class="rvgjtg4fi"/><path fill="url(#iC8J0qb)" class="rvgjtg4fi"/><path fill="url(#iEKgeUc)" class="rvgjtg4fi"/><path fill="url(#i48W4Vc)" class="rvgjtg4fi"/><path fill="url(#iHnvcFW)" class="rvgjtg4fi"/><path fill="url(#ivU7XFG)" class="rvgjtg4fi"/></g><path fill="url(#ivBeQCb)" class="rvgjtg4fi"/><path fill="url(#iWVHORd)" class="rvgjtg4fi"/><path fill="url(#iwomZQe)" class="rvgjtg4fi"/><path fill="url(#isVmEiw)" class="rvgjtg4fi"/><g filter="url(#ihQS4xc)"><path stroke="url(#iI9sDUb)" class="yf02b6ygm"/></g><g filter="url(#inUjmFb)"><path stroke="url(#iUUCLJd)" class="mzcd8ybsc"/></g><g filter="url(#i8Q3kRd)"><path stroke="url(#iDbcAtn)" class="ubz5oeoiz"/></g><g filter="url(#ipCNNQd)"><path class="mp5yrl3-i"/></g><g filter="url(#iASRDoe)"><path class="eywjsqb5l"/><path fill="url(#iO96kgc)" class="wliqnbp1k"/><path fill="url(#iPbL8Xb)" class="wliqnbp1k"/><path fill="url(#iyPwIbP)" class="wliqnbp1k"/></g><g filter="url(#imOI5Ab)"><path fill="url(#i9Z7uCc)" class="gjbve0bnv"/></g><path fill="url(#iocWmsc)" class="o87uryobz"/><g filter="url(#i5Oa0ze)"><path fill="url(#ijXzhjX)" class="ozq3jw9ll"/></g><g filter="url(#i1gee6c)"><path fill="url(#id0knUp)" class="pdupf-5td"/></g><g filter="url(#ixOJDVd)"><path fill="url(#i1U0JBc)" class="f_g0dqsvm"/></g><path fill="url(#iHJwOKc)" class="f_g0dqsvm"/><path fill="url(#iLI0Smd)" class="f_g0dqsvm"/><path fill="url(#igaULfb)" class="f_g0dqsvm"/><path fill="url(#igK9Wub)" class="f_g0dqsvm"/><path fill="url(#i8LjkDb)" class="f_g0dqsvm"/><path fill="url(#iULjESd)" class="f_g0dqsvm"/><g filter="url(#ifNxCcc)"><path class="jri39dp3m"/></g><path class="cfq0k4bto"/><path fill="url(#idGqx3d)" class="vckbn7bgk"/><path fill="url(#iDbZ59d)" class="vckbn7bgk"/><path fill="url(#iTnC2rb)" class="vckbn7bgk"/><path fill="url(#iVIpJAc)" class="vckbn7bgk"/><path fill="url(#i1k72qc)" class="vckbn7bgk"/><g filter="url(#iAwM83d)"><path stroke="url(#iahWGmc)" class="kzknyvg9e"/></g><path class="je2v5tfor"/><g filter="url(#iryhGgc)"><path class="oc32bubbt"/></g><g filter="url(#inVLqJc)"><path class="v3hxs-buk"/></g><g filter="url(#iZjGZnd)"><path fill="url(#i3gf1De)" class="hwk_mxbwm"/></g><g filter="url(#iAw41qe)"><path fill="url(#iKFTfdd)" clip-rule="evenodd" class="nu6p8xpxk"/></g><path class="ivaw61bob"/><path fill="url(#i5YbaKe)" class="akquh7bgt"/><path class="ro7svqvjx"/><g filter="url(#iZfLFFd)"><path class="nl_8d1b0i"/><path fill="url(#i2LqhIf)" class="rggh3hbuf"/></g><g filter="url(#ifCbZux)"><path fill="url(#idDVUGc)" class="yo-rx8c0q"/></g><path class="sdf9tobyx"/><path fill="url(#imJspBd)" class="o0eqsac9n"/><path class="eiflvuzgd"/><g filter="url(#ik5qD0C)"><path fill="url(#i1cZLfc)" class="x2e_pmc0g"/></g><g filter="url(#iYVW68Z)"><ellipse transform="rotate(-27.914 15.96 6.811)" class="t2ck-pbsh"/><ellipse fill="url(#iNxWnMx)" transform="rotate(-27.914 15.96 6.811)" class="utkhftb9q"/></g><g filter="url(#iTMwjld)"><path class="z5tt1acjt"/></g><g filter="url(#iGj8P3c)"><path class="f-9ripbsd"/></g><g filter="url(#ilijXxc)"><path fill="url(#i52D6Wc)" class="q2m7q-bcq"/></g><g filter="url(#iLfV56b)"><path fill="url(#ig4Jnib)" class="f32er0yca"/></g><g filter="url(#iKwXwNe)"><path fill="url(#iNCOsHX)" class="f32er0yca"/><path fill="url(#i6Ijz2c)" class="f32er0yca"/><path fill="url(#iZIVcbe)" class="f32er0yca"/><path fill="url(#inbtQed)" class="f32er0yca"/><path fill="url(#iIywqEd)" class="f32er0yca"/></g><g filter="url(#ixteNDc)"><path class="iorvdubip"/><path fill="url(#ibrXHpJ)" class="inz52_phe"/><path fill="url(#iII9RCc)" class="inz52_phe"/><path fill="url(#ihEBcfc)" class="inz52_phe"/></g><g filter="url(#i5BDcmd)"><path fill="url(#inqBmcd)" class="p6977lbwx"/></g><g filter="url(#ifOLD2b)"><path fill="url(#iZtPjwd)" class="idot92bag"/></g><g filter="url(#ihNqHrc)"><path stroke="url(#itr3efe)" class="vpkiteigl"/></g><defs><radialGradient id="is7igMb" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 9.371 7.073)scale(11.0359 20.9934)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="x0zlvzb_b"/><stop offset="1" class="jhou7tlnj"/></radialGradient><radialGradient id="iRCWc8c" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -6.09376 6.96548 4.14356 19.135 10.515)" gradientUnits="userSpaceOnUse"><stop class="i2h38kz1u"/><stop offset="1" class="ftmryjblq"/></radialGradient><radialGradient id="igD31Fd" cx="0" cy="0" r="1" gradientTransform="rotate(114.353 5.655 7.641)scale(3.2587 3.56285)" gradientUnits="userSpaceOnUse"><stop class="x7utjgb1r"/><stop offset="1" class="ke5ghyvxy"/><stop offset="1" class="ke5ghyvxy"/></radialGradient><radialGradient id="imdrOid" cx="0" cy="0" r="1" gradientTransform="rotate(-17.313 87.674 -23.135)scale(13.0953 16.0195)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="iOxYU2b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 22.702 20.572)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="iAJhgdb" cx="0" cy="0" r="1" gradientTransform="matrix(.67968 -.9375 .55678 .40367 6.762 16.9)" gradientUnits="userSpaceOnUse"><stop class="x6pc4sbye"/><stop offset="1" class="vs599jbgl"/></radialGradient><radialGradient id="ikXGgPe" cx="0" cy="0" r="1" gradientTransform="matrix(-.95313 .90937 -.4986 -.5226 25.737 7.283)" gradientUnits="userSpaceOnUse"><stop class="jsw980phx"/><stop offset=".611" class="yh8fa0s0y"/></radialGradient><radialGradient id="iBug4xd" cx="0" cy="0" r="1" gradientTransform="matrix(-.04224 -.75 .57465 -.03236 25.182 8.712)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="jmv4rsfcq"/><stop offset="1" class="ql9fbhbmb"/></radialGradient><radialGradient id="ifUuRab" cx="0" cy="0" r="1" gradientTransform="rotate(159 8.58 8.058)scale(4.71973 6.48913)" gradientUnits="userSpaceOnUse"><stop class="ipbb10b0b"/><stop offset="1" class="a5wwfyvbc"/></radialGradient><radialGradient id="idJDvJb" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 0 0 4.11135 14.48 17.197)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="um-4-ifpg"/><stop offset="1" class="u9ihbxbhg"/></radialGradient><radialGradient id="iC8J0qb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.509 15.769 2.034)scale(5.76427 2.15458)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="ck9qz_2lp"/><stop offset="1" class="l97w7x76c"/></radialGradient><radialGradient id="iEKgeUc" cx="0" cy="0" r="1" gradientTransform="matrix(1.14062 3.15625 -1.12664 .40715 23.76 10.838)" gradientUnits="userSpaceOnUse"><stop class="qg84xbb9n"/><stop offset="1" class="e_l7oqrnp"/></radialGradient><radialGradient id="i48W4Vc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29421 -1.39953 1.4063 -1.30048 16 13.76)" gradientUnits="userSpaceOnUse"><stop class="thpdt1biy"/><stop offset="1" class="njswj9qiy"/></radialGradient><radialGradient id="iHnvcFW" cx="0" cy="0" r="1" gradientTransform="matrix(-.49998 -1.89063 3.41696 -.90363 24.964 15.493)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="xcso8mb_w"/><stop offset="1" class="i_am4rb0b"/></radialGradient><radialGradient id="ivU7XFG" cx="0" cy="0" r="1" gradientTransform="rotate(155.579 7.477 6.669)scale(3.17465 2.03239)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="v-5fxgbwn"/><stop offset="1" class="ve6kq2bvl"/></radialGradient><radialGradient id="ivBeQCb" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 0 0 4.60938 14.12 16.9)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="tf07upwmc"/><stop offset="1" class="vdwscwwnn"/></radialGradient><radialGradient id="iwomZQe" cx="0" cy="0" r="1" gradientTransform="rotate(133.468 3.63 10.375)scale(2.48567 1.45387)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="b49-bdbcc"/><stop offset="1" class="rqv3tobxx"/></radialGradient><radialGradient id="isVmEiw" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78126 1.58593 -.17358 -.19496 13.002 15.384)" gradientUnits="userSpaceOnUse"><stop offset=".144" class="qxcnoh65g"/><stop offset="1" class="c4_34bhlh"/></radialGradient><radialGradient id="iO96kgc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17187 -1.23438 .5687 -.5399 16.852 14.384)" gradientUnits="userSpaceOnUse"><stop class="rd_1vj1uu"/><stop offset="1" class="w4wjacb9v"/></radialGradient><radialGradient id="iPbL8Xb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.26562 -.57617 0 17.413 13.306)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="dsu9eguof"/><stop offset="1" class="dogwq2blg"/></radialGradient><radialGradient id="iyPwIbP" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4707 1.41406 -.31529 -.32792 21.136 13.15)" gradientUnits="userSpaceOnUse"><stop class="gwqfskb8v"/><stop offset="1" class="n7-hw2b3h"/></radialGradient><radialGradient id="iocWmsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.66406 .65625 -.45034 -.4557 20.971 6.806)" gradientUnits="userSpaceOnUse"><stop class="ha79ukbar"/><stop offset="1" class="tyid2cb9a"/></radialGradient><radialGradient id="ijXzhjX" cx="0" cy="0" r="1" gradientTransform="rotate(90 6.521 13.742)scale(.63475)" gradientUnits="userSpaceOnUse"><stop class="t1wmkubur"/><stop offset="1" class="hy3u76v1i"/></radialGradient><radialGradient id="id0knUp" cx="0" cy="0" r="1" gradientTransform="rotate(106.949 4.602 8.875)scale(.85756)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="yem0kqbom"/><stop offset="1" class="icbl5ibjw"/></radialGradient><radialGradient id="i1U0JBc" cx="0" cy="0" r="1" gradientTransform="rotate(150.368 8.29 6.224)scale(3.48734 5.97003)" gradientUnits="userSpaceOnUse"><stop class="x0z57ccyo"/><stop offset="1" class="nj83g3bmu"/></radialGradient><radialGradient id="iHJwOKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.48957 -5.92174 0 17.41 6.259)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="jtmo9zbne"/><stop offset="1" class="x5vi3qbzz"/></radialGradient><radialGradient id="iLI0Smd" cx="0" cy="0" r="1" gradientTransform="rotate(146.659 9.247 5.583)scale(1.42145 2.26202)" gradientUnits="userSpaceOnUse"><stop class="y77jxgbee"/><stop offset="1" class="juawl1gfq"/></radialGradient><radialGradient id="igaULfb" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 .58426 -2.2344 2.03169 15.542 4.478)" gradientUnits="userSpaceOnUse"><stop class="u27eaq1ke"/><stop offset="1" class="zwlqziglb"/></radialGradient><radialGradient id="igK9Wub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72875 1.74927 -1.1218 -1.10864 19.052 5.182)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="nxpnkb1eb"/><stop offset="1" class="djrdya1sy"/></radialGradient><radialGradient id="i8LjkDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.69922 1.10156 0 18.776 6.562)" gradientUnits="userSpaceOnUse"><stop class="j055wdbud"/><stop offset="1" class="jyqj6pdqa"/></radialGradient><radialGradient id="iULjESd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.90625 .92188 0 16.01 6.515)" gradientUnits="userSpaceOnUse"><stop class="vmpvo2iof"/><stop offset="1" class="k39_6wapl"/></radialGradient><radialGradient id="iDbZ59d" cx="0" cy="0" r="1" gradientTransform="matrix(-.47656 0 0 -.14893 17.659 8.11)" gradientUnits="userSpaceOnUse"><stop class="k5p37d2fo"/><stop offset="1" class="yiekaulvh"/></radialGradient><radialGradient id="iTnC2rb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.39263 1.04529 0 17.41 8.425)" gradientUnits="userSpaceOnUse"><stop class="iwj441a3a"/><stop offset="1" class="nxis-vb-u"/></radialGradient><radialGradient id="i5YbaKe" cx="0" cy="0" r="1" gradientTransform="rotate(124.592 7.723 8.39)scale(.55383 .87854)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="chm_zob8h"/><stop offset="1" class="w_bi9zfnz"/></radialGradient><radialGradient id="i2LqhIf" cx="0" cy="0" r="1" gradientTransform="matrix(-.13647 -.17586 .24212 -.18789 18.564 6.918)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imJspBd" cx="0" cy="0" r="1" gradientTransform="rotate(124.592 6.433 7.713)scale(.55383 .87855)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="chm_zob8h"/><stop offset="1" class="w_bi9zfnz"/></radialGradient><radialGradient id="iNxWnMx" cx="0" cy="0" r="1" gradientTransform="matrix(-.00455 -.29073 .34947 -.00547 15.95 6.997)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i52D6Wc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.98437 1.60938 -.62216 -.76713 15.589 4.087)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="h0xizc-pq"/><stop offset=".77" class="lnzo7tbfa"/></radialGradient><radialGradient id="ig4Jnib" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46875 .08792 -.04263 -1.68195 19.76 4.138)" gradientUnits="userSpaceOnUse"><stop class="g2qbx_b_v"/><stop offset="1" class="cn6gyybop"/></radialGradient><radialGradient id="iNCOsHX" cx="0" cy="0" r="1" gradientTransform="rotate(-169.129 10.228 1.467)scale(2.40249 .68451)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="n4ybtv3-a"/><stop offset="1" class="k1mq2-9zz"/></radialGradient><radialGradient id="i6Ijz2c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.01562 .32813 -.2781 -2.55587 18.354 3.687)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="kd1pu_b5e"/><stop offset="1" class="dacedmb2p"/></radialGradient><radialGradient id="iZIVcbe" cx="0" cy="0" r="1" gradientTransform="matrix(.42188 -2.92187 6.42687 .92795 16.495 5.337)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="bh0i_3bdf"/><stop offset=".942" class="bd2iczr0j"/></radialGradient><radialGradient id="inbtQed" cx="0" cy="0" r="1" gradientTransform="rotate(43.877 3.336 26.975)scale(.84538 .59687)" gradientUnits="userSpaceOnUse"><stop class="mbrovup5s"/><stop offset="1" class="xpjl1tbpw"/></radialGradient><radialGradient id="iIywqEd" cx="0" cy="0" r="1" gradientTransform="matrix(-.64844 -.85938 .48227 -.3639 20.206 4.777)" gradientUnits="userSpaceOnUse"><stop offset=".15" class="rfs9njbxq"/><stop offset="1" class="ymbtox6zc"/></radialGradient><radialGradient id="ibrXHpJ" cx="0" cy="0" r="1" gradientTransform="matrix(.20313 1.2422 -.5655 .09247 21.027 3.806)" gradientUnits="userSpaceOnUse"><stop class="mk_tesa_t"/><stop offset="1" class="hj78b9cjo"/></radialGradient><radialGradient id="iII9RCc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11657 .3125 -.09737 -.3479 22.346 4.681)" gradientUnits="userSpaceOnUse"><stop class="o5bua8boy"/><stop offset="1" class="rz_b8bbbi"/></radialGradient><radialGradient id="ihEBcfc" cx="0" cy="0" r="1" gradientTransform="matrix(-.59375 -1.38766 .70345 -.301 21.932 6.494)" gradientUnits="userSpaceOnUse"><stop class="o0h7y_boi"/><stop offset="1" class="s9ajizb_e"/></radialGradient><filter id="iID5Xce" width="14.674" height="15.298" x="7.851" y="1.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.184314 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1297"/></filter><filter id="ijHydib" width="16.97" height="13.626" x="7.639" y="16.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1297"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1297" result="effect2_innerShadow_4002_1297"/></filter><filter id="i6XTmfY" width="8.803" height="12.453" x="15.083" y="15.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".5"/></filter><filter id="iMuyefc" width="1.41" height="1.949" x="24.485" y="7.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.352941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1297"/></filter><filter id="i3rG0Oc" width="20.634" height="10.708" x="5.683" y="7.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.352941 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1297"/></filter><filter id="ihQS4xc" width="11.112" height="3.615" x="10.829" y="25.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".2"/></filter><filter id="inUjmFb" width="3.297" height="3.17" x="8.245" y="23.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".2"/></filter><filter id="i8Q3kRd" width="3.085" height="3.032" x="11.506" y="23.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".2"/></filter><filter id="ipCNNQd" width="6.547" height="2.797" x="14.14" y="13.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".125"/></filter><filter id="iASRDoe" width="7.845" height="3.428" x="13.691" y="12.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.243137 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1297"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.32549 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1297" result="effect2_innerShadow_4002_1297"/></filter><filter id="imOI5Ab" width="2.002" height="1.902" x="13.691" y="6.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.462745 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1297"/></filter><filter id="i5Oa0ze" width="1.669" height="1.67" x="19.428" y="6.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".1"/></filter><filter id="i1gee6c" width="1.47" height="1.47" x="13.918" y="6.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".05"/></filter><filter id="ixOJDVd" width="6.422" height="6.428" x="14.399" y="4.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.466667 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1297"/></filter><filter id="ifNxCcc" width="1.609" height="2.085" x="16.51" y="6.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".125"/></filter><filter id="iAwM83d" width="2.152" height=".865" x="16.335" y="8.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".025"/></filter><filter id="iryhGgc" width="1.855" height=".76" x="17.885" y="6.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1297"/></filter><filter id="inVLqJc" width="1.855" height=".76" x="15.08" y="6.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1297"/></filter><filter id="iZjGZnd" width="1.531" height=".726" x="15.16" y="5.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.160784 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1297"/></filter><filter id="iAw41qe" width="1.531" height=".727" x="18.361" y="5.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.160784 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1297"/></filter><filter id="iZfLFFd" width=".545" height=".492" x="18.225" y="6.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".05"/></filter><filter id="ifCbZux" width=".689" height=".702" x="18.68" y="6.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".1"/></filter><filter id="ik5qD0C" width=".745" height=".777" x="16.055" y="6.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".1"/></filter><filter id="iYVW68Z" width=".62" height=".497" x="15.65" y="6.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".05"/></filter><filter id="iTMwjld" width="1.231" height=".473" x="18.431" y="5.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".05"/></filter><filter id="iGj8P3c" width="1.231" height=".473" x="15.21" y="5.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".05"/></filter><filter id="ilijXxc" width="2.163" height="2.504" x="13.885" y="3.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".05"/></filter><filter id="iLfV56b" width="5.15" height="3.645" x="15.32" y="2.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.14902 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1297"/><feGaussianBlur result="effect2_foregroundBlur_4002_1297" stdDeviation=".05"/></filter><filter id="iKwXwNe" width="5.15" height="3.495" x="15.32" y="2.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".05"/></filter><filter id="ixteNDc" width="3.17" height="3.061" x="19.276" y="3.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.529412 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1297"/></filter><filter id="i5BDcmd" width="2.055" height="6.641" x="24.354" y="7.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".25"/></filter><filter id="ifOLD2b" width="4.719" height="3.595" x="19.998" y="10.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".25"/></filter><filter id="ihNqHrc" width="1.175" height="2.326" x="23.635" y="7.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1297" stdDeviation=".125"/></filter><linearGradient id="isl3lXd" x1="6.713" x2="7.026" y1="16.853" y2="16.853" gradientUnits="userSpaceOnUse"><stop class="d0wb5fb-u"/><stop offset="1" class="bxcombcbd"/></linearGradient><linearGradient id="iWpOkBe" x1="8.135" x2="14.729" y1="16.572" y2="12.165" gradientUnits="userSpaceOnUse"><stop class="y1iz3jbsf"/><stop offset="1" class="gs2wj8m6y"/></linearGradient><linearGradient id="iWVHORd" x1="17.354" x2="17.354" y1="18.04" y2="16.384" gradientUnits="userSpaceOnUse"><stop offset=".113" class="aqs3hv35q"/><stop offset="1" class="wh5184nvn"/></linearGradient><linearGradient id="iI9sDUb" x1="11.768" x2="20.875" y1="26.97" y2="28.813" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iUUCLJd" x1="10.518" x2="8.203" y1="25.763" y2="25.39" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iDbcAtn" x1="14.012" x2="13.482" y1="24.1" y2="26.21" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="i9Z7uCc" x1="14.05" x2="14.641" y1="6.947" y2="8.172" gradientUnits="userSpaceOnUse"><stop class="vypt9ybrl"/><stop offset="1" class="u1lo-0nty"/></linearGradient><linearGradient id="idGqx3d" x1="17.838" x2="17.37" y1="7.767" y2="7.79" gradientUnits="userSpaceOnUse"><stop class="qy_lu4bmh"/><stop offset="1" class="no2vo2b5r"/></linearGradient><linearGradient id="iVIpJAc" x1="17.452" x2="17.452" y1="8.455" y2="8.275" gradientUnits="userSpaceOnUse"><stop class="l_2gubcru"/><stop offset="1" class="cic6athgq"/></linearGradient><linearGradient id="i1k72qc" x1="17.41" x2="17.41" y1="6.84" y2="7.775" gradientUnits="userSpaceOnUse"><stop class="r0kaalb9z"/><stop offset=".824" class="aau54zb2u"/></linearGradient><linearGradient id="iahWGmc" x1="16.98" x2="17.247" y1="9.352" y2="8.837" gradientUnits="userSpaceOnUse"><stop class="rp4tm-b1w"/><stop offset="1" class="wj_ij8b3z"/></linearGradient><linearGradient id="i3gf1De" x1="16.387" x2="15.16" y1="6.04" y2="6.04" gradientUnits="userSpaceOnUse"><stop class="t_opl6b5d"/><stop offset="1" class="r1b4l6vhf"/></linearGradient><linearGradient id="iKFTfdd" x1="19.588" x2="18.361" y1="6.04" y2="6.04" gradientUnits="userSpaceOnUse"><stop class="t_opl6b5d"/><stop offset="1" class="r1b4l6vhf"/></linearGradient><linearGradient id="idDVUGc" x1="19.158" x2="18.974" y1="6.899" y2="7.013" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1cZLfc" x1="16.559" x2="16.375" y1="6.899" y2="7.013" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="inqBmcd" x1="24.421" x2="26.951" y1="10.087" y2="11.158" gradientUnits="userSpaceOnUse"><stop class="gpb99wbpl"/><stop offset="1" class="g0107hbnw"/></linearGradient><linearGradient id="iZtPjwd" x1="23.06" x2="23.438" y1="13.196" y2="11.192" gradientUnits="userSpaceOnUse"><stop class="kutwh3b_w"/><stop offset="1" class="on9otxbot"/></linearGradient><linearGradient id="itr3efe" x1="24.213" x2="24.213" y1="9.29" y2="6.665" gradientUnits="userSpaceOnUse"><stop class="fkmin4duu"/><stop offset="1" class="b1mtrsw-m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-merpeople-medium" /></template>
<style>
.a5wwfyvbc {
  stop-color: var(--svg-color--a07570, #A07570);
}

.aau54zb2u {
  stop-color: var(--svg-color--a87e70, #A87E70);
  stop-opacity: 0;
}

.akquh7bgt {
  d: path("M18.701 6.586a.527.527 0 0 1 .508.666H18.19a.53.53 0 0 1 .51-.666");
}

.aqs3hv35q {
  stop-color: var(--svg-color--a47970, #A47970);
}

.b1mtrsw-m {
  stop-color: var(--svg-color--b49381, #B49381);
  stop-opacity: 0;
}

.b49-bdbcc {
  stop-color: var(--svg-color--794556, #794556);
}

.bd2iczr0j {
  stop-color: var(--svg-color--634b48, #634B48);
}

.bh0i_3bdf {
  stop-color: var(--svg-color--634b48, #634B48);
  stop-opacity: 0;
}

.bxcombcbd {
  stop-color: var(--svg-color--895d59, #895D59);
  stop-opacity: 0;
}

.c4_34bhlh {
  stop-color: var(--svg-color--855972, #855972);
  stop-opacity: 0;
}

.cfq0k4bto {
  fill: var(--svg-color--a37c6a, #A37C6A);
  d: path("m17.184 7.007l-.314 1.005a.32.32 0 0 0 .308.413h.465a.32.32 0 0 0 .307-.413l-.314-1.005c-.067-.222-.381-.222-.452 0");
}

.chm_zob8h {
  stop-color: var(--svg-color--7a5449, #7A5449);
}

.cic6athgq {
  stop-color: var(--svg-color--a2786d, #A2786D);
  stop-opacity: 0;
}

.ck9qz_2lp {
  stop-color: var(--svg-color--85506e, #85506E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn6gyybop {
  stop-color: var(--svg-color--56363a, #56363A);
}

.d0wb5fb-u {
  stop-color: var(--svg-color--a27b70, #A27B70);
}

.d804zky3u {
  d: path("M13.356 19.091c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.954-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531H13.64c-2.625 0-3.246-1.89-3.355-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.521-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.44-.296c.52.119.951.252 1.57.567a3.4 3.4 0 0 1 1.238 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.866.388c-.139.063-.208.223-.14.36c.474.956 1.468.87 2.858.87c1.851 0 2.96-1.325 2.843-2.724c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.328-2.055-1.145-2.055-2.926");
}

.dacedmb2p {
  stop-color: var(--svg-color--5e4341, #5E4341);
}

.djrdya1sy {
  stop-color: var(--svg-color--a07b73, #A07B73);
  stop-opacity: 0;
}

.dogwq2blg {
  stop-color: var(--svg-color--8b61d1, #8B61D1);
  stop-opacity: 0;
}

.dsu9eguof {
  stop-color: var(--svg-color--7550b8, #7550B8);
}

.e_l7oqrnp {
  stop-color: var(--svg-color--865b51, #865B51);
  stop-opacity: 0;
}

.eiflvuzgd {
  fill: var(--svg-color--000, #000);
  d: path("M16.422 7.113a.3.3 0 0 0-.302-.302a.3.3 0 0 0-.269.442h.535a.3.3 0 0 0 .036-.14");
}

.eywjsqb5l {
  fill: var(--svg-color--8d62d5, #8D62D5);
  d: path("M14.09 13.15a.4.4 0 0 0-.4.4v1.128a1.3 1.3 0 0 0 1.3 1.3h4.846a1.3 1.3 0 0 0 1.3-1.3V13.55a.4.4 0 0 0-.4-.4h-1.842a1.5 1.5 0 0 0-1.377.904c-.027.062-.18.062-.207 0a1.5 1.5 0 0 0-1.377-.904z");
}

.f_g0dqsvm {
  d: path("M14.404 6.474h.007l-.006-.156l-.006-.181c.012-.56.34-.778.479-.85l.03-.012l.03-.012c.316-.145.57-.398.704-.73l.048-.115a.156.156 0 0 1 .273-.03a2.28 2.28 0 0 0 1.885.99h1.902c.107 0 .64.05.672.786l-.07 1.816c-.073 1.657-1.367 2.769-2.945 2.769c-1.58 0-2.872-1.112-2.945-2.769z");
}

.f-9ripbsd {
  stroke: var(--svg-color--493236, #493236);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M16.316 5.819c-.19-.047-.664-.024-.981.203");
}

.f32er0yca {
  d: path("M17.054 2.597c-.67-.147-1.564.586-1.633.834c.91 2.14 2.14 2 3.841 1.936c.945-.035 1.02.301 1.1.506c.156-2.688-1.783-2.939-3.308-3.276");
}

.fkmin4duu {
  stop-color: var(--svg-color--b49381, #B49381);
}

.ft5dv1b6b {
  fill: none;
}

.ftmryjblq {
  stop-color: var(--svg-color--1c1414, #1C1414);
  stop-opacity: 0;
}

.g0107hbnw {
  stop-color: var(--svg-color--b58f7d, #B58F7D);
  stop-opacity: 0;
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.g2qbx_b_v {
  stop-color: var(--svg-color--694a46, #694A46);
}

.gjbve0bnv {
  d: path("M14.641 8.172a.95.95 0 1 0 0-1.902a.95.95 0 0 0 0 1.902");
}

.gpb99wbpl {
  stop-color: var(--svg-color--b58f7d, #B58F7D);
}

.gs2wj8m6y {
  stop-color: var(--svg-color--a47a6f, #A47A6F);
  stop-opacity: 0;
}

.gwqfskb8v {
  stop-color: var(--svg-color--9f7ada, #9F7ADA);
}

.h0xizc-pq {
  stop-color: var(--svg-color--5e3e40, #5E3E40);
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.ha79ukbar {
  stop-color: var(--svg-color--b29483, #B29483);
}

.hj78b9cjo {
  stop-color: var(--svg-color--34affa, #34AFFA);
  stop-opacity: 0;
}

.hwk_mxbwm {
  d: path("m15.402 6.17l-.002.002a.159.159 0 0 1-.163-.272l.002-.002l.006-.003l.02-.01q.024-.015.068-.035c.058-.028.141-.064.242-.096c.201-.064.482-.118.785-.065a.158.158 0 0 1-.055.313c-.236-.042-.462 0-.633.054a1.6 1.6 0 0 0-.257.107z");
}

.hy3u76v1i {
  stop-color: var(--svg-color--926760, #926760);
}

.i_am4rb0b {
  stop-color: var(--svg-color--92607c, #92607C);
  stop-opacity: 0;
}

.i2h38kz1u {
  stop-color: var(--svg-color--1c1414, #1C1414);
}

.icbl5ibjw {
  stop-color: var(--svg-color--7e554c, #7E554C);
}

.idot92bag {
  d: path("M24.218 13.296v.793l-3.72-2.397l.083-.198z");
}

.inz52_phe {
  d: path("m21.018 3.79l.204.628c.03.09.12.16.22.16l.697.01c.21 0 .285.242.105.382l-.532.418c-.08.06-.11.16-.08.26l.198.658c.07.22-.146.36-.336.23l-.542-.398a.225.225 0 0 0-.27 0l-.551.399c-.19.13-.396-.01-.336-.23l.197-.66c.03-.1 0-.2-.08-.26l-.539-.397c-.18-.14-.097-.382.133-.382l.666-.01c.1 0 .19-.07.22-.16l.231-.648c.07-.23.325-.21.395 0");
}

.iorvdubip {
  fill: var(--svg-color--33aef9, #33AEF9);
  d: path("m21.018 3.79l.204.628c.03.09.12.16.22.16l.697.01c.21 0 .285.242.105.382l-.532.418c-.08.06-.11.16-.08.26l.198.658c.07.22-.146.36-.336.23l-.542-.398a.225.225 0 0 0-.27 0l-.551.399c-.19.13-.396-.01-.336-.23l.197-.66c.03-.1 0-.2-.08-.26l-.539-.397c-.18-.14-.097-.382.133-.382l.666-.01c.1 0 .19-.07.22-.16l.231-.648c.07-.23.325-.21.395 0");
}

.ipbb10b0b {
  stop-color: var(--svg-color--b68c75, #B68C75);
}

.ivaw61bob {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.824 6.425c.385 0 .711.267.8.626a.162.162 0 0 1-.158.201h-1.319a.136.136 0 0 1-.134-.16a.826.826 0 0 1 .81-.667");
}

.iwj441a3a {
  stop-color: var(--svg-color--98636e, #98636E);
}

.j055wdbud {
  stop-color: var(--svg-color--9b6c69, #9B6C69);
}

.je2v5tfor {
  fill: var(--svg-color--87014e, #87014E);
  d: path("M17.41 8.941a1.8 1.8 0 0 1-.84-.203c-.083-.044-.172.052-.12.13a1.142 1.142 0 0 0 1.92 0c.053-.08-.036-.174-.12-.13a1.8 1.8 0 0 1-.84.203");
}

.jhou7tlnj {
  stop-color: var(--svg-color--201422, #201422);
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.jmv4rsfcq {
  stop-color: var(--svg-color--8c6152, #8C6152);
}

.jri39dp3m {
  fill: var(--svg-color--96606a, #96606A);
  d: path("m17.179 7.09l-.404 1.004a.32.32 0 0 0 .307.413h.465a.32.32 0 0 0 .308-.413l-.314-1.005c-.068-.222-.292-.222-.363 0");
}

.jsw980phx {
  stop-color: var(--svg-color--b79784, #B79784);
}

.jtmo9zbne {
  stop-color: var(--svg-color--9c6873, #9C6873);
  stop-opacity: 0;
}

.juawl1gfq {
  stop-color: var(--svg-color--886863, #886863);
  stop-opacity: 0;
}

.jyqj6pdqa {
  stop-color: var(--svg-color--9b6c69, #9B6C69);
  stop-opacity: 0;
}

.k1mq2-9zz {
  stop-color: var(--svg-color--6c4c4c, #6C4C4C);
  stop-opacity: 0;
}

.k39_6wapl {
  stop-color: var(--svg-color--98676b, #98676B);
  stop-opacity: 0;
}

.k5p37d2fo {
  stop-color: var(--svg-color--b48f7f, #B48F7F);
}

.kd1pu_b5e {
  stop-color: var(--svg-color--543737, #543737);
  stop-opacity: 0;
}

.ke5ghyvxy {
  stop-color: var(--svg-color--5c4040, #5C4040);
  stop-opacity: 0;
}

.kutwh3b_w {
  stop-color: var(--svg-color--b38c7a, #B38C7A);
}

.kzknyvg9e {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.41 8.941a1.8 1.8 0 0 1-.84-.203c-.083-.044-.172.052-.12.13a1.142 1.142 0 0 0 1.92 0c.053-.08-.036-.174-.12-.13a1.8 1.8 0 0 1-.84.203Z");
}

.l_2gubcru {
  stop-color: var(--svg-color--8f5864, #8F5864);
}

.l85u8ibfx {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M13.356 19.091c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.954-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531H13.64c-2.625 0-3.246-1.89-3.355-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.521-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.44-.296c.52.119.951.252 1.57.567a3.4 3.4 0 0 1 1.238 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.866.388c-.139.063-.208.223-.14.36c.474.956 1.468.87 2.858.87c1.851 0 2.96-1.325 2.843-2.724c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.328-2.055-1.145-2.055-2.926");
}

.l97w7x76c {
  stop-color: var(--svg-color--935f6a, #935F6A);
  stop-opacity: 0;
}

.lby3v6ati {
  d: path("M6.762 16.042a.486.486 0 1 1 .973 0v.775a.486.486 0 0 1-.973 0z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lnzo7tbfa {
  stop-color: var(--svg-color--542e3f, #542E3F);
  stop-opacity: 0;
}

.m4pcayl4x {
  d: path("M21.317 26.665c0-5.343-3.922-7.968-5.234-9l3.25-1.453c1.125.521 3.035 2.358 3.453 5.11c.484 3.187-.927 4.927-1.469 5.343");
}

.mbrovup5s {
  stop-color: var(--svg-color--3a1e36, #3A1E36);
}

.mk_tesa_t {
  stop-color: var(--svg-color--49c4fa, #49C4FA);
}

.mp5yrl3-i {
  fill: var(--svg-color--895a5c, #895A5C);
  d: path("M14.715 13.837a.325.325 0 0 0-.325.325v.916c0 .584.473 1.056 1.056 1.056h3.935c.583 0 1.055-.473 1.055-1.056v-.916a.325.325 0 0 0-.324-.325h-1.496a1.22 1.22 0 0 0-1.119.735c-.022.05-.146.05-.168 0a1.22 1.22 0 0 0-1.118-.735z");
}

.mzcd8ybsc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.845 24.428c.41.163 1.402.784 2.097 1.97");
}

.n4ybtv3-a {
  stop-color: var(--svg-color--6c4c4c, #6C4C4C);
}

.n7-hw2b3h {
  stop-color: var(--svg-color--9f7ada, #9F7ADA);
  stop-opacity: 0;
}

.nj83g3bmu {
  stop-color: var(--svg-color--99696c, #99696C);
}

.njswj9qiy {
  stop-color: var(--svg-color--8d6762, #8D6762);
  stop-opacity: 0;
}

.nl_8d1b0i {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.66 6.698c.038.05-.04.111-.13.178c-.088.066-.154.113-.191.063s.004-.145.093-.211c.089-.067.191-.08.229-.03");
}

.no2vo2b5r {
  stop-color: var(--svg-color--b69180, #B69180);
  stop-opacity: 0;
}

.nu6p8xpxk {
  fill-rule: evenodd;
  d: path("m19.615 5.9l-.081.136za.159.159 0 0 1-.162.272l-.003-.002l-.067-.034a2 2 0 0 0-.202-.08a1.34 1.34 0 0 0-.634-.054a.159.159 0 0 1-.055-.313c.303-.053.584 0 .785.065a2 2 0 0 1 .33.14l.006.004z");
}

.nxis-vb-u {
  stop-color: var(--svg-color--a0736f, #A0736F);
  stop-opacity: 0;
}

.nxpnkb1eb {
  stop-color: var(--svg-color--a07b73, #A07B73);
}

.o0eqsac9n {
  d: path("M16.12 6.586a.527.527 0 0 0-.508.667h1.018a.53.53 0 0 0-.51-.666");
}

.o0h7y_boi {
  stop-color: var(--svg-color--45beff, #45BEFF);
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
}

.o87uryobz {
  d: path("M20.263 8.172a.95.95 0 1 0 0-1.902a.95.95 0 0 0 0 1.902");
}

.oc32bubbt {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M18.085 6.884c.157-.275.396-.493.909-.493a.98.98 0 0 1 .634.218c.159.128.137.292.014.354l-.328.187c-.385-.124-.811-.141-1.229-.266");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.on9otxbot {
  stop-color: var(--svg-color--b38c7a, #B38C7A);
  stop-opacity: 0;
}

.ozq3jw9ll {
  d: path("M20.263 7.856a.635.635 0 1 0 0-1.27a.635.635 0 0 0 0 1.27");
}

.p6977lbwx {
  d: path("M25.054 9.557c.399-.066.488-.33.488-.501v-.535a.184.184 0 0 1 .367 0v4.93a.527.527 0 0 1-1.055 0V9.77c0-.11.09-.197.2-.214");
}

.pdupf-5td {
  d: path("M14.653 7.856a.635.635 0 1 0 0-1.27a.635.635 0 0 0 0 1.27");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q2m7q-bcq {
  d: path("M15.62 4.556c-.22.565-1.18 1.028-1.61 1.14c-.142-1.143.301-2.523 1.702-2.274l.236.915c-.236-.066-.286.11-.328.219");
}

.qdgeq05dx {
  d: path("M25.683 7.95h-.003a.53.53 0 0 0-.531.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.546l.56-.558a.44.44 0 0 1 .638.605");
}

.qg84xbb9n {
  stop-color: var(--svg-color--6d4941, #6D4941);
}

.ql9fbhbmb {
  stop-color: var(--svg-color--8c6152, #8C6152);
  stop-opacity: 0;
}

.qxbkqy2mr {
  d: path("M9.862 15.744c1.812 1.575 4.203 1.213 5.172.875v-4.626h7.234c.517-1.326.156-2.452-.236-3.066a.28.28 0 0 1-.03-.24c.083-.236.193-.616.207-.916c.032-.66-.171-.707-.19-1.613c-.02-.907-.308-1.241-.782-2.016c-.383-.625-1.371-1.031-1.973-1.27c-.66-.261-.894-.757-1.89-.757c-.77 0-1.277.39-1.626.729a.85.85 0 0 1-.48.23c-1.223.163-2.266.735-2.844 1.802c-.338.626-.368 1.608-.364 2.282a.53.53 0 0 1-.421.513c-1.528.345-2.65 1.23-3.18 2.233c-.578 1.093-.863 3.87 1.403 5.84");
}

.qxcnoh65g {
  stop-color: var(--svg-color--855972, #855972);
}

.qy_lu4bmh {
  stop-color: var(--svg-color--b69180, #B69180);
}

.r0kaalb9z {
  stop-color: var(--svg-color--a87e70, #A87E70);
}

.r1b4l6vhf {
  stop-color: var(--svg-color--3f2232, #3F2232);
}

.rd_1vj1uu {
  stop-color: var(--svg-color--9971db, #9971DB);
}

.rfs9njbxq {
  stop-color: var(--svg-color--4e373b, #4E373B);
}

.rggh3hbuf {
  d: path("M18.66 6.698c.038.05-.04.111-.13.178c-.088.066-.154.113-.191.063s.004-.145.093-.211c.089-.067.191-.08.229-.03");
}

.ro7svqvjx {
  fill: var(--svg-color--000, #000);
  d: path("M18.399 7.113a.3.3 0 0 1 .302-.302a.3.3 0 0 1 .269.441h-.535a.3.3 0 0 1-.036-.139");
}

.rp4tm-b1w {
  stop-color: var(--svg-color--a07674, #A07674);
}

.rqv3tobxx {
  stop-color: var(--svg-color--8e5e68, #8E5E68);
  stop-opacity: 0;
}

.rvgjtg4fi {
  d: path("M20.726 13.688v3.421a.65.65 0 0 1-.65.65H14.75a.65.65 0 0 1-.65-.65v-2.75l-1.953 1.697a2.5 2.5 0 0 1-1.64.613h-1.84l-.612.527a.527.527 0 0 1-.716-.774l.317-.316a.1.1 0 0 0-.019-.154l-.018-.011a.384.384 0 0 0-.476.065l-.554.583a.526.526 0 0 1-.776-.71l.755-.857a.98.98 0 0 1 .621-.326l3.069-.355a.5.5 0 0 0 .284-.132l3.247-3.04c.889-.89 2.57-.98 3.735-.98c1.495 0 2.532.234 3.2.574l2.862 1.473a.202.202 0 0 0 .293-.16c.049-.5.132-1.271.197-1.853a.2.2 0 0 0-.046-.15l-.373-.445a1 1 0 0 1-.235-.644V7.783a.531.531 0 0 1 1.062 0v.667c0 .18.045.36.17.488c.065.067.145.137.239.2c.116.078.255-.016.255-.156v-.5a.531.531 0 1 1 1.063 0v1.39l.015.703c.019.846.042 1.907.088 2.883c.03.64-.263 1.255-.79 1.618a1.8 1.8 0 0 1-1.84.121z");
}

.rz_b8bbbi {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
  stop-opacity: 0;
}

.s536pit3i {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
}

.s9ajizb_e {
  stop-color: var(--svg-color--45beff, #45BEFF);
  stop-opacity: 0;
}

.sdf9tobyx {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.997 6.425a.825.825 0 0 0-.8.626a.162.162 0 0 0 .158.201h1.318a.136.136 0 0 0 .135-.16a.83.83 0 0 0-.81-.667");
}

.t_opl6b5d {
  stop-color: var(--svg-color--412332, #412332);
}

.t1wmkubur {
  stop-color: var(--svg-color--9a736a, #9A736A);
}

.t2ck-pbsh {
  cx: 15.959px;
  cy: 6.811px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.229px;
  ry: 0.116px;
}

.tf07upwmc {
  stop-color: var(--svg-color--956f63, #956F63);
}

.thpdt1biy {
  stop-color: var(--svg-color--8d6762, #8D6762);
}

.tyid2cb9a {
  stop-color: var(--svg-color--9e7470, #9E7470);
}

.u1lo-0nty {
  stop-color: var(--svg-color--865a63, #865A63);
}

.u27eaq1ke {
  stop-color: var(--svg-color--5b3333, #5B3333);
}

.u9ihbxbhg {
  stop-color: var(--svg-color--9e776c, #9E776C);
  stop-opacity: 0;
}

.ubz5oeoiz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.991 23.91c-.307.352-1.133 1.1-1.885 1.832");
}

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.um-4-ifpg {
  stop-color: var(--svg-color--9e776c, #9E776C);
}

.utkhftb9q {
  cx: 15.959px;
  cy: 6.811px;
  rx: 0.229px;
  ry: 0.116px;
}

.v-5fxgbwn {
  stop-color: var(--svg-color--643b2f, #643B2F);
}

.v3hxs-buk {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.736 6.884c-.157-.275-.396-.493-.909-.493a.98.98 0 0 0-.634.218c-.159.128-.137.292-.014.354l.328.187c.385-.124.811-.141 1.229-.266");
}

.vckbn7bgk {
  d: path("m17.184 7.007l-.314 1.005a.32.32 0 0 0 .308.413h.465a.32.32 0 0 0 .307-.413l-.314-1.005c-.067-.222-.381-.222-.452 0");
}

.vdwscwwnn {
  stop-color: var(--svg-color--956f63, #956F63);
  stop-opacity: 0;
}

.ve6kq2bvl {
  stop-color: var(--svg-color--6c493c, #6C493C);
  stop-opacity: 0;
}

.vmpvo2iof {
  stop-color: var(--svg-color--98676b, #98676B);
}

.vpkiteigl {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M24.085 7.63v1.248c0 .066.026.13.073.177l.26.26");
}

.vs599jbgl {
  stop-color: var(--svg-color--6e4037, #6E4037);
}

.vypt9ybrl {
  stop-color: var(--svg-color--806058, #806058);
}

.w_bi9zfnz {
  stop-color: var(--svg-color--724c46, #724C46);
}

.w4wjacb9v {
  stop-color: var(--svg-color--8c60d5, #8C60D5);
  stop-opacity: 0;
}

.wh5184nvn {
  stop-color: var(--svg-color--a47970, #A47970);
  stop-opacity: 0;
}

.wj_ij8b3z {
  stop-color: var(--svg-color--a07674, #A07674);
  stop-opacity: 0;
}

.wliqnbp1k {
  d: path("M14.09 13.15a.4.4 0 0 0-.4.4v1.128a1.3 1.3 0 0 0 1.3 1.3h4.846a1.3 1.3 0 0 0 1.3-1.3V13.55a.4.4 0 0 0-.4-.4h-1.842a1.5 1.5 0 0 0-1.377.904c-.027.062-.18.062-.207 0a1.5 1.5 0 0 0-1.377-.904z");
}

.x0z57ccyo {
  stop-color: var(--svg-color--b08770, #B08770);
}

.x0zlvzb_b {
  stop-color: var(--svg-color--694c47, #694C47);
}

.x2e_pmc0g {
  d: path("M16.6 7.05c0-.17-.138-.283-.175-.317l-.17.164l.104.213z");
}

.x5vi3qbzz {
  stop-color: var(--svg-color--8b5560, #8B5560);
}

.x6pc4sbye {
  stop-color: var(--svg-color--8b5a63, #8B5A63);
}

.x7utjgb1r {
  stop-color: var(--svg-color--5c4040, #5C4040);
}

.xcso8mb_w {
  stop-color: var(--svg-color--92607c, #92607C);
}

.xpjl1tbpw {
  stop-color: var(--svg-color--3a1e36, #3A1E36);
  stop-opacity: 0;
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.y1iz3jbsf {
  stop-color: var(--svg-color--a47a6f, #A47A6F);
}

.y77jxgbee {
  stop-color: var(--svg-color--967669, #967669);
}

.yem0kqbom {
  stop-color: var(--svg-color--7b5554, #7B5554);
}

.yf02b6ygm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.429 26.864c-.007.65.436 1.948 2.266 1.948h3.177c1.01-.014 3.316-.516 4.469-2.414");
}

.yh8fa0s0y {
  stop-color: var(--svg-color--997366, #997366);
}

.yiekaulvh {
  stop-color: var(--svg-color--b48f7f, #B48F7F);
  stop-opacity: 0;
}

.ymbtox6zc {
  stop-color: var(--svg-color--4e373b, #4E373B);
  stop-opacity: 0;
}

.yo-rx8c0q {
  d: path("M19.17 7.043a.5.5 0 0 0-.137-.272l-.152.167l.069.135z");
}

.z5tt1acjt {
  stroke: var(--svg-color--493236, #493236);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M18.557 5.819c.19-.047.664-.024.981.203");
}

.zwlqziglb {
  stop-color: var(--svg-color--825a51, #825A51);
  stop-opacity: 0;
}

</style>
