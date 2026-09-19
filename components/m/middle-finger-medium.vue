<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iRrWTvd)"><path fill="url(#ix6AgGc)" class="f7p6tkbxz"/><path fill="url(#iGc7phc)" class="f7p6tkbxz"/><path fill="url(#i36beeb)" class="f7p6tkbxz"/><path fill="url(#i32ZFLj)" class="f7p6tkbxz"/><path fill="url(#iejUQQQ)" class="f7p6tkbxz"/><path fill="url(#ihvxWQd)" class="f7p6tkbxz"/><path fill="url(#iChK0mc)" class="f7p6tkbxz"/><path fill="url(#ixgZABb)" class="f7p6tkbxz"/><path fill="url(#iQ7zHeb)" class="f7p6tkbxz"/></g><path fill="url(#iHNzOBd)" class="f7p6tkbxz"/><path fill="url(#iWi7vMe)" class="f7p6tkbxz"/><rect fill="url(#iKY8jPi)" class="yepf0fbcr"/><rect fill="url(#ie4lokw)" class="yepf0fbcr"/><rect fill="url(#ix56Oub)" class="yepf0fbcr"/><rect fill="url(#ieOryjB)" class="yepf0fbcr"/><rect fill="url(#ihcvROd)" class="yepf0fbcr"/><g filter="url(#iFuMRPd)"><path stroke="url(#iXLjkjb)" class="q_7w00bst"/></g><g filter="url(#idb4lid)"><path stroke="url(#ilej1be)" class="obf4jpw-q"/></g><g filter="url(#iuqVHuG)"><path stroke="url(#iWzgGEe)" class="rsndbbg_u"/></g><g filter="url(#isXtsbc)"><path stroke="url(#ioxl55b)" class="x9k5_onzk"/></g><defs><radialGradient id="ix6AgGc" cx="0" cy="0" r="1" gradientTransform="rotate(130.4 8.799 12.719)scale(19.2866 13.5561)" gradientUnits="userSpaceOnUse"><stop class="o3ix6_bjr"/><stop offset="1" class="vv_jzobyt"/></radialGradient><radialGradient id="iGc7phc" cx="0" cy="0" r="1" gradientTransform="matrix(1.53125 2.84374 -2.45715 1.32308 8.438 13.45)" gradientUnits="userSpaceOnUse"><stop class="fnewwnbgg"/><stop offset="1" class="yydcwmbtq"/></radialGradient><radialGradient id="i36beeb" cx="0" cy="0" r="1" gradientTransform="matrix(.2806 2.65005 -2.93551 .31082 7.512 15.198)" gradientUnits="userSpaceOnUse"><stop class="wuw2accwx"/><stop offset="1" class="aj-1lsmxe"/></radialGradient><radialGradient id="i32ZFLj" cx="0" cy="0" r="1" gradientTransform="rotate(-56.31 20.158 -10.885)scale(1.88757 1.05297)" gradientUnits="userSpaceOnUse"><stop class="ah4bobcoa"/><stop offset="1" class="jnyqczbzd"/><stop offset="1" class="jsdp6pnbk"/></radialGradient><radialGradient id="iejUQQQ" cx="0" cy="0" r="1" gradientTransform="rotate(133.299 9.003 10.92)scale(2.23279 1.21415)" gradientUnits="userSpaceOnUse"><stop class="z5kw83b2o"/><stop offset="1" class="qabboz3vz"/></radialGradient><radialGradient id="ihvxWQd" cx="0" cy="0" r="1" gradientTransform="rotate(130.957 9.905 12.492)scale(2.93794 3.62296)" gradientUnits="userSpaceOnUse"><stop class="lr7zxlymh"/><stop offset="1" class="rjwpbidgh"/></radialGradient><radialGradient id="iChK0mc" cx="0" cy="0" r="1" gradientTransform="matrix(-.95712 2.1193 -1.60697 -.72574 20.544 12.578)" gradientUnits="userSpaceOnUse"><stop class="y5pwjv0kt"/><stop offset="1" class="lckhs0byv"/></radialGradient><radialGradient id="ixgZABb" cx="0" cy="0" r="1" gradientTransform="rotate(46.202 -13.867 17.735)scale(1.58029 .60823)" gradientUnits="userSpaceOnUse"><stop class="smhia43ly"/><stop offset="1" class="ezdhfiznq"/></radialGradient><radialGradient id="iQ7zHeb" cx="0" cy="0" r="1" gradientTransform="matrix(.85937 2.34375 -1.4916 .54692 12.39 11.781)" gradientUnits="userSpaceOnUse"><stop class="hqat1d8hc"/><stop offset="1" class="mlfrjgb6a"/></radialGradient><radialGradient id="iHNzOBd" cx="0" cy="0" r="1" gradientTransform="matrix(-18.56652 4.0743 -6.61005 -30.12186 25.541 19.076)" gradientUnits="userSpaceOnUse"><stop offset=".866" class="ky6winvfu"/><stop offset="1" class="iwv-i9b1x"/></radialGradient><radialGradient id="iWi7vMe" cx="0" cy="0" r="1" gradientTransform="matrix(-18.34738 4.08297 -6.6241 -29.76625 25.541 19.076)" gradientUnits="userSpaceOnUse"><stop offset=".976" class="can-iz3yi"/><stop offset="1" class="ytt_t5bbb"/></radialGradient><radialGradient id="ihcvROd" cx="0" cy="0" r="1" gradientTransform="matrix(.87792 2.66303 -4.99485 1.64666 13.84 1.617)" gradientUnits="userSpaceOnUse"><stop class="vdetz6bti"/><stop offset="1" class="bmgs3ee3d"/></radialGradient><linearGradient id="iKY8jPi" x1="13.092" x2="15.793" y1="9.78" y2="9.78" gradientUnits="userSpaceOnUse"><stop class="z2dwflb2a"/><stop offset="1" class="tf6erbn5j"/></linearGradient><linearGradient id="ie4lokw" x1="18.889" x2="15.27" y1="10.783" y2="11.35" gradientUnits="userSpaceOnUse"><stop class="a2fo3b0kr"/><stop offset="1" class="lu7cr5b6h"/></linearGradient><linearGradient id="ix56Oub" x1="14.733" x2="13.759" y1="14.287" y2="15.621" gradientUnits="userSpaceOnUse"><stop class="o178q4qly"/><stop offset="0" class="o2ezx-nou"/><stop offset="1" class="ap20oobtl"/></linearGradient><linearGradient id="ieOryjB" x1="15.314" x2="17.057" y1="14.595" y2="15.86" gradientUnits="userSpaceOnUse"><stop class="f_84sgb_v"/><stop offset="1" class="deobogk9w"/></linearGradient><linearGradient id="iXLjkjb" x1="24.565" x2="20.575" y1="14.264" y2="30.054" gradientUnits="userSpaceOnUse"><stop class="s3115pb1b"/><stop offset="1" class="auu1_fbgs"/></linearGradient><linearGradient id="ilej1be" x1="17.212" x2="9.854" y1="3.293" y2="15.396" gradientUnits="userSpaceOnUse"><stop class="xd1qixbwn"/><stop offset="1" class="xp3m0tmzy"/></linearGradient><linearGradient id="iWzgGEe" x1="17.974" x2="17.68" y1="13.246" y2="17.455" gradientUnits="userSpaceOnUse"><stop class="mkax12uzr"/><stop offset="1" class="ttkdjubcy"/></linearGradient><linearGradient id="ioxl55b" x1="11.656" x2="11.966" y1="12.875" y2="16.619" gradientUnits="userSpaceOnUse"><stop class="bue2cdcwr"/><stop offset="1" class="gvqtcc7ik"/></linearGradient><filter id="iRrWTvd" width="19.914" height="28.977" x="6.168" y="1.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.34902 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5372"/></filter><filter id="iFuMRPd" width="8.938" height="16.887" x="18.359" y="11.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5372" stdDeviation="1.25"/></filter><filter id="idb4lid" width="3.75" height="13.8" x="14.125" y="2.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5372" stdDeviation=".625"/></filter><filter id="iuqVHuG" width="4.222" height="4.735" x="14.28" y="12.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5372" stdDeviation=".375"/></filter><filter id="isXtsbc" width="4.722" height="5.235" x="11.398" y="12.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5372" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:middle-finger-medium" /></template>
<style>
.a2fo3b0kr {
  stop-color: var(--svg-color--c59c81, #C59C81);
}

.ah4bobcoa {
  stop-color: var(--svg-color--8d6a53, #8D6A53);
}

.aj-1lsmxe {
  stop-color: var(--svg-color--806555, #806555);
  stop-opacity: 0;
}

.ap20oobtl {
  stop-color: var(--svg-color--b1827a, #B1827A);
}

.auu1_fbgs {
  stop-color: var(--svg-color--d0a78f, #D0A78F);
  stop-opacity: 0;
}

.bmgs3ee3d {
  stop-color: var(--svg-color--a5856b, #A5856B);
  stop-opacity: 0;
}

.bue2cdcwr {
  stop-color: var(--svg-color--8b645a, #8B645A);
}

.can-iz3yi {
  stop-color: var(--svg-color--9d716a, #9D716A);
  stop-opacity: 0;
}

.deobogk9w {
  stop-color: var(--svg-color--b4877a, #B4877A);
}

.ezdhfiznq {
  stop-color: var(--svg-color--775a4b, #775A4B);
  stop-opacity: 0;
}

.f_84sgb_v {
  stop-color: var(--svg-color--b4877a, #B4877A);
  stop-opacity: 0;
}

.f7p6tkbxz {
  d: path("M12.645 4.402a2.39 2.39 0 0 1 4.78 0v7.587a2.391 2.391 0 0 1 4.242 1.146a2.39 2.39 0 0 1 4.119 2.07l-.29 2.854c-.117 1.242-.84 6.046-2.527 7.937c-1.825 2.456-4.576 3.992-7.645 3.992A8.353 8.353 0 0 1 7.03 22.62l-.784-4.457a2.28 2.28 0 0 1 2.6-2.835a2.602 2.602 0 0 1 3.798-3.11z");
}

.fnewwnbgg {
  stop-color: var(--svg-color--8f705c, #8F705C);
}

.ft5dv1b6b {
  fill: none;
}

.gvqtcc7ik {
  stop-color: var(--svg-color--8b645a, #8B645A);
  stop-opacity: 0;
}

.hqat1d8hc {
  stop-color: var(--svg-color--6a4f40, #6A4F40);
}

.iwv-i9b1x {
  stop-color: var(--svg-color--946764, #946764);
}

.jnyqczbzd {
  stop-color: var(--svg-color--74584e, #74584E);
  stop-opacity: 0;
}

.jsdp6pnbk {
  stop-color: var(--svg-color--8d6a53, #8D6A53);
  stop-opacity: 0;
}

.ky6winvfu {
  stop-color: var(--svg-color--946764, #946764);
  stop-opacity: 0;
}

.lckhs0byv {
  stop-color: var(--svg-color--cea688, #CEA688);
  stop-opacity: 0;
}

.lr7zxlymh {
  stop-color: var(--svg-color--c5a183, #C5A183);
}

.lu7cr5b6h {
  stop-color: var(--svg-color--c59c81, #C59C81);
  stop-opacity: 0;
}

.mkax12uzr {
  stop-color: var(--svg-color--cfa68b, #CFA68B);
}

.mlfrjgb6a {
  stop-color: var(--svg-color--6a4f40, #6A4F40);
  stop-opacity: 0;
}

.o178q4qly {
  stop-color: var(--svg-color--8c5f5e, #8C5F5E);
  stop-opacity: 0;
}

.o2ezx-nou {
  stop-color: var(--svg-color--b1827a, #B1827A);
  stop-opacity: 0;
}

.o3ix6_bjr {
  stop-color: var(--svg-color--b98e7b, #B98E7B);
}

.obf4jpw-q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M16 4.158v10.05");
}

.q_7w00bst {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M24.048 14.937c-.046 1.014-.215 3.148-.695 5.676s-1.362 4.194-1.744 4.711");
}

.qabboz3vz {
  stop-color: var(--svg-color--987762, #987762);
  stop-opacity: 0;
}

.rjwpbidgh {
  stop-color: var(--svg-color--c5a183, #C5A183);
  stop-opacity: 0;
}

.rsndbbg_u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m15.28 16.03l2.222-2.734");
}

.s3115pb1b {
  stop-color: var(--svg-color--d0a78f, #D0A78F);
}

.smhia43ly {
  stop-color: var(--svg-color--775a4b, #775A4B);
}

.tf6erbn5j {
  stop-color: var(--svg-color--936b60, #936B60);
  stop-opacity: 0;
}

.ttkdjubcy {
  stop-color: var(--svg-color--cfa68b, #CFA68B);
  stop-opacity: 0;
}

.vdetz6bti {
  stop-color: var(--svg-color--a5856b, #A5856B);
}

.vv_jzobyt {
  stop-color: var(--svg-color--ac7c78, #AC7C78);
}

.wuw2accwx {
  stop-color: var(--svg-color--806555, #806555);
}

.x9k5_onzk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m14.87 16.03l-2.222-2.734");
}

.xd1qixbwn {
  stop-color: var(--svg-color--cfa78e, #CFA78E);
}

.xp3m0tmzy {
  stop-color: var(--svg-color--cfa78e, #CFA78E);
  stop-opacity: 0;
}

.y5pwjv0kt {
  stop-color: var(--svg-color--cea688, #CEA688);
}

.yepf0fbcr {
  width: 4.781px;
  height: 14.813px;
  x: 12.648px;
  y: 2.012px;
  rx: 2.391px;
}

.ytt_t5bbb {
  stop-color: var(--svg-color--9d716a, #9D716A);
}

.yydcwmbtq {
  stop-color: var(--svg-color--8f705c, #8F705C);
  stop-opacity: 0;
}

.z2dwflb2a {
  stop-color: var(--svg-color--936b60, #936B60);
}

.z5kw83b2o {
  stop-color: var(--svg-color--987762, #987762);
}

</style>
