<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ityapKb)"><rect fill="url(#iqNhbde)" class="tesxadbvw"/></g><rect fill="url(#iqHTnlc)" class="tesxadbvw"/><g filter="url(#iGje3id)"><rect fill="url(#isBD8rd)" class="bl4kqeofd"/></g><g filter="url(#iTVRmxX)"><rect fill="url(#icHT8Dd)" class="a0si_xbbw"/></g><g filter="url(#iAbvD8c)"><path fill="url(#ioQLfoe)" class="n84q3bl-h"/></g><g filter="url(#ilmnyqe)"><path clip-rule="evenodd" class="x1tw_1bfp"/></g><path fill="url(#iO7UtRt)" clip-rule="evenodd" class="t8xhw9bko"/><path fill="url(#iuDkQOe)" clip-rule="evenodd" class="t8xhw9bko"/><path fill="url(#itMMSHd)" clip-rule="evenodd" class="t8xhw9bko"/><path fill="url(#iSoRUjy)" class="u2v3-5bog"/><path fill="url(#ihVuCEb)" class="u2v3-5bog"/><path fill="url(#ippuJRc)" class="u2v3-5bog"/><path fill="url(#izqm8zH)" class="u2v3-5bog"/><g filter="url(#iOaIlje)"><path fill="url(#i6l9tsd)" clip-rule="evenodd" class="lank04b8g"/></g><path fill="url(#iflbHFc)" class="wyt7ijbnx"/><path fill="url(#izNY0de)" class="wyt7ijbnx"/><path fill="url(#ilLqKrb)" class="wyt7ijbnx"/><path fill="url(#iot8xyR)" class="wyt7ijbnx"/><path fill="url(#iL1dlge)" class="wyt7ijbnx"/><path fill="url(#iacjeke)" class="wyt7ijbnx"/><path fill="url(#ioXfFOb)" class="wyt7ijbnx"/><path fill="url(#iLK8Vwe)" class="wyt7ijbnx"/><path fill="url(#idt177b)" class="wyt7ijbnx"/><g filter="url(#iG0MLde)"><path fill="url(#ih0yJXb)" class="chypklbbn"/></g><path fill="url(#ipLKMnU)" class="chypklbbn"/><g filter="url(#idhWzQc)"><path fill="url(#i7rz7Ro)" class="gqovb1bii"/></g><path fill="url(#iki3zOd)" class="gqovb1bii"/><g filter="url(#iuWMItd)"><circle fill="url(#iUZ8f2d)" class="xav90ddiz"/><circle fill="url(#i3oKe6b)" class="xav90ddiz"/></g><g filter="url(#iErAiPb)"><circle fill="url(#iWnPYjO)" class="zhqbmrjfs"/><circle fill="url(#izbz8QY)" class="zhqbmrjfs"/></g><path fill="url(#iw6qAzc)" class="wayre8bkf"/><path fill="url(#ixIG8zb)" class="ey65kibwz"/><path fill="url(#iBWDFWd)" class="ey65kibwz"/><path fill="url(#ioDAWdd)" clip-rule="evenodd" class="yp8ys1b9u"/><defs><linearGradient id="iqNhbde" x1="2.074" x2="29.922" y1="18.659" y2="18.659" gradientUnits="userSpaceOnUse"><stop class="p8fwgdb0u"/><stop offset="1" class="rr16fpbgs"/><stop offset="1" class="vdse234up"/></linearGradient><linearGradient id="iqHTnlc" x1="2.078" x2="4.586" y1="18.651" y2="18.651" gradientUnits="userSpaceOnUse"><stop class="u6268j_0k"/><stop offset="1" class="qhrekkrzr"/></linearGradient><linearGradient id="isBD8rd" x1="29.802" x2="22.961" y1="12.191" y2="18.302" gradientUnits="userSpaceOnUse"><stop class="ld4ysgprz"/><stop offset="1" class="u18dzg8_w"/></linearGradient><linearGradient id="icHT8Dd" x1="22.829" x2="15.988" y1="12.191" y2="18.302" gradientUnits="userSpaceOnUse"><stop class="ld4ysgprz"/><stop offset="1" class="u18dzg8_w"/></linearGradient><linearGradient id="ioQLfoe" x1="15.685" x2="8.843" y1="12.191" y2="18.302" gradientUnits="userSpaceOnUse"><stop class="ld4ysgprz"/><stop offset="1" class="u18dzg8_w"/></linearGradient><linearGradient id="iO7UtRt" x1="20.902" x2="19.828" y1="6.143" y2="6.455" gradientUnits="userSpaceOnUse"><stop class="x6ns7e5cu"/><stop offset="1" class="m-91dsbil"/></linearGradient><linearGradient id="iSoRUjy" x1="16.426" x2="16.426" y1="9.424" y2="11.815" gradientUnits="userSpaceOnUse"><stop class="j7twcjyjp"/><stop offset="1" class="gliduvryi"/></linearGradient><linearGradient id="ihVuCEb" x1="16.426" x2="16.426" y1="9.424" y2="9.983" gradientUnits="userSpaceOnUse"><stop class="mtn-ihv0n"/><stop offset="1" class="m5877q0-c"/></linearGradient><linearGradient id="ippuJRc" x1="12.703" x2="13.862" y1="11.408" y2="11.408" gradientUnits="userSpaceOnUse"><stop class="c-06avbju"/><stop offset="1" class="b6zktte5u"/></linearGradient><linearGradient id="izqm8zH" x1="19.934" x2="18.948" y1="11.408" y2="11.408" gradientUnits="userSpaceOnUse"><stop class="f4nqddcov"/><stop offset="1" class="tup94ybgy"/></linearGradient><linearGradient id="i6l9tsd" x1="2.531" x2="7.264" y1="18.384" y2="13.394" gradientUnits="userSpaceOnUse"><stop class="mplbu6vqz"/><stop offset="1" class="c409rkvsv"/></linearGradient><linearGradient id="iflbHFc" x1="2.955" x2="29.922" y1="24.883" y2="24.883" gradientUnits="userSpaceOnUse"><stop class="nh-ewrrzr"/><stop offset="1" class="qcny7x58q"/></linearGradient><linearGradient id="izNY0de" x1="2.078" x2="4.366" y1="27.268" y2="27.268" gradientUnits="userSpaceOnUse"><stop offset=".209" class="guzoaobsj"/><stop offset="1" class="r0eiy7f4g"/></linearGradient><linearGradient id="ilLqKrb" x1="29.922" x2="28.152" y1="27.268" y2="27.268" gradientUnits="userSpaceOnUse"><stop class="qv0vatbjj"/><stop offset="1" class="exqx96dio"/></linearGradient><linearGradient id="iot8xyR" x1="16" x2="16" y1="27.913" y2="23.801" gradientUnits="userSpaceOnUse"><stop class="ikgfrupop"/><stop offset="1" class="plqvv8b4c"/></linearGradient><linearGradient id="iL1dlge" x1="16" x2="16" y1="27.268" y2="27.002" gradientUnits="userSpaceOnUse"><stop class="y_231ubxt"/><stop offset="1" class="wadhz0bvv"/></linearGradient><linearGradient id="ih0yJXb" x1="26.968" x2="20.226" y1="26.931" y2="26.931" gradientUnits="userSpaceOnUse"><stop class="gdli92r2w"/><stop offset="1" class="xc9e4-4zl"/></linearGradient><linearGradient id="i7rz7Ro" x1="11.906" x2="5.164" y1="26.931" y2="26.931" gradientUnits="userSpaceOnUse"><stop class="gdli92r2w"/><stop offset="1" class="xc9e4-4zl"/></linearGradient><linearGradient id="iw6qAzc" x1="2.078" x2="29.922" y1="21.33" y2="21.33" gradientUnits="userSpaceOnUse"><stop offset=".03" class="adurvjzae"/><stop offset=".081" class="q4tx8lbnv"/><stop offset=".724" class="d2-7io-uz"/><stop offset="1" class="two1tm09f"/></linearGradient><linearGradient id="iBWDFWd" x1="29.922" x2="29.412" y1="23.833" y2="23.833" gradientUnits="userSpaceOnUse"><stop class="fi2pmhb-d"/><stop offset="1" class="ifzta6brl"/></linearGradient><linearGradient id="ioDAWdd" x1="1.901" x2="2.782" y1="22.391" y2="24.538" gradientUnits="userSpaceOnUse"><stop class="qpmhxkbyp"/><stop offset="1" class="kpkyj_ogw"/></linearGradient><radialGradient id="iuDkQOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.82463 1.08146 -.78198 -.59627 20.15 7.628)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="a8tgm138s"/><stop offset="1" class="g8cx95xfx"/></radialGradient><radialGradient id="itMMSHd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2126 -.7087 1.11312 -.33393 17.637 9.466)" gradientUnits="userSpaceOnUse"><stop class="vjb53v90y"/><stop offset="1" class="onqg_j3uv"/></radialGradient><radialGradient id="iacjeke" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.93075 4.42749 0 23.563 26.692)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="mhj_tfgos"/><stop offset="1" class="pj-hs_b9k"/></radialGradient><radialGradient id="ioXfFOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.80023 3.96085 0 8.546 27.268)" gradientUnits="userSpaceOnUse"><stop offset=".809" class="mhj_tfgos"/><stop offset="1" class="pj-hs_b9k"/></radialGradient><radialGradient id="iLK8Vwe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.04537 2.10926 -1.00762 -.9771 21.557 26.15)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="xj94qccwd"/><stop offset="1" class="iouknebtq"/></radialGradient><radialGradient id="idt177b" cx="0" cy="0" r="1" gradientTransform="rotate(146.725 -.307 13.872)scale(3.66969 1.75307)" gradientUnits="userSpaceOnUse"><stop offset=".291" class="xj94qccwd"/><stop offset="1" class="iouknebtq"/></radialGradient><radialGradient id="ipLKMnU" cx="0" cy="0" r="1" gradientTransform="rotate(90 -.198 23.795)scale(6.30592)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="tkb-y5c2n"/><stop offset="1" class="oya09dh9o"/></radialGradient><radialGradient id="iki3zOd" cx="0" cy="0" r="1" gradientTransform="rotate(90 -7.729 16.264)scale(6.30592)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="tkb-y5c2n"/><stop offset="1" class="oya09dh9o"/></radialGradient><radialGradient id="iUZ8f2d" cx="0" cy="0" r="1" gradientTransform="rotate(129.657 5.876 18.928)scale(1.84354 1.59884)" gradientUnits="userSpaceOnUse"><stop class="uy-elybtc"/><stop offset=".8" class="je7vqqg0r"/></radialGradient><radialGradient id="i3oKe6b" cx="0" cy="0" r="1" gradientTransform="rotate(-52.312 40.046 -9.25)scale(1.16909 2.40657)" gradientUnits="userSpaceOnUse"><stop class="fdomx0bpj"/><stop offset="1" class="li9m4eegn"/></radialGradient><radialGradient id="iWnPYjO" cx="0" cy="0" r="1" gradientTransform="rotate(129.657 -1.655 15.388)scale(1.84354 1.59884)" gradientUnits="userSpaceOnUse"><stop class="uy-elybtc"/><stop offset=".8" class="je7vqqg0r"/></radialGradient><radialGradient id="izbz8QY" cx="0" cy="0" r="1" gradientTransform="rotate(-52.312 32.514 6.086)scale(1.16909 2.40657)" gradientUnits="userSpaceOnUse"><stop class="fdomx0bpj"/><stop offset="1" class="li9m4eegn"/></radialGradient><radialGradient id="ixIG8zb" cx="0" cy="0" r="1" gradientTransform="matrix(1.20864 -1.23383 1.22193 1.19698 28.341 24.236)" gradientUnits="userSpaceOnUse"><stop class="dt33h99jv"/><stop offset="1" class="ab7k6mzuf"/></radialGradient><filter id="ityapKb" width="29.644" height="16.459" x="1.078" y="11.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.964706 0 0 0 0 0.988235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9941"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".8" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.54902 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9941" result="effect2_innerShadow_18_9941"/></filter><filter id="iGje3id" width="5.922" height="5.672" x="21.973" y="13.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.654902 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9941"/></filter><filter id="iTVRmxX" width="5.922" height="5.672" x="15" y="13.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.654902 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9941"/></filter><filter id="iAbvD8c" width="5.922" height="5.672" x="8.027" y="13.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.654902 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9941"/></filter><filter id="ilmnyqe" width="5.229" height="5.139" x="15.773" y="5.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.541176 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9941"/></filter><filter id="iOaIlje" width="5.84" height="5.99" x="1.078" y="13.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.5" dy="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.647059 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9941"/></filter><filter id="iG0MLde" width="7.734" height="6.734" x="19.73" y="23.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.117647 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9941"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.235294 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9941" result="effect2_innerShadow_18_9941"/></filter><filter id="idhWzQc" width="7.734" height="6.734" x="4.668" y="23.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.117647 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9941"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.235294 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9941" result="effect2_innerShadow_18_9941"/></filter><filter id="iuWMItd" width="3.128" height="3.128" x="21.834" y="25.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.129412 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_9941"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_9941" result="shape"/></filter><filter id="iErAiPb" width="3.128" height="3.128" x="6.771" y="25.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.129412 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_9941"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_9941" result="shape"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:trolleybus" /></template>
<style>
.a0si_xbbw {
  width: 4.922px;
  height: 4.922px;
  x: 16px;
  y: 13.394px;
  rx: 1.2px;
}

.a8tgm138s {
  stop-color: var(--svg-color--cbb2e0, #CBB2E0);
}

.ab7k6mzuf {
  stop-color: var(--svg-color--d50860, #D50860);
}

.adurvjzae {
  stop-color: var(--svg-color--3961d9, #3961D9);
}

.b6zktte5u {
  stop-color: var(--svg-color--868488, #868488);
  stop-opacity: 0;
}

.bl4kqeofd {
  width: 4.922px;
  height: 4.922px;
  x: 22.973px;
  y: 13.394px;
  rx: 1.2px;
}

.c-06avbju {
  stop-color: var(--svg-color--868488, #868488);
}

.c409rkvsv {
  stop-color: var(--svg-color--50baff, #50BAFF);
}

.chypklbbn {
  d: path("M23.598 30.299a3.367 3.367 0 1 0 0-6.734a3.367 3.367 0 0 0 0 6.734");
}

.d2-7io-uz {
  stop-color: var(--svg-color--71b4ff, #71B4FF);
}

.dt33h99jv {
  stop-color: var(--svg-color--fb2841, #FB2841);
}

.exqx96dio {
  stop-color: var(--svg-color--83ffa1, #83FFA1);
  stop-opacity: 0;
}

.ey65kibwz {
  d: path("M29.922 22.33v2.047h-1.027a1 1 0 0 1-1-1v-.047a1 1 0 0 1 1-1z");
}

.f4nqddcov {
  stop-color: var(--svg-color--fbf7fe, #FBF7FE);
}

.fdomx0bpj {
  stop-color: var(--svg-color--e0c7f5, #E0C7F5);
}

.fi2pmhb-d {
  stop-color: var(--svg-color--db217d, #DB217D);
}

.ft5dv1b6b {
  fill: none;
}

.g8cx95xfx {
  stop-color: var(--svg-color--cbb2e0, #CBB2E0);
  stop-opacity: 0;
}

.gdli92r2w {
  stop-color: var(--svg-color--502d79, #502D79);
}

.gliduvryi {
  stop-color: var(--svg-color--d4d0d9, #D4D0D9);
}

.gqovb1bii {
  d: path("M8.535 30.299a3.367 3.367 0 1 0 0-6.734a3.367 3.367 0 0 0 0 6.734");
}

.guzoaobsj {
  stop-color: var(--svg-color--4a7e57, #4A7E57);
}

.ifzta6brl {
  stop-color: var(--svg-color--db217d, #DB217D);
  stop-opacity: 0;
}

.ikgfrupop {
  stop-color: var(--svg-color--84afe5, #84AFE5);
}

.iouknebtq {
  stop-color: var(--svg-color--467a7a, #467A7A);
  stop-opacity: 0;
}

.j7twcjyjp {
  stop-color: var(--svg-color--e5d9f1, #E5D9F1);
}

.je7vqqg0r {
  stop-color: var(--svg-color--cabfd4, #CABFD4);
}

.kpkyj_ogw {
  stop-color: var(--svg-color--c6891e, #C6891E);
}

.lank04b8g {
  fill-rule: evenodd;
  d: path("M2.131 13.394a2.5 2.5 0 0 0-.053.514v4.476h3.74c.61 0 1.1-.49 1.1-1.1v-2.79c0-.61-.49-1.1-1.1-1.1z");
}

.ld4ysgprz {
  stop-color: var(--svg-color--46b2ff, #46B2FF);
}

.li9m4eegn {
  stop-color: var(--svg-color--e0c7f5, #E0C7F5);
  stop-opacity: 0;
}

.m-91dsbil {
  stop-color: var(--svg-color--fdf9ff, #FDF9FF);
  stop-opacity: 0;
}

.m5877q0-c {
  stop-color: var(--svg-color--c5c2c9, #C5C2C9);
  stop-opacity: 0;
}

.mhj_tfgos {
  stop-color: var(--svg-color--54c87a, #54C87A);
}

.mplbu6vqz {
  stop-color: var(--svg-color--4fd2ff, #4FD2FF);
}

.mtn-ihv0n {
  stop-color: var(--svg-color--c5c2c9, #C5C2C9);
}

.n84q3bl-h {
  d: path("M9.027 14.594a1.2 1.2 0 0 1 1.2-1.2h2.522a1.2 1.2 0 0 1 1.2 1.2v2.522a1.2 1.2 0 0 1-1.2 1.2h-2.522a1.2 1.2 0 0 1-1.2-1.2z");
}

.nh-ewrrzr {
  stop-color: var(--svg-color--62be87, #62BE87);
}

.onqg_j3uv {
  stop-color: var(--svg-color--eae7f0, #EAE7F0);
  stop-opacity: 0;
}

.oya09dh9o {
  stop-color: var(--svg-color--632d88, #632D88);
}

.p8fwgdb0u {
  stop-color: var(--svg-color--eaceff, #EACEFF);
}

.pj-hs_b9k {
  stop-color: var(--svg-color--54c87a, #54C87A);
  stop-opacity: 0;
}

.plqvv8b4c {
  stop-color: var(--svg-color--84afe5, #84AFE5);
  stop-opacity: 0;
}

.q4tx8lbnv {
  stop-color: var(--svg-color--5a84ff, #5A84FF);
}

.qcny7x58q {
  stop-color: var(--svg-color--6ef199, #6EF199);
}

.qhrekkrzr {
  stop-color: var(--svg-color--a490b5, #A490B5);
  stop-opacity: 0;
}

.qpmhxkbyp {
  stop-color: var(--svg-color--fa963e, #FA963E);
}

.qv0vatbjj {
  stop-color: var(--svg-color--83ffa1, #83FFA1);
}

.r0eiy7f4g {
  stop-color: var(--svg-color--4a7e57, #4A7E57);
  stop-opacity: 0;
}

.rr16fpbgs {
  stop-color: var(--svg-color--ddd3e4, #DDD3E4);
}

.t8xhw9bko {
  fill-rule: evenodd;
  d: path("M20.896 6.378a.75.75 0 0 1-.643.844c-.6.081-2.371.69-3.006 2.995a.75.75 0 0 1-1.447-.399c.84-3.045 3.242-3.945 4.251-4.083a.75.75 0 0 1 .845.643");
}

.tesxadbvw {
  width: 27.844px;
  height: 15.859px;
  x: 2.078px;
  y: 11.408px;
  rx: 2.5px;
}

.tkb-y5c2n {
  stop-color: var(--svg-color--632d88, #632D88);
  stop-opacity: 0;
}

.tup94ybgy {
  stop-color: var(--svg-color--fbf7fe, #FBF7FE);
  stop-opacity: 0;
}

.two1tm09f {
  stop-color: var(--svg-color--79d1ff, #79D1FF);
}

.u18dzg8_w {
  stop-color: var(--svg-color--4cddff, #4CDDFF);
}

.u2v3-5bog {
  d: path("M12.918 10.424a1 1 0 0 1 1-1h5.016a1 1 0 0 1 1 1v.984h-7.016z");
}

.u6268j_0k {
  stop-color: var(--svg-color--938d98, #938D98);
}

.uy-elybtc {
  stop-color: var(--svg-color--e8e4ef, #E8E4EF);
}

.vdse234up {
  stop-color: var(--svg-color--f2d5ff, #F2D5FF);
}

.vjb53v90y {
  stop-color: var(--svg-color--eae7f0, #EAE7F0);
}

.wadhz0bvv {
  stop-color: var(--svg-color--aea9fc, #AEA9FC);
  stop-opacity: 0;
}

.wayre8bkf {
  d: path("M2.078 21.33v-1.992h27.844v1.992z");
}

.wyt7ijbnx {
  d: path("M29.922 20.334v4.434a2.5 2.5 0 0 1-2.5 2.5H4.578a2.5 2.5 0 0 1-2.5-2.5v-4.434z");
}

.x1tw_1bfp {
  fill: var(--svg-color--e4d3f6, #E4D3F6);
  fill-rule: evenodd;
  d: path("M20.896 6.378a.75.75 0 0 1-.643.844c-.6.081-2.371.69-3.006 2.995a.75.75 0 0 1-1.447-.399c.84-3.045 3.242-3.945 4.251-4.083a.75.75 0 0 1 .845.643");
}

.x6ns7e5cu {
  stop-color: var(--svg-color--fdf9ff, #FDF9FF);
}

.xav90ddiz {
  cx: 23.598px;
  cy: 26.932px;
  r: 1.164px;
}

.xc9e4-4zl {
  stop-color: var(--svg-color--53307d, #53307D);
}

.xj94qccwd {
  stop-color: var(--svg-color--467a7a, #467A7A);
}

.y_231ubxt {
  stop-color: var(--svg-color--aea9fc, #AEA9FC);
}

.yp8ys1b9u {
  fill-rule: evenodd;
  d: path("M2.078 22.399a.81.81 0 0 1 .922.8v1.323a.81.81 0 0 1-.859.807a2.5 2.5 0 0 1-.063-.561z");
}

.zhqbmrjfs {
  cx: 8.535px;
  cy: 26.932px;
  r: 1.164px;
}

</style>
