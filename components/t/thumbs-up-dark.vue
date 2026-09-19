<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ib89D0b)"><path fill="url(#ixt1mGd)" class="sk42-mbfm"/></g><path fill="url(#inQ0Lud)" class="sk42-mbfm"/><path fill="url(#iUC9Vvh)" class="sk42-mbfm"/><path fill="url(#i8BTS4d)" class="sk42-mbfm"/><path fill="url(#i8h7pIe)" class="sk42-mbfm"/><path fill="url(#iLUeyGd)" class="sk42-mbfm"/><path fill="url(#iSkfkMb)" class="sk42-mbfm"/><g filter="url(#iHYsx7d)"><path fill="url(#iqPMIjJ)" class="q6s71tkwa"/></g><g filter="url(#ibByPcW)"><rect fill="url(#iJkzuBd)" transform="rotate(90 26.311 10.73)" class="m2bjxmrzi"/><rect fill="url(#ijhwWId)" transform="rotate(90 26.311 10.73)" class="m2bjxmrzi"/></g><g filter="url(#ivSCmve)"><rect fill="url(#izwNpwb)" class="zns-jebcc"/></g><g filter="url(#iTDkSve)"><rect fill="url(#i0mWivc)" transform="rotate(90 26.01 24.015)" class="f21bsab8n"/><rect fill="url(#ibxqS0j)" transform="rotate(90 26.01 24.015)" class="f21bsab8n"/><rect fill="url(#ijfniyd)" transform="rotate(90 26.01 24.015)" class="f21bsab8n"/></g><rect fill="url(#ir6JEUd)" transform="rotate(90 26.01 24.015)" class="f21bsab8n"/><rect fill="url(#irAkjBc)" transform="rotate(90 26.01 24.015)" class="f21bsab8n"/><g filter="url(#iQgeB4b)"><rect fill="url(#i89AJGd)" class="o2m71kb7x"/></g><g filter="url(#i2J6d5b)"><rect fill="url(#ixgNR9G)" transform="rotate(90 27.31 19.735)" class="oko1bkbgl"/><rect fill="url(#icVzXUd)" transform="rotate(90 27.31 19.735)" class="oko1bkbgl"/><rect fill="url(#id91qPc)" transform="rotate(90 27.31 19.735)" class="oko1bkbgl"/></g><g filter="url(#igIs6qc)"><rect fill="url(#i2cMCCe)" class="xxiabeboq"/></g><g filter="url(#i0i8RUd)"><rect fill="url(#izNFBPq)" transform="rotate(90 27.264 15.285)" class="fo_kxezst"/><rect fill="url(#iQn0u7T)" transform="rotate(90 27.264 15.285)" class="fo_kxezst"/></g><g filter="url(#icbpMTb)"><rect fill="url(#iWBa8Ne)" class="gmtv1fboh"/></g><path fill="url(#i8ckLcc)" class="wc-97k_wh"/><g filter="url(#id8V2Ta)"><rect fill="url(#iMJhHUc)" class="y8rh_fbng"/></g><defs><radialGradient id="inQ0Lud" cx="0" cy="0" r="1" gradientTransform="rotate(138.27 8.337 5.408)scale(4.15174 3.36548)" gradientUnits="userSpaceOnUse"><stop class="ok65aabmb"/><stop offset="1" class="j30gkmbty"/></radialGradient><radialGradient id="iUC9Vvh" cx="0" cy="0" r="1" gradientTransform="rotate(133.564 1.99 10.192)scale(7.41221 5.36952)" gradientUnits="userSpaceOnUse"><stop class="wfak367or"/><stop offset="1" class="sd2-r4jch"/></radialGradient><radialGradient id="i8BTS4d" cx="0" cy="0" r="1" gradientTransform="matrix(-7.66242 7.45294 -4.59455 -4.72369 20.294 16.665)" gradientUnits="userSpaceOnUse"><stop class="zmc711bmf"/><stop offset="1" class="vv_o26wue"/></radialGradient><radialGradient id="i8h7pIe" cx="0" cy="0" r="1" gradientTransform="matrix(5.90372 -10.09087 13.34185 7.80572 11.753 30.775)" gradientUnits="userSpaceOnUse"><stop class="v70h6u7jl"/><stop offset="1" class="mmt32_2jk"/></radialGradient><radialGradient id="iLUeyGd" cx="0" cy="0" r="1" gradientTransform="matrix(-15.534 0 0 -23.9075 20.588 20.643)" gradientUnits="userSpaceOnUse"><stop offset=".864" class="kduqygbeo"/><stop offset="1" class="yh8p8mbtm"/></radialGradient><radialGradient id="iSkfkMb" cx="0" cy="0" r="1" gradientTransform="matrix(1.21582 .98104 -1.29196 1.60114 18.72 11.156)" gradientUnits="userSpaceOnUse"><stop class="ln8qc12st"/><stop offset="1" class="o-5paobui"/></radialGradient><radialGradient id="ijhwWId" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40872 1.84473 -1.2348 -.94296 31.8 18.303)" gradientUnits="userSpaceOnUse"><stop class="rnrtshb6m"/><stop offset="1" class="gc43pu4kt"/></radialGradient><radialGradient id="ibxqS0j" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.31347 2.78222 0 31.674 31.081)" gradientUnits="userSpaceOnUse"><stop class="z--j5xb9c"/><stop offset="1" class="v-94t6bli"/></radialGradient><radialGradient id="ijfniyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.4169 1.66759 0 27.005 31.432)" gradientUnits="userSpaceOnUse"><stop class="yafccacai"/><stop offset="1" class="vkse7obwt"/></radialGradient><radialGradient id="irAkjBc" cx="0" cy="0" r="1" gradientTransform="rotate(-132.781 22.601 9.382)scale(1.21519 1.82666)" gradientUnits="userSpaceOnUse"><stop class="rrx3u2b9p"/><stop offset="1" class="qae2o70cz"/></radialGradient><radialGradient id="icVzXUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.38517 2.92967 0 33.273 27.836)" gradientUnits="userSpaceOnUse"><stop class="nzxiu0rqt"/><stop offset="1" class="d33t2ybal"/></radialGradient><radialGradient id="id91qPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.50376 2.09648 0 28.356 28.239)" gradientUnits="userSpaceOnUse"><stop class="bcjkesbyj"/><stop offset="1" class="s9v__5azz"/></radialGradient><radialGradient id="iQn0u7T" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.50067 2.44847 0 32.392 23.307)" gradientUnits="userSpaceOnUse"><stop class="uzwc_ugjd"/><stop offset="1" class="gdl7jobef"/></radialGradient><radialGradient id="i8ckLcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.57369 -2.59444 0 12.706 5.632)" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></radialGradient><linearGradient id="ixt1mGd" x1="19.608" x2="9.546" y1="6.639" y2="27.827" gradientUnits="userSpaceOnUse"><stop class="a99735bei"/><stop offset="1" class="qa7npib0t"/></linearGradient><linearGradient id="iqPMIjJ" x1="20.454" x2="20.454" y1="12.157" y2="25.445" gradientUnits="userSpaceOnUse"><stop class="abmwbz7nz"/><stop offset="1" class="w570v2b9y"/></linearGradient><linearGradient id="iJkzuBd" x1="29.221" x2="29.221" y1="10.73" y2="19.774" gradientUnits="userSpaceOnUse"><stop class="y_rsb8bve"/><stop offset="1" class="uabdogbwa"/></linearGradient><linearGradient id="izwNpwb" x1="25.027" x2="18.413" y1="12.847" y2="12.847" gradientUnits="userSpaceOnUse"><stop class="z_ok4qbes"/><stop offset="1" class="m2rehs_5n"/></linearGradient><linearGradient id="i0mWivc" x1="28.843" x2="28.843" y1="24.791" y2="32.876" gradientUnits="userSpaceOnUse"><stop class="aksjgob4r"/><stop offset="1" class="bhbd7ehzm"/></linearGradient><linearGradient id="ir6JEUd" x1="32.258" x2="30.426" y1="28.445" y2="28.445" gradientUnits="userSpaceOnUse"><stop class="pgh8tskok"/><stop offset="1" class="yin_l7b1j"/></linearGradient><linearGradient id="i89AJGd" x1="25.067" x2="19.278" y1="26.103" y2="26.103" gradientUnits="userSpaceOnUse"><stop class="vwo7htbky"/><stop offset="1" class="l920_zwmb"/></linearGradient><linearGradient id="ixgNR9G" x1="30.291" x2="30.291" y1="20.625" y2="29.894" gradientUnits="userSpaceOnUse"><stop class="qv73_qbby"/><stop offset="1" class="bl41r62ls"/></linearGradient><linearGradient id="i2cMCCe" x1="25.962" x2="18.713" y1="22.233" y2="22.233" gradientUnits="userSpaceOnUse"><stop class="mip3wjw9k"/><stop offset="1" class="evixpqbbz"/></linearGradient><linearGradient id="izNFBPq" x1="30.18" x2="30.18" y1="15.285" y2="25.398" gradientUnits="userSpaceOnUse"><stop class="mdqeewbkl"/><stop offset="1" class="b71g68bqj"/></linearGradient><linearGradient id="iWBa8Ne" x1="25.939" x2="18.208" y1="17.199" y2="17.199" gradientUnits="userSpaceOnUse"><stop class="eser-fblc"/><stop offset="1" class="v41ltixcj"/></linearGradient><linearGradient id="iMJhHUc" x1="18.221" x2="15.133" y1="5.305" y2="5.305" gradientUnits="userSpaceOnUse"><stop class="hejq6m4al"/><stop offset="1" class="r-g3baczj"/></linearGradient><filter id="ib89D0b" width="19.048" height="27.809" x="5.271" y="1.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.160784 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2926"/></filter><filter id="iHYsx7d" width="12.909" height="20.615" x="14" y="10.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2926" stdDeviation="1"/></filter><filter id="ibByPcW" width="9.543" height="5.82" x="17.268" y="10.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.152941 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2926"/></filter><filter id="ivSCmve" width="8.636" height="5.016" x="17.96" y="10.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2926" stdDeviation=".625"/></filter><filter id="iTDkSve" width="9.361" height="6.164" x="17.15" y="23.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0705882 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2926"/></filter><filter id="iQgeB4b" width="7.87" height="3.976" x="18.726" y="24.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2926" stdDeviation=".625"/></filter><filter id="i2J6d5b" width="10.659" height="6.464" x="17.15" y="19.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.0862745 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2926"/></filter><filter id="igIs6qc" width="9.225" height="3.976" x="18.336" y="20.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2926" stdDeviation=".625"/></filter><filter id="i0i8RUd" width="10.614" height="6.333" x="17.15" y="14.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.101961 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2926"/></filter><filter id="icbpMTb" width="9.672" height="5.016" x="17.889" y="15.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2926" stdDeviation=".625"/></filter><filter id="id8V2Ta" width="5.365" height="10.497" x="14.255" y="1.862" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2926" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:thumbs-up-dark" /></template>
<style>
.a99735bei {
  stop-color: var(--svg-color--5a423f, #5A423F);
}

.abmwbz7nz {
  stop-color: var(--svg-color--251616, #251616);
}

.aksjgob4r {
  stop-color: var(--svg-color--5a413f, #5A413F);
}

.b71g68bqj {
  stop-color: var(--svg-color--47302d, #47302D);
}

.bcjkesbyj {
  stop-color: var(--svg-color--2d1717, #2D1717);
}

.bhbd7ehzm {
  stop-color: var(--svg-color--3b212e, #3B212E);
}

.bl41r62ls {
  stop-color: var(--svg-color--3b2728, #3B2728);
}

.d33t2ybal {
  stop-color: var(--svg-color--3f2230, #3F2230);
  stop-opacity: 0;
}

.eser-fblc {
  stop-color: var(--svg-color--675250, #675250);
}

.evixpqbbz {
  stop-color: var(--svg-color--64504f, #64504F);
  stop-opacity: 0;
}

.f21bsab8n {
  width: 5.664px;
  height: 8.861px;
  x: 26.011px;
  y: 24.015px;
  rx: 2.832px;
}

.fo_kxezst {
  width: 5.833px;
  height: 10.114px;
  x: 27.264px;
  y: 15.285px;
  rx: 2.91px;
}

.ft5dv1b6b {
  fill: none;
}

.gc43pu4kt {
  stop-color: var(--svg-color--221213, #221213);
  stop-opacity: 0;
}

.gdl7jobef {
  stop-color: var(--svg-color--3d222e, #3D222E);
  stop-opacity: 0;
}

.gmtv1fboh {
  width: 7.172px;
  height: 2.516px;
  x: 19.139px;
  y: 16.509px;
  rx: 1.258px;
}

.hejq6m4al {
  stop-color: var(--svg-color--604c4a, #604C4A);
}

.j30gkmbty {
  stop-color: var(--svg-color--66514f, #66514F);
  stop-opacity: 0;
}

.kduqygbeo {
  stop-color: var(--svg-color--52413e, #52413E);
  stop-opacity: 0;
}

.l920_zwmb {
  stop-color: var(--svg-color--5f4d4c, #5F4D4C);
  stop-opacity: 0;
}

.ln8qc12st {
  stop-color: var(--svg-color--544341, #544341);
}

.m2bjxmrzi {
  width: 5.82px;
  height: 9.043px;
  x: 26.311px;
  y: 10.73px;
  rx: 2.91px;
}

.m2rehs_5n {
  stop-color: var(--svg-color--66524f, #66524F);
  stop-opacity: 0;
}

.mdqeewbkl {
  stop-color: var(--svg-color--543c3b, #543C3B);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mip3wjw9k {
  stop-color: var(--svg-color--64504f, #64504F);
}

.mmt32_2jk {
  stop-color: var(--svg-color--3f2330, #3F2330);
  stop-opacity: 0;
}

.nzxiu0rqt {
  stop-color: var(--svg-color--3f2230, #3F2230);
}

.o-5paobui {
  stop-color: var(--svg-color--544341, #544341);
  stop-opacity: 0;
}

.o2m71kb7x {
  width: 5.37px;
  height: 1.476px;
  x: 19.976px;
  y: 25.699px;
  rx: 0.738px;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.ok65aabmb {
  stop-color: var(--svg-color--66514f, #66514F);
}

.oko1bkbgl {
  width: 5.964px;
  height: 10.159px;
  x: 27.309px;
  y: 19.735px;
  rx: 2.91px;
}

.pgh8tskok {
  stop-color: var(--svg-color--40253e, #40253E);
}

.q6s71tkwa {
  d: path("M24.033 14.709a2.55 2.55 0 0 0-2.552-2.552h-2.826a2.552 2.552 0 0 0-1.638 4.509a2.557 2.557 0 0 0-.115 3.992A2.55 2.55 0 0 0 16 22.605v.125c0 .7.281 1.333.737 1.794a2.483 2.483 0 0 0 1.746 4.248h2.804a2.483 2.483 0 0 0 2.148-3.728a2.55 2.55 0 0 0 1.474-2.314v-.125c0-.79-.36-1.496-.922-1.964a2.56 2.56 0 0 0-.587-4.249c.394-.45.633-1.038.633-1.683");
}

.qa7npib0t {
  stop-color: var(--svg-color--422631, #422631);
}

.qae2o70cz {
  stop-color: var(--svg-color--402b31, #402B31);
  stop-opacity: 0;
}

.qv73_qbby {
  stop-color: var(--svg-color--553b39, #553B39);
}

.r-g3baczj {
  stop-color: var(--svg-color--604c4a, #604C4A);
  stop-opacity: 0;
}

.rnrtshb6m {
  stop-color: var(--svg-color--221213, #221213);
}

.rrx3u2b9p {
  stop-color: var(--svg-color--402b31, #402B31);
}

.s9v__5azz {
  stop-color: var(--svg-color--2d1717, #2D1717);
  stop-opacity: 0;
}

.sd2-r4jch {
  stop-color: var(--svg-color--49312e, #49312E);
  stop-opacity: 0;
}

.sk42-mbfm {
  d: path("M12.622 5.158a3.289 3.289 0 1 1 6.577 0v3.785q.002.483-.072.966c-.018.117-.037.235-.048.352c-.036.37.008.854.26 1.18l-.602.58a9.34 9.34 0 0 1 5.082 8.325a9.4 9.4 0 0 1-.433 2.826l-.996 6.507h-8.102v-.003c-5.003-.108-9.017-3.37-9.017-9.33c0-3.502 1.677-6.322 4.215-7.913l-.007-.005c.173-.12.377-.242.596-.373h.001c.72-.432 1.6-.96 2.063-1.822c.403-.747.481-1.96.481-2.523h.002z");
}

.uabdogbwa {
  stop-color: var(--svg-color--482928, #482928);
}

.uzwc_ugjd {
  stop-color: var(--svg-color--3d222e, #3D222E);
}

.v-94t6bli {
  stop-color: var(--svg-color--3b1f33, #3B1F33);
  stop-opacity: 0;
}

.v41ltixcj {
  stop-color: var(--svg-color--675250, #675250);
  stop-opacity: 0;
}

.v70h6u7jl {
  stop-color: var(--svg-color--3f2330, #3F2330);
}

.vkse7obwt {
  stop-color: var(--svg-color--281617, #281617);
  stop-opacity: 0;
}

.vv_o26wue {
  stop-color: var(--svg-color--453434, #453434);
  stop-opacity: 0;
}

.vwo7htbky {
  stop-color: var(--svg-color--5f4d4c, #5F4D4C);
}

.w570v2b9y {
  stop-color: var(--svg-color--2f1825, #2F1825);
}

.wc-97k_wh {
  d: path("M15.922 1.87a3.29 3.29 0 0 0-3.289 3.288v2.553l-.002-.001c0 .562-.078 1.776-.48 2.523c-.464.862-1.344 1.39-2.063 1.821c-.22.131-.424.254-.597.374c.995.797 3.032 2.39 3.082 2.352c.05-.037 2.344-1.255 3.484-1.86l-.048-.69a3.29 3.29 0 0 0 3.201-3.287V5.158a3.29 3.29 0 0 0-3.288-3.288");
}

.wfak367or {
  stop-color: var(--svg-color--49312e, #49312E);
}

.xxiabeboq {
  width: 6.725px;
  height: 1.476px;
  x: 19.586px;
  y: 21.829px;
  rx: 0.738px;
}

.y_rsb8bve {
  stop-color: var(--svg-color--523936, #523936);
}

.y8rh_fbng {
  width: 2.865px;
  height: 7.997px;
  x: 15.505px;
  y: 3.112px;
  rx: 1.433px;
}

.yafccacai {
  stop-color: var(--svg-color--281617, #281617);
}

.yh8p8mbtm {
  stop-color: var(--svg-color--52413e, #52413E);
}

.yin_l7b1j {
  stop-color: var(--svg-color--40253e, #40253E);
  stop-opacity: 0;
}

.z_ok4qbes {
  stop-color: var(--svg-color--66524f, #66524F);
}

.z--j5xb9c {
  stop-color: var(--svg-color--3b1f33, #3B1F33);
}

.zmc711bmf {
  stop-color: var(--svg-color--453434, #453434);
}

.zns-jebcc {
  width: 6.136px;
  height: 2.516px;
  x: 19.21px;
  y: 12.157px;
  rx: 1.258px;
}

</style>
