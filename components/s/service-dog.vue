<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ixYJQ2b)" class="cwgscqb8r"/><path fill="url(#iSy3wTc)" class="cwgscqb8r"/><path fill="url(#ilcRmjc)" class="cwgscqb8r"/><path fill="url(#iR8obEY)" class="s91nh5buy"/><path fill="url(#iNy1tjd)" class="s91nh5buy"/><path fill="url(#i9wZ7Cb)" class="s91nh5buy"/><path fill="url(#iN7SBAe)" class="s91nh5buy"/><g filter="url(#iMNmlfd)"><path fill="url(#iBec1Ac)" class="lwswxbctx"/><path fill="url(#iUsjsne)" class="lwswxbctx"/></g><path fill="url(#in3ttjb)" class="lwswxbctx"/><path fill="url(#ixsXB0b)" class="mjmzzwi1h"/><path fill="url(#iN7PS1b)" class="mjmzzwi1h"/><path fill="url(#i9sSv7c)" class="mjmzzwi1h"/><path fill="url(#iSQTfBW)" class="mjmzzwi1h"/><path fill="url(#iFXptFd)" class="mjmzzwi1h"/><path fill="url(#i7chBQG)" class="mjmzzwi1h"/><path fill="url(#icVdw9d)" class="mjmzzwi1h"/><path fill="url(#iCvdhJS)" class="mjmzzwi1h"/><path fill="url(#iy48pEe)" class="mjmzzwi1h"/><path fill="url(#iYgAK0b)" class="mjmzzwi1h"/><path fill="url(#incv4ed)" class="mjmzzwi1h"/><path fill="url(#iZ2CGje)" class="mjmzzwi1h"/><g filter="url(#iMrayGE)"><path class="v3mnicbzm"/></g><g filter="url(#ixZeIPD)"><path fill="url(#iEFTR6b)" class="nw00_ibao"/></g><path fill="url(#iDsUS3b)" class="v51hnp92r"/><path fill="url(#iU4M1sd)" class="v51hnp92r"/><path fill="url(#i2oLeLH)" class="v51hnp92r"/><path fill="url(#iqXETVd)" class="v51hnp92r"/><path fill="url(#i67QY1b)" class="v51hnp92r"/><path fill="url(#ikiCY5k)" class="g2j5f_bli"/><path fill="url(#i251LxS)" class="g2j5f_bli"/><path fill="url(#if86NsJ)" class="g2j5f_bli"/><path fill="url(#ifAuHUd)" class="k9w4pjagu"/><path class="i1hn1qbon"/><path fill="url(#iSMaFyT)" class="vascx6usj"/><path class="lhg41todo"/><path fill="url(#iGvjTkc)" class="ftcwxvr-q"/><path fill="url(#i8n1xed)" class="ftcwxvr-q"/><path fill="url(#iRx61lc)" class="ftcwxvr-q"/><path fill="url(#iJUIGCd)" class="ftcwxvr-q"/><path class="a4qhkhb1f"/><path fill="url(#in5Clxc)" class="u1aa3fs0j"/><path fill="url(#ioc6bke)" class="u1aa3fs0j"/><path fill="url(#iOFLRAb)" class="dnkgcry-m"/><path fill="url(#ipxwtrc)" class="dnkgcry-m"/><rect fill="url(#io6oN7c)" class="i1de2hbde"/><rect fill="url(#iyy5a1b)" class="i1de2hbde"/><g filter="url(#iqunitb)"><path stroke="url(#iwpYLvc)" class="kyacmn6hk"/></g><g filter="url(#i5Vk0Xc)"><path fill="url(#iHHt7kc)" class="zexp61p-y"/></g><g filter="url(#iJTCOXc)"><ellipse fill="url(#ijefcce)" transform="rotate(-37.52 20.204 25.959)" class="q3npcjx5o"/></g><defs><linearGradient id="ixYJQ2b" x1="22.332" x2="27.832" y1="28.74" y2="21.24" gradientUnits="userSpaceOnUse"><stop class="xpg7qbdiy"/><stop offset="1" class="u-1se5bme"/></linearGradient><linearGradient id="ilcRmjc" x1="31.853" x2="27.411" y1="29.131" y2="22.359" gradientUnits="userSpaceOnUse"><stop class="maky1vtxa"/><stop offset="1" class="fzg71fvoh"/></linearGradient><linearGradient id="iR8obEY" x1="24.832" x2="24.145" y1="9.052" y2="8.834" gradientUnits="userSpaceOnUse"><stop class="xxacj2gnf"/><stop offset="1" class="lytgfackk"/></linearGradient><linearGradient id="iNy1tjd" x1="22.176" x2="29.051" y1="13.888" y2="13.888" gradientUnits="userSpaceOnUse"><stop class="yai_z68dd"/><stop offset="1" class="f3m0o3b-h"/></linearGradient><linearGradient id="i9wZ7Cb" x1="21.207" x2="21.207" y1="14.99" y2="12.974" gradientUnits="userSpaceOnUse"><stop class="lytgfackk"/><stop offset=".651" class="xr1rukpfs"/></linearGradient><linearGradient id="iN7SBAe" x1="26.645" x2="25.707" y1="7.677" y2="7.365" gradientUnits="userSpaceOnUse"><stop class="syrm5i6wy"/><stop offset="1" class="ofmu9dbks"/></linearGradient><linearGradient id="iBec1Ac" x1="6.957" x2="10.27" y1="24.865" y2="23.396" gradientUnits="userSpaceOnUse"><stop class="h3sdvibxx"/><stop offset="1" class="pyheansxe"/></linearGradient><linearGradient id="iUsjsne" x1="8.52" x2="10.53" y1="24.927" y2="25.802" gradientUnits="userSpaceOnUse"><stop class="tbcwyjm5q"/><stop offset="1" class="pyheansxe"/></linearGradient><linearGradient id="in3ttjb" x1="8.075" x2="8.075" y1="30.857" y2="29.209" gradientUnits="userSpaceOnUse"><stop class="nqpm4fbda"/><stop offset="1" class="kazkw750e"/></linearGradient><linearGradient id="ixsXB0b" x1="18.582" x2="9.645" y1="18.99" y2="30.14" gradientUnits="userSpaceOnUse"><stop offset=".288" class="rktp8r2fg"/><stop offset="1" class="bfykyx-ej"/></linearGradient><linearGradient id="i9sSv7c" x1="13.525" x2="13.525" y1="30.802" y2="29.709" gradientUnits="userSpaceOnUse"><stop class="nqpm4fbda"/><stop offset="1" class="kazkw750e"/></linearGradient><linearGradient id="i7chBQG" x1="25.832" x2="23.457" y1="22.24" y2="22.24" gradientUnits="userSpaceOnUse"><stop class="bmuwf5bkz"/><stop offset="1" class="an-l7xssx"/></linearGradient><linearGradient id="icVdw9d" x1="20.02" x2="19.332" y1="32.927" y2="28.365" gradientUnits="userSpaceOnUse"><stop class="v_my4zb4k"/><stop offset="1" class="m5yoevamn"/></linearGradient><linearGradient id="iEFTR6b" x1="13.832" x2="13.354" y1="15.178" y2="7.643" gradientUnits="userSpaceOnUse"><stop class="co9duqo4c"/><stop offset="1" class="mi6prm8tt"/></linearGradient><linearGradient id="iDsUS3b" x1="17.03" x2="17.03" y1="32.052" y2="23.865" gradientUnits="userSpaceOnUse"><stop class="h3_x8shvd"/><stop offset="1" class="d2o6utbjp"/></linearGradient><linearGradient id="iqXETVd" x1="17.03" x2="17.03" y1="30.802" y2="28.24" gradientUnits="userSpaceOnUse"><stop class="am-slf3ky"/><stop offset="1" class="kazkw750e"/></linearGradient><linearGradient id="ikiCY5k" x1="12.53" x2="7.403" y1="16.14" y2="16.14" gradientUnits="userSpaceOnUse"><stop class="j11g_4jhd"/><stop offset="1" class="e4d0r_bxz"/></linearGradient><linearGradient id="i251LxS" x1="9.966" x2="9.966" y1="18.334" y2="17.756" gradientUnits="userSpaceOnUse"><stop class="iacjqaczs"/><stop offset="1" class="sl4x2nbyx"/></linearGradient><linearGradient id="if86NsJ" x1="13.629" x2="12.145" y1="17.756" y2="17.756" gradientUnits="userSpaceOnUse"><stop class="iacjqaczs"/><stop offset="1" class="sl4x2nbyx"/></linearGradient><linearGradient id="iGvjTkc" x1="18.472" x2="18.472" y1="22.427" y2="21.568" gradientUnits="userSpaceOnUse"><stop class="iacjqaczs"/><stop offset="1" class="sl4x2nbyx"/></linearGradient><linearGradient id="i8n1xed" x1="12.332" x2="12.989" y1="21.568" y2="21.568" gradientUnits="userSpaceOnUse"><stop class="iacjqaczs"/><stop offset="1" class="sl4x2nbyx"/></linearGradient><linearGradient id="in5Clxc" x1="4.527" x2="4.527" y1="9.14" y2="14.441" gradientUnits="userSpaceOnUse"><stop class="vrlbd5b7w"/><stop offset="1" class="xpg7qbdiy"/></linearGradient><linearGradient id="iOFLRAb" x1="4.218" x2="3.059" y1="9.613" y2="9.89" gradientUnits="userSpaceOnUse"><stop offset=".225" class="mp43u-g5l"/><stop offset="1" class="vzlnlu3vr"/></linearGradient><linearGradient id="ipxwtrc" x1="4.833" x2="4.833" y1="10.902" y2="9.637" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="io6oN7c" x1="9.379" x2="8.754" y1="10.14" y2="10.14" gradientUnits="userSpaceOnUse"><stop offset=".225" class="mp43u-g5l"/><stop offset="1" class="vzlnlu3vr"/></linearGradient><linearGradient id="iyy5a1b" x1="9.676" x2="9.676" y1="11.49" y2="9.802" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iwpYLvc" x1="27.113" x2="30.118" y1="17.685" y2="24.841" gradientUnits="userSpaceOnUse"><stop class="jq2jm93ju"/><stop offset="1" class="qf9031xau"/></linearGradient><linearGradient id="iHHt7kc" x1="13.707" x2="13.914" y1="3.177" y2="8.419" gradientUnits="userSpaceOnUse"><stop class="vibe9zqqm"/><stop offset="1" class="mi6prm8tt"/></linearGradient><radialGradient id="iSy3wTc" cx="0" cy="0" r="1" gradientTransform="matrix(2.48438 .27993 -.82312 7.30514 25.082 22.6)" gradientUnits="userSpaceOnUse"><stop class="n4xi2gben"/><stop offset="1" class="bis4wubxf"/></radialGradient><radialGradient id="iN7PS1b" cx="0" cy="0" r="1" gradientTransform="matrix(9.06248 14.58757 -25.02924 15.54935 13.082 15.552)" gradientUnits="userSpaceOnUse"><stop offset=".779" class="zx1ejwvhd"/><stop offset="1" class="ul95y5hdz"/></radialGradient><radialGradient id="iSQTfBW" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4687 -5.56253 4.45002 -2.77496 16.145 25.052)" gradientUnits="userSpaceOnUse"><stop class="jqr55ob2p"/><stop offset="1" class="jfy6mqh6p"/></radialGradient><radialGradient id="iFXptFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.53125 1.96875 -1.4253 1.10857 10.692 4.74)" gradientUnits="userSpaceOnUse"><stop class="bmuwf5bkz"/><stop offset="1" class="an-l7xssx"/></radialGradient><radialGradient id="iCvdhJS" cx="0" cy="0" r="1" gradientTransform="rotate(-120.192 15.529 8.612)scale(3.97698 3.24362)" gradientUnits="userSpaceOnUse"><stop class="u5irxdbxx"/><stop offset=".967" class="m5yoevamn"/></radialGradient><radialGradient id="iy48pEe" cx="0" cy="0" r="1" gradientTransform="rotate(-22.068 64.18 -1.678)scale(7.48593 13.0088)" gradientUnits="userSpaceOnUse"><stop class="tey3ncbla"/><stop offset="1" class="eghqhz1ar"/></radialGradient><radialGradient id="iYgAK0b" cx="0" cy="0" r="1" gradientTransform="matrix(3.5 -1.90625 1.63903 3.00937 6.77 22.74)" gradientUnits="userSpaceOnUse"><stop class="u5irxdbxx"/><stop offset=".967" class="m5yoevamn"/></radialGradient><radialGradient id="incv4ed" cx="0" cy="0" r="1" gradientTransform="matrix(3.03125 -3.46875 2.33083 2.03686 4.27 16.052)" gradientUnits="userSpaceOnUse"><stop class="dnk4gl4ip"/><stop offset=".967" class="m5yoevamn"/></radialGradient><radialGradient id="iZ2CGje" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 3.875 -6.73382 8.90603 4.895 6.927)" gradientUnits="userSpaceOnUse"><stop class="tey3ncbla"/><stop offset="1" class="eghqhz1ar"/></radialGradient><radialGradient id="iU4M1sd" cx="0" cy="0" r="1" gradientTransform="matrix(3 -5.6875 4.00842 2.11433 15.02 31.49)" gradientUnits="userSpaceOnUse"><stop class="jqr55ob2p"/><stop offset="1" class="jfy6mqh6p"/></radialGradient><radialGradient id="i2oLeLH" cx="0" cy="0" r="1" gradientTransform="matrix(6.375 -3.0563 5.6783 11.8441 12.083 30.14)" gradientUnits="userSpaceOnUse"><stop class="i1bkk5bps"/><stop offset="1" class="w0mjdsbpm"/></radialGradient><radialGradient id="i67QY1b" cx="0" cy="0" r="1" gradientTransform="matrix(12.59376 .03125 -.02014 8.11629 11.145 27.052)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="tbcwyjm5q"/><stop offset="1" class="pyheansxe"/></radialGradient><radialGradient id="ifAuHUd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.75 0 0 -10.5461 22.582 18.515)" gradientUnits="userSpaceOnUse"><stop class="opof10ogx"/><stop offset="1" class="zhd_p-83y"/></radialGradient><radialGradient id="iSMaFyT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33376 3.3125 -8.99697 -3.6226 20.864 15.521)" gradientUnits="userSpaceOnUse"><stop class="ejsudabne"/><stop offset="1" class="fy5086mts"/></radialGradient><radialGradient id="iRx61lc" cx="0" cy="0" r="1" gradientTransform="rotate(136.715 5.343 9.945)scale(3.69187 7.12318)" gradientUnits="userSpaceOnUse"><stop class="ejsudabne"/><stop offset="1" class="fy5086mts"/></radialGradient><radialGradient id="iJUIGCd" cx="0" cy="0" r="1" gradientTransform="rotate(157.238 10.367 12.438)scale(4.84617 8.40102)" gradientUnits="userSpaceOnUse"><stop class="ejsudabne"/><stop offset="1" class="fy5086mts"/></radialGradient><radialGradient id="ioc6bke" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.01685 -8.11095 0 5.86 10.926)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="fzg71fvoh"/><stop offset="1" class="maky1vtxa"/></radialGradient><radialGradient id="ijefcce" cx="0" cy="0" r="1" gradientTransform="matrix(-2.44462 2.58493 -1.99711 -1.8887 21.418 26.246)" gradientUnits="userSpaceOnUse"><stop class="qy69g9h_i"/><stop offset="1" class="i-f5_jb1j"/></radialGradient><filter id="iMNmlfd" width="4.974" height="12.25" x="5.806" y="17.89" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854167 0 0 0 0 0.599194 0 0 0 0 0.40217 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_1801"/></filter><filter id="iMrayGE" width="3.344" height="4.094" x="12.973" y="11.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1801" stdDeviation=".5"/></filter><filter id="ixZeIPD" width="3.605" height="11.313" x="11.53" y="6.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1801" stdDeviation=".5"/></filter><filter id="iqunitb" width="5.181" height="12.265" x="24.523" y="16.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1801" stdDeviation=".5"/></filter><filter id="i5Vk0Xc" width="2.556" height="7.128" x="11.979" y="3.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1801" stdDeviation=".2"/></filter><filter id="iJTCOXc" width="6.166" height="6.423" x="17.121" y="22.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1801" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:service-dog" /></template>
<style>
.a4qhkhb1f {
  fill: var(--svg-color--ff939c, #FF939C);
  d: path("M16.03 18.28a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.am-slf3ky {
  stop-color: var(--svg-color--eb64dd, #EB64DD);
}

.an-l7xssx {
  stop-color: var(--svg-color--e07b42, #E07B42);
  stop-opacity: 0;
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.bfykyx-ej {
  stop-color: var(--svg-color--d38c84, #D38C84);
}

.bis4wubxf {
  stop-color: var(--svg-color--914135, #914135);
  stop-opacity: 0;
}

.bmuwf5bkz {
  stop-color: var(--svg-color--e07b42, #E07B42);
}

.co9duqo4c {
  stop-color: var(--svg-color--f4d4a3, #F4D4A3);
  stop-opacity: 0.5;
}

.cwgscqb8r {
  d: path("M24.53 16.77c0 1.16.42 2.27 1.15 3.17c.56.69.89 1.59.84 2.56c-.09 1.94-1.65 3.52-3.59 3.62c-1.82.1-3.39-1.1-3.86-2.75H16c.51 3.29 3.37 5.8 6.82 5.76c3.63-.05 6.61-2.99 6.7-6.62a6.8 6.8 0 0 0-4.01-6.38a.7.7 0 0 0-.98.64");
}

.d2o6utbjp {
  stop-color: var(--svg-color--f3a372, #F3A372);
}

.dnk4gl4ip {
  stop-color: var(--svg-color--ec52dc, #EC52DC);
}

.dnkgcry-m {
  d: path("M3.77 10.64h-.5c-.41 0-.75-.34-.75-.75s.34-.75.75-.75h.5a.749.749 0 1 1 0 1.5");
}

.e4d0r_bxz {
  stop-color: var(--svg-color--605d65, #605D65);
}

.eghqhz1ar {
  stop-color: var(--svg-color--d49177, #D49177);
  stop-opacity: 0;
}

.ejsudabne {
  stop-color: var(--svg-color--8a898d, #8A898D);
}

.f3m0o3b-h {
  stop-color: var(--svg-color--01a6f0, #01A6F0);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftcwxvr-q {
  d: path("m15.534 21.167l-.004-.695c0-.72-.59-1.31-1.31-1.31h-.69V15.14h.69c.72 0 1.31-.59 1.31-1.31v-1.09l-.697-.418a.2.2 0 0 0-.303.171v1.337c0 .04-.01.08-.02.12a.35.35 0 0 1-.17.17c-.04.01-.08.02-.12.02h-.75c-.32 0-.61.16-.78.41a.94.94 0 0 0-.16.52v4.142a.93.93 0 0 0 .94.93h.75c.04 0 .08.01.12.02c.07.03.13.09.17.17c.02.04.02.08.02.12l.004.755a.93.93 0 0 0 .94.93h8.708a.196.196 0 0 0 .195-.228a9 9 0 0 0-.173-.772h-8.67z");
}

.fy5086mts {
  stop-color: var(--svg-color--79787d, #79787D);
  stop-opacity: 0;
}

.fzg71fvoh {
  stop-color: var(--svg-color--793875, #793875);
  stop-opacity: 0;
}

.g2j5f_bli {
  d: path("M12.53 16.14H7.553a.15.15 0 0 0-.15.15v1.7c0 .083.067.15.15.15h4.977z");
}

.h3_x8shvd {
  stop-color: var(--svg-color--f3a250, #F3A250);
}

.h3sdvibxx {
  stop-color: var(--svg-color--d29169, #D29169);
}

.i-f5_jb1j {
  stop-color: var(--svg-color--ffbf7a, #FFBF7A);
  stop-opacity: 0;
}

.i1bkk5bps {
  stop-color: var(--svg-color--f0b392, #F0B392);
}

.i1de2hbde {
  width: 1px;
  height: 2px;
  x: 8.52px;
  y: 9.14px;
  rx: 0.5px;
}

.i1hn1qbon {
  fill: var(--svg-color--636363, #636363);
  d: path("m19.8 15.3l-.27-.16v7h1v-6.35c-.23-.18-.48-.34-.73-.49");
}

.iacjqaczs {
  stop-color: var(--svg-color--5e4a66, #5E4A66);
}

.j11g_4jhd {
  stop-color: var(--svg-color--626067, #626067);
}

.jfy6mqh6p {
  stop-color: var(--svg-color--c67040, #C67040);
  stop-opacity: 0;
}

.jq2jm93ju {
  stop-color: var(--svg-color--fadcaf, #FADCAF);
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jqr55ob2p {
  stop-color: var(--svg-color--c67040, #C67040);
}

.k9w4pjagu {
  d: path("m19.8 15.3l-4.967-2.979a.2.2 0 0 0-.303.172v1.337c0 .17-.14.31-.31.31h-.75c-.52 0-.94.42-.94.94v4.12c0 .52.42.94.94.94h.75c.17 0 .31.14.31.31v.75c0 .52.42.94.94.94h8.706c.123 0 .217-.11.195-.23A9.73 9.73 0 0 0 19.8 15.3");
}

.kazkw750e {
  stop-color: var(--svg-color--eb8d98, #EB8D98);
  stop-opacity: 0;
}

.kyacmn6hk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M25.944 17.183c.746.45 2.301 1.862 2.549 3.901c.309 2.55-.541 4.79-2.82 6.064");
}

.lhg41todo {
  fill: var(--svg-color--636363, #636363);
  d: path("m15.534 21.167l-.004-.695c0-.72-.59-1.31-1.31-1.31h-.69V15.14h.69c.72 0 1.31-.59 1.31-1.31v-1.09l-.697-.418a.2.2 0 0 0-.303.171v1.337c0 .04-.01.08-.02.12a.35.35 0 0 1-.17.17c-.04.01-.08.02-.12.02h-.75c-.32 0-.61.16-.78.41a.94.94 0 0 0-.16.52v4.142a.93.93 0 0 0 .94.93h.75c.04 0 .08.01.12.02c.07.03.13.09.17.17c.02.04.02.08.02.12l.004.755a.93.93 0 0 0 .94.93h8.708a.196.196 0 0 0 .195-.228a9 9 0 0 0-.173-.772h-8.67z");
}

.lwswxbctx {
  d: path("M7.53 18.14v5.81c0 .14-.02.28-.05.41l-1.65 5.127a.5.5 0 0 0 .476.653H8.62l1.71-5.26c.13-.48.2-.99.2-1.49v-5.25z");
}

.lytgfackk {
  stop-color: var(--svg-color--1e6ca5, #1E6CA5);
}

.m5yoevamn {
  stop-color: var(--svg-color--d23ac3, #D23AC3);
  stop-opacity: 0;
}

.maky1vtxa {
  stop-color: var(--svg-color--793875, #793875);
}

.mi6prm8tt {
  stop-color: var(--svg-color--ffc38b, #FFC38B);
  stop-opacity: 0;
}

.mjmzzwi1h {
  d: path("m19.8 15.3l-5.076-3.043a.4.4 0 0 1-.194-.344V7.12c0-1.57-.82-3.05-2.12-3.88c-.38-.24-.88.05-.88.5l.024 1.894a.5.5 0 0 1-.5.506h-.934c-1.01 0-1.95.51-2.5 1.35l-.81 1.23c-.17.26-.46.42-.78.42H3.24c-.4 0-.72.32-.72.72v.27a3.993 3.993 0 0 0 3.99 4.01h.61c.22 0 .41.18.41.4l.01 3.52c0 1.074.55 2.016 1.384 2.566c.348.23.616.59.616 1.006V24.3c0 .14-.02.28-.05.41l-1.642 4.767a.5.5 0 0 0 .473.663h1.944a.5.5 0 0 0 .472-.335l1.593-4.555c.13-.48.2-.99.2-1.49v-.098a.3.3 0 0 1 .451-.259l2.549 1.487v5.25h4.86c2.29 0 4.14-1.85 4.14-4.14v-2.34c0-3.42-1.79-6.6-4.73-8.36");
}

.mp43u-g5l {
  stop-color: var(--svg-color--6b5e60, #6B5E60);
}

.n4xi2gben {
  stop-color: var(--svg-color--914135, #914135);
}

.nqpm4fbda {
  stop-color: var(--svg-color--ef74e3, #EF74E3);
}

.nw00_ibao {
  d: path("M12.53 7.115h1.605v9.313H12.53z");
}

.ofmu9dbks {
  stop-color: var(--svg-color--53b7ff, #53B7FF);
  stop-opacity: 0;
}

.opof10ogx {
  stop-color: var(--svg-color--ff6064, #FF6064);
}

.pyheansxe {
  stop-color: var(--svg-color--cd6a3d, #CD6A3D);
}

.q3npcjx5o {
  cx: 20.204px;
  cy: 25.959px;
  rx: 1.884px;
  ry: 2.383px;
}

.qf9031xau {
  stop-color: var(--svg-color--ffdeab, #FFDEAB);
  stop-opacity: 0;
}

.qy69g9h_i {
  stop-color: var(--svg-color--ffbf7a, #FFBF7A);
}

.rktp8r2fg {
  stop-color: var(--svg-color--eead71, #EEAD71);
}

.s91nh5buy {
  d: path("m26.57 2.14l-2.92 7.87a4.8 4.8 0 0 1-4.49 3.15h-5.63v1.5h5.63c2.63 0 5-1.66 5.9-4.13l3.11-8.39z");
}

.sl4x2nbyx {
  stop-color: var(--svg-color--5e4a66, #5E4A66);
  stop-opacity: 0;
}

.syrm5i6wy {
  stop-color: var(--svg-color--75c6ff, #75C6FF);
}

.tbcwyjm5q {
  stop-color: var(--svg-color--cd6a3d, #CD6A3D);
  stop-opacity: 0;
}

.tey3ncbla {
  stop-color: var(--svg-color--d49177, #D49177);
}

.u-1se5bme {
  stop-color: var(--svg-color--9c634d, #9C634D);
}

.u1aa3fs0j {
  d: path("M6.53 10.21c0-.59-.48-1.07-1.06-1.07H3.23c-.39.01-.71.32-.71.72v.27a3.993 3.993 0 0 0 3.99 4.01h.02z");
}

.u5irxdbxx {
  stop-color: var(--svg-color--e966dc, #E966DC);
}

.ul95y5hdz {
  stop-color: var(--svg-color--ef9766, #EF9766);
}

.v_my4zb4k {
  stop-color: var(--svg-color--d23ac3, #D23AC3);
}

.v3mnicbzm {
  fill: var(--svg-color--d98126, #D98126);
  d: path("M13.973 12.566v1.906l1.344.188v-1.344z");
}

.v51hnp92r {
  d: path("M19.03 23.14h-1.66c-2.12 0-3.84 1.72-3.84 3.84v1.16c-.93 0-1.716.642-1.938 1.505c-.068.268.162.495.438.495h7c1.93 0 3.5-1.57 3.5-3.5s-1.56-3.5-3.5-3.5");
}

.vascx6usj {
  d: path("m19.8 15.3l-.27-.16v7h1v-6.35c-.23-.18-.48-.34-.73-.49");
}

.vibe9zqqm {
  stop-color: var(--svg-color--f4d4a3, #F4D4A3);
}

.vrlbd5b7w {
  stop-color: var(--svg-color--a4745f, #A4745F);
}

.vzlnlu3vr {
  stop-color: var(--svg-color--433338, #433338);
}

.w0mjdsbpm {
  stop-color: var(--svg-color--f0b392, #F0B392);
  stop-opacity: 0;
}

.xpg7qbdiy {
  stop-color: var(--svg-color--63332a, #63332A);
}

.xr1rukpfs {
  stop-color: var(--svg-color--1e6ca5, #1E6CA5);
  stop-opacity: 0;
}

.xxacj2gnf {
  stop-color: var(--svg-color--229bff, #229BFF);
}

.yai_z68dd {
  stop-color: var(--svg-color--01a6f0, #01A6F0);
}

.zexp61p-y {
  d: path("M12.38 3.724c.473.133 1.602 1.255 1.728 3.668c.01.2.02 2.482.027 2.66h-1.068c0-4.328-.688-6.328-.688-6.328");
}

.zhd_p-83y {
  stop-color: var(--svg-color--fb3252, #FB3252);
}

.zx1ejwvhd {
  stop-color: var(--svg-color--ef9766, #EF9766);
  stop-opacity: 0;
}

</style>
