<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i576MnJ)"><path fill="url(#iBr64wc)" class="hxawe1bvw"/><path fill="url(#ictjlVc)" class="hxawe1bvw"/></g><path fill="url(#iWShhYt)" class="hxawe1bvw"/><path fill="url(#iWOEVzb)" class="gapgjlb2u"/><path fill="url(#ilUupjc)" class="gapgjlb2u"/><path fill="url(#iIZKUfe)" class="gapgjlb2u"/><path fill="url(#iw2YJFc)" class="hy5bczbge"/><path fill="url(#iorIl7b)" class="hy5bczbge"/><path fill="url(#iudIU6d)" class="fr74rck3u"/><g filter="url(#iD3Gsod)"><path fill="url(#i7Eo3Mb)" class="vttm5o78n"/><path fill="url(#idX7VIc)" class="vttm5o78n"/></g><path fill="url(#ivdc5ze)" class="lp5lg9kgv"/><path fill="url(#ipEuVzc)" class="lp5lg9kgv"/><path fill="url(#iAVvQWd)" class="lp5lg9kgv"/><g filter="url(#iTVwZUb)"><path class="cibaz8bjx"/></g><g filter="url(#iK9Hyjc)"><path fill="url(#i1hA05d)" class="pms6qkxms"/><path fill="url(#i7AwGMb)" class="pms6qkxms"/><path fill="url(#iQKVHvr)" class="pms6qkxms"/><path fill="url(#i8lWDze)" class="pms6qkxms"/><path fill="url(#i64abSb)" class="pms6qkxms"/></g><g filter="url(#i27FAdc)"><path class="c1udzvb2i"/></g><g filter="url(#inHAVgd)"><path class="gookgbqsm"/></g><g filter="url(#iQuPPwd)"><path class="r0elt_brj"/><path fill="url(#i0yg63b)" class="paa0g7bcq"/><path fill="url(#i6FXx2d)" class="paa0g7bcq"/></g><g filter="url(#i5zYJEb)"><path class="q568k0pgh"/><path fill="url(#itjJmPc)" class="pwuxh_ghz"/><path fill="url(#iTu15fj)" class="pwuxh_ghz"/></g><path fill="url(#iEB4crb)" class="lsom33rae"/><path fill="url(#i2jxyBb)" class="b7ls-m1aj"/><path fill="url(#iilnPae)" class="b7ls-m1aj"/><g filter="url(#ineulOb)"><path fill="url(#iE57MNb)" class="sbbg3pb0u"/></g><g filter="url(#iJRiMYd)"><path class="grwv7pb9x"/></g><g filter="url(#i3Nruid)"><path class="h-r0_gb7p"/></g><g filter="url(#ixtDUVo)"><path clip-rule="evenodd" class="owlglgb_q"/></g><path class="h3xzehbak"/><g filter="url(#iZEmTxc)"><path fill="url(#iMlwdJe)" class="xdqxlsbhz"/><path fill="url(#iKTJumc)" class="xdqxlsbhz"/><path fill="url(#irb99Cb)" class="xdqxlsbhz"/><path fill="url(#ioHXnjb)" class="xdqxlsbhz"/><path fill="url(#itRBylc)" class="xdqxlsbhz"/><path fill="url(#iBODv9b)" class="xdqxlsbhz"/></g><path fill="url(#idAGvzC)" class="v1j3m8bkp"/><path fill="url(#ilYR0qd)" class="v1j3m8bkp"/><path fill="url(#ia51WwI)" class="c-11seb3g"/><path fill="url(#iPecAHd)" class="c-11seb3g"/><g filter="url(#il355je)"><path class="vxrbqw1yr"/></g><g filter="url(#i0jkBfd)"><path class="bhfey7b2p"/></g><g filter="url(#iam6zSb)"><path class="c4gw_rbvm"/></g><g filter="url(#iYBqCCd)"><path stroke="url(#iEZ6LXd)" class="v8vgju-bc"/></g><g filter="url(#iyr48mW)"><path stroke="url(#i0pmXfb)" class="okkh45kiy"/></g><g filter="url(#iBp2Axd)"><path class="ov4q-2fcn"/></g><defs><radialGradient id="ictjlVc" cx="0" cy="0" r="1" gradientTransform="rotate(161.322 8.286 15.122)scale(5.27798 10.393)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="f8_tgzbue"/><stop offset="1" class="v_-r5lbgt"/></radialGradient><radialGradient id="iWShhYt" cx="0" cy="0" r="1" gradientTransform="matrix(-6.07686 2.88187 -1.88528 -3.9754 14.768 19.68)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="vzyrucblm"/><stop offset="1" class="a2i8hds4q"/></radialGradient><radialGradient id="iWOEVzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.93285 -1.52074 0 15.583 19.975)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="vwzcj430b"/><stop offset="1" class="u8gj1d_ed"/></radialGradient><radialGradient id="ilUupjc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.17187 -.58594 0 13.188 20.795)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="vqy53843t"/><stop offset="1" class="tp1nefb2t"/></radialGradient><radialGradient id="iw2YJFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.92987 3.82055 -4.53851 -1.1046 22.284 14.32)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset=".909" class="by5wrxbms"/></radialGradient><radialGradient id="iorIl7b" cx="0" cy="0" r="1" gradientTransform="matrix(.35375 .48515 -.41214 .30052 21.384 14.642)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iudIU6d" cx="0" cy="0" r="1" gradientTransform="matrix(1.78065 .55963 -1.7265 5.49342 8.289 14.91)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="idX7VIc" cx="0" cy="0" r="1" gradientTransform="rotate(120.76 6.917 8.998)scale(4.96207 3.38219)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="eivezvbjc"/><stop offset="1" class="dunk4xw2z"/></radialGradient><radialGradient id="ivdc5ze" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.70515 2.05291 0 13.07 11.76)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="cgs6kxogn"/><stop offset="1" class="b9vnfe-fk"/></radialGradient><radialGradient id="ipEuVzc" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 -3.6875 .88887 .86627 9 8.844)" gradientUnits="userSpaceOnUse"><stop class="s3fe4zf2e"/><stop offset="1" class="d4h8kcbpy"/><stop offset="1" class="ub-l1fbpr"/></radialGradient><radialGradient id="iAVvQWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.18947 15.5156 0 16 21.158)" gradientUnits="userSpaceOnUse"><stop class="jcwfr4b-x"/><stop offset=".247" class="m65v9eyqh"/><stop offset=".847" class="r91sqk84w"/></radialGradient><radialGradient id="i7AwGMb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.22268 10.6787 0 9.286 9.696)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iQKVHvr" cx="0" cy="0" r="1" gradientTransform="matrix(.13754 -3.03019 5.3689 .24369 21.455 11.276)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i8lWDze" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8448 -1.87103 1.37344 -2.08823 20.546 3.706)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="i64abSb" cx="0" cy="0" r="1" gradientTransform="rotate(60.727 5.726 13.27)scale(1.65664 3.836)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="i0yg63b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.65461 0 0 -.98523 15.899 4.51)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="i6FXx2d" cx="0" cy="0" r="1" gradientTransform="matrix(3.88123 -6.1452 6.80825 4.3 9.043 9.265)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="itjJmPc" cx="0" cy="0" r="1" gradientTransform="matrix(3.25355 -3.07798 5.63292 5.95423 18.792 9.238)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iTu15fj" cx="0" cy="0" r="1" gradientTransform="matrix(3.94525 .45788 -.19039 1.64046 17.716 7.457)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iilnPae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99989 0 0 -2.21994 9.665 12.88)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iE57MNb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1053 .18973 -.19453 -1.13328 9.638 12.88)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="iMlwdJe" cx="0" cy="0" r="1" gradientTransform="rotate(104.051 5.703 14.44)scale(10.3219 9.11334)" gradientUnits="userSpaceOnUse"><stop offset=".542" class="dy3bcxe9s"/><stop offset="1" class="mghihr2mt"/></radialGradient><radialGradient id="iKTJumc" cx="0" cy="0" r="1" gradientTransform="matrix(.98633 2.57228 -.42433 .1627 15.36 12.055)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="mkzsocckt"/><stop offset="1" class="peh2v9b4z"/></radialGradient><radialGradient id="irb99Cb" cx="0" cy="0" r="1" gradientTransform="matrix(.98438 3.84375 -.63406 .16238 17.174 9.986)" gradientUnits="userSpaceOnUse"><stop class="j35ckxhbd"/><stop offset="1" class="ryim261uk"/></radialGradient><radialGradient id="ioHXnjb" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 4.375 -.54534 .0818 19.455 9.174)" gradientUnits="userSpaceOnUse"><stop class="j35ckxhbd"/><stop offset="1" class="ryim261uk"/></radialGradient><radialGradient id="itRBylc" cx="0" cy="0" r="1" gradientTransform="rotate(98.227 6.558 15.398)scale(3.93108 .49375)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="rk9yz2b8g"/><stop offset="1" class="mleb6mb5e"/></radialGradient><radialGradient id="iBODv9b" cx="0" cy="0" r="1" gradientTransform="rotate(-175.482 11.247 7.42)scale(.97177 2.30137)" gradientUnits="userSpaceOnUse"><stop class="fvbl5pb0w"/><stop offset="1" class="my72jwxuh"/></radialGradient><radialGradient id="idAGvzC" cx="0" cy="0" r="1" gradientTransform="matrix(-3.96874 1.06253 -.45292 -1.69174 22.94 19.97)" gradientUnits="userSpaceOnUse"><stop class="yzag7e8_g"/><stop offset="1" class="tgllzx6xq"/></radialGradient><radialGradient id="iPecAHd" cx="0" cy="0" r="1" gradientTransform="rotate(76.973 -2.081 25.424)scale(8.17927 4.47567)" gradientUnits="userSpaceOnUse"><stop class="awna98bfd"/><stop offset="1" class="i4docjyne"/></radialGradient><filter id="i576MnJ" width="20.98" height="11.177" x="5.603" y="20.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.423529 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4112"/></filter><filter id="iD3Gsod" width="13.076" height="15.613" x="9.487" y="5.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.227451 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4112"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.368627 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4112" result="effect2_innerShadow_4002_4112"/></filter><filter id="iTVwZUb" width="12.214" height="13.502" x="12.005" y="7.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4112" stdDeviation=".625"/></filter><filter id="iK9Hyjc" width="15.525" height="9.975" x="7.831" y="2.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4112"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4112" result="effect2_innerShadow_4002_4112"/></filter><filter id="i27FAdc" width="2.8" height="1.394" x="17.51" y="9.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4112"/></filter><filter id="inHAVgd" width="2.8" height="1.377" x="11.17" y="9.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4112"/></filter><filter id="iQuPPwd" width="8.338" height="7.623" x="8.061" y="3.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4112"/><feGaussianBlur result="effect2_foregroundBlur_4002_4112" stdDeviation=".25"/></filter><filter id="i5zYJEb" width="8.12" height="7.368" x="15.151" y="3.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4112" stdDeviation=".25"/></filter><filter id="ineulOb" width="1.5" height="2.767" x="8.283" y="11.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4112" stdDeviation=".125"/></filter><filter id="iJRiMYd" width="2.051" height="3.216" x="21.118" y="11.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4112" stdDeviation=".15"/></filter><filter id="i3Nruid" width="2.746" height="1.245" x="11.15" y="9.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4112" stdDeviation=".125"/></filter><filter id="ixtDUVo" width="3.511" height="1.562" x="11.244" y="12.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4112"/></filter><filter id="iZEmTxc" width="11.547" height="12.796" x="13.324" y="8.097" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4112"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.321569 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4112" result="effect2_innerShadow_4002_4112"/></filter><filter id="il355je" width="2.467" height="5.606" x="17.564" y="8.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4112" stdDeviation=".25"/></filter><filter id="i0jkBfd" width="2.78" height="4.622" x="15.346" y="9.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4112" stdDeviation=".25"/></filter><filter id="iam6zSb" width="2.438" height="3.281" x="13.906" y="11.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4112" stdDeviation=".25"/></filter><filter id="iYBqCCd" width="3.688" height="7.656" x="20.862" y="12.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4112" stdDeviation=".25"/></filter><filter id="iyr48mW" width="2.422" height="10.188" x="20.064" y="8.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4112" stdDeviation=".25"/></filter><filter id="iBp2Axd" width="6.067" height="3.146" x="16.854" y="4.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4112" stdDeviation=".3"/></filter><linearGradient id="iBr64wc" x1="20.291" x2="5.914" y1="27.483" y2="30.387" gradientUnits="userSpaceOnUse"><stop class="ee6wyldiv"/><stop offset="1" class="lrdcrkb9v"/></linearGradient><linearGradient id="iIZKUfe" x1="18.738" x2="16.984" y1="21.927" y2="21.927" gradientUnits="userSpaceOnUse"><stop class="obs_54cbe"/><stop offset="1" class="t1udg90jz"/></linearGradient><linearGradient id="i7Eo3Mb" x1="15.65" x2="15.65" y1="5.742" y2="21.154" gradientUnits="userSpaceOnUse"><stop class="rly31c85z"/><stop offset="1" class="u2zqby_zw"/></linearGradient><linearGradient id="i1hA05d" x1="23.857" x2="9.852" y1="6.355" y2="6.355" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iEB4crb" x1="23.355" x2="21.9" y1="12.176" y2="14.801" gradientUnits="userSpaceOnUse"><stop class="gvh9ilzzf"/><stop offset="1" class="yr1b81w8m"/><stop offset="1" class="le1cd1ete"/></linearGradient><linearGradient id="i2jxyBb" x1="8.538" x2="10.297" y1="13.036" y2="12.881" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="ilYR0qd" x1="20.314" x2="20.396" y1="19.873" y2="20.166" gradientUnits="userSpaceOnUse"><stop offset=".245" class="f8osbx-ej"/><stop offset="1" class="oxk0gpbzd"/></linearGradient><linearGradient id="ia51WwI" x1="19.564" x2="26.002" y1="28.564" y2="27.189" gradientUnits="userSpaceOnUse"><stop class="uu8x24bjn"/><stop offset="1" class="gmelrdffb"/></linearGradient><linearGradient id="iEZ6LXd" x1="24.151" x2="22.213" y1="13.191" y2="17.836" gradientUnits="userSpaceOnUse"><stop class="jrsz9e89j"/><stop offset="1" class="lf-s-qkac"/></linearGradient><linearGradient id="i0pmXfb" x1="21.776" x2="18.39" y1="9.637" y2="11.607" gradientUnits="userSpaceOnUse"><stop class="jrsz9e89j"/><stop offset="1" class="lf-s-qkac"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-facepalming-medium-dark" /></template>
<style>
.a2i8hds4q {
  stop-color: var(--svg-color--9f3b09, #9F3B09);
  stop-opacity: 0;
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.awna98bfd {
  stop-color: var(--svg-color--ff9946, #FF9946);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b7ls-m1aj {
  d: path("M9.516 10.96c-.943.132-1.685.925-1.685 1.904A1.94 1.94 0 0 0 9.665 14.8a93 93 0 0 1-.15-3.842");
}

.b9vnfe-fk {
  stop-color: var(--svg-color--6c4747, #6C4747);
  stop-opacity: 0;
}

.bhfey7b2p {
  stroke: var(--svg-color--8f7770, #8F7770);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m16.22 10.549l1.03 2.871");
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c-11seb3g {
  d: path("M17.177 22.95a1 1 0 0 1 .723-1.221l5.303-1.34a1 1 0 0 1 1.213.719l2.414 9.289h-7.719z");
}

.c1udzvb2i {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M20.095 9.962c-.211-.184-.457-.379-.83-.496c-.366-.115-.826-.147-1.462-.069a.334.334 0 1 0 .082.664c.58-.07.936-.034 1.18.043c.24.075.4.197.59.363a.334.334 0 0 0 .44-.505");
}

.c4gw_rbvm {
  stroke: var(--svg-color--8f7770, #8F7770);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m14.781 12.733l.688 1.531");
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cgs6kxogn {
  stop-color: var(--svg-color--693e49, #693E49);
}

.cibaz8bjx {
  fill: var(--svg-color--5e3740, #5E3740);
  d: path("M17.3 8.916a.946.946 0 0 1 1.108.75l.356 1.849l-.086-1.383a.946.946 0 0 1 1.888-.117l.197 3.17l.327-.675a.989.989 0 1 1 1.78.863l-.817 1.683c-.174.42-.182.808-.19 1.219c-.008.374-.017.767-.152 1.221c-.236.796-.707 1.433-.913 1.653l-2.634.752c-2.028-.497-2.646-1.652-2.982-2.62a13 13 0 0 0-.659-1.585l-1.161-2.238a.946.946 0 0 1 1.678-.872l.194.372l-.463-1.348a.946.946 0 0 1 1.79-.614l.404 1.18l-.415-2.152a.946.946 0 0 1 .75-1.108");
}

.d4h8kcbpy {
  stop-color: var(--svg-color--502b29, #502B29);
  stop-opacity: 0;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dunk4xw2z {
  stop-color: var(--svg-color--725953, #725953);
  stop-opacity: 0;
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dy3bcxe9s {
  stop-color: var(--svg-color--8d635e, #8D635E);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.ee6wyldiv {
  stop-color: var(--svg-color--f84d1b, #F84D1B);
}

.eivezvbjc {
  stop-color: var(--svg-color--725953, #725953);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f8_tgzbue {
  stop-color: var(--svg-color--ff5016, #FF5016);
}

.f8osbx-ej {
  stop-color: var(--svg-color--d74a13, #D74A13);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fr74rck3u {
  d: path("M9.73 14.691a2 2 0 0 1-1.09-.372v1.123a2.62 2.62 0 0 0 1.616 2.435a5 5 0 0 1-.417-1.423z");
}

.ft5dv1b6b {
  fill: none;
}

.fvbl5pb0w {
  stop-color: var(--svg-color--a17b72, #A17B72);
}

.gapgjlb2u {
  d: path("M15.583 23.22c-1.46 0-2.64-.911-2.64-2.04v-2.41c0-1.128 1.18-2.04 2.64-2.04s2.64.912 2.64 2.04v2.41c0 1.129-1.18 2.04-2.64 2.04");
}

.gmelrdffb {
  stop-color: var(--svg-color--ff8040, #FF8040);
}

.gookgbqsm {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M11.48 9.83a3.35 3.35 0 0 1 2.097-.433a.335.335 0 0 1-.082.664a2.68 2.68 0 0 0-1.672.344q-.062.037-.09.058l-.02.014l-.004.002a.335.335 0 0 1-.41-.529z");
}

.grwv7pb9x {
  stroke: var(--svg-color--947468, #947468);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.577 14.016q.07-1.147.133-2.296a1.152 1.152 0 0 1-.133 2.296Z");
}

.gvh9ilzzf {
  stop-color: var(--svg-color--896758, #896758);
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h-r0_gb7p {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.525 10.168c.31-.222 1.082-.613 1.996-.46");
}

.h3xzehbak {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M17.643 17.841a2.47 2.47 0 0 0-2.06-1.12c-.862 0-1.618.45-2.059 1.12c-.096.144.038.316.192.297h3.726c.153.038.296-.144.2-.297");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hxawe1bvw {
  d: path("M25.583 30.397v-.39c0-5.4-4.47-9.787-9.99-9.787c-5.52.01-9.99 4.387-9.99 9.786v.39z");
}

.hy5bczbge {
  d: path("M21.456 14.691c.404-.013.783-.15 1.09-.372v1.123a2.62 2.62 0 0 1-1.616 2.435c.205-.437.346-.914.417-1.423z");
}

.i4docjyne {
  stop-color: var(--svg-color--ff9946, #FF9946);
  stop-opacity: 0;
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.j35ckxhbd {
  stop-color: var(--svg-color--66453c, #66453C);
}

.jcwfr4b-x {
  stop-color: var(--svg-color--77313f, #77313F);
}

.jrsz9e89j {
  stop-color: var(--svg-color--8f7770, #8F7770);
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.le1cd1ete {
  stop-color: var(--svg-color--805242, #805242);
}

.lf-s-qkac {
  stop-color: var(--svg-color--8f7770, #8F7770);
  stop-opacity: 0;
}

.lp5lg9kgv {
  d: path("M9.774 17.05a4.72 4.72 0 0 0 4.686 4.108h2.276a4.72 4.72 0 0 0 4.686-4.107c.142-2.272.285-5.067.39-7.338a1.75 1.75 0 0 0-1.662-1.727h-1.69a2.92 2.92 0 0 1-2.667-1.74a.8.8 0 0 0-.742-.504h-1.535c-2.226 0-4.03 1.824-4.03 4.075c0 2.244.14 4.984.287 7.234");
}

.lrdcrkb9v {
  stop-color: var(--svg-color--e5571e, #E5571E);
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lsom33rae {
  d: path("M21.529 14.8q.121-1.923.223-3.848a1.941 1.941 0 0 1-.223 3.849");
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m65v9eyqh {
  stop-color: var(--svg-color--6e3651, #6E3651);
}

.mghihr2mt {
  stop-color: var(--svg-color--7a4a3d, #7A4A3D);
}

.mkzsocckt {
  stop-color: var(--svg-color--664239, #664239);
}

.mleb6mb5e {
  stop-color: var(--svg-color--3f2a28, #3F2A28);
  stop-opacity: 0;
}

.my72jwxuh {
  stop-color: var(--svg-color--a17b72, #A17B72);
  stop-opacity: 0;
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.obs_54cbe {
  stop-color: var(--svg-color--804e49, #804E49);
}

.okkh45kiy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m20.94 9.252l.671 8.437");
}

.ov4q-2fcn {
  fill: var(--svg-color--46363b, #46363B);
  d: path("M20.767 6.355h-2.69a.626.626 0 1 1 .1-1.242c.698.111 1.625.266 2.246.42c1.403.348 1.79 1.03 1.898 1.518a1.96 1.96 0 0 0-1.554-.696");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.owlglgb_q {
  fill: var(--svg-color--2e201f, #2E201F);
  fill-rule: evenodd;
  d: path("M14.517 12.613c.15.11.183.32.074.47a2.02 2.02 0 0 1-1.641.828a2.05 2.05 0 0 1-1.639-.825a.336.336 0 1 1 .538-.403c.255.341.656.556 1.1.556c.457 0 .854-.216 1.098-.552c.11-.15.32-.183.47-.074");
}

.oxk0gpbzd {
  stop-color: var(--svg-color--d74a13, #D74A13);
  stop-opacity: 0;
}

.paa0g7bcq {
  d: path("M15.873 6.411a3 3 0 0 1-.08-.165a.8.8 0 0 0-.741-.504h-1.535c-2.226 0-4.03 1.824-4.03 4.075v.332c-.41-.312-.926-.97-.926-2.036c0-1.292.943-1.946 1.544-2.363c.17-.117.312-.216.399-.305l.12-.126c.422-.448 1.173-1.244 2.484-1.592a6.7 6.7 0 0 1 1.986-.193c.472.022.805.43.805.903v1.958z");
}

.peh2v9b4z {
  stop-color: var(--svg-color--664239, #664239);
  stop-opacity: 0;
}

.pms6qkxms {
  d: path("M21.448 5.172a2.8 2.8 0 0 1 1.529 1.268c.563.99.48 2.174-.128 3.047a1.9 1.9 0 0 0-.326 1.054v1.433a2.1 2.1 0 0 0-.805-.323l.095-1.938a1.75 1.75 0 0 0-1.663-1.727h-1.69a2.92 2.92 0 0 1-2.666-1.74a.8.8 0 0 0-.742-.504h-1.536c-2.226 0-4.03 1.824-4.03 4.075l.038 1.854c-.307.045-.627.147-.869.318v-1.448a1.9 1.9 0 0 0-.326-1.054a2.88 2.88 0 0 1-.173-2.95A2.83 2.83 0 0 1 9.723 5.18a3.23 3.23 0 0 0 1.67-1.34a2.804 2.804 0 0 1 3.486-1.099c.46.2.979.2 1.44 0c.338-.142.71-.226 1.1-.226c1.016 0 1.905.55 2.398 1.365c.371.614.953 1.06 1.631 1.293");
}

.pwuxh_ghz {
  d: path("m21.88 10.478l-.035-.761c-.013-.92-.774-1.68-1.695-1.72h-1.69A2.92 2.92 0 0 1 15.9 6.48s-.132-.306-.225-.796c-.185-.986.732-1.717 1.721-1.548c1.252.214 2.765.622 3.855 1.333c2.104 1.372 1.736 3.846.629 5.01");
}

.q568k0pgh {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m21.88 10.478l-.035-.761c-.013-.92-.774-1.68-1.695-1.72h-1.69A2.92 2.92 0 0 1 15.9 6.48s-.132-.306-.225-.796c-.185-.986.732-1.717 1.721-1.548c1.252.214 2.765.622 3.855 1.333c2.104 1.372 1.736 3.846.629 5.01");
}

.r0elt_brj {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("M15.873 6.411a3 3 0 0 1-.08-.165a.8.8 0 0 0-.741-.504h-1.535c-2.226 0-4.03 1.824-4.03 4.075v.332c-.41-.312-.926-.97-.926-2.036c0-1.292.943-1.946 1.544-2.363c.17-.117.312-.216.399-.305l.12-.126c.422-.448 1.173-1.244 2.484-1.592a6.7 6.7 0 0 1 1.986-.193c.472.022.805.43.805.903v1.958z");
}

.r91sqk84w {
  stop-color: var(--svg-color--6e3651, #6E3651);
  stop-opacity: 0;
}

.rk9yz2b8g {
  stop-color: var(--svg-color--3f2a28, #3F2A28);
}

.rly31c85z {
  stop-color: var(--svg-color--77514b, #77514B);
}

.ryim261uk {
  stop-color: var(--svg-color--66453c, #66453C);
  stop-opacity: 0;
}

.s3fe4zf2e {
  stop-color: var(--svg-color--502b29, #502B29);
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.sbbg3pb0u {
  d: path("M9.432 11.747a1.153 1.153 0 0 0 .1 2.267a94 94 0 0 1-.1-2.267");
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.t1udg90jz {
  stop-color: var(--svg-color--804e49, #804E49);
  stop-opacity: 0;
}

.tgllzx6xq {
  stop-color: var(--svg-color--d54625, #D54625);
}

.tp1nefb2t {
  stop-color: var(--svg-color--7b534e, #7B534E);
  stop-opacity: 0;
}

.u2zqby_zw {
  stop-color: var(--svg-color--6b4646, #6B4646);
}

.u8gj1d_ed {
  stop-color: var(--svg-color--6a3d40, #6A3D40);
}

.ub-l1fbpr {
  stop-color: var(--svg-color--211011, #211011);
  stop-opacity: 0;
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uu8x24bjn {
  stop-color: var(--svg-color--e5562d, #E5562D);
}

.v_-r5lbgt {
  stop-color: var(--svg-color--ff5016, #FF5016);
  stop-opacity: 0;
}

.v1j3m8bkp {
  d: path("M17.74 20.876a.25.25 0 0 1 .182-.302l4.733-1.205a.25.25 0 0 1 .305.183l.274 1.131l-5.229 1.267z");
}

.v8vgju-bc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m23.675 12.922l-.938 1.89a3.56 3.56 0 0 0-.36 1.782c.08.969-.265 1.828-.64 2.234");
}

.vqy53843t {
  stop-color: var(--svg-color--7b534e, #7B534E);
}

.vttm5o78n {
  d: path("M9.771 17.047a4.72 4.72 0 0 0 4.686 4.107h2.276a4.72 4.72 0 0 0 4.686-4.107c.142-2.272.288-5.063.394-7.334a1.75 1.75 0 0 0-1.663-1.727h-1.69a2.92 2.92 0 0 1-2.667-1.74a.8.8 0 0 0-.742-.504h-1.535c-2.226 0-4.03 1.824-4.03 4.075c0 2.244.137 4.98.284 7.23");
}

.vwzcj430b {
  stop-color: var(--svg-color--6f374a, #6F374A);
}

.vxrbqw1yr {
  stroke: var(--svg-color--8f7770, #8F7770);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m18.44 8.877l.716 3.856");
}

.vzyrucblm {
  stop-color: var(--svg-color--9f3b09, #9F3B09);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.xdqxlsbhz {
  d: path("M18.028 8.117a1.1 1.1 0 0 1 1.289.872l.414 2.15l-.1-1.608a1.1 1.1 0 0 1 2.195-.136l.23 3.687l.38-.785a1.15 1.15 0 1 1 2.07 1.004l-.95 1.957c-.203.489-.212.94-.222 1.417c-.01.435-.019.892-.176 1.42c-.275.926-.823 1.667-1.062 1.923l-3.063.875c-2.36-.579-3.078-1.922-3.469-3.047c-.312-.9-.64-1.605-.765-1.844L13.448 13.4a1.1 1.1 0 1 1 1.952-1.014l.225.432l-.539-1.569a1.1 1.1 0 0 1 2.081-.713l.471 1.372l-.482-2.503a1.1 1.1 0 0 1 .872-1.288");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.yr1b81w8m {
  stop-color: var(--svg-color--381d1b, #381D1B);
}

.yzag7e8_g {
  stop-color: var(--svg-color--ff764c, #FF764C);
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

</style>
