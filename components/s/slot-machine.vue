<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iK5TJ8b)" class="ej--kigpy"/><path fill="url(#iiGq2uc)" class="xujadw5yq"/><path fill="url(#i7H93ee)" class="xujadw5yq"/><path fill="url(#i7Z0T0T)" class="xujadw5yq"/><path fill="url(#iYNNyZb)" class="bao-28bor"/><path fill="url(#i4UBvwe)" class="bao-28bor"/><path fill="url(#iYjJQbe)" class="bao-28bor"/><path class="th4wgnzka"/><path fill="url(#ic44a3c)" class="ki4vx9b_o"/><path fill="url(#ioGVUcU)" class="ki4vx9b_o"/><path fill="url(#i9n1Vlz)" class="ki4vx9b_o"/><path fill="url(#iFjXEve)" class="ki4vx9b_o"/><path fill="url(#iL0B9Dd)" class="ki4vx9b_o"/><path fill="url(#iOhUeTb)" class="ki4vx9b_o"/><path class="jifcfwb4d"/><path fill="url(#iXb6eLb)" class="vm-tdqbhu"/><path fill="url(#iWz26kc)" class="vm-tdqbhu"/><path fill="url(#i1H0bWc)" class="vm-tdqbhu"/><g filter="url(#ipkxrTa)"><path fill="url(#iA8eyxU)" class="vjyey-bjh"/></g><rect fill="url(#in3mltd)" class="q3l761b8o"/><rect fill="url(#ii4pcFb)" class="q3l761b8o"/><rect fill="url(#iB7PDHc)" class="q3l761b8o"/><rect fill="url(#i6YdGgH)" class="q3l761b8o"/><g filter="url(#iVwYrkc)"><rect class="v9i9x3_9g"/></g><g filter="url(#iMaeA9c)"><rect class="tbi0tbmwv"/></g><g filter="url(#iRDYOlc)"><rect class="qh523x3ey"/></g><g filter="url(#iIdObJd)"><rect fill="url(#i3FIl0d)" class="banz_gfmi"/></g><rect fill="url(#i1cH1de)" class="banz_gfmi"/><rect fill="url(#ij1SZgb)" class="banz_gfmi"/><g filter="url(#iygiP4b)"><rect fill="url(#iJPA6Ac)" class="kt70v3b2v"/></g><rect fill="url(#iyyDeXc)" class="kt70v3b2v"/><rect fill="url(#iRLMnhc)" class="kt70v3b2v"/><g filter="url(#iiAZFsd)"><rect fill="url(#iZqJjJD)" class="l2tcl0clu"/></g><rect fill="url(#iiYsZHc)" class="l2tcl0clu"/><rect fill="url(#ibk5IQb)" class="l2tcl0clu"/><path fill="url(#i9oZeie)" class="v1no0l_id"/><path fill="url(#iLVRh7c)" class="vd-scqbki"/><path fill="url(#i7rD2Zb)" class="a0w47eb2z"/><path fill="url(#ikSjcfe)" class="z8e371foh"/><path fill="url(#iHftK2b)" class="ga-1bgbmx"/><path fill="url(#i8gxt2c)" class="wl0c17xjq"/><path fill="url(#iSLceze)" clip-rule="evenodd" class="a93vr8bhp"/><path fill="url(#i2Zl8Jd)" clip-rule="evenodd" class="co60uvbig"/><path fill="url(#idPPb5d)" clip-rule="evenodd" class="nzcjcyg6p"/><circle fill="url(#ioCiP8b)" class="nf6gwsb4o"/><circle fill="url(#iEUS7Ie)" class="nf6gwsb4o"/><defs><linearGradient id="iK5TJ8b" x1="28.105" x2="28.858" y1="11.165" y2="11.165" gradientUnits="userSpaceOnUse"><stop class="jmhwfhw8h"/><stop offset="1" class="d6tqwnx_z"/></linearGradient><linearGradient id="iiGq2uc" x1="28.512" x2="28.512" y1="13.734" y2="18.891" gradientUnits="userSpaceOnUse"><stop class="rp89rzbku"/><stop offset="1" class="s1blbdcmr"/></linearGradient><linearGradient id="i7H93ee" x1="28.683" x2="28.683" y1="19.188" y2="18.313" gradientUnits="userSpaceOnUse"><stop class="ma2-e7o5e"/><stop offset="1" class="c8s5kenya"/></linearGradient><linearGradient id="iYNNyZb" x1="26.371" x2="26.371" y1="12.406" y2="19.844" gradientUnits="userSpaceOnUse"><stop class="an7ekthzq"/><stop offset="1" class="vcxzl8_5l"/></linearGradient><linearGradient id="iYjJQbe" x1="26.492" x2="26.492" y1="20.272" y2="19.01" gradientUnits="userSpaceOnUse"><stop class="ma2-e7o5e"/><stop offset="1" class="c8s5kenya"/></linearGradient><linearGradient id="ioGVUcU" x1="14.496" x2="14.496" y1="30.469" y2="27.344" gradientUnits="userSpaceOnUse"><stop class="y_tbxibuc"/><stop offset="1" class="f0867wbae"/></linearGradient><linearGradient id="iL0B9Dd" x1="14.183" x2="14.183" y1="5.589" y2="6.954" gradientUnits="userSpaceOnUse"><stop class="lcmap-bqc"/><stop offset="1" class="t8w4sfhjq"/></linearGradient><linearGradient id="iA8eyxU" x1="19.621" x2="5.746" y1="26.156" y2="26.156" gradientUnits="userSpaceOnUse"><stop class="h8mvwcbtf"/><stop offset="1" class="m56_bd-xu"/></linearGradient><linearGradient id="in3mltd" x1="14.215" x2="14.215" y1="12.781" y2="22.016" gradientUnits="userSpaceOnUse"><stop class="hbw9zdysu"/><stop offset="1" class="cdxxlr5xf"/></linearGradient><linearGradient id="i3FIl0d" x1="7.418" x2="7.418" y1="12.313" y2="18.969" gradientUnits="userSpaceOnUse"><stop class="s8ha6h6fo"/><stop offset=".343" class="x8dw-wbjj"/><stop offset=".592" class="x8dw-wbjj"/><stop offset="1" class="vrju4bhom"/></linearGradient><linearGradient id="ij1SZgb" x1="3.871" x2="5.746" y1="17.438" y2="17.438" gradientUnits="userSpaceOnUse"><stop class="iqb1i1b2e"/><stop offset="1" class="d268hqbnf"/></linearGradient><linearGradient id="iJPA6Ac" x1="14.183" x2="14.183" y1="12.313" y2="18.969" gradientUnits="userSpaceOnUse"><stop class="s8ha6h6fo"/><stop offset=".343" class="x8dw-wbjj"/><stop offset=".592" class="x8dw-wbjj"/><stop offset="1" class="vrju4bhom"/></linearGradient><linearGradient id="iRLMnhc" x1="10.636" x2="12.511" y1="17.438" y2="17.438" gradientUnits="userSpaceOnUse"><stop class="iqb1i1b2e"/><stop offset="1" class="d268hqbnf"/></linearGradient><linearGradient id="iZqJjJD" x1="20.949" x2="20.949" y1="12.313" y2="18.969" gradientUnits="userSpaceOnUse"><stop class="s8ha6h6fo"/><stop offset=".343" class="x8dw-wbjj"/><stop offset=".592" class="x8dw-wbjj"/><stop offset="1" class="vrju4bhom"/></linearGradient><linearGradient id="ibk5IQb" x1="17.402" x2="19.277" y1="17.438" y2="17.438" gradientUnits="userSpaceOnUse"><stop class="iqb1i1b2e"/><stop offset="1" class="d268hqbnf"/></linearGradient><linearGradient id="i9oZeie" x1="7.418" x2="7.418" y1="12.047" y2="12.813" gradientUnits="userSpaceOnUse"><stop class="clz5hpmij"/><stop offset="1" class="zr8x_ebay"/></linearGradient><linearGradient id="iLVRh7c" x1="14.183" x2="14.183" y1="12.047" y2="12.813" gradientUnits="userSpaceOnUse"><stop class="clz5hpmij"/><stop offset="1" class="zr8x_ebay"/></linearGradient><linearGradient id="i7rD2Zb" x1="20.949" x2="20.949" y1="12.047" y2="12.813" gradientUnits="userSpaceOnUse"><stop class="clz5hpmij"/><stop offset="1" class="zr8x_ebay"/></linearGradient><linearGradient id="ikSjcfe" x1="7.355" x2="7.371" y1="21.117" y2="19.914" gradientUnits="userSpaceOnUse"><stop class="qw2r0zbrj"/><stop offset="1" class="jr6n91bky"/></linearGradient><linearGradient id="iHftK2b" x1="14.121" x2="14.136" y1="21.117" y2="19.914" gradientUnits="userSpaceOnUse"><stop class="qw2r0zbrj"/><stop offset="1" class="jr6n91bky"/></linearGradient><linearGradient id="i8gxt2c" x1="20.886" x2="20.902" y1="21.117" y2="19.914" gradientUnits="userSpaceOnUse"><stop class="qw2r0zbrj"/><stop offset="1" class="jr6n91bky"/></linearGradient><linearGradient id="iSLceze" x1="7.365" x2="7.365" y1="14.719" y2="18.594" gradientUnits="userSpaceOnUse"><stop class="gvz8xfb-j"/><stop offset="1" class="gz6o7-b4w"/></linearGradient><linearGradient id="i2Zl8Jd" x1="14.13" x2="14.13" y1="14.719" y2="18.594" gradientUnits="userSpaceOnUse"><stop class="gvz8xfb-j"/><stop offset="1" class="gz6o7-b4w"/></linearGradient><linearGradient id="idPPb5d" x1="20.896" x2="20.896" y1="14.719" y2="18.594" gradientUnits="userSpaceOnUse"><stop class="gvz8xfb-j"/><stop offset="1" class="gz6o7-b4w"/></linearGradient><radialGradient id="i7Z0T0T" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.59191 -.42188 0 30.043 15.844)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="s-bf2y57z"/></radialGradient><radialGradient id="i4UBvwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5 -.45796 0 27.449 14.688)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="s-bf2y57z"/></radialGradient><radialGradient id="ic44a3c" cx="0" cy="0" r="1" gradientTransform="matrix(5.875 0 0 17.189 1.37 17.281)" gradientUnits="userSpaceOnUse"><stop offset=".46" class="kue2qsb6o"/><stop offset="1" class="zesxk5bxb"/></radialGradient><radialGradient id="i9n1Vlz" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.8125 10.1875 0 18.933 31.344)" gradientUnits="userSpaceOnUse"><stop class="y_tbxibuc"/><stop offset="1" class="f0867wbae"/></radialGradient><radialGradient id="iFjXEve" cx="0" cy="0" r="1" gradientTransform="matrix(-3.6875 -6.0625 3.09589 -1.88307 28.12 28.281)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="bp6h_obxn"/><stop offset="1" class="zfhczbcla"/></radialGradient><radialGradient id="iOhUeTb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.89784 2.89784 -1.98102 -1.98102 24.552 7.864)" gradientUnits="userSpaceOnUse"><stop class="wk5nlbbsx"/><stop offset="1" class="kokh1f-ff"/></radialGradient><radialGradient id="iXb6eLb" cx="0" cy="0" r="1" gradientTransform="matrix(5.12524 0 0 10.8125 2.183 17.031)" gradientUnits="userSpaceOnUse"><stop class="qf385907q"/><stop offset="1" class="bx9_ymbxw"/></radialGradient><radialGradient id="iWz26kc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.71875 -4.5827 0 25.496 9.938)" gradientUnits="userSpaceOnUse"><stop class="qm43exjmp"/><stop offset="1" class="zbk31m9xm"/></radialGradient><radialGradient id="i1H0bWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.9375 5.3025 0 25.746 23.906)" gradientUnits="userSpaceOnUse"><stop class="r72xfzb9m"/><stop offset="1" class="tc49b1bbn"/></radialGradient><radialGradient id="ii4pcFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.1875 -4.0625 0 7.465 10.906)" gradientUnits="userSpaceOnUse"><stop class="o9d43bcsm"/><stop offset="1" class="iab4d0rqv"/></radialGradient><radialGradient id="iB7PDHc" cx="0" cy="0" r="1" gradientTransform="scale(4.97855 3.90625)rotate(90 .056 2.8)" gradientUnits="userSpaceOnUse"><stop class="o9d43bcsm"/><stop offset="1" class="iab4d0rqv"/></radialGradient><radialGradient id="i6YdGgH" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.1875 -5.33701 0 21.09 10.531)" gradientUnits="userSpaceOnUse"><stop class="o9d43bcsm"/><stop offset="1" class="iab4d0rqv"/></radialGradient><radialGradient id="i1cH1de" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 0 0 -4.64423 10.465 15.875)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="hzkhwsb_i"/><stop offset="1" class="x1o2c2bqv"/></radialGradient><radialGradient id="iyyDeXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 0 0 -4.64423 17.23 15.875)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="hzkhwsb_i"/><stop offset="1" class="x1o2c2bqv"/></radialGradient><radialGradient id="iiYsZHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 0 0 -4.64423 23.996 15.875)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="hzkhwsb_i"/><stop offset="1" class="x1o2c2bqv"/></radialGradient><radialGradient id="ioCiP8b" cx="0" cy="0" r="1" gradientTransform="rotate(149.036 14.001 7.419)scale(2.58151 2.18807)" gradientUnits="userSpaceOnUse"><stop class="hjopq79sq"/><stop offset="1" class="nu-ciqbzr"/></radialGradient><radialGradient id="iEUS7Ie" cx="0" cy="0" r="1" gradientTransform="rotate(180 14.791 3.531)scale(2.5242)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="pm-tq87ir"/><stop offset="1" class="sk3z55bew"/></radialGradient><filter id="ipkxrTa" width="15.938" height="4.531" x="6.496" y="24.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0431373 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3612"/></filter><filter id="iVwYrkc" width="8.719" height="10.491" x="3.058" y="11.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3612" stdDeviation=".5"/></filter><filter id="iMaeA9c" width="8.719" height="10.491" x="9.771" y="11.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3612" stdDeviation=".5"/></filter><filter id="iRDYOlc" width="8.719" height="10.491" x="16.484" y="11.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3612" stdDeviation=".5"/></filter><filter id="iIdObJd" width="6.094" height="9.094" x="4.371" y="12.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.407843 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.376471 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3612" result="effect2_innerShadow_18_3612"/></filter><filter id="iygiP4b" width="6.094" height="9.094" x="11.136" y="12.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.407843 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.376471 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3612" result="effect2_innerShadow_18_3612"/></filter><filter id="iiAZFsd" width="6.094" height="9.094" x="17.902" y="12.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.407843 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.376471 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3612" result="effect2_innerShadow_18_3612"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:slot-machine" /></template>
<style>
.a0w47eb2z {
  d: path("M20.949 13.477c.643 0 1.164-.522 1.164-1.165h-2.328c0 .643.52 1.165 1.164 1.165");
}

.a93vr8bhp {
  fill-rule: evenodd;
  d: path("M6.683 15.719v.031a.5.5 0 0 1-1 0v-.431a.6.6 0 0 1 .6-.6h2.163a.6.6 0 0 1 .54.861l-1.321 2.731a.5.5 0 1 1-.9-.435l1.043-2.157z");
}

.an7ekthzq {
  stop-color: var(--svg-color--c3c1c4, #C3C1C4);
}

.banz_gfmi {
  width: 6.094px;
  height: 8.594px;
  x: 4.371px;
  y: 12.313px;
  rx: 1px;
}

.bao-28bor {
  d: path("M25.293 12.406h1.556a.6.6 0 0 1 .6.6v6.238a.6.6 0 0 1-.6.6h-1.556z");
}

.bp6h_obxn {
  stop-color: var(--svg-color--cbc4d3, #CBC4D3);
}

.bx9_ymbxw {
  stop-color: var(--svg-color--8a8293, #8A8293);
  stop-opacity: 0;
}

.c8s5kenya {
  stop-color: var(--svg-color--9e80b9, #9E80B9);
  stop-opacity: 0;
}

.cdxxlr5xf {
  stop-color: var(--svg-color--402d56, #402D56);
}

.clz5hpmij {
  stop-color: var(--svg-color--135c9a, #135C9A);
}

.co60uvbig {
  fill-rule: evenodd;
  d: path("M13.449 15.719v.031a.5.5 0 0 1-1 0v-.431a.6.6 0 0 1 .6-.6h2.162a.6.6 0 0 1 .54.861l-1.32 2.731a.5.5 0 1 1-.901-.435l1.043-2.157z");
}

.d268hqbnf {
  stop-color: var(--svg-color--a79eb0, #A79EB0);
  stop-opacity: 0;
}

.d6tqwnx_z {
  stop-color: var(--svg-color--bcb8bf, #BCB8BF);
}

.ej--kigpy {
  d: path("M28.105 7.828h.969v5.906h-.969z");
}

.f0867wbae {
  stop-color: var(--svg-color--a174c7, #A174C7);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ga-1bgbmx {
  d: path("M15.347 20.906a1.164 1.164 0 0 0-2.328 0z");
}

.gvz8xfb-j {
  stop-color: var(--svg-color--f73d4b, #F73D4B);
}

.gz6o7-b4w {
  stop-color: var(--svg-color--e82486, #E82486);
}

.h8mvwcbtf {
  stop-color: var(--svg-color--30154c, #30154C);
}

.hbw9zdysu {
  stop-color: var(--svg-color--4e4b8d, #4E4B8D);
}

.hjopq79sq {
  stop-color: var(--svg-color--ff64a1, #FF64A1);
}

.hzkhwsb_i {
  stop-color: var(--svg-color--f9f2ff, #F9F2FF);
}

.iab4d0rqv {
  stop-color: var(--svg-color--363374, #363374);
  stop-opacity: 0;
}

.iqb1i1b2e {
  stop-color: var(--svg-color--a79eb0, #A79EB0);
}

.jifcfwb4d {
  fill: var(--svg-color--ccc3d9, #CCC3D9);
  d: path("M2.183 23.281V9.938h24V23.28z");
}

.jmhwfhw8h {
  stop-color: var(--svg-color--a09ca3, #A09CA3);
}

.jr6n91bky {
  stop-color: var(--svg-color--d08a39, #D08A39);
}

.ki4vx9b_o {
  d: path("M2.183 8.5a2.75 2.75 0 0 1 2.75-2.75h18.5a2.75 2.75 0 0 1 2.75 2.75V28a2 2 0 0 1-2 2h-20a2 2 0 0 1-2-2z");
}

.kokh1f-ff {
  stop-color: var(--svg-color--d5d4d7, #D5D4D7);
  stop-opacity: 0;
}

.kt70v3b2v {
  width: 6.094px;
  height: 8.594px;
  x: 11.136px;
  y: 12.313px;
  rx: 1px;
}

.kue2qsb6o {
  stop-color: var(--svg-color--817989, #817989);
}

.kzw1yxrkd {
  stop-color: var(--svg-color--d3d0d5, #D3D0D5);
}

.l2tcl0clu {
  width: 6.094px;
  height: 8.594px;
  x: 17.902px;
  y: 12.313px;
  rx: 1px;
}

.lcmap-bqc {
  stop-color: var(--svg-color--adadad, #ADADAD);
}

.m56_bd-xu {
  stop-color: var(--svg-color--1a122d, #1A122D);
}

.ma2-e7o5e {
  stop-color: var(--svg-color--9e80b9, #9E80B9);
}

.nf6gwsb4o {
  cx: 28.59px;
  cy: 7.063px;
  r: 1.531px;
}

.nu-ciqbzr {
  stop-color: var(--svg-color--de2d55, #DE2D55);
}

.nzcjcyg6p {
  fill-rule: evenodd;
  d: path("M20.214 15.719v.031a.5.5 0 0 1-1 0v-.431a.6.6 0 0 1 .6-.6h2.163a.6.6 0 0 1 .54.861l-1.321 2.731a.5.5 0 1 1-.9-.435l1.043-2.157z");
}

.o9d43bcsm {
  stop-color: var(--svg-color--363374, #363374);
}

.pm-tq87ir {
  stop-color: var(--svg-color--bd4245, #BD4245);
  stop-opacity: 0;
}

.q3l761b8o {
  width: 21.625px;
  height: 10.813px;
  x: 3.402px;
  y: 11.203px;
  rx: 1.2px;
}

.qf385907q {
  stop-color: var(--svg-color--8a8293, #8A8293);
}

.qh523x3ey {
  width: 6.719px;
  height: 8.491px;
  x: 17.484px;
  y: 12.696px;
  fill: var(--svg-color--2f212d, #2F212D);
  rx: 1px;
}

.qm43exjmp {
  stop-color: var(--svg-color--efeaf5, #EFEAF5);
}

.qw2r0zbrj {
  stop-color: var(--svg-color--776024, #776024);
}

.r72xfzb9m {
  stop-color: var(--svg-color--ebe4f2, #EBE4F2);
}

.rp89rzbku {
  stop-color: var(--svg-color--bab7b9, #BAB7B9);
}

.s-bf2y57z {
  stop-color: var(--svg-color--d3d0d5, #D3D0D5);
  stop-opacity: 0;
}

.s1blbdcmr {
  stop-color: var(--svg-color--a899b8, #A899B8);
}

.s8ha6h6fo {
  stop-color: var(--svg-color--c7c5ca, #C7C5CA);
}

.sk3z55bew {
  stop-color: var(--svg-color--bd4245, #BD4245);
}

.t8w4sfhjq {
  stop-color: var(--svg-color--adadad, #ADADAD);
  stop-opacity: 0;
}

.tbi0tbmwv {
  width: 6.719px;
  height: 8.491px;
  x: 10.771px;
  y: 12.696px;
  fill: var(--svg-color--2f212d, #2F212D);
  rx: 1px;
}

.tc49b1bbn {
  stop-color: var(--svg-color--ebe4f2, #EBE4F2);
  stop-opacity: 0;
}

.th4wgnzka {
  fill: var(--svg-color--b6b1bb, #B6B1BB);
  d: path("M2.183 8.5a2.75 2.75 0 0 1 2.75-2.75h18.5a2.75 2.75 0 0 1 2.75 2.75V28a2 2 0 0 1-2 2h-20a2 2 0 0 1-2-2z");
}

.v1no0l_id {
  d: path("M7.418 13.477c.643 0 1.164-.522 1.164-1.165H6.254c0 .643.52 1.165 1.164 1.165");
}

.v9i9x3_9g {
  width: 6.719px;
  height: 8.491px;
  x: 4.058px;
  y: 12.696px;
  fill: var(--svg-color--2f212d, #2F212D);
  rx: 1px;
}

.vcxzl8_5l {
  stop-color: var(--svg-color--a596b4, #A596B4);
}

.vd-scqbki {
  d: path("M14.183 13.477c.643 0 1.164-.522 1.164-1.165H13.02c0 .643.521 1.165 1.164 1.165");
}

.vjyey-bjh {
  d: path("M6.496 25.031a.5.5 0 0 1 .5-.5h14.437a.5.5 0 0 1 .5.5v.532a3 3 0 0 1-3 3H9.496a3 3 0 0 1-3-3z");
}

.vm-tdqbhu {
  d: path("M2.183 23.281V9.938h24V23.28z");
}

.vrju4bhom {
  stop-color: var(--svg-color--d5bbef, #D5BBEF);
}

.wk5nlbbsx {
  stop-color: var(--svg-color--d5d4d7, #D5D4D7);
}

.wl0c17xjq {
  d: path("M22.113 20.906a1.164 1.164 0 0 0-2.328 0z");
}

.x1o2c2bqv {
  stop-color: var(--svg-color--f9f2ff, #F9F2FF);
  stop-opacity: 0;
}

.x8dw-wbjj {
  stop-color: var(--svg-color--e7dff0, #E7DFF0);
}

.xujadw5yq {
  d: path("M26.98 13.734h2.563a.5.5 0 0 1 .5.5v4.157a.5.5 0 0 1-.5.5H26.98z");
}

.y_tbxibuc {
  stop-color: var(--svg-color--a174c7, #A174C7);
}

.z8e371foh {
  d: path("M8.582 20.906a1.164 1.164 0 0 0-2.328 0z");
}

.zbk31m9xm {
  stop-color: var(--svg-color--efeaf5, #EFEAF5);
  stop-opacity: 0;
}

.zesxk5bxb {
  stop-color: var(--svg-color--817989, #817989);
  stop-opacity: 0;
}

.zfhczbcla {
  stop-color: var(--svg-color--cbc4d3, #CBC4D3);
  stop-opacity: 0;
}

.zr8x_ebay {
  stop-color: var(--svg-color--149de6, #149DE6);
}

</style>
