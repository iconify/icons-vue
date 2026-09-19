<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iYNyZni)"><path fill="url(#iIe1hXd)" class="moa72ubmz"/></g><g filter="url(#iMZGHvb)"><path class="xlcpw2lzk"/></g><path fill="url(#i23C6Tc)" class="xbsaj-uui"/><path fill="url(#iaWmr0d)" class="xbsaj-uui"/><path fill="url(#iiH4Yfc)" class="xbsaj-uui"/><circle fill="url(#iQ4iY3c)" class="vm907b-lg"/><g filter="url(#iRioHZc)"><circle class="j7c2dm8ek"/></g><circle class="sri0u8-pr"/><g filter="url(#iwsCLFb)"><circle class="rzb2lf74w"/></g><path class="pvypw42ze"/><path fill="url(#iopwVuO)" class="v1ttmlbhg"/><g filter="url(#iZr33Xk)"><path fill="url(#ijs8vxb)" class="tii-dc-0g"/><path fill="url(#iGjKI8b)" class="tii-dc-0g"/><path fill="url(#id16IEc)" class="tii-dc-0g"/></g><g filter="url(#iirSMre)"><path class="xkcjtxb6u"/></g><g filter="url(#i2OHOsd)"><path fill="url(#iDQbyCb)" class="z2uwyibrq"/></g><g filter="url(#i1jm78c)"><circle stroke="url(#iCg7scd)" class="vzhyoybzj"/></g><circle class="knw8ztr-l"/><g filter="url(#i3fM1Yc)"><path class="ad2oyzbjh"/></g><g filter="url(#iKEGB6c)"><path class="b2obgtbti"/><path fill="url(#irlHV5b)" class="uwaliwtlv"/></g><path fill="url(#ih5Yt9d)" transform="rotate(45.489 15.02 13.488)" class="ypnnu1btu"/><path fill="url(#iynbCFc)" transform="rotate(45.489 15.02 13.488)" class="ypnnu1btu"/><path fill="url(#iTHAuIb)" class="eesmu_bgd"/><path fill="url(#iPodnxe)" class="eesmu_bgd"/><path fill="url(#imVCgud)" class="eesmu_bgd"/><path class="coggbopni"/><path fill="url(#izDhg5z)" class="heobtbbbw"/><path fill="url(#iVcGvId)" class="heobtbbbw"/><path fill="url(#iAp3ICb)" class="heobtbbbw"/><g filter="url(#iRAUQfe)"><path fill="url(#iIqC4Xb)" class="hfdahkb0n"/></g><path clip-rule="evenodd" class="tudbb9b0c"/><g filter="url(#iyRBunc)"><path clip-rule="evenodd" class="kskm1tbdw"/></g><g filter="url(#iYeAzNe)"><path fill="url(#iEP0K6d)" class="qxbfyfb0t"/></g><path clip-rule="evenodd" class="li_hepbct"/><g filter="url(#iUBYuLb)"><path stroke="url(#i2u60Oe)" clip-rule="evenodd" class="oapqf7b_d"/></g><path fill="url(#iEjaAJb)" class="kqhcfygcq"/><path fill="url(#ibukxLe)" class="kqhcfygcq"/><path fill="url(#i5KzQnc)" class="kqhcfygcq"/><path fill="url(#iIHLFwd)" clip-rule="evenodd" class="a0y9fmbmk"/><path clip-rule="evenodd" class="qgfqmgb-o"/><path fill="url(#ilWc86c)" clip-rule="evenodd" class="gkhhozbmw"/><path clip-rule="evenodd" class="dfa2ecbyh"/><path fill="url(#iVgNxcd)" clip-rule="evenodd" class="soik0-6nk"/><path clip-rule="evenodd" class="q_q7vijmu"/><path fill="url(#ifl2Mxb)" clip-rule="evenodd" class="nuvyj7bxr"/><g filter="url(#i5oBoHd)"><path clip-rule="evenodd" class="ehsl30bnf"/></g><path fill="url(#iZAIVsc)" class="ehe--tbpl"/><g filter="url(#iKkx4Xd)"><path class="km749hnka"/></g><defs><radialGradient id="i23C6Tc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.55405 -7.26436 11.24805 -3.95466 25.208 22.247)" gradientUnits="userSpaceOnUse"><stop class="yi44m24qf"/><stop offset="1" class="n84teibwv"/></radialGradient><radialGradient id="iaWmr0d" cx="0" cy="0" r="1" gradientTransform="matrix(5.40625 1.9375 -3.91835 10.93347 17.085 17.686)" gradientUnits="userSpaceOnUse"><stop class="krf-kcben"/><stop offset="1" class="vu2z42ehc"/></radialGradient><radialGradient id="iiH4Yfc" cx="0" cy="0" r="1" gradientTransform="matrix(-.20312 .59375 -4.82693 -1.65131 22.476 14.904)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="rt88_hbzi"/><stop offset="1" class="ohhy_ccoa"/></radialGradient><radialGradient id="iQ4iY3c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01562 .92188 -.5107 -.56264 19.098 11.265)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="nxwyz4bhr"/><stop offset="1" class="b5e11ac5g"/></radialGradient><radialGradient id="iopwVuO" cx="0" cy="0" r="1" gradientTransform="matrix(-.96094 .57072 -1.33444 -2.24682 12.031 16.99)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="vmakp5jzq"/><stop offset="1" class="un0gu9ray"/></radialGradient><radialGradient id="iGjKI8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.62564 5.1713 -5.97735 1.87902 16.573 15.085)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="q55noc2it"/><stop offset="1" class="cvbc4ozwb"/></radialGradient><radialGradient id="id16IEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 1.4375 -1.27293 1.32828 16.312 12.75)" gradientUnits="userSpaceOnUse"><stop offset=".277" class="j9zy7hbht"/><stop offset="1" class="zy0uiq7qe"/></radialGradient><radialGradient id="irlHV5b" cx="0" cy="0" r="1" gradientTransform="rotate(135.14 5.255 11.068)scale(.85969 .22297)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="p03ir8b6c"/><stop offset="1" class="vf734srhg"/></radialGradient><radialGradient id="iynbCFc" cx="0" cy="0" r="1" gradientTransform="rotate(90.613 1.04 14.327)scale(.28732 .60402)" gradientUnits="userSpaceOnUse"><stop offset=".649" class="wjyjhxryd"/><stop offset="1" class="y01zyrbyt"/></radialGradient><radialGradient id="izDhg5z" cx="0" cy="0" r="1" gradientTransform="matrix(-.49002 .31976 -.36893 -.56538 12.282 16.221)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="y84i3jbqp"/><stop offset="1" class="mn36x_bue"/></radialGradient><radialGradient id="iEjaAJb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.98375 -2.84815 4.15752 -4.35547 14.676 11.827)" gradientUnits="userSpaceOnUse"><stop class="vlvwusbfo"/><stop offset="1" class="p6ttd9f2t"/></radialGradient><radialGradient id="ibukxLe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.62339 -2.71253 4.39512 -10.73188 15.151 12.573)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="rhchqfjux"/><stop offset="1" class="zutq5mb1t"/></radialGradient><radialGradient id="i5KzQnc" cx="0" cy="0" r="1" gradientTransform="rotate(-166.638 8.312 5.4)scale(6.57907 6.85827)" gradientUnits="userSpaceOnUse"><stop offset=".729" class="rhchqfjux"/><stop offset="1" class="upjjwiblx"/></radialGradient><radialGradient id="ilWc86c" cx="0" cy="0" r="1" gradientTransform="rotate(146.787 3.763 4.337)scale(3.43755 1.60167)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="mhuz5bc6e"/><stop offset="1" class="ys3ttgv6u"/></radialGradient><radialGradient id="iVgNxcd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.21274 2.13195 -.99864 -1.5049 9.406 7.027)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="mhuz5bc6e"/><stop offset="1" class="ys3ttgv6u"/></radialGradient><radialGradient id="ifl2Mxb" cx="0" cy="0" r="1" gradientTransform="rotate(144.615 3.584 5.257)scale(3.29193 1.58011)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="mhuz5bc6e"/><stop offset="1" class="ys3ttgv6u"/></radialGradient><radialGradient id="iZAIVsc" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 .375 -.21772 2.97553 11.086 4.1)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="nih21rkyj"/><stop offset="1" class="irx6ulbbo"/></radialGradient><filter id="iYNyZni" width="28.306" height="9.762" x="2.291" y="12.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23152"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.584314 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23152" result="effect2_innerShadow_3987_23152"/></filter><filter id="iMZGHvb" width="19.969" height="19.969" x="11.086" y="1.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.137255 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23152"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.2 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23152" result="effect2_innerShadow_3987_23152"/></filter><filter id="iRioHZc" width="2.053" height="2.053" x="17.203" y="10.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23152" stdDeviation=".075"/></filter><filter id="iwsCLFb" width="9.644" height="9.644" x="7.823" y="12.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23152" stdDeviation="2"/></filter><filter id="iZr33Xk" width="10.005" height="10.019" x="10.953" y="10.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.152941 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23152"/></filter><filter id="iirSMre" width="2.645" height="2.414" x="15.445" y="9.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0313726 0 0 0 0 0.0352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23152"/></filter><filter id="i2OHOsd" width="28.306" height="9.762" x="2.291" y="19.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.580392 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23152"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.482353 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23152" result="effect2_innerShadow_3987_23152"/></filter><filter id="i1jm78c" width="2.217" height="2.217" x="16.332" y="15.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23152" stdDeviation=".1"/></filter><filter id="i3fM1Yc" width="2.906" height="2.964" x="14.27" y="13.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23152" stdDeviation=".2"/></filter><filter id="iKEGB6c" width="2.203" height="2.458" x="14.783" y="13.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.113725 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23152"/><feGaussianBlur result="effect2_foregroundBlur_3987_23152" stdDeviation=".05"/></filter><filter id="iRAUQfe" width="2.23" height="2.219" x="15.143" y="11.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.407843 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23152"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.631373 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23152" result="effect2_innerShadow_3987_23152"/></filter><filter id="iyRBunc" width="2.872" height="2.874" x="14.905" y="11.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23152" stdDeviation=".075"/></filter><filter id="iYeAzNe" width="2.23" height="2.219" x="12.354" y="14.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.407843 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23152"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.564706 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23152" result="effect2_innerShadow_3987_23152"/></filter><filter id="iUBYuLb" width="2.872" height="2.874" x="12.124" y="14.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23152" stdDeviation=".075"/></filter><filter id="i5oBoHd" width="4.333" height="3.319" x="8.122" y="5.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.188235 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23152"/></filter><filter id="iKkx4Xd" width="10.371" height="13.323" x="17.558" y="4.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23152" stdDeviation=".35"/></filter><linearGradient id="iIe1hXd" x1="27.278" x2="2.491" y1="16.555" y2="16.555" gradientUnits="userSpaceOnUse"><stop class="q8sgc5k5k"/><stop offset="1" class="o5v952b3t"/></linearGradient><linearGradient id="ijs8vxb" x1="19.797" x2="15.736" y1="14.865" y2="19.711" gradientUnits="userSpaceOnUse"><stop class="cj1s4nyzm"/><stop offset=".886" class="m7ycihb2x"/></linearGradient><linearGradient id="iDQbyCb" x1="27.278" x2="2.491" y1="23.617" y2="23.617" gradientUnits="userSpaceOnUse"><stop class="t8k4gwbbc"/><stop offset="1" class="kpw0uhrkg"/></linearGradient><linearGradient id="iCg7scd" x1="17.663" x2="17.632" y1="17.623" y2="15.717" gradientUnits="userSpaceOnUse"><stop class="wlhz9nb6r"/><stop offset="1" class="uq8mvlbhp"/></linearGradient><linearGradient id="ih5Yt9d" x1="15.39" x2="15.399" y1="13.662" y2="14.611" gradientUnits="userSpaceOnUse"><stop class="uhfoyqb3x"/><stop offset="1" class="eb0haibji"/></linearGradient><linearGradient id="iTHAuIb" x1="16.771" x2="17.861" y1="11.358" y2="11.181" gradientUnits="userSpaceOnUse"><stop class="nd7thpbgb"/><stop offset="1" class="fs5c4ebko"/></linearGradient><linearGradient id="iPodnxe" x1="17.146" x2="17.26" y1="10.625" y2="10.695" gradientUnits="userSpaceOnUse"><stop offset=".354" class="r7rn_bcmx"/><stop offset="1" class="ht-1xqb8g"/></linearGradient><linearGradient id="imVCgud" x1="17.753" x2="17.671" y1="11.064" y2="11.015" gradientUnits="userSpaceOnUse"><stop class="hb9tx9b6i"/><stop offset="1" class="ppgh7wbyg"/></linearGradient><linearGradient id="iVcGvId" x1="11.717" x2="11.591" y1="17.065" y2="16.87" gradientUnits="userSpaceOnUse"><stop offset=".145" class="u8ol5ho1k"/><stop offset="1" class="bbcrpz64i"/></linearGradient><linearGradient id="iAp3ICb" x1="11.256" x2="11.303" y1="16.394" y2="16.469" gradientUnits="userSpaceOnUse"><stop class="bwf4x3cld"/><stop offset="1" class="a5orf1efs"/></linearGradient><linearGradient id="iIqC4Xb" x1="17.21" x2="15.663" y1="12.154" y2="13.67" gradientUnits="userSpaceOnUse"><stop class="t40s1ccrt"/><stop offset="1" class="vjkwz1bxm"/></linearGradient><linearGradient id="iEP0K6d" x1="14.421" x2="12.874" y1="14.912" y2="16.428" gradientUnits="userSpaceOnUse"><stop class="ol7r9kndd"/><stop offset="1" class="xs-q3bbyy"/></linearGradient><linearGradient id="i2u60Oe" x1="14.713" x2="12.571" y1="14.615" y2="16.661" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qi1y9bzby"/><stop offset=".322" class="f-nlkoezi"/><stop offset=".768" class="qi1y9bzby"/></linearGradient><linearGradient id="iIHLFwd" x1="8.649" x2="11.674" y1="3.844" y2="3.527" gradientUnits="userSpaceOnUse"><stop class="fbovgw07t"/><stop offset="1" class="ir1yjg4tb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-swimming-dark" /></template>
<style>
.a0y9fmbmk {
  fill-rule: evenodd;
  d: path("M10.38 4.45c-.557.043-1.037.101-1.262.158a.663.663 0 0 1-.323-1.285c.836-.21 1.78-.262 2.642-.262c.365 0 1.049.296 1.049.662a.66.66 0 0 1-.663.663c-.345 0-.9.023-1.442.064");
}

.a5orf1efs {
  stop-color: var(--svg-color--504b5b, #504B5B);
  stop-opacity: 0;
}

.ad2oyzbjh {
  fill: var(--svg-color--2f1820, #2F1820);
  d: path("m15.491 16.282l-.82-1.636l.303-.296l1.588.896a.42.42 0 0 1 .089.666l-.488.481a.42.42 0 0 1-.672-.111");
}

.b2obgtbti {
  fill: var(--svg-color--4a3230, #4A3230);
  d: path("m15.664 16.015l-.781-1.556l.289-.281l1.51.852a.4.4 0 0 1 .084.634l-.464.457a.4.4 0 0 1-.638-.106");
}

.b5e11ac5g {
  stop-color: var(--svg-color--493430, #493430);
}

.bbcrpz64i {
  stop-color: var(--svg-color--443873, #443873);
  stop-opacity: 0;
}

.bwf4x3cld {
  stop-color: var(--svg-color--504b5b, #504B5B);
}

.cj1s4nyzm {
  stop-color: var(--svg-color--65504e, #65504E);
}

.coggbopni {
  fill: var(--svg-color--4e496a, #4E496A);
  d: path("M11.254 17.382c-.046.03-.082.05-.165 0l-.428-.283a.1.1 0 0 1-.026-.03a.1.1 0 0 1 .038-.12l1.538-1.06l.27.704z");
}

.cvbc4ozwb {
  stop-color: var(--svg-color--2c1421, #2C1421);
}

.dfa2ecbyh {
  fill: var(--svg-color--3b2726, #3B2726);
  fill-rule: evenodd;
  d: path("M12.115 4.727a.66.66 0 0 1-.608.713c-.639.05-1.949.359-2.427.803c-.482.448-.861 1.004-1.156 1.487a.663.663 0 0 1-1.13-.69c.314-.516.768-1.195 1.384-1.768c.62-.576 1.5-1.153 3.223-1.153c.366 0 .684.243.713.608");
}

.eb0haibji {
  stop-color: var(--svg-color--413251, #413251);
}

.eesmu_bgd {
  d: path("M17.576 10.162a.1.1 0 0 1 .122-.036q.017.008.027.024l.292.421l.01.02a.2.2 0 0 1-.023.173l-.73 1.13l-.605-.41z");
}

.ehe--tbpl {
  d: path("M11.086 7.037h4.829a4 4 0 0 1 3.602 2.26l6.163 12.459l4.125-.594L23.12 7.558a8 8 0 0 0-7.204-4.52h-4.457z");
}

.ehsl30bnf {
  fill: var(--svg-color--442b2d, #442B2D);
  fill-rule: evenodd;
  d: path("M11.792 7.063c-.584 0-1.22.227-1.658.526c-.31.21-.668.602-.821.805a.662.662 0 1 1-1.057-.8c.201-.266.66-.78 1.132-1.1c.63-.429 1.52-.756 2.404-.756a.662.662 0 1 1 0 1.325");
}

.f-nlkoezi {
  stop-color: var(--svg-color--5f5669, #5F5669);
  stop-opacity: 0;
}

.fbovgw07t {
  stop-color: var(--svg-color--402e2b, #402E2B);
}

.fs5c4ebko {
  stop-color: var(--svg-color--4c4055, #4C4055);
}

.ft5dv1b6b {
  fill: none;
}

.gkhhozbmw {
  fill-rule: evenodd;
  d: path("M11.71 3.945a.663.663 0 0 1-.607.714c-1.395.11-2.488 1.076-3.037 1.863a.662.662 0 1 1-1.087-.758c.678-.972 2.085-2.272 4.018-2.426a.663.663 0 0 1 .713.607");
}

.hb9tx9b6i {
  stop-color: var(--svg-color--574e60, #574E60);
}

.heobtbbbw {
  d: path("M11.254 17.382c-.046.03-.082.05-.165 0l-.428-.283a.1.1 0 0 1-.026-.03a.1.1 0 0 1 .038-.12l1.538-1.06l.27.704z");
}

.hfdahkb0n {
  d: path("M15.978 11.958a.821.821 0 0 1 1.148 1.175l-.488.476a.822.822 0 0 1-1.148-1.175z");
}

.ht-1xqb8g {
  stop-color: var(--svg-color--403044, #403044);
  stop-opacity: 0;
}

.ir1yjg4tb {
  stop-color: var(--svg-color--3d2d35, #3D2D35);
}

.irx6ulbbo {
  stop-color: var(--svg-color--3b2726, #3B2726);
  stop-opacity: 0;
}

.j7c2dm8ek {
  cx: 18.23px;
  cy: 11.925px;
  r: 0.877px;
  fill: var(--svg-color--3a1f1e, #3A1F1E);
}

.j9zy7hbht {
  stop-color: var(--svg-color--3b262a, #3B262A);
}

.km749hnka {
  fill: var(--svg-color--645352, #645352);
  d: path("M20.696 7.45c-.675-1.474-1.907-1.968-2.438-2.03c1.469-.157 2.672.789 3.156 1.656l5.815 10.25l-2.533-1.282c-1.053-2.25-3.325-7.118-4-8.593");
}

.knw8ztr-l {
  cx: 17.44px;
  cy: 16.693px;
  r: 0.809px;
  fill: var(--svg-color--290119, #290119);
}

.kpw0uhrkg {
  stop-color: var(--svg-color--4184e7, #4184E7);
}

.kqhcfygcq {
  d: path("M9.547 16.106c-1.483-1.483-1.304-3.838.255-5.61l1.314-1.305c1.687-1.534 4.11-1.73 5.593-.248l.345.345a.217.217 0 0 1 0 .306l-6.856 6.856a.217.217 0 0 1-.307 0z");
}

.krf-kcben {
  stop-color: var(--svg-color--2d1a1e, #2D1A1E);
}

.kskm1tbdw {
  stroke: var(--svg-color--5c4c6d, #5C4C6D);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.301 11.809c-.363-.372-1-.409-1.372-.045l-.56.546c-.372.364-.34.99.024 1.362s.976.431 1.349.067l.56-.546c.372-.363.363-1.012 0-1.384Z");
}

.li_hepbct {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m14.588 16.149l-.487.476a1.181 1.181 0 1 1-1.651-1.69l.487-.477a1.181 1.181 0 1 1 1.651 1.69m-.238-1.42a.82.82 0 0 0-1.161-.013l-.488.476a.821.821 0 0 0 1.148 1.175l.487-.476a.82.82 0 0 0 .014-1.162");
}

.m7ycihb2x {
  stop-color: var(--svg-color--381f30, #381F30);
}

.mhuz5bc6e {
  stop-color: var(--svg-color--31182a, #31182A);
}

.mn36x_bue {
  stop-color: var(--svg-color--483e5b, #483E5B);
  stop-opacity: 0;
}

.moa72ubmz {
  d: path("M4.366 12.139c-.975 0-1.656.49-1.875.734V21.9h27.907v-8.87l-.004-.004c-.623-.545-1.014-.887-2.2-.887c-.905 0-1.67.67-2.05 1.003c-.26.225-.939.637-1.864.637s-1.469-.406-2.07-.906c-.27-.224-.952-.734-1.914-.734c-.963 0-1.857.666-2.164 1c-.245.224-.719.64-1.871.64c-.793 0-1.396-.35-1.613-.562c-.37-.36-1.133-1.078-2.313-1.078c-.975 0-1.54.468-1.906.78c-.367.313-1.007.891-2.094.891c-.985 0-1.585-.5-1.914-.774l-.008-.007c-.276-.297-1.072-.89-2.047-.89");
}

.n84teibwv {
  stop-color: var(--svg-color--4a312f, #4A312F);
}

.nd7thpbgb {
  stop-color: var(--svg-color--574c62, #574C62);
}

.nih21rkyj {
  stop-color: var(--svg-color--3b2726, #3B2726);
}

.nuvyj7bxr {
  fill-rule: evenodd;
  d: path("M11.814 5.501a.66.66 0 0 1-.634.69c-1.184.05-2.098.941-2.666 1.871a.662.662 0 1 1-1.13-.69c.65-1.067 1.892-2.427 3.74-2.505a.66.66 0 0 1 .69.634");
}

.nxwyz4bhr {
  stop-color: var(--svg-color--655654, #655654);
}

.o5v952b3t {
  stop-color: var(--svg-color--3ea5fe, #3EA5FE);
}

.oapqf7b_d {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.52 14.604c-.363-.373-1-.41-1.372-.046l-.559.547c-.372.363-.34.99.024 1.362c.363.372.976.43 1.348.067l.56-.546c.372-.364.363-1.012 0-1.384Z");
}

.ohhy_ccoa {
  stop-color: var(--svg-color--291315, #291315);
  stop-opacity: 0;
}

.ol7r9kndd {
  stop-color: var(--svg-color--3387e0, #3387E0);
}

.p03ir8b6c {
  stop-color: var(--svg-color--645452, #645452);
}

.p6ttd9f2t {
  stop-color: var(--svg-color--287ed9, #287ED9);
}

.ppgh7wbyg {
  stop-color: var(--svg-color--574e60, #574E60);
  stop-opacity: 0;
}

.pvypw42ze {
  fill: var(--svg-color--282e5c, #282E5C);
  d: path("m11.273 17.399l-1.367-.93l1.102-1.266l1.226 2.196c-.293.294-.763.122-.96 0");
}

.q_q7vijmu {
  fill: var(--svg-color--3b2726, #3B2726);
  fill-rule: evenodd;
  d: path("M11.814 5.501a.66.66 0 0 1-.634.69c-1.184.05-2.098.941-2.666 1.871a.662.662 0 1 1-1.13-.69c.65-1.067 1.892-2.427 3.74-2.505a.66.66 0 0 1 .69.634");
}

.q55noc2it {
  stop-color: var(--svg-color--2c1421, #2C1421);
  stop-opacity: 0;
}

.q8sgc5k5k {
  stop-color: var(--svg-color--40aafe, #40AAFE);
}

.qgfqmgb-o {
  fill: var(--svg-color--3b2726, #3B2726);
  fill-rule: evenodd;
  d: path("M11.71 3.945a.663.663 0 0 1-.607.714c-1.395.11-2.488 1.076-3.037 1.863a.662.662 0 1 1-1.087-.758c.678-.972 2.085-2.272 4.018-2.426a.663.663 0 0 1 .713.607");
}

.qi1y9bzby {
  stop-color: var(--svg-color--5f5669, #5F5669);
}

.qxbfyfb0t {
  d: path("M13.189 14.716a.821.821 0 0 1 1.148 1.175l-.488.476a.821.821 0 1 1-1.148-1.175z");
}

.r7rn_bcmx {
  stop-color: var(--svg-color--403044, #403044);
}

.rhchqfjux {
  stop-color: var(--svg-color--3e81b3, #3E81B3);
  stop-opacity: 0;
}

.rt88_hbzi {
  stop-color: var(--svg-color--291315, #291315);
}

.rzb2lf74w {
  cx: 12.646px;
  cy: 17.514px;
  r: 0.822px;
  fill: var(--svg-color--25141e, #25141E);
}

.soik0-6nk {
  fill-rule: evenodd;
  d: path("M12.115 4.727a.66.66 0 0 1-.608.713c-.639.05-1.949.359-2.427.803c-.482.448-.861 1.004-1.156 1.487a.663.663 0 0 1-1.13-.69c.314-.516.768-1.195 1.384-1.768c.62-.576 1.5-1.153 3.223-1.153c.366 0 .684.243.713.608");
}

.sri0u8-pr {
  cx: 12.646px;
  cy: 17.514px;
  r: 1.296px;
  fill: var(--svg-color--2f1929, #2F1929);
}

.t40s1ccrt {
  stop-color: var(--svg-color--489be1, #489BE1);
}

.t8k4gwbbc {
  stop-color: var(--svg-color--3f90f0, #3F90F0);
}

.tii-dc-0g {
  d: path("M10.953 16.024v-.766l4.563-4.82c.21-.01.661-.045.98-.05c.319-.007.465.097.543.175c.68.672 2.117 2.238 3.102 3.367c.934 1.071.732 2.465.328 2.977c-.61.77-2.003 2.354-3.14 3.054s-2.397-.01-2.884-.453c-.86-.773-2.671-2.403-3.046-2.734c-.375-.332-.454-.638-.446-.75");
}

.tudbb9b0c {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m17.377 13.39l-.487.477a1.182 1.182 0 0 1-1.651-1.69l.487-.477a1.181 1.181 0 0 1 1.651 1.69m-.238-1.418a.82.82 0 0 0-1.161-.014l-.488.476a.821.821 0 1 0 1.148 1.175l.488-.476a.82.82 0 0 0 .013-1.161");
}

.u8ol5ho1k {
  stop-color: var(--svg-color--443873, #443873);
}

.uhfoyqb3x {
  stop-color: var(--svg-color--52475d, #52475D);
}

.un0gu9ray {
  stop-color: var(--svg-color--080207, #080207);
  stop-opacity: 0;
}

.upjjwiblx {
  stop-color: var(--svg-color--5c86b9, #5C86B9);
}

.uq8mvlbhp {
  stop-color: var(--svg-color--4a2b36, #4A2B36);
}

.uwaliwtlv {
  d: path("m15.664 16.015l-.781-1.556l.289-.281l1.51.852a.4.4 0 0 1 .084.634l-.464.457a.4.4 0 0 1-.638-.106");
}

.v1ttmlbhg {
  d: path("m11.273 17.399l-1.367-.93l1.102-1.266l1.226 2.196c-.293.294-.763.122-.96 0");
}

.vf734srhg {
  stop-color: var(--svg-color--645452, #645452);
  stop-opacity: 0;
}

.vjkwz1bxm {
  stop-color: var(--svg-color--4799ea, #4799EA);
}

.vlvwusbfo {
  stop-color: var(--svg-color--58a9fa, #58A9FA);
}

.vm907b-lg {
  cx: 18.23px;
  cy: 11.925px;
  r: 1.296px;
}

.vmakp5jzq {
  stop-color: var(--svg-color--080207, #080207);
}

.vu2z42ehc {
  stop-color: var(--svg-color--2d1a1e, #2D1A1E);
  stop-opacity: 0;
}

.vzhyoybzj {
  cx: 17.44px;
  cy: 16.693px;
  r: 0.809px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.wjyjhxryd {
  stop-color: var(--svg-color--453b50, #453B50);
}

.wlhz9nb6r {
  stop-color: var(--svg-color--544446, #544446);
}

.xbsaj-uui {
  d: path("M17.757 16.56c-1.688 1.15-3.224 3.25-3.781 4.157c3.25 2.162 7.927 2.172 9.859 1.906l6.531-2.266c-.765-1.304-2.036-2.52-2.531-3l-5.406-2.375c-.938 0-2.563.141-4.672 1.579");
}

.xkcjtxb6u {
  fill: var(--svg-color--322e2f, #322E2F);
  d: path("m17.086 9.375l.86 1.336c.095.141.224.492.08.878a39 39 0 0 0-.987-1.026c-.079-.078-.224-.182-.543-.176c-.22.004-.504.022-.727.036h-.003l-.32-.196z");
}

.xlcpw2lzk {
  fill: var(--svg-color--5a413e, #5A413E);
  d: path("M11.086 7.037h4.829a4 4 0 0 1 3.602 2.26l6.163 12.459l4.125-.594L23.12 7.558a8 8 0 0 0-7.204-4.52h-4.43z");
}

.xs-q3bbyy {
  stop-color: var(--svg-color--2f81cb, #2F81CB);
}

.y01zyrbyt {
  stop-color: var(--svg-color--453b50, #453B50);
  stop-opacity: 0;
}

.y84i3jbqp {
  stop-color: var(--svg-color--483e5b, #483E5B);
}

.yi44m24qf {
  stop-color: var(--svg-color--5c4a4a, #5C4A4A);
}

.ypnnu1btu {
  d: path("M15.02 13.488h.758v1.123h-.758z");
}

.ys3ttgv6u {
  stop-color: var(--svg-color--31182a, #31182A);
  stop-opacity: 0;
}

.z2uwyibrq {
  d: path("M4.366 19.201c-.975 0-1.656.49-1.875.735v9.027h27.907v-8.871l-.004-.003c-.623-.545-1.014-.888-2.2-.888c-.905 0-1.67.67-2.05 1.003v.001c-.26.224-.939.637-1.864.637s-1.469-.406-2.07-.906c-.27-.224-.952-.735-1.914-.735c-.963 0-1.857.667-2.164 1c-.245.224-.719.64-1.871.64c-.793 0-1.396-.35-1.613-.562c-.37-.36-1.133-1.078-2.313-1.078c-.975 0-1.54.469-1.906.781c-.367.313-1.007.891-2.094.891c-.985 0-1.585-.5-1.914-.775l-.008-.006c-.276-.297-1.072-.89-2.047-.89");
}

.zutq5mb1t {
  stop-color: var(--svg-color--3560c1, #3560C1);
}

.zy0uiq7qe {
  stop-color: var(--svg-color--3b262a, #3B262A);
  stop-opacity: 0;
}

</style>
