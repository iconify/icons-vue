<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ij4XeDd)"><path fill="url(#i3s9oab)" class="qeh5ncbyw"/></g><path fill="url(#isoOANe)" class="qeh5ncbyw"/><path fill="url(#iF2j7Rc)" class="qeh5ncbyw"/><path fill="url(#iStjpae)" class="qeh5ncbyw"/><path fill="url(#iFKsxic)" class="qeh5ncbyw"/><path fill="url(#iqo1Y5d)" class="qeh5ncbyw"/><path fill="url(#iMyzEOR)" class="qeh5ncbyw"/><path fill="url(#i7Rkbob)" class="qeh5ncbyw"/><g filter="url(#i66M1QF)"><path fill="url(#idBZCnb)" class="a6vpb3wgj"/></g><g filter="url(#i9P9RDc)"><rect fill="url(#i1YUgGG)" transform="rotate(90 26.311 10.956)" class="nulv6tb5a"/><rect fill="url(#ijr71Fb)" transform="rotate(90 26.311 10.956)" class="nulv6tb5a"/><rect fill="url(#iLcvfxd)" transform="rotate(90 26.311 10.956)" class="nulv6tb5a"/></g><g filter="url(#io2UDRd)"><rect fill="url(#iIMkmic)" class="w25b19b4p"/></g><g filter="url(#i7uYIqc)"><rect fill="url(#i5Ufmlg)" transform="rotate(90 26.01 24.241)" class="kyccnjggu"/><rect fill="url(#iDvhGFd)" transform="rotate(90 26.01 24.241)" class="kyccnjggu"/><rect fill="url(#ioMklND)" transform="rotate(90 26.01 24.241)" class="kyccnjggu"/></g><g filter="url(#inCrZ2d)"><rect fill="url(#iHlGXKe)" class="r1mt1hjkq"/></g><g filter="url(#imRtQRc)"><rect fill="url(#i9BORjc)" transform="rotate(90 27.31 19.96)" class="pio5ct8ci"/><rect fill="url(#ik55lCb)" transform="rotate(90 27.31 19.96)" class="pio5ct8ci"/><rect fill="url(#iAxd6Ob)" transform="rotate(90 27.31 19.96)" class="pio5ct8ci"/></g><g filter="url(#iKNlTve)"><rect fill="url(#i85ab0b)" class="grgqambzq"/></g><g filter="url(#i0jc0Ub)"><rect fill="url(#i4aWk7i)" transform="rotate(90 27.264 15.51)" class="c98xuu6bx"/><rect fill="url(#i8qrjie)" transform="rotate(90 27.264 15.51)" class="c98xuu6bx"/></g><g filter="url(#iTaytwI)"><rect fill="url(#i5aGGNb)" class="i1jeh-bor"/></g><path fill="url(#ijaJcAd)" class="uigkqbban"/><g filter="url(#ia2Hdjc)"><rect fill="url(#iZSS9nc)" class="ark9ru4af"/></g><defs><radialGradient id="isoOANe" cx="0" cy="0" r="1" gradientTransform="rotate(138.814 8.593 5.237)scale(3.70607 2.89161)" gradientUnits="userSpaceOnUse"><stop class="ru98iw_3a"/><stop offset="1" class="z5li42eoo"/></radialGradient><radialGradient id="iF2j7Rc" cx="0" cy="0" r="1" gradientTransform="rotate(133.564 1.942 10.305)scale(7.41221 5.36952)" gradientUnits="userSpaceOnUse"><stop class="yntexy35g"/><stop offset="1" class="ec0d7pbvy"/></radialGradient><radialGradient id="iStjpae" cx="0" cy="0" r="1" gradientTransform="matrix(-7.66242 7.45294 -4.59455 -4.72369 20.294 16.89)" gradientUnits="userSpaceOnUse"><stop class="zrjenab_c"/><stop offset="1" class="qyocg9-pb"/></radialGradient><radialGradient id="iFKsxic" cx="0" cy="0" r="1" gradientTransform="rotate(-62.612 33.391 8.059)scale(14.7421 26.2114)" gradientUnits="userSpaceOnUse"><stop class="ygl7afttv"/><stop offset="1" class="xtl7vac_b"/></radialGradient><radialGradient id="iqo1Y5d" cx="0" cy="0" r="1" gradientTransform="matrix(-15.534 0 0 -23.9075 20.588 20.869)" gradientUnits="userSpaceOnUse"><stop offset=".864" class="d-szx0bel"/><stop offset="1" class="bx7xnhbtf"/></radialGradient><radialGradient id="iMyzEOR" cx="0" cy="0" r="1" gradientTransform="matrix(1.21582 .98104 -1.29196 1.60114 18.72 11.382)" gradientUnits="userSpaceOnUse"><stop class="z4fb6ub1i"/><stop offset="1" class="e3ftxir7h"/><stop offset="1" class="stkx6k9pb"/></radialGradient><radialGradient id="ijr71Fb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.62598 2.65767 0 30.97 19.177)" gradientUnits="userSpaceOnUse"><stop class="wjf91u1qq"/><stop offset="1" class="bhlxa4q1r"/></radialGradient><radialGradient id="iLcvfxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40872 1.84473 -1.2348 -.94296 31.8 18.529)" gradientUnits="userSpaceOnUse"><stop class="ku54jj8kv"/><stop offset="1" class="x15ym-56r"/></radialGradient><radialGradient id="iDvhGFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.20767 1.55607 0 31.674 30.55)" gradientUnits="userSpaceOnUse"><stop class="yrmc81bmf"/><stop offset="1" class="b2_1gmnqk"/></radialGradient><radialGradient id="ioMklND" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.72969 1.51308 0 27.005 30.97)" gradientUnits="userSpaceOnUse"><stop class="mi-x0xb8a"/><stop offset="1" class="ur3hlccac"/></radialGradient><radialGradient id="ik55lCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.21683 3.27876 0 33.273 28.062)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="c1klzybds"/><stop offset="1" class="e79j01bcx"/></radialGradient><radialGradient id="iAxd6Ob" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75329 1.92955 0 27.83 27.241)" gradientUnits="userSpaceOnUse"><stop class="rdqwj6bmr"/><stop offset="1" class="lcskbtbgt"/></radialGradient><radialGradient id="i8qrjie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.09375 3.75685 0 33.097 23.056)" gradientUnits="userSpaceOnUse"><stop class="pt8z4j02c"/><stop offset="1" class="bwrmzkhui"/></radialGradient><radialGradient id="ijaJcAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.32895 -2.49784 0 12.706 6.167)" gradientUnits="userSpaceOnUse"><stop class="isd7-25wt"/><stop offset="1" class="v_z7nenim"/></radialGradient><linearGradient id="i3s9oab" x1="20.081" x2="8.725" y1="12.059" y2="33.73" gradientUnits="userSpaceOnUse"><stop class="x_q7-kble"/><stop offset="1" class="auk33tc_r"/></linearGradient><linearGradient id="i7Rkbob" x1="14.545" x2="14.545" y1="31.125" y2="27.688" gradientUnits="userSpaceOnUse"><stop class="hil9j9kpd"/><stop offset="1" class="x73gdabcv"/></linearGradient><linearGradient id="idBZCnb" x1="19.753" x2="19.753" y1="14.231" y2="29.599" gradientUnits="userSpaceOnUse"><stop class="eegbscaef"/><stop offset="1" class="na5ei0zsx"/></linearGradient><linearGradient id="i1YUgGG" x1="29.221" x2="29.221" y1="10.956" y2="19.101" gradientUnits="userSpaceOnUse"><stop class="nsooqoy6p"/><stop offset="1" class="yfy1_vovx"/></linearGradient><linearGradient id="iIMkmic" x1="25.027" x2="18.413" y1="13.072" y2="13.072" gradientUnits="userSpaceOnUse"><stop class="yt0xribym"/><stop offset="1" class="l-gqjgbqw"/></linearGradient><linearGradient id="i5Ufmlg" x1="28.843" x2="28.843" y1="25.017" y2="33.102" gradientUnits="userSpaceOnUse"><stop class="njm9l3bis"/><stop offset="1" class="p-o1c0b1l"/></linearGradient><linearGradient id="iHlGXKe" x1="25.067" x2="19.278" y1="26.329" y2="26.329" gradientUnits="userSpaceOnUse"><stop class="vz3o85b-o"/><stop offset="1" class="exe7gfbfv"/></linearGradient><linearGradient id="i9BORjc" x1="30.291" x2="30.291" y1="20.851" y2="30.12" gradientUnits="userSpaceOnUse"><stop class="i8xyi-54t"/><stop offset="1" class="rfkom0qbt"/></linearGradient><linearGradient id="i85ab0b" x1="25.962" x2="18.713" y1="22.459" y2="22.459" gradientUnits="userSpaceOnUse"><stop class="yj1c11i9y"/><stop offset="1" class="q4mksjbcu"/></linearGradient><linearGradient id="i4aWk7i" x1="30.18" x2="30.18" y1="15.511" y2="25.624" gradientUnits="userSpaceOnUse"><stop class="x0n4s-bkb"/><stop offset="1" class="tnnnao6lh"/></linearGradient><linearGradient id="i5aGGNb" x1="25.939" x2="18.208" y1="17.425" y2="17.425" gradientUnits="userSpaceOnUse"><stop class="scjo-lbpq"/><stop offset="1" class="r9hd54buy"/></linearGradient><linearGradient id="iZSS9nc" x1="18.247" x2="15.692" y1="5.531" y2="5.531" gradientUnits="userSpaceOnUse"><stop class="yt0xribym"/><stop offset="1" class="l-gqjgbqw"/></linearGradient><filter id="ij4XeDd" width="19.048" height="27.809" x="5.271" y="2.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.67451 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2983"/></filter><filter id="i66M1QF" width="12.909" height="20.615" x="14" y="10.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2983" stdDeviation="1"/></filter><filter id="i9P9RDc" width="9.543" height="5.82" x="17.268" y="10.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.690196 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2983"/></filter><filter id="io2UDRd" width="8.636" height="5.016" x="17.96" y="11.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2983" stdDeviation=".625"/></filter><filter id="i7uYIqc" width="9.361" height="6.164" x="17.15" y="24.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.568627 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2983"/></filter><filter id="inCrZ2d" width="7.87" height="3.976" x="18.726" y="24.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2983" stdDeviation=".625"/></filter><filter id="imRtQRc" width="11.159" height="6.464" x="17.15" y="19.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.576471 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2983"/></filter><filter id="iKNlTve" width="9.225" height="3.976" x="18.336" y="20.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2983" stdDeviation=".625"/></filter><filter id="i0jc0Ub" width="10.614" height="6.333" x="17.15" y="15.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.658824 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2983"/></filter><filter id="iTaytwI" width="9.672" height="5.016" x="17.889" y="15.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2983" stdDeviation=".625"/></filter><filter id="ia2Hdjc" width="4.87" height="10.497" x="14.75" y="2.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2983" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:thumbs-up-light" /></template>
<style>
.a6vpb3wgj {
  d: path("M24.033 14.935a2.55 2.55 0 0 0-2.552-2.552h-2.826a2.552 2.552 0 0 0-1.638 4.508a2.557 2.557 0 0 0-.115 3.993A2.55 2.55 0 0 0 16 22.83v.126c0 .7.281 1.333.737 1.794a2.483 2.483 0 0 0 1.746 4.248h2.804a2.483 2.483 0 0 0 2.148-3.729a2.55 2.55 0 0 0 1.474-2.313v-.126c0-.79-.36-1.495-.922-1.963a2.56 2.56 0 0 0-.587-4.249c.394-.45.633-1.039.633-1.684");
}

.ark9ru4af {
  width: 2.37px;
  height: 7.997px;
  x: 16px;
  y: 3.338px;
  rx: 1.185px;
}

.auk33tc_r {
  stop-color: var(--svg-color--e7afa8, #E7AFA8);
}

.b2_1gmnqk {
  stop-color: var(--svg-color--bf8196, #BF8196);
  stop-opacity: 0;
}

.bhlxa4q1r {
  stop-color: var(--svg-color--dfa995, #DFA995);
  stop-opacity: 0;
}

.bwrmzkhui {
  stop-color: var(--svg-color--d39797, #D39797);
  stop-opacity: 0;
}

.bx7xnhbtf {
  stop-color: var(--svg-color--edb29b, #EDB29B);
}

.c1klzybds {
  stop-color: var(--svg-color--ca8e96, #CA8E96);
}

.c98xuu6bx {
  width: 5.833px;
  height: 10.114px;
  x: 27.264px;
  y: 15.511px;
  rx: 2.91px;
}

.d-szx0bel {
  stop-color: var(--svg-color--edb29b, #EDB29B);
  stop-opacity: 0;
}

.e3ftxir7h {
  stop-color: var(--svg-color--f7c49c, #F7C49C);
  stop-opacity: 0;
}

.e79j01bcx {
  stop-color: var(--svg-color--ca8e96, #CA8E96);
  stop-opacity: 0;
}

.ec0d7pbvy {
  stop-color: var(--svg-color--f2c0a5, #F2C0A5);
  stop-opacity: 0;
}

.eegbscaef {
  stop-color: var(--svg-color--b5755f, #B5755F);
}

.exe7gfbfv {
  stop-color: var(--svg-color--ffd2c1, #FFD2C1);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.grgqambzq {
  width: 6.725px;
  height: 1.476px;
  x: 19.586px;
  y: 22.054px;
  rx: 0.738px;
}

.hil9j9kpd {
  stop-color: var(--svg-color--b57895, #B57895);
}

.i1jeh-bor {
  width: 7.172px;
  height: 2.516px;
  x: 19.139px;
  y: 16.735px;
  rx: 1.258px;
}

.i8xyi-54t {
  stop-color: var(--svg-color--ffddc1, #FFDDC1);
}

.isd7-25wt {
  stop-color: var(--svg-color--e0a892, #E0A892);
}

.ku54jj8kv {
  stop-color: var(--svg-color--ca8c6f, #CA8C6F);
}

.kyccnjggu {
  width: 5.664px;
  height: 8.861px;
  x: 26.011px;
  y: 24.241px;
  rx: 2.832px;
}

.l-gqjgbqw {
  stop-color: var(--svg-color--ffe7ca, #FFE7CA);
  stop-opacity: 0;
}

.lcskbtbgt {
  stop-color: var(--svg-color--bb7e6c, #BB7E6C);
  stop-opacity: 0;
}

.mi-x0xb8a {
  stop-color: var(--svg-color--b57767, #B57767);
}

.na5ei0zsx {
  stop-color: var(--svg-color--b3748d, #B3748D);
}

.njm9l3bis {
  stop-color: var(--svg-color--feceb7, #FECEB7);
}

.nsooqoy6p {
  stop-color: var(--svg-color--ffd8ba, #FFD8BA);
}

.nulv6tb5a {
  width: 5.82px;
  height: 9.043px;
  x: 26.311px;
  y: 10.956px;
  rx: 2.91px;
}

.p-o1c0b1l {
  stop-color: var(--svg-color--daa59e, #DAA59E);
}

.pio5ct8ci {
  width: 5.964px;
  height: 10.159px;
  x: 27.309px;
  y: 19.961px;
  rx: 2.91px;
}

.pt8z4j02c {
  stop-color: var(--svg-color--d39797, #D39797);
}

.q4mksjbcu {
  stop-color: var(--svg-color--ffe2c9, #FFE2C9);
  stop-opacity: 0;
}

.qeh5ncbyw {
  d: path("M12.622 5.384a3.289 3.289 0 1 1 6.577 0v3.784q.002.484-.072.967c-.018.117-.037.235-.048.352c-.036.37.008.854.26 1.179l-.602.58a9.34 9.34 0 0 1 5.082 8.326c0 .985-.152 1.935-.433 2.826l-.996 6.507h-8.102v-.003c-5.003-.108-9.017-3.37-9.017-9.33c0-3.503 1.677-6.323 4.215-7.913l-.007-.005c.173-.12.377-.242.596-.373l.001-.001c.72-.431 1.6-.959 2.063-1.821c.403-.748.481-1.961.481-2.523h.002z");
}

.qyocg9-pb {
  stop-color: var(--svg-color--dda895, #DDA895);
  stop-opacity: 0;
}

.r1mt1hjkq {
  width: 5.37px;
  height: 1.476px;
  x: 19.976px;
  y: 25.924px;
  rx: 0.738px;
}

.r9hd54buy {
  stop-color: var(--svg-color--ffe8ca, #FFE8CA);
  stop-opacity: 0;
}

.rdqwj6bmr {
  stop-color: var(--svg-color--bb7e6c, #BB7E6C);
}

.rfkom0qbt {
  stop-color: var(--svg-color--e5b1a3, #E5B1A3);
}

.ru98iw_3a {
  stop-color: var(--svg-color--ffe6c7, #FFE6C7);
}

.scjo-lbpq {
  stop-color: var(--svg-color--ffe8ca, #FFE8CA);
}

.stkx6k9pb {
  stop-color: var(--svg-color--ffdbba, #FFDBBA);
  stop-opacity: 0;
}

.tnnnao6lh {
  stop-color: var(--svg-color--e2ae9c, #E2AE9C);
}

.uigkqbban {
  d: path("M15.922 2.095a3.29 3.29 0 0 0-3.289 3.289v2.552h-.002c0 .562-.078 1.775-.48 2.523c-.464.862-1.344 1.39-2.063 1.82c-.22.132-.424.255-.597.375c.995.797 3.032 2.39 3.082 2.352s2.344-1.255 3.484-1.86l-.048-.69a3.29 3.29 0 0 0 3.201-3.288V5.384a3.29 3.29 0 0 0-3.288-3.289");
}

.ur3hlccac {
  stop-color: var(--svg-color--b57767, #B57767);
  stop-opacity: 0;
}

.v_z7nenim {
  stop-color: var(--svg-color--e0a892, #E0A892);
  stop-opacity: 0;
}

.vz3o85b-o {
  stop-color: var(--svg-color--ffd2c1, #FFD2C1);
}

.w25b19b4p {
  width: 6.136px;
  height: 2.516px;
  x: 19.21px;
  y: 12.383px;
  rx: 1.258px;
}

.wjf91u1qq {
  stop-color: var(--svg-color--dfa995, #DFA995);
}

.x_q7-kble {
  stop-color: var(--svg-color--ffddbe, #FFDDBE);
}

.x0n4s-bkb {
  stop-color: var(--svg-color--ffdfbf, #FFDFBF);
}

.x15ym-56r {
  stop-color: var(--svg-color--ca8c6f, #CA8C6F);
  stop-opacity: 0;
}

.x73gdabcv {
  stop-color: var(--svg-color--b57895, #B57895);
  stop-opacity: 0;
}

.xtl7vac_b {
  stop-color: var(--svg-color--c08494, #C08494);
  stop-opacity: 0;
}

.yfy1_vovx {
  stop-color: var(--svg-color--ecb9a3, #ECB9A3);
}

.ygl7afttv {
  stop-color: var(--svg-color--c08494, #C08494);
}

.yj1c11i9y {
  stop-color: var(--svg-color--ffe2c9, #FFE2C9);
}

.yntexy35g {
  stop-color: var(--svg-color--f2c0a5, #F2C0A5);
}

.yrmc81bmf {
  stop-color: var(--svg-color--bf8196, #BF8196);
}

.yt0xribym {
  stop-color: var(--svg-color--ffe7ca, #FFE7CA);
}

.z4fb6ub1i {
  stop-color: var(--svg-color--ffdbba, #FFDBBA);
}

.z5li42eoo {
  stop-color: var(--svg-color--ffe6c7, #FFE6C7);
  stop-opacity: 0;
}

.zrjenab_c {
  stop-color: var(--svg-color--dda895, #DDA895);
}

</style>
