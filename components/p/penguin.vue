<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iwycgOd)" class="i44p1ccgu"/><path fill="url(#i8681Rh)" class="i44p1ccgu"/><path fill="url(#iWxFlQc)" class="i44p1ccgu"/><path fill="url(#iWZcHrB)" class="q12-azily"/><path fill="url(#iiRdRto)" class="q12-azily"/><g filter="url(#i3OXTTi)"><path fill="url(#iMEN6ic)" class="ufgy3mbbo"/></g><path fill="url(#iBL3wzc)" class="aiukmxp6n"/><path fill="url(#iPfwUee)" class="aiukmxp6n"/><path fill="url(#iWTUmPb)" class="aiukmxp6n"/><path fill="url(#iLFJx8d)" class="aiukmxp6n"/><path fill="url(#iHn2Ttc)" class="aiukmxp6n"/><g filter="url(#ismAq7C)"><path stroke="url(#iuDWW6d)" class="trc2tew3o"/></g><g filter="url(#i6O83ad)"><path fill="url(#ilm1Qic)" class="gyjig-b8s"/><path fill="url(#iIGXl5d)" class="gyjig-b8s"/></g><g filter="url(#ietrs9c)"><path fill="url(#iJBugKc)" class="z5x64-5yz"/><path fill="url(#ixv8mjO)" class="z5x64-5yz"/></g><path class="sz461vb9t"/><path fill="url(#iR3Mbrb)" class="f853ybv2u"/><path fill="url(#iWG4Qld)" class="f853ybv2u"/><path fill="url(#ibzsXVC)" class="f853ybv2u"/><g filter="url(#immFt0c)"><rect class="w0jqlz_ko"/></g><g filter="url(#idOBQXc)"><rect class="qz20p0yck"/></g><rect fill="url(#iit8amc)" class="gzh5anbox"/><rect fill="url(#ibCbrxb)" class="gzh5anbox"/><rect fill="url(#iV1Cfsc)" class="gzh5anbox"/><rect fill="url(#i8L5mcc)" class="k-dcf9bmo"/><rect fill="url(#iXNh7Qc)" class="k-dcf9bmo"/><rect fill="url(#iad4tOe)" class="k-dcf9bmo"/><g filter="url(#iwIxL4d)"><rect class="wmas7-boi"/></g><g filter="url(#iDb2Rib)"><rect class="ky8edobqo"/></g><path class="da_kdnbez"/><path fill="url(#i64BSVb)" class="uh-849bcw"/><path fill="url(#iTlIv0d)" class="uh-849bcw"/><path fill="url(#igysgoc)" class="uh-849bcw"/><path fill="url(#ik5GJqe)" class="uh-849bcw"/><path class="tqhh4psnb"/><path fill="url(#i9SxJge)" class="sbovpebcw"/><path fill="url(#ipFDfic)" class="sbovpebcw"/><defs><linearGradient id="i8681Rh" x1="4.959" x2="7.24" y1="24.558" y2="21.37" gradientUnits="userSpaceOnUse"><stop class="atic51bjk"/><stop offset="1" class="mnv661bzp"/></linearGradient><linearGradient id="iWZcHrB" x1="25.644" x2="25.644" y1="14.543" y2="23.866" gradientUnits="userSpaceOnUse"><stop class="z102g1bas"/><stop offset="1" class="esyyglbvv"/></linearGradient><linearGradient id="iiRdRto" x1="27.303" x2="25.244" y1="24.589" y2="22.193" gradientUnits="userSpaceOnUse"><stop class="atic51bjk"/><stop offset="1" class="mnv661bzp"/></linearGradient><linearGradient id="iMEN6ic" x1="28.317" x2="23.803" y1="23.37" y2="15.495" gradientUnits="userSpaceOnUse"><stop class="epl8o5bol"/><stop offset="1" class="xgd-vbbtg"/></linearGradient><linearGradient id="iBL3wzc" x1="15.975" x2="15.975" y1="5.808" y2="29.868" gradientUnits="userSpaceOnUse"><stop class="p9vp2dbhp"/><stop offset="1" class="lvne400bn"/></linearGradient><linearGradient id="iuDWW6d" x1="15.964" x2="15.964" y1="8.008" y2="28.113" gradientUnits="userSpaceOnUse"><stop class="h88-8nbww"/><stop offset="1" class="ogp-_dbzw"/></linearGradient><linearGradient id="ilm1Qic" x1="15.964" x2="15.964" y1="9.245" y2="28.113" gradientUnits="userSpaceOnUse"><stop class="w-hb9j-6l"/><stop offset="1" class="liqygh5yd"/></linearGradient><linearGradient id="iJBugKc" x1="18.24" x2="13.385" y1="14.554" y2="16.429" gradientUnits="userSpaceOnUse"><stop class="q6ay06bpd"/><stop offset="1" class="h31e8ibwb"/></linearGradient><linearGradient id="ixv8mjO" x1="16" x2="16" y1="13.933" y2="15.026" gradientUnits="userSpaceOnUse"><stop class="wmwuhcjfg"/><stop offset="1" class="r6opmy1bm"/></linearGradient><linearGradient id="ibzsXVC" x1="15.99" x2="15.99" y1="14.808" y2="14.214" gradientUnits="userSpaceOnUse"><stop offset=".136" class="al7xk3bms"/><stop offset="1" class="tkptz_bjg"/></linearGradient><linearGradient id="iit8amc" x1="14.943" x2="14.419" y1="10.51" y2="10.51" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="ibCbrxb" x1="15.085" x2="15.085" y1="11.356" y2="10.574" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="i8L5mcc" x1="17.943" x2="17.419" y1="10.51" y2="10.51" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iXNh7Qc" x1="18.085" x2="18.085" y1="11.356" y2="10.574" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="i64BSVb" x1="20.069" x2="20.069" y1="30.433" y2="29.058" gradientUnits="userSpaceOnUse"><stop offset=".136" class="al7xk3bms"/><stop offset="1" class="tkptz_bjg"/></linearGradient><linearGradient id="ik5GJqe" x1="20.069" x2="20.069" y1="30.127" y2="29.436" gradientUnits="userSpaceOnUse"><stop class="p_ptxbjeb"/><stop offset=".828" class="u5vkysn3x"/></linearGradient><linearGradient id="i9SxJge" x1="11.884" x2="11.884" y1="30.127" y2="29.436" gradientUnits="userSpaceOnUse"><stop class="p_ptxbjeb"/><stop offset=".828" class="u5vkysn3x"/></linearGradient><linearGradient id="ipFDfic" x1="16.521" x2="11.443" y1="29.436" y2="29.436" gradientUnits="userSpaceOnUse"><stop class="p_ptxbjeb"/><stop offset="1" class="u5vkysn3x"/></linearGradient><radialGradient id="iwycgOd" cx="0" cy="0" r="1" gradientTransform="rotate(-62.482 21.255 5.963)scale(5.88447 3.37643)" gradientUnits="userSpaceOnUse"><stop class="q9ixf49hc"/><stop offset="1" class="gg-lozmwe"/></radialGradient><radialGradient id="iWxFlQc" cx="0" cy="0" r="1" gradientTransform="rotate(130.427 .267 11.602)scale(7.30067 3.02415)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="bb-6enbhm"/><stop offset="1" class="rx-anjuzz"/></radialGradient><radialGradient id="iPfwUee" cx="0" cy="0" r="1" gradientTransform="rotate(138.39 9.464 8.207)scale(12.706 18.4562)" gradientUnits="userSpaceOnUse"><stop class="tywoi-4-t"/><stop offset="1" class="o2k99gbaw"/></radialGradient><radialGradient id="iWTUmPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.8125 7.20261 0 15.975 32.808)" gradientUnits="userSpaceOnUse"><stop class="s1bfw5bvk"/><stop offset="1" class="kfisb6bzr"/></radialGradient><radialGradient id="iLFJx8d" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 .64062 -.62073 .77212 17.084 8.089)" gradientUnits="userSpaceOnUse"><stop class="ryz1dqb4h"/><stop offset="1" class="kvg6lr7ul"/></radialGradient><radialGradient id="iHn2Ttc" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -1.0625 1.40213 1.97948 20.053 10.933)" gradientUnits="userSpaceOnUse"><stop class="ryz1dqb4h"/><stop offset="1" class="kvg6lr7ul"/></radialGradient><radialGradient id="iIGXl5d" cx="0" cy="0" r="1" gradientTransform="rotate(171.69 10.35 8.383)scale(11.2431 13.4274)" gradientUnits="userSpaceOnUse"><stop class="xf3nhjbpw"/><stop offset="1" class="rjglfj6xm"/></radialGradient><radialGradient id="iR3Mbrb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75 0 0 -2.69572 17.771 14.554)" gradientUnits="userSpaceOnUse"><stop class="x4izm_b1t"/><stop offset="1" class="n4t8q-2_w"/></radialGradient><radialGradient id="iWG4Qld" cx="0" cy="0" r="1" gradientTransform="rotate(106.025 3.889 11.864)scale(1.92439 1.93572)" gradientUnits="userSpaceOnUse"><stop class="x4izm_b1t"/><stop offset="1" class="n4t8q-2_w"/></radialGradient><radialGradient id="iV1Cfsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.27066 -.92835 1.08552 -.31648 14.587 10.741)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="iad4tOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.27066 -.92835 1.08552 -.31648 17.587 10.742)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="iTlIv0d" cx="0" cy="0" r="1" gradientTransform="matrix(4.25 0 0 8.69274 17.021 28.933)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="al7xk3bms"/><stop offset="1" class="tkptz_bjg"/></radialGradient><radialGradient id="igysgoc" cx="0" cy="0" r="1" gradientTransform="matrix(8.4375 0 0 8.1987 18.615 28.933)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="tkptz_bjg"/><stop offset="1" class="al7xk3bms"/></radialGradient><filter id="i3OXTTi" width="6.232" height="8.726" x="21.959" y="14.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4875" stdDeviation=".375"/></filter><filter id="ismAq7C" width="14.785" height="21.005" x="8.571" y="7.558" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4875" stdDeviation=".1"/></filter><filter id="i6O83ad" width="13.885" height="20.305" x="9.021" y="7.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.711813 0 0 0 0 0.656753 0 0 0 0 0.754167 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4875"/></filter><filter id="ietrs9c" width="6.73" height="4.621" x="12.635" y="13.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4875" stdDeviation=".375"/></filter><filter id="immFt0c" width="1.906" height="2.641" x="13.435" y="9.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4875" stdDeviation=".25"/></filter><filter id="idOBQXc" width="1.906" height="2.641" x="16.436" y="9.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4875" stdDeviation=".25"/></filter><filter id="iwIxL4d" width="1.12" height="1.997" x="17.051" y="9.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4875" stdDeviation=".2"/></filter><filter id="iDb2Rib" width="1.12" height="1.997" x="14.036" y="9.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4875" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:penguin" /></template>
<style>
.aiukmxp6n {
  d: path("M16.067 6.132c3.46 0 6.702 3.17 6.99 6.306c.028.298.176.99.37 1.878l.986 4.71c.165.793.301 2.448-.048 4.053a8.8 8.8 0 0 1-1.253 2.825l-.264 3.068s-5.133.922-6.995.895c-1.784-.025-6.72-.895-6.72-.895l-.311-3.068a8.9 8.9 0 0 1-1.236-2.83h-.002c-.348-1.603-.212-3.256-.047-4.048l.984-5.046l-.004-.001l.076-.36c.119-.557.208-.977.243-1.181c.553-3.207 3.363-6.306 7.23-6.306");
}

.al7xk3bms {
  stop-color: var(--svg-color--ff5762, #FF5762);
}

.atic51bjk {
  stop-color: var(--svg-color--462096, #462096);
}

.bb-6enbhm {
  stop-color: var(--svg-color--493659, #493659);
  stop-opacity: 0;
}

.da_kdnbez {
  fill: var(--svg-color--ff9d63, #FF9D63);
  d: path("M15.99 29.868h7.782a.37.37 0 0 0 .376-.385a8.2 8.2 0 0 0-1.02-3.603c-1.541 2.315-4.16 3.98-7.138 3.988");
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.epl8o5bol {
  stop-color: var(--svg-color--8760b5, #8760B5);
}

.esyyglbvv {
  stop-color: var(--svg-color--511691, #511691);
}

.f853ybv2u {
  d: path("M13.385 14.554h5.21a2.606 2.606 0 0 0-5.21 0");
}

.ft5dv1b6b {
  fill: none;
}

.gg-lozmwe {
  stop-color: var(--svg-color--501e65, #501E65);
}

.gyjig-b8s {
  d: path("M20.662 16.233c.505-.804.79-1.846.79-3.149c0-2.596-2.585-5.076-4.388-5.076c-.24 0-.324.26-.416.543c-.111.342-.234.72-.654.72c-.43 0-.571-.394-.696-.742c-.098-.275-.186-.52-.399-.52c-1.791 0-4.424 2.416-4.424 5.075c0 1.326.29 2.361.788 3.152A6.78 6.78 0 0 0 9.02 21.27c0 3.778 3.108 6.842 6.943 6.842s6.942-3.064 6.942-6.842a6.78 6.78 0 0 0-2.244-5.038");
}

.gzh5anbox {
  width: 0.906px;
  height: 1.641px;
  x: 14.037px;
  y: 9.792px;
  rx: 0.453px;
}

.h31e8ibwb {
  stop-color: var(--svg-color--e0b4e2, #E0B4E2);
  stop-opacity: 0;
}

.h88-8nbww {
  stop-color: var(--svg-color--60166f, #60166F);
}

.i44p1ccgu {
  d: path("M7.584 23.075c-1.34.722-2.542 1.073-3.099.516c-1.651-1.65 2.542-7.477 3.912-9.048l.12-.564h.004l-.984 5.047c-.165.793-.3 2.445.047 4.049");
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.k-dcf9bmo {
  width: 0.906px;
  height: 1.641px;
  x: 17.037px;
  y: 9.792px;
  rx: 0.453px;
}

.kfisb6bzr {
  stop-color: var(--svg-color--552eaa, #552EAA);
  stop-opacity: 0;
}

.kvg6lr7ul {
  stop-color: var(--svg-color--884790, #884790);
  stop-opacity: 0;
}

.ky8edobqo {
  width: 0.32px;
  height: 1.197px;
  x: 14.435px;
  y: 10.014px;
  fill: var(--svg-color--76676a, #76676A);
  rx: 0.16px;
}

.liqygh5yd {
  stop-color: var(--svg-color--efc3ff, #EFC3FF);
}

.lvne400bn {
  stop-color: var(--svg-color--4c20a3, #4C20A3);
}

.mnv661bzp {
  stop-color: var(--svg-color--462096, #462096);
  stop-opacity: 0;
}

.n4t8q-2_w {
  stop-color: var(--svg-color--ffa864, #FFA864);
  stop-opacity: 0;
}

.o2k99gbaw {
  stop-color: var(--svg-color--813687, #813687);
  stop-opacity: 0;
}

.ogp-_dbzw {
  stop-color: var(--svg-color--51309a, #51309A);
}

.p_ptxbjeb {
  stop-color: var(--svg-color--f15cc7, #F15CC7);
}

.p9vp2dbhp {
  stop-color: var(--svg-color--57275f, #57275F);
}

.q12-azily {
  d: path("M24.342 23.075c1.341.722 2.543 1.073 3.1.516c1.65-1.65-2.6-7.477-3.971-9.048c.07.394.774 3.74.919 4.483c.164.793.3 2.445-.048 4.049");
}

.q6ay06bpd {
  stop-color: var(--svg-color--e0b4e2, #E0B4E2);
}

.q9ixf49hc {
  stop-color: var(--svg-color--652998, #652998);
}

.qz20p0yck {
  width: 0.906px;
  height: 1.641px;
  x: 16.936px;
  y: 9.87px;
  fill: var(--svg-color--b5aaba, #B5AABA);
  rx: 0.453px;
}

.r6opmy1bm {
  stop-color: var(--svg-color--d9a7e6, #D9A7E6);
  stop-opacity: 0;
}

.rjglfj6xm {
  stop-color: var(--svg-color--fff6ff, #FFF6FF);
  stop-opacity: 0;
}

.rx-anjuzz {
  stop-color: var(--svg-color--493659, #493659);
}

.ryz1dqb4h {
  stop-color: var(--svg-color--884790, #884790);
}

.s1bfw5bvk {
  stop-color: var(--svg-color--552eaa, #552EAA);
}

.sbovpebcw {
  d: path("M15.964 29.868H8.182a.37.37 0 0 1-.376-.385a8.2 8.2 0 0 1 1.02-3.603c1.541 2.315 4.16 3.98 7.138 3.988");
}

.sz461vb9t {
  fill: var(--svg-color--f97725, #F97725);
  d: path("M13.385 14.554h5.21a2.606 2.606 0 0 0-5.21 0");
}

.tkptz_bjg {
  stop-color: var(--svg-color--ff5762, #FF5762);
  stop-opacity: 0;
}

.tqhh4psnb {
  fill: var(--svg-color--dd4533, #DD4533);
  d: path("M15.964 29.868H8.182a.37.37 0 0 1-.376-.385a8.2 8.2 0 0 1 1.02-3.603c1.541 2.315 4.16 3.98 7.138 3.988");
}

.trc2tew3o {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.822 16.211c.486-.815.756-1.852.756-3.127c0-1.338-.665-2.636-1.552-3.596c-.883-.957-2.01-1.605-2.962-1.605c-.178 0-.293.102-.37.224c-.07.114-.118.262-.162.396l-.003.01c-.057.175-.11.335-.194.454a.39.39 0 0 1-.341.179a.42.42 0 0 1-.362-.19c-.091-.124-.152-.291-.216-.469l-.003-.009a2 2 0 0 0-.166-.38c-.072-.114-.181-.215-.348-.215c-.944 0-2.08.63-2.975 1.58c-.897.953-1.574 2.251-1.574 3.621c0 1.296.273 2.328.752 3.13a6.9 6.9 0 0 0-2.206 5.057c0 3.85 3.166 6.967 7.068 6.967s7.067-3.118 7.067-6.967c0-1.993-.849-3.79-2.209-5.06Z");
}

.tywoi-4-t {
  stop-color: var(--svg-color--813687, #813687);
}

.u5vkysn3x {
  stop-color: var(--svg-color--f15cc7, #F15CC7);
  stop-opacity: 0;
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.ufgy3mbbo {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M27.425 22.142c-1.088-2.856-3.33-5.85-4.185-6.897l-.531 3.313c.845.496 2.955 2.395 4.277 3.828c.186.202.536.013.438-.244");
}

.uh-849bcw {
  d: path("M15.99 29.868h7.782a.37.37 0 0 0 .376-.385a8.2 8.2 0 0 0-1.02-3.603c-1.541 2.315-4.16 3.98-7.138 3.988");
}

.vh3k8hojv {
  stop-color: var(--svg-color--492847, #492847);
}

.w-hb9j-6l {
  stop-color: var(--svg-color--d4c5df, #D4C5DF);
}

.w0jqlz_ko {
  width: 0.906px;
  height: 1.641px;
  x: 13.935px;
  y: 9.87px;
  fill: var(--svg-color--b5aaba, #B5AABA);
  rx: 0.453px;
}

.wmas7-boi {
  width: 0.32px;
  height: 1.197px;
  x: 17.451px;
  y: 10.014px;
  fill: var(--svg-color--76676a, #76676A);
  rx: 0.16px;
}

.wmwuhcjfg {
  stop-color: var(--svg-color--d9a7e6, #D9A7E6);
}

.x4izm_b1t {
  stop-color: var(--svg-color--ffa864, #FFA864);
}

.xf3nhjbpw {
  stop-color: var(--svg-color--fff6ff, #FFF6FF);
}

.xgd-vbbtg {
  stop-color: var(--svg-color--8760b5, #8760B5);
  stop-opacity: 0;
}

.z102g1bas {
  stop-color: var(--svg-color--814690, #814690);
}

.z5x64-5yz {
  d: path("m13.385 17.398l5.23-2.844l-5.23-.278z");
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

</style>
