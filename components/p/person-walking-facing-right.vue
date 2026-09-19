<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i1nsQQb)" transform="scale(-1 1)rotate(-4.337 80.037 240.838)" class="z8jy9-b3h"/><path fill="url(#icSmT8b)" transform="scale(-1 1)rotate(-4.337 80.037 240.838)" class="z8jy9-b3h"/><path fill="url(#iZ7aa9b)" class="kl_73lr_c"/><g filter="url(#itHB7Cb)"><path fill="url(#iSMJ4HR)" class="owigx3bpe"/><path fill="url(#i4XuSbX)" class="owigx3bpe"/></g><g filter="url(#ipGeY4b)"><path class="adaq0ebao"/><path fill="url(#iUadBfy)" class="bszqmbzpt"/><path fill="url(#iwF7EUc)" class="bszqmbzpt"/><path fill="url(#iCDa9sc)" class="bszqmbzpt"/><path fill="url(#igc7Lnb)" class="bszqmbzpt"/><path fill="url(#iZoPpJe)" class="bszqmbzpt"/></g><path fill="url(#iMBlJBe)" class="irjdxuv0o"/><g filter="url(#ihfw40Q)"><path fill="url(#ioB011n)" class="rx9sqxbed"/><path fill="url(#ivwMO4b)" class="rx9sqxbed"/><path fill="url(#ib05Mfe)" class="rx9sqxbed"/></g><g filter="url(#isPjtRv)"><path class="j_bzaeb4b"/><path fill="url(#iEnTSKe)" class="g3fqo4glu"/><path fill="url(#imTNWHh)" class="g3fqo4glu"/><path fill="url(#iJw1yqd)" class="g3fqo4glu"/><path fill="url(#iNuObqc)" class="g3fqo4glu"/><path fill="url(#iYXg6Uc)" class="g3fqo4glu"/></g><path fill="url(#i1fMzmd)" class="irx8fxn1d"/><path fill="url(#iZOf9Fb)" class="irx8fxn1d"/><path fill="url(#iOFiend)" class="irx8fxn1d"/><path fill="url(#ibKEaYd)" class="irx8fxn1d"/><path fill="url(#iJivS3K)" class="irx8fxn1d"/><path class="xmto8db1n"/><path fill="url(#ixyxped)" class="gyv6967sg"/><path fill="url(#iWYsRCe)" class="gyv6967sg"/><path fill="url(#i5APagb)" class="gyv6967sg"/><g filter="url(#iydwzEe)"><path clip-rule="evenodd" class="z6_y2in4e"/></g><path fill="url(#itjmijd)" class="qk2fd-d7d"/><path fill="url(#i8fOGHd)" class="kl3mfkb2l"/><path fill="url(#iGgJ3wo)" class="kl3mfkb2l"/><path fill="url(#irCnhQE)" class="kl3mfkb2l"/><path fill="url(#ijnaYOA)" class="kl3mfkb2l"/><circle fill="url(#iBatVRV)" transform="matrix(-1 0 0 1 11.62 17.476)" class="am9uocbqt"/><g filter="url(#ifpV2He)"><path clip-rule="evenodd" class="awpk2eb_n"/></g><path fill="url(#iHmjkqc)" class="r9z1qobnf"/><path fill="url(#ioWOwyd)" class="r9z1qobnf"/><path fill="url(#iBHWAdc)" class="r9z1qobnf"/><path fill="url(#imWDpBb)" class="khn7ydrmc"/><path clip-rule="evenodd" class="bbds8hj9q"/><g filter="url(#i9FnPlc)"><path clip-rule="evenodd" class="kmd31z90f"/></g><path class="no9rs03zd"/><path fill="url(#ieZyC7b)" class="a7ssucnzv"/><path fill="url(#ikGnU8Q)" class="ctpk5jb_q"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -21.707 -42.447)" class="m1l7k9jve"/><g filter="url(#ilwuAQc)"><path fill="url(#iP74X4n)" class="bfzot6byw"/></g><g filter="url(#iUk4rnc)"><path fill="url(#i4SycYd)" class="gvltpob4o"/></g><defs><radialGradient id="i1nsQQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.05152 -2.21336 1.59858 -.0372 1.708 2.01)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="xpz0ltqsz"/><stop offset="1" class="vj0bxeigc"/></radialGradient><radialGradient id="icSmT8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.53617 .66448 -.89991 -.72614 2.062 .438)" gradientUnits="userSpaceOnUse"><stop class="wlrmkubjk"/><stop offset="1" class="bdl3pn0lv"/></radialGradient><radialGradient id="iZ7aa9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 .60583 -.77155 -.39799 20.699 5.961)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="i4XuSbX" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 17.16 5.547)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="iUadBfy" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90805 -1.94145 2.83721 -2.78841 16.677 6.982)" gradientUnits="userSpaceOnUse"><stop class="re8izvbqw"/><stop offset="1" class="kgio6d1ee"/></radialGradient><radialGradient id="iwF7EUc" cx="0" cy="0" r="1" gradientTransform="matrix(2.125 .89062 -1.25031 2.9832 15.27 3.32)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iCDa9sc" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 -.23437 .10899 .37782 15.316 6.523)" gradientUnits="userSpaceOnUse"><stop class="jkk-xsb9b"/><stop offset="1" class="g6je8pe2z"/></radialGradient><radialGradient id="igc7Lnb" cx="0" cy="0" r="1" gradientTransform="matrix(1.79688 .32813 -.1515 .82965 16.902 1.96)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="t5jak8x3h"/><stop offset="1" class="hze7fms1a"/></radialGradient><radialGradient id="iZoPpJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.50781 .47657 -.68826 -.73338 19.816 1.874)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="an20q5kfx"/><stop offset="1" class="xh4g4qbuv"/></radialGradient><radialGradient id="iMBlJBe" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 .9414 -1.52974 .7363 16.855 5.367)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="ivwMO4b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45369 2.93958 -5.96661 -4.98038 15.047 18.024)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="oiy_54b9a"/><stop offset="1" class="rm4aiz5dn"/></radialGradient><radialGradient id="ib05Mfe" cx="0" cy="0" r="1" gradientTransform="rotate(143.616 4.553 12.044)scale(1.10629 6.64432)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="v5lz4sb9o"/><stop offset="1" class="m_uy2vb_d"/></radialGradient><radialGradient id="iEnTSKe" cx="0" cy="0" r="1" gradientTransform="rotate(-122.302 13.824 5.995)scale(6.08182 1.60193)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="mngz2ebss"/><stop offset="1" class="ttsumpbek"/></radialGradient><radialGradient id="imTNWHh" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.38588 0 15.332 16.18)" gradientUnits="userSpaceOnUse"><stop class="f3j6dkfip"/><stop offset="1" class="fxoxl0blj"/></radialGradient><radialGradient id="iNuObqc" cx="0" cy="0" r="1" gradientTransform="matrix(-.14062 -.17969 .6458 -.50541 20.027 28.093)" gradientUnits="userSpaceOnUse"><stop class="ryq0o3qru"/><stop offset="1" class="yfqxgqb1h"/></radialGradient><radialGradient id="iYXg6Uc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.375 -1.81248 4.6745 -16.4415 19.707 19.226)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ex23x-brg"/><stop offset="1" class="ux4w7lb6c"/></radialGradient><radialGradient id="i1fMzmd" cx="0" cy="0" r="1" gradientTransform="matrix(.09374 -1.53125 2.45635 .15037 21.16 29.445)" gradientUnits="userSpaceOnUse"><stop class="cl2mlwbhs"/><stop offset="1" class="yvuyjoqpy"/></radialGradient><radialGradient id="iZOf9Fb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 -.21876 .15137 -.73521 24.27 28.508)" gradientUnits="userSpaceOnUse"><stop class="m3n9jy0fh"/><stop offset="1" class="hdzwkybza"/></radialGradient><radialGradient id="iOFiend" cx="0" cy="0" r="1" gradientTransform="matrix(-.59376 -1.71875 .84778 -.29287 20.253 29.742)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="a541b3bqx"/><stop offset="1" class="zc8ie-1dg"/></radialGradient><radialGradient id="i5APagb" cx="0" cy="0" r="1" gradientTransform="rotate(-47.125 35.154 4.24)scale(1.99789 1.10527)" gradientUnits="userSpaceOnUse"><stop class="xh_da2q2q"/><stop offset="1" class="stwbr2bhy"/></radialGradient><radialGradient id="i8fOGHd" cx="0" cy="0" r="1" gradientTransform="rotate(107.896 4.378 11.87)scale(6.30507 4.4383)" gradientUnits="userSpaceOnUse"><stop offset=".446" class="pvqp1vbsj"/><stop offset="1" class="jbtp05a5b"/></radialGradient><radialGradient id="iGgJ3wo" cx="0" cy="0" r="1" gradientTransform="matrix(-3.0625 2.84375 -4.8238 -5.19485 18.675 9.726)" gradientUnits="userSpaceOnUse"><stop class="v6cmgr7lo"/><stop offset="1" class="zvi2r2b9j"/></radialGradient><radialGradient id="irCnhQE" cx="0" cy="0" r="1" gradientTransform="rotate(102.458 3.233 11.677)scale(2.75231 1.4881)" gradientUnits="userSpaceOnUse"><stop class="wb44sjbzz"/><stop offset="1" class="w8350jbiw"/></radialGradient><radialGradient id="ijnaYOA" cx="0" cy="0" r="1" gradientTransform="matrix(2.71802 .3081 -.16137 1.42362 15.3 8.597)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ayezflb3j"/><stop offset="1" class="ujjr06bwy"/></radialGradient><radialGradient id="iBatVRV" cx="0" cy="0" r="1" gradientTransform="rotate(90 .008 .406)scale(.90625)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="d69nsybly"/><stop offset="1" class="eluf2xb_e"/></radialGradient><radialGradient id="ioWOwyd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72656 -.10938 .20535 -3.24138 17.12 10.523)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="ou5ot-gfg"/><stop offset="1" class="uz8jx9bci"/></radialGradient><radialGradient id="iBHWAdc" cx="0" cy="0" r="1" gradientTransform="matrix(.40625 -3.15625 3.68021 .4737 15.144 11.758)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="z7rq8royu"/><stop offset=".958" class="p1zm9vufc"/></radialGradient><radialGradient id="imWDpBb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09375 .1806 -.14313 -.86685 23.675 16.398)" gradientUnits="userSpaceOnUse"><stop class="j4xesqbgr"/><stop offset=".839" class="fa3xzswyd"/></radialGradient><radialGradient id="ieZyC7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 19.523 5.62)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ikGnU8Q" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 19.691 5.642)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iSMJ4HR" x1="17.472" x2="20.335" y1="6.289" y2="6.461" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="ioB011n" x1="14.027" x2="11.799" y1="22.883" y2="20.939" gradientUnits="userSpaceOnUse"><stop offset=".211" class="pat1zf4-w"/><stop offset="1" class="wtea7v6lu"/></linearGradient><linearGradient id="iJw1yqd" x1="16.253" x2="16.253" y1="16.07" y2="16.414" gradientUnits="userSpaceOnUse"><stop offset=".136" class="x5p6yzbmf"/><stop offset="1" class="cnh3p8b3x"/></linearGradient><linearGradient id="ibKEaYd" x1="21.722" x2="21.636" y1="29.617" y2="29.305" gradientUnits="userSpaceOnUse"><stop class="l138bfbcs"/><stop offset="1" class="oxce79bcz"/></linearGradient><linearGradient id="iJivS3K" x1="19.753" x2="20.332" y1="29.992" y2="29.773" gradientUnits="userSpaceOnUse"><stop offset=".064" class="lhdz7oxfj"/><stop offset="1" class="csaq2_bel"/></linearGradient><linearGradient id="ixyxped" x1="11.144" x2="10.55" y1="27.976" y2="28.148" gradientUnits="userSpaceOnUse"><stop class="oxg1n1wjw"/><stop offset="1" class="y0g_czb9f"/></linearGradient><linearGradient id="iWYsRCe" x1="9.019" x2="9.199" y1="28.051" y2="27.902" gradientUnits="userSpaceOnUse"><stop class="p6qc3nb-j"/><stop offset="0" class="ezcqmvbni"/><stop offset="1" class="stwbr2bhy"/></linearGradient><linearGradient id="itjmijd" x1="19.3" x2="18.425" y1="12.836" y2="10.445" gradientUnits="userSpaceOnUse"><stop class="h2o5q3bga"/><stop offset=".787" class="md0ucwkak"/></linearGradient><linearGradient id="iHmjkqc" x1="15.269" x2="14.16" y1="9.117" y2="12.57" gradientUnits="userSpaceOnUse"><stop offset=".118" class="fjz5hab9p"/><stop offset="1" class="ljdv6tb3r"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iP74X4n" x1="19.925" x2="15.3" y1="27.414" y2="17.273" gradientUnits="userSpaceOnUse"><stop class="v9kimlbms"/><stop offset="1" class="g24ahctiy"/></linearGradient><linearGradient id="i4SycYd" x1="9.781" x2="14.092" y1="25.323" y2="19.951" gradientUnits="userSpaceOnUse"><stop class="ckhjb_bgt"/><stop offset="1" class="rnrhdzckq"/></linearGradient><filter id="itHB7Cb" width="4.443" height="5.249" x="15.892" y="3.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.52549 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_451"/></filter><filter id="ipGeY4b" width="5.503" height="5.499" x="14.769" y="1.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_451"/></filter><filter id="ihfw40Q" width="8.674" height="14.771" x="7.888" y="15.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_451"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.423529 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_451" result="effect2_innerShadow_2_451"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_2_451" result="effect3_innerShadow_2_451"/></filter><filter id="isPjtRv" width="10.972" height="14.104" x="13.646" y="15.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.592157 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_451"/></filter><filter id="iydwzEe" width="8.438" height="7.859" x="15.777" y="10.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.505882 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_451"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.466667 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_451" result="effect2_innerShadow_2_451"/></filter><filter id="ifpV2He" width="7.59" height="10.511" x="8.519" y="9.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.623529 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_451"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_451" result="effect2_innerShadow_2_451"/></filter><filter id="i9FnPlc" width="1.013" height=".568" x="18.66" y="4.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_451"/></filter><filter id="ilwuAQc" width="6.844" height="12.891" x="14.3" y="16.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_451" stdDeviation=".5"/></filter><filter id="iUk4rnc" width="6.45" height="8.475" x="8.746" y="18.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_451" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-walking-facing-right" /></template>
<style>
.a541b3bqx {
  stop-color: var(--svg-color--515279, #515279);
}

.a7ssucnzv {
  d: path("M19.195 5.642v-.004c0-.32.137-.58.307-.58s.306.26.306.58v.004z");
}

.adaq0ebao {
  fill: var(--svg-color--ffba23, #FFBA23);
  d: path("M20.156 2.496a1.025 1.025 0 0 0-.984-.578c-.86.047-.977.343-1.754.183c-.822-.169-1.227-.12-1.578.04l-.007.003c-.347.157-1.064.483-1.064 1.95c0 1.351.482 2.065.715 2.32l-.046.016c-.231.084-.327.33-.243.562c.071.197.322.311.637.262c.36-.057.624-.106.831-.147a.25.25 0 0 0 .2-.245V5.75c0-.469.33-.749.477-.832c.015-.485.163-.707.406-.824c.4-.195.526-.099 1.484-.157c.965-.058 1.223-.832.926-1.441");
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.am9uocbqt {
  cx: 0.551px;
  cy: 0.551px;
  r: 0.551px;
}

.an20q5kfx {
  stop-color: var(--svg-color--e0a531, #E0A531);
}

.awpk2eb_n {
  fill: var(--svg-color--ffbf35, #FFBF35);
  fill-rule: evenodd;
  d: path("M10.164 19.223a.614.614 0 0 0 .775-.407c1.215-3.921 3.166-6.29 4.542-7.545c.438-.4.516-1.082.128-1.53c-.346-.401-.944-.472-1.348-.13c-1.626 1.381-3.91 3.976-5.316 8.605a.59.59 0 0 0 .382.73z");
}

.ayezflb3j {
  stop-color: var(--svg-color--fc8c16, #FC8C16);
}

.bbds8hj9q {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M19.055 6.756a.125.125 0 0 0 .002.177c.238.233.582.293.692.304a.125.125 0 0 0 .025-.248c-.094-.01-.366-.062-.542-.235a.125.125 0 0 0-.177.002");
}

.bdl3pn0lv {
  stop-color: var(--svg-color--fda533, #FDA533);
  stop-opacity: 0;
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bfzot6byw {
  d: path("m18.8 21.18l1.344 6.5l-.36.312l-1.468-6.531l-3.016-3.875l.703-.485z");
}

.bszqmbzpt {
  d: path("M20.156 2.496a1.025 1.025 0 0 0-.984-.578c-.86.047-.977.343-1.754.183c-.822-.169-1.227-.12-1.578.04l-.007.003c-.347.157-1.064.483-1.064 1.95c0 1.351.482 2.065.715 2.32l-.046.016c-.231.084-.327.33-.243.562c.071.197.322.311.637.262c.36-.057.624-.106.831-.147a.25.25 0 0 0 .2-.245V5.75c0-.469.33-.749.477-.832c.015-.485.163-.707.406-.824c.4-.195.526-.099 1.484-.157c.965-.058 1.223-.832.926-1.441");
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.ckhjb_bgt {
  stop-color: var(--svg-color--a39fa7, #A39FA7);
}

.cl2mlwbhs {
  stop-color: var(--svg-color--4a4b75, #4A4B75);
}

.cnh3p8b3x {
  stop-color: var(--svg-color--817076, #817076);
  stop-opacity: 0;
}

.csaq2_bel {
  stop-color: var(--svg-color--444571, #444571);
  stop-opacity: 0;
}

.ctpk5jb_q {
  d: path("m19.39 5.642l-.004-.072c0-.185.08-.336.176-.336c.097 0 .176.15.176.336l-.004.072z");
}

.d69nsybly {
  stop-color: var(--svg-color--e99f2e, #E99F2E);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.eluf2xb_e {
  stop-color: var(--svg-color--ce853f, #CE853F);
}

.ex23x-brg {
  stop-color: var(--svg-color--8c8388, #8C8388);
  stop-opacity: 0;
}

.ezcqmvbni {
  stop-color: var(--svg-color--443a80, #443A80);
}

.f3j6dkfip {
  stop-color: var(--svg-color--99919a, #99919A);
}

.fa3xzswyd {
  stop-color: var(--svg-color--eb9f1c, #EB9F1C);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fjz5hab9p {
  stop-color: var(--svg-color--f67e18, #F67E18);
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.fxoxl0blj {
  stop-color: var(--svg-color--8c8393, #8C8393);
  stop-opacity: 0;
}

.g24ahctiy {
  stop-color: var(--svg-color--94899e, #94899E);
  stop-opacity: 0;
}

.g3fqo4glu {
  d: path("M19.183 18.562c-.383-1.05-.716-2.028-.773-2.383h-4.742c-.1 1.375.144 1.713.773 2.422c.693.782 2.172 2.43 2.54 2.895c.35.35.5.789.554.98l2.262 7.43a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.333-.5-.886-.656c-.663-.187-1.943-.284-2.516-.336c-.213-1.766-.66-5.431-.734-5.969c-.094-.672-.227-1.414-.774-2.914");
}

.g6je8pe2z {
  stop-color: var(--svg-color--ffd237, #FFD237);
  stop-opacity: 0;
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gvltpob4o {
  d: path("m12.972 21.127l-3.476 4.428l.514.199l3.484-3.708a3 3 0 0 0 .761-1.493l.19-1l-.751-.774l-.544 1.994a1 1 0 0 1-.178.354");
}

.gyv6967sg {
  d: path("m8.965 25.653l1.638.678l-.022.02l.107.355c.217.713.536 1.764.62 2.27c.077.462-.145.768-.35.953c-.094.083-.235.064-.319-.03l-2.688-2.995a.25.25 0 0 1 .02-.352l.985-.888z");
}

.h2o5q3bga {
  stop-color: var(--svg-color--f3563a, #F3563A);
}

.hdzwkybza {
  stop-color: var(--svg-color--63617e, #63617E);
  stop-opacity: 0;
}

.hze7fms1a {
  stop-color: var(--svg-color--ffbf27, #FFBF27);
  stop-opacity: 0;
}

.irjdxuv0o {
  d: path("m17.536 6.303l-.2-1.44a.727.727 0 0 0 .2 1.44");
}

.irx8fxn1d {
  d: path("m19.406 28.62l.391 1.286a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.333-.5-.886-.656c-.591-.167-1.673-.262-2.306-.317l-.21-.019v-.002z");
}

.j_bzaeb4b {
  fill: var(--svg-color--8c8393, #8C8393);
  d: path("M19.183 18.562c-.383-1.05-.716-2.028-.773-2.383h-4.742c-.1 1.375.144 1.713.773 2.422c.693.782 2.172 2.43 2.54 2.895c.35.35.5.789.554.98l2.262 7.43a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.333-.5-.886-.656c-.663-.187-1.943-.284-2.516-.336c-.213-1.766-.66-5.431-.734-5.969c-.094-.672-.227-1.414-.774-2.914");
}

.j4xesqbgr {
  stop-color: var(--svg-color--ffbf3f, #FFBF3F);
}

.jbtp05a5b {
  stop-color: var(--svg-color--d34015, #D34015);
}

.jkk-xsb9b {
  stop-color: var(--svg-color--ffd237, #FFD237);
}

.kgio6d1ee {
  stop-color: var(--svg-color--ffa526, #FFA526);
  stop-opacity: 0;
}

.khn7ydrmc {
  d: path("m23.343 16.011l-.496.052a.435.435 0 0 0-.388.403a.38.38 0 0 0 .077.266c.264.33.524.366.721.408c.22.047.676-.191.59-.691a.53.53 0 0 0-.504-.438");
}

.kl_73lr_c {
  d: path("M20.53 5.812a1 1 0 0 1-.257-.457h-.18V6.48c.215.137.522.115.614-.09c.078-.175.02-.394-.176-.578");
}

.kl3mfkb2l {
  d: path("M16.476 8.597c-.89 0-1.137.215-1.433.407L14.019 11.6c-.3 1.4-.364 3.636-.36 4.578h4.766c.258-.656.678-2.675.516-4.578c-.164-1.93-1.207-2.902-2.465-3.004");
}

.kmd31z90f {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M19.288 4.61a.8.8 0 0 1 .216-.016a.15.15 0 0 0 .038-.298a1 1 0 0 0-.313.02a1 1 0 0 0-.409.173a.15.15 0 0 0 .179.24c.085-.062.19-.1.289-.12");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l138bfbcs {
  stop-color: var(--svg-color--282955, #282955);
}

.lhdz7oxfj {
  stop-color: var(--svg-color--444571, #444571);
}

.ljdv6tb3r {
  stop-color: var(--svg-color--ee462e, #EE462E);
}

.m_uy2vb_d {
  stop-color: var(--svg-color--695c75, #695C75);
  stop-opacity: 0;
}

.m1l7k9jve {
  cx: 0.064px;
  cy: 0.088px;
  rx: 0.064px;
  ry: 0.088px;
}

.m3n9jy0fh {
  stop-color: var(--svg-color--63617e, #63617E);
}

.md0ucwkak {
  stop-color: var(--svg-color--ea6f3e, #EA6F3E);
}

.mngz2ebss {
  stop-color: var(--svg-color--897998, #897998);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.no9rs03zd {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.8 5.642h-.988c0-.391.221-.709.494-.709s.494.318.494.71");
}

.oiy_54b9a {
  stop-color: var(--svg-color--887e8b, #887E8B);
}

.ou5ot-gfg {
  stop-color: var(--svg-color--f27f2f, #F27F2F);
}

.owigx3bpe {
  d: path("M20.307 4.848c-.039-.8-.298-1.187-.42-1.3h-3.733l-.062 3.164c.866 2.121 3.511 2.212 3.906 1.445s.354-2.381.309-3.309");
}

.oxce79bcz {
  stop-color: var(--svg-color--282955, #282955);
  stop-opacity: 0;
}

.oxg1n1wjw {
  stop-color: var(--svg-color--5a577e, #5A577E);
}

.p1zm9vufc {
  stop-color: var(--svg-color--ef7c07, #EF7C07);
}

.p6qc3nb-j {
  stop-color: var(--svg-color--492d85, #492D85);
}

.pat1zf4-w {
  stop-color: var(--svg-color--8b8290, #8B8290);
}

.pvqp1vbsj {
  stop-color: var(--svg-color--e9672b, #E9672B);
}

.qk2fd-d7d {
  d: path("M18.785 10.5c-.282-.713-.774-1.224-.985-1.39l.04 4.468l1.785-.836c-.278-.524-.489-1.352-.84-2.242");
}

.r9z1qobnf {
  d: path("M16.612 11.203a1.355 1.355 0 1 0-1.729-2.088c-.951.692-1.79 1.592-2.27 2.135l2.039 1.914c.308-.32 1.382-1.393 1.96-1.96");
}

.re8izvbqw {
  stop-color: var(--svg-color--ffa526, #FFA526);
}

.rm4aiz5dn {
  stop-color: var(--svg-color--887e8b, #887E8B);
  stop-opacity: 0;
}

.rnrhdzckq {
  stop-color: var(--svg-color--a39fa7, #A39FA7);
  stop-opacity: 0;
}

.rx9sqxbed {
  d: path("m12.831 19.945l.891-3.734h1.781c.052.614.152 2.215.29 3.515s-.492 2.032-.766 2.313L10.58 26.35c.198.662.627 2.025.727 2.625c.077.462-.145.768-.35.953c-.094.083-.235.064-.319-.03l-2.687-2.995a.25.25 0 0 1 .018-.352l.986-.888c1.042-1.365 3.191-4.194 3.454-4.594c.18-.276.39-.917.421-1.125");
}

.ryq0o3qru {
  stop-color: var(--svg-color--a19da6, #A19DA6);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.stwbr2bhy {
  stop-color: var(--svg-color--46437b, #46437B);
  stop-opacity: 0;
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.t5jak8x3h {
  stop-color: var(--svg-color--e4af34, #E4AF34);
}

.ttsumpbek {
  stop-color: var(--svg-color--897998, #897998);
  stop-opacity: 0;
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ujjr06bwy {
  stop-color: var(--svg-color--fc8c16, #FC8C16);
  stop-opacity: 0;
}

.ux4w7lb6c {
  stop-color: var(--svg-color--8c8388, #8C8388);
}

.uz8jx9bci {
  stop-color: var(--svg-color--f27f2f, #F27F2F);
  stop-opacity: 0;
}

.v5lz4sb9o {
  stop-color: var(--svg-color--695c75, #695C75);
}

.v6cmgr7lo {
  stop-color: var(--svg-color--f08337, #F08337);
}

.v9kimlbms {
  stop-color: var(--svg-color--94899e, #94899E);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vj0bxeigc {
  stop-color: var(--svg-color--fba433, #FBA433);
}

.w8350jbiw {
  stop-color: var(--svg-color--dd3e06, #DD3E06);
  stop-opacity: 0;
}

.wb44sjbzz {
  stop-color: var(--svg-color--dd3e06, #DD3E06);
}

.wlrmkubjk {
  stop-color: var(--svg-color--cd7f1a, #CD7F1A);
}

.wtea7v6lu {
  stop-color: var(--svg-color--9f9c9f, #9F9C9F);
}

.x5p6yzbmf {
  stop-color: var(--svg-color--817076, #817076);
}

.xh_da2q2q {
  stop-color: var(--svg-color--60618d, #60618D);
}

.xh4g4qbuv {
  stop-color: var(--svg-color--e0a531, #E0A531);
  stop-opacity: 0;
}

.xmto8db1n {
  fill: var(--svg-color--45437a, #45437A);
  d: path("m8.965 25.653l1.638.678l-.022.02l.107.355c.217.713.536 1.764.62 2.27c.077.462-.145.768-.35.953c-.094.083-.235.064-.319-.03l-2.688-2.995a.25.25 0 0 1 .02-.352l.985-.888z");
}

.xpz0ltqsz {
  stop-color: var(--svg-color--ffcd3e, #FFCD3E);
}

.y0g_czb9f {
  stop-color: var(--svg-color--5a577e, #5A577E);
  stop-opacity: 0;
}

.yfqxgqb1h {
  stop-color: var(--svg-color--a19da6, #A19DA6);
  stop-opacity: 0;
}

.yvuyjoqpy {
  stop-color: var(--svg-color--47456f, #47456F);
}

.z6_y2in4e {
  fill: var(--svg-color--f5b02e, #F5B02E);
  fill-rule: evenodd;
  d: path("M22.831 18.391a.85.85 0 0 0 1.13-.433l.19-.426a.755.755 0 0 0-.383-.993c-1.533-.704-4.023-2.149-4.983-5.93l-2.008.524c1.185 4.668 4.29 6.44 6.054 7.258");
}

.z7rq8royu {
  stop-color: var(--svg-color--f07f0f, #F07F0F);
  stop-opacity: 0;
}

.z8jy9-b3h {
  d: path("M0 0h1.946v3.44H0z");
}

.zc8ie-1dg {
  stop-color: var(--svg-color--515279, #515279);
  stop-opacity: 0;
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

.zvi2r2b9j {
  stop-color: var(--svg-color--f08337, #F08337);
  stop-opacity: 0;
}

</style>
