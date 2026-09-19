<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iRSA9Ld)"><path class="ri3n41bmg"/></g><g filter="url(#i4xZ9Ge)"><path stroke="url(#iOmZ2wc)" class="ojh1fleoa"/></g><path fill="url(#iHGRKkb)" class="s9z3jkbdd"/><g filter="url(#iTexqBb)"><path class="kh4m-x6vr"/></g><path fill="url(#ipljM2j)" class="tr7t_rbgt"/><path fill="url(#il2anXd)" class="tr7t_rbgt"/><path fill="url(#ix6Tusc)" class="l3pib11wq"/><g filter="url(#iDBbWWz)"><path class="b73vblb6y"/><path fill="url(#ihZhDed)" class="fyyb5wxvb"/><path fill="url(#imKHItb)" class="fyyb5wxvb"/></g><g filter="url(#isCxfBb)"><path class="s-vq7hbns"/><path fill="url(#iGdUVQc)" class="ku5md_ocu"/><path fill="url(#iUmkrXc)" class="ku5md_ocu"/></g><path fill="url(#iJG5Jac)" transform="rotate(-14.867 14.3 10.454)" class="cd_fnsb8c"/><path fill="url(#iaC77Wb)" transform="rotate(-14.867 14.3 10.454)" class="cd_fnsb8c"/><path fill="url(#iKpwwUb)" transform="rotate(-14.867 14.3 10.454)" class="cd_fnsb8c"/><path fill="url(#iCmJLOe)" class="qbinlrgys"/><path fill="url(#iRIHiUF)" class="qbinlrgys"/><path fill="url(#iu8hjKd)" class="qbinlrgys"/><g filter="url(#iC2pbYd)"><path class="fxbube-hx"/><path fill="url(#imt73Ud)" class="gg3gfcb3s"/></g><g filter="url(#iJMgsQe)"><path class="wvhbdpmui"/></g><g filter="url(#iffsbAS)"><path class="bymauc5ot"/></g><path fill="url(#iRJf9Rf)" class="kpqoceb4x"/><path fill="url(#idcmAXc)" class="kpqoceb4x"/><g filter="url(#isjGCin)"><path fill="url(#iSgNpsd)" class="ylstrmb2p"/></g><path fill="url(#iYMkfJb)" class="yszhkacta"/><path fill="url(#ieR7lnc)" class="yszhkacta"/><g filter="url(#inFrbye)"><path fill="url(#i7tsL2x)" class="xjy0q9jeg"/><path fill="url(#iQ8TSUl)" class="xjy0q9jeg"/><path fill="url(#i7CHZMy)" class="xjy0q9jeg"/><path fill="url(#iUdCOnd)" class="xjy0q9jeg"/></g><g filter="url(#iCBAYbe)"><path fill="url(#iu8DRBe)" class="f9ns8fftm"/><path fill="url(#iZqsM4c)" class="f9ns8fftm"/><path fill="url(#iFvfV2Z)" class="f9ns8fftm"/></g><path fill="url(#iMqE5sq)" class="yhhf5mb6i"/><path fill="url(#ij9hw3c)" class="yhhf5mb6i"/><path fill="url(#iZKq8Bc)" class="yhhf5mb6i"/><path clip-rule="evenodd" class="dod-0_b2k"/><path class="r0cqiqbmf"/><path fill="url(#i0fkTzA)" class="spewgdbbb"/><path fill="url(#i7jVw8c)" class="ss8_r02og"/><ellipse fill="url(#i17tU0N)" transform="rotate(24.61 13.11 8.457)" class="zk_0ssb7p"/><g filter="url(#i5J1iqe)"><path clip-rule="evenodd" class="bsowywbxt"/></g><defs><radialGradient id="iOmZ2wc" cx="0" cy="0" r="1" gradientTransform="matrix(3.48437 -4.05522 3.01176 2.5878 16.544 27.609)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iHGRKkb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 3.29646 -1.78135 -.28708 16.638 21.257)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="il2anXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 13.263 18.929)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="ix6Tusc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10938 3.14063 -8.2876 -.28863 14.857 19.038)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="iJG5Jac" cx="0" cy="0" r="1" gradientTransform="matrix(1.75062 .2869 -.80956 4.93988 14.391 12.036)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="eitmobczl"/><stop offset="1" class="l5cg6c78h"/></radialGradient><radialGradient id="iaC77Wb" cx="0" cy="0" r="1" gradientTransform="rotate(117.861 4.924 10.376)scale(.83385 .74963)" gradientUnits="userSpaceOnUse"><stop class="ef2avdbrg"/><stop offset="1" class="ju9-v_r3z"/></radialGradient><radialGradient id="iCmJLOe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4531 4.00002 -4.9949 -4.31194 18.091 14.554)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="b2o3a7r9l"/><stop offset="1" class="g7ee89odc"/></radialGradient><radialGradient id="iRIHiUF" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03122 3.14064 -3.13218 -2.02576 17.654 12.679)" gradientUnits="userSpaceOnUse"><stop class="oo0a8g8xe"/><stop offset="1" class="hc1x_wbbe"/></radialGradient><radialGradient id="iu8hjKd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.73437 .23436 -.4261 -6.78981 17.576 16.304)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="brpomvbii"/><stop offset="1" class="lmk5_gb2n"/></radialGradient><radialGradient id="imt73Ud" cx="0" cy="0" r="1" gradientTransform="rotate(86.947 -.214 16.99)scale(2.34708 .80604)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="q3uvkbbyl"/><stop offset="1" class="utxluw1tg"/></radialGradient><radialGradient id="idcmAXc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 1.04686 -.99542 -1.2183 17.21 12.679)" gradientUnits="userSpaceOnUse"><stop class="n6csxrxuy"/><stop offset="1" class="obkbkpctx"/></radialGradient><radialGradient id="iYMkfJb" cx="0" cy="0" r="1" gradientTransform="matrix(.47656 .25781 -.36391 .67269 11.915 9.416)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ng2hgzbhn"/><stop offset=".684" class="nz7jfnb_b"/></radialGradient><radialGradient id="ieR7lnc" cx="0" cy="0" r="1" gradientTransform="matrix(-.12005 -.29152 .43751 -.18018 12.32 9.733)" gradientUnits="userSpaceOnUse"><stop class="av0_6yb2f"/><stop offset="1" class="lhhdsccyq"/></radialGradient><radialGradient id="iQ8TSUl" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 -.04688 .05715 -1.0287 15.577 8.713)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="i7CHZMy" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.01562 0 12.68 9.9)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="vb_gc7b6b"/><stop offset="1" class="rhkf30kvu"/></radialGradient><radialGradient id="iUdCOnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 13.509 8.76)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="iu8DRBe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43749 3.12502 -3.54357 -3.89789 17.452 6.05)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="i2p5fqtly"/><stop offset="1" class="pw8a02b5q"/></radialGradient><radialGradient id="iZqsM4c" cx="0" cy="0" r="1" gradientTransform="rotate(81.634 4.736 13.441)scale(2.71158 1.19788)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="ltxof3fvo"/><stop offset="1" class="nj0viubvx"/></radialGradient><radialGradient id="iFvfV2Z" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -.09375 .18397 2.94358 12.155 6.666)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="id9lp4hub"/><stop offset="1" class="fed4ggbgk"/></radialGradient><radialGradient id="iMqE5sq" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 -.21094 .10296 .35463 15.352 8.595)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="ij9hw3c" cx="0" cy="0" r="1" gradientTransform="matrix(.22596 1.17975 -1.22934 .23546 15.384 8.295)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="i0fkTzA" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 0 0 .53125 13.214 8.787)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="i7jVw8c" cx="0" cy="0" r="1" gradientTransform="matrix(.25 0 0 .54102 13.046 8.808)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><filter id="iRSA9Ld" width="7.28" height="8.609" x="15.138" y="20.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_251"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_251" result="effect2_innerShadow_4002_251"/></filter><filter id="i4xZ9Ge" width="5.734" height="7.279" x="15.609" y="21.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_251" stdDeviation=".25"/></filter><filter id="iTexqBb" width="11.64" height="10.135" x="8.244" y="18.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_251"/></filter><filter id="iDBbWWz" width="4.352" height="2.364" x="8.244" y="26.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_251"/></filter><filter id="isCxfBb" width="3.579" height="3.542" x="21.005" y="25.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_251"/></filter><filter id="iC2pbYd" width="6.876" height="3.179" x="10.319" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.403922 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_251"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.337255 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_251" result="effect2_innerShadow_4002_251"/></filter><filter id="iJMgsQe" width="1.071" height="1.439" x="9.985" y="18.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.4 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_251"/></filter><filter id="iffsbAS" width="1.196" height="1.065" x="10.34" y="18.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.4 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_251"/></filter><filter id="isjGCin" width="8.168" height="8.42" x="9.97" y="19.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_251" stdDeviation=".375"/></filter><filter id="inFrbye" width="4.443" height="5.249" x="12.202" y="6.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.329412 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_251"/></filter><filter id="iCBAYbe" width="6.391" height="5.479" x="11.769" y="4.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.266667 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_251"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.137255 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_251" result="effect2_innerShadow_4002_251"/></filter><filter id="i5J1iqe" width="1.117" height=".648" x="12.906" y="7.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.168627 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_251"/></filter><linearGradient id="ipljM2j" x1="17.2" x2="17.2" y1="18.835" y2="19.366" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="ihZhDed" x1="12.325" x2="11.341" y1="28.101" y2="28.101" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="imKHItb" x1="10.888" x2="10.888" y1="28.964" y2="28.593" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="iGdUVQc" x1="21.351" x2="22.036" y1="26.054" y2="26.718" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="iUmkrXc" x1="23.497" x2="23.282" y1="27.257" y2="27.429" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="iKpwwUb" x1="14.297" x2="14.533" y1="12.329" y2="12.323" gradientUnits="userSpaceOnUse"><stop class="a-mj2kbzz"/><stop offset="1" class="ikw2jw0zo"/></linearGradient><linearGradient id="iRJf9Rf" x1="17.18" x2="14.689" y1="15.304" y2="15.382" gradientUnits="userSpaceOnUse"><stop class="ofo46gsuq"/><stop offset="1" class="lq0qk0brb"/></linearGradient><linearGradient id="iSgNpsd" x1="10.72" x2="17.201" y1="25.851" y2="19.913" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="i7tsL2x" x1="15.265" x2="12.402" y1="9.455" y2="9.627" gradientUnits="userSpaceOnUse"><stop class="xwzzv0ryq"/><stop offset="1" class="l3_0v7cyw"/></linearGradient><linearGradient id="iZKq8Bc" x1="15.298" x2="15.446" y1="8.664" y2="8.676" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="i17tU0N" x1="13.039" x2="13.225" y1="8.419" y2="8.479" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-kneeling-medium" /></template>
<style>
.a-mj2kbzz {
  stop-color: var(--svg-color--a67a6e, #A67A6E);
}

.ao9a_pbsn {
  stop-color: var(--svg-color--9c6e67, #9C6E67);
  stop-opacity: 0;
}

.av0_6yb2f {
  stop-color: var(--svg-color--a66d75, #A66D75);
}

.b2o3a7r9l {
  stop-color: var(--svg-color--45a7f8, #45A7F8);
}

.b73vblb6y {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M12.184 27.542a6.3 6.3 0 0 0-1.412-.643q0 .008.003.014c-.433.175-1.005.467-1.55.746l-.517.262c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253z");
}

.bils69brp {
  stop-color: var(--svg-color--a49dac, #A49DAC);
  stop-opacity: 0;
}

.bmj_fbbea {
  stop-color: var(--svg-color--6a5a7a, #6A5A7A);
}

.brpomvbii {
  stop-color: var(--svg-color--4b77af, #4B77AF);
  stop-opacity: 0;
}

.bsowywbxt {
  fill: var(--svg-color--513a3c, #513A3C);
  fill-rule: evenodd;
  d: path("M13.706 7.951c-.147-.105-.362-.11-.5-.11a.2.2 0 0 1 0-.4h.01c.128 0 .463-.001.723.185a.2.2 0 1 1-.233.325");
}

.bymauc5ot {
  fill: var(--svg-color--a27b6d, #A27B6D);
  d: path("M10.966 18.769c.325-.003.516.178.57.27a2.2 2.2 0 0 0-.65.566c-.1.124-.278.17-.413.086a.266.266 0 0 1-.079-.39c.257-.329.48-.49.572-.532");
}

.cd_fnsb8c {
  d: path("M14.3 10.454h1.976v2.198H14.3z");
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.dod-0_b2k {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.682 9.922a.125.125 0 0 1-.002.177c-.238.233-.582.293-.692.304a.125.125 0 0 1-.025-.248c.094-.01.366-.062.542-.235a.125.125 0 0 1 .177.002");
}

.ef2avdbrg {
  stop-color: var(--svg-color--8e695b, #8E695B);
}

.eitmobczl {
  stop-color: var(--svg-color--9b6a61, #9B6A61);
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
}

.f9ns8fftm {
  d: path("M13.07 7.261c-.657 0-.97-.37-1-.835c0-.657.5-.796.694-.817c.22-.023.305-.047.61-.262a.9.9 0 0 1 .91-.097c.148.07.476.105.71.035c.392-.117.696-.113.997.117c.209.16.363.16.613.16c.344 0 .636.154.856.32c.657.498.582 2.208.258 3.169c-.31.919-.778 1.027-1.168.992c-.47-.043-.59-.399-.66-.696c-.057-.237-.201-.99-.266-1.237c-.136-.063-.431-.086-.532-.474c-.1-.387-.492-.431-.757-.406c-.162.016-.61.031-1.266.031");
}

.fed4ggbgk {
  stop-color: var(--svg-color--634d4a, #634D4A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwheo7gdw {
  stop-color: var(--svg-color--60608e, #60608E);
}

.fxbube-hx {
  fill: var(--svg-color--ad8375, #AD8375);
  d: path("m15.099 17.1l-.04-.78l1.892-.126c.046.664.117 1.594-.149 1.985c-.266.39-.765.858-2.2.945a42 42 0 0 1-3.269.031v-.18h-.672l-.34-.214c-.038-.192.39-.568.79-.711c1.253-.45 2.96-.82 3.988-.95");
}

.fy99v1bac {
  stop-color: var(--svg-color--897694, #897694);
}

.fyyb5wxvb {
  d: path("M12.184 27.542a6.3 6.3 0 0 0-1.412-.643q0 .008.003.014c-.433.175-1.005.467-1.55.746l-.517.262c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253z");
}

.g7ee89odc {
  stop-color: var(--svg-color--3370b9, #3370B9);
}

.g87nnpbqu {
  stop-color: var(--svg-color--a67d65, #A67D65);
}

.gg3gfcb3s {
  d: path("m15.099 17.1l-.04-.78l1.892-.126c.046.664.117 1.594-.149 1.985c-.266.39-.765.858-2.2.945a42 42 0 0 1-3.269.031v-.18h-.672l-.34-.214c-.038-.192.39-.568.79-.711c1.253-.45 2.96-.82 3.988-.95");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwwxm_bpq {
  stop-color: var(--svg-color--857297, #857297);
  stop-opacity: 0;
}

.hc1x_wbbe {
  stop-color: var(--svg-color--4aa9ee, #4AA9EE);
  stop-opacity: 0;
}

.i2p5fqtly {
  stop-color: var(--svg-color--52343b, #52343B);
}

.id9lp4hub {
  stop-color: var(--svg-color--634d4a, #634D4A);
}

.ifze1vbqw {
  stop-color: var(--svg-color--605f91, #605F91);
  stop-opacity: 0;
}

.igg0ouipp {
  stop-color: var(--svg-color--a67d65, #A67D65);
  stop-opacity: 0;
}

.ikw2jw0zo {
  stop-color: var(--svg-color--a67a6e, #A67A6E);
  stop-opacity: 0;
}

.jje8gccwz {
  stop-color: var(--svg-color--605f91, #605F91);
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
}

.ju9-v_r3z {
  stop-color: var(--svg-color--8e695b, #8E695B);
  stop-opacity: 0;
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.kh4m-x6vr {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M9.65 22.132c.137.575.807 3.427 1.125 4.781c-.573.232-1.39.668-2.067 1.008c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253l-.076-7.169c1.787.442 3.937.808 5.747.262c1.2-.363 1.266-1.817 1.266-2.875l-7.61.078a2.726 2.726 0 0 0-1.874 3.125");
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.kpqoceb4x {
  d: path("M14.69 13.636a1.261 1.261 0 0 1 2.52-.119l.155 2.775l-2.567.152z");
}

.ku5md_ocu {
  d: path("m21.89 25.788l-.885.75l.406 1.5c.391.198 1.35.653 2.063.89c.547.183.887.06 1.056-.083c.078-.065.066-.178 0-.257l-2.286-2.769a.25.25 0 0 0-.354-.031");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l0bg_dlbj {
  stop-color: var(--svg-color--897694, #897694);
  stop-opacity: 0;
}

.l3_0v7cyw {
  stop-color: var(--svg-color--ab826c, #AB826C);
}

.l3pib11wq {
  d: path("M12.121 21.545v-.003c1.787.442 3.937.808 5.748.262c1.2-.363 1.265-1.817 1.265-2.875l-7.61.078a3.2 3.2 0 0 0-.701.336z");
}

.l5cg6c78h {
  stop-color: var(--svg-color--ba8f7c, #BA8F7C);
}

.lhhdsccyq {
  stop-color: var(--svg-color--a66d75, #A66D75);
  stop-opacity: 0;
}

.lmk5_gb2n {
  stop-color: var(--svg-color--4b77af, #4B77AF);
}

.lq0qk0brb {
  stop-color: var(--svg-color--3a78c3, #3A78C3);
}

.lt2_2ybqi {
  stop-color: var(--svg-color--a49dac, #A49DAC);
}

.ltxof3fvo {
  stop-color: var(--svg-color--624646, #624646);
}

.n6csxrxuy {
  stop-color: var(--svg-color--4ba6ed, #4BA6ED);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.necsq7bka {
  stop-color: var(--svg-color--9e6563, #9E6563);
}

.ng2hgzbhn {
  stop-color: var(--svg-color--bf9580, #BF9580);
}

.nj0viubvx {
  stop-color: var(--svg-color--624646, #624646);
  stop-opacity: 0;
}

.nu9hhfe4u {
  stop-color: var(--svg-color--774e55, #774E55);
}

.nz7jfnb_b {
  stop-color: var(--svg-color--ad7f6d, #AD7F6D);
}

.obkbkpctx {
  stop-color: var(--svg-color--4ba6ed, #4BA6ED);
  stop-opacity: 0;
}

.ofo46gsuq {
  stop-color: var(--svg-color--439ff0, #439FF0);
}

.ojh1fleoa {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.622 21.616c-.138.941-.573 3.264-1.239 5.338a.5.5 0 0 0 .152.535a.55.55 0 0 0 .538.086c.689-.244 2.053-.526 3.737-.302");
}

.olt5ljabw {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
}

.oo0a8g8xe {
  stop-color: var(--svg-color--4aa9ee, #4AA9EE);
}

.oy9f4cbur {
  stop-color: var(--svg-color--60608e, #60608E);
  stop-opacity: 0;
}

.pe7odhb7d {
  stop-color: var(--svg-color--916051, #916051);
}

.pqpq_lljy {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
  stop-opacity: 0;
}

.pw8a02b5q {
  stop-color: var(--svg-color--492b38, #492B38);
}

.q_g8mnbhc {
  stop-color: var(--svg-color--766b81, #766B81);
  stop-opacity: 0;
}

.q3uvkbbyl {
  stop-color: var(--svg-color--b98e81, #B98E81);
}

.qbinlrgys {
  d: path("M14.091 14.151c-.162 1.15-.094 2.637.016 3.528v1.289h5.031c-.055-2.063-.578-4.728-1.367-6.047c-.664-1.11-1.422-1.176-2.055-.957c-.605.183-1.422.75-1.625 2.187");
}

.r0cqiqbmf {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.937 8.808h.988c0-.391-.221-.709-.494-.709s-.494.318-.494.71");
}

.rhkf30kvu {
  stop-color: var(--svg-color--bd927e, #BD927E);
  stop-opacity: 0;
}

.ri3n41bmg {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M15.145 26.64c-.05-1.838.195-4.492.32-5.57l3.484-.696c-.554 3.344-1.328 5.508-1.687 6.266c1.062-.266 2.578-.172 3.765-.117l.391 1.515c-1.234.125-3.34.523-3.844.648c-.562.141-2.371.086-2.43-2.046");
}

.s-vq7hbns {
  fill: var(--svg-color--443c7f, #443C7F);
  d: path("m21.89 25.788l-.885.75l.406 1.5c.391.198 1.35.653 2.063.89c.547.183.887.06 1.056-.083c.078-.065.066-.178 0-.257l-2.286-2.769a.25.25 0 0 0-.354-.031");
}

.s9z3jkbdd {
  d: path("M15.145 26.64c-.05-1.838.195-4.492.32-5.57l3.484-.696c-.554 3.344-1.328 5.508-1.687 6.266c1.062-.266 2.578-.172 3.765-.117l.391 1.515c-1.234.125-3.34.523-3.844.648c-.562.141-2.371.086-2.43-2.046");
}

.spewgdbbb {
  d: path("M13.542 8.808v-.004c0-.32-.137-.58-.307-.58s-.306.26-.306.58v.004z");
}

.ss8_r02og {
  d: path("m13.347 8.808l.004-.072c0-.185-.08-.336-.176-.336c-.097 0-.176.15-.176.336q0 .038.004.072z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t_vl9fbku {
  stop-color: var(--svg-color--8f7c7f, #8F7C7F);
  stop-opacity: 0;
}

.tr7t_rbgt {
  d: path("M9.65 22.132c.137.575.807 3.427 1.125 4.781c-.573.232-1.39.668-2.067 1.008c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253l-.076-7.169c1.787.442 3.937.808 5.747.262c1.2-.363 1.266-1.817 1.266-2.875l-7.61.078a2.726 2.726 0 0 0-1.874 3.125");
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.utxluw1tg {
  stop-color: var(--svg-color--b98e81, #B98E81);
  stop-opacity: 0;
}

.v224y-b0w {
  stop-color: var(--svg-color--a098a8, #A098A8);
  stop-opacity: 0;
}

.vb_gc7b6b {
  stop-color: var(--svg-color--c19382, #C19382);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wvhbdpmui {
  fill: var(--svg-color--a27b6d, #A27B6D);
  d: path("m11.013 18.17l.043.634a4.3 4.3 0 0 0-.603.608a.27.27 0 0 1-.345.059c-.118-.073-.161-.224-.085-.339c.311-.472.794-.844.99-.961");
}

.xgk77dt3o {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
  stop-opacity: 0;
}

.xjy0q9jeg {
  d: path("M12.43 8.015c.039-.802.298-1.188.42-1.3h3.733l.062 3.163C15.78 12 13.134 12.09 12.74 11.323c-.395-.767-.354-2.38-.309-3.308");
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.xwzzv0ryq {
  stop-color: var(--svg-color--a87a72, #A87A72);
}

.yhhf5mb6i {
  d: path("m15.2 9.469l.2-1.44a.727.727 0 0 1-.2 1.44");
}

.ylstrmb2p {
  d: path("m10.732 21.468l.656 5.492l.313.125l-.43-5.73a.487.487 0 0 1 .481-.528c.926-.006 3.848 0 4.542 0c.813 0 1.094-.273 1.094-.648c-1.193-.01-4.677-.025-5.664 0s-1.039.862-.992 1.289");
}

.yszhkacta {
  d: path("M12.206 8.978a1 1 0 0 0 .258-.457h.18v1.125c-.215.137-.522.115-.614-.09c-.078-.175-.02-.394.176-.578");
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
}

.zk_0ssb7p {
  cx: 13.11px;
  cy: 8.457px;
  rx: 0.064px;
  ry: 0.088px;
}

</style>
