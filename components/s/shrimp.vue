<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ia7Ieqk)" class="c-pfapb0g"/><path fill="url(#iotbLIc)" class="qg2361bhj"/><path fill="url(#i2XxFob)" class="z7ovgcbon"/><path fill="url(#i4SCz4c)" class="aj0lxkbyu"/><path fill="url(#i7KMmoD)" class="sj063sbzt"/><path fill="url(#i2nuAvd)" class="fuj2tn8tg"/><g filter="url(#iXSgsPn)"><path stroke="url(#iSXmdZb)" class="n56iw0qxs"/></g><path fill="url(#igUJJ5c)" class="ecf-7oy1o"/><g filter="url(#ie1eTmB)"><path stroke="url(#iHSi6Db)" class="hcon2mrkj"/></g><path fill="url(#igrzuAc)" class="xm_5eqbxk"/><path fill="url(#irZFr6c)" class="y1j5i17ae"/><path fill="url(#iOchtId)" class="b6oanpblz"/><path fill="url(#indE8jc)" class="b6oanpblz"/><path fill="url(#ix3qnjb)" class="b6oanpblz"/><path fill="url(#ieOqfSc)" class="b6oanpblz"/><path fill="url(#iZFFvFb)" class="b6oanpblz"/><path fill="url(#ia06aYd)" class="b6oanpblz"/><path fill="url(#iSvBp5c)" class="b6oanpblz"/><g filter="url(#iGtkdYd)"><path stroke="url(#idrXMSb)" class="m0gx6zbvb"/></g><g filter="url(#ixcV2Bd)"><path stroke="url(#iRwmRLe)" class="rodxn0b_k"/></g><g filter="url(#iNzUApX)"><path stroke="url(#iiBtn0B)" class="dm9nhcsnr"/></g><g filter="url(#ivPXNJb)"><path class="ee3q35bvt"/></g><path fill="url(#iJzuzkd)" class="e6mu72b4g"/><path fill="url(#irpclBd)" class="e6mu72b4g"/><path fill="url(#iHHxU6d)" class="e6mu72b4g"/><path fill="url(#ixdDwEd)" class="bs5hwccye"/><path fill="url(#iv4KJJd)" class="bs5hwccye"/><path fill="url(#iAdEJCc)" class="egs03eblm"/><path fill="url(#ijkBBii)" class="egs03eblm"/><path class="u1m9pzotu"/><path fill="url(#ij5e0ed)" class="dbjeo_xez"/><g filter="url(#igqOBID)"><path stroke="url(#iV4K0yc)" class="n0aagpz8v"/></g><g filter="url(#iX23Cjb)"><path stroke="url(#iZKkLxb)" class="najxq7bwq"/></g><g filter="url(#i1Kznbm)"><path stroke="url(#ib1MGMb)" class="is-9reoiu"/></g><g filter="url(#ijhsGgc)"><path stroke="url(#iihOISb)" class="uiom1be2e"/></g><defs><linearGradient id="ia7Ieqk" x1="9.688" x2="29.994" y1="5.741" y2="5.741" gradientUnits="userSpaceOnUse"><stop class="ni0r16bse"/><stop offset=".849" class="rpg8vbclg"/></linearGradient><linearGradient id="iotbLIc" x1="17.534" x2="21.972" y1="20.551" y2="20.551" gradientUnits="userSpaceOnUse"><stop class="jzux2mbrx"/><stop offset="1" class="rjjttlbvo"/></linearGradient><linearGradient id="i2XxFob" x1="19.517" x2="21.938" y1="20.551" y2="20.551" gradientUnits="userSpaceOnUse"><stop class="jm744dbdm"/><stop offset="1" class="vh1wn4bcq"/></linearGradient><linearGradient id="i4SCz4c" x1="17.534" x2="21.972" y1="17.551" y2="17.551" gradientUnits="userSpaceOnUse"><stop class="jzux2mbrx"/><stop offset="1" class="rjjttlbvo"/></linearGradient><linearGradient id="i7KMmoD" x1="19.517" x2="21.938" y1="17.551" y2="17.551" gradientUnits="userSpaceOnUse"><stop class="jm744dbdm"/><stop offset="1" class="vh1wn4bcq"/></linearGradient><linearGradient id="i2nuAvd" x1="6.313" x2="6.313" y1="15.563" y2="19.152" gradientUnits="userSpaceOnUse"><stop class="z6nhqibww"/><stop offset="1" class="wpiwyc_ua"/></linearGradient><linearGradient id="iSXmdZb" x1="7.563" x2="5.719" y1="15.594" y2="18.656" gradientUnits="userSpaceOnUse"><stop offset=".051" class="xeabqocoi"/><stop offset="1" class="y4v9l4baq"/></linearGradient><linearGradient id="igUJJ5c" x1="9.308" x2="9.308" y1="16.172" y2="20.652" gradientUnits="userSpaceOnUse"><stop class="z6nhqibww"/><stop offset=".45" class="wpiwyc_ua"/></linearGradient><linearGradient id="iHSi6Db" x1="10.617" x2="8.594" y1="15.594" y2="20.156" gradientUnits="userSpaceOnUse"><stop offset=".051" class="b7-ipbnwd"/><stop offset="1" class="s-kb6qblb"/></linearGradient><linearGradient id="igrzuAc" x1="12.308" x2="12.308" y1="16.172" y2="20.652" gradientUnits="userSpaceOnUse"><stop class="z6nhqibww"/><stop offset=".45" class="wpiwyc_ua"/></linearGradient><linearGradient id="irZFr6c" x1="15.308" x2="15.308" y1="16.172" y2="20.652" gradientUnits="userSpaceOnUse"><stop class="z6nhqibww"/><stop offset=".45" class="wpiwyc_ua"/></linearGradient><linearGradient id="iOchtId" x1="3.625" x2="29.998" y1="15.313" y2="15.313" gradientUnits="userSpaceOnUse"><stop class="br-tcublg"/><stop offset=".235" class="iry1s_bpg"/><stop offset=".78" class="bcxqkfb-d"/><stop offset="1" class="q6di75j4u"/></linearGradient><linearGradient id="idrXMSb" x1="20.828" x2="20.686" y1="20.113" y2="21.464" gradientUnits="userSpaceOnUse"><stop offset=".051" class="xeabqocoi"/><stop offset=".736" class="mbthmtb5k"/></linearGradient><linearGradient id="iRwmRLe" x1="13.633" x2="11.609" y1="15.594" y2="20.156" gradientUnits="userSpaceOnUse"><stop offset=".051" class="b7-ipbnwd"/><stop offset="1" class="s-kb6qblb"/></linearGradient><linearGradient id="iiBtn0B" x1="16.645" x2="14.622" y1="15.594" y2="20.156" gradientUnits="userSpaceOnUse"><stop offset=".051" class="b7-ipbnwd"/><stop offset="1" class="s-kb6qblb"/></linearGradient><linearGradient id="iJzuzkd" x1="7.518" x2="9.018" y1="11.157" y2="11.157" gradientUnits="userSpaceOnUse"><stop class="zkbdjac-u"/><stop offset=".293" class="mtkhizwsu"/><stop offset=".626" class="g5hcmwqte"/><stop offset="1" class="j_o37lb8k"/></linearGradient><linearGradient id="iV4K0yc" x1="20.828" x2="20.686" y1="17.071" y2="18.421" gradientUnits="userSpaceOnUse"><stop offset=".051" class="xeabqocoi"/><stop offset=".736" class="mbthmtb5k"/></linearGradient><linearGradient id="iZKkLxb" x1="21.125" x2="20.692" y1="17.188" y2="18.28" gradientUnits="userSpaceOnUse"><stop offset=".051" class="xeabqocoi"/><stop offset=".726" class="v1-wjxb4r"/></linearGradient><linearGradient id="ib1MGMb" x1="21.125" x2="20.692" y1="20.245" y2="21.338" gradientUnits="userSpaceOnUse"><stop offset=".051" class="xeabqocoi"/><stop offset=".726" class="v1-wjxb4r"/></linearGradient><linearGradient id="iihOISb" x1="29.719" x2="29.001" y1="3.703" y2="7.317" gradientUnits="userSpaceOnUse"><stop offset=".036" class="f1a0of9xa"/><stop offset=".081" class="n-zdqh5gz"/><stop offset="1" class="u-gpgvb7w"/></linearGradient><radialGradient id="indE8jc" cx="0" cy="0" r="1" gradientTransform="rotate(113.86 8.92 13.774)scale(3.55372 6.79155)" gradientUnits="userSpaceOnUse"><stop class="xaoqkwbsn"/><stop offset="1" class="k6ci_ulvn"/></radialGradient><radialGradient id="ix3qnjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.75 -10.5 0 11.625 15.875)" gradientUnits="userSpaceOnUse"><stop class="t48e9cbqp"/><stop offset="1" class="e6yuwxo6a"/></radialGradient><radialGradient id="ieOqfSc" cx="0" cy="0" r="1" gradientTransform="rotate(90.507 -5.615 7.32)scale(3.53139 3.40695)" gradientUnits="userSpaceOnUse"><stop offset=".246" class="fxj8vd8ii"/><stop offset=".565" class="nd6yk8bxu"/><stop offset=".662" class="tb2x4fa0e"/></radialGradient><radialGradient id="iZFFvFb" cx="0" cy="0" r="1" gradientTransform="rotate(159.775 7.998 13.55)scale(6.32764 3.9692)" gradientUnits="userSpaceOnUse"><stop class="chwl1ccvz"/><stop offset=".557" class="pjo0xc2qo"/><stop offset="1" class="vtsj3ns4l"/></radialGradient><radialGradient id="ia06aYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.625 -15.5222 0 14 8)" gradientUnits="userSpaceOnUse"><stop class="av_3bvcef"/><stop offset=".823" class="vkhjbdbgb"/></radialGradient><radialGradient id="iSvBp5c" cx="0" cy="0" r="1" gradientTransform="rotate(122.296 -1.409 18.084)scale(7.83746 5.05872)" gradientUnits="userSpaceOnUse"><stop class="ecd8wgl9a"/><stop offset=".509" class="qzfy6zdle"/><stop offset=".755" class="gi20eib_s"/><stop offset=".845" class="t84p3dbvu"/><stop offset=".871" class="lyjpj84gm"/></radialGradient><radialGradient id="irpclBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.495 -1.00208 0 8.268 11.157)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="d0trfgwcy"/><stop offset="1" class="m15cacc1v"/></radialGradient><radialGradient id="iHHxU6d" cx="0" cy="0" r="1" gradientTransform="rotate(88.315 -1.068 9.557)scale(.53148 .57764)" gradientUnits="userSpaceOnUse"><stop class="pbl0i9ftj"/><stop offset="1" class="bb2evob4t"/></radialGradient><radialGradient id="ixdDwEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1251 10.5 -16.70328 -1.78978 18.374 15.625)" gradientUnits="userSpaceOnUse"><stop class="varrlsbiv"/><stop offset=".134" class="t_7id5qoj"/><stop offset=".621" class="zhj430b8m"/><stop offset="1" class="wi5biccqk"/></radialGradient><radialGradient id="iv4KJJd" cx="0" cy="0" r="1" gradientTransform="rotate(106.996 8.352 14.306)scale(3.33308 6.02447)" gradientUnits="userSpaceOnUse"><stop class="ju14yzb2x"/><stop offset="1" class="kzl8uityg"/></radialGradient><radialGradient id="iAdEJCc" cx="0" cy="0" r="1" gradientTransform="matrix(9.0625 .625 -.79512 11.52921 21.625 19.375)" gradientUnits="userSpaceOnUse"><stop offset=".05" class="q3627esih"/><stop offset=".183" class="c2jm9_mmj"/><stop offset=".418" class="k90zx_bzc"/><stop offset=".652" class="mdmnal5_l"/><stop offset=".956" class="bcesubcjx"/></radialGradient><radialGradient id="ijkBBii" cx="0" cy="0" r="1" gradientTransform="matrix(.3125 8.75 -2.20279 .07867 27.375 11.75)" gradientUnits="userSpaceOnUse"><stop class="w_ilr5kdc"/><stop offset="1" class="r78eeuw1g"/></radialGradient><radialGradient id="ij5e0ed" cx="0" cy="0" r="1" gradientTransform="rotate(89.076 -3.828 21.456)scale(3.8755 9.77099)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="mcyrh7trb"/><stop offset="1" class="mhbgkbbvg"/></radialGradient><filter id="iXSgsPn" width="2.969" height="3.969" x="5.156" y="15.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28515" stdDeviation=".125"/></filter><filter id="ie1eTmB" width="3.055" height="5.469" x="8.125" y="15.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28515" stdDeviation=".125"/></filter><filter id="iGtkdYd" width="3.891" height="1.866" x="17.516" y="19.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28515" stdDeviation=".125"/></filter><filter id="ixcV2Bd" width="3.055" height="5.469" x="11.141" y="15.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28515" stdDeviation=".125"/></filter><filter id="iNzUApX" width="3.055" height="5.469" x="14.153" y="15.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28515" stdDeviation=".125"/></filter><filter id="ivPXNJb" width="3.5" height="4.99" x="6.258" y="8.88" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28515" stdDeviation=".5"/></filter><filter id="igqOBID" width="3.891" height="1.866" x="17.516" y="16.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28515" stdDeviation=".125"/></filter><filter id="iX23Cjb" width="2.172" height="1.813" x="19.484" y="16.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28515" stdDeviation=".125"/></filter><filter id="i1Kznbm" width="2.172" height="1.813" x="19.484" y="19.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28515" stdDeviation=".125"/></filter><filter id="ijhsGgc" width="19.82" height="3.352" x="10.141" y="3.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28515" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:shrimp" /></template>
<style>
.aj0lxkbyu {
  d: path("M18.038 18.442a.506.506 0 0 1-.47-.67c.24-.67.87-1.12 1.58-1.12h2.33c.28 0 .5.22.5.5s-.22.5-.5.5h-2.33a.67.67 0 0 0-.64.45c-.07.22-.27.34-.47.34");
}

.av_3bvcef {
  stop-color: var(--svg-color--f15844, #F15844);
}

.b6oanpblz {
  d: path("M17.998 5.652h-4.85c-2.05 0-4.06.58-5.8 1.67l-5.02 2.95c-.35.2-.43.67-.18.98l.76.96c.39.48.4 1.16.04 1.67l-.88 1.22c-.17.23 0 .56.29.56h16.13c1.93 0 3.5 1.57 3.5 3.5s-1.57 3.5-3.5 3.5h-2.62a7.37 7.37 0 0 0-6.77 4.46l-.84 1.97c-.11.27.08.56.37.56h9.37c6.63 0 12-5.37 12-12s-5.37-12-12-12");
}

.b7-ipbnwd {
  stop-color: var(--svg-color--fc675f, #FC675F);
  stop-opacity: 0;
}

.bb2evob4t {
  stop-color: var(--svg-color--5c5052, #5C5052);
  stop-opacity: 0;
}

.bcesubcjx {
  stop-color: var(--svg-color--ff8f43, #FF8F43);
}

.bcxqkfb-d {
  stop-color: var(--svg-color--ea4365, #EA4365);
}

.br-tcublg {
  stop-color: var(--svg-color--e05c2f, #E05C2F);
}

.bs5hwccye {
  d: path("M17.998 5.652h-.99c2.11 0 3.34 2.37 2.13 4.09l-4.13 5.91h3.48c.95 0 1.82.38 2.45 1h.07l2.6-3.58c1.85-2.55.6-6.18-2.44-7c-1.01-.27-2.07-.42-3.17-.42");
}

.c-pfapb0g {
  d: path("M7.238 8.482a.52.52 0 0 1-.43-.24a.5.5 0 0 1 .17-.69l4.24-2.59a13.42 13.42 0 0 1 10.51-1.49l2.24.61c1.81.49 3.67.19 5.25-.82a.5.5 0 0 1 .69.15c.16.24.09.55-.14.69c-1.82 1.16-3.97 1.51-6.05.94l-2.24-.61c-3.28-.89-6.83-.39-9.73 1.38l-4.25 2.59c-.08.05-.17.08-.26.08");
}

.c2jm9_mmj {
  stop-color: var(--svg-color--e35a29, #E35A29);
}

.chwl1ccvz {
  stop-color: var(--svg-color--e13b32, #E13B32);
}

.d0trfgwcy {
  stop-color: var(--svg-color--4b2639, #4B2639);
  stop-opacity: 0;
}

.dbjeo_xez {
  d: path("M24.398 27.802c-2.03.67-2.95-.92-2.95-.92l-2.38-4.23h-3.45c-.05 0-.1 0-.15.01c-.03 0-.06 0-.09.01c-.06 0-.13.01-.19.02h-.03c-.07.01-.14.02-.22.02l.14 6.94h2.92c2.36 0 4.55-.68 6.4-1.85");
}

.dm9nhcsnr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.833 15.438s-2.133 2.921-2.22 3.218c-.085.297-.085 1.5-.085 1.5");
}

.e6mu72b4g {
  d: path("M8.268 12.652c-.41 0-.75-.34-.75-.75v-1.49c0-.41.34-.75.75-.75s.75.34.75.75v1.49c-.01.41-.34.75-.75.75");
}

.e6yuwxo6a {
  stop-color: var(--svg-color--e04259, #E04259);
  stop-opacity: 0;
}

.ecd8wgl9a {
  stop-color: var(--svg-color--e74765, #E74765);
}

.ecf-7oy1o {
  d: path("M8.508 20.652c-.28 0-.5-.22-.5-.5v-.7c0-.62.19-1.22.55-1.74l3.04-4.34c.16-.23.47-.28.7-.12s.28.47.12.7l-3.04 4.34c-.24.34-.37.75-.37 1.16v.7c0 .28-.22.5-.5.5");
}

.ee3q35bvt {
  fill: var(--svg-color--ae2616, #AE2616);
  d: path("M8.008 12.87c-.41 0-.75-.34-.75-.75v-1.49c0-.41.34-.75.75-.75s.75.34.75.75v1.49c-.01.41-.34.75-.75.75");
}

.egs03eblm {
  d: path("m26.818 13.832l-5.09 6.67a3.46 3.46 0 0 1-1.09 1.42c-.59.46-1.33.73-2.14.73h6.52c2.74 0 4.98-2.21 4.99-4.95v-.05c0-2.72-.91-5.23-2.43-7.24c-.01 0 .72 1.48-.76 3.42");
}

.f1a0of9xa {
  stop-color: var(--svg-color--f76d8c, #F76D8C);
}

.ft5dv1b6b {
  fill: none;
}

.fuj2tn8tg {
  d: path("M5.518 19.152a.499.499 0 0 1-.41-.79l3.49-5c.16-.23.47-.28.7-.12s.28.47.12.7l-3.49 5c-.1.14-.26.21-.41.21");
}

.fxj8vd8ii {
  stop-color: var(--svg-color--b7503a, #B7503A);
}

.g5hcmwqte {
  stop-color: var(--svg-color--55464d, #55464D);
}

.gi20eib_s {
  stop-color: var(--svg-color--e46451, #E46451);
}

.hcon2mrkj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.805 15.438s-2.133 2.921-2.22 3.218c-.085.297-.085 1.5-.085 1.5");
}

.iry1s_bpg {
  stop-color: var(--svg-color--eb544d, #EB544D);
}

.is-9reoiu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.984 21.058c.094-.27.46-.812 1.172-.812");
}

.j_o37lb8k {
  stop-color: var(--svg-color--583637, #583637);
}

.jm744dbdm {
  stop-color: var(--svg-color--de3d3c, #DE3D3C);
}

.ju14yzb2x {
  stop-color: var(--svg-color--ff9060, #FF9060);
}

.jzux2mbrx {
  stop-color: var(--svg-color--d34126, #D34126);
}

.k6ci_ulvn {
  stop-color: var(--svg-color--ff7486, #FF7486);
  stop-opacity: 0;
}

.k90zx_bzc {
  stop-color: var(--svg-color--ee6434, #EE6434);
}

.kzl8uityg {
  stop-color: var(--svg-color--ff7f4a, #FF7F4A);
  stop-opacity: 0;
}

.lyjpj84gm {
  stop-color: var(--svg-color--dc4d3c, #DC4D3C);
  stop-opacity: 0;
}

.m0gx6zbvb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.016 20.98c.135-.313.506-.847 1.093-.86a60 60 0 0 1 1.797 0");
}

.m15cacc1v {
  stop-color: var(--svg-color--49243b, #49243B);
}

.mbthmtb5k {
  stop-color: var(--svg-color--dc4534, #DC4534);
}

.mcyrh7trb {
  stop-color: var(--svg-color--f77132, #F77132);
}

.mdmnal5_l {
  stop-color: var(--svg-color--ff7b38, #FF7B38);
}

.mhbgkbbvg {
  stop-color: var(--svg-color--ea605a, #EA605A);
}

.mtkhizwsu {
  stop-color: var(--svg-color--402d32, #402D32);
}

.n-zdqh5gz {
  stop-color: var(--svg-color--e33767, #E33767);
}

.n0aagpz8v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.016 17.938c.135-.313.506-.847 1.093-.86a60 60 0 0 1 1.797 0");
}

.n56iw0qxs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m5.531 18.656l2.219-3.218");
}

.najxq7bwq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.984 18c.094-.27.46-.812 1.172-.812");
}

.nd6yk8bxu {
  stop-color: var(--svg-color--e36b4e, #E36B4E);
}

.ni0r16bse {
  stop-color: var(--svg-color--f2431e, #F2431E);
}

.pbl0i9ftj {
  stop-color: var(--svg-color--5e5153, #5E5153);
}

.pjo0xc2qo {
  stop-color: var(--svg-color--ee406d, #EE406D);
}

.q3627esih {
  stop-color: var(--svg-color--d64010, #D64010);
}

.q6di75j4u {
  stop-color: var(--svg-color--e13c61, #E13C61);
}

.qg2361bhj {
  d: path("M18.038 21.442a.506.506 0 0 1-.47-.67c.24-.67.87-1.12 1.58-1.12h2.33c.28 0 .5.22.5.5s-.22.5-.5.5h-2.33a.67.67 0 0 0-.64.45c-.07.21-.27.34-.47.34");
}

.qzfy6zdle {
  stop-color: var(--svg-color--e54f45, #E54F45);
}

.r78eeuw1g {
  stop-color: var(--svg-color--ffa16e, #FFA16E);
  stop-opacity: 0;
}

.rjjttlbvo {
  stop-color: var(--svg-color--bd0f25, #BD0F25);
}

.rodxn0b_k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.82 15.438s-2.133 2.921-2.219 3.218s-.085 1.5-.085 1.5");
}

.rpg8vbclg {
  stop-color: var(--svg-color--df2a68, #DF2A68);
}

.s-kb6qblb {
  stop-color: var(--svg-color--f66141, #F66141);
}

.sj063sbzt {
  d: path("M20.018 18.442a.506.506 0 0 1-.47-.67c.24-.67.87-1.12 1.58-1.12h1.43c.28 0 .5.22.5.5s-.22.5-.5.5h-1.43a.67.67 0 0 0-.64.45a.48.48 0 0 1-.47.34");
}

.t_7id5qoj {
  stop-color: var(--svg-color--e54b46, #E54B46);
}

.t48e9cbqp {
  stop-color: var(--svg-color--e0415b, #E0415B);
}

.t84p3dbvu {
  stop-color: var(--svg-color--dc4d3c, #DC4D3C);
}

.tb2x4fa0e {
  stop-color: var(--svg-color--e36a4d, #E36A4D);
  stop-opacity: 0;
}

.u-gpgvb7w {
  stop-color: var(--svg-color--ef5a34, #EF5A34);
}

.u1m9pzotu {
  fill: var(--svg-color--f77035, #F77035);
  d: path("M24.398 27.802c-2.03.67-2.95-.92-2.95-.92l-2.38-4.23h-3.45c-.05 0-.1 0-.15.01c-.03 0-.06 0-.09.01c-.06 0-.13.01-.19.02h-.03c-.07.01-.14.02-.22.02l.14 6.94h2.92c2.36 0 4.55-.68 6.4-1.85");
}

.uiom1be2e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.516 6.094c1.078-.938 4.178-2.619 7.328-2.594c3.937.031 6.062 1.375 8.156 1.375c.876 0 2.617-.633 3.586-1.383");
}

.v1-wjxb4r {
  stop-color: var(--svg-color--df484e, #DF484E);
}

.varrlsbiv {
  stop-color: var(--svg-color--df3b12, #DF3B12);
}

.vh1wn4bcq {
  stop-color: var(--svg-color--d23146, #D23146);
}

.vkhjbdbgb {
  stop-color: var(--svg-color--ed5b3c, #ED5B3C);
  stop-opacity: 0;
}

.vtsj3ns4l {
  stop-color: var(--svg-color--ee3c71, #EE3C71);
  stop-opacity: 0;
}

.w_ilr5kdc {
  stop-color: var(--svg-color--ffa06e, #FFA06E);
}

.wi5biccqk {
  stop-color: var(--svg-color--ff7727, #FF7727);
}

.wpiwyc_ua {
  stop-color: var(--svg-color--ed504b, #ED504B);
}

.xaoqkwbsn {
  stop-color: var(--svg-color--ff7486, #FF7486);
}

.xeabqocoi {
  stop-color: var(--svg-color--f0564e, #F0564E);
  stop-opacity: 0;
}

.xm_5eqbxk {
  d: path("M11.508 20.652c-.28 0-.5-.22-.5-.5v-.7c0-.62.19-1.22.55-1.74l3.04-4.34c.16-.23.47-.28.7-.12s.28.47.12.7l-3.04 4.34c-.24.34-.37.75-.37 1.16v.7c0 .28-.22.5-.5.5");
}

.y1j5i17ae {
  d: path("M14.508 20.652c-.28 0-.5-.22-.5-.5v-.7c0-.62.19-1.22.55-1.74l3.04-4.34c.16-.23.47-.28.7-.12s.28.47.12.7l-3.04 4.34c-.24.34-.37.75-.37 1.16v.7c0 .28-.22.5-.5.5");
}

.y4v9l4baq {
  stop-color: var(--svg-color--ef554d, #EF554D);
}

.z6nhqibww {
  stop-color: var(--svg-color--d4264c, #D4264C);
}

.z7ovgcbon {
  d: path("M20.018 21.442a.506.506 0 0 1-.47-.67c.24-.67.87-1.12 1.58-1.12h1.43c.28 0 .5.22.5.5s-.22.5-.5.5h-1.43a.67.67 0 0 0-.64.45c-.07.21-.26.34-.47.34");
}

.zhj430b8m {
  stop-color: var(--svg-color--ff7c49, #FF7C49);
}

.zkbdjac-u {
  stop-color: var(--svg-color--553836, #553836);
}

</style>
