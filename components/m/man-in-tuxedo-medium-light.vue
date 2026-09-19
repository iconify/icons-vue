<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iXgldre)" class="r_dde0bjs"/><path fill="url(#isb0KAe)" class="r_dde0bjs"/><path fill="url(#io64Fkb)" class="r_dde0bjs"/><path fill="url(#innkFvb)" class="r_dde0bjs"/><path fill="url(#iSyvqye)" class="r_dde0bjs"/><path fill="url(#it13lPd)" class="v7_asvbup"/><path fill="url(#iwtApwb)" class="v7_asvbup"/><g filter="url(#i8PI6rc)"><path fill="url(#iWb4Erb)" class="i4bfus74w"/><path fill="url(#iU26Bic)" class="i4bfus74w"/></g><path fill="url(#ifRivkX)" class="cmjtiobwc"/><g filter="url(#i16povb)"><path fill="url(#iHfv3vd)" class="ur3-f2bxg"/><path fill="url(#inAPX1c)" class="ur3-f2bxg"/></g><g filter="url(#inctEYc)"><path clip-rule="evenodd" class="ohok_pr6g"/></g><path fill="url(#igYigtA)" class="mnhguyxxv"/><path fill="url(#i2Yp6zb)" class="mnhguyxxv"/><path fill="url(#i8eM4jc)" class="mnhguyxxv"/><path fill="url(#ivSNRAc)" class="mnhguyxxv"/><path fill="url(#ivBVDeb)" class="yod-f__vb"/><path fill="url(#iDmYgQc)" class="yod-f__vb"/><path fill="url(#iz6lKBe)" class="yod-f__vb"/><path fill="url(#ixoWjdd)" class="yod-f__vb"/><g filter="url(#iTX2Tdb)"><path fill="url(#iyEAavb)" class="qgls9_bhu"/></g><g filter="url(#iQ5FIqe)"><path fill="url(#iEhWmfe)" class="j2tlhn_ku"/></g><path fill="url(#iT1EDWZ)" class="j2tlhn_ku"/><path fill="url(#ijCP3RK)" class="j2tlhn_ku"/><path fill="url(#iOno0ye)" class="j2tlhn_ku"/><g filter="url(#iDciKmb)"><path class="d2k6_zbgr"/></g><g filter="url(#i9dzX0d)"><circle class="nfk4j0bpr"/></g><g filter="url(#iiOpUkc)"><circle class="b1dt7tbhz"/></g><g filter="url(#iO1GXTc)"><circle fill="url(#iOIeteb)" class="lqnrqrgpd"/></g><g filter="url(#iB3gWnd)"><circle fill="url(#iKvMr1c)" class="t52-74brh"/></g><rect fill="url(#ilQBGTd)" class="x64-dzbyg"/><rect fill="url(#icBSzEd)" class="x64-dzbyg"/><rect fill="url(#iW5t3Ie)" class="x64-dzbyg"/><rect fill="url(#iY0fGZc)" class="x64-dzbyg"/><g filter="url(#iYmrRsd)"><path fill="url(#iyqz13b)" class="l0zvedylt"/></g><path fill="url(#irifE9c)" class="l0zvedylt"/><g filter="url(#iWv0Qrd)"><path class="vws41pbfh"/><path fill="url(#iCSMbXb)" class="zr2l1ybki"/><path fill="url(#ioDUrMc)" class="zr2l1ybki"/><path fill="url(#ieQanZd)" class="zr2l1ybki"/></g><g filter="url(#ilyh8ec)"><circle fill="url(#i8PvrCc)" class="vx3rjpzqv"/><circle fill="url(#iIuXvJe)" class="vx3rjpzqv"/></g><g filter="url(#iPsajpc)"><circle fill="url(#ifW3QHs)" class="hc5ioib3d"/></g><g filter="url(#iSnTJce)"><circle fill="url(#iIGdLQb)" class="rvyek79ap"/></g><g filter="url(#igiAepe)"><circle fill="url(#ilVYRad)" class="mijhkwbrl"/><circle fill="url(#i51tDNe)" class="mijhkwbrl"/></g><g filter="url(#izoJ36i)"><circle class="l6okjl_yx"/><circle fill="url(#iayVSmb)" class="uw1oasn2r"/><circle fill="url(#iN8b6Hd)" class="uw1oasn2r"/></g><g filter="url(#iS931Xb)"><path fill="url(#i69iSPc)" class="ewhsb4b9b"/><path fill="url(#iVGWkOd)" class="ewhsb4b9b"/><path fill="url(#iCVnMab)" class="ewhsb4b9b"/><path fill="url(#iiJtCib)" class="ewhsb4b9b"/><path fill="url(#ixBIRFb)" class="ewhsb4b9b"/><path fill="url(#it9Lywz)" class="ewhsb4b9b"/></g><g filter="url(#igtuMBe)"><path class="yo1zipbes"/><path fill="url(#iQeuwgb)" class="wasy5xbgj"/><path fill="url(#i1oOn1c)" class="wasy5xbgj"/><path fill="url(#i8YsmLb)" class="wasy5xbgj"/><path fill="url(#iLEL3EQ)" class="wasy5xbgj"/><path fill="url(#i9WgQOe)" class="wasy5xbgj"/></g><path fill="url(#iMLqWbb)" class="wasy5xbgj"/><path fill="url(#i5AjFVc)" class="wasy5xbgj"/><g filter="url(#iQ09tRc)"><path class="sweynhbyn"/></g><g filter="url(#iTP8TVc)"><path class="tze17_bvh"/><path fill="url(#ikRRyjc)" class="sviot6mlz"/><path fill="url(#iKsuvHc)" class="sviot6mlz"/><path fill="url(#ik4YXne)" class="sviot6mlz"/></g><path stroke="url(#i4qj4oc)" class="ws4ma4lmo"/><g filter="url(#iLTKkab)"><path class="tk1teelas"/></g><g filter="url(#iXKwVsd)"><path class="lj1oyn2lk"/></g><path class="ljpvikb1z"/><path fill="url(#i8QSH8b)" class="t4cn-6bfi"/><path class="kv5l7-dbe"/><g filter="url(#ihNFORf)"><path class="t810qw9at"/><path fill="url(#iah6dud)" class="uui3gyu-f"/></g><g filter="url(#ituUzdd)"><path fill="url(#i5qWANc)" class="q43d9p4nd"/></g><path class="w16iu6xog"/><path fill="url(#iAgBJ1d)" class="uyq2hibxk"/><path class="jbvo0678w"/><g filter="url(#ibszJRc)"><path fill="url(#iYdTu4d)" class="wwn6slsot"/></g><g filter="url(#iaqnn8c)"><ellipse transform="rotate(-27.914 13.583 9.881)" class="ekhlziuiq"/><ellipse fill="url(#iIL8I8d)" transform="rotate(-27.914 13.583 9.881)" class="syeyeqb6i"/></g><g filter="url(#ipv1lkd)"><path stroke="url(#ijFn71d)" class="m8g60fwwb"/></g><g filter="url(#i9g5wPP)"><path stroke="url(#i51Z63d)" class="wwxx-0ybr"/></g><defs><radialGradient id="iXgldre" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.345)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="isb0KAe" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.763 10.827)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="io64Fkb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.255)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="it13lPd" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.256 2.624)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="iwtApwb" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.156)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="iWb4Erb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.411)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="ifRivkX" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.567)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="iHfv3vd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.096 22.536)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="inAPX1c" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.34 13.04)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="i2Yp6zb" cx="0" cy="0" r="1" gradientTransform="rotate(-152.488 10.108 8.371)scale(1.16274 3.57827)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="i8eM4jc" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 -.22754 .55824 1.95507 13.236 18.677)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="iDmYgQc" cx="0" cy="0" r="1" gradientTransform="matrix(1.39062 .34376 -1.28105 5.18228 17.174 18.771)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="iz6lKBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .35156 -1.56152 -1.21452 17.276 19.412)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="iEhWmfe" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.074 11.87)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="iT1EDWZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.91838 1.78314 -4.30906 -2.21931 13.135 16.293)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="ijCP3RK" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.94239 -.4885 0 11.747 16.35)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="iOno0ye" cx="0" cy="0" r="1" gradientTransform="matrix(.0919 1.7035 -.36222 .01954 10.658 20.646)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="iOIeteb" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.869 16.058)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iKvMr1c" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.487 14.554)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="icBSzEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.26562 -2.59161 0 16.012 16.854)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="rwdag_b_k"/><stop offset="1" class="pv5xcyfwi"/></radialGradient><radialGradient id="iW5t3Ie" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 -1.22153 .56328 .63405 16.697 18.81)" gradientUnits="userSpaceOnUse"><stop class="erqbxmbxf"/><stop offset="1" class="ocbkol0bt"/></radialGradient><radialGradient id="iY0fGZc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4375 -1.32812 .29393 -.31814 15.353 18.573)" gradientUnits="userSpaceOnUse"><stop class="p-2t4fbpu"/><stop offset="1" class="ckn25zbri"/></radialGradient><radialGradient id="iyqz13b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.76)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="irifE9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.134)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="ioDUrMc" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.443 6.87)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="ieQanZd" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 18.99)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="i8PvrCc" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.369 12.598)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iIuXvJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.35)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="ifW3QHs" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07076 9.622 10.66)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="i51tDNe" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.176 10.395)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iayVSmb" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.762 11.48)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iN8b6Hd" cx="0" cy="0" r="1" gradientTransform="matrix(.25926 .25663 -.33084 .33423 20.803 10.66)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iVGWkOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.93273 -9.48977 0 16.51 7.318)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="fal1rxboc"/><stop offset=".975" class="i7do3ibnh"/></radialGradient><radialGradient id="iiJtCib" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60857 0 18.384 9.388)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="ixBIRFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.827 9.354)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iQeuwgb" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 9.144 6.306)scale(5.6057 9.53299)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="i8YsmLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.06682 -1.86131 .91413 -.03282 11.846 7.204)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="iLEL3EQ" cx="0" cy="0" r="1" gradientTransform="matrix(.85907 -1.96631 1.60368 .70064 20.265 8.922)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="i9WgQOe" cx="0" cy="0" r="1" gradientTransform="matrix(.9927 1.23176 -1.08755 .87648 15.263 2.059)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iMLqWbb" cx="0" cy="0" r="1" gradientTransform="matrix(.18136 .78313 -1.28748 .29815 16.733 2.059)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="i5AjFVc" cx="0" cy="0" r="1" gradientTransform="matrix(.72544 .89725 -2.0104 1.62544 11.694 3.787)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="i8QSH8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90308 -1.06858 0 18.217 10.31)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iah6dud" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.459 .626)scale(.37817 .52064)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iAgBJ1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90312 -1.06863 0 13.855 10.31)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iIL8I8d" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.803 -1.58)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="i8PI6rc" width="4.081" height="11.683" x="5.07" y="18.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/></filter><filter id="i16povb" width="5.909" height="14.117" x="12.858" y="15.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/></filter><filter id="inctEYc" width="7.13" height="5.229" x="12.285" y="16.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3334" stdDeviation=".3"/></filter><filter id="iTX2Tdb" width="7.239" height="14.645" x="9.195" y="15.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3334" stdDeviation=".5"/></filter><filter id="iQ5FIqe" width="5.917" height="14.31" x="10.326" y="15.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3334" result="effect2_innerShadow_4002_3334"/></filter><filter id="iDciKmb" width="6.504" height="14.261" x="15.345" y="15.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3334" result="effect2_innerShadow_4002_3334"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3334" result="effect3_innerShadow_4002_3334"/></filter><filter id="i9dzX0d" width="2" height="2" x="14.731" y="24.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3334" stdDeviation=".25"/></filter><filter id="iiOpUkc" width="2" height="2" x="14.731" y="21.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3334" stdDeviation=".25"/></filter><filter id="iO1GXTc" width="1.05" height="1.05" x="15.504" y="25.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/></filter><filter id="iB3gWnd" width="1.05" height="1.05" x="15.504" y="22.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/></filter><filter id="iYmrRsd" width="2.465" height="2.95" x="16.029" y="17.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3334" result="effect2_innerShadow_4002_3334"/></filter><filter id="iWv0Qrd" width="2.365" height="2.9" x="13.731" y="17.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/></filter><filter id="ilyh8ec" width="1.717" height="1.717" x="15.204" y="17.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/></filter><filter id="iPsajpc" width="3.539" height="3.339" x="9.622" y="8.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/></filter><filter id="iSnTJce" width="2.99" height="2.99" x="9.796" y="9.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3334" stdDeviation=".25"/></filter><filter id="igiAepe" width="3.589" height="3.589" x="19.134" y="8.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/></filter><filter id="izoJ36i" width="2.99" height="2.99" x="19.309" y="9.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3334" stdDeviation=".25"/></filter><filter id="iS931Xb" width="10.373" height="12.177" x="10.881" y="5.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/></filter><filter id="igtuMBe" width="12.601" height="8.543" x="9.738" y="1.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/></filter><filter id="iQ09tRc" width="3.26" height="4.181" x="14.17" y="9.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3334" stdDeviation=".375"/></filter><filter id="iTP8TVc" width="2.377" height="3.181" x="14.85" y="9.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3334" stdDeviation=".125"/></filter><filter id="iLTKkab" width="2.979" height="1.873" x="17.221" y="7.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/></filter><filter id="iXKwVsd" width="2.98" height="1.873" x="12.073" y="7.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3334"/></filter><filter id="ihNFORf" width=".787" height=".696" x="17.483" y="9.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3334" stdDeviation=".05"/></filter><filter id="ituUzdd" width=".891" height=".913" x="18.323" y="9.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3334" stdDeviation=".1"/></filter><filter id="ibszJRc" width=".986" height="1.04" x="13.882" y="9.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3334" stdDeviation=".1"/></filter><filter id="iaqnn8c" width=".913" height=".704" x="13.127" y="9.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3334" stdDeviation=".05"/></filter><filter id="ipv1lkd" width="3.099" height="1.681" x="17.074" y="7.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3334" stdDeviation=".25"/></filter><filter id="i9g5wPP" width="3.177" height="1.738" x="11.855" y="7.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3334" stdDeviation=".25"/></filter><linearGradient id="innkFvb" x1="23.131" x2="22.971" y1="29.935" y2="29.935" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="iSyvqye" x1="8.858" x2="9.061" y1="29.935" y2="29.935" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="iU26Bic" x1="9.19" x2="7.596" y1="29.941" y2="29.941" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="igYigtA" x1="14.705" x2="13.268" y1="20.005" y2="16.88" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="zynu2nm7a"/></linearGradient><linearGradient id="ivSNRAc" x1="15.518" x2="15.209" y1="20.084" y2="19.966" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="ivBVDeb" x1="16.799" x2="18.471" y1="20.021" y2="17.146" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="ig120dbzq"/></linearGradient><linearGradient id="ixoWjdd" x1="16.486" x2="16.713" y1="19.822" y2="19.732" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="iyEAavb" x1="12.815" x2="12.815" y1="16.802" y2="29.447" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="ilQBGTd" x1="17.033" x2="14.384" y1="18.412" y2="18.542" gradientUnits="userSpaceOnUse"><stop class="g1x_nzvxe"/><stop offset="1" class="rmrnz5b-v"/></linearGradient><linearGradient id="iCSMbXb" x1="15.205" x2="14.838" y1="19.458" y2="19.005" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="iIGdLQb" x1="11.291" x2="10.651" y1="10.938" y2="10.938" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="ilVYRad" x1="21.89" x2="21.071" y1="9.568" y2="12.104" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="i69iSPc" x1="20.074" x2="12.438" y1="11.049" y2="12.187" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="iCVnMab" x1="10.643" x2="12.956" y1="13.744" y2="13.443" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="it9Lywz" x1="16.067" x2="16.067" y1="17.062" y2="16.422" gradientUnits="userSpaceOnUse"><stop class="hsnvekbai"/><stop offset="1" class="wmjuo_j3y"/></linearGradient><linearGradient id="i1oOn1c" x1="11.178" x2="14.08" y1="10.392" y2="5.238" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="ikRRyjc" x1="15.175" x2="16.113" y1="11.708" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="iKsuvHc" x1="16.977" x2="15.951" y1="12.03" y2="12.016" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="ik4YXne" x1="16.233" x2="16.233" y1="12.773" y2="12.2" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="i4qj4oc" x1="15.002" x2="15.437" y1="14.387" y2="13.7" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="i5qWANc" x1="18.995" x2="18.681" y1="10.031" y2="10.224" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iYdTu4d" x1="14.598" x2="14.285" y1="10.031" y2="10.224" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ijFn71d" x1="19.011" x2="18.591" y1="7.892" y2="7.033" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="i51Z63d" x1="13.707" x2="12.517" y1="7.764" y2="7.265" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-in-tuxedo-medium-light" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.az-h38bei {
  stop-color: var(--svg-color--4b3973, #4B3973);
}

.b_mjjkbmw {
  stop-color: var(--svg-color--8179b0, #8179B0);
}

.b0z0paczy {
  stop-color: var(--svg-color--4f3a77, #4F3A77);
}

.b1dt7tbhz {
  cx: 15.731px;
  cy: 22.729px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
}

.ckn25zbri {
  stop-color: var(--svg-color--905b44, #905B44);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm2l5-bra {
  stop-color: var(--svg-color--554181, #554181);
}

.cmjtiobwc {
  d: path("M8.901 18.258a10.68 10.68 0 0 0-3.831 8.18v3.497H8.9z");
}

.cof-_sb7w {
  stop-color: var(--svg-color--a487bb, #A487BB);
}

.cosmi4y3y {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
}

.cyzx27bkq {
  stop-color: var(--svg-color--978394, #978394);
}

.d2k6_zbgr {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.316 17.572c.031-1.094-.595-1.537-.887-1.626l-.668-.07v5.816c0 3.873-1.388 6.263-2.648 8.089c-.062.09.047.2.139.138c2.976-2.036 4.851-4.005 5.196-9.228a.203.203 0 0 0-.188-.215c-.321-.02-.607-.047-.809-.066a.204.204 0 0 1-.185-.206c.011-.575.022-1.659.05-2.632");
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.ekhlziuiq {
  cx: 13.583px;
  cy: 9.881px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.erqbxmbxf {
  stop-color: var(--svg-color--9c684f, #9C684F);
}

.ewhsb4b9b {
  d: path("m10.94 10.047l.048.001s-.053-.853-.107-1.44c0-.266.107-.586.322-.746l.16-.16c.269-.214.376-.534.376-.854v-.853a.52.52 0 0 1 .43-.533c.643-.16 1.984-.427 3.915-.427c1.93 0 3.271.267 3.915.427c.215.053.43.266.43.533v.853c0 .32.16.64.375.854c.502.351.47.545.429.96c-.054.533-.108 1.44-.108 1.44h.018l-.265 3.957c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.713 0-3.05-1.233-3.21-3.003z");
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.fal1rxboc {
  stop-color: var(--svg-color--ce938b, #CE938B);
  stop-opacity: 0;
}

.ff2asxc8d {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
}

.fj3b0ib3x {
  stop-color: var(--svg-color--564561, #564561);
  stop-opacity: 0;
}

.fojlwlb9t {
  stop-color: var(--svg-color--dfc6d4, #DFC6D4);
  stop-opacity: 0;
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1x_nzvxe {
  stop-color: var(--svg-color--a47264, #A47264);
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
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

.hc5ioib3d {
  cx: 11.291px;
  cy: 10.659px;
  r: 1.669px;
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hsnvekbai {
  stop-color: var(--svg-color--9a6266, #9A6266);
}

.i4bfus74w {
  d: path("M8.901 18.258a10.69 10.69 0 0 0-3.831 8.186v3.497H8.9z");
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i7do3ibnh {
  stop-color: var(--svg-color--b2767e, #B2767E);
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.ig120dbzq {
  stop-color: var(--svg-color--aea5b6, #AEA5B6);
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.j2tlhn_ku {
  d: path("M11.709 17.572c-.032-1.094.595-1.537.886-1.626l.668-.07v5.816c0 3.873 1.453 6.261 2.712 8.087c.063.09-.047.2-.138.138c-2.977-2.036-4.916-4.003-5.26-9.226a.203.203 0 0 1 .188-.215c.321-.02.606-.047.808-.066c.107-.01.188-.1.186-.206c-.011-.575-.023-1.659-.05-2.632");
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.jbvo0678w {
  fill: var(--svg-color--000, #000);
  d: path("M14.364 10.393a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .06-.235");
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.kv5l7-dbe {
  fill: var(--svg-color--000, #000);
  d: path("M17.708 10.393a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.06-.235");
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.l0zvedylt {
  d: path("m17.892 17.504l-1.813 1.251l1.795 1.259a.246.246 0 0 0 .388-.188c.041-.79.041-1.569.008-2.143a.239.239 0 0 0-.378-.18");
}

.l6okjl_yx {
  cx: 20.804px;
  cy: 10.659px;
  r: 0.995px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj1oyn2lk {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m12.265 7.94l.001-.002l.002-.001l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.062.241-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 1 1-.166 1.055a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.679-.823");
}

.ljpvikb1z {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.426 9.229c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

.lqnrqrgpd {
  cx: 16.004px;
  cy: 25.604px;
  r: 0.5px;
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.m8g60fwwb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.7 7.795c.43-.075 1.268-.054 1.848.398");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mijhkwbrl {
  cx: 20.804px;
  cy: 10.659px;
  r: 1.669px;
}

.mnhguyxxv {
  d: path("M14.41 20.306c-1.185-1.235-1.403-3.046-1.367-3.87h2.969l.035 2.222l-.773 1.52c-.148.308-.608.393-.863.128");
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.nfk4j0bpr {
  cx: 15.731px;
  cy: 25.877px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.ocbkol0bt {
  stop-color: var(--svg-color--9c684f, #9C684F);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohok_pr6g {
  fill: var(--svg-color--9c80b1, #9C80B1);
  fill-rule: evenodd;
  d: path("M12.889 16.71c-.037.824.18 2.636 1.367 3.87c.255.266.715.18.863-.128l.73-1.435l.731 1.435c.149.308.608.394.863.129c1.186-1.235 1.404-3.047 1.368-3.872z");
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.p-2t4fbpu {
  stop-color: var(--svg-color--905b44, #905B44);
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
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

.pv5xcyfwi {
  stop-color: var(--svg-color--a16969, #A16969);
  stop-opacity: 0;
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.q43d9p4nd {
  d: path("M19.014 10.275a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.qgls9_bhu {
  d: path("M11.242 18.37c-.03-1.012.55-1.42.819-1.503l.617-.065v5.373c0 3.575.239 4.662 2.733 7.12l.011.015c.047.083-.05.176-.132.12c-2.75-1.881-4.776-3.354-5.094-8.18a.19.19 0 0 1 .174-.198c.297-.019.56-.044.747-.06a.19.19 0 0 0 .171-.192c-.01-.53-.02-1.532-.046-2.43");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r_dde0bjs {
  d: path("M5.07 26.439c0-5.797 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.823 10.5 10.62v3.496H5.07z");
}

.rmrnz5b-v {
  stop-color: var(--svg-color--8d5a49, #8D5A49);
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.rvyek79ap {
  cx: 11.291px;
  cy: 10.659px;
  r: 0.995px;
}

.rwdag_b_k {
  stop-color: var(--svg-color--a16969, #A16969);
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sviot6mlz {
  d: path("m15.657 10.374l-.532 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.699c-.114-.376-.645-.376-.764 0");
}

.sweynhbyn {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.763 10.537l-.82 1.7c-.102.35.142.699.488.699h.737c.346 0 .59-.355.488-.7l-.498-1.699c-.107-.376-.283-.376-.395 0");
}

.syeyeqb6i {
  cx: 13.583px;
  cy: 9.881px;
  rx: 0.389px;
  ry: 0.197px;
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.t4cn-6bfi {
  d: path("M18.22 9.5a.892.892 0 0 1 .86 1.128h-1.724A.896.896 0 0 1 18.22 9.5");
}

.t52-74brh {
  cx: 16.004px;
  cy: 22.596px;
  r: 0.5px;
}

.t810qw9at {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.154 9.69c.063.084-.07.188-.22.3c-.152.114-.264.193-.327.108c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.tk1teelas {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m19.758 7.94l-.001-.002l-.002-.001l-.005-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.24-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 1 0 .167 1.055c.397-.063.716.01.933.096a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .679-.824");
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.tze17_bvh {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.657 10.374l-.532 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.699c-.114-.376-.645-.376-.764 0");
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.ubq14mb-s {
  stop-color: var(--svg-color--422131, #422131);
}

.uc5leibtb {
  stop-color: var(--svg-color--796ba6, #796BA6);
}

.udzp2zp0e {
  stop-color: var(--svg-color--4e3566, #4E3566);
}

.ur3-f2bxg {
  d: path("M18.767 16.086a10.3 10.3 0 0 0-2.337-.268h-.86q-1.194.002-2.312.262v5.422c0 4.175 1.065 5.972 2.654 8.433h.285c1.59-2.461 2.57-4.258 2.57-8.433z");
}

.uui3gyu-f {
  d: path("M18.154 9.69c.063.084-.07.188-.22.3c-.152.114-.264.193-.327.108c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.uw1oasn2r {
  cx: 20.804px;
  cy: 10.659px;
  r: 0.995px;
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.uyq2hibxk {
  d: path("M13.853 9.5a.892.892 0 0 0-.86 1.128h1.723a1 1 0 0 0 .033-.235a.9.9 0 0 0-.896-.893");
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v7_asvbup {
  d: path("M23.099 18.258a10.68 10.68 0 0 1 3.831 8.18v3.497H23.1z");
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
}

.vjj8ifxqk {
  stop-color: var(--svg-color--5e5962, #5E5962);
  stop-opacity: 0;
}

.vo3um_bur {
  stop-color: var(--svg-color--dcc1f4, #DCC1F4);
  stop-opacity: 0;
}

.voa0z2bgu {
  stop-color: var(--svg-color--47305d, #47305D);
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vws41pbfh {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.504l1.813 1.251l-1.795 1.259a.246.246 0 0 1-.389-.188c-.04-.79-.04-1.569-.007-2.143a.239.239 0 0 1 .378-.18");
}

.vx3rjpzqv {
  cx: 16.012px;
  cy: 18.724px;
  r: 0.809px;
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w16iu6xog {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.646 9.229c-.653 0-1.205.45-1.355 1.058c-.044.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.127");
}

.wasy5xbgj {
  d: path("m20.857 4.182l.43.213c.75.374 1.18 1.227 1.018 2.133l-.59 3.04c-.052.314-.26.525-.572.533h-.018s.054-.906.108-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.429-.533c-.644-.16-1.984-.427-3.915-.427s-3.272.267-3.916.427a.52.52 0 0 0-.429.533v.853c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.746c.054.587.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.108-.853.321-1.706 1.072-2.08l.43-.213c.268-.16.536-.373.804-.587l.965-1.013c.59-.533 1.449-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.805-.267 1.717-.053 2.36.533l.805.8c.214.267.482.427.804.587");
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wmjuo_j3y {
  stop-color: var(--svg-color--b57a7f, #B57A7F);
  stop-opacity: 0;
}

.ws4ma4lmo {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.677 13.416c.393.205.862.323 1.362.323c.504 0 .968-.118 1.361-.323h.001a.2.2 0 0 1 .241.04a.19.19 0 0 1 .021.241m-2.986-.28l2.945.252m-2.945-.253a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.253m3.207.028l-.041-.027m.041.027l-.041-.027m.041.027a1.94 1.94 0 0 1-1.624.868c-.682 0-1.28-.347-1.625-.867m3.208-.029a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.583-.846m-.042.028v.001l.042-.029m-.042.028l.042-.027");
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.wwn6slsot {
  d: path("M14.668 10.288c0-.289-.235-.48-.298-.539l-.288.279l.177.361z");
}

.wwxx-0ybr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.48 8.313c.327-.289 1.041-.593 1.927-.452");
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x64-dzbyg {
  width: 3.875px;
  height: 4.5px;
  x: 14.075px;
  y: 14.31px;
  rx: 1.938px;
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.yo1zipbes {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m20.857 4.182l.43.213c.75.374 1.18 1.227 1.018 2.133l-.59 3.04c-.052.314-.26.525-.572.533h-.018s.054-.906.108-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.429-.533c-.644-.16-1.984-.427-3.915-.427s-3.272.267-3.916.427a.52.52 0 0 0-.429.533v.853c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.746c.054.587.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.108-.853.321-1.706 1.072-2.08l.43-.213c.268-.16.536-.373.804-.587l.965-1.013c.59-.533 1.449-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.805-.267 1.717-.053 2.36.533l.805.8c.214.267.482.427.804.587");
}

.yod-f__vb {
  d: path("M17.598 20.306c1.186-1.235 1.404-3.046 1.367-3.87h-2.968l-.036 2.222l.774 1.52c.148.308.608.393.863.128");
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zr2l1ybki {
  d: path("m14.133 17.504l1.813 1.251l-1.795 1.259a.246.246 0 0 1-.389-.188c-.04-.79-.04-1.569-.007-2.143a.239.239 0 0 1 .378-.18");
}

.zynu2nm7a {
  stop-color: var(--svg-color--6b5977, #6B5977);
}

</style>
