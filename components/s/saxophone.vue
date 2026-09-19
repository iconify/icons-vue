<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iz8BAbc)"><path fill="url(#iDqh26c)" class="rp7maqmic"/><path fill="url(#izghBuC)" class="rp7maqmic"/></g><g filter="url(#iUxf1bb)"><circle fill="url(#i3VxFZc)" class="eg7vccegn"/><circle fill="url(#i4sCWAP)" class="eg7vccegn"/><circle fill="url(#iiXrIMe)" class="eg7vccegn"/></g><g filter="url(#iRk9njc)"><circle fill="url(#i83XHhc)" class="r5-igrxvm"/><circle fill="url(#ikaU2Qc)" class="r5-igrxvm"/><circle fill="url(#iDpTOVc)" class="r5-igrxvm"/></g><g filter="url(#iuCJPoe)"><circle fill="url(#iIXvnce)" class="snp1rhgnt"/><circle fill="url(#iZUtPCb)" class="snp1rhgnt"/><circle fill="url(#iiaZqse)" class="snp1rhgnt"/></g><path class="ifva0mgpq"/><path fill="url(#ixGHdbc)" class="nczy6pd9d"/><path fill="url(#i4b6Cpd)" class="nczy6pd9d"/><path fill="url(#i2LXjKV)" class="x2o07ob7z"/><path fill="url(#iWV9Xlc)" class="x2o07ob7z"/><g filter="url(#ipWK6LR)"><path fill="url(#i35E4xb)" class="ff6tdcclz"/></g><g filter="url(#iP1iAVb)"><path fill="url(#ikqrs7d)" class="ce6n26bqw"/><path fill="url(#iOZBMMc)" class="ce6n26bqw"/><path fill="url(#iw8Fr7c)" class="ce6n26bqw"/><path fill="url(#iLluKDc)" class="ce6n26bqw"/></g><g filter="url(#imwPc6c)"><path fill="url(#id7NtPe)" class="mzx-8cbor"/></g><defs><radialGradient id="izghBuC" cx="0" cy="0" r="1" gradientTransform="matrix(1.00004 12.81253 -6.07912 .47449 14.812 13.585)" gradientUnits="userSpaceOnUse"><stop class="i45twfitp"/><stop offset=".762" class="p-l4ao7ru"/><stop offset="1" class="vd988kbvj"/></radialGradient><radialGradient id="i3VxFZc" cx="0" cy="0" r="1" gradientTransform="matrix(.39844 -1.70312 2.0303 .47498 15.07 12.225)" gradientUnits="userSpaceOnUse"><stop class="fb_nn0lbo"/><stop offset="1" class="acwy_yb8z"/></radialGradient><radialGradient id="i4sCWAP" cx="0" cy="0" r="1" gradientTransform="rotate(-159.274 8.858 4.334)scale(1.85438 1.54532)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="temd9acge"/><stop offset="1" class="aw4202b8k"/></radialGradient><radialGradient id="iiXrIMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 .29687 -.31562 -.89705 15.812 10.975)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="g5ci82brk"/><stop offset="1" class="cst_tfahq"/></radialGradient><radialGradient id="i83XHhc" cx="0" cy="0" r="1" gradientTransform="matrix(.39844 -1.70312 2.0303 .47498 15.305 8.756)" gradientUnits="userSpaceOnUse"><stop class="fb_nn0lbo"/><stop offset="1" class="acwy_yb8z"/></radialGradient><radialGradient id="ikaU2Qc" cx="0" cy="0" r="1" gradientTransform="rotate(-159.274 8.658 2.578)scale(1.85438 1.54532)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="temd9acge"/><stop offset="1" class="aw4202b8k"/></radialGradient><radialGradient id="iDpTOVc" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 .29687 -.31562 -.89705 16.046 7.506)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="g5ci82brk"/><stop offset="1" class="cst_tfahq"/></radialGradient><radialGradient id="iIXvnce" cx="0" cy="0" r="1" gradientTransform="matrix(.39844 -1.70312 2.0303 .47498 16.633 5.936)" gradientUnits="userSpaceOnUse"><stop class="fb_nn0lbo"/><stop offset="1" class="acwy_yb8z"/></radialGradient><radialGradient id="iZUtPCb" cx="0" cy="0" r="1" gradientTransform="rotate(-159.274 9.064 1.046)scale(1.85438 1.54532)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="temd9acge"/><stop offset="1" class="aw4202b8k"/></radialGradient><radialGradient id="iiaZqse" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 .29687 -.31562 -.89705 17.374 4.687)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="g5ci82brk"/><stop offset="1" class="cst_tfahq"/></radialGradient><radialGradient id="iWV9Xlc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.53295 .21877 -.02826 -.8439 29.595 3.178)" gradientUnits="userSpaceOnUse"><stop class="dwh48tz1p"/><stop offset="1" class="b5_53rm9x"/></radialGradient><radialGradient id="iOZBMMc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.9375 1.71874 -.43286 -1.2435 11.25 14.146)" gradientUnits="userSpaceOnUse"><stop class="c9qjkr9lh"/><stop offset="1" class="cuh_l7bfn"/></radialGradient><radialGradient id="iw8Fr7c" cx="0" cy="0" r="1" gradientTransform="matrix(-7.3125 -.6875 .83687 -8.90129 8.688 17.209)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="a9ed7p-ej"/><stop offset=".955" class="d_ps2o_xs"/></radialGradient><radialGradient id="iLluKDc" cx="0" cy="0" r="1" gradientTransform="matrix(5.2669 -2 .49907 1.31427 2.014 16.115)" gradientUnits="userSpaceOnUse"><stop class="z7o7m3bpm"/><stop offset="1" class="o5klo7zsf"/></radialGradient><linearGradient id="iDqh26c" x1="10.938" x2="24.813" y1="25.709" y2="6.897" gradientUnits="userSpaceOnUse"><stop class="yrie72uvk"/><stop offset="1" class="fzx7zkzps"/></linearGradient><linearGradient id="ixGHdbc" x1="24.078" x2="23.891" y1="5.506" y2="3.82" gradientUnits="userSpaceOnUse"><stop class="ve6cg52gh"/><stop offset="1" class="xmv2ezdmp"/></linearGradient><linearGradient id="i4b6Cpd" x1="23.531" x2="23.594" y1="2.047" y2="2.818" gradientUnits="userSpaceOnUse"><stop class="us_9e2s-g"/><stop offset="1" class="vtddx6tbu"/></linearGradient><linearGradient id="i2LXjKV" x1="29.313" x2="24.163" y1="4.115" y2="4.49" gradientUnits="userSpaceOnUse"><stop class="p39rjtc5t"/><stop offset="1" class="texvaoe5e"/></linearGradient><linearGradient id="i35E4xb" x1="9.75" x2="18.091" y1="12.021" y2="25.769" gradientUnits="userSpaceOnUse"><stop class="spzv7b71s"/><stop offset="1" class="zr7-kvq9y"/></linearGradient><linearGradient id="ikqrs7d" x1="12.313" x2="3.063" y1="12.521" y2="19.146" gradientUnits="userSpaceOnUse"><stop class="aapeelcoy"/><stop offset="1" class="vnzqdt9vu"/></linearGradient><linearGradient id="id7NtPe" x1="16" x2="21.313" y1="30.959" y2="3.084" gradientUnits="userSpaceOnUse"><stop class="spzv7b71s"/><stop offset="1" class="zr7-kvq9y"/></linearGradient><filter id="iz8BAbc" width="26.183" height="28.405" x="4.063" y="1.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.498039 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18496"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".45"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.741176 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18496" result="effect2_innerShadow_18_18496"/></filter><filter id="iUxf1bb" width="2.172" height="2.172" x="13.984" y="10.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.65098 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18496"/></filter><filter id="iRk9njc" width="2.172" height="2.172" x="14.219" y="6.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.65098 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18496"/></filter><filter id="iuCJPoe" width="2.172" height="2.172" x="15.547" y="3.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.65098 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18496"/></filter><filter id="ipWK6LR" width="9.5" height="14.625" x="6.281" y="12.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18496" stdDeviation="1"/></filter><filter id="iP1iAVb" width="12.523" height="6.419" x="1.814" y="12.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.72549 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18496"/></filter><filter id="imwPc6c" width="9.313" height="25.906" x="14.5" y="2.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18496" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:saxophone" /></template>
<style>
.a9ed7p-ej {
  stop-color: var(--svg-color--e8d99d, #E8D99D);
  stop-opacity: 0;
}

.aapeelcoy {
  stop-color: var(--svg-color--dbc733, #DBC733);
}

.acwy_yb8z {
  stop-color: var(--svg-color--b8acbb, #B8ACBB);
}

.aw4202b8k {
  stop-color: var(--svg-color--cfc9cc, #CFC9CC);
}

.b5_53rm9x {
  stop-color: var(--svg-color--5e5864, #5E5864);
  stop-opacity: 0;
}

.c9qjkr9lh {
  stop-color: var(--svg-color--f0dd6a, #F0DD6A);
}

.ce6n26bqw {
  d: path("M2.097 17.459a1.38 1.38 0 0 1 .829-1.768l9.56-3.458a1.38 1.38 0 0 1 .94 2.597l-9.56 3.458a1.38 1.38 0 0 1-1.769-.83");
}

.cst_tfahq {
  stop-color: var(--svg-color--bcaec1, #BCAEC1);
  stop-opacity: 0;
}

.cuh_l7bfn {
  stop-color: var(--svg-color--dac537, #DAC537);
  stop-opacity: 0;
}

.d_ps2o_xs {
  stop-color: var(--svg-color--e8d99d, #E8D99D);
}

.dwh48tz1p {
  stop-color: var(--svg-color--5e5864, #5E5864);
}

.eg7vccegn {
  cx: 15.07px;
  cy: 11.271px;
  r: 1.086px;
}

.fb_nn0lbo {
  stop-color: var(--svg-color--bca6be, #BCA6BE);
}

.ff6tdcclz {
  d: path("m12.875 25.022l-4.594-8.75l4.375-1.875l1.125 7.093z");
}

.ft5dv1b6b {
  fill: none;
}

.fzx7zkzps {
  stop-color: var(--svg-color--d8a534, #D8A534);
}

.g5ci82brk {
  stop-color: var(--svg-color--d3c9d5, #D3C9D5);
}

.i45twfitp {
  stop-color: var(--svg-color--dfa61b, #DFA61B);
}

.ifva0mgpq {
  fill: var(--svg-color--c3b9cc, #C3B9CC);
  d: path("M23.215 5.592c.457-.095.97-.19 1.55-.297l.965-.147c2.76-.418 3.807-.576 3.864-1.478c.057-.911-1.424-1.278-2.207-1.471l-.207-.052c-.552-.103-2.279-.182-4.234.06c.07.714.176 1.928.27 3.385");
}

.mzx-8cbor {
  d: path("M17.563 7.584c.8-2.9 3.5-3.73 4.75-3.781v.562c-2.125.313-3.657 1.438-4.032 3.594c-.75 3.75 0 8.219 0 12.781c0 3.65-.708 5.5-1.062 5.969L16 23.803c.26-.344.806-1.313.906-2.438c.125-1.406-.343-10.156.657-13.781");
}

.nczy6pd9d {
  d: path("M23.215 5.592c.457-.095.97-.19 1.55-.297l.965-.147c2.76-.418 3.807-.576 3.864-1.478c.057-.911-1.424-1.278-2.207-1.471l-.207-.052c-.552-.103-2.279-.182-4.234.06c.07.714.176 1.928.27 3.385");
}

.o5klo7zsf {
  stop-color: var(--svg-color--c8ae3d, #C8AE3D);
  stop-opacity: 0;
}

.p-l4ao7ru {
  stop-color: var(--svg-color--dfa61b, #DFA61B);
  stop-opacity: 0.896;
}

.p39rjtc5t {
  stop-color: var(--svg-color--4a4351, #4A4351);
}

.r5-igrxvm {
  cx: 15.305px;
  cy: 7.803px;
  r: 1.086px;
}

.rp7maqmic {
  d: path("m7.688 25.453l-3.625-7.656l9.203-3.703l.683 5.856a.499.499 0 0 0 .994-.06l-.037-6.64c-.057-2.02.247-6.565 1.922-8.578c2.703-2.854 9.18-2.744 10.352-2.525c.687.18 2.476.523 2.414 1.523c-.063 1-1.344 1.086-4.828 1.625c-2.97.547-4.18.797-5.055 2.094c-.7 1.037-.857 2.762-.852 3.549c.058 3.182.172 10.01.172 11.86c0 2.312-.086 5.997-4.554 7.028c-3.575.825-6.04-2.591-6.79-4.373");
}

.snp1rhgnt {
  cx: 16.633px;
  cy: 4.982px;
  r: 1.086px;
}

.spzv7b71s {
  stop-color: var(--svg-color--fdcd6b, #FDCD6B);
}

.temd9acge {
  stop-color: var(--svg-color--cfc9cc, #CFC9CC);
  stop-opacity: 0;
}

.texvaoe5e {
  stop-color: var(--svg-color--412856, #412856);
}

.us_9e2s-g {
  stop-color: var(--svg-color--bbb7bd, #BBB7BD);
}

.vd988kbvj {
  stop-color: var(--svg-color--dfa61b, #DFA61B);
  stop-opacity: 0;
}

.ve6cg52gh {
  stop-color: var(--svg-color--ad90c5, #AD90C5);
}

.vnzqdt9vu {
  stop-color: var(--svg-color--c4a147, #C4A147);
}

.vtddx6tbu {
  stop-color: var(--svg-color--bbb7bd, #BBB7BD);
  stop-opacity: 0;
}

.x2o07ob7z {
  d: path("m24.425 5.358l.34-.063l.965-.147c2.76-.418 3.807-.576 3.864-1.478c.062-1-1.524-1.406-2.414-1.523c-.434-.081-1.592-.147-3.017-.054c.069.69.17 1.858.262 3.265");
}

.xmv2ezdmp {
  stop-color: var(--svg-color--ad90c5, #AD90C5);
  stop-opacity: 0;
}

.yrie72uvk {
  stop-color: var(--svg-color--d59f41, #D59F41);
}

.z7o7m3bpm {
  stop-color: var(--svg-color--e6d597, #E6D597);
}

.zr7-kvq9y {
  stop-color: var(--svg-color--fdcd6b, #FDCD6B);
  stop-opacity: 0;
}

</style>
