<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iXL1tNB)"><path fill="url(#i3VmBtb)" class="qeh5ncbyw"/></g><path fill="url(#idlPMAA)" class="qeh5ncbyw"/><path fill="url(#iiYVGGt)" class="qeh5ncbyw"/><path fill="url(#ifJf4uc)" class="qeh5ncbyw"/><path fill="url(#izQKupd)" class="qeh5ncbyw"/><path fill="url(#i4wDKHe)" class="qeh5ncbyw"/><path fill="url(#id1rf4d)" class="qeh5ncbyw"/><g filter="url(#iV5esAe)"><path fill="url(#irQUpce)" class="a6vpb3wgj"/></g><g filter="url(#iZe4fVc)"><rect fill="url(#iNPwODQ)" transform="rotate(90 26.311 10.956)" class="nulv6tb5a"/><rect fill="url(#izmNOae)" transform="rotate(90 26.311 10.956)" class="nulv6tb5a"/><rect fill="url(#ilHGbcc)" transform="rotate(90 26.311 10.956)" class="nulv6tb5a"/></g><g filter="url(#iWUMICe)"><rect fill="url(#isPhBhe)" class="w25b19b4p"/></g><g filter="url(#iDgQqHb)"><rect fill="url(#itDdoMd)" transform="rotate(90 26.01 24.241)" class="kyccnjggu"/><rect fill="url(#iBSrEQb)" transform="rotate(90 26.01 24.241)" class="kyccnjggu"/><rect fill="url(#iHDwcfo)" transform="rotate(90 26.01 24.241)" class="kyccnjggu"/></g><g filter="url(#iU0hQWd)"><rect fill="url(#iSqCQqb)" class="r1mt1hjkq"/></g><g filter="url(#izhN9Lc)"><rect fill="url(#iFRq9xi)" transform="rotate(90 27.31 19.96)" class="pio5ct8ci"/><rect fill="url(#iEmdGxI)" transform="rotate(90 27.31 19.96)" class="pio5ct8ci"/><rect fill="url(#iwcDQTc)" transform="rotate(90 27.31 19.96)" class="pio5ct8ci"/></g><g filter="url(#iQFZzPd)"><rect fill="url(#iMDbIEe)" class="grgqambzq"/></g><g filter="url(#ier8Gpb)"><rect fill="url(#iRdwxsb)" transform="rotate(90 27.264 15.51)" class="c98xuu6bx"/><rect fill="url(#ikHBJFb)" transform="rotate(90 27.264 15.51)" class="c98xuu6bx"/></g><g filter="url(#iCE6CFe)"><rect fill="url(#iOpdirc)" class="i1jeh-bor"/></g><path fill="url(#i1jRBPK)" class="uigkqbban"/><g filter="url(#ibDVpSc)"><rect fill="url(#iuRX8yi)" class="ark9ru4af"/></g><defs><radialGradient id="idlPMAA" cx="0" cy="0" r="1" gradientTransform="rotate(138.814 8.593 5.237)scale(3.70607 2.89161)" gradientUnits="userSpaceOnUse"><stop class="advb1zb4m"/><stop offset="1" class="ia5-t3c-u"/></radialGradient><radialGradient id="iiYVGGt" cx="0" cy="0" r="1" gradientTransform="matrix(-7.66242 7.45294 -4.59455 -4.72369 20.294 16.89)" gradientUnits="userSpaceOnUse"><stop class="gfmakcbdd"/><stop offset="1" class="yfah7vbku"/></radialGradient><radialGradient id="ifJf4uc" cx="0" cy="0" r="1" gradientTransform="rotate(-62.612 33.391 8.059)scale(14.7421 26.2114)" gradientUnits="userSpaceOnUse"><stop class="onzqjjixs"/><stop offset="1" class="fje43bhwd"/></radialGradient><radialGradient id="izQKupd" cx="0" cy="0" r="1" gradientTransform="matrix(-15.534 0 0 -23.9075 20.588 20.869)" gradientUnits="userSpaceOnUse"><stop offset=".864" class="vnjmj3gpn"/><stop offset="1" class="fwyazab1n"/></radialGradient><radialGradient id="i4wDKHe" cx="0" cy="0" r="1" gradientTransform="matrix(1.21582 .98104 -1.29196 1.60114 18.72 11.382)" gradientUnits="userSpaceOnUse"><stop class="sv9xf0bly"/><stop offset="1" class="e3ftxir7h"/></radialGradient><radialGradient id="izmNOae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.62598 2.65767 0 30.97 19.177)" gradientUnits="userSpaceOnUse"><stop class="slefdpdcm"/><stop offset="1" class="hji893t6i"/></radialGradient><radialGradient id="ilHGbcc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40872 1.84473 -1.2348 -.94296 31.8 18.529)" gradientUnits="userSpaceOnUse"><stop class="w0-cqc19b"/><stop offset="1" class="o_g7hdb4z"/></radialGradient><radialGradient id="iBSrEQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.31347 2.78222 0 31.674 31.307)" gradientUnits="userSpaceOnUse"><stop class="nf2o5qbze"/><stop offset="1" class="ex60piboi"/></radialGradient><radialGradient id="iHDwcfo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.72969 1.51308 0 27.005 30.97)" gradientUnits="userSpaceOnUse"><stop class="dtjv0j7qk"/><stop offset="1" class="w4to8_b-b"/></radialGradient><radialGradient id="iEmdGxI" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.21683 3.27876 0 33.273 28.062)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="bkf4m2zqp"/><stop offset="1" class="clyj_tzfk"/></radialGradient><radialGradient id="iwcDQTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75329 1.92955 0 27.83 27.241)" gradientUnits="userSpaceOnUse"><stop class="r05c89boy"/><stop offset="1" class="g1he-4h_q"/></radialGradient><radialGradient id="ikHBJFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.09375 3.75685 0 33.097 23.056)" gradientUnits="userSpaceOnUse"><stop class="kjtniebpy"/><stop offset="1" class="gb--i1bbk"/></radialGradient><radialGradient id="i1jRBPK" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.32895 -2.49784 0 12.706 6.167)" gradientUnits="userSpaceOnUse"><stop class="g6u-gdy9j"/><stop offset="1" class="xxz-t-ndp"/><stop offset="1" class="n490tzi7b"/></radialGradient><linearGradient id="i3VmBtb" x1="20.081" x2="8.725" y1="12.059" y2="33.73" gradientUnits="userSpaceOnUse"><stop class="yhcqnrlhd"/><stop offset="1" class="d-kel6q6i"/></linearGradient><linearGradient id="id1rf4d" x1="14.545" x2="14.545" y1="31.125" y2="27.688" gradientUnits="userSpaceOnUse"><stop class="ohlm_6lse"/><stop offset="1" class="dahqgvbpg"/></linearGradient><linearGradient id="irQUpce" x1="19.753" x2="19.753" y1="14.231" y2="29.599" gradientUnits="userSpaceOnUse"><stop class="ixut9_1bw"/><stop offset="1" class="qb6dh_ucy"/></linearGradient><linearGradient id="iNPwODQ" x1="29.221" x2="29.221" y1="10.956" y2="18.218" gradientUnits="userSpaceOnUse"><stop class="e-4q8mblz"/><stop offset="1" class="sd49k712l"/></linearGradient><linearGradient id="isPhBhe" x1="25.027" x2="18.413" y1="13.072" y2="13.072" gradientUnits="userSpaceOnUse"><stop class="eyqrs1b7e"/><stop offset="1" class="oixbo9bdy"/></linearGradient><linearGradient id="itDdoMd" x1="28.843" x2="28.843" y1="25.017" y2="33.102" gradientUnits="userSpaceOnUse"><stop class="gapeqnpmv"/><stop offset="1" class="wbaklabni"/></linearGradient><linearGradient id="iSqCQqb" x1="25.067" x2="19.278" y1="26.329" y2="26.329" gradientUnits="userSpaceOnUse"><stop class="ux79_ktnr"/><stop offset="1" class="hqvkw0ons"/></linearGradient><linearGradient id="iFRq9xi" x1="30.291" x2="30.291" y1="20.851" y2="30.12" gradientUnits="userSpaceOnUse"><stop class="j570yibrm"/><stop offset="1" class="hjg23zbyn"/></linearGradient><linearGradient id="iMDbIEe" x1="25.962" x2="18.713" y1="22.459" y2="22.459" gradientUnits="userSpaceOnUse"><stop class="sw9kfub9a"/><stop offset="1" class="pt9iq2bqp"/></linearGradient><linearGradient id="iRdwxsb" x1="30.18" x2="30.18" y1="15.511" y2="25.624" gradientUnits="userSpaceOnUse"><stop class="z4c1o0b3n"/><stop offset="1" class="pwls1xxqu"/></linearGradient><linearGradient id="iOpdirc" x1="25.939" x2="18.208" y1="17.425" y2="17.425" gradientUnits="userSpaceOnUse"><stop class="eyqrs1b7e"/><stop offset="1" class="oixbo9bdy"/></linearGradient><linearGradient id="iuRX8yi" x1="18.247" x2="15.692" y1="5.531" y2="5.531" gradientUnits="userSpaceOnUse"><stop class="r_tw_ub5a"/><stop offset="1" class="oa5qxrb6u"/><stop offset="1" class="ph-1oee-a"/></linearGradient><filter id="iXL1tNB" width="19.048" height="27.809" x="5.271" y="2.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.766667 0 0 0 0 0.57524 0 0 0 0 0.440833 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2969"/></filter><filter id="iV5esAe" width="12.909" height="20.615" x="14" y="10.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2969" stdDeviation="1"/></filter><filter id="iZe4fVc" width="9.543" height="5.82" x="17.268" y="10.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2969"/></filter><filter id="iWUMICe" width="8.636" height="5.016" x="17.96" y="11.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2969" stdDeviation=".625"/></filter><filter id="iDgQqHb" width="9.361" height="6.164" x="17.15" y="24.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.52549 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2969"/></filter><filter id="iU0hQWd" width="7.87" height="3.976" x="18.726" y="24.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2969" stdDeviation=".625"/></filter><filter id="izhN9Lc" width="11.159" height="6.464" x="17.15" y="19.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.576471 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2969"/></filter><filter id="iQFZzPd" width="9.225" height="3.976" x="18.336" y="20.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2969" stdDeviation=".625"/></filter><filter id="ier8Gpb" width="10.614" height="6.333" x="17.15" y="15.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.643137 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2969"/></filter><filter id="iCE6CFe" width="9.672" height="5.016" x="17.889" y="15.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2969" stdDeviation=".625"/></filter><filter id="ibDVpSc" width="4.87" height="10.497" x="14.75" y="2.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2969" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:thumbs-up-medium-light" /></template>
<style>
.a6vpb3wgj {
  d: path("M24.033 14.935a2.55 2.55 0 0 0-2.552-2.552h-2.826a2.552 2.552 0 0 0-1.638 4.508a2.557 2.557 0 0 0-.115 3.993A2.55 2.55 0 0 0 16 22.83v.126c0 .7.281 1.333.737 1.794a2.483 2.483 0 0 0 1.746 4.248h2.804a2.483 2.483 0 0 0 2.148-3.729a2.55 2.55 0 0 0 1.474-2.313v-.126c0-.79-.36-1.495-.922-1.963a2.56 2.56 0 0 0-.587-4.249c.394-.45.633-1.039.633-1.684");
}

.advb1zb4m {
  stop-color: var(--svg-color--ffd1a8, #FFD1A8);
}

.ark9ru4af {
  width: 2.37px;
  height: 7.997px;
  x: 16px;
  y: 3.338px;
  rx: 1.185px;
}

.bkf4m2zqp {
  stop-color: var(--svg-color--bd7884, #BD7884);
}

.c98xuu6bx {
  width: 5.833px;
  height: 10.114px;
  x: 27.264px;
  y: 15.511px;
  rx: 2.91px;
}

.clyj_tzfk {
  stop-color: var(--svg-color--bd7884, #BD7884);
  stop-opacity: 0;
}

.d-kel6q6i {
  stop-color: var(--svg-color--d59792, #D59792);
}

.dahqgvbpg {
  stop-color: var(--svg-color--b56f8a, #B56F8A);
  stop-opacity: 0;
}

.dtjv0j7qk {
  stop-color: var(--svg-color--b37365, #B37365);
}

.e-4q8mblz {
  stop-color: var(--svg-color--efc39b, #EFC39B);
}

.e3ftxir7h {
  stop-color: var(--svg-color--f7c49c, #F7C49C);
  stop-opacity: 0;
}

.ex60piboi {
  stop-color: var(--svg-color--b66e8d, #B66E8D);
  stop-opacity: 0;
}

.eyqrs1b7e {
  stop-color: var(--svg-color--ffd1ab, #FFD1AB);
}

.fje43bhwd {
  stop-color: var(--svg-color--b66f8a, #B66F8A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwyazab1n {
  stop-color: var(--svg-color--dda488, #DDA488);
}

.g1he-4h_q {
  stop-color: var(--svg-color--ad7158, #AD7158);
  stop-opacity: 0;
}

.g6u-gdy9j {
  stop-color: var(--svg-color--cd967a, #CD967A);
}

.gapeqnpmv {
  stop-color: var(--svg-color--edbb9d, #EDBB9D);
}

.gb--i1bbk {
  stop-color: var(--svg-color--c07d80, #C07D80);
  stop-opacity: 0;
}

.gfmakcbdd {
  stop-color: var(--svg-color--d09c82, #D09C82);
}

.grgqambzq {
  width: 6.725px;
  height: 1.476px;
  x: 19.586px;
  y: 22.054px;
  rx: 0.738px;
}

.hjg23zbyn {
  stop-color: var(--svg-color--d19b86, #D19B86);
}

.hji893t6i {
  stop-color: var(--svg-color--c28a6e, #C28A6E);
  stop-opacity: 0;
}

.hqvkw0ons {
  stop-color: var(--svg-color--eeb8a3, #EEB8A3);
  stop-opacity: 0;
}

.i1jeh-bor {
  width: 7.172px;
  height: 2.516px;
  x: 19.139px;
  y: 16.735px;
  rx: 1.258px;
}

.ia5-t3c-u {
  stop-color: var(--svg-color--ffd1a8, #FFD1A8);
  stop-opacity: 0;
}

.ixut9_1bw {
  stop-color: var(--svg-color--9b6049, #9B6049);
}

.j570yibrm {
  stop-color: var(--svg-color--f3bf9a, #F3BF9A);
}

.kjtniebpy {
  stop-color: var(--svg-color--c07d80, #C07D80);
}

.kyccnjggu {
  width: 5.664px;
  height: 8.861px;
  x: 26.011px;
  y: 24.241px;
  rx: 2.832px;
}

.n490tzi7b {
  stop-color: var(--svg-color--cd967a, #CD967A);
  stop-opacity: 0;
}

.nf2o5qbze {
  stop-color: var(--svg-color--b66e8d, #B66E8D);
}

.nulv6tb5a {
  width: 5.82px;
  height: 9.043px;
  x: 26.311px;
  y: 10.956px;
  rx: 2.91px;
}

.o_g7hdb4z {
  stop-color: var(--svg-color--a96f52, #A96F52);
  stop-opacity: 0;
}

.oa5qxrb6u {
  stop-color: var(--svg-color--d0a88e, #D0A88E);
  stop-opacity: 0;
}

.ohlm_6lse {
  stop-color: var(--svg-color--b56f8a, #B56F8A);
}

.oixbo9bdy {
  stop-color: var(--svg-color--ffd1ab, #FFD1AB);
  stop-opacity: 0;
}

.onzqjjixs {
  stop-color: var(--svg-color--b66f8a, #B66F8A);
}

.ph-1oee-a {
  stop-color: var(--svg-color--ffd2aa, #FFD2AA);
  stop-opacity: 0;
}

.pio5ct8ci {
  width: 5.964px;
  height: 10.159px;
  x: 27.309px;
  y: 19.961px;
  rx: 2.91px;
}

.pt9iq2bqp {
  stop-color: var(--svg-color--ffcbab, #FFCBAB);
  stop-opacity: 0;
}

.pwls1xxqu {
  stop-color: var(--svg-color--ce997e, #CE997E);
}

.qb6dh_ucy {
  stop-color: var(--svg-color--a66663, #A66663);
}

.qeh5ncbyw {
  d: path("M12.622 5.384a3.289 3.289 0 1 1 6.577 0v3.784q.002.484-.072.967c-.018.117-.037.235-.048.352c-.036.37.008.854.26 1.179l-.602.58a9.34 9.34 0 0 1 5.082 8.326c0 .985-.152 1.935-.433 2.826l-.996 6.507h-8.102v-.003c-5.003-.108-9.017-3.37-9.017-9.33c0-3.503 1.677-6.323 4.215-7.913l-.007-.005c.173-.12.377-.242.596-.373l.001-.001c.72-.431 1.6-.959 2.063-1.821c.403-.748.481-1.961.481-2.523h.002z");
}

.r_tw_ub5a {
  stop-color: var(--svg-color--ffd2aa, #FFD2AA);
}

.r05c89boy {
  stop-color: var(--svg-color--ad7158, #AD7158);
}

.r1mt1hjkq {
  width: 5.37px;
  height: 1.476px;
  x: 19.976px;
  y: 25.924px;
  rx: 0.738px;
}

.sd49k712l {
  stop-color: var(--svg-color--d5a184, #D5A184);
}

.slefdpdcm {
  stop-color: var(--svg-color--c28a6e, #C28A6E);
}

.sv9xf0bly {
  stop-color: var(--svg-color--f7c49c, #F7C49C);
}

.sw9kfub9a {
  stop-color: var(--svg-color--ffcbab, #FFCBAB);
}

.uigkqbban {
  d: path("M15.922 2.095a3.29 3.29 0 0 0-3.289 3.289v2.552h-.002c0 .562-.078 1.775-.48 2.523c-.464.862-1.344 1.39-2.063 1.82c-.22.132-.424.255-.597.375c.995.797 3.032 2.39 3.082 2.352s2.344-1.255 3.484-1.86l-.048-.69a3.29 3.29 0 0 0 3.201-3.288V5.384a3.29 3.29 0 0 0-3.288-3.289");
}

.ux79_ktnr {
  stop-color: var(--svg-color--eeb8a3, #EEB8A3);
}

.vnjmj3gpn {
  stop-color: var(--svg-color--dda488, #DDA488);
  stop-opacity: 0;
}

.w0-cqc19b {
  stop-color: var(--svg-color--a96f52, #A96F52);
}

.w25b19b4p {
  width: 6.136px;
  height: 2.516px;
  x: 19.21px;
  y: 12.383px;
  rx: 1.258px;
}

.w4to8_b-b {
  stop-color: var(--svg-color--b37365, #B37365);
  stop-opacity: 0;
}

.wbaklabni {
  stop-color: var(--svg-color--c68e82, #C68E82);
}

.xxz-t-ndp {
  stop-color: var(--svg-color--936d5f, #936D5F);
  stop-opacity: 0;
}

.yfah7vbku {
  stop-color: var(--svg-color--d09c82, #D09C82);
  stop-opacity: 0;
}

.yhcqnrlhd {
  stop-color: var(--svg-color--fdc79f, #FDC79F);
}

.z4c1o0b3n {
  stop-color: var(--svg-color--f9c89d, #F9C89D);
}

</style>
