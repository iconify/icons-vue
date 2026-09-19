<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ik2QgrL)" transform="rotate(-4.337 12.169 7.015)" class="lkpioyf1j"/><path fill="url(#ibJFVjY)" class="xt5vs6hpj"/><g filter="url(#iGHRwbe)"><path fill="url(#iZLzPIe)" class="k558rwp2v"/><path fill="url(#ii5bZ3c)" class="k558rwp2v"/></g><g filter="url(#ilZ8Heb)"><path fill="url(#iSyicic)" class="yve947blh"/></g><path fill="url(#ikYz2Ib)" class="qfb_bkbwg"/><path clip-rule="evenodd" class="wdwg5acnj"/><g filter="url(#iDxjEgb)"><path clip-rule="evenodd" class="yqieyzxqh"/></g><path class="vxqt7pqab"/><path class="m6-wa9b_n"/><path fill="url(#iFJTqOB)" class="rprodib_j"/><path fill="url(#ipIARnc)" class="z09zrg2ws"/><ellipse fill="url(#il9mm5b)" transform="rotate(23.132 10.47 5.657)" class="ywa-pi6dd"/><path class="q4uc6ifip"/><path fill="url(#iJlUcVd)" class="yyyaqhbvh"/><path fill="url(#iVvly9c)" class="yyyaqhbvh"/><path fill="url(#i37Baok)" class="yyyaqhbvh"/><path fill="url(#iabPxZc)" class="yyyaqhbvh"/><path fill="url(#iFcrfyd)" class="yyyaqhbvh"/><path class="xv7la5f4x"/><path fill="url(#iIohujc)" class="ggfbl_btw"/><path fill="url(#iS5yf8a)" class="ggfbl_btw"/><path fill="url(#iQxcAZd)" class="ggfbl_btw"/><path fill="url(#iJdCLld)" class="ggfbl_btw"/><path fill="url(#icSokZb)" class="ggfbl_btw"/><path fill="url(#i2N1fqD)" class="ggfbl_btw"/><path fill="url(#iJWW2Ge)" class="ggfbl_btw"/><circle fill="url(#imKHgze)" class="twtu81b8y"/><g filter="url(#iUNRY6b)"><path clip-rule="evenodd" class="g_bbf4oav"/></g><path class="qixt6fh6e"/><path fill="url(#iGiVXBe)" class="pkb2ecb-i"/><path fill="url(#izhFgyd)" class="pkb2ecb-i"/><path fill="url(#i9GifBm)" class="pkb2ecb-i"/><path fill="url(#in7O52b)" class="pkb2ecb-i"/><rect class="fbr4ovb4g"/><path fill="url(#iquZtwc)" class="x-14vebxg"/><path fill="url(#id3hfka)" class="x-14vebxg"/><path fill="url(#i0ULtfc)" class="x-14vebxg"/><path fill="url(#iCdbyKK)" class="x-14vebxg"/><g filter="url(#igfm6Rc)"><path class="j-b5abb0k"/><path fill="url(#irUV7Cd)" class="ue-otbbij"/><path fill="url(#iKftmnd)" class="ue-otbbij"/></g><path fill="url(#iCyMECd)" class="ue-otbbij"/><g filter="url(#i09ATuD)"><path class="ebrez8ufy"/><path fill="url(#i84p3Zm)" class="cs6b3_bft"/><path fill="url(#iJyBJ9b)" class="cs6b3_bft"/></g><g filter="url(#iTKVrsU)"><path stroke="url(#iLfe1IZ)" class="k2f_chb8t"/></g><path class="ga7_5nlso"/><path fill="url(#i6zOcxe)" class="m0ssmi6lw"/><path fill="url(#i6FOjqc)" class="m0ssmi6lw"/><path fill="url(#iazWone)" class="m0ssmi6lw"/><g filter="url(#iz11Tsb)"><path class="fn728kbvi"/><path fill="url(#iL2VgDg)" class="qm99sj_of"/></g><path class="bv6dc6b8z"/><path fill="url(#iogyNPd)" class="zthft-zgm"/><path fill="url(#iuw4bHb)" class="zthft-zgm"/><path fill="url(#itUYq8b)" class="zthft-zgm"/><path fill="url(#ixrywXc)" class="zthft-zgm"/><path fill="url(#ieX9EUc)" class="zthft-zgm"/><defs><radialGradient id="ik2QgrL" cx="0" cy="0" r="1" gradientTransform="rotate(137.185 4.859 6.944)scale(1.45254 1.83228)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="h9m8yybrj"/><stop offset="1" class="qd6gpkarr"/></radialGradient><radialGradient id="ibJFVjY" cx="0" cy="0" r="1" gradientTransform="matrix(.34044 .62018 -.78984 .43357 9.516 6.381)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="ii5bZ3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.87665 -.02605 .03176 -1.0688 13.223 5.8)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="iSyicic" cx="0" cy="0" r="1" gradientTransform="rotate(-135.779 9.51 .38)scale(6.49715 5.47476)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="yqqs-9b9v"/><stop offset="1" class="zu2i70p8m"/></radialGradient><radialGradient id="ikYz2Ib" cx="0" cy="0" r="1" gradientTransform="matrix(-.44492 .98884 -1.60681 -.72297 13.246 5.665)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="iFJTqOB" cx="0" cy="0" r="1" gradientTransform="matrix(.2837 -.00732 .01422 .55117 10.586 5.997)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ipIARnc" cx="0" cy="0" r="1" gradientTransform="matrix(.25938 -.0067 .01448 .5613 10.413 6.023)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iJlUcVd" cx="0" cy="0" r="1" gradientTransform="rotate(27.371 -18.52 13.855)scale(7.9528 2.89243)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="ssz2hzbxz"/><stop offset="1" class="qi0ilhbio"/></radialGradient><radialGradient id="iVvly9c" cx="0" cy="0" r="1" gradientTransform="matrix(7 5.09375 -5.69907 7.83185 4.984 9.19)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="txwnmebwl"/><stop offset=".956" class="lr609_zbb"/></radialGradient><radialGradient id="i37Baok" cx="0" cy="0" r="1" gradientTransform="matrix(-.85938 1.24999 -.4913 -.33777 5.077 11.081)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="yeyqi9phi"/><stop offset="1" class="j9k09pb-s"/></radialGradient><radialGradient id="iabPxZc" cx="0" cy="0" r="1" gradientTransform="matrix(.59003 .20313 -.9568 2.77923 3.535 11.237)" gradientUnits="userSpaceOnUse"><stop class="mcvrg0kam"/><stop offset="1" class="q-30hhb4p"/></radialGradient><radialGradient id="iFcrfyd" cx="0" cy="0" r="1" gradientTransform="rotate(143.499 .989 5.88)scale(.97189 1.16056)" gradientUnits="userSpaceOnUse"><stop class="bjjn4ob6s"/><stop offset="1" class="snqm-cbpd"/></radialGradient><radialGradient id="iIohujc" cx="0" cy="0" r="1" gradientTransform="rotate(141.806 6.122 10.013)scale(5.40769 7.07772)" gradientUnits="userSpaceOnUse"><stop offset=".611" class="z3ho42bzm"/><stop offset=".986" class="kl05mmksp"/></radialGradient><radialGradient id="iS5yf8a" cx="0" cy="0" r="1" gradientTransform="rotate(-159.126 10.318 5.322)scale(7.10407 10.7105)" gradientUnits="userSpaceOnUse"><stop offset=".765" class="g4frhmb7u"/><stop offset=".965" class="ls7ahvbmb"/></radialGradient><radialGradient id="iQxcAZd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.36366 1.59373 -2.8979 -6.11618 17.364 13.784)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="bhhn8hbxv"/><stop offset="1" class="lychkpbnw"/></radialGradient><radialGradient id="iJdCLld" cx="0" cy="0" r="1" gradientTransform="rotate(121.109 5.172 9.927)scale(2.11694 2.06251)" gradientUnits="userSpaceOnUse"><stop class="o6m3gysuc"/><stop offset="1" class="oqmg4vaes"/></radialGradient><radialGradient id="icSokZb" cx="0" cy="0" r="1" gradientTransform="matrix(2.125 -1.09375 .92592 1.79894 15.047 10.519)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="ciwfevm-x"/><stop offset="1" class="nim1shnhj"/></radialGradient><radialGradient id="i2N1fqD" cx="0" cy="0" r="1" gradientTransform="matrix(-.89062 .32813 -.43976 -1.19362 13.422 10.675)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="kpglbvlsk"/><stop offset="1" class="j1ev22o7x"/></radialGradient><radialGradient id="iJWW2Ge" cx="0" cy="0" r="1" gradientTransform="matrix(-.26562 -.34375 2.58518 -1.99762 15.719 15.706)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="kba1trwhz"/><stop offset="1" class="pb6-h6b6v"/></radialGradient><radialGradient id="imKHgze" cx="0" cy="0" r="1" gradientTransform="rotate(24.692 -17.275 55.426)scale(1.12213 1.1783)" gradientUnits="userSpaceOnUse"><stop class="bmfdee-fc"/><stop offset=".906" class="y5luhbaev"/></radialGradient><radialGradient id="i9GifBm" cx="0" cy="0" r="1" gradientTransform="matrix(1.33216 .125 -.21108 2.2495 12.918 10.253)" gradientUnits="userSpaceOnUse"><stop class="mx7n4_bgp"/><stop offset="1" class="pism_984o"/></radialGradient><radialGradient id="in7O52b" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 .45313 -.88734 -1.71347 17.485 8.722)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="vunrlhvcc"/><stop offset="1" class="tm7ezfuma"/></radialGradient><radialGradient id="i0ULtfc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65317 9.34098 -2.71885 -1.35439 14.084 21.27)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="y_4ptxbzf"/><stop offset="1" class="ado7u1b7k"/></radialGradient><radialGradient id="iCdbyKK" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8268 4.82559 -1.33887 -.50685 13.911 21.236)" gradientUnits="userSpaceOnUse"><stop class="hpbocun_g"/><stop offset="1" class="umrurxb6b"/></radialGradient><radialGradient id="iCyMECd" cx="0" cy="0" r="1" gradientTransform="matrix(.89465 -.29687 .493 1.48575 3.933 28.096)" gradientUnits="userSpaceOnUse"><stop class="rmzq06bzd"/><stop offset="1" class="n1b4mhj1w"/></radialGradient><radialGradient id="iJyBJ9b" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 1.96875 -.89768 .49871 17.828 21.378)" gradientUnits="userSpaceOnUse"><stop class="nkql81bxe"/><stop offset="1" class="bi5pn_1vn"/></radialGradient><radialGradient id="iL2VgDg" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 17.015 18.91)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iogyNPd" cx="0" cy="0" r="1" gradientTransform="matrix(2.87501 3.59374 -13.67711 10.94177 13.922 17.128)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="iuw4bHb" cx="0" cy="0" r="1" gradientTransform="matrix(1.01138 -2.18079 7.25457 3.36445 14.536 22.608)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="itUYq8b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.05436 1.3596 -1.29326 -1.95412 18.044 16.95)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="ieX9EUc" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 -.90625 .11383 .23944 13.515 17.237)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><linearGradient id="iZLzPIe" x1="12.919" x2="9.954" y1="6.578" y2="6.833" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="il9mm5b" x1="10.396" x2="10.589" y1="5.617" y2="5.68" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iGiVXBe" x1="15.125" x2="15.781" y1="8.034" y2="9.159" gradientUnits="userSpaceOnUse"><stop class="tseva3beu"/><stop offset="1" class="jbtab4n_d"/></linearGradient><linearGradient id="izhFgyd" x1="16.515" x2="15.109" y1="11.128" y2="8.69" gradientUnits="userSpaceOnUse"><stop class="f-yzz_-ef"/><stop offset="1" class="qlv8umoui"/></linearGradient><linearGradient id="iquZtwc" x1="12.453" x2="9.078" y1="20.19" y2="28.315" gradientUnits="userSpaceOnUse"><stop class="rshq-s3st"/><stop offset="1" class="rvpou-b_v"/></linearGradient><linearGradient id="id3hfka" x1="7.845" x2="9.12" y1="24.855" y2="25.337" gradientUnits="userSpaceOnUse"><stop class="q2m7j_fif"/><stop offset="1" class="mt6f54ber"/></linearGradient><linearGradient id="irUV7Cd" x1="5.898" x2="6.054" y1="29.151" y2="28.839" gradientUnits="userSpaceOnUse"><stop class="vrnt79u8g"/><stop offset="1" class="z-p3-w_an"/></linearGradient><linearGradient id="iKftmnd" x1="8.14" x2="7.484" y1="29.55" y2="29.112" gradientUnits="userSpaceOnUse"><stop class="sted03b1z"/><stop offset="1" class="ubkqlww9x"/></linearGradient><linearGradient id="i84p3Zm" x1="18.172" x2="19.64" y1="22.878" y2="22.222" gradientUnits="userSpaceOnUse"><stop class="rz90b38rn"/><stop offset="1" class="lngpjjb0b"/></linearGradient><linearGradient id="iLfe1IZ" x1="19.437" x2="24.375" y1="21.409" y2="21.222" gradientUnits="userSpaceOnUse"><stop class="f7j3ni3bi"/><stop offset="1" class="i_d2dkbya"/></linearGradient><linearGradient id="i6zOcxe" x1="26.14" x2="26.64" y1="19.745" y2="20.909" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="i6FOjqc" x1="26.14" x2="26.904" y1="22.706" y2="21.901" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="iazWone" x1="27.922" x2="27.515" y1="21.987" y2="22.128" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="ixrywXc" x1="13.171" x2="13.859" y1="17.378" y2="18.31" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><filter id="iGHRwbe" width="4.68" height="5.713" x="9.682" y="3.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.592157 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_533"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.411765 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_533" result="effect2_innerShadow_4002_533"/></filter><filter id="ilZ8Heb" width="7.162" height="7.559" x="9.11" y="1.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_533"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_533" result="effect2_innerShadow_4002_533"/></filter><filter id="iDxjEgb" width="1.052" height=".571" x="10.299" y="4.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_533"/></filter><filter id="iUNRY6b" width="10.118" height="5.774" x="14.278" y="7.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.552941 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_533"/></filter><filter id="igfm6Rc" width="4.813" height="3.178" x="3.933" y="27.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.286275 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_533"/></filter><filter id="i09ATuD" width="8.943" height="4.095" x="17.135" y="19.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_533"/></filter><filter id="iTKVrsU" width="6.408" height="2.475" x="18.707" y="19.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_533" stdDeviation=".2"/></filter><filter id="iz11Tsb" width="3.978" height="6.092" x="16.312" y="15.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_533"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-running" /></template>
<style>
.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.ado7u1b7k {
  stop-color: var(--svg-color--ec8b4b, #EC8B4B);
  stop-opacity: 0;
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bhhn8hbxv {
  stop-color: var(--svg-color--896fcc, #896FCC);
}

.bi5pn_1vn {
  stop-color: var(--svg-color--f3953d, #F3953D);
  stop-opacity: 0;
}

.bjjn4ob6s {
  stop-color: var(--svg-color--e9b636, #E9B636);
}

.bmfdee-fc {
  stop-color: var(--svg-color--fc9d34, #FC9D34);
}

.bv6dc6b8z {
  fill: var(--svg-color--918996, #918996);
  d: path("M17.351 14.417s-4.125 3.031-6.023 4.703a17.7 17.7 0 0 0 2.544 2.853a.92.92 0 0 0 1.23-.012c.92-.81 1.78-1.6 2.616-2.552c1.375-1.562 1.047-2.663.766-3.312c-.244-.563-.857-1.355-1.133-1.68");
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.c6vpnsb1w {
  stop-color: var(--svg-color--9c959a, #9C959A);
}

.ciwfevm-x {
  stop-color: var(--svg-color--5b39a7, #5B39A7);
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.cs6b3_bft {
  d: path("m17.937 22.808l-.652-1.278l2.613-1.683l.344 1.015l5.836-.687l-.625 1.773c-1.422.446-4.465 1.408-5.504 1.68c-1.074.281-1.848-.434-2.012-.82");
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.ebrez8ufy {
  fill: var(--svg-color--ffc439, #FFC439);
  d: path("m17.937 22.808l-.652-1.278l2.613-1.683l.344 1.015l5.836-.687l-.625 1.773c-1.422.446-4.465 1.408-5.504 1.68c-1.074.281-1.848-.434-2.012-.82");
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.f-yzz_-ef {
  stop-color: var(--svg-color--5836a4, #5836A4);
}

.f7j3ni3bi {
  stop-color: var(--svg-color--ffcc43, #FFCC43);
}

.fbr4ovb4g {
  width: 1.484px;
  height: 1.324px;
  x: 4.738px;
  y: 10.155px;
  fill: var(--svg-color--ffc039, #FFC039);
  rx: 0.662px;
}

.fn728kbvi {
  fill: var(--svg-color--97919e, #97919E);
  d: path("m17.226 21.745l-.914-2.148l1.793-3.844c1.258 1.754 1.738 2.664 1.98 3.055c.269.432.298.922-.062 1.28c-.637.57-2.13 1.342-2.797 1.657");
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.g_bbf4oav {
  fill: var(--svg-color--ffc538, #FFC538);
  fill-rule: evenodd;
  d: path("M19.704 10.332a1.85 1.85 0 0 0-1.873-.286l-2.687 1.093l-.866-2.131l2.687-1.092a4.15 4.15 0 0 1 4.2.64l2.997 2.508a.65.65 0 0 1 .085.911l-.636.772a.65.65 0 0 1-.919.085z");
}

.g4frhmb7u {
  stop-color: var(--svg-color--746399, #746399);
  stop-opacity: 0;
}

.ga7_5nlso {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m26.737 19.762l-1.234.472l-.16 1.75c.305.314 1.058 1.04 1.715 1.633c.428.387.844.467 1.146.433c.23-.027.312-.276.23-.492l-1.374-3.65a.25.25 0 0 0-.323-.146");
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
}

.ggfbl_btw {
  d: path("m13.136 9.07l.74-.39a1 1 0 0 1 .585-.107l2.003 1.774c-.23 1.789.13 3.008.9 4.077l-4.254 3.23c-1.516-2.635-1.93-5.073-1.555-6.354c.317-1.229 1.05-1.899 1.581-2.23");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h9m8yybrj {
  stop-color: var(--svg-color--d97c27, #D97C27);
}

.hpbocun_g {
  stop-color: var(--svg-color--d77364, #D77364);
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.i_d2dkbya {
  stop-color: var(--svg-color--ffcc43, #FFCC43);
  stop-opacity: 0;
}

.j-b5abb0k {
  fill: var(--svg-color--534e8c, #534E8C);
  d: path("m5.039 27.245l2.46.07l1.048 1.391l-.624 1.184a.25.25 0 0 1-.335.105l-3.41-1.748c-.197-.101-.317-.329-.197-.514c.247-.38.74-.488 1.058-.488");
}

.j1ev22o7x {
  stop-color: var(--svg-color--715fa7, #715FA7);
  stop-opacity: 0;
}

.j23k_cb2p {
  stop-color: var(--svg-color--9c959a, #9C959A);
  stop-opacity: 0;
}

.j2u_3dtev {
  stop-color: var(--svg-color--908582, #908582);
  stop-opacity: 0;
}

.j96xv6b5h {
  stop-color: var(--svg-color--917ea3, #917EA3);
  stop-opacity: 0;
}

.j9k09pb-s {
  stop-color: var(--svg-color--fea724, #FEA724);
  stop-opacity: 0;
}

.jbtab4n_d {
  stop-color: var(--svg-color--6b5396, #6B5396);
  stop-opacity: 0;
}

.k2f_chb8t {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.297 20.331l.392 1.14a.4.4 0 0 0 .435.266l4.563-.656");
}

.k558rwp2v {
  d: path("M9.94 5.16c.018-.833.277-1.24.4-1.361l3.873-.1l.15 3.28c-.843 2.225-3.585 2.39-4.015 1.605s-.43-2.461-.409-3.425");
}

.kba1trwhz {
  stop-color: var(--svg-color--7052bb, #7052BB);
}

.kg-rnkb9f {
  stop-color: var(--svg-color--827483, #827483);
  stop-opacity: 0;
}

.kl05mmksp {
  stop-color: var(--svg-color--836dbc, #836DBC);
}

.kpglbvlsk {
  stop-color: var(--svg-color--715fa7, #715FA7);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.lkpioyf1j {
  d: path("M12.169 7.015h1.946v3.44h-1.946z");
}

.lngpjjb0b {
  stop-color: var(--svg-color--ffb657, #FFB657);
  stop-opacity: 0;
}

.lr609_zbb {
  stop-color: var(--svg-color--e77553, #E77553);
}

.ls7ahvbmb {
  stop-color: var(--svg-color--746399, #746399);
}

.lychkpbnw {
  stop-color: var(--svg-color--896fcc, #896FCC);
  stop-opacity: 0;
}

.m0ssmi6lw {
  d: path("m26.737 19.762l-1.234.472l-.16 1.75c.305.314 1.058 1.04 1.715 1.633c.428.387.844.467 1.146.433c.23-.027.312-.276.23-.492l-1.374-3.65a.25.25 0 0 0-.323-.146");
}

.m6-wa9b_n {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.3 6.026L11.324 6c-.01-.406-.249-.73-.532-.722c-.283.007-.504.342-.494.748");
}

.mcvrg0kam {
  stop-color: var(--svg-color--ffd05b, #FFD05B);
}

.mt6f54ber {
  stop-color: var(--svg-color--ffd558, #FFD558);
  stop-opacity: 0;
}

.mx7n4_bgp {
  stop-color: var(--svg-color--806cb1, #806CB1);
}

.n1b4mhj1w {
  stop-color: var(--svg-color--64628c, #64628C);
  stop-opacity: 0;
}

.n8gqlhnrc {
  stop-color: var(--svg-color--9583a6, #9583A6);
  stop-opacity: 0;
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nim1shnhj {
  stop-color: var(--svg-color--5b39a7, #5B39A7);
  stop-opacity: 0;
}

.nkql81bxe {
  stop-color: var(--svg-color--f3953d, #F3953D);
}

.o6m3gysuc {
  stop-color: var(--svg-color--68549d, #68549D);
}

.oqmg4vaes {
  stop-color: var(--svg-color--68549d, #68549D);
  stop-opacity: 0;
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
}

.pb6-h6b6v {
  stop-color: var(--svg-color--7052bb, #7052BB);
  stop-opacity: 0;
}

.pism_984o {
  stop-color: var(--svg-color--6c57a8, #6C57A8);
  stop-opacity: 0;
}

.pkb2ecb-i {
  d: path("M17.85 10.188L16.524 7.47L13.76 8.792a1.483 1.483 0 0 0 1.255 2.687z");
}

.q-30hhb4p {
  stop-color: var(--svg-color--ffd05b, #FFD05B);
  stop-opacity: 0;
}

.q2m7j_fif {
  stop-color: var(--svg-color--ffd558, #FFD558);
}

.q4uc6ifip {
  fill: var(--svg-color--ffb93c, #FFB93C);
  d: path("M3.761 11.987c-.285-.363-.293-.87-.07-1.293s.547-.832 1.016-.812c.328.013.598.276.711.619q.105.027.206.076l3 1.447a1.6 1.6 0 0 0 1.639-.148l2.223-1.622a1.15 1.15 0 1 1 1.356 1.858l-2.224 1.622a3.9 3.9 0 0 1-3.993.362l-2.918-1.421c-.246-.121-.72-.4-.946-.688");
}

.qd6gpkarr {
  stop-color: var(--svg-color--eaaa45, #EAAA45);
}

.qfb_bkbwg {
  d: path("M12.66 6.657c-.053.001-.09-.046-.085-.098l.147-1.304c.006-.055.057-.095.11-.081a.754.754 0 0 1-.172 1.483");
}

.qi0ilhbio {
  stop-color: var(--svg-color--ff9b2a, #FF9B2A);
}

.qixt6fh6e {
  fill: var(--svg-color--6b47b8, #6B47B8);
  d: path("M17.85 10.188L16.524 7.47L13.76 8.792a1.483 1.483 0 0 0 1.255 2.687z");
}

.qlv8umoui {
  stop-color: var(--svg-color--5836a4, #5836A4);
  stop-opacity: 0;
}

.qm99sj_of {
  d: path("m17.226 21.745l-.914-2.148l1.793-3.844c1.258 1.754 1.738 2.664 1.98 3.055c.269.432.298.922-.062 1.28c-.637.57-2.13 1.342-2.797 1.657");
}

.rmzq06bzd {
  stop-color: var(--svg-color--64628c, #64628C);
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.rprodib_j {
  d: path("M10.927 6.01v-.004c-.008-.332-.158-.598-.333-.593c-.176.004-.312.277-.303.61v.004z");
}

.rshq-s3st {
  stop-color: var(--svg-color--ffc235, #FFC235);
}

.ruyfycb4r {
  stop-color: var(--svg-color--444367, #444367);
}

.rvpou-b_v {
  stop-color: var(--svg-color--ffc443, #FFC443);
}

.rz90b38rn {
  stop-color: var(--svg-color--ffb657, #FFB657);
}

.snqm-cbpd {
  stop-color: var(--svg-color--e9b636, #E9B636);
  stop-opacity: 0;
}

.sq7_rccwx {
  stop-color: var(--svg-color--885fa7, #885FA7);
}

.ssz2hzbxz {
  stop-color: var(--svg-color--ff9b2a, #FF9B2A);
  stop-opacity: 0;
}

.sted03b1z {
  stop-color: var(--svg-color--4c438d, #4C438D);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.tm7ezfuma {
  stop-color: var(--svg-color--7d68ba, #7D68BA);
  stop-opacity: 0;
}

.tseva3beu {
  stop-color: var(--svg-color--6b5396, #6B5396);
}

.twtu81b8y {
  cx: 22.204px;
  cy: 12.201px;
  r: 0.63px;
}

.txwnmebwl {
  stop-color: var(--svg-color--ff9231, #FF9231);
  stop-opacity: 0;
}

.ubkqlww9x {
  stop-color: var(--svg-color--4c438d, #4C438D);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ue-otbbij {
  d: path("m5.039 27.245l2.46.07l1.048 1.391l-.624 1.184a.25.25 0 0 1-.335.105l-3.41-1.748c-.197-.101-.317-.329-.197-.514c.247-.38.74-.488 1.058-.488");
}

.umrurxb6b {
  stop-color: var(--svg-color--d77364, #D77364);
  stop-opacity: 0;
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vrnt79u8g {
  stop-color: var(--svg-color--443088, #443088);
}

.vunrlhvcc {
  stop-color: var(--svg-color--7d68ba, #7D68BA);
}

.vuvc8_ujh {
  stop-color: var(--svg-color--444367, #444367);
  stop-opacity: 0;
}

.vx88q5bse {
  stop-color: var(--svg-color--484083, #484083);
  stop-opacity: 0;
}

.vxqt7pqab {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M11.35 5.469c-.14-.133-.367-.158-.463-.154l.326.476c.153-.013.31-.157.136-.322");
}

.wdwg5acnj {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M11.102 7.162a.13.13 0 0 1 .003.183c-.24.25-.596.32-.71.335a.13.13 0 1 1-.032-.257c.096-.013.378-.074.556-.258a.13.13 0 0 1 .183-.003");
}

.x-14vebxg {
  d: path("M9.015 22.097a855 855 0 0 1-1.546 5.218l1.074 1.391c.86-1.614 2.641-4.987 2.93-5.66c.242-.566.566-.711.808-.856l1.34-.804l-1.973-2.473c-.12.094-.594.445-1.32 1.074c-.734.637-1.169 1.618-1.313 2.11");
}

.xt5vs6hpj {
  d: path("M9.686 6.222c.159-.156.236-.386.256-.48l.186-.006l.03 1.168c-.219.147-.538.133-.638-.077c-.086-.18-.031-.41.166-.605");
}

.xv7la5f4x {
  fill: var(--svg-color--7351bf, #7351BF);
  d: path("m13.136 9.07l.74-.39a1 1 0 0 1 .585-.107l2.003 1.774c-.23 1.789.13 3.008.9 4.077l-4.254 3.23c-1.516-2.635-1.93-5.073-1.555-6.354c.317-1.229 1.05-1.899 1.581-2.23");
}

.y_4ptxbzf {
  stop-color: var(--svg-color--ec8b4b, #EC8B4B);
}

.y5luhbaev {
  stop-color: var(--svg-color--e17e4b, #E17E4B);
}

.yeyqi9phi {
  stop-color: var(--svg-color--fea724, #FEA724);
}

.yqieyzxqh {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M10.803 4.941a.8.8 0 0 0-.225-.01a.156.156 0 1 1-.046-.308c.073-.011.193-.011.325.011c.132.023.29.072.428.17a.156.156 0 1 1-.179.254a.8.8 0 0 0-.303-.117");
}

.yqqs-9b9v {
  stop-color: var(--svg-color--ffba29, #FFBA29);
}

.yve947blh {
  d: path("M9.592 3.822c-.189-.42-.005-.876.09-1.032c.364-.707 1.152-.773 1.612-.585c.541.221.704.342 1.564.073c.861-.27 1.933-.184 2.519.807c.585.99.006 2.137.16 2.75c.153.612.549.662.713 1.372c.147.986-.449 1.646-.988 1.806c-.54.16-1.662.043-2.05-.856c-.635-1.47-.247-2.183-.396-2.926c-.15-.742-.6-.941-1.407-.758c-.95.215-1.565-.09-1.817-.65");
}

.ywa-pi6dd {
  cx: 10.47px;
  cy: 5.657px;
  rx: 0.067px;
  ry: 0.091px;
}

.yyyaqhbvh {
  d: path("M3.761 11.987c-.285-.363-.293-.87-.07-1.293s.547-.832 1.016-.812c.328.013.598.276.711.619q.105.027.206.076l3 1.447a1.6 1.6 0 0 0 1.639-.148l2.223-1.622a1.15 1.15 0 1 1 1.356 1.858l-2.224 1.622a3.9 3.9 0 0 1-3.993.362l-2.918-1.421c-.246-.121-.72-.4-.946-.688");
}

.z-p3-w_an {
  stop-color: var(--svg-color--534f8c, #534F8C);
  stop-opacity: 0;
}

.z09zrg2ws {
  d: path("m10.725 6.015l.002-.075c-.005-.192-.09-.346-.192-.344c-.1.003-.178.161-.173.354q0 .038.006.075z");
}

.z3ho42bzm {
  stop-color: var(--svg-color--836dbc, #836DBC);
  stop-opacity: 0;
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

.zthft-zgm {
  d: path("M17.351 14.417s-4.125 3.031-6.023 4.703a17.7 17.7 0 0 0 2.544 2.853a.92.92 0 0 0 1.23-.012c.92-.81 1.78-1.6 2.616-2.552c1.375-1.562 1.047-2.663.766-3.312c-.244-.563-.857-1.355-1.133-1.68");
}

.zu2i70p8m {
  stop-color: var(--svg-color--ffb029, #FFB029);
}

</style>
