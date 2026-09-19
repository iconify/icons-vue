<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iG8LmQb" class="cphzxcbvl"/></defs><g class="ft5dv1b6b"><path fill="url(#iqehyGd)" class="ypm46bm8d"/><path fill="url(#iCixeAd)" class="ypm46bm8d"/><path fill="url(#inZdjlb)" class="ypm46bm8d"/><path fill="url(#ihQGmVb)" class="ypm46bm8d"/><path fill="url(#iTWIrfc)" class="ypm46bm8d"/><path fill="url(#i002cjd)" class="wybie4bpu"/><path fill="url(#irLbDOc)" class="wybie4bpu"/><g filter="url(#iomqGse)"><path fill="url(#idvFVTc)" class="wbjjo4b2k"/><path fill="url(#iu9ReAb)" class="wbjjo4b2k"/></g><path fill="url(#idk9juB)" class="s798t3bdo"/><g filter="url(#idwQDSd)"><path fill="url(#i0wn0tp)" class="aoyotcbvb"/><path fill="url(#iHDpKIb)" class="aoyotcbvb"/></g><g filter="url(#iErRRrc)"><path clip-rule="evenodd" class="wx-tubcsu"/></g><path fill="url(#iIh8RSb)" class="ug9br4b0a"/><path fill="url(#itJNtOc)" class="ug9br4b0a"/><path fill="url(#i4RfRRb)" class="ug9br4b0a"/><path fill="url(#iIIz1ML)" class="ug9br4b0a"/><path fill="url(#i3jdcdd)" class="e3kzphwdf"/><path fill="url(#i3TyRZb)" class="e3kzphwdf"/><path fill="url(#irb69zB)" class="e3kzphwdf"/><path fill="url(#iB3a55c)" class="e3kzphwdf"/><g filter="url(#im6SUcd)"><path fill="url(#iTfuFHc)" class="r2caxb7hn"/></g><g filter="url(#ihQW2Oc)"><path fill="url(#iFtZZhb)" class="mkv8j1exr"/></g><path fill="url(#iQh2WWd)" class="mkv8j1exr"/><path fill="url(#irUY0bc)" class="mkv8j1exr"/><path fill="url(#inj2CWb)" class="mkv8j1exr"/><g filter="url(#i92PaCI)"><path class="zr5ogpbvn"/></g><g filter="url(#iq2L0Yd)"><circle class="ugl6544nh"/></g><g filter="url(#iFRgTpb)"><circle class="aumbfpbca"/></g><g filter="url(#i9M7l2b)"><circle fill="url(#i9uS03c)" class="mcmaclfsj"/></g><g filter="url(#iaA7ZOs)"><circle fill="url(#iGFZpab)" class="gwzuulbku"/></g><rect fill="url(#i6blC3c)" class="x320pei4a"/><rect fill="url(#i3XIqae)" class="x320pei4a"/><rect fill="url(#ivle0qk)" class="x320pei4a"/><rect fill="url(#iUURlIe)" class="x320pei4a"/><g filter="url(#iljxQxZ)"><path fill="url(#i6eH8Mc)" class="spwvj561f"/></g><path fill="url(#ih3jqge)" class="spwvj561f"/><g filter="url(#iC5L5Fc)"><path class="pm_hkebah"/><path fill="url(#ia1Odqd)" class="l3du-jb6t"/><path fill="url(#iWaORMy)" class="l3du-jb6t"/><path fill="url(#ircJB0c)" class="l3du-jb6t"/></g><g filter="url(#iOojNod)"><circle fill="url(#i1MQFgW)" class="grj3g7q3o"/><circle fill="url(#ikE8UFc)" class="grj3g7q3o"/></g><g filter="url(#iJdjnIb)"><circle fill="url(#iozNu0b)" class="yxd4887ur"/></g><g filter="url(#i8GhNIe)"><circle fill="url(#igSDi7k)" class="dx0tyrk8h"/></g><g filter="url(#i0VLtod)"><circle fill="url(#iBbs2Gc)" class="cjj96i06g"/><circle fill="url(#ic4byqb)" class="cjj96i06g"/></g><g filter="url(#itNzZqd)"><circle class="adn0yssle"/><circle fill="url(#iVZnUtd)" class="ns0erft0k"/><circle fill="url(#iHPDaVz)" class="ns0erft0k"/></g><g filter="url(#id9OFPc)"><path fill="url(#iVXhBPd)" class="q3zgr4vac"/><path fill="url(#i5kWfcD)" class="q3zgr4vac"/><path fill="url(#i06gQid)" class="q3zgr4vac"/></g><path fill="url(#iE65RTb)" class="kjn4_jnsl"/><path fill="url(#i0lKdxu)" class="kjn4_jnsl"/><path fill="url(#i4XdDIV)" class="kjn4_jnsl"/><g filter="url(#ikZHMeb)"><path fill="url(#iQqstRd)" class="xl5nf8bds"/></g><g filter="url(#inJBxKc)"><path class="bav2uy6kj"/><path fill="url(#iq37YiO)" class="xllem6_zr"/><path fill="url(#iGJusSb)" class="xllem6_zr"/><path fill="url(#ib3Q88c)" class="xllem6_zr"/><path fill="url(#ij3Nvdc)" class="xllem6_zr"/></g><g filter="url(#iT7iEzd)"><path class="zt__uob5o"/></g><g filter="url(#iqHovbb)"><path class="xk-b_ybqq"/><path fill="url(#iokjO1b)" class="o6kfmnf5w"/><path fill="url(#i44UIqE)" class="o6kfmnf5w"/><path fill="url(#iLp8NFd)" class="o6kfmnf5w"/><path fill="url(#iots2Ce)" class="o6kfmnf5w"/></g><g filter="url(#i4BSS1c)"><path fill="url(#iaFUTvc)" class="ulmwl8fuy"/></g><g filter="url(#i38YAFb)"><use href="#iG8LmQb"/><path stroke="url(#ilMZB4b)" class="wqdk7pb-r"/></g><use href="#iG8LmQb"/><g filter="url(#i2tSx9b)"><path class="d0i8811bb"/><path fill="url(#i10qhmd)" class="prjtzwj5e"/></g><g filter="url(#iVuFAoc)"><path class="hq13plbwg"/><path fill="url(#i7TA9jd)" class="lqr5hz3jg"/></g><path class="q26cybfno"/><path fill="url(#igwgXtd)" class="omlvb3bzi"/><path class="br0i98l6a"/><g filter="url(#iKxX1bd)"><path class="efxf0ibap"/><path fill="url(#i0JeNfb)" class="kthwevg6y"/></g><g filter="url(#ieeaa1b)"><path fill="url(#i59DDpc)" class="gff0pleob"/></g><path class="owbh--bna"/><path fill="url(#ivcRwsd)" class="wlzcu1-ya"/><path class="c3romf04r"/><g filter="url(#iBvQgxc)"><path fill="url(#ipjFSwe)" class="r25ed1bru"/></g><g filter="url(#ik3NKzb)"><ellipse transform="rotate(-27.914 13.581 9.912)" class="spsvpb1-x"/><ellipse fill="url(#ija98Td)" transform="rotate(-27.914 13.581 9.912)" class="d-xhlzyyh"/></g><g filter="url(#iOlG0sb)"><path stroke="url(#iOlSWNQ)" class="frcscsi9m"/></g><g filter="url(#ivjNzce)"><path stroke="url(#i9AV8rc)" class="k3ohkr-ai"/></g><g filter="url(#ibgN7Hp)"><path stroke="url(#ilMmfqc)" class="ksr8l1b0e"/></g><defs><radialGradient id="iqehyGd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.322)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="iCixeAd" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.768 10.816)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="inZdjlb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.233)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="i002cjd" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.245 2.613)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="irLbDOc" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.134)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="idvFVTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.39)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="idk9juB" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.545)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="i0wn0tp" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.097 22.513)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="iHDpKIb" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.347 13.028)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="itJNtOc" cx="0" cy="0" r="1" gradientTransform="rotate(-152.488 10.105 8.36)scale(1.16274 3.57827)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="i4RfRRb" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 -.22754 .55824 1.95507 13.236 18.654)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="i3TyRZb" cx="0" cy="0" r="1" gradientTransform="matrix(1.39062 .34376 -1.28105 5.18228 17.174 18.749)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="irb69zB" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .35156 -1.56152 -1.21452 17.276 19.389)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="iFtZZhb" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.074 11.859)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="iQh2WWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.91838 1.78314 -4.30906 -2.21931 13.135 16.27)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="irUY0bc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.94239 -.4885 0 11.747 16.328)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="inj2CWb" cx="0" cy="0" r="1" gradientTransform="matrix(.0919 1.7035 -.36222 .01954 10.658 20.623)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="i9uS03c" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.873 16.047)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iGFZpab" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.492 14.543)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="i3XIqae" cx="0" cy="0" r="1" gradientTransform="rotate(83.713 -1.77 17.015)scale(.92745 3.60872)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="ikki_bb0h"/><stop offset="1" class="rh_kjqbmn"/></radialGradient><radialGradient id="ivle0qk" cx="0" cy="0" r="1" gradientTransform="rotate(-25.475 46.055 -22.578)scale(.96227 1.70904)" gradientUnits="userSpaceOnUse"><stop class="v_iq93bvf"/><stop offset="1" class="qblrfac0m"/></radialGradient><radialGradient id="iUURlIe" cx="0" cy="0" r="1" gradientTransform="rotate(-154.262 11.033 6.96)scale(.82759 1.88786)" gradientUnits="userSpaceOnUse"><stop class="wu3upgb0d"/><stop offset="1" class="m-_zxbjbn"/></radialGradient><radialGradient id="i6eH8Mc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.737)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="ih3jqge" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.111)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="iWaORMy" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.44 6.858)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="ircJB0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 18.967)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="i1MQFgW" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.374 12.587)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="ikE8UFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.326)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="iozNu0b" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.615 10.69)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="ic4byqb" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.18 10.425)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="iVZnUtd" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.767 11.512)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iHPDaVz" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.81 10.69)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="i5kWfcD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.387 9.417)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="i06gQid" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37541 1.71044 0 13.825 9.552)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="i4XdDIV" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.43358 -11.4481 0 15.737 8.914)" gradientUnits="userSpaceOnUse"><stop offset=".594" class="ir08v0b5x"/><stop offset=".97" class="hc6kxkbxc"/></radialGradient><radialGradient id="iq37YiO" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.42495 .3845 20.389 6.58)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="iGJusSb" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.744 4.819)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="ib3Q88c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 16.039 2.08)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="ij3Nvdc" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.584 8.905)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iots2Ce" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.366 12.298)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="i10qhmd" cx="0" cy="0" r="1" gradientTransform="matrix(.10429 -.60384 1.7864 .30853 18.483 8.603)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="i7TA9jd" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.774 -3.614)scale(.61278 1.81296)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="igwgXtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.22 10.007)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i0JeNfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.991 10.092)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ivcRwsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.852 10.007)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ija98Td" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.817 -1.564)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iomqGse" width="4.081" height="11.683" x="5.07" y="18.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/></filter><filter id="idwQDSd" width="5.909" height="14.117" x="12.858" y="15.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/></filter><filter id="iErRRrc" width="7.13" height="5.229" x="12.285" y="16.087" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".3"/></filter><filter id="im6SUcd" width="7.239" height="14.645" x="9.195" y="15.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".5"/></filter><filter id="ihQW2Oc" width="5.917" height="14.31" x="10.326" y="15.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3328" result="effect2_innerShadow_4002_3328"/></filter><filter id="i92PaCI" width="6.504" height="14.261" x="15.345" y="15.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3328" result="effect2_innerShadow_4002_3328"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3328" result="effect3_innerShadow_4002_3328"/></filter><filter id="iq2L0Yd" width="2" height="2" x="14.731" y="24.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".25"/></filter><filter id="iFRgTpb" width="2" height="2" x="14.731" y="21.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".25"/></filter><filter id="i9M7l2b" width="1.05" height="1.05" x="15.504" y="25.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/></filter><filter id="iaA7ZOs" width="1.05" height="1.05" x="15.504" y="22.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/></filter><filter id="iljxQxZ" width="2.465" height="2.95" x="16.029" y="17.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3328" result="effect2_innerShadow_4002_3328"/></filter><filter id="iC5L5Fc" width="2.365" height="2.9" x="13.731" y="17.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/></filter><filter id="iOojNod" width="1.717" height="1.717" x="15.204" y="17.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/></filter><filter id="iJdjnIb" width="3.542" height="3.342" x="9.615" y="9.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/></filter><filter id="i8GhNIe" width="2.992" height="2.992" x="9.79" y="9.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".25"/></filter><filter id="i0VLtod" width="3.592" height="3.592" x="19.137" y="8.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/></filter><filter id="itNzZqd" width="2.992" height="2.992" x="19.313" y="9.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".25"/></filter><filter id="id9OFPc" width="10.383" height="12.189" x="10.876" y="5.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/></filter><filter id="ikZHMeb" width="8.25" height="7.07" x="14.209" y="3.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation="1"/></filter><filter id="inJBxKc" width="12.614" height="8.551" x="9.732" y="1.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/></filter><filter id="iT7iEzd" width="3.262" height="4.184" x="14.169" y="9.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".375"/></filter><filter id="iqHovbb" width="2.379" height="3.184" x="14.849" y="9.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".125"/></filter><filter id="i4BSS1c" width="2.379" height="3.184" x="14.832" y="9.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".125"/></filter><filter id="i38YAFb" width="3.621" height="1.474" x="14.228" y="13.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".05"/></filter><filter id="i2tSx9b" width="2.982" height="1.874" x="17.222" y="7.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/></filter><filter id="iVuFAoc" width="2.982" height="1.874" x="12.069" y="7.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3328"/></filter><filter id="iKxX1bd" width=".787" height=".697" x="17.485" y="9.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".05"/></filter><filter id="ieeaa1b" width=".892" height=".914" x="18.326" y="9.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".1"/></filter><filter id="iBvQgxc" width=".987" height="1.041" x="13.88" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".1"/></filter><filter id="ik3NKzb" width=".914" height=".705" x="13.124" y="9.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".05"/></filter><filter id="iOlG0sb" width="3.101" height="1.681" x="17.076" y="7.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".25"/></filter><filter id="ivjNzce" width="3.179" height="1.739" x="11.851" y="7.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".25"/></filter><filter id="ibgN7Hp" width="1.008" height="2.271" x="10.868" y="5.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3328" stdDeviation=".125"/></filter><linearGradient id="ihQGmVb" x1="23.131" x2="22.971" y1="29.912" y2="29.912" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="iTWIrfc" x1="8.858" x2="9.061" y1="29.912" y2="29.912" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="iu9ReAb" x1="9.19" x2="7.596" y1="29.919" y2="29.919" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="iIh8RSb" x1="14.705" x2="13.268" y1="19.983" y2="16.858" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="zynu2nm7a"/></linearGradient><linearGradient id="iIIz1ML" x1="15.518" x2="15.209" y1="20.061" y2="19.944" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="i3jdcdd" x1="16.799" x2="18.471" y1="19.998" y2="17.123" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="ig120dbzq"/></linearGradient><linearGradient id="iB3a55c" x1="16.486" x2="16.713" y1="19.799" y2="19.709" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="iTfuFHc" x1="12.815" x2="12.815" y1="16.779" y2="29.424" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="i6blC3c" x1="17.033" x2="14.649" y1="18.389" y2="17.821" gradientUnits="userSpaceOnUse"><stop class="mu_8u8bza"/><stop offset="1" class="k65ymqbbb"/></linearGradient><linearGradient id="ia1Odqd" x1="15.205" x2="14.838" y1="19.436" y2="18.982" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="igSDi7k" x1="11.286" x2="10.645" y1="10.969" y2="10.969" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iBbs2Gc" x1="21.896" x2="21.076" y1="9.598" y2="12.136" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iVXhBPd" x1="20.078" x2="12.434" y1="11.08" y2="12.219" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iE65RTb" x1="10.638" x2="12.521" y1="13.778" y2="13.711" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="i0lKdxu" x1="20.907" x2="19.851" y1="12.94" y2="12.839" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iQqstRd" x1="15.507" x2="23.658" y1="8.092" y2="5.174" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iokjO1b" x1="15.174" x2="16.113" y1="11.74" y2="11.74" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="i44UIqE" x1="16.978" x2="15.951" y1="12.063" y2="12.048" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iLp8NFd" x1="16.233" x2="16.233" y1="12.806" y2="12.232" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iaFUTvc" x1="16.021" x2="16.021" y1="9.89" y2="10.956" gradientUnits="userSpaceOnUse"><stop class="u9tzj8pul"/><stop offset="1" class="xws_kqc-j"/></linearGradient><linearGradient id="ilMZB4b" x1="15.001" x2="15.436" y1="14.422" y2="13.734" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="i59DDpc" x1="18.998" x2="18.684" y1="10.061" y2="10.255" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipjFSwe" x1="14.597" x2="14.283" y1="10.061" y2="10.255" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iOlSWNQ" x1="19.014" x2="18.593" y1="7.92" y2="7.06" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="i9AV8rc" x1="13.704" x2="12.514" y1="7.792" y2="7.293" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="ilMmfqc" x1="11.372" x2="11.372" y1="5.775" y2="7.935" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-in-tuxedo-medium-dark" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.adn0yssle {
  cx: 20.809px;
  cy: 10.69px;
  r: 0.996px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.aoyotcbvb {
  d: path("M18.767 16.063a10.3 10.3 0 0 0-2.337-.267h-.86c-.795 0-1.568.09-2.312.261v5.422c0 4.175 1.065 5.972 2.654 8.433h.285c1.59-2.46 2.57-4.258 2.57-8.433z");
}

.aumbfpbca {
  cx: 15.731px;
  cy: 22.706px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
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

.bav2uy6kj {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m20.862 4.206l.43.214c.751.374 1.18 1.228 1.02 2.135l-.59 3.043c-.053.314-.261.526-.573.534h-.018s.053-.908.107-1.441c.044-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.855v-.854c0-.267-.215-.48-.43-.533c-.644-.16-1.986-.428-3.92-.428c-1.932 0-3.274.267-3.919.428a.52.52 0 0 0-.43.533v.854c0 .32-.107.641-.375.855l-.161.16c-.215.16-.322.48-.322.747c.054.587.107 1.442.107 1.442l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.321-1.708 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.014c.591-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.267 1.718-.054 2.362.533l.806.801c.215.267.483.427.805.587");
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
}

.br0i98l6a {
  fill: var(--svg-color--000, #000);
  d: path("M17.71 10.423a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.06-.236");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c3romf04r {
  fill: var(--svg-color--000, #000);
  d: path("M14.362 10.423a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.747h.905c.037-.07.06-.15.06-.236");
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.cjj96i06g {
  cx: 20.808px;
  cy: 10.69px;
  r: 1.671px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm2l5-bra {
  stop-color: var(--svg-color--554181, #554181);
}

.cof-_sb7w {
  stop-color: var(--svg-color--a487bb, #A487BB);
}

.cosmi4y3y {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
}

.cphzxcbvl {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M16.039 13.823c-.508 0-.986-.12-1.387-.328c-.137-.07-.284.084-.198.209c.335.508.92.846 1.585.846s1.249-.338 1.584-.846c.086-.13-.06-.28-.198-.21a3 3 0 0 1-1.386.33");
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.cyzx27bkq {
  stop-color: var(--svg-color--978394, #978394);
}

.d-xhlzyyh {
  cx: 13.581px;
  cy: 9.912px;
  rx: 0.39px;
  ry: 0.197px;
}

.d0i8811bb {
  fill: var(--svg-color--352827, #352827);
  d: path("m19.762 7.968l-.002-.001l-.001-.002l-.005-.004l-.012-.01l-.036-.026a2.6 2.6 0 0 0-.54-.291a2.84 2.84 0 0 0-1.493-.16a.534.534 0 0 0 .167 1.056c.398-.063.716.01.934.097a1.5 1.5 0 0 1 .309.165a.534.534 0 0 0 .679-.824");
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.dx0tyrk8h {
  cx: 11.286px;
  cy: 10.69px;
  r: 0.996px;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3kzphwdf {
  d: path("M17.598 20.283c1.186-1.235 1.404-3.046 1.367-3.87h-2.968l-.036 2.222l.774 1.52c.148.308.608.394.863.128");
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.efxf0ibap {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.156 9.719c.064.085-.07.189-.22.302c-.152.113-.264.193-.328.107c-.063-.085.008-.245.159-.358s.325-.136.389-.051");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
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

.frcscsi9m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.7 7.823c.431-.075 1.27-.054 1.852.398");
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gff0pleob {
  d: path("M19.017 10.306a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.grj3g7q3o {
  cx: 16.012px;
  cy: 18.701px;
  r: 0.809px;
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gwzuulbku {
  cx: 16.004px;
  cy: 22.573px;
  r: 0.5px;
}

.hc6kxkbxc {
  stop-color: var(--svg-color--603847, #603847);
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hq13plbwg {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.262 7.968l.001-.001l.002-.002l.005-.004l.011-.01a2 2 0 0 1 .155-.107c.1-.062.242-.14.42-.21a2.84 2.84 0 0 1 1.495-.16a.534.534 0 1 1-.167 1.056a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.68-.824");
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

.ikki_bb0h {
  stop-color: var(--svg-color--5c313e, #5C313E);
}

.ir08v0b5x {
  stop-color: var(--svg-color--784756, #784756);
  stop-opacity: 0;
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.k3ohkr-ai {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.476 8.342c.328-.29 1.043-.594 1.93-.453");
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.k65ymqbbb {
  stop-color: var(--svg-color--4f2b2b, #4F2B2B);
}

.kjn4_jnsl {
  d: path("M10.876 8.637c0-.267.107-.587.322-.747l.16-.16c.27-.214.377-.534.377-.855v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.054.429.267.429.534v.854c0 .32.16.641.375.855c.503.352.472.545.43.96a47 47 0 0 0-.107 1.442h.018l-.266 3.962c-.161 1.771-1.554 3.006-3.214 3.006h-3.213c-1.714 0-3.053-1.235-3.214-3.006c-.14-1.818-.2-3.642-.366-5.457");
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.ksr8l1b0e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.502 5.874v.899c-.008.148-.07.481-.259.622");
}

.kthwevg6y {
  d: path("M18.156 9.719c.064.085-.07.189-.22.302c-.152.113-.264.193-.328.107c-.063-.085.008-.245.159-.358s.325-.136.389-.051");
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l3du-jb6t {
  d: path("m14.133 17.481l1.813 1.251l-1.795 1.259a.246.246 0 0 1-.389-.187c-.04-.792-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.179");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lqr5hz3jg {
  d: path("m12.262 7.968l.001-.001l.002-.002l.005-.004l.011-.01a2 2 0 0 1 .155-.107c.1-.062.242-.14.42-.21a2.84 2.84 0 0 1 1.495-.16a.534.534 0 1 1-.167 1.056a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.68-.824");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m-_zxbjbn {
  stop-color: var(--svg-color--75514f, #75514F);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcmaclfsj {
  cx: 16.004px;
  cy: 25.581px;
  r: 0.5px;
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mkv8j1exr {
  d: path("M11.709 17.55c-.032-1.095.595-1.538.886-1.626l.668-.07v5.815c0 3.873 1.453 6.261 2.712 8.087c.063.091-.047.201-.138.139c-2.977-2.037-4.916-4.004-5.26-9.227a.203.203 0 0 1 .188-.215c.321-.02.606-.047.808-.066c.107-.01.188-.1.186-.206c-.011-.575-.023-1.659-.05-2.632");
}

.mu_8u8bza {
  stop-color: var(--svg-color--5b3733, #5B3733);
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.ns0erft0k {
  cx: 20.809px;
  cy: 10.69px;
  r: 0.996px;
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o6kfmnf5w {
  d: path("m15.656 10.405l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.377-.646-.377-.765 0");
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.omlvb3bzi {
  d: path("M18.222 9.53a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.owbh--bna {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.643 9.258c-.653 0-1.205.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.373-1.129");
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pm_hkebah {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.481l1.813 1.251l-1.795 1.259a.246.246 0 0 1-.389-.187c-.04-.792-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.179");
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.prjtzwj5e {
  d: path("m19.762 7.968l-.002-.001l-.001-.002l-.005-.004l-.012-.01l-.036-.026a2.6 2.6 0 0 0-.54-.291a2.84 2.84 0 0 0-1.493-.16a.534.534 0 0 0 .167 1.056c.398-.063.716.01.934.097a1.5 1.5 0 0 1 .309.165a.534.534 0 0 0 .679-.824");
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.q26cybfno {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.429 9.258c.653 0 1.205.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q3zgr4vac {
  d: path("m10.934 10.077l.05.001s-.055-.854-.108-1.44c0-.268.107-.588.322-.748l.16-.16c.27-.214.377-.534.377-.855v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.054.429.267.429.534v.854c0 .32.16.641.375.855c.503.352.472.545.43.96a47 47 0 0 0-.107 1.442h.018l-.266 3.962c-.161 1.771-1.554 3.006-3.214 3.006h-3.213c-1.714 0-3.053-1.235-3.214-3.006z");
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qblrfac0m {
  stop-color: var(--svg-color--4b2f32, #4B2F32);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r25ed1bru {
  d: path("M14.666 10.318c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.r2caxb7hn {
  d: path("M11.242 18.347c-.03-1.011.55-1.42.819-1.503l.617-.065v5.373c0 3.575.239 4.662 2.733 7.12l.011.016c.047.082-.05.175-.132.12c-2.75-1.882-4.776-3.355-5.094-8.18a.19.19 0 0 1 .174-.199c.297-.019.56-.044.747-.06a.19.19 0 0 0 .171-.191c-.01-.531-.02-1.533-.046-2.431");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rh_kjqbmn {
  stop-color: var(--svg-color--5c313e, #5C313E);
  stop-opacity: 0;
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.s798t3bdo {
  d: path("M8.901 18.236a10.68 10.68 0 0 0-3.831 8.18v3.497H8.9z");
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.spsvpb1-x {
  cx: 13.581px;
  cy: 9.912px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.spwvj561f {
  d: path("m17.892 17.481l-1.813 1.251l1.795 1.259a.246.246 0 0 0 .388-.187c.041-.792.041-1.57.008-2.144a.239.239 0 0 0-.378-.179");
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.u9tzj8pul {
  stop-color: var(--svg-color--895f56, #895F56);
}

.ubq14mb-s {
  stop-color: var(--svg-color--422131, #422131);
}

.uc5leibtb {
  stop-color: var(--svg-color--796ba6, #796BA6);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.udzp2zp0e {
  stop-color: var(--svg-color--4e3566, #4E3566);
}

.ug9br4b0a {
  d: path("M14.41 20.283c-1.185-1.235-1.403-3.046-1.367-3.87h2.969l.035 2.222l-.773 1.52c-.148.308-.608.394-.863.128");
}

.ugl6544nh {
  cx: 15.731px;
  cy: 25.855px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.ulmwl8fuy {
  d: path("m15.639 10.173l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.v_iq93bvf {
  stop-color: var(--svg-color--4b2f32, #4B2F32);
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
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

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wbjjo4b2k {
  d: path("M8.901 18.236a10.69 10.69 0 0 0-3.831 8.185v3.498H8.9z");
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wlzcu1-ya {
  d: path("M13.85 9.53a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .033-.236a.9.9 0 0 0-.898-.893");
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wqdk7pb-r {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.039 13.823c-.508 0-.986-.12-1.387-.328c-.137-.07-.284.084-.198.209c.335.508.92.846 1.585.846s1.249-.338 1.584-.846c.086-.13-.06-.28-.198-.21a3 3 0 0 1-1.386.33Z");
}

.wu3upgb0d {
  stop-color: var(--svg-color--75514f, #75514F);
}

.wx-tubcsu {
  fill: var(--svg-color--9c80b1, #9C80B1);
  fill-rule: evenodd;
  d: path("M12.889 16.687c-.037.825.18 2.636 1.367 3.87c.255.266.715.18.863-.128l.73-1.435l.731 1.435c.149.309.608.394.863.129c1.186-1.235 1.404-3.046 1.368-3.871z");
}

.wybie4bpu {
  d: path("M23.099 18.236a10.68 10.68 0 0 1 3.831 8.18v3.497H23.1z");
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x320pei4a {
  width: 3.875px;
  height: 4.5px;
  x: 14.075px;
  y: 14.287px;
  rx: 1.938px;
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xk-b_ybqq {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.656 10.405l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.377-.646-.377-.765 0");
}

.xl5nf8bds {
  d: path("m20.006 5.06l-3.08 1.027a1.048 1.048 0 0 0 .47 2.034l3.063-.41z");
}

.xllem6_zr {
  d: path("m20.862 4.206l.43.214c.751.374 1.18 1.228 1.02 2.135l-.59 3.043c-.053.314-.261.526-.573.534h-.018s.053-.908.107-1.441c.044-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.855v-.854c0-.267-.215-.48-.43-.533c-.644-.16-1.986-.428-3.92-.428c-1.932 0-3.274.267-3.919.428a.52.52 0 0 0-.43.533v.854c0 .32-.107.641-.375.855l-.161.16c-.215.16-.322.48-.322.747c.054.587.107 1.442.107 1.442l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.321-1.708 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.014c.591-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.267 1.718-.054 2.362.533l.806.801c.215.267.483.427.805.587");
}

.xws_kqc-j {
  stop-color: var(--svg-color--895f56, #895F56);
  stop-opacity: 0;
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ypm46bm8d {
  d: path("M5.07 26.416c0-5.796 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.824 10.5 10.62v3.496H5.07z");
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.yxd4887ur {
  cx: 11.286px;
  cy: 10.69px;
  r: 1.671px;
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zr5ogpbvn {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.316 17.55c.031-1.095-.595-1.538-.887-1.626l-.668-.07v5.815c0 3.873-1.388 6.264-2.648 8.089c-.062.091.047.201.139.139c2.976-2.037 4.851-4.006 5.196-9.229a.203.203 0 0 0-.188-.215c-.321-.02-.607-.047-.809-.066a.204.204 0 0 1-.185-.206c.011-.575.022-1.659.05-2.632");
}

.zt__uob5o {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.763 10.568l-.821 1.701c-.102.35.143.7.489.7h.738c.346 0 .59-.355.488-.7l-.499-1.701c-.107-.377-.283-.377-.395 0");
}

.zynu2nm7a {
  stop-color: var(--svg-color--6b5977, #6B5977);
}

</style>
