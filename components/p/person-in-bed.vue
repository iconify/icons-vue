<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iFCjYDb" class="wjxfwib9z"/></defs><g class="ft5dv1b6b"><path fill="url(#isL7gwc)" class="jddm9tctr"/><path fill="url(#izoXaNe)" class="jddm9tctr"/><path fill="url(#iJxIRqd)" class="mmf83abgd"/><path fill="url(#iWhRu4b)" class="mmf83abgd"/><path fill="url(#iC2kHcc)" class="b5feq2trt"/><path fill="url(#ibGZYEe)" class="b5feq2trt"/><path fill="url(#iDqZRFd)" class="b5feq2trt"/><path fill="url(#i2YVihb)" class="b5feq2trt"/><path fill="url(#iLZLVBb)" class="b5feq2trt"/><g filter="url(#ixFZFWk)"><path fill="url(#iwU2Fmc)" class="by3ainbne"/><path fill="url(#iuMDS5b)" class="by3ainbne"/></g><g filter="url(#iHJy7td)"><path class="eunxegb_m"/><path fill="url(#i3Zy4Zc)" class="j5-4bzb_q"/></g><path fill="url(#irqIBHc)" class="bthh05_yc"/><path fill="url(#iyOKeWz)" class="bthh05_yc"/><g filter="url(#inBXmMb)"><path class="oydooacgz"/></g><g filter="url(#iksmSIc)"><path class="krsb9vstl"/></g><path fill="url(#ijHWFqc)" class="mz-tmnbha"/><path fill="url(#iZAqkAe)" class="mz-tmnbha"/><path fill="url(#irMNDvd)" class="mz-tmnbha"/><path fill="url(#iwKRTOe)" class="mz-tmnbha"/><path fill="url(#it0p1Nb)" class="mz-tmnbha"/><path fill="url(#iZXJxNc)" class="mz-tmnbha"/><g filter="url(#iMEKVTV)"><path fill="url(#is3Y98N)" class="ezijx-2ny"/></g><path fill="url(#igmboBn)" class="h512dubmk"/><g filter="url(#iBKuQWd)"><path fill="url(#ipiUDyc)" class="hk15obc3x"/><path fill="url(#idm7WGb)" class="hk15obc3x"/></g><g filter="url(#i5bLbpb)"><use href="#iFCjYDb"/><path fill="url(#ilkobrb)" class="ti0324qcb"/><path fill="url(#ibYWLOv)" class="ti0324qcb"/><path fill="url(#iY8xmee)" class="ti0324qcb"/><path fill="url(#iey4Tsb)" class="ti0324qcb"/><path fill="url(#idpPgKe)" class="ti0324qcb"/></g><g filter="url(#i1OLRHe)"><use href="#iFCjYDb"/><path fill="url(#ilkobrb)" class="ti0324qcb"/><path fill="url(#ibYWLOv)" class="ti0324qcb"/><path fill="url(#iY8xmee)" class="ti0324qcb"/><path fill="url(#iey4Tsb)" class="ti0324qcb"/><path fill="url(#idpPgKe)" class="ti0324qcb"/></g><path fill="url(#iLDOrCe)" class="o8jz8mb4l"/><path clip-rule="evenodd" class="rnq8-kbby"/><g filter="url(#iMCyG3c)"><path clip-rule="evenodd" class="xlbqkwbxp"/></g><g filter="url(#iux5bmd)"><path class="et566ebvf"/></g><g filter="url(#ikN3FRb)"><path class="yj7_fabwq"/></g><defs><linearGradient id="isL7gwc" x1="5.919" x2="5.919" y1="27.454" y2="29.142" gradientUnits="userSpaceOnUse"><stop class="jp856yt_g"/><stop offset="1" class="we894y8xm"/></linearGradient><linearGradient id="izoXaNe" x1="4.181" x2="4.642" y1="29.509" y2="29.509" gradientUnits="userSpaceOnUse"><stop class="kun3pubeg"/><stop offset="1" class="onfzp-bwy"/></linearGradient><linearGradient id="iJxIRqd" x1="26.818" x2="26.818" y1="27.454" y2="29.142" gradientUnits="userSpaceOnUse"><stop class="jp856yt_g"/><stop offset="1" class="yudqmabvt"/></linearGradient><linearGradient id="iWhRu4b" x1="25.052" x2="25.52" y1="29.509" y2="29.509" gradientUnits="userSpaceOnUse"><stop class="kun3pubeg"/><stop offset="1" class="onfzp-bwy"/></linearGradient><linearGradient id="iC2kHcc" x1="14.33" x2="16.353" y1="21.111" y2="26.361" gradientUnits="userSpaceOnUse"><stop class="s50shpiqt"/><stop offset="1" class="ctq4_rb_x"/></linearGradient><linearGradient id="ibGZYEe" x1="2.439" x2="4.189" y1="26.236" y2="26.236" gradientUnits="userSpaceOnUse"><stop offset=".205" class="xxaw6lbdd"/><stop offset="1" class="znfsawb6t"/></linearGradient><linearGradient id="iDqZRFd" x1="30.267" x2="28.861" y1="25.986" y2="25.986" gradientUnits="userSpaceOnUse"><stop offset=".089" class="dzbbssbmi"/><stop offset="1" class="ihb5mw0qq"/></linearGradient><linearGradient id="i2YVihb" x1="18.58" x2="18.58" y1="27.826" y2="27.548" gradientUnits="userSpaceOnUse"><stop class="bw9bhgcag"/><stop offset="1" class="yylhrtbwl"/></linearGradient><linearGradient id="iLZLVBb" x1="16.353" x2="16.353" y1="20.704" y2="20.907" gradientUnits="userSpaceOnUse"><stop class="yonqiacdw"/><stop offset="1" class="u7ukf0cyw"/></linearGradient><linearGradient id="iwU2Fmc" x1="11.486" x2="5.58" y1="19.954" y2="19.954" gradientUnits="userSpaceOnUse"><stop class="j_iqhtv2z"/><stop offset="1" class="lfx99ibod"/></linearGradient><linearGradient id="iuMDS5b" x1="11.705" x2="10.173" y1="20.298" y2="20.298" gradientUnits="userSpaceOnUse"><stop class="erd70ybna"/><stop offset="1" class="xrdg6g6_d"/></linearGradient><linearGradient id="i3Zy4Zc" x1="11.611" x2="9.955" y1="16.673" y2="16.673" gradientUnits="userSpaceOnUse"><stop offset=".057" class="qpqpigz0q"/><stop offset="1" class="nw5hewkux"/></linearGradient><linearGradient id="irqIBHc" x1="5.361" x2="2.439" y1="20.704" y2="20.704" gradientUnits="userSpaceOnUse"><stop offset=".193" class="tmk_n7bre"/><stop offset="1" class="kgz9t0b5t"/></linearGradient><linearGradient id="iyOKeWz" x1="5.548" x2="4.486" y1="20.704" y2="20.704" gradientUnits="userSpaceOnUse"><stop class="zq06kkbop"/><stop offset="1" class="atnucacjf"/></linearGradient><linearGradient id="ijHWFqc" x1="12.267" x2="29.142" y1="18.361" y2="18.361" gradientUnits="userSpaceOnUse"><stop class="oesdu5b_i"/><stop offset="1" class="yeuw1mqbz"/></linearGradient><linearGradient id="iZAqkAe" x1="11.455" x2="12.767" y1="21.017" y2="21.017" gradientUnits="userSpaceOnUse"><stop class="yx0c6y8nw"/><stop offset="1" class="fl_2tebol"/></linearGradient><linearGradient id="irMNDvd" x1="23.392" x2="23.392" y1="21.978" y2="21.54" gradientUnits="userSpaceOnUse"><stop class="kbcj9odgo"/><stop offset="1" class="gmid2kucu"/></linearGradient><linearGradient id="iwKRTOe" x1="11.275" x2="11.744" y1="18.361" y2="18.361" gradientUnits="userSpaceOnUse"><stop class="z7g_zwxuh"/><stop offset="1" class="fu6a58b1y"/></linearGradient><linearGradient id="it0p1Nb" x1="20.861" x2="20.861" y1="12.361" y2="13.548" gradientUnits="userSpaceOnUse"><stop class="gr6t18twh"/><stop offset="1" class="s8sy2oshg"/></linearGradient><linearGradient id="ipiUDyc" x1="10.382" x2="12.425" y1="12.949" y2="10.513" gradientUnits="userSpaceOnUse"><stop class="m1kxp_byq"/><stop offset="1" class="p6fb0tb2m"/></linearGradient><radialGradient id="iZXJxNc" cx="0" cy="0" r="1" gradientTransform="rotate(125.151 11.972 14.136)scale(6.45916 9.77416)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="tejv_ybih"/><stop offset="1" class="cf8m5rrfx"/></radialGradient><radialGradient id="is3Y98N" cx="0" cy="0" r="1" gradientTransform="matrix(-9.2187 9.56259 -16.93759 -16.32847 30.017 13.767)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="ffbkz6xwn"/><stop offset="1" class="w-2pnubhf"/></radialGradient><radialGradient id="igmboBn" cx="0" cy="0" r="1" gradientTransform="rotate(63.839 -1.803 14.74)scale(.75481 .9613)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="idm7WGb" cx="0" cy="0" r="1" gradientTransform="matrix(.51543 -.78235 .95266 .62763 9.516 12.738)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="ilkobrb" cx="0" cy="0" r="1" gradientTransform="rotate(172.015 4.744 7.422)scale(3.016 4.40766)" gradientUnits="userSpaceOnUse"><stop class="re8izvbqw"/><stop offset="1" class="kgio6d1ee"/></radialGradient><radialGradient id="ibYWLOv" cx="0" cy="0" r="1" gradientTransform="matrix(2.19532 -1.30518 3.42952 5.7685 6.287 12.953)" gradientUnits="userSpaceOnUse"><stop class="y125gvbnz"/><stop offset="1" class="ldg9ygbfk"/></radialGradient><radialGradient id="iY8xmee" cx="0" cy="0" r="1" gradientTransform="matrix(1.47833 -1.3839 .63822 .68177 6.156 10.602)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="t5jak8x3h"/><stop offset="1" class="hze7fms1a"/></radialGradient><radialGradient id="iey4Tsb" cx="0" cy="0" r="1" gradientTransform="rotate(83.407 -.46 8.466)scale(.77164 1.11431)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="an20q5kfx"/><stop offset="1" class="xh4g4qbuv"/></radialGradient><radialGradient id="idpPgKe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.13293 -.54848 .24992 -.97191 8.474 14.962)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="pw1txj0qv"/><stop offset="1" class="s9yijwaob"/></radialGradient><radialGradient id="iLDOrCe" cx="0" cy="0" r="1" gradientTransform="matrix(1.13656 .21728 -.35334 1.84829 9.155 12.89)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><filter id="ixFZFWk" width="8.313" height="3.734" x="5.361" y="16.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.376471 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_35"/></filter><filter id="iHJy7td" width="8.313" height="3.734" x="5.361" y="13.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.266667 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_35"/></filter><filter id="inBXmMb" width="19.127" height="9.563" x="11.265" y="13.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_35" stdDeviation=".25"/></filter><filter id="iksmSIc" width="8.547" height="8.868" x="5.618" y="8.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_35" stdDeviation=".5"/></filter><filter id="iMEKVTV" width="18.738" height="9.363" x="11.58" y="12.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_35" stdDeviation=".375"/></filter><filter id="iBKuQWd" width="6.948" height="5.784" x="7.074" y="8.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.533333 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_35"/></filter><filter id="i5bLbpb" width="5.052" height="7.57" x="5.55" y="7.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_35"/></filter><filter id="i1OLRHe" width="5.552" height="7.67" x="5.55" y="8.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.52549 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_35"/></filter><filter id="iMCyG3c" width=".691" height="1.087" x="9.571" y="9.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_35"/></filter><filter id="iux5bmd" width=".929" height="1.118" x="10.505" y="9.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.172549 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_35"/></filter><filter id="ikN3FRb" width=".779" height=".968" x="10.593" y="10.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_35" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-bed" /></template>
<style>
.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.an20q5kfx {
  stop-color: var(--svg-color--e0a531, #E0A531);
}

.atnucacjf {
  stop-color: var(--svg-color--2a2356, #2A2356);
  stop-opacity: 0;
}

.b5feq2trt {
  d: path("M2.439 20.854a.15.15 0 0 1 .15-.15h27.528a.15.15 0 0 1 .15.15v6.822a.15.15 0 0 1-.15.15H2.59a.15.15 0 0 1-.15-.15z");
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bthh05_yc {
  d: path("M2.439 11.4a1.46 1.46 0 0 1 2.922 0v9.304H2.539a.1.1 0 0 1-.1-.1z");
}

.bw9bhgcag {
  stop-color: var(--svg-color--481764, #481764);
}

.by3ainbne {
  d: path("M5.36 17.37c0-.22.18-.4.4-.4h7.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.cf8m5rrfx {
  stop-color: var(--svg-color--3173da, #3173DA);
  stop-opacity: 0;
}

.ctq4_rb_x {
  stop-color: var(--svg-color--4a2160, #4A2160);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.dzbbssbmi {
  stop-color: var(--svg-color--4e3568, #4E3568);
}

.erd70ybna {
  stop-color: var(--svg-color--6964bd, #6964BD);
}

.et566ebvf {
  stroke: var(--svg-color--a03c29, #A03C29);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M10.68 10.935c.094-.029.257-.053.399-.242c.104-.14.084-.314.062-.426");
}

.eunxegb_m {
  fill: var(--svg-color--2f63c0, #2F63C0);
  d: path("M5.36 14.636a1.4 1.4 0 0 1 1.4-1.4h6.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.ezijx-2ny {
  d: path("M12.33 14.067h14.437v-.6H12.33zm16.637 2.2v5.062h.6v-5.062zm-2.2-2.2a2.2 2.2 0 0 1 2.2 2.2h.6a2.8 2.8 0 0 0-2.8-2.8z");
}

.ffbkz6xwn {
  stop-color: var(--svg-color--5490e6, #5490E6);
}

.fl_2tebol {
  stop-color: var(--svg-color--1f60bf, #1F60BF);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fu6a58b1y {
  stop-color: var(--svg-color--1d46a7, #1D46A7);
  stop-opacity: 0;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.gmid2kucu {
  stop-color: var(--svg-color--1441b8, #1441B8);
  stop-opacity: 0;
}

.gr6t18twh {
  stop-color: var(--svg-color--497dba, #497DBA);
}

.h512dubmk {
  d: path("M11.978 9.91a1.1 1.1 0 0 1-.577-.071l-.118.16l1 .741c.264-.1.447-.388.325-.604c-.105-.186-.338-.278-.63-.225");
}

.hk15obc3x {
  d: path("M10.973 9.475c-.738-.494-1.253-.518-1.434-.484l-2.465 3.324l2.773 2.142c2.46.628 4.287-1.668 3.865-2.526s-1.885-1.884-2.74-2.456");
}

.hze7fms1a {
  stop-color: var(--svg-color--ffbf27, #FFBF27);
  stop-opacity: 0;
}

.ihb5mw0qq {
  stop-color: var(--svg-color--4e3568, #4E3568);
  stop-opacity: 0;
}

.j_iqhtv2z {
  stop-color: var(--svg-color--817ed9, #817ED9);
}

.j5-4bzb_q {
  d: path("M5.36 14.636a1.4 1.4 0 0 1 1.4-1.4h6.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.jddm9tctr {
  d: path("M4.439 26.892h2.96v2.969H4.44z");
}

.jp856yt_g {
  stop-color: var(--svg-color--5e4ac0, #5E4AC0);
}

.kbcj9odgo {
  stop-color: var(--svg-color--1441b8, #1441B8);
}

.kgio6d1ee {
  stop-color: var(--svg-color--ffa526, #FFA526);
  stop-opacity: 0;
}

.kgz9t0b5t {
  stop-color: var(--svg-color--32274d, #32274D);
}

.krsb9vstl {
  fill: var(--svg-color--25409f, #25409F);
  d: path("M8.073 10.15c.157-.239.531-.56 1.078-.459c.448.084.809.408.85.855c.232.007.642.098 1.179.457c.168.113.362.245.566.39a1 1 0 0 0 .364.014c.27-.05.486.036.583.208c.077.136.023.303-.096.425c.486.404.287 1.533.483 1.93c.36.732-.415 1.903-2.422 1.734q-.098.197-.233.456c-.152.29-.399.427-.605.366c-.241-.073-.386-.302-.313-.544l.014-.048c-.352.037-1.235-.002-2.347-.827c-1.208-.895-.082-1.448 0-1.83l.53-.237c.084-.387-1.193-.758-.552-1.332c.355-.318.443-.545.553-.826c.077-.2.166-.426.368-.732");
}

.kun3pubeg {
  stop-color: var(--svg-color--5a4eb7, #5A4EB7);
}

.ldg9ygbfk {
  stop-color: var(--svg-color--fca123, #FCA123);
  stop-opacity: 0;
}

.lfx99ibod {
  stop-color: var(--svg-color--7f7dcb, #7F7DCB);
}

.m1kxp_byq {
  stop-color: var(--svg-color--ffd03a, #FFD03A);
}

.mmf83abgd {
  d: path("M25.314 26.892h3.008v2.969h-3.008z");
}

.mz-tmnbha {
  d: path("M11.455 12.767h15.312a3.5 3.5 0 0 1 3.5 3.5v5.325a.3.3 0 0 1-.3.3H11.855a.4.4 0 0 1-.4-.4z");
}

.nw5hewkux {
  stop-color: var(--svg-color--305fb8, #305FB8);
  stop-opacity: 0;
}

.o8jz8mb4l {
  d: path("m10.437 12.901l-1.412-.771a.805.805 0 0 0 1.412.771");
}

.oesdu5b_i {
  stop-color: var(--svg-color--3071d8, #3071D8);
}

.onfzp-bwy {
  stop-color: var(--svg-color--5a4eb7, #5A4EB7);
  stop-opacity: 0;
}

.oydooacgz {
  fill: var(--svg-color--321853, #321853);
  d: path("M12.142 14.142H26.59a3.293 3.293 0 0 1 3.302 3.284v4.997a.28.28 0 0 1-.283.281H12.142a.376.376 0 0 1-.377-.375z");
}

.p6fb0tb2m {
  stop-color: var(--svg-color--ffe331, #FFE331);
}

.pw1txj0qv {
  stop-color: var(--svg-color--e8653b, #E8653B);
}

.qpqpigz0q {
  stop-color: var(--svg-color--28469e, #28469E);
}

.re8izvbqw {
  stop-color: var(--svg-color--ffa526, #FFA526);
}

.rnq8-kbby {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M11.843 11.848a.14.14 0 0 0 .159.115c.365-.058.645-.326.727-.416a.139.139 0 1 0-.204-.187c-.07.078-.297.286-.567.329a.14.14 0 0 0-.115.159");
}

.s50shpiqt {
  stop-color: var(--svg-color--40225f, #40225F);
}

.s8sy2oshg {
  stop-color: var(--svg-color--497dba, #497DBA);
  stop-opacity: 0;
}

.s9yijwaob {
  stop-color: var(--svg-color--faa030, #FAA030);
  stop-opacity: 0;
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.t5jak8x3h {
  stop-color: var(--svg-color--e4af34, #E4AF34);
}

.tejv_ybih {
  stop-color: var(--svg-color--4790dd, #4790DD);
}

.ti0324qcb {
  d: path("M8.78 8.057c-.59-.11-.993.238-1.163.496c-.526.796-.34 1.096-.995 1.683c-.693.62-.917 1.013-1.007 1.431l-.002.008c-.089.413-.273 1.266 1.032 2.233c1.202.892 2.155.933 2.536.894l-.015.051c-.079.262.077.51.338.588c.223.066.49-.082.654-.395a23 23 0 0 0 .418-.838a.275.275 0 0 0-.085-.338l-.99-.734a1.1 1.1 0 0 1-.426-.973c-.42-.334-.52-.613-.464-.906c.092-.485.26-.533.84-1.425c.586-.898.068-1.637-.67-1.775");
}

.tmk_n7bre {
  stop-color: var(--svg-color--403064, #403064);
}

.u7ukf0cyw {
  stop-color: var(--svg-color--160639, #160639);
  stop-opacity: 0;
}

.w-2pnubhf {
  stop-color: var(--svg-color--5490e6, #5490E6);
  stop-opacity: 0;
}

.we894y8xm {
  stop-color: var(--svg-color--7b74d4, #7B74D4);
}

.wjxfwib9z {
  fill: var(--svg-color--ffba23, #FFBA23);
  d: path("M8.78 8.057c-.59-.11-.993.238-1.163.496c-.526.796-.34 1.096-.995 1.683c-.693.62-.917 1.013-1.007 1.431l-.002.008c-.089.413-.273 1.266 1.032 2.233c1.202.892 2.155.933 2.536.894l-.015.051c-.079.262.077.51.338.588c.223.066.49-.082.654-.395a23 23 0 0 0 .418-.838a.275.275 0 0 0-.085-.338l-.99-.734a1.1 1.1 0 0 1-.426-.973c-.42-.334-.52-.613-.464-.906c.092-.485.26-.533.84-1.425c.586-.898.068-1.637-.67-1.775");
}

.xh4g4qbuv {
  stop-color: var(--svg-color--e0a531, #E0A531);
  stop-opacity: 0;
}

.xlbqkwbxp {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M10.087 10.225a1 1 0 0 1 .13-.204a.166.166 0 1 0-.24-.23a1.2 1.2 0 0 0-.19.292c-.062.13-.115.297-.116.478a.166.166 0 1 0 .333 0c0-.117.036-.235.083-.336");
}

.xrdg6g6_d {
  stop-color: var(--svg-color--6964bd, #6964BD);
  stop-opacity: 0;
}

.xxaw6lbdd {
  stop-color: var(--svg-color--3c2c4d, #3C2C4D);
}

.y125gvbnz {
  stop-color: var(--svg-color--f69637, #F69637);
}

.yeuw1mqbz {
  stop-color: var(--svg-color--3172d9, #3172D9);
}

.yj7_fabwq {
  stroke: var(--svg-color--b2685e, #B2685E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.743 10.9c.093-.028.257-.053.398-.242c.105-.139.085-.313.063-.425");
}

.yonqiacdw {
  stop-color: var(--svg-color--160639, #160639);
}

.yudqmabvt {
  stop-color: var(--svg-color--7c75d7, #7C75D7);
}

.yx0c6y8nw {
  stop-color: var(--svg-color--1c4eb1, #1C4EB1);
}

.yylhrtbwl {
  stop-color: var(--svg-color--481764, #481764);
  stop-opacity: 0;
}

.z7g_zwxuh {
  stop-color: var(--svg-color--0b3081, #0B3081);
}

.znfsawb6t {
  stop-color: var(--svg-color--3c2c4d, #3C2C4D);
  stop-opacity: 0;
}

.zq06kkbop {
  stop-color: var(--svg-color--0d0426, #0D0426);
}

</style>
