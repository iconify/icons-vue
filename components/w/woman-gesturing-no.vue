<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#igbXbnf)"><path fill="url(#iBI8oZS)" clip-rule="evenodd" class="lazml4x6u"/><path fill="url(#iRUfufi)" clip-rule="evenodd" class="lazml4x6u"/><path fill="url(#ixDnjmb)" clip-rule="evenodd" class="lazml4x6u"/><path fill="url(#iUF7O1b)" clip-rule="evenodd" class="lazml4x6u"/><path fill="url(#iU1RC3A)" clip-rule="evenodd" class="lazml4x6u"/><path fill="url(#iGWu1me)" clip-rule="evenodd" class="lazml4x6u"/><path fill="url(#ijWZfOb)" clip-rule="evenodd" class="lazml4x6u"/><path fill="url(#ip9Wice)" clip-rule="evenodd" class="lazml4x6u"/><path fill="url(#iYuQVSs)" clip-rule="evenodd" class="lazml4x6u"/></g><g filter="url(#iHNqB6c)"><path fill="url(#i5JlMjc)" class="hhsxjkz4s"/></g><g filter="url(#ixNwppb)"><path fill="url(#iJCJHqd)" class="t783pebvk"/></g><g filter="url(#iVhx2ld)"><path class="odvf_hblg"/><path fill="url(#iHUlaee)" class="xzzcm4noc"/></g><g filter="url(#iO7eeSb)"><path class="nzmi08x1q"/><path fill="url(#iOoTqyc)" class="fni8pabwx"/></g><g filter="url(#iY8B7rc)"><path fill="url(#ir18isQ)" class="m6qah3bpu"/><path fill="url(#ibwdrfc)" class="m6qah3bpu"/><path fill="url(#iWFvObd)" class="m6qah3bpu"/><path fill="url(#indQF1B)" class="m6qah3bpu"/><path fill="url(#iNR2MBd)" class="m6qah3bpu"/><path fill="url(#ixzAr8i)" class="m6qah3bpu"/><path fill="url(#iz76Sdd)" class="m6qah3bpu"/></g><path fill="url(#iqysTxq)" class="m6qah3bpu"/><g filter="url(#iGPSPlb)"><path class="e4ggbyv4d"/></g><g filter="url(#iPZIZFd)"><path fill="url(#i36aPoe)" class="hm-5is4jw"/><path fill="url(#iWNBoyb)" class="hm-5is4jw"/><path fill="url(#ijguerR)" class="hm-5is4jw"/><path fill="url(#iO9qyfe)" class="hm-5is4jw"/></g><path fill="url(#ifb1Vmc)" class="hm-5is4jw"/><path fill="url(#inrjBIl)" class="hm-5is4jw"/><g filter="url(#i8XYCGd)"><path class="jd89qlxvf"/></g><g filter="url(#iwuYcjc)"><path class="khin39btp"/></g><path class="uhq58tb_t"/><path fill="url(#ixonCkA)" class="gpwfefbug"/><path class="lxu9agbhl"/><g filter="url(#i4gsPFc)"><path class="o9744mstp"/><path fill="url(#ilOwVId)" class="e216ayp8d"/></g><g filter="url(#iPemlqb)"><path fill="url(#iKZB9jd)" class="tggjchboz"/></g><path class="qjofjzfcx"/><path fill="url(#iTY7jpe)" class="odvtinkkj"/><path class="a6o12m-zc"/><g filter="url(#iKuZjLC)"><path fill="url(#iDQ44rx)" class="nkx91ea4s"/></g><g filter="url(#imbF7Fe)"><ellipse transform="rotate(-27.914 12.895 11.9)" class="dpx2mxb1b"/><ellipse fill="url(#instGHd)" transform="rotate(-27.914 12.895 11.9)" class="odccdtbzx"/></g><g filter="url(#iCvZi1d)"><path fill="url(#i4TXMsh)" class="tirq037go"/><path fill="url(#i4CP00b)" class="tirq037go"/></g><g filter="url(#i1X6anc)"><path fill="url(#iBrILqc)" class="e9fmv0b0m"/><path fill="url(#ioigDcb)" class="e9fmv0b0m"/><path fill="url(#ibfrJgc)" class="e9fmv0b0m"/></g><g filter="url(#iSEBdye)"><path stroke="url(#iByjpbd)" class="z0isz9w8b"/></g><g filter="url(#iaPvxQb)"><path class="r3qwwubqj"/></g><g filter="url(#i0ct6tc)"><path class="qx4-gbcmu"/></g><g filter="url(#iXmllue)"><path class="s4nlh4bda"/></g><g filter="url(#iup3Amd)"><path class="tn-3jhb_c"/></g><path class="ft_6brbza"/><path fill="url(#iug4Bgw)" class="lnkgnybzi"/><path fill="url(#iFrnlDb)" class="lnkgnybzi"/><path fill="url(#i0PVwAd)" class="lnkgnybzi"/><path fill="url(#iBmjHub)" class="hg_a8ccmi"/><path fill="url(#iKqzjJd)" class="uj6txmbjr"/><path fill="url(#i7CRD3q)" class="uj6txmbjr"/><path fill="url(#iFd2Eyd)" class="uj6txmbjr"/><path fill="url(#imXnd8b)" class="uj6txmbjr"/><path fill="url(#io7lQEe)" class="uj6txmbjr"/><path fill="url(#itU35Le)" class="uj6txmbjr"/><path fill="url(#igNdC4b)" class="uj6txmbjr"/><path fill="url(#iF7ZNSc)" class="l8ybf1tay"/><path fill="url(#iQAtpQe)" class="c29lbacgt"/><path fill="url(#iTFL3Le)" class="c29lbacgt"/><path fill="url(#iocxsMc)" class="c29lbacgt"/><path fill="url(#idVxunc)" class="c29lbacgt"/><path fill="url(#iTggJDj)" class="m99jgnbvc"/><path fill="url(#iqkOAec)" class="m99jgnbvc"/><path fill="url(#iwnOmvb)" class="m99jgnbvc"/><path fill="url(#ivR7svd)" class="ep_azxb0v"/><path fill="url(#iKjzZec)" class="ep_azxb0v"/><path fill="url(#i1gz52c)" class="ep_azxb0v"/><path fill="url(#irB1IAh)" class="z3vxlgnwk"/><path fill="url(#i0xQPqc)" class="z3vxlgnwk"/><path fill="url(#iFgbVlc)" class="z3vxlgnwk"/><path fill="url(#i6BBYid)" class="z3vxlgnwk"/><g filter="url(#iAhQskd)"><path fill="url(#ipdokFd)" class="oplayzbfr"/><path fill="url(#i4RYQPe)" class="oplayzbfr"/></g><defs><radialGradient id="iRUfufi" cx="0" cy="0" r="1" gradientTransform="matrix(-.76083 5.74882 -7.18144 -.95043 15.608 15.927)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="i7le4lbop"/><stop offset="1" class="grze2mvec"/></radialGradient><radialGradient id="ixDnjmb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.97343 3.08578 -3.79843 -4.89109 12.058 16.265)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="mu7f4ktwz"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="iUF7O1b" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.715 8.968)scale(2.7139 2.63505)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="hafysqb0k"/><stop offset="1" class="j_flb889r"/></radialGradient><radialGradient id="iU1RC3A" cx="0" cy="0" r="1" gradientTransform="rotate(91.818 -.188 9.847)scale(2.6644 1.86166)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="z7rsnjfsy"/><stop offset="1" class="ljqghbbdk"/></radialGradient><radialGradient id="iGWu1me" cx="0" cy="0" r="1" gradientTransform="matrix(3.1703 3.59301 -6.2703 5.53262 10.705 3.626)" gradientUnits="userSpaceOnUse"><stop class="co9sqzbyd"/><stop offset="1" class="w1102jwkv"/></radialGradient><radialGradient id="ijWZfOb" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 10.245 7.806)scale(2.06435 2.8849)" gradientUnits="userSpaceOnUse"><stop class="l_fnne1yj"/><stop offset="1" class="yw4y67b7z"/></radialGradient><radialGradient id="ip9Wice" cx="0" cy="0" r="1" gradientTransform="matrix(-2.32479 .67634 -1.47162 -5.05842 25.458 11.7)" gradientUnits="userSpaceOnUse"><stop class="vj4m2tb3q"/><stop offset="1" class="hottnizrg"/></radialGradient><radialGradient id="iYuQVSs" cx="0" cy="0" r="1" gradientTransform="rotate(156.949 11.01 10.165)scale(4.31824 6.88027)" gradientUnits="userSpaceOnUse"><stop class="vj4m2tb3q"/><stop offset="1" class="hottnizrg"/></radialGradient><radialGradient id="iJCJHqd" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 41.305 -42.002)scale(3.44762 4.20939)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iHUlaee" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 47.408 -54.3)scale(1.64503)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iOoTqyc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35441 0 0 -1.29558 10.105 12.774)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="ir18isQ" cx="0" cy="0" r="1" gradientTransform="matrix(-8.20075 3.78164 -5.06166 -10.97656 19.594 12.096)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="ibwdrfc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6603 1.40713 -1.19385 -2.25707 18.385 12.975)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iWFvObd" cx="0" cy="0" r="1" gradientTransform="matrix(1.05533 -5.10075 6.4719 1.33902 13.24 20.648)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="indQF1B" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01136 8.57454 -8.62045 -1.01677 16.67 12.294)" gradientUnits="userSpaceOnUse"><stop offset=".809" class="n6m453btf"/><stop offset=".997" class="ox4_yyb3q"/></radialGradient><radialGradient id="iNR2MBd" cx="0" cy="0" r="1" gradientTransform="rotate(164.542 7.428 8.231)scale(7.09426 12.2141)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="ixzAr8i" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45108 1.78087 0 18.89 11.568)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iz76Sdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.71491 1.9654 0 13.57 11.678)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iqysTxq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69845 0 0 -5.59136 22.414 13.444)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iWNBoyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.87947 -3.08902 1.76758 -.50324 16.978 14.36)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="inrjBIl" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 5.947 9.575)scale(1.98587 2.65993)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="ixonCkA" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02304 -1.62726 0 18.74 12.02)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ilOwVId" cx="0" cy="0" r="1" gradientTransform="matrix(-.29244 -.37685 .51883 -.40262 18.453 12.127)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTY7jpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02304 -1.62727 0 13.238 12.02)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="instGHd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.491 -.19)scale(.62307 .74895)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4TXMsh" cx="0" cy="0" r="1" gradientTransform="matrix(-4.31164 5.2204 -2.56595 -2.11927 12.565 4.007)" gradientUnits="userSpaceOnUse"><stop class="esh4v5qtq"/><stop offset=".558" class="smjhikemm"/><stop offset="1" class="lc4hw_a_v"/></radialGradient><radialGradient id="i4CP00b" cx="0" cy="0" r="1" gradientTransform="rotate(117.646 4.712 6.397)scale(3.00628 2.57299)" gradientUnits="userSpaceOnUse"><stop class="xprjt9owh"/><stop offset="1" class="abu2lcc5n"/></radialGradient><radialGradient id="iBrILqc" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.325 7.174)scale(6.14454 8.73728)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="esh4v5qtq"/><stop offset="1" class="smjhikemm"/></radialGradient><radialGradient id="ioigDcb" cx="0" cy="0" r="1" gradientTransform="rotate(105.018 7.819 9.381)scale(3.58878 5.99259)" gradientUnits="userSpaceOnUse"><stop class="xprjt9owh"/><stop offset="1" class="abu2lcc5n"/></radialGradient><radialGradient id="ibfrJgc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.16362 -7.86238 7.03795 -3.72703 17.616 11.15)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><radialGradient id="iug4Bgw" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.8125 10.4384 0 16.562 30.383)" gradientUnits="userSpaceOnUse"><stop class="gfj1348zm"/><stop offset=".714" class="vqiy7zq_f"/></radialGradient><radialGradient id="iFrnlDb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.438 22.418)" gradientUnits="userSpaceOnUse"><stop class="uatqp3rks"/><stop offset="1" class="oln0s8bds"/></radialGradient><radialGradient id="i0PVwAd" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.063 21.199)" gradientUnits="userSpaceOnUse"><stop class="leds28lfi"/><stop offset="1" class="x0hvtbbrr"/></radialGradient><radialGradient id="iBmjHub" cx="0" cy="0" r="1" gradientTransform="matrix(2.6551 1.32154 -2.0509 4.12044 8.345 17.221)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="yocx2rbki"/><stop offset="1" class="o9l8d3osf"/></radialGradient><radialGradient id="iKqzjJd" cx="0" cy="0" r="1" gradientTransform="matrix(16.5217 8.52358 -2.95327 5.72447 14.913 18.637)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="zlzo724_f"/><stop offset="1" class="lfko0tbrz"/></radialGradient><radialGradient id="i7CRD3q" cx="0" cy="0" r="1" gradientTransform="matrix(-4.80476 2.04336 -1.52855 -3.59423 29 24.883)" gradientUnits="userSpaceOnUse"><stop class="n-rd_0bmv"/><stop offset="1" class="yx9d6ib5k"/></radialGradient><radialGradient id="iFd2Eyd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.07575 5.3158 -8.32749 -3.25178 14.245 17.664)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="nrkcd8b4q"/><stop offset="1" class="uwifpabgl"/></radialGradient><radialGradient id="io7lQEe" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.407 -3.085)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="de672vbvk"/><stop offset="1" class="w7mjpac8w"/></radialGradient><radialGradient id="igNdC4b" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -3 .29081 .6725 18.155 24.461)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="h-ljyaczz"/><stop offset="1" class="h08s6tvxi"/></radialGradient><radialGradient id="iF7ZNSc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45313 .59375 -1.31526 -3.21892 23.405 17.79)" gradientUnits="userSpaceOnUse"><stop class="zm-3ej5xp"/><stop offset="1" class="ip569gqjb"/></radialGradient><radialGradient id="iQAtpQe" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.313 18.855)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="pzrhisbdp"/><stop offset="1" class="yahds0bfr"/></radialGradient><radialGradient id="iTggJDj" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 .75001 -.6198 -1.21376 28.875 17.62)" gradientUnits="userSpaceOnUse"><stop class="x5ozldbku"/><stop offset=".697" class="wwlvfha4h"/></radialGradient><radialGradient id="ivR7svd" cx="0" cy="0" r="1" gradientTransform="matrix(1.724 .84238 -1.17381 2.40231 3.175 17.62)" gradientUnits="userSpaceOnUse"><stop class="xg7pvujwr"/><stop offset=".697" class="gltbvazww"/></radialGradient><radialGradient id="irB1IAh" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.292 6.342)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="di5a24oyc"/><stop offset="1" class="ln7fo96zz"/></radialGradient><radialGradient id="i0xQPqc" cx="0" cy="0" r="1" gradientTransform="rotate(152.447 13.376 10.3)scale(1.21604 1.30616)" gradientUnits="userSpaceOnUse"><stop class="y0na07-wu"/><stop offset="1" class="nshtk9bjl"/></radialGradient><radialGradient id="iFgbVlc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49999 1.70314 -.73757 -.64959 28.906 15.87)" gradientUnits="userSpaceOnUse"><stop offset=".282" class="xpv5cjbuo"/><stop offset="1" class="yk9k1_boe"/></radialGradient><filter id="igbXbnf" width="19.187" height="19.687" x="6.52" y="1.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.629167 0 0 0 0 0.41525 0 0 0 0 0.183507 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24792"/></filter><filter id="iHNqB6c" width="4.208" height="4.308" x="8.052" y="10.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.627451 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24792"/></filter><filter id="ixNwppb" width="4.058" height="4.308" x="20.047" y="10.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24792"/></filter><filter id="iVhx2ld" width="3.709" height="3.709" x="20.222" y="10.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24792" stdDeviation=".25"/></filter><filter id="iO7eeSb" width="3.209" height="3.209" x="8.501" y="11.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24792" stdDeviation=".125"/></filter><filter id="iY8B7rc" width="12.85" height="14.115" x="9.564" y="6.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24792"/></filter><filter id="iGPSPlb" width="3.367" height="4.382" x="14.101" y="11.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24792" stdDeviation=".25"/></filter><filter id="iPZIZFd" width="2.867" height="3.882" x="14.556" y="11.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24792" stdDeviation=".125"/></filter><filter id="i8XYCGd" width="3.732" height="1.621" x="17.229" y="11.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24792"/></filter><filter id="iwuYcjc" width="3.732" height="1.621" x="11.017" y="11.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24792"/></filter><filter id="i4gsPFc" width=".94" height=".826" x="17.841" y="11.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24792" stdDeviation=".05"/></filter><filter id="iPemlqb" width="1.019" height="1.047" x="18.926" y="11.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24792" stdDeviation=".1"/></filter><filter id="iKuZjLC" width="1.139" height="1.207" x="13.324" y="11.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24792" stdDeviation=".1"/></filter><filter id="imbF7Fe" width="1.099" height=".836" x="12.346" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24792" stdDeviation=".05"/></filter><filter id="iCvZi1d" width="5.195" height="5.483" x="8.077" y="4.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24792" stdDeviation=".2"/></filter><filter id="i1X6anc" width="11.11" height="7.158" x="11.871" y="2.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24792" stdDeviation=".125"/></filter><filter id="iSEBdye" width="1.287" height="2.756" x="12.043" y="4.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24792" stdDeviation=".1"/></filter><filter id="iaPvxQb" width="2.884" height="1.34" x="11.376" y="9.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.192157 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24792"/></filter><filter id="i0ct6tc" width="2.884" height="1.34" x="17.939" y="9.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.192157 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24792"/></filter><filter id="iXmllue" width="2.717" height="1.234" x="11.486" y="9.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24792" stdDeviation=".125"/></filter><filter id="iup3Amd" width="2.717" height="1.234" x="17.896" y="9.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24792" stdDeviation=".125"/></filter><filter id="iAhQskd" width="7.3" height="8.016" x="2" y="12.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.564706 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24792"/></filter><linearGradient id="iBI8oZS" x1="21.907" x2="13.326" y1="4.007" y2="19.901" gradientUnits="userSpaceOnUse"><stop class="e11_y8bnv"/><stop offset="1" class="es-yqbcrh"/></linearGradient><linearGradient id="i5JlMjc" x1="8.052" x2="11.783" y1="12.884" y2="12.884" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="i36aPoe" x1="15.989" x2="15.989" y1="15.344" y2="11.962" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="ijguerR" x1="14.67" x2="15.747" y1="14.382" y2="14.514" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iO9qyfe" x1="15.989" x2="15.989" y1="15.46" y2="14.69" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="ifb1Vmc" x1="16.088" x2="16.088" y1="15.427" y2="15.251" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="iKZB9jd" x1="19.721" x2="19.326" y1="12.089" y2="12.332" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDQ44rx" x1="14.175" x2="13.78" y1="12.089" y2="12.332" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iByjpbd" x1="12.343" x2="13.03" y1="4.958" y2="6.564" gradientUnits="userSpaceOnUse"><stop class="tgfwo6lwf"/><stop offset="1" class="x-1h17b9i"/></linearGradient><linearGradient id="imXnd8b" x1="9.156" x2="10.486" y1="18.48" y2="19.104" gradientUnits="userSpaceOnUse"><stop class="f3jl2ubaa"/><stop offset="1" class="lm4fgpbpx"/></linearGradient><linearGradient id="itU35Le" x1="17.482" x2="17.906" y1="26.686" y2="25.73" gradientUnits="userSpaceOnUse"><stop class="u1h38hb7g"/><stop offset=".46" class="q371tsszr"/></linearGradient><linearGradient id="iTFL3Le" x1="14.945" x2="14.231" y1="27.124" y2="25.517" gradientUnits="userSpaceOnUse"><stop class="co9njablf"/><stop offset="1" class="riql8ub8u"/></linearGradient><linearGradient id="iocxsMc" x1="22.827" x2="21.613" y1="18.791" y2="19.355" gradientUnits="userSpaceOnUse"><stop class="ml-f4mb1m"/><stop offset="1" class="rs3gs1b0v"/></linearGradient><linearGradient id="idVxunc" x1="3.231" x2="6.517" y1="28.267" y2="26.66" gradientUnits="userSpaceOnUse"><stop class="fuha5wbor"/><stop offset="1" class="ltxdv-but"/></linearGradient><linearGradient id="iqkOAec" x1="27.945" x2="27.547" y1="19.503" y2="18.655" gradientUnits="userSpaceOnUse"><stop offset=".399" class="fmlt5vcjq"/><stop offset="1" class="jyrqxvbae"/></linearGradient><linearGradient id="iwnOmvb" x1="26.75" x2="27.266" y1="17.371" y2="17.949" gradientUnits="userSpaceOnUse"><stop class="jhw3pwb_r"/><stop offset="1" class="q6hso6-yu"/></linearGradient><linearGradient id="iKjzZec" x1="4.085" x2="4.483" y1="19.492" y2="18.644" gradientUnits="userSpaceOnUse"><stop offset=".399" class="x8wetqqbt"/><stop offset="1" class="um2qp2-uc"/></linearGradient><linearGradient id="i1gz52c" x1="5.28" x2="4.763" y1="17.359" y2="17.935" gradientUnits="userSpaceOnUse"><stop class="esmsrpb1o"/><stop offset="1" class="diy-71qna"/></linearGradient><linearGradient id="i6BBYid" x1="25.489" x2="25.997" y1="14.262" y2="15.161" gradientUnits="userSpaceOnUse"><stop class="r375w-bke"/><stop offset="1" class="nsk7h83lk"/></linearGradient><linearGradient id="ipdokFd" x1="8" x2="4.375" y1="15.73" y2="19.98" gradientUnits="userSpaceOnUse"><stop offset=".206" class="y2jmkqeym"/><stop offset="1" class="srr6nlykd"/></linearGradient><linearGradient id="i4RYQPe" x1="6.232" x2="7.245" y1="20.59" y2="18.421" gradientUnits="userSpaceOnUse"><stop class="v69eygbez"/><stop offset="1" class="xg3e-vb_e"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-gesturing-no" /></template>
<style>
.a6o12m-zc {
  fill: var(--svg-color--000, #000);
  d: path("M13.88 12.545a.64.64 0 0 0-.645-.645a.642.642 0 0 0-.573.941h1.14a.64.64 0 0 0 .078-.296");
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.c29lbacgt {
  d: path("M20.44 16.078L5.033 23.252a3.53 3.53 0 0 0-1.7 4.69a3.516 3.516 0 0 0 4.679 1.706l15.407-7.183c.503-.232.724-.837.483-1.342l-2.123-4.57a1.003 1.003 0 0 0-1.339-.474");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co9njablf {
  stop-color: var(--svg-color--7747cd, #7747CD);
}

.co9sqzbyd {
  stop-color: var(--svg-color--cd9f3b, #CD9F3B);
}

.de672vbvk {
  stop-color: var(--svg-color--8569a1, #8569A1);
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.di5a24oyc {
  stop-color: var(--svg-color--ffda2a, #FFDA2A);
}

.diy-71qna {
  stop-color: var(--svg-color--c47f1c, #C47F1C);
  stop-opacity: 0;
}

.dpx2mxb1b {
  cx: 12.895px;
  cy: 11.9px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.491px;
  ry: 0.249px;
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e11_y8bnv {
  stop-color: var(--svg-color--ffd340, #FFD340);
}

.e216ayp8d {
  d: path("M18.66 11.657c.08.107-.087.238-.278.38c-.19.143-.332.243-.412.136s.01-.31.2-.452s.41-.171.49-.064");
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e4ggbyv4d {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.494 12.493l-.862 2.143a.68.68 0 0 0 .657.882h.991a.682.682 0 0 0 .657-.882l-.67-2.143c-.144-.475-.623-.475-.773 0");
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.e9fmv0b0m {
  d: path("M15.228 2.95c-1.428-.315-2.959 1.205-3.107 1.733c1.945 4.565 4.93 4.13 8.243 3.762c1.983-.22 2.198.684 2.367 1.12c-.55-5.114-4.248-5.896-7.503-6.615");
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.ep_azxb0v {
  d: path("M7.246 19.753a.885.885 0 0 0-.35-1.203l-2.554-1.398a.899.899 0 1 0-.856 1.58l2.566 1.375a.885.885 0 0 0 1.194-.354");
}

.es-yqbcrh {
  stop-color: var(--svg-color--e4841d, #E4841D);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esmsrpb1o {
  stop-color: var(--svg-color--c47f1c, #C47F1C);
}

.f3jl2ubaa {
  stop-color: var(--svg-color--864dab, #864DAB);
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fmlt5vcjq {
  stop-color: var(--svg-color--e39546, #E39546);
}

.fni8pabwx {
  d: path("M10.105 14.128a1.354 1.354 0 1 0 0-2.709a1.354 1.354 0 0 0 0 2.71");
}

.ft_6brbza {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M15.989 19.43c.791 0 1.433-.688 1.433-1.537c0-.85-.642-1.538-1.433-1.538s-1.433.689-1.433 1.538s.642 1.537 1.433 1.537");
}

.ft5dv1b6b {
  fill: none;
}

.fuha5wbor {
  stop-color: var(--svg-color--6b45ab, #6B45AB);
}

.gfj1348zm {
  stop-color: var(--svg-color--6547af, #6547AF);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gltbvazww {
  stop-color: var(--svg-color--df841b, #DF841B);
}

.gpwfefbug {
  d: path("M18.743 11.42a1.125 1.125 0 0 1 1.085 1.421h-2.174a1.13 1.13 0 0 1 1.09-1.422");
}

.grze2mvec {
  stop-color: var(--svg-color--a05e12, #A05E12);
  stop-opacity: 0;
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.h-ljyaczz {
  stop-color: var(--svg-color--6b44c2, #6B44C2);
}

.h08s6tvxi {
  stop-color: var(--svg-color--6b44c2, #6B44C2);
  stop-opacity: 0;
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.hafysqb0k {
  stop-color: var(--svg-color--bd6115, #BD6115);
}

.hg_a8ccmi {
  d: path("m6.81 20.55l2.28 1.06l2.11-4.52l-2.23-1.05z");
}

.hhsxjkz4s {
  d: path("M10.08 14.803a2.029 2.029 0 1 0 0-4.058a2.029 2.029 0 0 0 0 4.058");
}

.hm-5is4jw {
  d: path("m15.507 12.318l-.67 2.144a.68.68 0 0 0 .656.882h.992a.682.682 0 0 0 .656-.882l-.67-2.144c-.143-.475-.813-.475-.964 0");
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.i7le4lbop {
  stop-color: var(--svg-color--a05e12, #A05E12);
}

.ip569gqjb {
  stop-color: var(--svg-color--6547a3, #6547A3);
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j_flb889r {
  stop-color: var(--svg-color--bd6115, #BD6115);
  stop-opacity: 0;
}

.jd89qlxvf {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.43 12.056c.334-.588.843-1.053 1.938-1.053c.48 0 .942.132 1.352.464c.34.274.294.625.032.756l-.702.4c-.822-.265-1.73-.301-2.62-.567");
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jhw3pwb_r {
  stop-color: var(--svg-color--e9a71b, #E9A71B);
}

.jyrqxvbae {
  stop-color: var(--svg-color--ffc128, #FFC128);
  stop-opacity: 0;
}

.khin39btp {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.55 12.056c-.336-.588-.844-1.053-1.94-1.053c-.479 0-.941.132-1.352.464c-.34.274-.294.625-.031.756l.7.4c.823-.265 1.732-.301 2.622-.567");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.l_fnne1yj {
  stop-color: var(--svg-color--ffe03f, #FFE03F);
}

.l8ybf1tay {
  d: path("m25.19 20.55l-2.28 1.06l-2.11-4.52l2.26-1.07z");
}

.lazml4x6u {
  fill-rule: evenodd;
  d: path("M25.05 14.551a4.1 4.1 0 0 0 .408-1.799c0-.59-.122-1.142-.339-1.646h.007a4 4 0 0 0-.355-.647l-.002-.004a4.1 4.1 0 0 1-.664-2.233v-.013a4.16 4.16 0 0 0-4.16-4.16a.68.68 0 0 1-.574-.294a4.17 4.17 0 0 0-3.382-1.735c-1.391 0-2.629.69-3.382 1.735a.71.71 0 0 1-.574.294l-.107.001a4.16 4.16 0 0 0-4.053 4.16v.012c0 .791-.23 1.57-.664 2.233l-.003.005a4.16 4.16 0 0 0-.277 4.091c.09.179.09.396 0 .575a4.1 4.1 0 0 0-.409 1.773a4.05 4.05 0 0 0 4.058 4.058H21.4a4.05 4.05 0 0 0 4.058-4.058c0-.638-.153-1.238-.409-1.774a.65.65 0 0 1 0-.574m-15.46-3.37h-.016l1.512 2.97c.155 3.535 1.534 0 4.903 0s4.837 3.934 4.993.4l1.432-4.031c-.068-1.57-1.205-1.68-1.432-1.68h-4.06A4.87 4.87 0 0 1 12.9 6.73a.333.333 0 0 0-.582.064l-.103.245A2.9 2.9 0 0 1 10.65 8.62q-.035.016-.065.026c-.297.154-.995.618-1.021 1.814l.013.386z");
}

.lc4hw_a_v {
  stop-color: var(--svg-color--b56f0d, #B56F0D);
}

.leds28lfi {
  stop-color: var(--svg-color--785e96, #785E96);
}

.lfko0tbrz {
  stop-color: var(--svg-color--7041c4, #7041C4);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljqghbbdk {
  stop-color: var(--svg-color--b57316, #B57316);
  stop-opacity: 0;
}

.lm4fgpbpx {
  stop-color: var(--svg-color--864dab, #864DAB);
  stop-opacity: 0;
}

.ln7fo96zz {
  stop-color: var(--svg-color--f5a227, #F5A227);
}

.lnkgnybzi {
  d: path("M25.5 29.98h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.ltxdv-but {
  stop-color: var(--svg-color--6b45ab, #6B45AB);
  stop-opacity: 0;
}

.lxu9agbhl {
  fill: var(--svg-color--000, #000);
  d: path("M18.099 12.545c0-.358.286-.645.644-.645a.642.642 0 0 1 .573.941h-1.14a.6.6 0 0 1-.077-.296");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m6qah3bpu {
  d: path("M9.574 11.182h.016l-.013-.335l-.013-.386c.026-1.196.724-1.66 1.021-1.814l.065-.026q.035-.016.065-.025a2.9 2.9 0 0 0 1.5-1.557l.103-.245a.333.333 0 0 1 .582-.064a4.87 4.87 0 0 0 4.022 2.11h4.06c.227 0 1.364.11 1.432 1.68l-.15 3.875c-.155 3.534-2.915 5.907-6.283 5.907s-6.128-2.373-6.284-5.907z");
}

.m99jgnbvc {
  d: path("M24.75 19.783a.885.885 0 0 1 .35-1.203l2.609-1.427a.899.899 0 1 1 .856 1.58l-2.621 1.404a.885.885 0 0 1-1.194-.354");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.ml-f4mb1m {
  stop-color: var(--svg-color--b282eb, #B282EB);
}

.mu7f4ktwz {
  stop-color: var(--svg-color--d77117, #D77117);
}

.n-rd_0bmv {
  stop-color: var(--svg-color--987dd3, #987DD3);
}

.n6m453btf {
  stop-color: var(--svg-color--d77a74, #D77A74);
  stop-opacity: 0;
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nkx91ea4s {
  d: path("M14.263 12.412c0-.363-.296-.606-.376-.679l-.363.352l.224.455z");
}

.nrkcd8b4q {
  stop-color: var(--svg-color--b077df, #B077DF);
}

.nshtk9bjl {
  stop-color: var(--svg-color--ffe032, #FFE032);
  stop-opacity: 0;
}

.nsk7h83lk {
  stop-color: var(--svg-color--eaac25, #EAAC25);
  stop-opacity: 0;
}

.nzmi08x1q {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M10.105 14.128a1.354 1.354 0 1 0 0-2.709a1.354 1.354 0 0 0 0 2.71");
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o9744mstp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.66 11.657c.08.107-.087.238-.278.38c-.19.143-.332.243-.412.136s.01-.31.2-.452s.41-.171.49-.064");
}

.o9l8d3osf {
  stop-color: var(--svg-color--55377f, #55377F);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odccdtbzx {
  cx: 12.895px;
  cy: 11.9px;
  rx: 0.491px;
  ry: 0.249px;
}

.odvf_hblg {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M22.076 14.128a1.354 1.354 0 1 0 0-2.709a1.354 1.354 0 0 0 0 2.71");
}

.odvtinkkj {
  d: path("M13.235 11.42a1.125 1.125 0 0 0-1.085 1.421h2.175q.039-.144.04-.296a1.133 1.133 0 0 0-1.13-1.126");
}

.oln0s8bds {
  stop-color: var(--svg-color--9f7dda, #9F7DDA);
  stop-opacity: 0;
}

.oplayzbfr {
  d: path("m9 16.05l-2.12 4.54l-.72-.38a2.79 2.79 0 0 1-1.44-1.9l-.29-1.39c-.08-.42-.29-.8-.59-1.1l-1.51-1.3a.933.933 0 0 1 1.05-1.53z");
}

.ox4_yyb3q {
  stop-color: var(--svg-color--d77a74, #D77A74);
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pzrhisbdp {
  stop-color: var(--svg-color--a56bdf, #A56BDF);
}

.q371tsszr {
  stop-color: var(--svg-color--7f4cce, #7F4CCE);
  stop-opacity: 0;
}

.q6hso6-yu {
  stop-color: var(--svg-color--e9a71b, #E9A71B);
  stop-opacity: 0;
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qjofjzfcx {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.974 11.077a1.76 1.76 0 0 0-1.708 1.335c-.057.22.112.43.337.43h2.814a.29.29 0 0 0 .286-.343a1.77 1.77 0 0 0-1.729-1.423");
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

.qx4-gbcmu {
  fill: var(--svg-color--b24820, #B24820);
  d: path("M20.712 10.164a.35.35 0 0 0-.25-.426l-2.087-.543a.349.349 0 0 0-.175.675l2.086.543a.35.35 0 0 0 .425-.25");
}

.r375w-bke {
  stop-color: var(--svg-color--eaac25, #EAAC25);
}

.r3qwwubqj {
  fill: var(--svg-color--b24820, #B24820);
  d: path("M11.388 10.164a.35.35 0 0 1 .25-.426l2.086-.543a.349.349 0 0 1 .175.675l-2.086.543a.35.35 0 0 1-.425-.25");
}

.riql8ub8u {
  stop-color: var(--svg-color--7747cd, #7747CD);
  stop-opacity: 0;
}

.rs3gs1b0v {
  stop-color: var(--svg-color--b282eb, #B282EB);
  stop-opacity: 0;
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s4nlh4bda {
  stroke: var(--svg-color--c36853, #C36853);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m11.836 9.983l2.017-.533");
}

.smjhikemm {
  stop-color: var(--svg-color--ee971b, #EE971B);
}

.srr6nlykd {
  stop-color: var(--svg-color--e9901f, #E9901F);
}

.t783pebvk {
  d: path("M22.076 14.803a2.029 2.029 0 1 0 0-4.058a2.029 2.029 0 0 0 0 4.058");
}

.tgfwo6lwf {
  stop-color: var(--svg-color--f3950f, #F3950F);
}

.tggjchboz {
  d: path("M19.746 12.396a1.06 1.06 0 0 0-.292-.583l-.328.36l.148.287z");
}

.tirq037go {
  d: path("M9.818 5.19c.783-.697 1.912-.704 2.546-.591l.508 1.627c-.325-.05-.613.063-.856.296c-.575 1.59-2.55 2.466-3.467 2.705c-.19-1.88-.084-2.832 1.269-4.037");
}

.tn-3jhb_c {
  stroke: var(--svg-color--c36853, #C36853);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m20.263 9.983l-2.017-.533");
}

.u1h38hb7g {
  stop-color: var(--svg-color--7f4cce, #7F4CCE);
}

.uatqp3rks {
  stop-color: var(--svg-color--9f7dda, #9F7DDA);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.uhq58tb_t {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.004 11.077c.823 0 1.52.567 1.708 1.335a.346.346 0 0 1-.337.43H17.56a.29.29 0 0 1-.286-.343a1.76 1.76 0 0 1 1.729-1.422");
}

.uj6txmbjr {
  d: path("m11.56 16.078l15.407 7.178a3.53 3.53 0 0 1 1.7 4.687a3.52 3.52 0 0 1-4.679 1.704L8.581 22.46a1.003 1.003 0 0 1-.483-1.341l2.123-4.567a1.004 1.004 0 0 1 1.339-.474");
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.um2qp2-uc {
  stop-color: var(--svg-color--cb7831, #CB7831);
  stop-opacity: 0;
}

.uwifpabgl {
  stop-color: var(--svg-color--b077df, #B077DF);
  stop-opacity: 0;
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v69eygbez {
  stop-color: var(--svg-color--d97b26, #D97B26);
}

.vj4m2tb3q {
  stop-color: var(--svg-color--ffd336, #FFD336);
}

.vqiy7zq_f {
  stop-color: var(--svg-color--53329c, #53329C);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.w1102jwkv {
  stop-color: var(--svg-color--cd9f3b, #CD9F3B);
  stop-opacity: 0;
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w7mjpac8w {
  stop-color: var(--svg-color--8569a1, #8569A1);
  stop-opacity: 0;
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wwlvfha4h {
  stop-color: var(--svg-color--ffc028, #FFC028);
}

.x-1h17b9i {
  stop-color: var(--svg-color--b77a28, #B77A28);
}

.x0hvtbbrr {
  stop-color: var(--svg-color--785e96, #785E96);
  stop-opacity: 0;
}

.x5ozldbku {
  stop-color: var(--svg-color--ffdd32, #FFDD32);
}

.x8wetqqbt {
  stop-color: var(--svg-color--cb7831, #CB7831);
}

.xg3e-vb_e {
  stop-color: var(--svg-color--d97b26, #D97B26);
  stop-opacity: 0;
}

.xg7pvujwr {
  stop-color: var(--svg-color--e79c19, #E79C19);
}

.xprjt9owh {
  stop-color: var(--svg-color--ffe134, #FFE134);
}

.xpv5cjbuo {
  stop-color: var(--svg-color--e6a736, #E6A736);
}

.xzzcm4noc {
  d: path("M22.076 14.128a1.354 1.354 0 1 0 0-2.709a1.354 1.354 0 0 0 0 2.71");
}

.y0na07-wu {
  stop-color: var(--svg-color--ffe032, #FFE032);
}

.y2jmkqeym {
  stop-color: var(--svg-color--ffe128, #FFE128);
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.yahds0bfr {
  stop-color: var(--svg-color--7b4cd2, #7B4CD2);
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yk9k1_boe {
  stop-color: var(--svg-color--e6a736, #E6A736);
  stop-opacity: 0;
}

.yocx2rbki {
  stop-color: var(--svg-color--8e6da8, #8E6DA8);
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yw4y67b7z {
  stop-color: var(--svg-color--ffe03f, #FFE03F);
  stop-opacity: 0;
}

.yx9d6ib5k {
  stop-color: var(--svg-color--7241c5, #7241C5);
  stop-opacity: 0;
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z0isz9w8b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.343 4.525c.03.306.296 1.458.687 2.155");
}

.z3vxlgnwk {
  d: path("m23 16.05l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.z7rsnjfsy {
  stop-color: var(--svg-color--b57316, #B57316);
}

.zlzo724_f {
  stop-color: var(--svg-color--896acb, #896ACB);
}

.zm-3ej5xp {
  stop-color: var(--svg-color--8362ac, #8362AC);
}

</style>
