<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iBLbR0c)"><path fill="url(#iErP9He)" class="p3f63zb1c"/><path fill="url(#iDGGgdc)" class="p3f63zb1c"/></g><g filter="url(#iEBC17o)"><path class="l85u8ibfx"/></g><path fill="url(#imdrOid)" class="d804zky3u"/><g filter="url(#ikyTbAd)"><path fill="url(#iOxYU2b)" class="m4pcayl4x"/></g><path fill="url(#iRZdv7s)" class="lby3v6ati"/><path fill="url(#ii1khxe)" class="lby3v6ati"/><g filter="url(#ip33ySb)"><path fill="url(#iFgDB4b)" class="qdgeq05dx"/><path fill="url(#iZIqq2d)" class="qdgeq05dx"/></g><g filter="url(#i4TK9Md)"><path fill="url(#i1cvDBD)" class="rvgjtg4fi"/><path fill="url(#iDxz2Ld)" class="rvgjtg4fi"/><path fill="url(#iqQ830c)" class="rvgjtg4fi"/><path fill="url(#iV8mwie)" class="rvgjtg4fi"/><path fill="url(#i0PlaYd)" class="rvgjtg4fi"/><path fill="url(#i3fWf4d)" class="rvgjtg4fi"/><path fill="url(#iuQ0Edb)" class="rvgjtg4fi"/><path fill="url(#i8tOShe)" class="rvgjtg4fi"/></g><path fill="url(#iVSNocb)" class="rvgjtg4fi"/><path fill="url(#iE4ja3b)" class="rvgjtg4fi"/><path fill="url(#id8YB5z)" class="rvgjtg4fi"/><path fill="url(#ijGhmSb)" class="rvgjtg4fi"/><g filter="url(#iw7K3ug)"><path stroke="url(#iMhaxNb)" class="pzjsfkxkt"/></g><g filter="url(#iBofRPe)"><path stroke="url(#iUUCLJd)" class="nl2u64eej"/></g><g filter="url(#iCMeVye)"><path stroke="url(#idVwZGb)" class="y1syambbk"/></g><g filter="url(#iA8eDNc)"><path class="mrsd5vi6x"/></g><g filter="url(#ivGgnJc)"><path class="eywjsqb5l"/><path fill="url(#iO96kgc)" class="wliqnbp1k"/><path fill="url(#iPbL8Xb)" class="wliqnbp1k"/><path fill="url(#iyPwIbP)" class="wliqnbp1k"/></g><g filter="url(#infbYPb)"><path fill="url(#iIZ8Dmp)" class="gjbve0bnv"/></g><path fill="url(#i9UNGJb)" class="o87uryobz"/><g filter="url(#ilS1Orc)"><path fill="url(#iiEsmFd)" class="s4f5kgi2d"/></g><g filter="url(#i1WzQGe)"><path fill="url(#iiuil9d)" class="xyq99dbsm"/></g><g filter="url(#iiAibSO)"><path fill="url(#iyL1vcd)" class="f8wxf-tdu"/></g><path fill="url(#ibm8jAb)" class="f8wxf-tdu"/><path fill="url(#iTozLNb)" class="f8wxf-tdu"/><path fill="url(#iP4iEdd)" class="f8wxf-tdu"/><path fill="url(#id3avud)" class="f8wxf-tdu"/><g filter="url(#iq7TUgb)"><path class="dbiyjrp-x"/></g><path class="cd06k8bas"/><path fill="url(#i1pRTic)" class="vckbn7bgk"/><path fill="url(#itE4EEc)" class="vckbn7bgk"/><path fill="url(#ia36kNb)" class="vckbn7bgk"/><path fill="url(#ioaRNOd)" class="vckbn7bgk"/><path fill="url(#ikAGyNc)" class="vckbn7bgk"/><g filter="url(#iarZ9Ec)"><path stroke="url(#itKhjLl)" class="dg-q56b3p"/></g><path class="gbs005z-w"/><g filter="url(#iYWQP4b)"><path class="y-i88cmqv"/></g><g filter="url(#in5wpDd)"><path class="kcaiikrsb"/></g><g filter="url(#iJTgIWb)"><path fill="url(#iRE1yCb)" class="o_h0y6b3p"/></g><g filter="url(#ijJwNDe)"><path fill="url(#i24rJMd)" clip-rule="evenodd" class="qohe4djmm"/></g><path class="vlytvntgs"/><path fill="url(#i5YbaKe)" class="ay_phd11e"/><path class="ro7svqvjx"/><g filter="url(#iviDgJc)"><path class="zj8l1oboz"/><path fill="url(#i2LqhIf)" class="co87qobft"/></g><g filter="url(#iDDryGd)"><path fill="url(#idDVUGc)" class="nud75cb3r"/></g><path class="sdf9tobyx"/><path fill="url(#imJspBd)" class="axurn_5zl"/><path class="eiflvuzgd"/><g filter="url(#iRnRUgc)"><path fill="url(#i1cZLfc)" class="rlu2hsbuy"/></g><g filter="url(#iqUMUZw)"><ellipse transform="rotate(-27.914 15.96 6.811)" class="c9hto3rdo"/><ellipse fill="url(#iNxWnMx)" transform="rotate(-27.914 15.96 6.811)" class="nk8pt8bvw"/></g><g filter="url(#iGGU5Ke)"><path class="idokdtbun"/></g><g filter="url(#ipPMy0d)"><path class="av94dpbjb"/></g><g filter="url(#i1jS15d)"><path fill="url(#iXDLQKe)" class="q2m7q-bcq"/></g><g filter="url(#ioldmmb)"><path fill="url(#ihxD5Ic)" class="f32er0yca"/></g><g filter="url(#iLhFsNc)"><path fill="url(#ikoqwOd)" class="f32er0yca"/><path fill="url(#idoXnUd)" class="f32er0yca"/></g><g filter="url(#i0zyNWc)"><path class="iorvdubip"/><path fill="url(#ibrXHpJ)" class="inz52_phe"/><path fill="url(#iII9RCc)" class="inz52_phe"/><path fill="url(#ihEBcfc)" class="inz52_phe"/></g><g filter="url(#iqHrkEF)"><path fill="url(#iiovjoc)" class="p6977lbwx"/></g><g filter="url(#i4rBUCc)"><path fill="url(#iRFs2qe)" class="t7nle4uwx"/></g><g filter="url(#iItCWDd)"><path stroke="url(#iuYQKFc)" class="vpkiteigl"/></g><defs><radialGradient id="iErP9He" cx="0" cy="0" r="1" gradientTransform="matrix(-2.56252 4.21874 -9.37274 -5.69311 20.977 3.26)" gradientUnits="userSpaceOnUse"><stop class="dbrr_ge-k"/><stop offset="1" class="whopo0y2h"/></radialGradient><radialGradient id="iDGGgdc" cx="0" cy="0" r="1" gradientTransform="rotate(167.39 10.728 6.08)scale(1.76333 1.96679)" gradientUnits="userSpaceOnUse"><stop class="f88wzbb7k"/><stop offset="1" class="w4rlmo2dn"/></radialGradient><radialGradient id="imdrOid" cx="0" cy="0" r="1" gradientTransform="rotate(-17.313 87.674 -23.135)scale(13.0953 16.0195)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="iOxYU2b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 22.702 20.572)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="iRZdv7s" cx="0" cy="0" r="1" gradientTransform="matrix(.67968 -.9375 .55678 .40367 6.762 16.9)" gradientUnits="userSpaceOnUse"><stop class="bcouvbcoc"/><stop offset="1" class="gsmej6bma"/></radialGradient><radialGradient id="iFgDB4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.95313 .90937 -.4986 -.5226 25.737 7.283)" gradientUnits="userSpaceOnUse"><stop class="ko7--3b4k"/><stop offset=".611" class="qz1n7cnnp"/></radialGradient><radialGradient id="iZIqq2d" cx="0" cy="0" r="1" gradientTransform="matrix(-.04224 -.75 .57465 -.03236 25.182 8.712)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="m3rlai98t"/><stop offset="1" class="mrehmk1hy"/></radialGradient><radialGradient id="i1cvDBD" cx="0" cy="0" r="1" gradientTransform="rotate(159 8.58 8.058)scale(4.71973 6.48913)" gradientUnits="userSpaceOnUse"><stop class="yywcf0gub"/><stop offset="1" class="m2_uv2a4m"/></radialGradient><radialGradient id="iqQ830c" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 0 0 4.11135 14.48 17.197)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="vx5g9qbgu"/><stop offset="1" class="sim-rnb6d"/></radialGradient><radialGradient id="iV8mwie" cx="0" cy="0" r="1" gradientTransform="rotate(-124.509 15.769 2.034)scale(5.76427 2.15458)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="z-iy1qoxq"/><stop offset="1" class="wyqz88nbk"/></radialGradient><radialGradient id="i0PlaYd" cx="0" cy="0" r="1" gradientTransform="matrix(1.14062 3.15625 -1.12664 .40715 23.76 10.838)" gradientUnits="userSpaceOnUse"><stop class="nkfqvvjuz"/><stop offset="1" class="xkh31bbow"/></radialGradient><radialGradient id="i3fWf4d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29421 -1.39953 1.4063 -1.30048 16 13.76)" gradientUnits="userSpaceOnUse"><stop class="m_tl88bid"/><stop offset="1" class="bjbtwzbgn"/></radialGradient><radialGradient id="iuQ0Edb" cx="0" cy="0" r="1" gradientTransform="matrix(-.49998 -1.89063 3.41696 -.90363 24.964 15.493)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="qbkpv6z7a"/><stop offset="1" class="hwzcsbbxl"/></radialGradient><radialGradient id="i8tOShe" cx="0" cy="0" r="1" gradientTransform="rotate(155.579 7.477 6.669)scale(3.17465 2.03239)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="huqdsg6wj"/><stop offset="1" class="ve4hytcdg"/></radialGradient><radialGradient id="iVSNocb" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 0 0 4.60938 14.12 16.9)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="tg9xefb7i"/><stop offset="1" class="w9t1efbqg"/></radialGradient><radialGradient id="id8YB5z" cx="0" cy="0" r="1" gradientTransform="rotate(133.468 3.63 10.375)scale(2.48567 1.45387)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="u2z2j8k6b"/><stop offset="1" class="m7soyj5jb"/><stop offset="1" class="hsx8ilbej"/></radialGradient><radialGradient id="ijGhmSb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78126 1.58593 -.17358 -.19496 13.002 15.384)" gradientUnits="userSpaceOnUse"><stop offset=".144" class="o93elw41z"/><stop offset="1" class="g4s3nac-z"/></radialGradient><radialGradient id="iO96kgc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17187 -1.23438 .5687 -.5399 16.852 14.384)" gradientUnits="userSpaceOnUse"><stop class="rd_1vj1uu"/><stop offset="1" class="w4wjacb9v"/></radialGradient><radialGradient id="iPbL8Xb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.26562 -.57617 0 17.413 13.306)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="dsu9eguof"/><stop offset="1" class="dogwq2blg"/></radialGradient><radialGradient id="iyPwIbP" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4707 1.41406 -.31529 -.32792 21.136 13.15)" gradientUnits="userSpaceOnUse"><stop class="gwqfskb8v"/><stop offset="1" class="n7-hw2b3h"/></radialGradient><radialGradient id="i9UNGJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.66406 .65625 -.45034 -.4557 20.971 6.806)" gradientUnits="userSpaceOnUse"><stop class="kv4_lccbf"/><stop offset="1" class="a0kmoyxfg"/></radialGradient><radialGradient id="iiEsmFd" cx="0" cy="0" r="1" gradientTransform="rotate(90 6.521 13.742)scale(.63475)" gradientUnits="userSpaceOnUse"><stop class="kn22s4txk"/><stop offset="1" class="y4inpcddo"/></radialGradient><radialGradient id="iiuil9d" cx="0" cy="0" r="1" gradientTransform="rotate(106.949 4.602 8.875)scale(.85756)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="h9hedgb-i"/><stop offset="1" class="fcfe9dfwi"/></radialGradient><radialGradient id="iyL1vcd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.03126 1.72424 -2.40572 -4.22933 18.573 7.535)" gradientUnits="userSpaceOnUse"><stop class="t-07fdchd"/><stop offset="1" class="jk372--tq"/></radialGradient><radialGradient id="ibm8jAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.48957 -5.92174 0 17.41 6.26)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="s3-919bdo"/><stop offset=".999" class="zrq_ottju"/></radialGradient><radialGradient id="iTozLNb" cx="0" cy="0" r="1" gradientTransform="rotate(146.659 9.248 5.584)scale(1.42145 2.26202)" gradientUnits="userSpaceOnUse"><stop class="q6mg8ibon"/><stop offset="1" class="m4wre3b4e"/></radialGradient><radialGradient id="iP4iEdd" cx="0" cy="0" r="1" gradientTransform="matrix(.5 .53125 -2.03167 1.91217 15.542 4.478)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="y6gj-0bkn"/><stop offset="1" class="ta7v5vpcw"/></radialGradient><radialGradient id="id3avud" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72875 1.74927 -1.1218 -1.10864 19.052 5.182)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="gr1si2b-x"/><stop offset="1" class="s0bi7iy1o"/></radialGradient><radialGradient id="itE4EEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.47656 0 0 -.14893 17.659 8.11)" gradientUnits="userSpaceOnUse"><stop class="cn11jacls"/><stop offset="1" class="mkrjvhq2k"/></radialGradient><radialGradient id="ia36kNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.39263 1.04529 0 17.41 8.425)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="chywufrfu"/><stop offset="1" class="u7harwjoq"/></radialGradient><radialGradient id="i5YbaKe" cx="0" cy="0" r="1" gradientTransform="rotate(124.592 7.723 8.39)scale(.55383 .87854)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="chm_zob8h"/><stop offset="1" class="w_bi9zfnz"/></radialGradient><radialGradient id="i2LqhIf" cx="0" cy="0" r="1" gradientTransform="matrix(-.13647 -.17586 .24212 -.18789 18.564 6.918)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imJspBd" cx="0" cy="0" r="1" gradientTransform="rotate(124.592 6.433 7.713)scale(.55383 .87855)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="chm_zob8h"/><stop offset="1" class="w_bi9zfnz"/></radialGradient><radialGradient id="iNxWnMx" cx="0" cy="0" r="1" gradientTransform="matrix(-.00455 -.29073 .34947 -.00547 15.95 6.997)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iXDLQKe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.98437 1.60938 -.62216 -.76713 15.589 4.087)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="dgweptk-f"/><stop offset=".77" class="nhe36etun"/></radialGradient><radialGradient id="ihxD5Ic" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46875 .08792 -.04263 -1.68195 19.76 4.138)" gradientUnits="userSpaceOnUse"><stop class="p224_4b9x"/><stop offset="1" class="umf8cbcnm"/></radialGradient><radialGradient id="ikoqwOd" cx="0" cy="0" r="1" gradientTransform="matrix(.42188 -2.92187 6.42687 .92795 16.495 5.337)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="rlatyn0wa"/><stop offset="1" class="x_nmsobjl"/></radialGradient><radialGradient id="idoXnUd" cx="0" cy="0" r="1" gradientTransform="rotate(-169.129 10.228 1.467)scale(2.40249 .68451)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="xz2vy3rji"/><stop offset="1" class="bw1rz3b-f"/></radialGradient><radialGradient id="ibrXHpJ" cx="0" cy="0" r="1" gradientTransform="matrix(.20313 1.2422 -.5655 .09247 21.027 3.806)" gradientUnits="userSpaceOnUse"><stop class="mk_tesa_t"/><stop offset="1" class="hj78b9cjo"/></radialGradient><radialGradient id="iII9RCc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11657 .3125 -.09737 -.3479 22.346 4.681)" gradientUnits="userSpaceOnUse"><stop class="o5bua8boy"/><stop offset="1" class="rz_b8bbbi"/></radialGradient><radialGradient id="ihEBcfc" cx="0" cy="0" r="1" gradientTransform="matrix(-.59375 -1.38766 .70345 -.301 21.932 6.494)" gradientUnits="userSpaceOnUse"><stop class="o0h7y_boi"/><stop offset="1" class="s9ajizb_e"/></radialGradient><filter id="iBLbR0c" width="14.674" height="15.298" x="7.851" y="1.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.184314 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1294"/></filter><filter id="iEBC17o" width="16.97" height="13.626" x="7.639" y="16.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1294"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1294" result="effect2_innerShadow_4002_1294"/></filter><filter id="ikyTbAd" width="8.803" height="12.453" x="15.083" y="15.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".5"/></filter><filter id="ip33ySb" width="1.41" height="1.949" x="24.485" y="7.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.243137 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1294"/></filter><filter id="i4TK9Md" width="20.634" height="10.708" x="5.683" y="7.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.258824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1294"/></filter><filter id="iw7K3ug" width="11.112" height="3.615" x="10.829" y="25.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".2"/></filter><filter id="iBofRPe" width="3.297" height="3.17" x="8.245" y="23.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".2"/></filter><filter id="iCMeVye" width="3.085" height="3.032" x="11.507" y="23.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".2"/></filter><filter id="iA8eDNc" width="6.547" height="2.797" x="14.14" y="13.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".125"/></filter><filter id="ivGgnJc" width="7.845" height="3.428" x="13.691" y="12.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.243137 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1294"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.32549 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1294" result="effect2_innerShadow_4002_1294"/></filter><filter id="infbYPb" width="2.002" height="1.902" x="13.691" y="6.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.368627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1294"/></filter><filter id="ilS1Orc" width="1.669" height="1.67" x="19.428" y="6.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".1"/></filter><filter id="i1WzQGe" width="1.47" height="1.47" x="13.918" y="6.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".05"/></filter><filter id="iiAibSO" width="6.422" height="6.428" x="14.399" y="4.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.380392 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1294"/></filter><filter id="iq7TUgb" width="1.609" height="2.085" x="16.51" y="6.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".125"/></filter><filter id="iarZ9Ec" width="2.152" height=".865" x="16.335" y="8.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".025"/></filter><filter id="iYWQP4b" width="1.855" height=".76" x="17.885" y="6.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1294"/></filter><filter id="in5wpDd" width="1.855" height=".76" x="15.08" y="6.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1294"/></filter><filter id="iJTgIWb" width="1.531" height=".726" x="15.16" y="5.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0431373 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1294"/></filter><filter id="ijJwNDe" width="1.531" height=".727" x="18.361" y="5.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0431373 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1294"/></filter><filter id="iviDgJc" width=".545" height=".492" x="18.225" y="6.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".05"/></filter><filter id="iDDryGd" width=".689" height=".702" x="18.68" y="6.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".1"/></filter><filter id="iRnRUgc" width=".745" height=".777" x="16.055" y="6.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".1"/></filter><filter id="iqUMUZw" width=".62" height=".497" x="15.65" y="6.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".05"/></filter><filter id="iGGU5Ke" width="1.231" height=".473" x="18.432" y="5.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".05"/></filter><filter id="ipPMy0d" width="1.231" height=".473" x="15.21" y="5.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".05"/></filter><filter id="i1jS15d" width="2.163" height="2.504" x="13.885" y="3.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".05"/></filter><filter id="ioldmmb" width="5.15" height="3.645" x="15.32" y="2.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0823529 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1294"/><feGaussianBlur result="effect2_foregroundBlur_4002_1294" stdDeviation=".05"/></filter><filter id="iLhFsNc" width="5.15" height="3.495" x="15.32" y="2.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".05"/></filter><filter id="i0zyNWc" width="3.17" height="3.061" x="19.276" y="3.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.529412 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1294"/></filter><filter id="iqHrkEF" width="2.055" height="6.641" x="24.354" y="7.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".25"/></filter><filter id="i4rBUCc" width="4.719" height="3.595" x="19.999" y="10.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".25"/></filter><filter id="iItCWDd" width="1.175" height="2.326" x="23.635" y="7.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1294" stdDeviation=".125"/></filter><linearGradient id="ii1khxe" x1="6.713" x2="7.026" y1="16.853" y2="16.853" gradientUnits="userSpaceOnUse"><stop class="m6o04wbub"/><stop offset="1" class="jebbfvb-u"/></linearGradient><linearGradient id="iDxz2Ld" x1="8.135" x2="14.729" y1="16.572" y2="12.165" gradientUnits="userSpaceOnUse"><stop class="qcex0vb1a"/><stop offset="1" class="afm1rlbwt"/></linearGradient><linearGradient id="iE4ja3b" x1="17.354" x2="17.354" y1="18.04" y2="16.384" gradientUnits="userSpaceOnUse"><stop offset=".113" class="ljw2z7djf"/><stop offset="1" class="nay2tcbrd"/></linearGradient><linearGradient id="iMhaxNb" x1="11.768" x2="20.875" y1="26.97" y2="28.812" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iUUCLJd" x1="10.518" x2="8.203" y1="25.763" y2="25.39" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="idVwZGb" x1="14.013" x2="13.482" y1="24.1" y2="26.21" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iIZ8Dmp" x1="14.05" x2="14.641" y1="6.947" y2="8.172" gradientUnits="userSpaceOnUse"><stop class="e-084nbmr"/><stop offset="1" class="sh2s77xqm"/></linearGradient><linearGradient id="i1pRTic" x1="17.838" x2="17.37" y1="7.767" y2="7.79" gradientUnits="userSpaceOnUse"><stop class="raocb-buh"/><stop offset="1" class="jcz4yrb9y"/></linearGradient><linearGradient id="ioaRNOd" x1="17.452" x2="17.452" y1="8.454" y2="8.275" gradientUnits="userSpaceOnUse"><stop class="ouau4qbku"/><stop offset="1" class="er3a68ttw"/></linearGradient><linearGradient id="ikAGyNc" x1="17.41" x2="17.41" y1="6.84" y2="7.775" gradientUnits="userSpaceOnUse"><stop class="i1ro3snza"/><stop offset=".824" class="knng2sb5f"/></linearGradient><linearGradient id="itKhjLl" x1="16.98" x2="17.247" y1="9.352" y2="8.837" gradientUnits="userSpaceOnUse"><stop class="muhp3gb-x"/><stop offset="1" class="pteqlcbvj"/></linearGradient><linearGradient id="iRE1yCb" x1="16.387" x2="15.16" y1="6.04" y2="6.04" gradientUnits="userSpaceOnUse"><stop class="wqxrteb3u"/><stop offset="1" class="pmqh-db2s"/></linearGradient><linearGradient id="i24rJMd" x1="19.589" x2="18.361" y1="6.04" y2="6.04" gradientUnits="userSpaceOnUse"><stop class="wqxrteb3u"/><stop offset="1" class="pmqh-db2s"/></linearGradient><linearGradient id="idDVUGc" x1="19.158" x2="18.974" y1="6.899" y2="7.013" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1cZLfc" x1="16.559" x2="16.375" y1="6.899" y2="7.013" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iiovjoc" x1="24.421" x2="26.951" y1="10.087" y2="11.158" gradientUnits="userSpaceOnUse"><stop class="a6808p9jc"/><stop offset="1" class="mo83k0x5i"/></linearGradient><linearGradient id="iRFs2qe" x1="23.061" x2="23.439" y1="13.196" y2="11.191" gradientUnits="userSpaceOnUse"><stop class="w36aet_8l"/><stop offset="1" class="l_hojzbwo"/></linearGradient><linearGradient id="iuYQKFc" x1="24.213" x2="24.213" y1="9.29" y2="6.665" gradientUnits="userSpaceOnUse"><stop class="u1gy5srjx"/><stop offset="1" class="oiiwkjp_m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-merpeople-medium-dark" /></template>
<style>
.a0kmoyxfg {
  stop-color: var(--svg-color--795354, #795354);
}

.a6808p9jc {
  stop-color: var(--svg-color--916d64, #916D64);
}

.afm1rlbwt {
  stop-color: var(--svg-color--7e5553, #7E5553);
  stop-opacity: 0;
}

.av94dpbjb {
  stroke: var(--svg-color--362c2f, #362C2F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M16.317 5.818c-.191-.046-.665-.023-.982.204");
}

.axurn_5zl {
  d: path("M16.12 6.586a.527.527 0 0 0-.508.666h1.018a.53.53 0 0 0-.51-.666");
}

.ay_phd11e {
  d: path("M18.701 6.586a.527.527 0 0 1 .508.666h-1.018a.53.53 0 0 1 .51-.666");
}

.bcouvbcoc {
  stop-color: var(--svg-color--6d404e, #6D404E);
}

.bjbtwzbgn {
  stop-color: var(--svg-color--704b4a, #704B4A);
  stop-opacity: 0;
}

.bw1rz3b-f {
  stop-color: var(--svg-color--443339, #443339);
  stop-opacity: 0;
}

.c9hto3rdo {
  cx: 15.96px;
  cy: 6.811px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.229px;
  ry: 0.116px;
}

.cd06k8bas {
  fill: var(--svg-color--7e584e, #7E584E);
  d: path("m17.184 7.007l-.314 1.005a.32.32 0 0 0 .308.413h.465a.32.32 0 0 0 .307-.413l-.314-1.005c-.067-.222-.381-.222-.452 0");
}

.chm_zob8h {
  stop-color: var(--svg-color--7a5449, #7A5449);
}

.chywufrfu {
  stop-color: var(--svg-color--784554, #784554);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn11jacls {
  stop-color: var(--svg-color--906d67, #906D67);
}

.co87qobft {
  d: path("M18.66 6.698c.038.05-.04.11-.129.177s-.155.114-.192.064s.004-.145.093-.211c.09-.067.192-.08.229-.03");
}

.d804zky3u {
  d: path("M13.356 19.091c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.954-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531H13.64c-2.625 0-3.246-1.89-3.355-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.521-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.44-.296c.52.119.951.252 1.57.567a3.4 3.4 0 0 1 1.238 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.866.388c-.139.063-.208.223-.14.36c.474.956 1.468.87 2.858.87c1.851 0 2.96-1.325 2.843-2.724c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.328-2.055-1.145-2.055-2.926");
}

.dbiyjrp-x {
  fill: var(--svg-color--774555, #774555);
  d: path("m17.179 7.09l-.404 1.004a.32.32 0 0 0 .307.413h.465a.32.32 0 0 0 .308-.413l-.314-1.005c-.068-.222-.292-.222-.363 0");
}

.dbrr_ge-k {
  stop-color: var(--svg-color--473a3e, #473A3E);
}

.dg-q56b3p {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.41 8.941a1.8 1.8 0 0 1-.84-.204c-.083-.043-.172.053-.12.13a1.142 1.142 0 0 0 1.92 0c.053-.08-.036-.173-.12-.13a1.8 1.8 0 0 1-.84.204Z");
}

.dgweptk-f {
  stop-color: var(--svg-color--3d2c2f, #3D2C2F);
}

.dogwq2blg {
  stop-color: var(--svg-color--8b61d1, #8B61D1);
  stop-opacity: 0;
}

.dsu9eguof {
  stop-color: var(--svg-color--7550b8, #7550B8);
}

.e-084nbmr {
  stop-color: var(--svg-color--624543, #624543);
}

.eiflvuzgd {
  fill: var(--svg-color--000, #000);
  d: path("M16.422 7.113a.3.3 0 0 0-.302-.302a.3.3 0 0 0-.269.442h.535a.3.3 0 0 0 .036-.14");
}

.er3a68ttw {
  stop-color: var(--svg-color--774654, #774654);
  stop-opacity: 0;
}

.eywjsqb5l {
  fill: var(--svg-color--8d62d5, #8D62D5);
  d: path("M14.09 13.15a.4.4 0 0 0-.4.4v1.128a1.3 1.3 0 0 0 1.3 1.3h4.846a1.3 1.3 0 0 0 1.3-1.3V13.55a.4.4 0 0 0-.4-.4h-1.842a1.5 1.5 0 0 0-1.377.904c-.027.062-.18.062-.207 0a1.5 1.5 0 0 0-1.377-.904z");
}

.f32er0yca {
  d: path("M17.054 2.597c-.67-.147-1.564.586-1.633.834c.91 2.14 2.14 2 3.841 1.936c.945-.035 1.02.301 1.1.506c.156-2.688-1.783-2.939-3.308-3.276");
}

.f88wzbb7k {
  stop-color: var(--svg-color--242223, #242223);
}

.f8wxf-tdu {
  d: path("M14.404 6.475h.008l-.006-.157l-.007-.181c.013-.56.34-.778.48-.85l.03-.012l.03-.012c.315-.145.57-.398.703-.73l.048-.114a.156.156 0 0 1 .273-.03a2.28 2.28 0 0 0 1.885.988h1.903c.106 0 .64.052.67.788l-.07 1.816c-.072 1.656-1.366 2.768-2.944 2.768c-1.579 0-2.872-1.112-2.945-2.768z");
}

.fcfe9dfwi {
  stop-color: var(--svg-color--654342, #654342);
}

.ft5dv1b6b {
  fill: none;
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.g4s3nac-z {
  stop-color: var(--svg-color--653d59, #653D59);
  stop-opacity: 0;
}

.gbs005z-w {
  fill: var(--svg-color--87014d, #87014D);
  d: path("M17.41 8.941a1.8 1.8 0 0 1-.84-.204c-.083-.043-.172.053-.12.13a1.142 1.142 0 0 0 1.92 0c.053-.08-.036-.173-.12-.13a1.8 1.8 0 0 1-.84.204");
}

.gjbve0bnv {
  d: path("M14.641 8.172a.95.95 0 1 0 0-1.902a.95.95 0 0 0 0 1.902");
}

.gr1si2b-x {
  stop-color: var(--svg-color--7b5958, #7B5958);
}

.gsmej6bma {
  stop-color: var(--svg-color--5a3336, #5A3336);
}

.gwqfskb8v {
  stop-color: var(--svg-color--9f7ada, #9F7ADA);
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.h9hedgb-i {
  stop-color: var(--svg-color--5d3a3f, #5D3A3F);
}

.hj78b9cjo {
  stop-color: var(--svg-color--34affa, #34AFFA);
  stop-opacity: 0;
}

.hsx8ilbej {
  stop-color: var(--svg-color--5d2f40, #5D2F40);
  stop-opacity: 0;
}

.huqdsg6wj {
  stop-color: var(--svg-color--442520, #442520);
}

.hwzcsbbxl {
  stop-color: var(--svg-color--764463, #764463);
  stop-opacity: 0;
}

.i1ro3snza {
  stop-color: var(--svg-color--835b53, #835B53);
}

.idokdtbun {
  stroke: var(--svg-color--362c2f, #362C2F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M18.557 5.818c.19-.046.664-.023.981.204");
}

.inz52_phe {
  d: path("m21.018 3.79l.204.628c.03.09.12.16.22.16l.697.01c.21 0 .285.242.105.382l-.532.418c-.08.06-.11.16-.08.26l.198.658c.07.22-.146.36-.336.23l-.542-.398a.225.225 0 0 0-.27 0l-.551.399c-.19.13-.396-.01-.336-.23l.197-.66c.03-.1 0-.2-.08-.26l-.539-.397c-.18-.14-.097-.382.133-.382l.666-.01c.1 0 .19-.07.22-.16l.231-.648c.07-.23.325-.21.395 0");
}

.iorvdubip {
  fill: var(--svg-color--33aef9, #33AEF9);
  d: path("m21.018 3.79l.204.628c.03.09.12.16.22.16l.697.01c.21 0 .285.242.105.382l-.532.418c-.08.06-.11.16-.08.26l.198.658c.07.22-.146.36-.336.23l-.542-.398a.225.225 0 0 0-.27 0l-.551.399c-.19.13-.396-.01-.336-.23l.197-.66c.03-.1 0-.2-.08-.26l-.539-.397c-.18-.14-.097-.382.133-.382l.666-.01c.1 0 .19-.07.22-.16l.231-.648c.07-.23.325-.21.395 0");
}

.jcz4yrb9y {
  stop-color: var(--svg-color--916f68, #916F68);
  stop-opacity: 0;
}

.jebbfvb-u {
  stop-color: var(--svg-color--653f41, #653F41);
  stop-opacity: 0;
}

.jk372--tq {
  stop-color: var(--svg-color--794f52, #794F52);
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.kcaiikrsb {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.736 6.884c-.157-.276-.396-.494-.909-.494a.98.98 0 0 0-.634.218c-.159.129-.137.293-.014.355l.328.187c.385-.124.811-.141 1.229-.266");
}

.kn22s4txk {
  stop-color: var(--svg-color--755252, #755252);
}

.knng2sb5f {
  stop-color: var(--svg-color--835b53, #835B53);
  stop-opacity: 0;
}

.ko7--3b4k {
  stop-color: var(--svg-color--91756a, #91756A);
}

.kv4_lccbf {
  stop-color: var(--svg-color--8c726a, #8C726A);
}

.l_hojzbwo {
  stop-color: var(--svg-color--8d695f, #8D695F);
  stop-opacity: 0;
}

.l85u8ibfx {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M13.356 19.091c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.954-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531H13.64c-2.625 0-3.246-1.89-3.355-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.521-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.44-.296c.52.119.951.252 1.57.567a3.4 3.4 0 0 1 1.238 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.866.388c-.139.063-.208.223-.14.36c.474.956 1.468.87 2.858.87c1.851 0 2.96-1.325 2.843-2.724c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.328-2.055-1.145-2.055-2.926");
}

.lby3v6ati {
  d: path("M6.762 16.042a.486.486 0 1 1 .973 0v.775a.486.486 0 0 1-.973 0z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljw2z7djf {
  stop-color: var(--svg-color--7f5457, #7F5457);
}

.m_tl88bid {
  stop-color: var(--svg-color--704b4a, #704B4A);
}

.m2_uv2a4m {
  stop-color: var(--svg-color--7c5352, #7C5352);
}

.m3rlai98t {
  stop-color: var(--svg-color--694039, #694039);
}

.m4pcayl4x {
  d: path("M21.317 26.665c0-5.343-3.922-7.968-5.234-9l3.25-1.453c1.125.521 3.035 2.358 3.453 5.11c.484 3.187-.927 4.927-1.469 5.343");
}

.m4wre3b4e {
  stop-color: var(--svg-color--73544f, #73544F);
  stop-opacity: 0;
}

.m6o04wbub {
  stop-color: var(--svg-color--82605a, #82605A);
}

.m7soyj5jb {
  stop-color: var(--svg-color--714551, #714551);
  stop-opacity: 0;
}

.mk_tesa_t {
  stop-color: var(--svg-color--49c4fa, #49C4FA);
}

.mkrjvhq2k {
  stop-color: var(--svg-color--906d67, #906D67);
  stop-opacity: 0;
}

.mo83k0x5i {
  stop-color: var(--svg-color--916d64, #916D64);
  stop-opacity: 0;
}

.mrehmk1hy {
  stop-color: var(--svg-color--694039, #694039);
  stop-opacity: 0;
}

.mrsd5vi6x {
  fill: var(--svg-color--643743, #643743);
  d: path("M14.715 13.837a.325.325 0 0 0-.325.325v.916c0 .584.473 1.056 1.056 1.056h3.935c.583 0 1.055-.473 1.055-1.056v-.916a.325.325 0 0 0-.324-.325h-1.496a1.22 1.22 0 0 0-1.119.735c-.022.05-.146.05-.168 0a1.22 1.22 0 0 0-1.118-.735z");
}

.muhp3gb-x {
  stop-color: var(--svg-color--7f595b, #7F595B);
}

.n7-hw2b3h {
  stop-color: var(--svg-color--9f7ada, #9F7ADA);
  stop-opacity: 0;
}

.nay2tcbrd {
  stop-color: var(--svg-color--7f5457, #7F5457);
  stop-opacity: 0;
}

.nhe36etun {
  stop-color: var(--svg-color--3d2c2f, #3D2C2F);
  stop-opacity: 0;
}

.nk8pt8bvw {
  cx: 15.96px;
  cy: 6.811px;
  rx: 0.229px;
  ry: 0.116px;
}

.nkfqvvjuz {
  stop-color: var(--svg-color--53302e, #53302E);
}

.nl2u64eej {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.845 24.429c.41.162 1.402.783 2.097 1.97");
}

.nud75cb3r {
  d: path("M19.17 7.043a.5.5 0 0 0-.137-.273l-.152.168l.069.135z");
}

.o_h0y6b3p {
  d: path("m15.402 6.17l-.002.001a.159.159 0 0 1-.163-.272l.002-.001l.006-.003l.02-.011l.068-.035a2 2 0 0 1 .242-.095c.201-.064.482-.118.785-.065a.158.158 0 0 1-.055.312c-.236-.041-.462 0-.633.055a1.6 1.6 0 0 0-.257.107z");
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

.o93elw41z {
  stop-color: var(--svg-color--653d59, #653D59);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oiiwkjp_m {
  stop-color: var(--svg-color--90736b, #90736B);
  stop-opacity: 0;
}

.ouau4qbku {
  stop-color: var(--svg-color--6e3b49, #6E3B49);
}

.p224_4b9x {
  stop-color: var(--svg-color--3f2b31, #3F2B31);
}

.p3f63zb1c {
  d: path("M9.862 15.744c1.813 1.575 4.203 1.213 5.172.875v-4.626h7.234c.517-1.326.156-2.452-.236-3.066a.28.28 0 0 1-.029-.24c.082-.236.192-.616.207-.916c.031-.66-.172-.707-.192-1.613c-.02-.907-.306-1.241-.78-2.016c-.384-.625-1.372-1.031-1.974-1.27c-.66-.261-.894-.757-1.89-.757c-.77 0-1.277.39-1.626.729a.85.85 0 0 1-.48.23c-1.223.163-2.266.735-2.843 1.802c-.339.626-.369 1.608-.365 2.282a.53.53 0 0 1-.42.513c-1.53.345-2.65 1.23-3.18 2.233c-.578 1.093-.864 3.87 1.402 5.84");
}

.p6977lbwx {
  d: path("M25.054 9.557c.399-.066.488-.33.488-.501v-.535a.184.184 0 0 1 .367 0v4.93a.527.527 0 0 1-1.055 0V9.77c0-.11.09-.197.2-.214");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmqh-db2s {
  stop-color: var(--svg-color--2c1829, #2C1829);
}

.pteqlcbvj {
  stop-color: var(--svg-color--7f595b, #7F595B);
  stop-opacity: 0;
}

.pzjsfkxkt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.429 26.864c-.007.65.436 1.948 2.266 1.948h3.177c1.01-.014 3.317-.517 4.469-2.414");
}

.q2m7q-bcq {
  d: path("M15.62 4.556c-.22.565-1.18 1.028-1.61 1.14c-.142-1.143.301-2.523 1.702-2.274l.236.915c-.236-.066-.286.11-.328.219");
}

.q6mg8ibon {
  stop-color: var(--svg-color--73544f, #73544F);
}

.qbkpv6z7a {
  stop-color: var(--svg-color--764463, #764463);
}

.qcex0vb1a {
  stop-color: var(--svg-color--7e5553, #7E5553);
}

.qdgeq05dx {
  d: path("M25.683 7.95h-.003a.53.53 0 0 0-.531.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.546l.56-.558a.44.44 0 0 1 .638.605");
}

.qohe4djmm {
  fill-rule: evenodd;
  d: path("m19.616 5.9l-.082.135za.159.159 0 0 1-.163.272l-.003-.001l-.067-.035a2 2 0 0 0-.202-.08a1.34 1.34 0 0 0-.634-.054a.158.158 0 1 1-.055-.312c.304-.053.584 0 .785.065a2 2 0 0 1 .33.14l.006.004h.002z");
}

.qz1n7cnnp {
  stop-color: var(--svg-color--6e4942, #6E4942);
}

.raocb-buh {
  stop-color: var(--svg-color--916f68, #916F68);
}

.rd_1vj1uu {
  stop-color: var(--svg-color--9971db, #9971DB);
}

.rlatyn0wa {
  stop-color: var(--svg-color--45383c, #45383C);
  stop-opacity: 0;
}

.rlu2hsbuy {
  d: path("M16.6 7.05c0-.17-.138-.283-.175-.317l-.17.164l.104.212z");
}

.ro7svqvjx {
  fill: var(--svg-color--000, #000);
  d: path("M18.399 7.113a.3.3 0 0 1 .302-.302a.3.3 0 0 1 .269.441h-.535a.3.3 0 0 1-.036-.139");
}

.rvgjtg4fi {
  d: path("M20.726 13.688v3.421a.65.65 0 0 1-.65.65H14.75a.65.65 0 0 1-.65-.65v-2.75l-1.953 1.697a2.5 2.5 0 0 1-1.64.613h-1.84l-.612.527a.527.527 0 0 1-.716-.774l.317-.316a.1.1 0 0 0-.019-.154l-.018-.011a.384.384 0 0 0-.476.065l-.554.583a.526.526 0 0 1-.776-.71l.755-.857a.98.98 0 0 1 .621-.326l3.069-.355a.5.5 0 0 0 .284-.132l3.247-3.04c.889-.89 2.57-.98 3.735-.98c1.495 0 2.532.234 3.2.574l2.862 1.473a.202.202 0 0 0 .293-.16c.049-.5.132-1.271.197-1.853a.2.2 0 0 0-.046-.15l-.373-.445a1 1 0 0 1-.235-.644V7.783a.531.531 0 0 1 1.062 0v.667c0 .18.045.36.17.488c.065.067.145.137.239.2c.116.078.255-.016.255-.156v-.5a.531.531 0 1 1 1.063 0v1.39l.015.703c.019.846.042 1.907.088 2.883c.03.64-.263 1.255-.79 1.618a1.8 1.8 0 0 1-1.84.121z");
}

.rz_b8bbbi {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
  stop-opacity: 0;
}

.s0bi7iy1o {
  stop-color: var(--svg-color--7b5958, #7B5958);
  stop-opacity: 0;
}

.s3-919bdo {
  stop-color: var(--svg-color--774658, #774658);
  stop-opacity: 0;
}

.s4f5kgi2d {
  d: path("M20.263 7.855a.635.635 0 1 0 0-1.27a.635.635 0 0 0 0 1.27");
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

.sh2s77xqm {
  stop-color: var(--svg-color--663c4d, #663C4D);
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.t-07fdchd {
  stop-color: var(--svg-color--896053, #896053);
}

.t7nle4uwx {
  d: path("M24.218 13.295v.794l-3.72-2.397l.083-.199z");
}

.ta7v5vpcw {
  stop-color: var(--svg-color--7c4f55, #7C4F55);
  stop-opacity: 0;
}

.tg9xefb7i {
  stop-color: var(--svg-color--785650, #785650);
}

.u1gy5srjx {
  stop-color: var(--svg-color--90736b, #90736B);
}

.u2z2j8k6b {
  stop-color: var(--svg-color--5d2f40, #5D2F40);
}

.u7harwjoq {
  stop-color: var(--svg-color--784554, #784554);
  stop-opacity: 0;
}

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.umf8cbcnm {
  stop-color: var(--svg-color--2e1a26, #2E1A26);
}

.vckbn7bgk {
  d: path("m17.184 7.007l-.314 1.005a.32.32 0 0 0 .308.413h.465a.32.32 0 0 0 .307-.413l-.314-1.005c-.067-.222-.381-.222-.452 0");
}

.ve4hytcdg {
  stop-color: var(--svg-color--573730, #573730);
  stop-opacity: 0;
}

.vlytvntgs {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.824 6.425c.386 0 .712.266.8.626a.162.162 0 0 1-.158.201h-1.318a.136.136 0 0 1-.134-.16a.826.826 0 0 1 .81-.667");
}

.vpkiteigl {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M24.085 7.63v1.248c0 .066.026.13.073.177l.26.26");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_bi9zfnz {
  stop-color: var(--svg-color--724c46, #724C46);
}

.w36aet_8l {
  stop-color: var(--svg-color--8d695f, #8D695F);
}

.w4rlmo2dn {
  stop-color: var(--svg-color--242223, #242223);
  stop-opacity: 0;
}

.w4wjacb9v {
  stop-color: var(--svg-color--8c60d5, #8C60D5);
  stop-opacity: 0;
}

.w9t1efbqg {
  stop-color: var(--svg-color--785650, #785650);
  stop-opacity: 0;
}

.whopo0y2h {
  stop-color: var(--svg-color--200e23, #200E23);
}

.wliqnbp1k {
  d: path("M14.09 13.15a.4.4 0 0 0-.4.4v1.128a1.3 1.3 0 0 0 1.3 1.3h4.846a1.3 1.3 0 0 0 1.3-1.3V13.55a.4.4 0 0 0-.4-.4h-1.842a1.5 1.5 0 0 0-1.377.904c-.027.062-.18.062-.207 0a1.5 1.5 0 0 0-1.377-.904z");
}

.wqxrteb3u {
  stop-color: var(--svg-color--2a1d27, #2A1D27);
}

.wyqz88nbk {
  stop-color: var(--svg-color--7a4b52, #7A4B52);
  stop-opacity: 0;
}

.x_nmsobjl {
  stop-color: var(--svg-color--45383c, #45383C);
}

.xkh31bbow {
  stop-color: var(--svg-color--663d3a, #663D3A);
  stop-opacity: 0;
}

.xyq99dbsm {
  d: path("M14.653 7.855a.635.635 0 1 0 0-1.27a.635.635 0 0 0 0 1.27");
}

.xz2vy3rji {
  stop-color: var(--svg-color--443339, #443339);
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.y-i88cmqv {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M18.085 6.884c.157-.276.396-.494.909-.494a.98.98 0 0 1 .634.218c.159.129.137.293.014.355l-.328.187c-.385-.124-.811-.141-1.229-.266");
}

.y1syambbk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.992 23.91c-.308.352-1.134 1.1-1.885 1.832");
}

.y4inpcddo {
  stop-color: var(--svg-color--734945, #734945);
}

.y6gj-0bkn {
  stop-color: var(--svg-color--4b2526, #4B2526);
}

.yywcf0gub {
  stop-color: var(--svg-color--8c6256, #8C6256);
}

.z-iy1qoxq {
  stop-color: var(--svg-color--67385a, #67385A);
}

.zj8l1oboz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.66 6.698c.038.05-.04.11-.129.177s-.155.114-.192.064s.004-.145.093-.211c.09-.067.192-.08.229-.03");
}

.zrq_ottju {
  stop-color: var(--svg-color--693945, #693945);
}

</style>
