<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ikmWRXc)" class="wi3d_9b6k"/><g filter="url(#i38Q5fd)"><path fill="url(#iwmEZiw)" class="qoo971gwk"/></g><g filter="url(#iSNEHJb)"><path fill="url(#iNzoOxd)" class="zi18cob7s"/></g><path fill="url(#iosrcgb)" class="yid_v2bte"/><g filter="url(#i0Dw9Hb)"><path fill="url(#iovepnb)" class="lxyh5oakp"/></g><g filter="url(#il344se)"><path fill="url(#iW1tSue)" class="hj0e80bvc"/></g><g filter="url(#iDaGTjb)"><path fill="url(#ifdmGEb)" class="rjlkldbta"/></g><path fill="url(#iSVgmzc)" class="f-vc59law"/><path fill="url(#iTm6czb)" class="f-vc59law"/><path fill="url(#i9gPB1c)" class="f-vc59law"/><g filter="url(#iY5lHXd)"><path fill="url(#ivKUZVb)" class="xgazf3bqf"/></g><g filter="url(#iIbV4Xb)"><path fill="url(#ivKUZVb)" class="j5d7jachl"/></g><g filter="url(#ivRP1sc)"><path fill="url(#ikAyNwb)" class="slaorzbbf"/></g><defs><linearGradient id="ikmWRXc" x1="6.581" x2="16.126" y1="6.877" y2="6.702" gradientUnits="userSpaceOnUse"><stop class="wz747hb4o"/><stop offset="1" class="itnspbbta"/></linearGradient><linearGradient id="iwmEZiw" x1="6.581" x2="16.126" y1="6.877" y2="6.702" gradientUnits="userSpaceOnUse"><stop class="j2cc9nbls"/><stop offset="1" class="jzrs3dbvo"/></linearGradient><linearGradient id="iNzoOxd" x1="6.659" x2="16.262" y1="3.094" y2="7.204" gradientUnits="userSpaceOnUse"><stop offset=".203" class="nkbzqo3uj"/><stop offset=".495" class="plt72-cpb"/><stop offset=".885" class="nkbzqo3uj"/></linearGradient><linearGradient id="iosrcgb" x1="26.551" x2="17.67" y1="6.874" y2="4.006" gradientUnits="userSpaceOnUse"><stop class="dxaf82bmw"/><stop offset="1" class="vm4u-79hr"/></linearGradient><linearGradient id="iovepnb" x1="26.551" x2="17.67" y1="6.874" y2="4.006" gradientUnits="userSpaceOnUse"><stop class="sso4v_buz"/><stop offset="1" class="x7-rw1b5w"/></linearGradient><linearGradient id="iW1tSue" x1="17.085" x2="27.055" y1="7.373" y2="3" gradientUnits="userSpaceOnUse"><stop offset=".203" class="ov85rttnb"/><stop offset=".74" class="plp63kb-n"/><stop offset="1" class="nemkkdb0f"/></linearGradient><linearGradient id="ifdmGEb" x1="27.602" x2="23.43" y1="2.946" y2="8.287" gradientUnits="userSpaceOnUse"><stop class="nv3-lgb7b"/><stop offset=".578" class="i-d58hfiv"/></linearGradient><linearGradient id="ivKUZVb" x1="24.516" x2="17.971" y1="8.514" y2="11.051" gradientUnits="userSpaceOnUse"><stop class="p-f-u_bpt"/><stop offset="1" class="p4jldr6gm"/></linearGradient><linearGradient id="ikAyNwb" x1="8.184" x2="8.184" y1="11.733" y2="26.168" gradientUnits="userSpaceOnUse"><stop class="ukh2v6_wz"/><stop offset=".255" class="u7nd3_f2e"/><stop offset="1" class="ukh2v6_wz"/></linearGradient><filter id="i38Q5fd" width="10.969" height="5.46" x="5.585" y="2.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29474" stdDeviation=".25"/></filter><filter id="iSNEHJb" width="10.602" height="5.948" x="6.159" y="2.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29474" stdDeviation=".25"/></filter><filter id="i0Dw9Hb" width="10.97" height="5.46" x="16.585" y="2.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29474" stdDeviation=".25"/></filter><filter id="il344se" width="10.97" height="5.94" x="16.585" y="2.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29474" stdDeviation=".25"/></filter><filter id="iDaGTjb" width="11.648" height="6.065" x="16.287" y="2.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29474" stdDeviation=".25"/></filter><filter id="iY5lHXd" width="9.254" height="14.126" x="15.959" y="6.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29474" stdDeviation=".3"/></filter><filter id="iIbV4Xb" width="9.254" height="14.126" x="15.959" y="6.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29474" stdDeviation=".3"/></filter><filter id="ivRP1sc" width="12.339" height="18.435" x="2.015" y="9.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29474" stdDeviation="1"/></filter><radialGradient id="iSVgmzc" cx="0" cy="0" r="1" gradientTransform="rotate(-66.166 40.115 15.038)scale(34.1728)" gradientUnits="userSpaceOnUse"><stop offset=".469" class="nxd2g-34i"/><stop offset=".828" class="sm0nlcukq"/><stop offset="1" class="tsthfc-sx"/></radialGradient><radialGradient id="iTm6czb" cx="0" cy="0" r="1" gradientTransform="matrix(9.66011 9.41191 -10.9845 11.27418 2.55 7.252)" gradientUnits="userSpaceOnUse"><stop class="vbw58rbxo"/><stop offset="1" class="osmw32b6k"/></radialGradient><radialGradient id="i9gPB1c" cx="0" cy="0" r="1" gradientTransform="matrix(-5.68528 18.00073 -21.00838 -6.6352 22.24 12.68)" gradientUnits="userSpaceOnUse"><stop class="vicy7xbfz"/><stop offset="1" class="jkmho4-la"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:peach" /></template>
<style>
.dxaf82bmw {
  stop-color: var(--svg-color--b3d944, #B3D944);
}

.f-vc59law {
  d: path("M16.555 7.53a9.9 9.9 0 0 0-4.035-.85c-5.5 0-9.97 4.46-9.97 9.97c0 2.25.75 4.37 2 6.03c2.29 3.07 6.49 5.79 6.49 5.79c2.1 1.41 3.7 2.21 5.86 2.21c2.34 0 4.49-.78 6.34-2.43c0 0 2.78-2.3 5.3-5.58h-.002a9.93 9.93 0 0 0 2.022-6.02c0-5.506-4.464-9.97-9.97-9.97a9.9 9.9 0 0 0-4.035.85");
}

.ft5dv1b6b {
  fill: none;
}

.hj0e80bvc {
  d: path("M27.055 3h-5.03a4.935 4.935 0 0 0-4.94 4.94c2.598-4.342 3.187-4.315 9.97-4.94");
}

.i-d58hfiv {
  stop-color: var(--svg-color--d2f168, #D2F168);
  stop-opacity: 0;
}

.itnspbbta {
  stop-color: var(--svg-color--a0cb40, #A0CB40);
}

.j2cc9nbls {
  stop-color: var(--svg-color--87b327, #87B327);
}

.j5d7jachl {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M16.559 7.535c3.094-.535 5.313-.775 8.054.538c-1.347 2.508-1.322 7.447-1.191 10.127q.097.87.126 1.833s-.072-.723-.126-1.833c-.979-8.83-6.863-10.665-6.863-10.665");
}

.jkmho4-la {
  stop-color: var(--svg-color--ff6700, #FF6700);
  stop-opacity: 0;
}

.jzrs3dbvo {
  stop-color: var(--svg-color--b6d740, #B6D740);
}

.lxyh5oakp {
  d: path("M22.12 7.7h-5.035a4.954 4.954 0 0 1 4.935-4.46h5.035A4.96 4.96 0 0 1 22.12 7.7");
}

.nemkkdb0f {
  stop-color: var(--svg-color--b5df5a, #B5DF5A);
  stop-opacity: 0.5;
}

.nkbzqo3uj {
  stop-color: var(--svg-color--cced63, #CCED63);
  stop-opacity: 0;
}

.nv3-lgb7b {
  stop-color: var(--svg-color--d2f168, #D2F168);
}

.nxd2g-34i {
  stop-color: var(--svg-color--ff458f, #FF458F);
}

.osmw32b6k {
  stop-color: var(--svg-color--db9263, #DB9263);
  stop-opacity: 0;
}

.ov85rttnb {
  stop-color: var(--svg-color--add558, #ADD558);
  stop-opacity: 0;
}

.p-f-u_bpt {
  stop-color: var(--svg-color--ffad60, #FFAD60);
  stop-opacity: 0.4;
}

.p4jldr6gm {
  stop-color: var(--svg-color--ff8704, #FF8704);
}

.plp63kb-n {
  stop-color: var(--svg-color--b5df5a, #B5DF5A);
}

.plt72-cpb {
  stop-color: var(--svg-color--cced63, #CCED63);
}

.qoo971gwk {
  d: path("M11.02 7.7a4.96 4.96 0 0 1-4.935-4.46h5.035a4.965 4.965 0 0 1 4.934 4.46z");
}

.rjlkldbta {
  d: path("M27.435 2.946c0 2.737-2.703 5.007-5.407 5.007h-2.536c-1.558.13-2.705 0-2.705 0h2.705c2.685-.225 6.591-1.225 7.943-5.007");
}

.slaorzbbf {
  d: path("M4.13 17.517c-.715-5.46 2.07-6.647 3.444-5.244s-2.427 6.11 4.78 13.895c0 0-7.508-3.192-8.224-8.651");
}

.sm0nlcukq {
  stop-color: var(--svg-color--ff5d5b, #FF5D5B);
}

.sso4v_buz {
  stop-color: var(--svg-color--c0e148, #C0E148);
}

.tsthfc-sx {
  stop-color: var(--svg-color--ff8e2d, #FF8E2D);
}

.u7nd3_f2e {
  stop-color: var(--svg-color--ff9068, #FF9068);
  stop-opacity: 0.6;
}

.ukh2v6_wz {
  stop-color: var(--svg-color--ff9068, #FF9068);
  stop-opacity: 0;
}

.vbw58rbxo {
  stop-color: var(--svg-color--db9263, #DB9263);
}

.vicy7xbfz {
  stop-color: var(--svg-color--ffc98a, #FFC98A);
}

.vm4u-79hr {
  stop-color: var(--svg-color--83b337, #83B337);
}

.wi3d_9b6k {
  d: path("M11.12 2.74H5.56a5.46 5.46 0 0 0 5.46 5.46h5.56c-.01-3.02-2.45-5.46-5.46-5.46");
}

.wz747hb4o {
  stop-color: var(--svg-color--86b528, #86B528);
}

.x7-rw1b5w {
  stop-color: var(--svg-color--90ba2a, #90BA2A);
}

.xgazf3bqf {
  d: path("M16.559 7.535c3.094-.535 5.313-.775 8.054.539c-1.347 2.507-1.322 7.446-1.191 10.126q.097.87.126 1.833s-.072-.723-.126-1.833c-.979-8.83-6.863-10.665-6.863-10.665");
}

.yid_v2bte {
  d: path("M22.02 2.74h5.56a5.46 5.46 0 0 1-5.46 5.46h-5.56c0-3.02 2.44-5.46 5.46-5.46");
}

.zi18cob7s {
  d: path("M6.66 3.094h4.378c2.836 0 5.214 2.103 5.224 4.948c-1.995-5.179-4.694-4.434-9.603-4.948");
}

</style>
