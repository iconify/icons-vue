<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="eg3nxccbz"/><path fill="url(#iFpGBxN)" class="ezmvqxgyx"/><path fill="url(#if6zGXc)" class="ezmvqxgyx"/><g filter="url(#iYkKkjb)"><path stroke="url(#ipDOj0v)" class="qo7h6rbir"/></g><path class="u2nc90b4v"/><path fill="url(#iK8f2Wd)" class="akbg0ebpp"/><path fill="url(#ioqngQe)" class="akbg0ebpp"/><path fill="url(#iZ58bpe)" class="akbg0ebpp"/><g filter="url(#iQMUWEc)"><circle class="ge2gdrbsn"/><circle fill="url(#ifdZ41n)" class="e_alqdb_h"/><circle fill="url(#iUN1Eqe)" class="e_alqdb_h"/><circle fill="url(#i8nE9he)" class="e_alqdb_h"/></g><path stroke="url(#iYrmb8d)" class="ko0uhzbxc"/><g filter="url(#ixVg1we)"><path stroke="url(#iFPTiLe)" class="p-1nbgbrg"/></g><path stroke="url(#ivosqcb)" class="xn825ib6l"/><path stroke="url(#iytKZab)" class="pampxm3ck"/><g filter="url(#idhY9Oc)"><path stroke="url(#iHgkRYc)" class="rgm440b1p"/></g><path stroke="url(#iWlpxul)" class="ch9aulpwo"/><path stroke="url(#iYscgdc)" class="glfet11ti"/><g filter="url(#iUEERGc)"><path stroke="url(#iEwkeQc)" class="qk089syzt"/></g><path stroke="url(#i0U0tAe)" class="s-rw5yajm"/><path stroke="url(#itcOnTd)" class="w-xtk3bpl"/><g filter="url(#ifvc7de)"><path stroke="url(#i5144hc)" class="kzlbucb4w"/></g><path stroke="url(#ieVsZNc)" class="aym2r_b0y"/><g filter="url(#ipKumVb)"><path stroke="url(#iW9wK8d)" class="ga8uxs2xn"/></g><path stroke="url(#ia3BV8c)" class="g_1jwabmc"/><g filter="url(#i3mA3Vc)"><path stroke="url(#iwHPuGb)" class="a30mkct5t"/></g><path stroke="url(#i0fZHtd)" class="tma2q51kt"/><path stroke="url(#i3Tfcdd)" class="s97tetsbl"/><g filter="url(#ihk9uuc)"><path stroke="url(#isWajDe)" class="wsk9occmp"/></g><path stroke="url(#itLFhMe)" class="ttoiym-bf"/><path stroke="url(#iCOuy2p)" class="a1spzdbjq"/><g filter="url(#iNXPQXb)"><path stroke="url(#itPNmxR)" class="kfqglsddp"/></g><circle class="hkqid3rda"/><circle fill="url(#i1kBfFd)" class="cje76sv3k"/><circle fill="url(#iey64Oe)" class="cje76sv3k"/><circle fill="url(#i4XaJmc)" class="cje76sv3k"/><circle fill="url(#ifsVVCe)" class="cje76sv3k"/><circle fill="url(#iYvfmCd)" class="cje76sv3k"/><circle class="hkqid3rda"/><circle fill="url(#i1kBfFd)" class="cje76sv3k"/><circle fill="url(#iey64Oe)" class="cje76sv3k"/><circle fill="url(#i4XaJmc)" class="cje76sv3k"/><circle fill="url(#ifsVVCe)" class="cje76sv3k"/><circle fill="url(#iYvfmCd)" class="cje76sv3k"/><circle fill="url(#iXgGLkL)" class="cje76sv3k"/><circle fill="url(#iDXYPSc)" class="cje76sv3k"/><circle fill="url(#i5qiGjb)" class="cje76sv3k"/><circle fill="url(#icxofVf)" class="cje76sv3k"/><g filter="url(#i5K6Obd)"><ellipse fill="url(#iueFOEb)" transform="rotate(-15.24 18.286 17.044)" class="gnfwqibxp"/></g><g filter="url(#iDo1Cfc)"><circle fill="url(#itbgpSb)" class="t9rbze9wu"/></g><defs><radialGradient id="if6zGXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .875 -.45313 0 14.71 6.188)" gradientUnits="userSpaceOnUse"><stop class="znxitwelz"/><stop offset="1" class="ghsfwrbip"/></radialGradient><radialGradient id="ioqngQe" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 .71875 -.6058 -.2634 17.586 6.016)" gradientUnits="userSpaceOnUse"><stop class="znxitwelz"/><stop offset="1" class="ghsfwrbip"/></radialGradient><radialGradient id="ifdZ41n" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.9375 -9.68451 0 16 8.22)" gradientUnits="userSpaceOnUse"><stop class="l4lmbqggl"/><stop offset=".78" class="w4xdaxb3b"/></radialGradient><radialGradient id="iUN1Eqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.23437 3.331 0 16.078 13)" gradientUnits="userSpaceOnUse"><stop class="w4xdaxb3b"/><stop offset="1" class="l4lmbqggl"/></radialGradient><radialGradient id="i8nE9he" cx="0" cy="0" r="1" gradientTransform="rotate(42.421 -2.248 21.604)scale(.61382 1.16085)" gradientUnits="userSpaceOnUse"><stop class="yj7nl8b8u"/><stop offset="1" class="dyrclpaql"/></radialGradient><radialGradient id="iytKZab" cx="0" cy="0" r="1" gradientTransform="matrix(.69704 -.19804 .08099 .28504 3.204 16.92)" gradientUnits="userSpaceOnUse"><stop class="avpn2yb6z"/><stop offset="1" class="d-2ijyb-v"/></radialGradient><radialGradient id="iYscgdc" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.28125 .13125 .39375 3.305 6.22)" gradientUnits="userSpaceOnUse"><stop class="avpn2yb6z"/><stop offset="1" class="d-2ijyb-v"/></radialGradient><radialGradient id="itcOnTd" cx="0" cy="0" r="1" gradientTransform="matrix(.94531 0 0 .26855 9.23 2.454)" gradientUnits="userSpaceOnUse"><stop class="avpn2yb6z"/><stop offset="1" class="d-2ijyb-v"/></radialGradient><radialGradient id="i3Tfcdd" cx="0" cy="0" r="1" gradientTransform="rotate(-171.254 15.21 2.153)scale(.82206 .38363)" gradientUnits="userSpaceOnUse"><stop class="avpn2yb6z"/><stop offset="1" class="d-2ijyb-v"/></radialGradient><radialGradient id="iCOuy2p" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29688 .09376 -.04541 -.62817 24.273 2.454)" gradientUnits="userSpaceOnUse"><stop class="avpn2yb6z"/><stop offset="1" class="d-2ijyb-v"/></radialGradient><radialGradient id="i1kBfFd" cx="0" cy="0" r="1" gradientTransform="scale(8.375 6.125)rotate(-90 2.86 .95)" gradientUnits="userSpaceOnUse"><stop class="rwkiqzbut"/><stop offset="1" class="lwytjzx5n"/></radialGradient><radialGradient id="iey64Oe" cx="0" cy="0" r="1" gradientTransform="scale(8.59375 12.5)rotate(90 .48 1.382)" gradientUnits="userSpaceOnUse"><stop offset=".97" class="wrw9dbc9n"/><stop offset="1" class="kl-3u8bvo"/></radialGradient><radialGradient id="i4XaJmc" cx="0" cy="0" r="1" gradientTransform="matrix(11.7188 0 0 8.95743 11.492 17.875)" gradientUnits="userSpaceOnUse"><stop offset=".84" class="muatvic6r"/><stop offset="1" class="jic23ybkp"/></radialGradient><radialGradient id="ifsVVCe" cx="0" cy="0" r="1" gradientTransform="matrix(-16 0 0 -13.6471 21.617 17.875)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="muatvic6r"/><stop offset="1" class="jic23ybkp"/></radialGradient><radialGradient id="iYvfmCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.53125 -3.4611 0 15.992 10.688)" gradientUnits="userSpaceOnUse"><stop class="rwkiqzbut"/><stop offset="1" class="lwytjzx5n"/></radialGradient><radialGradient id="iXgGLkL" cx="0" cy="0" r="1" gradientTransform="matrix(.21094 .39063 -.5507 .29738 13.055 12.329)" gradientUnits="userSpaceOnUse"><stop class="xqrqlqbwn"/><stop offset="1" class="ob8zzqxyt"/></radialGradient><radialGradient id="iDXYPSc" cx="0" cy="0" r="1" gradientTransform="matrix(.76562 .4375 -.61679 1.07938 11.086 13.61)" gradientUnits="userSpaceOnUse"><stop class="xqrqlqbwn"/><stop offset="1" class="ob8zzqxyt"/></radialGradient><radialGradient id="i5qiGjb" cx="0" cy="0" r="1" gradientTransform="matrix(.7539 .07813 -.11014 1.06286 10.004 16.125)" gradientUnits="userSpaceOnUse"><stop class="xqrqlqbwn"/><stop offset="1" class="ob8zzqxyt"/></radialGradient><radialGradient id="icxofVf" cx="0" cy="0" r="1" gradientTransform="matrix(1.10938 -.51563 .6465 1.39096 9.695 19.657)" gradientUnits="userSpaceOnUse"><stop class="xqrqlqbwn"/><stop offset="1" class="ob8zzqxyt"/></radialGradient><radialGradient id="iueFOEb" cx="0" cy="0" r="1" gradientTransform="rotate(160.795 8.496 9.93)scale(4.81563 3.60225)" gradientUnits="userSpaceOnUse"><stop class="j1qkpnxpi"/><stop offset="1" class="ockf42bpg"/></radialGradient><radialGradient id="itbgpSb" cx="0" cy="0" r="1" gradientTransform="rotate(159.77 7.837 6.225)scale(2.25953 1.86136)" gradientUnits="userSpaceOnUse"><stop class="mr-5tog2k"/><stop offset="1" class="p-2yf1j2g"/></radialGradient><linearGradient id="iFpGBxN" x1="15.117" x2="15.117" y1="5.391" y2="7.266" gradientUnits="userSpaceOnUse"><stop class="q47baub5c"/><stop offset="1" class="w13yuab_q"/></linearGradient><linearGradient id="ipDOj0v" x1="15.59" x2="15.59" y1="5.555" y2="7.079" gradientUnits="userSpaceOnUse"><stop class="wa1-a3--k"/><stop offset="1" class="vqmpnwgyx"/></linearGradient><linearGradient id="iK8f2Wd" x1="16.867" x2="16.867" y1="5.391" y2="7.266" gradientUnits="userSpaceOnUse"><stop class="q47baub5c"/><stop offset="1" class="w13yuab_q"/></linearGradient><linearGradient id="iZ58bpe" x1="16.785" x2="16.957" y1="7.012" y2="7.012" gradientUnits="userSpaceOnUse"><stop class="bb3h_9i2r"/><stop offset="1" class="j9hzq_0_b"/></linearGradient><linearGradient id="iYrmb8d" x1="9.744" x2="8.395" y1="23.015" y2="20.35" gradientUnits="userSpaceOnUse"><stop class="hnspy7bll"/><stop offset="1" class="nr2_5zbef"/></linearGradient><linearGradient id="iFPTiLe" x1="8.664" x2="11.809" y1="29.594" y2="28.777" gradientUnits="userSpaceOnUse"><stop class="b6enp4b-g"/><stop offset=".536" class="h0a4438yd"/><stop offset=".932" class="i2jicl2xu"/></linearGradient><linearGradient id="ivosqcb" x1="7.68" x2="7.398" y1="19.188" y2="17.094" gradientUnits="userSpaceOnUse"><stop class="hnspy7bll"/><stop offset="1" class="nr2_5zbef"/></linearGradient><linearGradient id="iHgkRYc" x1="3.727" x2="10.879" y1="22.719" y2="21.033" gradientUnits="userSpaceOnUse"><stop class="b6enp4b-g"/><stop offset=".701" class="h0a4438yd"/><stop offset="1" class="i2jicl2xu"/></linearGradient><linearGradient id="iWlpxul" x1="7.469" x2="7.469" y1="7.752" y2="14.813" gradientUnits="userSpaceOnUse"><stop class="hnspy7bll"/><stop offset="1" class="nr2_5zbef"/></linearGradient><linearGradient id="iEwkeQc" x1="3.891" x2="8.984" y1="7.374" y2="15.176" gradientUnits="userSpaceOnUse"><stop class="b6enp4b-g"/><stop offset=".782" class="h0a4438yd"/><stop offset="1" class="i2jicl2xu"/></linearGradient><linearGradient id="i0U0tAe" x1="10.969" x2="10.969" y1="4.125" y2="13.329" gradientUnits="userSpaceOnUse"><stop class="hnspy7bll"/><stop offset="1" class="nr2_5zbef"/></linearGradient><linearGradient id="i5144hc" x1="9.734" x2="11.163" y1="3.227" y2="13.329" gradientUnits="userSpaceOnUse"><stop class="b6enp4b-g"/><stop offset="1" class="h0a4438yd"/></linearGradient><linearGradient id="ieVsZNc" x1="23.43" x2="25.064" y1="27.063" y2="19.193" gradientUnits="userSpaceOnUse"><stop class="hnspy7bll"/><stop offset="1" class="nr2_5zbef"/></linearGradient><linearGradient id="iW9wK8d" x1="23.477" x2="20.332" y1="29.594" y2="28.777" gradientUnits="userSpaceOnUse"><stop class="b6enp4b-g"/><stop offset=".536" class="h0a4438yd"/></linearGradient><linearGradient id="ia3BV8c" x1="27.742" x2="22.367" y1="22.625" y2="15.438" gradientUnits="userSpaceOnUse"><stop class="hnspy7bll"/><stop offset="1" class="nr2_5zbef"/></linearGradient><linearGradient id="iwHPuGb" x1="27.247" x2="23.135" y1="23.377" y2="19.353" gradientUnits="userSpaceOnUse"><stop class="b6enp4b-g"/><stop offset=".536" class="h0a4438yd"/></linearGradient><linearGradient id="i0fZHtd" x1="27.742" x2="20.108" y1="12.563" y2="15.74" gradientUnits="userSpaceOnUse"><stop class="hnspy7bll"/><stop offset="1" class="nr2_5zbef"/></linearGradient><linearGradient id="isWajDe" x1="29.711" x2="23.722" y1="9.125" y2="19.675" gradientUnits="userSpaceOnUse"><stop class="b6enp4b-g"/><stop offset=".536" class="h0a4438yd"/><stop offset="1" class="i2jicl2xu"/></linearGradient><linearGradient id="itLFhMe" x1="24.492" x2="16.016" y1="7.375" y2="12.596" gradientUnits="userSpaceOnUse"><stop class="hnspy7bll"/><stop offset="1" class="nr2_5zbef"/></linearGradient><linearGradient id="itPNmxR" x1="24.773" x2="28.066" y1="4.063" y2="9.618" gradientUnits="userSpaceOnUse"><stop class="b6enp4b-g"/><stop offset=".536" class="h0a4438yd"/><stop offset=".932" class="i2jicl2xu"/></linearGradient><filter id="iYkKkjb" width=".25" height="1.773" x="14.965" y="5.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6626" stdDeviation=".05"/></filter><filter id="iQMUWEc" width="6.961" height="6.961" x="12.52" y="6.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411302 0 0 0 0 0.380937 0 0 0 0 0.441667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6626"/></filter><filter id="ixVg1we" width="4.285" height="10.277" x="7.31" y="19.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6626" stdDeviation=".2"/></filter><filter id="idhY9Oc" width="8.808" height="6.925" x="2.35" y="16.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6626" stdDeviation=".2"/></filter><filter id="iUEERGc" width="10.441" height="9.394" x="2.248" y="5.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6626" stdDeviation=".2"/></filter><filter id="ifvc7de" width="5.939" height="11.925" x="8.193" y="1.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6626" stdDeviation=".2"/></filter><filter id="ipKumVb" width="4.285" height="10.277" x="20.545" y="19.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6626" stdDeviation=".2"/></filter><filter id="i3mA3Vc" width="8.808" height="6.925" x="20.952" y="16.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6626" stdDeviation=".2"/></filter><filter id="ihk9uuc" width="10.441" height="9.394" x="19.311" y="5.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6626" stdDeviation=".2"/></filter><filter id="iNXPQXb" width="5.939" height="11.925" x="18.061" y="1.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6626" stdDeviation=".2"/></filter><filter id="i5K6Obd" width="8.589" height="9.108" x="13.991" y="12.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6626" stdDeviation=".5"/></filter><filter id="iDo1Cfc" width="5.406" height="5.406" x="14.34" y="6.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6626" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:spider" /></template>
<style>
.a1spzdbjq {
  stroke-linecap: round;
  stroke-opacity: 0.75;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M23.445 2.454c.172 3.171-.265 9.093-4.86 10.875");
}

.a30mkct5t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M29.234 22.97c-.62-1.923-2.632-5.509-7.757-5.876");
}

.akbg0ebpp {
  d: path("M18.004 6.663c0-.536-.269-1.035-.716-1.33a.354.354 0 0 0-.55.295v2.45h1.266z");
}

.avpn2yb6z {
  stop-color: var(--svg-color--7b6e89, #7B6E89);
}

.aym2r_b0y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M21.07 19.727c1.573 1.26 4.5 5.188 2.633 9.227");
}

.b6enp4b-g {
  stop-color: var(--svg-color--776985, #776985);
}

.bb3h_9i2r {
  stop-color: var(--svg-color--41394a, #41394A);
}

.ch9aulpwo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M2.773 6.47c.485 2.359 2.797 7.562 9.391 8.343");
}

.cje76sv3k {
  cx: 15.992px;
  cy: 17.684px;
  r: 5.988px;
}

.d-2ijyb-v {
  stop-color: var(--svg-color--7b6e89, #7B6E89);
  stop-opacity: 0;
}

.dyrclpaql {
  stop-color: var(--svg-color--4b4650, #4B4650);
  stop-opacity: 0;
}

.e_alqdb_h {
  cx: 16px;
  cy: 10.207px;
  r: 3.48px;
}

.eg3nxccbz {
  fill: var(--svg-color--403947, #403947);
  d: path("M13.98 6.663c0-.536.27-1.035.716-1.33a.354.354 0 0 1 .55.295v2.45H13.98z");
}

.ezmvqxgyx {
  d: path("M13.98 6.663c0-.536.27-1.035.716-1.33a.354.354 0 0 1 .55.295v2.45H13.98z");
}

.ft5dv1b6b {
  fill: none;
}

.g_1jwabmc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M29.234 22.97c-.62-1.923-2.632-5.509-7.757-5.876");
}

.ga8uxs2xn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M21.07 19.727c1.573 1.26 4.5 5.188 2.633 9.227");
}

.ge2gdrbsn {
  cx: 16px;
  cy: 10.207px;
  r: 3.48px;
  fill: var(--svg-color--4f3e5f, #4F3E5F);
}

.ghsfwrbip {
  stop-color: var(--svg-color--5e5567, #5E5567);
  stop-opacity: 0;
}

.glfet11ti {
  stroke-linecap: round;
  stroke-opacity: 0.6;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M2.773 6.47c.485 2.359 2.797 7.562 9.391 8.343");
}

.gnfwqibxp {
  cx: 18.286px;
  cy: 17.044px;
  rx: 3.272px;
  ry: 3.573px;
}

.h0a4438yd {
  stop-color: var(--svg-color--605a67, #605A67);
}

.hkqid3rda {
  cx: 15.992px;
  cy: 17.684px;
  r: 5.988px;
  fill: var(--svg-color--332b3b, #332B3B);
}

.hnspy7bll {
  stop-color: var(--svg-color--433156, #433156);
}

.i2jicl2xu {
  stop-color: var(--svg-color--605a67, #605A67);
  stop-opacity: 0;
}

.j1qkpnxpi {
  stop-color: var(--svg-color--6b6671, #6B6671);
}

.j9hzq_0_b {
  stop-color: var(--svg-color--41394a, #41394A);
  stop-opacity: 0;
}

.jic23ybkp {
  stop-color: var(--svg-color--6e6b72, #6E6B72);
}

.kfqglsddp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.445 2.454c.172 3.171-.265 9.093-4.86 10.875");
}

.kl-3u8bvo {
  stop-color: var(--svg-color--634c78, #634C78);
}

.ko0uhzbxc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M10.93 19.727c-1.573 1.26-4.5 5.188-2.633 9.227");
}

.kzlbucb4w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M8.748 2.454c-.172 3.171.266 9.093 4.86 10.875");
}

.l4lmbqggl {
  stop-color: var(--svg-color--1d1525, #1D1525);
  stop-opacity: 0;
}

.lwytjzx5n {
  stop-color: var(--svg-color--3f2355, #3F2355);
  stop-opacity: 0;
}

.mr-5tog2k {
  stop-color: var(--svg-color--736781, #736781);
}

.muatvic6r {
  stop-color: var(--svg-color--6e6b72, #6E6B72);
  stop-opacity: 0;
}

.nr2_5zbef {
  stop-color: var(--svg-color--1e1823, #1E1823);
}

.ob8zzqxyt {
  stop-color: var(--svg-color--5d5a60, #5D5A60);
  stop-opacity: 0;
}

.ockf42bpg {
  stop-color: var(--svg-color--6b6671, #6B6671);
  stop-opacity: 0;
}

.p-1nbgbrg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.07 19.727c-1.573 1.26-4.5 5.188-2.633 9.227");
}

.p-2yf1j2g {
  stop-color: var(--svg-color--736781, #736781);
  stop-opacity: 0;
}

.pampxm3ck {
  stroke-linecap: round;
  stroke-opacity: 0.6;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M2.766 22.97c.62-1.923 2.632-5.509 7.757-5.876");
}

.q47baub5c {
  stop-color: var(--svg-color--534262, #534262);
}

.qk089syzt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.773 6.317c.485 2.36 2.797 7.562 9.391 8.344");
}

.qo7h6rbir {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M15.09 5.555V7.08");
}

.rgm440b1p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.875 22.97c.62-1.923 2.633-5.509 7.758-5.876");
}

.rwkiqzbut {
  stop-color: var(--svg-color--3f2355, #3F2355);
}

.s-rw5yajm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M8.555 2.454c-.172 3.171.265 9.093 4.86 10.875");
}

.s97tetsbl {
  stroke-linecap: round;
  stroke-opacity: 0.75;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M29.227 6.47c-.485 2.359-2.797 7.562-9.391 8.343");
}

.t9rbze9wu {
  cx: 17.043px;
  cy: 9.563px;
  r: 1.953px;
}

.tma2q51kt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M29.227 6.47c-.485 2.359-2.797 7.562-9.391 8.343");
}

.ttoiym-bf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M23.445 2.454c.172 3.171-.265 9.093-4.86 10.875");
}

.u2nc90b4v {
  fill: var(--svg-color--403947, #403947);
  d: path("M18.004 6.663c0-.536-.269-1.035-.716-1.33a.354.354 0 0 0-.55.295v2.45h1.266z");
}

.vqmpnwgyx {
  stop-color: var(--svg-color--6d6376, #6D6376);
  stop-opacity: 0;
}

.w-xtk3bpl {
  stroke-linecap: round;
  stroke-opacity: 0.6;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M8.555 2.454c-.172 3.171.265 9.093 4.86 10.875");
}

.w13yuab_q {
  stop-color: var(--svg-color--534262, #534262);
  stop-opacity: 0;
}

.w4xdaxb3b {
  stop-color: var(--svg-color--1d1525, #1D1525);
}

.wa1-a3--k {
  stop-color: var(--svg-color--6d6376, #6D6376);
}

.wrw9dbc9n {
  stop-color: var(--svg-color--634c78, #634C78);
  stop-opacity: 0;
}

.wsk9occmp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M29.227 6.47c-.485 2.359-2.797 7.562-9.391 8.343");
}

.xn825ib6l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M2.766 22.97c.62-1.923 2.632-5.509 7.757-5.876");
}

.xqrqlqbwn {
  stop-color: var(--svg-color--5d5a60, #5D5A60);
}

.yj7nl8b8u {
  stop-color: var(--svg-color--4b4650, #4B4650);
}

.znxitwelz {
  stop-color: var(--svg-color--5e5567, #5E5567);
}

</style>
