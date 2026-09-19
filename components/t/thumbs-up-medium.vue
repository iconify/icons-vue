<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ib7fu8b)"><path fill="url(#iDkmlte)" class="qeh5ncbyw"/></g><path fill="url(#iv3po2c)" class="qeh5ncbyw"/><path fill="url(#iqV4SFc)" class="qeh5ncbyw"/><path fill="url(#ikHVsWd)" class="qeh5ncbyw"/><path fill="url(#iCaQCxK)" class="qeh5ncbyw"/><path fill="url(#iNZeASc)" class="qeh5ncbyw"/><path fill="url(#iPmtSEb)" class="qeh5ncbyw"/><g filter="url(#isqr2pc)"><path fill="url(#iPhBRnb)" class="a6vpb3wgj"/></g><g filter="url(#ie5Ahod)"><rect fill="url(#i4HtH4b)" transform="rotate(90 26.311 10.956)" class="nulv6tb5a"/><rect fill="url(#i7go5tb)" transform="rotate(90 26.311 10.956)" class="nulv6tb5a"/><rect fill="url(#iiaq21b)" transform="rotate(90 26.311 10.956)" class="nulv6tb5a"/></g><g filter="url(#iCxeQMH)"><rect fill="url(#iRSUuWb)" class="w25b19b4p"/></g><g filter="url(#iQt9ped)"><rect fill="url(#ioLvbnc)" transform="rotate(90 26.01 24.241)" class="kyccnjggu"/><rect fill="url(#ifYeVge)" transform="rotate(90 26.01 24.241)" class="kyccnjggu"/><rect fill="url(#iLsg7Kb)" transform="rotate(90 26.01 24.241)" class="kyccnjggu"/></g><g filter="url(#iShjHob)"><rect fill="url(#icKN9pc)" class="r1mt1hjkq"/></g><g filter="url(#iCg70Dp)"><rect fill="url(#iRagPFc)" transform="rotate(90 27.31 19.96)" class="pio5ct8ci"/><rect fill="url(#iAcG8Jb)" transform="rotate(90 27.31 19.96)" class="pio5ct8ci"/><rect fill="url(#iHS1TsB)" transform="rotate(90 27.31 19.96)" class="pio5ct8ci"/></g><g filter="url(#irJt2Oe)"><rect fill="url(#iO4iaNb)" class="grgqambzq"/></g><g filter="url(#iP7KNAc)"><rect fill="url(#iZFZCLc)" transform="rotate(90 27.264 15.51)" class="c98xuu6bx"/><rect fill="url(#ixMKNzc)" transform="rotate(90 27.264 15.51)" class="c98xuu6bx"/></g><g filter="url(#iKPjsJb)"><rect fill="url(#iZRPb7G)" class="i1jeh-bor"/></g><path fill="url(#iRr9Wae)" class="uigkqbban"/><g filter="url(#iupeWqb)"><rect fill="url(#i3yHhie)" class="ark9ru4af"/></g><defs><radialGradient id="iv3po2c" cx="0" cy="0" r="1" gradientTransform="rotate(138.814 8.593 5.237)scale(3.70607 2.89161)" gradientUnits="userSpaceOnUse"><stop class="pts0xy57c"/><stop offset="1" class="twwcrgbem"/></radialGradient><radialGradient id="iqV4SFc" cx="0" cy="0" r="1" gradientTransform="rotate(133.564 1.942 10.305)scale(7.41221 5.36952)" gradientUnits="userSpaceOnUse"><stop class="jjdjrvb4p"/><stop offset="1" class="pqdo0bcyy"/></radialGradient><radialGradient id="ikHVsWd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.66242 7.45294 -4.59455 -4.72369 20.294 16.89)" gradientUnits="userSpaceOnUse"><stop class="t924gt6vp"/><stop offset="1" class="y7dc8cn2n"/></radialGradient><radialGradient id="iCaQCxK" cx="0" cy="0" r="1" gradientTransform="matrix(4.1316 -9.88413 13.06853 5.4627 13.525 30.794)" gradientUnits="userSpaceOnUse"><stop class="wbdjj5bzh"/><stop offset="1" class="m6ntpcjub"/></radialGradient><radialGradient id="iNZeASc" cx="0" cy="0" r="1" gradientTransform="matrix(-15.534 0 0 -23.9075 20.588 20.869)" gradientUnits="userSpaceOnUse"><stop offset=".864" class="k5m091goq"/><stop offset="1" class="skiu2vbny"/></radialGradient><radialGradient id="iPmtSEb" cx="0" cy="0" r="1" gradientTransform="matrix(1.21582 .98104 -1.29196 1.60114 18.72 11.382)" gradientUnits="userSpaceOnUse"><stop class="sg0dxj1cp"/><stop offset="1" class="c2ewiqcfn"/></radialGradient><radialGradient id="i7go5tb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.62598 2.65767 0 30.97 19.177)" gradientUnits="userSpaceOnUse"><stop class="l3zd0qkkt"/><stop offset="1" class="edpa67bvy"/></radialGradient><radialGradient id="iiaq21b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40872 1.84473 -1.2348 -.94296 31.8 18.529)" gradientUnits="userSpaceOnUse"><stop class="jjygqp2-n"/><stop offset="1" class="rss6y6b1y"/></radialGradient><radialGradient id="ifYeVge" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.31347 2.78222 0 31.674 31.307)" gradientUnits="userSpaceOnUse"><stop class="uixdc5dir"/><stop offset="1" class="vly00xzfz"/></radialGradient><radialGradient id="iLsg7Kb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.4169 1.66759 0 27.005 31.658)" gradientUnits="userSpaceOnUse"><stop class="c1ihkjwso"/><stop offset="1" class="o7z7cobtk"/></radialGradient><radialGradient id="iAcG8Jb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.21683 3.27876 0 33.273 28.062)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="mu5xzcbrj"/><stop offset="1" class="a6slafb4v"/></radialGradient><radialGradient id="iHS1TsB" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75329 1.92955 0 27.83 27.241)" gradientUnits="userSpaceOnUse"><stop class="o48cdutjm"/><stop offset="1" class="acz6lebqy"/></radialGradient><radialGradient id="ixMKNzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.09375 3.75685 0 33.097 23.056)" gradientUnits="userSpaceOnUse"><stop class="ayl9o28ey"/><stop offset="1" class="y87e1yqor"/></radialGradient><radialGradient id="iRr9Wae" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.57369 -2.59444 0 12.706 5.858)" gradientUnits="userSpaceOnUse"><stop class="bwtn_ui9b"/><stop offset="1" class="xxz-t-ndp"/></radialGradient><linearGradient id="iDkmlte" x1="20.081" x2="8.725" y1="12.059" y2="33.73" gradientUnits="userSpaceOnUse"><stop class="tn__pvw1l"/><stop offset="1" class="i1xbxnbsx"/></linearGradient><linearGradient id="iPhBRnb" x1="21.393" x2="21.393" y1="10.936" y2="26.587" gradientUnits="userSpaceOnUse"><stop class="w6hzl2b_r"/><stop offset="1" class="erc49nu5d"/></linearGradient><linearGradient id="i4HtH4b" x1="29.221" x2="29.221" y1="10.956" y2="18.218" gradientUnits="userSpaceOnUse"><stop class="sno2sab1o"/><stop offset="1" class="tw3wpibsq"/></linearGradient><linearGradient id="iRSUuWb" x1="25.027" x2="18.413" y1="13.072" y2="13.072" gradientUnits="userSpaceOnUse"><stop class="s3115pb1b"/><stop offset="1" class="auu1_fbgs"/></linearGradient><linearGradient id="ioLvbnc" x1="28.843" x2="28.843" y1="25.017" y2="33.102" gradientUnits="userSpaceOnUse"><stop class="g7cxi65hi"/><stop offset="1" class="c9c2-pb-q"/></linearGradient><linearGradient id="icKN9pc" x1="25.067" x2="19.278" y1="26.329" y2="26.329" gradientUnits="userSpaceOnUse"><stop class="zl2y45b_n"/><stop offset="1" class="twk-dubji"/></linearGradient><linearGradient id="iRagPFc" x1="30.291" x2="30.291" y1="20.851" y2="30.12" gradientUnits="userSpaceOnUse"><stop class="pltu3_b-x"/><stop offset="1" class="bhz3iekbj"/></linearGradient><linearGradient id="iO4iaNb" x1="25.962" x2="18.713" y1="22.459" y2="22.459" gradientUnits="userSpaceOnUse"><stop class="tnycaobjx"/><stop offset="1" class="c-_i80c1i"/></linearGradient><linearGradient id="iZFZCLc" x1="30.18" x2="30.18" y1="15.511" y2="25.624" gradientUnits="userSpaceOnUse"><stop class="qkblpbbna"/><stop offset="1" class="rekdx72fr"/></linearGradient><linearGradient id="iZRPb7G" x1="25.939" x2="18.208" y1="17.425" y2="17.425" gradientUnits="userSpaceOnUse"><stop class="aoch_x-kg"/><stop offset="1" class="qil1uhbke"/></linearGradient><linearGradient id="i3yHhie" x1="18.247" x2="15.692" y1="5.531" y2="5.531" gradientUnits="userSpaceOnUse"><stop class="i94u7374x"/><stop offset="1" class="oa5qxrb6u"/></linearGradient><filter id="ib7fu8b" width="19.048" height="27.809" x="5.271" y="2.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.443137 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2955"/></filter><filter id="isqr2pc" width="12.909" height="20.615" x="14" y="10.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2955" stdDeviation="1"/></filter><filter id="ie5Ahod" width="9.543" height="5.82" x="17.268" y="10.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.396078 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2955"/></filter><filter id="iCxeQMH" width="8.636" height="5.016" x="17.96" y="11.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2955" stdDeviation=".625"/></filter><filter id="iQt9ped" width="9.361" height="6.164" x="17.15" y="24.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.32549 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2955"/></filter><filter id="iShjHob" width="7.87" height="3.976" x="18.726" y="24.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2955" stdDeviation=".625"/></filter><filter id="iCg70Dp" width="11.159" height="6.464" x="17.15" y="19.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.55 0 0 0 0 0.385598 0 0 0 0 0.320833 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2955"/></filter><filter id="irJt2Oe" width="9.225" height="3.976" x="18.336" y="20.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2955" stdDeviation=".625"/></filter><filter id="iP7KNAc" width="10.614" height="6.333" x="17.15" y="15.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.566667 0 0 0 0 0.428736 0 0 0 0 0.323472 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2955"/></filter><filter id="iKPjsJb" width="9.672" height="5.016" x="17.889" y="15.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2955" stdDeviation=".625"/></filter><filter id="iupeWqb" width="4.87" height="10.497" x="14.75" y="2.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2955" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:thumbs-up-medium" /></template>
<style>
.a6slafb4v {
  stop-color: var(--svg-color--965973, #965973);
  stop-opacity: 0;
}

.a6vpb3wgj {
  d: path("M24.033 14.935a2.55 2.55 0 0 0-2.552-2.552h-2.826a2.552 2.552 0 0 0-1.638 4.508a2.557 2.557 0 0 0-.115 3.993A2.55 2.55 0 0 0 16 22.83v.126c0 .7.281 1.333.737 1.794a2.483 2.483 0 0 0 1.746 4.248h2.804a2.483 2.483 0 0 0 2.148-3.729a2.55 2.55 0 0 0 1.474-2.313v-.126c0-.79-.36-1.495-.922-1.963a2.56 2.56 0 0 0-.587-4.249c.394-.45.633-1.039.633-1.684");
}

.acz6lebqy {
  stop-color: var(--svg-color--70483e, #70483E);
  stop-opacity: 0;
}

.aoch_x-kg {
  stop-color: var(--svg-color--cda38e, #CDA38E);
}

.ark9ru4af {
  width: 2.37px;
  height: 7.997px;
  x: 16px;
  y: 3.338px;
  rx: 1.185px;
}

.auu1_fbgs {
  stop-color: var(--svg-color--d0a78f, #D0A78F);
  stop-opacity: 0;
}

.ayl9o28ey {
  stop-color: var(--svg-color--8f566c, #8F566C);
}

.bhz3iekbj {
  stop-color: var(--svg-color--8f665f, #8F665F);
}

.bwtn_ui9b {
  stop-color: var(--svg-color--936d5f, #936D5F);
}

.c-_i80c1i {
  stop-color: var(--svg-color--d0a68e, #D0A68E);
  stop-opacity: 0;
}

.c1ihkjwso {
  stop-color: var(--svg-color--744844, #744844);
}

.c2ewiqcfn {
  stop-color: var(--svg-color--c59f80, #C59F80);
  stop-opacity: 0;
}

.c98xuu6bx {
  width: 5.833px;
  height: 10.114px;
  x: 27.264px;
  y: 15.511px;
  rx: 2.91px;
}

.c9c2-pb-q {
  stop-color: var(--svg-color--906562, #906562);
}

.edpa67bvy {
  stop-color: var(--svg-color--9c7268, #9C7268);
  stop-opacity: 0;
}

.erc49nu5d {
  stop-color: var(--svg-color--794659, #794659);
}

.ft5dv1b6b {
  fill: none;
}

.g7cxi65hi {
  stop-color: var(--svg-color--c8a086, #C8A086);
}

.grgqambzq {
  width: 6.725px;
  height: 1.476px;
  x: 19.586px;
  y: 22.054px;
  rx: 0.738px;
}

.i1jeh-bor {
  width: 7.172px;
  height: 2.516px;
  x: 19.139px;
  y: 16.735px;
  rx: 1.258px;
}

.i1xbxnbsx {
  stop-color: var(--svg-color--a47077, #A47077);
}

.i94u7374x {
  stop-color: var(--svg-color--d0a88e, #D0A88E);
}

.jjdjrvb4p {
  stop-color: var(--svg-color--a9836c, #A9836C);
}

.jjygqp2-n {
  stop-color: var(--svg-color--6e4d3d, #6E4D3D);
}

.k5m091goq {
  stop-color: var(--svg-color--9d776a, #9D776A);
  stop-opacity: 0;
}

.kyccnjggu {
  width: 5.664px;
  height: 8.861px;
  x: 26.011px;
  y: 24.241px;
  rx: 2.832px;
}

.l3zd0qkkt {
  stop-color: var(--svg-color--9c7268, #9C7268);
}

.m6ntpcjub {
  stop-color: var(--svg-color--94527a, #94527A);
  stop-opacity: 0;
}

.mu5xzcbrj {
  stop-color: var(--svg-color--965973, #965973);
}

.nulv6tb5a {
  width: 5.82px;
  height: 9.043px;
  x: 26.311px;
  y: 10.956px;
  rx: 2.91px;
}

.o48cdutjm {
  stop-color: var(--svg-color--70483e, #70483E);
}

.o7z7cobtk {
  stop-color: var(--svg-color--744844, #744844);
  stop-opacity: 0;
}

.oa5qxrb6u {
  stop-color: var(--svg-color--d0a88e, #D0A88E);
  stop-opacity: 0;
}

.pio5ct8ci {
  width: 5.964px;
  height: 10.159px;
  x: 27.309px;
  y: 19.961px;
  rx: 2.91px;
}

.pltu3_b-x {
  stop-color: var(--svg-color--c6a083, #C6A083);
}

.pqdo0bcyy {
  stop-color: var(--svg-color--a9836c, #A9836C);
  stop-opacity: 0;
}

.pts0xy57c {
  stop-color: var(--svg-color--d1a98e, #D1A98E);
}

.qeh5ncbyw {
  d: path("M12.622 5.384a3.289 3.289 0 1 1 6.577 0v3.784q.002.484-.072.967c-.018.117-.037.235-.048.352c-.036.37.008.854.26 1.179l-.602.58a9.34 9.34 0 0 1 5.082 8.326c0 .985-.152 1.935-.433 2.826l-.996 6.507h-8.102v-.003c-5.003-.108-9.017-3.37-9.017-9.33c0-3.503 1.677-6.323 4.215-7.913l-.007-.005c.173-.12.377-.242.596-.373l.001-.001c.72-.431 1.6-.959 2.063-1.821c.403-.748.481-1.961.481-2.523h.002z");
}

.qil1uhbke {
  stop-color: var(--svg-color--cda38e, #CDA38E);
  stop-opacity: 0;
}

.qkblpbbna {
  stop-color: var(--svg-color--c6a183, #C6A183);
}

.r1mt1hjkq {
  width: 5.37px;
  height: 1.476px;
  x: 19.976px;
  y: 25.924px;
  rx: 0.738px;
}

.rekdx72fr {
  stop-color: var(--svg-color--9f7967, #9F7967);
}

.rss6y6b1y {
  stop-color: var(--svg-color--6e4d3d, #6E4D3D);
  stop-opacity: 0;
}

.s3115pb1b {
  stop-color: var(--svg-color--d0a78f, #D0A78F);
}

.sg0dxj1cp {
  stop-color: var(--svg-color--c59f80, #C59F80);
}

.skiu2vbny {
  stop-color: var(--svg-color--9d776a, #9D776A);
}

.sno2sab1o {
  stop-color: var(--svg-color--c29e7f, #C29E7F);
}

.t924gt6vp {
  stop-color: var(--svg-color--a17b6a, #A17B6A);
}

.tn__pvw1l {
  stop-color: var(--svg-color--c49c7f, #C49C7F);
}

.tnycaobjx {
  stop-color: var(--svg-color--d0a68e, #D0A68E);
}

.tw3wpibsq {
  stop-color: var(--svg-color--9a7561, #9A7561);
}

.twk-dubji {
  stop-color: var(--svg-color--c39a8a, #C39A8A);
  stop-opacity: 0;
}

.twwcrgbem {
  stop-color: var(--svg-color--d1a98e, #D1A98E);
  stop-opacity: 0;
}

.uigkqbban {
  d: path("M15.922 2.095a3.29 3.29 0 0 0-3.289 3.289v2.552h-.002c0 .562-.078 1.775-.48 2.523c-.464.862-1.344 1.39-2.063 1.82c-.22.132-.424.255-.597.375c.995.797 3.032 2.39 3.082 2.352s2.344-1.255 3.484-1.86l-.048-.69a3.29 3.29 0 0 0 3.201-3.288V5.384a3.29 3.29 0 0 0-3.288-3.289");
}

.uixdc5dir {
  stop-color: var(--svg-color--9d5e8e, #9D5E8E);
}

.vly00xzfz {
  stop-color: var(--svg-color--9d5e8e, #9D5E8E);
  stop-opacity: 0;
}

.w25b19b4p {
  width: 6.136px;
  height: 2.516px;
  x: 19.21px;
  y: 12.383px;
  rx: 1.258px;
}

.w6hzl2b_r {
  stop-color: var(--svg-color--5c3a34, #5C3A34);
}

.wbdjj5bzh {
  stop-color: var(--svg-color--94527a, #94527A);
}

.xxz-t-ndp {
  stop-color: var(--svg-color--936d5f, #936D5F);
  stop-opacity: 0;
}

.y7dc8cn2n {
  stop-color: var(--svg-color--a17b6a, #A17B6A);
  stop-opacity: 0;
}

.y87e1yqor {
  stop-color: var(--svg-color--8f566c, #8F566C);
  stop-opacity: 0;
}

.zl2y45b_n {
  stop-color: var(--svg-color--c39a8a, #C39A8A);
}

</style>
