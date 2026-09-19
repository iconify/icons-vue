<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#isJSOdc)" class="u20glubrv"/><path fill="url(#ib5Q9dc)" class="u20glubrv"/><path fill="url(#iS1nHyb)" class="u20glubrv"/><path fill="url(#iOzabcD)" class="u20glubrv"/><path fill="url(#i92qmGe)" class="u20glubrv"/><path fill="url(#iZenc8c)" class="fwk1cccir"/><path fill="url(#imegCXd)" class="fwk1cccir"/><g filter="url(#iAFSOjb)"><path fill="url(#iS3wa7b)" class="onlyh41-v"/><path fill="url(#iZKLFxb)" class="onlyh41-v"/></g><path fill="url(#idBPj3b)" class="cyzd0orik"/><g filter="url(#iFci02x)"><path fill="url(#iEjPYgX)" class="n5s_jmfjd"/><path fill="url(#iDuToeQ)" class="n5s_jmfjd"/></g><g filter="url(#iMY8BFc)"><path clip-rule="evenodd" class="d-oj02bhv"/></g><path fill="url(#ilLsepe)" class="fh6lz2byj"/><path fill="url(#ikgV5Dc)" class="fh6lz2byj"/><path fill="url(#iKKSBYV)" class="fh6lz2byj"/><path fill="url(#iMS09jc)" class="fh6lz2byj"/><path fill="url(#iEsPyWb)" class="r3kjru5pk"/><path fill="url(#iCIUKvd)" class="r3kjru5pk"/><path fill="url(#iv7Upid)" class="r3kjru5pk"/><path fill="url(#iqVzvKd)" class="r3kjru5pk"/><g filter="url(#iJBVEHb)"><path fill="url(#i5kLHMd)" class="uulepxbde"/></g><g filter="url(#iOffi1d)"><path fill="url(#iB3zRLd)" class="wz5nbobfe"/></g><path fill="url(#iKiHcbb)" class="wz5nbobfe"/><path fill="url(#iqaIXPc)" class="wz5nbobfe"/><path fill="url(#iAZZNzb)" class="wz5nbobfe"/><g filter="url(#ieDJJjd)"><path class="mc718w60c"/></g><g filter="url(#ifgWyIb)"><circle class="sw824ncpr"/></g><g filter="url(#ii5QtGe)"><circle class="fj0yz_bxo"/></g><g filter="url(#iN9SlWb)"><circle fill="url(#iQWVlgf)" class="k-woaxbco"/></g><g filter="url(#iHvsNIq)"><circle fill="url(#i1xsAGY)" class="ei30mue4b"/></g><rect fill="url(#i6HnE5d)" class="k4-w_gber"/><rect fill="url(#iDC5zVc)" class="k4-w_gber"/><rect fill="url(#iwfHt9d)" class="k4-w_gber"/><rect fill="url(#iVReSue)" class="k4-w_gber"/><g filter="url(#ifHxAwc)"><path fill="url(#iHrAMlb)" class="uxsl2bcrx"/></g><path fill="url(#igrMGEd)" class="uxsl2bcrx"/><g filter="url(#iGAIvhc)"><path class="od7v9yb-r"/><path fill="url(#iV7fCwb)" class="bncqycl0m"/><path fill="url(#iQlpT3b)" class="bncqycl0m"/><path fill="url(#iQbtvjb)" class="bncqycl0m"/></g><g filter="url(#i6FL91g)"><circle fill="url(#in03t1b)" class="ze44yb5sy"/><circle fill="url(#iHjr1Ec)" class="ze44yb5sy"/></g><g filter="url(#iv8d99b)"><circle fill="url(#iePF9Nc)" class="jv15ttban"/></g><circle fill="url(#iVxLqUd)" class="jv15ttban"/><g filter="url(#i54F8ie)"><circle fill="url(#itMTmFe)" class="it0fjhsyk"/></g><g filter="url(#igoL39b)"><circle fill="url(#icDRRrq)" class="zt84ve0na"/><circle fill="url(#iwWgkie)" class="zt84ve0na"/></g><g filter="url(#iX6twge)"><circle class="npzu-lhln"/><circle fill="url(#iJdDjHe)" class="l1s8r78-t"/><circle fill="url(#iEBn79d)" class="l1s8r78-t"/></g><g filter="url(#iIeCAbb)"><path fill="url(#i01vHre)" class="ik_0lbc2c"/><path fill="url(#iu3Nybk)" class="ik_0lbc2c"/><path fill="url(#iFuKhAd)" class="ik_0lbc2c"/></g><path fill="url(#iVqUsjd)" class="ik_0lbc2c"/><path fill="url(#iNszLgD)" class="ik_0lbc2c"/><path fill="url(#i3k4Tnb)" class="ik_0lbc2c"/><g filter="url(#if7FOMe)"><path fill="url(#imJTMGc)" class="ptmj4k9iv"/></g><g filter="url(#iFxCsVb)"><path class="ue55907gp"/><path fill="url(#iTy46Wc)" class="w50_9yv8z"/><path fill="url(#iCeKLMd)" class="w50_9yv8z"/><path fill="url(#iD9tq7c)" class="w50_9yv8z"/><path fill="url(#iPBc1bb)" class="w50_9yv8z"/></g><g filter="url(#ibPC9kc)"><path class="e8i4rxbyq"/></g><g filter="url(#iKfbZ2t)"><path class="gz4hdcxqr"/><path fill="url(#iYPAFUc)" class="z4tu46reo"/><path fill="url(#iSrPeJc)" class="z4tu46reo"/><path fill="url(#isMleMf)" class="z4tu46reo"/><path fill="url(#i44PD5b)" class="z4tu46reo"/></g><g filter="url(#iJP2jdd)"><path fill="url(#iJQAyAb)" class="jtyod-blm"/></g><g filter="url(#iCFXcDe)"><path stroke="url(#ibw4Mhb)" class="i2dybtqva"/></g><path class="ubrs-bctf"/><g filter="url(#ipM1UYd)"><path class="nvdw7829u"/><path fill="url(#igWUDmd)" class="pkcglwbkx"/></g><g filter="url(#iW6Gz4c)"><path class="hm0g8_bfx"/><path fill="url(#ijJQpfb)" class="t_8u16qsh"/></g><path class="zp--al1eg"/><path fill="url(#iPblfdc)" class="ry7_t_boz"/><path class="c0g91f1_o"/><g filter="url(#iIGF2Ge)"><path class="r-w6c-b9x"/><path fill="url(#iZmOxjc)" class="owmzu2bjp"/></g><g filter="url(#iDb66fT)"><path fill="url(#iYC74pb)" class="pb7unhq3c"/></g><path class="giw350bfu"/><path fill="url(#ikDoENe)" class="b6bpc2c7c"/><path class="iz5jq4bxn"/><g filter="url(#iGNKGBd)"><path fill="url(#idp6Oui)" class="fjze36bgs"/></g><g filter="url(#iMgAIVc)"><ellipse transform="rotate(-27.914 13.615 9.912)" class="ymo61nddj"/><ellipse fill="url(#iz4jQDe)" transform="rotate(-27.914 13.615 9.912)" class="la41nacxs"/></g><g filter="url(#iEN7bhb)"><path stroke="url(#iZ7tYic)" class="gdaxw7kdg"/></g><g filter="url(#iwDQmbd)"><path stroke="url(#iMTzIdS)" class="kqbcczbhj"/></g><g filter="url(#iNU6V1c)"><path stroke="url(#iMym4mc)" class="kiuv3bb0l"/></g><defs><radialGradient id="isJSOdc" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.314)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="ib5Q9dc" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.77 10.812)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="iS1nHyb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.225)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="iZenc8c" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.241 2.61)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="imegCXd" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.126)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="iS3wa7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.381)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="idBPj3b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.537)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="iEjPYgX" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.096 22.506)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="iDuToeQ" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.349 13.024)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="ikgV5Dc" cx="0" cy="0" r="1" gradientTransform="rotate(-152.488 10.104 8.356)scale(1.16274 3.57827)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="iKKSBYV" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 -.22754 .55824 1.95507 13.236 18.647)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="iCIUKvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.39062 .34376 -1.28105 5.18228 17.174 18.742)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="iv7Upid" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .35156 -1.56152 -1.21452 17.276 19.382)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="iB3zRLd" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.075 11.855)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="iKiHcbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91838 1.78314 -4.30906 -2.21931 13.135 16.263)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="iqaIXPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.94239 -.4885 0 11.747 16.32)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="iAZZNzb" cx="0" cy="0" r="1" gradientTransform="matrix(.0919 1.7035 -.36222 .01954 10.658 20.616)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="iQWVlgf" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.875 16.043)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="i1xsAGY" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.493 14.54)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iDC5zVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.26562 -2.59161 0 16.012 16.824)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="d-u8-kbex"/><stop offset="1" class="mv2j_rbqw"/></radialGradient><radialGradient id="iwfHt9d" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 -1.22153 .56328 .63405 16.697 18.78)" gradientUnits="userSpaceOnUse"><stop class="s63rm99ts"/><stop offset="1" class="lhrzwlh3v"/></radialGradient><radialGradient id="iVReSue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4375 -1.32812 .29393 -.31814 15.353 18.543)" gradientUnits="userSpaceOnUse"><stop class="r3a9gccgj"/><stop offset="1" class="atoivyxyp"/></radialGradient><radialGradient id="iHrAMlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.73)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="igrMGEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.104)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="iQlpT3b" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.438 6.854)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="iQbtvjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 18.96)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="in03t1b" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.375 12.583)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iHjr1Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.32)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="iePF9Nc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75472 0 0 3.07077 9.653 10.69)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iVxLqUd" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 8.88 3.231)scale(1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iwWgkie" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.207 10.425)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iJdDjHe" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.794 11.51)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iEBn79d" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.58 30.678)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iu3Nybk" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 18.416 9.418)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="iFuKhAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37399 1.70868 0 13.858 9.552)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="i3k4Tnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.08718 -10.8268 0 15.942 9.156)" gradientUnits="userSpaceOnUse"><stop offset=".621" class="gjuy173ra"/><stop offset="1" class="ta0qu5bfy"/></radialGradient><radialGradient id="iTy46Wc" cx="0" cy="0" r="1" gradientTransform="matrix(.79775 -2.95637 1.09632 .29583 20.415 6.583)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="iCeKLMd" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -43.14 206.838)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="iD9tq7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 16.07 2.089)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iPBc1bb" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 9.622 8.906)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="i44PD5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 16.398 12.296)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="igWUDmd" cx="0" cy="0" r="1" gradientTransform="matrix(.10418 -.60322 1.78457 .30822 18.513 8.605)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="ijJQpfb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.792 -3.633)scale(.61215 1.81109)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iPblfdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 18.249 10.007)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iZmOxjc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 18.02 10.092)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikDoENe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.886 10.007)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iz4jQDe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.834 -1.581)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iAFSOjb" width="4.081" height="11.683" x="5.07" y="18.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/></filter><filter id="iFci02x" width="5.909" height="14.117" x="12.858" y="15.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/></filter><filter id="iMY8BFc" width="7.13" height="5.229" x="12.285" y="16.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".3"/></filter><filter id="iJBVEHb" width="7.239" height="14.645" x="9.195" y="15.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".5"/></filter><filter id="iOffi1d" width="5.917" height="14.31" x="10.326" y="15.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3331" result="effect2_innerShadow_4002_3331"/></filter><filter id="ieDJJjd" width="6.504" height="14.261" x="15.345" y="15.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3331" result="effect2_innerShadow_4002_3331"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3331" result="effect3_innerShadow_4002_3331"/></filter><filter id="ifgWyIb" width="2" height="2" x="14.731" y="24.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".25"/></filter><filter id="ii5QtGe" width="2" height="2" x="14.731" y="21.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".25"/></filter><filter id="iN9SlWb" width="1.05" height="1.05" x="15.504" y="25.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/></filter><filter id="iHvsNIq" width="1.05" height="1.05" x="15.504" y="22.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/></filter><filter id="ifHxAwc" width="2.465" height="2.95" x="16.029" y="17.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3331" result="effect2_innerShadow_4002_3331"/></filter><filter id="iGAIvhc" width="2.365" height="2.9" x="13.731" y="17.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/></filter><filter id="i6FL91g" width="1.717" height="1.717" x="15.204" y="17.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/></filter><filter id="iv8d99b" width="3.539" height="3.339" x="9.653" y="9.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/></filter><filter id="i54F8ie" width="2.99" height="2.99" x="9.828" y="9.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".25"/></filter><filter id="igoL39b" width="3.589" height="3.589" x="19.166" y="8.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/></filter><filter id="iX6twge" width="2.99" height="2.99" x="19.34" y="9.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".25"/></filter><filter id="iIeCAbb" width="10.373" height="12.177" x="10.913" y="5.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/></filter><filter id="if7FOMe" width="8.246" height="7.066" x="14.24" y="3.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation="1"/></filter><filter id="iFxCsVb" width="12.601" height="8.543" x="9.77" y="1.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/></filter><filter id="ibPC9kc" width="3.26" height="4.181" x="14.201" y="9.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".375"/></filter><filter id="iKfbZ2t" width="2.377" height="3.181" x="14.882" y="9.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".125"/></filter><filter id="iJP2jdd" width="2.377" height="3.181" x="14.882" y="9.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".125"/></filter><filter id="iCFXcDe" width="3.617" height="1.472" x="14.262" y="13.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".05"/></filter><filter id="ipM1UYd" width="2.979" height="1.873" x="17.252" y="7.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/></filter><filter id="iW6Gz4c" width="2.98" height="1.873" x="12.105" y="7.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3331"/></filter><filter id="iIGF2Ge" width=".787" height=".696" x="17.515" y="9.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".05"/></filter><filter id="iDb66fT" width=".891" height=".913" x="18.355" y="9.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".1"/></filter><filter id="iGNKGBd" width=".986" height="1.04" x="13.913" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".1"/></filter><filter id="iMgAIVc" width=".913" height=".704" x="13.159" y="9.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".05"/></filter><filter id="iEN7bhb" width="2.599" height="1.181" x="17.356" y="7.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".125"/></filter><filter id="iwDQmbd" width="2.677" height="1.238" x="12.137" y="7.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".125"/></filter><filter id="iNU6V1c" width="1.008" height="2.269" x="10.905" y="5.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3331" stdDeviation=".125"/></filter><linearGradient id="iOzabcD" x1="23.131" x2="22.971" y1="29.905" y2="29.905" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="i92qmGe" x1="8.858" x2="9.061" y1="29.905" y2="29.905" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="iZKLFxb" x1="9.19" x2="7.596" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="ilLsepe" x1="14.705" x2="13.268" y1="19.975" y2="16.85" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="zynu2nm7a"/></linearGradient><linearGradient id="iMS09jc" x1="15.518" x2="15.209" y1="20.053" y2="19.936" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="iEsPyWb" x1="16.799" x2="18.471" y1="19.991" y2="17.116" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="ig120dbzq"/></linearGradient><linearGradient id="iqVzvKd" x1="16.486" x2="16.713" y1="19.792" y2="19.702" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="i5kLHMd" x1="12.815" x2="12.815" y1="16.772" y2="29.417" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="i6HnE5d" x1="17.033" x2="14.384" y1="18.382" y2="18.512" gradientUnits="userSpaceOnUse"><stop class="i8xst-hts"/><stop offset="1" class="bkwwoacyf"/></linearGradient><linearGradient id="iV7fCwb" x1="15.205" x2="14.838" y1="19.428" y2="18.975" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="itMTmFe" x1="11.323" x2="10.682" y1="10.968" y2="10.968" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="icDRRrq" x1="21.922" x2="21.103" y1="9.598" y2="12.134" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="i01vHre" x1="20.106" x2="12.47" y1="11.079" y2="12.216" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iVqUsjd" x1="10.675" x2="12.556" y1="13.774" y2="13.707" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="iNszLgD" x1="20.991" x2="19.879" y1="12.933" y2="12.836" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="imJTMGc" x1="15.539" x2="23.682" y1="8.094" y2="5.179" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="iYPAFUc" x1="15.206" x2="16.144" y1="11.738" y2="11.738" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iSrPeJc" x1="17.009" x2="15.983" y1="12.06" y2="12.046" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="isMleMf" x1="16.265" x2="16.265" y1="12.803" y2="12.23" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iJQAyAb" x1="16.07" x2="16.07" y1="9.912" y2="10.84" gradientUnits="userSpaceOnUse"><stop class="gtmlp_nxh"/><stop offset="1" class="gqwz64btm"/></linearGradient><linearGradient id="ibw4Mhb" x1="15.033" x2="15.468" y1="14.418" y2="13.73" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iYC74pb" x1="19.027" x2="18.713" y1="10.061" y2="10.254" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="idp6Oui" x1="14.63" x2="14.316" y1="10.061" y2="10.254" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZ7tYic" x1="19.042" x2="18.622" y1="7.922" y2="7.063" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iMTzIdS" x1="13.738" x2="12.549" y1="7.794" y2="7.295" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iMym4mc" x1="11.409" x2="11.409" y1="5.78" y2="7.937" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-in-tuxedo-medium" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.atoivyxyp {
  stop-color: var(--svg-color--4f3026, #4F3026);
  stop-opacity: 0;
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

.b6bpc2c7c {
  d: path("M13.884 9.53a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
}

.bkwwoacyf {
  stop-color: var(--svg-color--593a35, #593A35);
}

.bncqycl0m {
  d: path("m14.133 17.474l1.813 1.251l-1.795 1.258a.246.246 0 0 1-.389-.187c-.04-.79-.04-1.569-.007-2.143a.239.239 0 0 1 .378-.18");
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c0g91f1_o {
  fill: var(--svg-color--000, #000);
  d: path("M17.74 10.423c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.06-.235");
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
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

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cyzd0orik {
  d: path("M8.901 18.228a10.68 10.68 0 0 0-3.831 8.18v3.497H8.9z");
}

.cyzx27bkq {
  stop-color: var(--svg-color--978394, #978394);
}

.d-oj02bhv {
  fill: var(--svg-color--9c80b1, #9C80B1);
  fill-rule: evenodd;
  d: path("M12.889 16.68c-.037.824.18 2.636 1.367 3.87c.255.266.715.18.863-.128l.73-1.435l.731 1.435c.149.308.608.394.863.128c1.186-1.234 1.404-3.046 1.368-3.87z");
}

.d-u8-kbex {
  stop-color: var(--svg-color--7c4b59, #7C4B59);
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.e8i4rxbyq {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.795 10.567l-.82 1.7c-.102.35.142.699.488.699h.737c.346 0 .59-.355.488-.7l-.498-1.699c-.107-.376-.283-.376-.395 0");
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.ei30mue4b {
  cx: 16.004px;
  cy: 22.566px;
  r: 0.5px;
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.ff2asxc8d {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
}

.fh6lz2byj {
  d: path("M14.41 20.276c-1.185-1.235-1.403-3.046-1.367-3.871h2.969l.035 2.223l-.773 1.52c-.148.308-.608.393-.863.128");
}

.fj0yz_bxo {
  cx: 15.731px;
  cy: 22.699px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
}

.fj3b0ib3x {
  stop-color: var(--svg-color--564561, #564561);
  stop-opacity: 0;
}

.fjze36bgs {
  d: path("M14.7 10.318c0-.289-.235-.48-.298-.539l-.289.279l.178.361z");
}

.fojlwlb9t {
  stop-color: var(--svg-color--dfc6d4, #DFC6D4);
  stop-opacity: 0;
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwk1cccir {
  d: path("M23.099 18.228a10.68 10.68 0 0 1 3.831 8.18v3.497H23.1z");
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.gdaxw7kdg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.73 7.825c.43-.075 1.27-.054 1.85.398");
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.giw350bfu {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.677 9.259c-.652 0-1.204.45-1.354 1.058c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.127");
}

.gjuy173ra {
  stop-color: var(--svg-color--986470, #986470);
  stop-opacity: 0;
}

.gqwz64btm {
  stop-color: var(--svg-color--ad8272, #AD8272);
  stop-opacity: 0;
}

.gtmlp_nxh {
  stop-color: var(--svg-color--ad8272, #AD8272);
}

.gz4hdcxqr {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.688 10.404l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.114-.376-.646-.376-.765 0");
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hm0g8_bfx {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m12.297 7.97l.002-.002l.002-.001l.004-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 0 1-.166 1.055a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.679-.823");
}

.i2dybtqva {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.07 13.819c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.919.845 1.583.845c.665 0 1.248-.338 1.583-.845c.086-.13-.06-.279-.198-.21c-.4.21-.872.329-1.385.329Z");
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.i8xst-hts {
  stop-color: var(--svg-color--7b5c51, #7B5C51);
}

.ig120dbzq {
  stop-color: var(--svg-color--aea5b6, #AEA5B6);
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.ik_0lbc2c {
  d: path("M10.913 8.638c0-.266.107-.586.322-.746l.16-.16c.269-.214.376-.534.376-.854v-.853c0-.267.16-.48.429-.533c.644-.16 1.985-.427 3.915-.427c1.931 0 3.272.267 3.916.427c.214.053.429.266.429.533v.853c0 .32.16.64.375.854c.502.351.471.545.43.96c-.054.533-.108 1.44-.108 1.44h.018l-.266 3.957c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003c-.14-1.816-.2-3.638-.366-5.45");
}

.it0fjhsyk {
  cx: 11.323px;
  cy: 10.69px;
  r: 0.995px;
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.iz5jq4bxn {
  fill: var(--svg-color--000, #000);
  d: path("M14.395 10.423a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.235");
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.jtyod-blm {
  d: path("m15.688 10.194l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.114-.376-.646-.376-.765 0");
}

.jv15ttban {
  cx: 11.323px;
  cy: 10.69px;
  r: 1.669px;
}

.k-woaxbco {
  cx: 16.004px;
  cy: 25.574px;
  r: 0.5px;
}

.k4-w_gber {
  width: 3.875px;
  height: 4.5px;
  x: 14.075px;
  y: 14.28px;
  rx: 1.938px;
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kiuv3bb0l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.538 5.879v.897c-.008.149-.07.481-.258.622");
}

.kqbcczbhj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.512 8.343c.327-.289 1.041-.593 1.927-.452");
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.l1s8r78-t {
  cx: 20.835px;
  cy: 10.69px;
  r: 0.995px;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.la41nacxs {
  cx: 13.615px;
  cy: 9.912px;
  rx: 0.389px;
  ry: 0.197px;
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lhrzwlh3v {
  stop-color: var(--svg-color--5d3e32, #5D3E32);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mc718w60c {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.316 17.542c.031-1.094-.595-1.537-.887-1.626l-.668-.07v5.815c0 3.874-1.388 6.264-2.648 8.09c-.062.09.047.2.139.138c2.976-2.036 4.851-4.005 5.196-9.228a.203.203 0 0 0-.188-.215c-.321-.02-.607-.047-.809-.066a.204.204 0 0 1-.185-.206c.011-.575.022-1.66.05-2.632");
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mv2j_rbqw {
  stop-color: var(--svg-color--7c4b59, #7C4B59);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n5s_jmfjd {
  d: path("M18.767 16.056a10.3 10.3 0 0 0-2.337-.268h-.86a10.3 10.3 0 0 0-2.312.262v5.422c0 4.175 1.065 5.972 2.654 8.433h.285c1.59-2.461 2.57-4.258 2.57-8.433z");
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.npzu-lhln {
  cx: 20.835px;
  cy: 10.69px;
  r: 0.995px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.nvdw7829u {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m19.79 7.97l-.002-.002l-.002-.001l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.24-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 0 0 .166 1.055c.398-.063.716.01.934.096a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.823");
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od7v9yb-r {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.474l1.813 1.251l-1.795 1.258a.246.246 0 0 1-.389-.187c-.04-.79-.04-1.569-.007-2.143a.239.239 0 0 1 .378-.18");
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.onlyh41-v {
  d: path("M8.901 18.228a10.69 10.69 0 0 0-3.831 8.185v3.498H8.9z");
}

.owmzu2bjp {
  d: path("M18.186 9.72c.063.084-.07.188-.22.3c-.152.114-.264.193-.328.108c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.pb7unhq3c {
  d: path("M19.046 10.305a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.pkcglwbkx {
  d: path("m19.79 7.97l-.002-.002l-.002-.001l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.24-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 0 0 .166 1.055c.398-.063.716.01.934.096a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.823");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ptmj4k9iv {
  d: path("m20.034 5.065l-3.078 1.026a1.047 1.047 0 0 0 .47 2.031l3.06-.41z");
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r-w6c-b9x {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.186 9.72c.063.084-.07.188-.22.3c-.152.114-.264.193-.328.108c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.r3a9gccgj {
  stop-color: var(--svg-color--4f3026, #4F3026);
}

.r3kjru5pk {
  d: path("M17.598 20.276c1.186-1.235 1.404-3.046 1.367-3.871h-2.968l-.036 2.223l.774 1.52c.148.308.608.393.863.128");
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.ry7_t_boz {
  d: path("M18.251 9.53a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.127");
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.s63rm99ts {
  stop-color: var(--svg-color--5d3e32, #5D3E32);
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.sw824ncpr {
  cx: 15.731px;
  cy: 25.847px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.t_8u16qsh {
  d: path("m12.297 7.97l.002-.002l.002-.001l.004-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 0 1-.166 1.055a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.679-.823");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.ta0qu5bfy {
  stop-color: var(--svg-color--7f4f5f, #7F4F5F);
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.u20glubrv {
  d: path("M5.07 26.409c0-5.797 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.823 10.5 10.62v3.496H5.07z");
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.ubq14mb-s {
  stop-color: var(--svg-color--422131, #422131);
}

.ubrs-bctf {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.07 13.819c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.919.845 1.583.845c.665 0 1.248-.338 1.583-.845c.086-.13-.06-.279-.198-.21c-.4.21-.872.329-1.385.329");
}

.uc5leibtb {
  stop-color: var(--svg-color--796ba6, #796BA6);
}

.udzp2zp0e {
  stop-color: var(--svg-color--4e3566, #4E3566);
}

.ue55907gp {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m20.889 4.212l.429.213c.75.374 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.054-.906.107-1.44c.044-.432-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.271.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.106.64-.375.854l-.16.16c-.215.16-.322.48-.322.746c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.43-.213c.267-.16.536-.373.804-.587l.965-1.013c.59-.533 1.448-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.267 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.uulepxbde {
  d: path("M11.242 18.34c-.03-1.012.55-1.421.819-1.503l.617-.065v5.373c0 3.575.239 4.662 2.733 7.12l.011.015c.047.083-.05.176-.132.12c-2.75-1.881-4.776-3.354-5.094-8.18a.187.187 0 0 1 .174-.198c.297-.019.56-.044.747-.06a.19.19 0 0 0 .171-.192c-.01-.53-.02-1.532-.046-2.43");
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.uxsl2bcrx {
  d: path("m17.892 17.474l-1.813 1.251l1.795 1.258a.246.246 0 0 0 .388-.187c.041-.79.041-1.569.008-2.143a.239.239 0 0 0-.378-.18");
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
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

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.voa0z2bgu {
  stop-color: var(--svg-color--47305d, #47305D);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w50_9yv8z {
  d: path("m20.889 4.212l.429.213c.75.374 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.054-.906.107-1.44c.044-.432-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.271.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.106.64-.375.854l-.16.16c-.215.16-.322.48-.322.746c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.43-.213c.267-.16.536-.373.804-.587l.965-1.013c.59-.533 1.448-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.267 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wz5nbobfe {
  d: path("M11.709 17.542c-.032-1.094.595-1.537.886-1.626l.668-.07v5.815c0 3.874 1.453 6.262 2.712 8.088c.063.09-.047.2-.138.138c-2.977-2.036-4.916-4.003-5.26-9.226a.203.203 0 0 1 .188-.215c.321-.02.606-.047.808-.066c.107-.01.188-.1.186-.206c-.011-.575-.023-1.66-.05-2.632");
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.ymo61nddj {
  cx: 13.615px;
  cy: 9.912px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z4tu46reo {
  d: path("m15.688 10.404l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.114-.376-.646-.376-.765 0");
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.ze44yb5sy {
  cx: 16.012px;
  cy: 18.694px;
  r: 0.809px;
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

.zp--al1eg {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.458 9.259c.653 0 1.204.45 1.354 1.059a.274.274 0 0 1-.267.34h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.37-1.127");
}

.zt84ve0na {
  cx: 20.835px;
  cy: 10.69px;
  r: 1.669px;
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

.zynu2nm7a {
  stop-color: var(--svg-color--6b5977, #6B5977);
}

</style>
