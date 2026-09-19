<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="iuetbobya"/><path fill="url(#iViKTLd)" class="wd-1lzi5x"/><path fill="url(#iqWod6c)" class="wd-1lzi5x"/><path fill="url(#iAgKp6V)" class="wd-1lzi5x"/><g filter="url(#iSF03mb)"><path class="s90tzhfxo"/></g><g filter="url(#i9jvmMd)"><path fill="url(#i6geKgc)" clip-rule="evenodd" class="fexcm827x"/></g><path fill="url(#iaZ0uKe)" class="jscaxfbci"/><path fill="url(#ic2b0eb)" class="jscaxfbci"/><path fill="url(#idhWwmb)" class="jscaxfbci"/><g filter="url(#iX9Q0gb)"><path fill="url(#iZ3g62d)" class="xo_16ykwd"/></g><g filter="url(#iTUESee)"><path fill="url(#iHwv9Sd)" class="tlf42qb4e"/><path fill="url(#iuwI7db)" class="tlf42qb4e"/><path fill="url(#i2xQyNe)" class="tlf42qb4e"/></g><path fill="url(#icYO2he)" class="o2lsp2w0d"/><path fill="url(#iwM8bpA)" class="o2lsp2w0d"/><path fill="url(#iYXV7fc)" class="o2lsp2w0d"/><path fill="url(#i9MG8pJ)" class="o2lsp2w0d"/><g filter="url(#iGq0YPw)"><path stroke="url(#iP3jhFd)" class="h_18_9ahu"/></g><path fill="url(#iEDxs6d)" class="v7cfb5bbr"/><path fill="url(#inhHTPd)" class="v7cfb5bbr"/><path fill="url(#iVnjQUd)" class="v7cfb5bbr"/><path fill="url(#iEDxs6d)" class="v7cfb5bbr"/><path fill="url(#inhHTPd)" class="v7cfb5bbr"/><path fill="url(#iVnjQUd)" class="v7cfb5bbr"/><path fill="url(#ikVbZRb)" class="j4l55wfrs"/><g filter="url(#ihUnNQd)"><path fill="url(#iNEJO4d)" class="g_xbg78sz"/></g><g filter="url(#ivrtLjd)"><path stroke="url(#i9dFVSb)" class="jlaoni2le"/></g><g filter="url(#iICXoWc)"><rect fill="url(#iDvCOAe)" transform="rotate(33.34 21.809 3.067)" class="jmgk98bjr"/></g><path fill="url(#iWE2b4b)" class="kqwqr5brg"/><path fill="url(#i2HG7Bd)" class="kqwqr5brg"/><path fill="url(#i4nkqlc)" class="kqwqr5brg"/><path fill="url(#iRacE5d)" class="kqwqr5brg"/><path fill="url(#i01WWRc)" class="ge6yyzbum"/><path fill="url(#iXOSRmd)" class="ge6yyzbum"/><g filter="url(#itRwWxc)"><path fill="url(#ijbTBNc)" class="k265s_5hs"/><path fill="url(#iOSrE9d)" class="k265s_5hs"/></g><defs><linearGradient id="iViKTLd" x1="20.738" x2="20.738" y1="6.633" y2="17.258" gradientUnits="userSpaceOnUse"><stop offset=".158" class="wt_mbtbaj"/><stop offset="1" class="gd_h0d51j"/></linearGradient><linearGradient id="iqWod6c" x1="23.692" x2="23.192" y1="15.039" y2="15.039" gradientUnits="userSpaceOnUse"><stop class="wnn6rnbcj"/><stop offset="1" class="yos6dxbpk"/></linearGradient><linearGradient id="iaZ0uKe" x1="15.907" x2="15.907" y1="13.664" y2="29.352" gradientUnits="userSpaceOnUse"><stop class="ptcurt63y"/><stop offset="1" class="nlq_uledg"/></linearGradient><linearGradient id="ic2b0eb" x1="7.853" x2="16.942" y1="26.227" y2="26.227" gradientUnits="userSpaceOnUse"><stop class="qaxvm8x0l"/><stop offset="1" class="ry6zeta3b"/></linearGradient><linearGradient id="idhWwmb" x1="7.241" x2="9.058" y1="27.083" y2="27.394" gradientUnits="userSpaceOnUse"><stop class="m9n27-0bb"/><stop offset="1" class="muc9tzbwq"/></linearGradient><linearGradient id="iHwv9Sd" x1="10.973" x2="9.23" y1="2.355" y2="7.57" gradientUnits="userSpaceOnUse"><stop class="po3w25m7q"/><stop offset="1" class="aycri4bym"/></linearGradient><linearGradient id="iuwI7db" x1="11.215" x2="10.035" y1="7.602" y2="7.258" gradientUnits="userSpaceOnUse"><stop offset=".138" class="gb-qaryqk"/><stop offset="1" class="vkq51acjx"/></linearGradient><linearGradient id="i2xQyNe" x1="8.035" x2="8.692" y1="3.695" y2="4.523" gradientUnits="userSpaceOnUse"><stop class="o-dtq8bmx"/><stop offset="1" class="napw3jb9y"/></linearGradient><linearGradient id="icYO2he" x1="16.002" x2="16.002" y1="2.125" y2="8.539" gradientUnits="userSpaceOnUse"><stop class="qcq6f2bam"/><stop offset="1" class="b0i2aguye"/></linearGradient><linearGradient id="iwM8bpA" x1="11.192" x2="13.098" y1="12.289" y2="6.863" gradientUnits="userSpaceOnUse"><stop class="l_h3q8bgz"/><stop offset="1" class="rw4kpmb9x"/></linearGradient><linearGradient id="i9MG8pJ" x1="15.645" x2="15.66" y1="1.664" y2="2.445" gradientUnits="userSpaceOnUse"><stop class="r7jvq6bqh"/><stop offset="1" class="yakuvsbxs"/></linearGradient><linearGradient id="inhHTPd" x1="16.002" x2="16.002" y1="1.852" y2="2.914" gradientUnits="userSpaceOnUse"><stop class="zflo59pnd"/><stop offset="1" class="xlqnx-v9p"/></linearGradient><linearGradient id="ikVbZRb" x1="22.004" x2="22.973" y1="3.195" y2="7.758" gradientUnits="userSpaceOnUse"><stop class="edbromsyo"/><stop offset="1" class="uumd-6bmi"/></linearGradient><linearGradient id="iNEJO4d" x1="11.567" x2="21.973" y1="29.898" y2="29.898" gradientUnits="userSpaceOnUse"><stop class="pypw_c7sl"/><stop offset="1" class="fofddtbvg"/></linearGradient><linearGradient id="i9dFVSb" x1="20.882" x2="23.945" y1="13.008" y2="28.352" gradientUnits="userSpaceOnUse"><stop class="h7w2od9dd"/><stop offset="1" class="rzrmw7b2q"/></linearGradient><linearGradient id="iDvCOAe" x1="22.27" x2="25.094" y1="3.379" y2="3.242" gradientUnits="userSpaceOnUse"><stop class="d9qg1-egq"/><stop offset="1" class="mjsgjab4h"/></linearGradient><linearGradient id="iWE2b4b" x1="17.16" x2="14.785" y1="14.383" y2="9.508" gradientUnits="userSpaceOnUse"><stop class="zhegycger"/><stop offset=".919" class="sdqp2rb6w"/></linearGradient><linearGradient id="i4nkqlc" x1="20.535" x2="20.535" y1="1.852" y2="10.008" gradientUnits="userSpaceOnUse"><stop class="y5-9ccb1m"/><stop offset="1" class="c-37edb3m"/></linearGradient><linearGradient id="iRacE5d" x1="9.504" x2="11.098" y1="17.102" y2="17.383" gradientUnits="userSpaceOnUse"><stop class="mqjfi0afr"/><stop offset="1" class="u6raypbbk"/></linearGradient><linearGradient id="ijbTBNc" x1="22.059" x2="13.785" y1="2.695" y2="19.508" gradientUnits="userSpaceOnUse"><stop class="nkaqxzf-k"/><stop offset="1" class="mo07kebig"/></linearGradient><linearGradient id="iOSrE9d" x1="9.41" x2="15.556" y1="21.133" y2="14.539" gradientUnits="userSpaceOnUse"><stop class="js6hf0d9d"/><stop offset="1" class="btzeu68jv"/></linearGradient><radialGradient id="iAgKp6V" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.16406 .5625 0 23.504 16.008)" gradientUnits="userSpaceOnUse"><stop class="ufrvc7bgk"/><stop offset="1" class="okg-pnqec"/></radialGradient><radialGradient id="i6geKgc" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 0 0 1.01646 21.223 16.555)" gradientUnits="userSpaceOnUse"><stop class="uq-kwjbag"/><stop offset="1" class="wdygibbsb"/></radialGradient><radialGradient id="iZ3g62d" cx="0" cy="0" r="1" gradientTransform="rotate(144.966 7.84 9.66)scale(13.7394 13.3825)" gradientUnits="userSpaceOnUse"><stop class="lseetzbzp"/><stop offset="1" class="xnf5soydx"/></radialGradient><radialGradient id="iYXV7fc" cx="0" cy="0" r="1" gradientTransform="matrix(6.125 1.42187 -3.41514 14.7114 13.223 4.648)" gradientUnits="userSpaceOnUse"><stop offset=".752" class="q6fkwjf_n"/><stop offset=".905" class="cuy4wwbhu"/></radialGradient><radialGradient id="iP3jhFd" cx="0" cy="0" r="1" gradientTransform="matrix(.85938 -1.03125 1.80469 1.5039 13.848 4.383)" gradientUnits="userSpaceOnUse"><stop class="zw_x9tolp"/><stop offset="1" class="q2vl6vabq"/></radialGradient><radialGradient id="iEDxs6d" cx="0" cy="0" r="1" gradientTransform="matrix(1.21485 3.15625 -6.4512 2.48308 14.787 2.125)" gradientUnits="userSpaceOnUse"><stop class="xfwspiptv"/><stop offset="1" class="bbz2_qlhq"/></radialGradient><radialGradient id="iVnjQUd" cx="0" cy="0" r="1" gradientTransform="matrix(3.1875 2.01563 -2.11963 3.35197 15.145 2.523)" gradientUnits="userSpaceOnUse"><stop offset=".812" class="ciem70bqa"/><stop offset=".915" class="kuxd16b7f"/></radialGradient><radialGradient id="i2HG7Bd" cx="0" cy="0" r="1" gradientTransform="rotate(-58.82 22.574 .922)scale(8.51068 11.1097)" gradientUnits="userSpaceOnUse"><stop class="su1u610wi"/><stop offset="1" class="no2btkbrp"/></radialGradient><radialGradient id="i01WWRc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.78125 -3.6875 9.40603 -7.09439 18.223 8.258)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="d0jlu04gp"/><stop offset="1" class="uri3t9b2r"/></radialGradient><radialGradient id="iXOSRmd" cx="0" cy="0" r="1" gradientTransform="rotate(9.246 -13.158 114.479)scale(1.36144 3.03257)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="nufp_k9jo"/><stop offset="1" class="b_khxc7xy"/></radialGradient><filter id="iSF03mb" width="4.469" height="6.575" x="20.224" y="2.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16776" stdDeviation=".125"/></filter><filter id="i9jvmMd" width="5.506" height="1.1" x="17.973" y="15.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.619608 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16776"/></filter><filter id="iX9Q0gb" width="12.444" height="12.744" x="8.994" y="8.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16776" stdDeviation=".3"/></filter><filter id="iTUESee" width="4.119" height="6.394" x="7.246" y="2.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.219608 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16776"/></filter><filter id="iGq0YPw" width="5.924" height="3.556" x="13.04" y="1.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16776" stdDeviation=".05"/></filter><filter id="ihUnNQd" width="15.952" height=".947" x="7.873" y="28.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.521569 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16776"/></filter><filter id="ivrtLjd" width="3.788" height="17.134" x="20.276" y="11.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16776" stdDeviation=".15"/></filter><filter id="iICXoWc" width="3.72" height="2.968" x="21.122" y="2.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16776" stdDeviation=".25"/></filter><filter id="itRwWxc" width="13.007" height="18.838" x="9.052" y="2.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.611765 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16776"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sari" /></template>
<style>
.aycri4bym {
  stop-color: var(--svg-color--d94971, #D94971);
}

.b_khxc7xy {
  stop-color: var(--svg-color--d29c35, #D29C35);
  stop-opacity: 0;
}

.b0i2aguye {
  stop-color: var(--svg-color--e54c74, #E54C74);
}

.bbz2_qlhq {
  stop-color: var(--svg-color--a34c52, #A34C52);
}

.btzeu68jv {
  stop-color: var(--svg-color--ccb948, #CCB948);
  stop-opacity: 0;
}

.c-37edb3m {
  stop-color: var(--svg-color--34acf4, #34ACF4);
  stop-opacity: 0;
}

.ciem70bqa {
  stop-color: var(--svg-color--95312b, #95312B);
  stop-opacity: 0;
}

.cuy4wwbhu {
  stop-color: var(--svg-color--cb4637, #CB4637);
}

.d0jlu04gp {
  stop-color: var(--svg-color--f4cf4b, #F4CF4B);
}

.d9qg1-egq {
  stop-color: var(--svg-color--ff7f68, #FF7F68);
}

.edbromsyo {
  stop-color: var(--svg-color--ff6c60, #FF6C60);
}

.fexcm827x {
  fill-rule: evenodd;
  d: path("M23.48 16.055c-.117.57-.621 1-1.226 1h-4.281v-1z");
}

.fofddtbvg {
  stop-color: var(--svg-color--f7c44f, #F7C44F);
}

.ft5dv1b6b {
  fill: none;
}

.g_xbg78sz {
  d: path("M23.825 29.102a1.4 1.4 0 0 1-1.264.796H8.853a1 1 0 0 1-.98-.796z");
}

.gb-qaryqk {
  stop-color: var(--svg-color--ca4a4c, #CA4A4C);
}

.gd_h0d51j {
  stop-color: var(--svg-color--6bffab, #6BFFAB);
}

.ge6yyzbum {
  d: path("m10.466 12.723l7.362-4.955a5 5 0 0 0 2.207-4.148V2.102h-.666a.3.3 0 0 0-.3.3v1.284a3.75 3.75 0 0 1-1.611 3.081l-6.083 4.222a2 2 0 0 0-.828 1.286z");
}

.h_18_9ahu {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.24 2.075h-.05v.445a2.812 2.812 0 1 0 5.624 0v-.445z");
}

.h7w2od9dd {
  stop-color: var(--svg-color--56c0f6, #56C0F6);
}

.iuetbobya {
  fill: var(--svg-color--836ce0, #836CE0);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("m7.868 28.724l1.746-9.872l11.296-7.25l3.028 16.646a1.4 1.4 0 0 1-1.377 1.65H8.853a1 1 0 0 1-.985-1.174");
}

.j4l55wfrs {
  d: path("M21.988 2.785a4 4 0 0 0-.922-.426l-.281.383v4.75l1.491.861a.6.6 0 0 0 .823-.224l1.57-2.78a.654.654 0 0 0-.198-.859c-.919-.632-2.17-1.506-2.483-1.705");
}

.jlaoni2le {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m20.726 12.352l2.888 16.234");
}

.jmgk98bjr {
  width: 3.153px;
  height: 0.522px;
  x: 21.809px;
  y: 3.067px;
  rx: 0.261px;
}

.js6hf0d9d {
  stop-color: var(--svg-color--ccb948, #CCB948);
}

.jscaxfbci {
  d: path("m7.868 28.724l1.746-9.872l11.296-7.25l3.028 16.646a1.4 1.4 0 0 1-1.377 1.65H8.853a1 1 0 0 1-.985-1.174");
}

.k265s_5hs {
  d: path("m9.156 19.952l11.092-8.126a2 2 0 0 0 .819-1.614V2.218q.184.066.354.167l.272.162a.75.75 0 0 1 .366.644v7.401a2.25 2.25 0 0 1-.912 1.81L9.69 20.875a.4.4 0 0 1-.632-.393z");
}

.kqwqr5brg {
  d: path("M19.069 3.686V2.402a.3.3 0 0 1 .3-.3h1.026a2 2 0 0 1 1.026.283l.272.162a.75.75 0 0 1 .366.644v7.401a2.25 2.25 0 0 1-.912 1.81L9.69 20.875a.4.4 0 0 1-.632-.393l1.488-8.208a2 2 0 0 1 .828-1.286l6.082-4.222a3.75 3.75 0 0 0 1.612-3.08");
}

.kuxd16b7f {
  stop-color: var(--svg-color--95312b, #95312B);
}

.l_h3q8bgz {
  stop-color: var(--svg-color--cb2979, #CB2979);
}

.lseetzbzp {
  stop-color: var(--svg-color--49a9d9, #49A9D9);
}

.m9n27-0bb {
  stop-color: var(--svg-color--86cead, #86CEAD);
}

.mjsgjab4h {
  stop-color: var(--svg-color--ff7b85, #FF7B85);
}

.mo07kebig {
  stop-color: var(--svg-color--e7c93b, #E7C93B);
}

.mqjfi0afr {
  stop-color: var(--svg-color--77c6af, #77C6AF);
}

.muc9tzbwq {
  stop-color: var(--svg-color--86cead, #86CEAD);
  stop-opacity: 0;
}

.napw3jb9y {
  stop-color: var(--svg-color--e9766f, #E9766F);
  stop-opacity: 0;
}

.nkaqxzf-k {
  stop-color: var(--svg-color--feca52, #FECA52);
}

.nlq_uledg {
  stop-color: var(--svg-color--63eba8, #63EBA8);
}

.no2btkbrp {
  stop-color: var(--svg-color--4ec18d, #4EC18D);
  stop-opacity: 0;
}

.nufp_k9jo {
  stop-color: var(--svg-color--d29c35, #D29C35);
}

.o-dtq8bmx {
  stop-color: var(--svg-color--e9766f, #E9766F);
}

.o2lsp2w0d {
  d: path("M10.95 11.602V2.367c.196-.08.735-.242 1.314-.242h7.476c.58 0 1.118.161 1.315.242v9.235z");
}

.okg-pnqec {
  stop-color: var(--svg-color--65fca7, #65FCA7);
  stop-opacity: 0;
}

.po3w25m7q {
  stop-color: var(--svg-color--ec6a4c, #EC6A4C);
}

.ptcurt63y {
  stop-color: var(--svg-color--4fb7e8, #4FB7E8);
}

.pypw_c7sl {
  stop-color: var(--svg-color--ceb032, #CEB032);
}

.q2vl6vabq {
  stop-color: var(--svg-color--f2674f, #F2674F);
  stop-opacity: 0;
}

.q6fkwjf_n {
  stop-color: var(--svg-color--cb4637, #CB4637);
  stop-opacity: 0;
}

.qaxvm8x0l {
  stop-color: var(--svg-color--5dbba1, #5DBBA1);
}

.qcq6f2bam {
  stop-color: var(--svg-color--e5653f, #E5653F);
}

.r7jvq6bqh {
  stop-color: var(--svg-color--f78555, #F78555);
}

.rw4kpmb9x {
  stop-color: var(--svg-color--cb2979, #CB2979);
  stop-opacity: 0;
}

.ry6zeta3b {
  stop-color: var(--svg-color--5dbba1, #5DBBA1);
  stop-opacity: 0;
}

.rzrmw7b2q {
  stop-color: var(--svg-color--6fffb8, #6FFFB8);
}

.s90tzhfxo {
  fill: var(--svg-color--2f8aa6, #2F8AA6);
  d: path("M21.677 2.926a4 4 0 0 0-.922-.426l-.281.383v4.75l1.491.861a.6.6 0 0 0 .823-.224l1.57-2.78a.653.653 0 0 0-.199-.86c-.918-.63-2.169-1.505-2.482-1.703");
}

.sdqp2rb6w {
  stop-color: var(--svg-color--3fbbca, #3FBBCA);
}

.su1u610wi {
  stop-color: var(--svg-color--4ec18d, #4EC18D);
}

.tlf42qb4e {
  d: path("M10.012 2.8c.375-.237.86-.416.973-.445l.23.403v4.75l-1.491.861a.6.6 0 0 1-.822-.224L7.33 5.365a.653.653 0 0 1 .2-.86c.918-.63 2.169-1.505 2.482-1.703");
}

.u6raypbbk {
  stop-color: var(--svg-color--77c6af, #77C6AF);
  stop-opacity: 0;
}

.ufrvc7bgk {
  stop-color: var(--svg-color--65fca7, #65FCA7);
}

.uq-kwjbag {
  stop-color: var(--svg-color--ffdc4f, #FFDC4F);
}

.uri3t9b2r {
  stop-color: var(--svg-color--f0be3d, #F0BE3D);
}

.uumd-6bmi {
  stop-color: var(--svg-color--e63e7e, #E63E7E);
}

.v7cfb5bbr {
  d: path("M13.24 2.125v.395a2.762 2.762 0 1 0 5.524 0v-.395z");
}

.vkq51acjx {
  stop-color: var(--svg-color--ca4a4c, #CA4A4C);
  stop-opacity: 0;
}

.wd-1lzi5x {
  d: path("M17.973 6.633h5.531v9.172c0 .69-.56 1.25-1.25 1.25h-4.281z");
}

.wdygibbsb {
  stop-color: var(--svg-color--ffcd53, #FFCD53);
}

.wnn6rnbcj {
  stop-color: var(--svg-color--49c4e3, #49C4E3);
}

.wt_mbtbaj {
  stop-color: var(--svg-color--53c8da, #53C8DA);
}

.xfwspiptv {
  stop-color: var(--svg-color--bb5a4a, #BB5A4A);
}

.xlqnx-v9p {
  stop-color: var(--svg-color--ba594a, #BA594A);
  stop-opacity: 0;
}

.xnf5soydx {
  stop-color: var(--svg-color--2b877d, #2B877D);
}

.xo_16ykwd {
  d: path("M10.174 17.281c4.136-3.028 8.106-6.073 10.664-7.941v2.397a2.07 2.07 0 0 1-.84 1.665l-9.817 7.408a.368.368 0 0 1-.58-.362z");
}

.y5-9ccb1m {
  stop-color: var(--svg-color--34acf4, #34ACF4);
}

.yakuvsbxs {
  stop-color: var(--svg-color--f78555, #F78555);
  stop-opacity: 0;
}

.yos6dxbpk {
  stop-color: var(--svg-color--49c4e3, #49C4E3);
  stop-opacity: 0;
}

.zflo59pnd {
  stop-color: var(--svg-color--ce6741, #CE6741);
}

.zhegycger {
  stop-color: var(--svg-color--52d3bf, #52D3BF);
}

.zw_x9tolp {
  stop-color: var(--svg-color--f2674f, #F2674F);
}

</style>
