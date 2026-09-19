<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i95glyb)" class="b53so-ben"/><path fill="url(#ixZxduc)" class="b53so-ben"/><path fill="url(#ieafmgc)" class="f1vmx30mm"/><path fill="url(#iDBUv1B)" class="f1vmx30mm"/><g filter="url(#i1PpfUc)"><path fill="url(#ieHuajc)" class="utkqq-1vm"/></g><path fill="url(#iatW4xe)" class="utkqq-1vm"/><path fill="url(#iBWOAgc)" class="utkqq-1vm"/><path fill="url(#iPY71dc)" class="utkqq-1vm"/><path fill="url(#iFDp7Cb)" class="utkqq-1vm"/><path fill="url(#iEepgUc)" class="dxs2u4bkb"/><path fill="url(#iaiVR4n)" class="dxs2u4bkb"/><path fill="url(#itTe0cJ)" class="dxs2u4bkb"/><path fill="url(#ie1iDMI)" class="t6b7jmb8v"/><path fill="url(#iPEtr5d)" class="t6b7jmb8v"/><path fill="url(#iuzGdDe)" class="t6b7jmb8v"/><g filter="url(#icmZWKd)"><path fill="url(#iNKL2Me)" class="d3quornkc"/></g><g filter="url(#iC9Qkmt)"><path fill="url(#iNOgGqb)" class="jg_4avb4m"/></g><g filter="url(#i3cBfWc)"><path fill="url(#i7Ce21c)" class="xnmca801k"/><path fill="url(#ixOOSTR)" class="xnmca801k"/></g><g filter="url(#imv8wdd)"><path fill="url(#irp6Umc)" class="e9o53jb8s"/><path fill="url(#i0uqgRd)" class="e9o53jb8s"/></g><g filter="url(#iSESrCd)"><path fill="url(#iFlLCmb)" class="h762a0bxd"/><path fill="url(#ir7BKud)" class="h762a0bxd"/></g><path fill="url(#i7xtjEc)" class="yrxbrciiu"/><path fill="url(#imk2LBc)" class="yrxbrciiu"/><path fill="url(#iApVcId)" class="yrxbrciiu"/><path fill="url(#izUo80c)" class="yrxbrciiu"/><rect fill="url(#iBbASEe)" class="vacseh2iy"/><rect fill="url(#i9P7Pwe)" class="vacseh2iy"/><rect fill="url(#iizzovc)" class="vacseh2iy"/><g filter="url(#ii4zlUg)"><path stroke="url(#ioNAZPg)" class="nicusyj3q"/></g><g filter="url(#iMrxFab)"><path stroke="url(#imWvwHb)" class="bzbflbc1n"/></g><g filter="url(#idCi5bb)"><path stroke="url(#ii79Rwe)" class="t_y8spp0w"/></g><g filter="url(#iGYHXQc)"><path fill="url(#ixWQlNc)" class="b-tsujbar"/></g><g filter="url(#iKAHCIb)"><ellipse fill="url(#iWH9vbc)" class="s8gpdxbze"/></g><g filter="url(#irGs71d)"><path fill="url(#iYSnD8d)" class="hvq_a3foa"/></g><g filter="url(#iCAdkjc)"><path stroke="url(#ixBZRHd)" class="n611c2b-a"/></g><defs><linearGradient id="ieHuajc" x1="17.392" x2="17.392" y1="14.724" y2="30.162" gradientUnits="userSpaceOnUse"><stop class="rzj_sxbux"/><stop offset="1" class="gevqk-coj"/></linearGradient><linearGradient id="iEepgUc" x1="27.465" x2="27.465" y1="8.03" y2="8.796" gradientUnits="userSpaceOnUse"><stop class="v2ba7hjem"/><stop offset="1" class="trlqtr3kv"/></linearGradient><linearGradient id="iaiVR4n" x1="24.03" x2="24.321" y1="8.727" y2="8.727" gradientUnits="userSpaceOnUse"><stop class="pm_a5g9kk"/><stop offset="1" class="a65m14nmn"/></linearGradient><linearGradient id="itTe0cJ" x1="30.9" x2="30.66" y1="9.02" y2="9.02" gradientUnits="userSpaceOnUse"><stop class="t9uecpb_t"/><stop offset="1" class="deq_o8bbe"/></linearGradient><linearGradient id="ie1iDMI" x1="5.445" x2="5.445" y1="8.03" y2="8.796" gradientUnits="userSpaceOnUse"><stop class="v2ba7hjem"/><stop offset="1" class="trlqtr3kv"/></linearGradient><linearGradient id="iPEtr5d" x1="2.01" x2="2.301" y1="8.727" y2="8.727" gradientUnits="userSpaceOnUse"><stop class="pm_a5g9kk"/><stop offset="1" class="a65m14nmn"/></linearGradient><linearGradient id="iuzGdDe" x1="8.88" x2="8.64" y1="9.02" y2="9.02" gradientUnits="userSpaceOnUse"><stop class="t9uecpb_t"/><stop offset="1" class="deq_o8bbe"/></linearGradient><linearGradient id="iNKL2Me" x1="4.43" x2="6.45" y1="14.354" y2="14.354" gradientUnits="userSpaceOnUse"><stop class="c0snqvuhx"/><stop offset="1" class="zimffnu2h"/><stop offset="1" class="j2uxz-b9j"/><stop offset="1" class="bb3393bce"/></linearGradient><linearGradient id="iNOgGqb" x1="26.43" x2="28.45" y1="14.354" y2="14.354" gradientUnits="userSpaceOnUse"><stop class="c0snqvuhx"/><stop offset="1" class="zimffnu2h"/><stop offset="1" class="j2uxz-b9j"/><stop offset="1" class="bb3393bce"/></linearGradient><linearGradient id="i7Ce21c" x1="13.44" x2="19.41" y1="24.833" y2="24.833" gradientUnits="userSpaceOnUse"><stop class="v52ofib4o"/><stop offset="1" class="zimffnu2h"/><stop offset="1" class="o-4e8gwlc"/></linearGradient><linearGradient id="ixOOSTR" x1="13.44" x2="14.289" y1="25.714" y2="25.714" gradientUnits="userSpaceOnUse"><stop class="t0_vb0b-l"/><stop offset="1" class="ffb59jj-e"/></linearGradient><linearGradient id="irp6Umc" x1="3.45" x2="8.47" y1="26.09" y2="26.09" gradientUnits="userSpaceOnUse"><stop class="i6jb1_zqm"/><stop offset="1" class="zimffnu2h"/><stop offset="1" class="j2uxz-b9j"/></linearGradient><linearGradient id="i0uqgRd" x1="3.45" x2="4.164" y1="26.707" y2="26.707" gradientUnits="userSpaceOnUse"><stop class="oon63-kza"/><stop offset="1" class="cxj9w1svw"/></linearGradient><linearGradient id="iFlLCmb" x1="24.44" x2="29.45" y1="26.09" y2="26.09" gradientUnits="userSpaceOnUse"><stop class="i6jb1_zqm"/><stop offset="1" class="zimffnu2h"/><stop offset="1" class="j2uxz-b9j"/></linearGradient><linearGradient id="ir7BKud" x1="24.44" x2="25.153" y1="26.707" y2="26.707" gradientUnits="userSpaceOnUse"><stop class="oon63-kza"/><stop offset="1" class="cxj9w1svw"/></linearGradient><linearGradient id="i7xtjEc" x1="10.768" x2="21.205" y1="12.037" y2="12.037" gradientUnits="userSpaceOnUse"><stop offset=".108" class="foj016edh"/><stop offset=".946" class="ht5mvpbtp"/></linearGradient><linearGradient id="iBbASEe" x1="16.504" x2="16.504" y1="14.159" y2="14.935" gradientUnits="userSpaceOnUse"><stop class="v2ba7hjem"/><stop offset="1" class="trlqtr3kv"/></linearGradient><linearGradient id="i9P7Pwe" x1="10.509" x2="11.018" y1="14.865" y2="14.865" gradientUnits="userSpaceOnUse"><stop class="pm_a5g9kk"/><stop offset="1" class="a65m14nmn"/></linearGradient><linearGradient id="iizzovc" x1="22.5" x2="22.08" y1="15.162" y2="15.162" gradientUnits="userSpaceOnUse"><stop class="t9uecpb_t"/><stop offset="1" class="deq_o8bbe"/></linearGradient><linearGradient id="ioNAZPg" x1="11.776" x2="23.913" y1="14.849" y2="14.849" gradientUnits="userSpaceOnUse"><stop class="x7qgcwd4r"/><stop offset="1" class="gy_cffs1h"/></linearGradient><linearGradient id="imWvwHb" x1="24.937" x2="31.352" y1="318531" y2="318531" gradientUnits="userSpaceOnUse"><stop class="x7qgcwd4r"/><stop offset="1" class="gy_cffs1h"/></linearGradient><linearGradient id="ii79Rwe" x1="2.785" x2="9.2" y1="339713" y2="339713" gradientUnits="userSpaceOnUse"><stop class="x7qgcwd4r"/><stop offset="1" class="gy_cffs1h"/></linearGradient><linearGradient id="ixWQlNc" x1="31.11" x2="28.57" y1="5.412" y2="6.412" gradientUnits="userSpaceOnUse"><stop class="y2m_-ackd"/><stop offset="1" class="ua1yppbot"/></linearGradient><linearGradient id="iYSnD8d" x1="8.983" x2="6.444" y1="5.412" y2="6.412" gradientUnits="userSpaceOnUse"><stop class="y2m_-ackd"/><stop offset="1" class="ua1yppbot"/></linearGradient><linearGradient id="ixBZRHd" x1="21.407" x2="13.251" y1="9.036" y2="9.036" gradientUnits="userSpaceOnUse"><stop class="lv37gme0q"/><stop offset="1" class="of-c7c8wd"/></linearGradient><filter id="i1PpfUc" width="29" height="21.15" x="1.96" y="8.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.482353 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7226"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.921569 0 0 0 0 0.945098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7226" result="effect2_innerShadow_18_7226"/></filter><filter id="icmZWKd" width="2.52" height="4.25" x="3.93" y="12.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0196078 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7226"/></filter><filter id="iC9Qkmt" width="2.52" height="4.25" x="25.93" y="12.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0196078 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7226"/></filter><filter id="i3cBfWc" width="6.47" height="10.24" x="12.94" y="19.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0196078 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7226"/></filter><filter id="imv8wdd" width="5.52" height="7.24" x="2.95" y="22.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0196078 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7226"/></filter><filter id="iSESrCd" width="5.51" height="7.24" x="23.94" y="22.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0196078 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7226"/></filter><filter id="ii4zlUg" width="11.888" height="1.05" x="10.635" y="14.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7226" stdDeviation=".175"/></filter><filter id="iMrxFab" width="6.811" height="1.05" x="24.197" y="8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7226" stdDeviation=".175"/></filter><filter id="idCi5bb" width="6.912" height="1.05" x="2.047" y="8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7226" stdDeviation=".175"/></filter><filter id="iGYHXQc" width="3.504" height="4.803" x="27.662" y="3.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7226" stdDeviation=".25"/></filter><filter id="iKAHCIb" width="9" height="5.623" x="14.08" y="6.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7226" stdDeviation=".75"/></filter><filter id="irGs71d" width="3.504" height="4.803" x="5.536" y="3.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7226" stdDeviation=".25"/></filter><filter id="iCAdkjc" width="12.025" height="2.15" x="10.457" y="7.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7226" stdDeviation=".5"/></filter><radialGradient id="i95glyb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.125 2 -2.62046 -6.7149 29.83 5.224)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="i5laf9bnn"/><stop offset="1" class="vb9jg0b5x"/></radialGradient><radialGradient id="ixZxduc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.58067 2.80263 -.57497 -.52943 26.53 2.333)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="ctbh3hb2u"/><stop offset="1" class="njrtiacdb"/></radialGradient><radialGradient id="ieafmgc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.125 2 -2.62046 -6.7149 7.704 5.224)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="i5laf9bnn"/><stop offset="1" class="vb9jg0b5x"/></radialGradient><radialGradient id="iDBUv1B" cx="0" cy="0" r="1" gradientTransform="matrix(-2.58067 2.80263 -.57497 -.52943 4.404 2.333)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="ctbh3hb2u"/><stop offset="1" class="njrtiacdb"/></radialGradient><radialGradient id="iatW4xe" cx="0" cy="0" r="1" gradientTransform="matrix(-.68761 14.12497 -3.296 -.16045 9.268 10.662)" gradientUnits="userSpaceOnUse"><stop offset=".119" class="louiir_5t"/><stop offset="1" class="e1vy16bpd"/></radialGradient><radialGradient id="iBWOAgc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 5.00001 -2.10193 -2.46976 28.611 6.662)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="u_i1t5bry"/><stop offset="1" class="vi11q7b1l"/></radialGradient><radialGradient id="iPY71dc" cx="0" cy="0" r="1" gradientTransform="rotate(146.31 2.5 4.564)scale(7.09843 2.98408)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="u_i1t5bry"/><stop offset="1" class="vi11q7b1l"/></radialGradient><radialGradient id="iFDp7Cb" cx="0" cy="0" r="1" gradientTransform="rotate(166.065 7.666 7.933)scale(8.56455 3.65242)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="u_i1t5bry"/><stop offset="1" class="vi11q7b1l"/></radialGradient><radialGradient id="imk2LBc" cx="0" cy="0" r="1" gradientTransform="rotate(134.326 6.574 5.577)scale(2.81757 1.52718)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="kt82o6e0b"/><stop offset="1" class="ndmsdabhq"/></radialGradient><radialGradient id="iApVcId" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.57469 7.6415 0 16.47 14.861)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="e06pmbclu"/><stop offset="1" class="g-hza0j1o"/></radialGradient><radialGradient id="izUo80c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.25 -1.4375 0 22.861 9.85)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="tei94jbui"/><stop offset="1" class="qb1230bzy"/></radialGradient><radialGradient id="iWH9vbc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.65455 0 0 -.5616 21.29 9.036)" gradientUnits="userSpaceOnUse"><stop offset=".069" class="st3nqfbuf"/><stop offset="1" class="mua8o9m8m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mosque" /></template>
<style>
.a65m14nmn {
  stop-color: var(--svg-color--673f38, #673F38);
  stop-opacity: 0;
}

.b-tsujbar {
  d: path("M30.307 7.636c1.066-1.316-.526-3.312-1.053-3.803l.275.862a1 1 0 0 1-.382 1.125l-.985.684h1.097c.467 0 .873.323.975.779c.038.169.065.3.073.353");
}

.b53so-ben {
  d: path("M30.95 6.55c0 1.88-1.57 3.41-3.5 3.41s-3.5-1.53-3.5-3.41s2.9-4.56 3.51-4.55c.56-.02 3.49 2.66 3.49 4.55");
}

.bb3393bce {
  stop-color: var(--svg-color--1d112b, #1D112B);
}

.bzbflbc1n {
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M24.547 8.525h6.111");
}

.c0snqvuhx {
  stop-color: var(--svg-color--332347, #332347);
}

.ctbh3hb2u {
  stop-color: var(--svg-color--c99055, #C99055);
}

.cxj9w1svw {
  stop-color: var(--svg-color--4d2b55, #4D2B55);
  stop-opacity: 0;
}

.d3quornkc {
  d: path("M6.44 16.03H4.43l.01-2.34c0-.55.67-1.66 1-1.66c.34 0 1.01 1.12 1.01 1.67z");
}

.deq_o8bbe {
  stop-color: var(--svg-color--8e6962, #8E6962);
  stop-opacity: 0;
}

.dxs2u4bkb {
  d: path("M30.41 9.02h-5.89a.49.49 0 0 1-.49-.49v-.01c0-.27.22-.49.49-.49h5.89c.27 0 .49.22.49.49v.01c0 .27-.22.49-.49.49");
}

.e06pmbclu {
  stop-color: var(--svg-color--744416, #744416);
}

.e1vy16bpd {
  stop-color: var(--svg-color--aca2ae, #ACA2AE);
  stop-opacity: 0;
}

.e9o53jb8s {
  d: path("M8.47 26.02c0-1.37-1.03-4.01-2.54-3.99c-1.46-.02-2.48 2.6-2.48 3.97l.01 3.01h.98v.01h4z");
}

.f1vmx30mm {
  d: path("M8.824 6.55c0 1.88-1.57 3.41-3.5 3.41s-3.5-1.53-3.5-3.41s2.9-4.56 3.51-4.55c.56-.02 3.49 2.66 3.49 4.55");
}

.ffb59jj-e {
  stop-color: var(--svg-color--512953, #512953);
  stop-opacity: 0;
}

.foj016edh {
  stop-color: var(--svg-color--c77047, #C77047);
}

.ft5dv1b6b {
  fill: none;
}

.g-hza0j1o {
  stop-color: var(--svg-color--744416, #744416);
  stop-opacity: 0;
}

.gevqk-coj {
  stop-color: var(--svg-color--cec5d4, #CEC5D4);
}

.gy_cffs1h {
  stop-color: var(--svg-color--845b52, #845B52);
}

.h762a0bxd {
  d: path("M29.45 26.02c0-1.37-1.02-4.01-2.53-3.99c-1.45-.02-2.47 2.6-2.47 3.97l-.01 3.02h4.98z");
}

.ht5mvpbtp {
  stop-color: var(--svg-color--fdc939, #FDC939);
}

.hvq_a3foa {
  d: path("M8.18 7.636c1.066-1.316-.526-3.312-1.052-3.803l.275.862a1 1 0 0 1-.382 1.125l-.985.684h1.096a1 1 0 0 1 .976.779c.037.169.065.3.073.353");
}

.i5laf9bnn {
  stop-color: var(--svg-color--febb4a, #FEBB4A);
}

.i6jb1_zqm {
  stop-color: var(--svg-color--45244f, #45244F);
}

.j2uxz-b9j {
  stop-color: var(--svg-color--371d42, #371D42);
}

.jg_4avb4m {
  d: path("M28.44 16.03h-2.01l.01-2.34c0-.55.67-1.66 1-1.66c.34 0 1.01 1.12 1.01 1.67z");
}

.kt82o6e0b {
  stop-color: var(--svg-color--bb8a5d, #BB8A5D);
}

.louiir_5t {
  stop-color: var(--svg-color--aca2ae, #ACA2AE);
}

.lv37gme0q {
  stop-color: var(--svg-color--ffdf6b, #FFDF6B);
}

.mua8o9m8m {
  stop-color: var(--svg-color--ffe262, #FFE262);
  stop-opacity: 0;
}

.n611c2b-a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M11.532 9.036h9.875");
}

.ndmsdabhq {
  stop-color: var(--svg-color--bb8a5d, #BB8A5D);
  stop-opacity: 0;
}

.nicusyj3q {
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M10.985 14.537h11.189");
}

.njrtiacdb {
  stop-color: var(--svg-color--c99055, #C99055);
  stop-opacity: 0;
}

.o-4e8gwlc {
  stop-color: var(--svg-color--3c1a3f, #3C1A3F);
}

.of-c7c8wd {
  stop-color: var(--svg-color--ef9b4c, #EF9B4C);
}

.oon63-kza {
  stop-color: var(--svg-color--4d2b55, #4D2B55);
}

.pm_a5g9kk {
  stop-color: var(--svg-color--673f38, #673F38);
}

.qb1230bzy {
  stop-color: var(--svg-color--b8964b, #B8964B);
  stop-opacity: 0;
}

.rzj_sxbux {
  stop-color: var(--svg-color--baafbe, #BAAFBE);
}

.s8gpdxbze {
  cx: 18.58px;
  cy: 9.036px;
  rx: 3px;
  ry: 1.312px;
}

.st3nqfbuf {
  stop-color: var(--svg-color--ffe262, #FFE262);
}

.t_y8spp0w {
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M2.397 8.525H8.61");
}

.t0_vb0b-l {
  stop-color: var(--svg-color--512953, #512953);
}

.t6b7jmb8v {
  d: path("M8.39 9.02H2.5a.49.49 0 0 1-.49-.49v-.01c0-.27.22-.49.49-.49h5.89c.27 0 .49.22.49.49v.01c.01.27-.21.49-.49.49");
}

.t9uecpb_t {
  stop-color: var(--svg-color--8e6962, #8E6962);
}

.tei94jbui {
  stop-color: var(--svg-color--b8964b, #B8964B);
}

.trlqtr3kv {
  stop-color: var(--svg-color--6e3f3f, #6E3F3F);
}

.u_i1t5bry {
  stop-color: var(--svg-color--766173, #766173);
}

.ua1yppbot {
  stop-color: var(--svg-color--ffed67, #FFED67);
  stop-opacity: 0;
}

.utkqq-1vm {
  d: path("M24.46 9.05v7c0 .54-.44.98-.99.98h-1.02c-.55 0-.99-.44-.99-.98V14.8h-10v1.25c0 .54-.44.99-.99.99h-1c-.55 0-.99-.44-.99-.98V8.87c0-.41-.34-.74-.75-.74H3.21c-.41 0-.75.33-.75.74v20.16h28V9.06c0-.54-.44-.98-.99-.98h-4.02a.97.97 0 0 0-.99.97");
}

.v2ba7hjem {
  stop-color: var(--svg-color--78482c, #78482C);
}

.v52ofib4o {
  stop-color: var(--svg-color--4c204c, #4C204C);
}

.vacseh2iy {
  width: 11.991px;
  height: 1.003px;
  x: 10.509px;
  y: 14.159px;
  rx: 0.502px;
}

.vb9jg0b5x {
  stop-color: var(--svg-color--c86b37, #C86B37);
}

.vi11q7b1l {
  stop-color: var(--svg-color--766173, #766173);
  stop-opacity: 0;
}

.x7qgcwd4r {
  stop-color: var(--svg-color--7b5951, #7B5951);
}

.xnmca801k {
  d: path("M16.4 19.03c-.99.02-2.95 2.6-2.95 3.97l-.01 6.02h5.97v-6c.01-1.36-1.99-3.98-3.01-3.99");
}

.y2m_-ackd {
  stop-color: var(--svg-color--ffed67, #FFED67);
}

.yrxbrciiu {
  d: path("M16.414 4.208a.58.58 0 0 0-.475.278c-.629.958-2.103 1.814-3.261 2.486q-.309.178-.579.339c-.977.585-1.66 1.47-1.66 2.61v2.238a2 2 0 0 0 2 2h8.06a2 2 0 0 0 2-2V9.92c0-1.14-.681-2.025-1.659-2.61q-.268-.16-.579-.34c-1.157-.67-2.632-1.527-3.26-2.485a.58.58 0 0 0-.476-.278z");
}

.zimffnu2h {
  stop-color: var(--svg-color--3f1c41, #3F1C41);
}

</style>
