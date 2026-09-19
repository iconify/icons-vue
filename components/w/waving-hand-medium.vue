<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="e27bo2hjb"/><path fill="url(#iH0lzfc)" class="ymcz05bgh"/><path fill="url(#itAIwje)" class="ymcz05bgh"/><path fill="url(#i3JK9je)" class="i2g5lq_8h"/><path fill="url(#ipVdXpX)" class="i2g5lq_8h"/><path fill="url(#i3dpbfP)" class="i2g5lq_8h"/><path fill="url(#iwDKCPc)" class="i2g5lq_8h"/><path fill="url(#i5MqhKV)" class="i2g5lq_8h"/><path fill="url(#iOCKwad)" class="w8ik5kb4l"/><path fill="url(#iKKU8Ob)" class="w8ik5kb4l"/><path fill="url(#iYZf2ne)" class="w8ik5kb4l"/><path fill="url(#iuZUZ4b)" class="w8ik5kb4l"/><path fill="url(#iF8tHJc)" class="w8ik5kb4l"/><g filter="url(#i6kFyhe)"><path class="o2t390wlc"/></g><g filter="url(#ioBJYCd)"><path class="p6i82d7hq"/><path fill="url(#iFg0xte)" class="rrrpenbho"/></g><g filter="url(#iY5dXre)"><ellipse fill="url(#i63y6Mc)" transform="rotate(-29.74 28.164 11.32)" class="b6l-5mbrj"/></g><g filter="url(#iG6UNyd)"><path class="pwfr29imc"/></g><g filter="url(#iQyyBme)"><path fill="url(#iCt786b)" class="ho-p919zk"/></g><path fill="url(#il4bO7L)" class="wjpozccyw"/><path fill="url(#i5SoMjc)" class="wjpozccyw"/><path fill="url(#iWZ6lXd)" class="wjpozccyw"/><path fill="url(#iGefVLh)" class="wjpozccyw"/><path fill="url(#ilX0TUc)" class="h46ghk6cn"/><path fill="url(#iijcorc)" class="h46ghk6cn"/><g filter="url(#i1zJM4b)"><path class="wiry0-bwi"/></g><g filter="url(#iHzIdue)"><path class="kqivx2rtg"/></g><g filter="url(#irqrBlb)"><path stroke="url(#ir2mTGS)" class="hej7y5urj"/></g><g filter="url(#ikNpLzc)"><path class="l3gxjyh7l"/><path stroke="url(#iRrEtpE)" class="z5pol9bvk"/></g><g filter="url(#iqVaqxc)"><path class="q5mwj2bpq"/><path stroke="url(#iuXF37b)" class="c5f8q6bth"/></g><path stroke="url(#isJpAAc)" class="ivt52iv4f"/><path stroke="url(#iSsgKRT)" class="ivt52iv4f"/><path stroke="url(#iUsALte)" class="zjmnh5tuh"/><path stroke="url(#i2uWvgA)" class="zjmnh5tuh"/><g filter="url(#ipTtnfb)"><path class="eidlcumqs"/></g><g filter="url(#iI2iVRd)"><path class="y2uoumjad"/></g><g filter="url(#imawnxe)"><path class="jzzifgbmv"/></g><defs><radialGradient id="iH0lzfc" cx="0" cy="0" r="1" gradientTransform="rotate(98.848 5.618 17.374)scale(16.6966 17.7193)" gradientUnits="userSpaceOnUse"><stop offset=".779" class="y1bncpb2x"/><stop offset="1" class="s5u211w7l"/></radialGradient><radialGradient id="i3JK9je" cx="0" cy="0" r="1" gradientTransform="rotate(156.037 10.42 8.078)scale(4.10207 8.61847)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="dhhq2noev"/><stop offset="1" class="vn9j6bcji"/></radialGradient><radialGradient id="ipVdXpX" cx="0" cy="0" r="1" gradientTransform="rotate(154.952 10.364 8.193)scale(5.1506 12.9593)" gradientUnits="userSpaceOnUse"><stop offset=".769" class="x9diso5po"/><stop offset="1" class="xol3sj3nk"/></radialGradient><radialGradient id="iwDKCPc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.591 15.91 1.399)scale(3.72686 .79712)" gradientUnits="userSpaceOnUse"><stop class="f694gm54t"/><stop offset="1" class="akz-xebip"/></radialGradient><radialGradient id="i5MqhKV" cx="0" cy="0" r="1" gradientTransform="rotate(84.463 6.569 13.732)scale(2.29203 2.86609)" gradientUnits="userSpaceOnUse"><stop class="htzqp4bmx"/><stop offset="1" class="essb3qbce"/></radialGradient><radialGradient id="iOCKwad" cx="0" cy="0" r="1" gradientTransform="rotate(146.452 5.632 10.211)scale(3.50589 9.38314)" gradientUnits="userSpaceOnUse"><stop offset=".425" class="lj6-6xbkg"/><stop offset="1" class="hm7ovmbun"/></radialGradient><radialGradient id="iKKU8Ob" cx="0" cy="0" r="1" gradientTransform="matrix(-3.875 2.43748 -6.52366 -10.37103 15.969 15.61)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="mo74wksyz"/><stop offset="1" class="fleblv_-n"/></radialGradient><radialGradient id="iYZf2ne" cx="0" cy="0" r="1" gradientTransform="rotate(-32.681 36.166 -12.852)scale(3.93552 24.9102)" gradientUnits="userSpaceOnUse"><stop offset=".692" class="ry489_bsm"/><stop offset="1" class="v0t-ucb-b"/></radialGradient><radialGradient id="iF8tHJc" cx="0" cy="0" r="1" gradientTransform="matrix(.27556 2.28608 -2.69994 .32545 12.74 11.218)" gradientUnits="userSpaceOnUse"><stop class="yy1sefn2s"/><stop offset="1" class="a_3turbnx"/></radialGradient><radialGradient id="iFg0xte" cx="0" cy="0" r="1" gradientTransform="rotate(-77.656 23.9 -6.9)scale(5.26228 2.27148)" gradientUnits="userSpaceOnUse"><stop class="bc-j2cvty"/><stop offset="1" class="n3cg72bca"/></radialGradient><radialGradient id="i63y6Mc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69946 .39095 -.54292 -2.3601 28.784 11.323)" gradientUnits="userSpaceOnUse"><stop class="pjl-eibvn"/><stop offset="1" class="cdl2eclmr"/></radialGradient><radialGradient id="iCt786b" cx="0" cy="0" r="1" gradientTransform="rotate(113.948 8.56 19.112)scale(12.2413 6.11907)" gradientUnits="userSpaceOnUse"><stop class="ubfibhb8p"/><stop offset="1" class="iwd5b1dfm"/></radialGradient><radialGradient id="il4bO7L" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74425 2.16183 -5.117 -8.86255 18.94 12.488)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="gsqd3fbuc"/><stop offset="1" class="ps9b87bmr"/></radialGradient><radialGradient id="i5SoMjc" cx="0" cy="0" r="1" gradientTransform="rotate(155.037 8.377 8.288)scale(1.99927 7.66345)" gradientUnits="userSpaceOnUse"><stop class="zt52bkbqx"/><stop offset="1" class="hs0rixbhx"/></radialGradient><radialGradient id="iGefVLh" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 2.5 -2.76076 .31059 15.446 6.68)" gradientUnits="userSpaceOnUse"><stop class="b_lanbb4s"/><stop offset="1" class="cmhqf5b8y"/></radialGradient><radialGradient id="ilX0TUc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15624 .96876 -3.28463 -3.9203 14.313 18.547)" gradientUnits="userSpaceOnUse"><stop class="k54ioxb9c"/><stop offset="1" class="fqq1f6-ge"/></radialGradient><radialGradient id="iijcorc" cx="0" cy="0" r="1" gradientTransform="matrix(.2813 2.1063 -2.74727 .36691 11.12 15.872)" gradientUnits="userSpaceOnUse"><stop class="fyn7nub_u"/><stop offset="1" class="ih52_ybrt"/></radialGradient><radialGradient id="iRrEtpE" cx="0" cy="0" r="1" gradientTransform="matrix(1.54687 -1.53125 3.91781 3.95778 22.844 5.469)" gradientUnits="userSpaceOnUse"><stop class="kzdh98h8q"/><stop offset=".744" class="t68_d7h5n"/></radialGradient><radialGradient id="iuXF37b" cx="0" cy="0" r="1" gradientTransform="matrix(1.6667 -1.60486 4.1034 4.26156 20.83 7.183)" gradientUnits="userSpaceOnUse"><stop class="kzdh98h8q"/><stop offset=".862" class="t68_d7h5n"/></radialGradient><radialGradient id="iSsgKRT" cx="0" cy="0" r="1" gradientTransform="rotate(164.814 1.832 9.818)scale(2.26665 6.09358)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="l96_08dtf"/><stop offset="1" class="mes48ob5k"/></radialGradient><radialGradient id="i2uWvgA" cx="0" cy="0" r="1" gradientTransform="matrix(-2.08905 .55293 -1.45444 -5.4951 4.177 20.5)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="l96_08dtf"/><stop offset="1" class="mes48ob5k"/></radialGradient><filter id="i6kFyhe" width="5.595" height="8.26" x="11.937" y="11.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1118" stdDeviation=".375"/></filter><filter id="ioBJYCd" width="5.458" height="10.186" x="24.37" y="9.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.368627 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1118"/></filter><filter id="iY5dXre" width="2.735" height="3.069" x="26.797" y="9.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1118" stdDeviation=".25"/></filter><filter id="iG6UNyd" width="6.259" height="7.813" x="22.905" y="14.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1118" stdDeviation=".5"/></filter><filter id="iQyyBme" width="6.88" height="14" x="23.281" y="15.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1118" stdDeviation=".75"/></filter><filter id="i1zJM4b" width="11.875" height="11.063" x="13" y="13.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1118" stdDeviation=".75"/></filter><filter id="iHzIdue" width="7.072" height="11.259" x="18.112" y="5.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1118" stdDeviation=".6"/></filter><filter id="irqrBlb" width="4.444" height="6.709" x="20.09" y="9.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1118" stdDeviation=".35"/></filter><filter id="ikNpLzc" width="5.549" height="6.363" x="20.362" y="2.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0823529 0 0 0 0 0.337255 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1118"/></filter><filter id="iqVaqxc" width="5.902" height="6.621" x="18.191" y="3.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0823529 0 0 0 0 0.337255 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1118"/></filter><filter id="ipTtnfb" width="5.285" height="6.928" x="10.346" y="16.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1118" stdDeviation=".375"/></filter><filter id="iI2iVRd" width="6.281" height="10.797" x="14.5" y="6.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1118" stdDeviation=".5"/></filter><filter id="imawnxe" width="2.688" height="2.59" x="18" y="15.233" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1118" stdDeviation=".25"/></filter><linearGradient id="itAIwje" x1="24.144" x2="12.456" y1="18.153" y2="28.431" gradientUnits="userSpaceOnUse"><stop offset=".702" class="y1bncpb2x"/><stop offset="1" class="s5u211w7l"/></linearGradient><linearGradient id="i3dpbfP" x1="21.137" x2="20.043" y1="16.255" y2="13.961" gradientUnits="userSpaceOnUse"><stop class="elyy913hw"/><stop offset="1" class="tg0ay4bgk"/></linearGradient><linearGradient id="iuZUZ4b" x1="16.813" x2="15.094" y1="19.359" y2="18.453" gradientUnits="userSpaceOnUse"><stop class="elyy913hw"/><stop offset="1" class="tg0ay4bgk"/></linearGradient><linearGradient id="iWZ6lXd" x1="17.656" x2="16.797" y1="17.969" y2="15.328" gradientUnits="userSpaceOnUse"><stop class="elyy913hw"/><stop offset="1" class="tg0ay4bgk"/></linearGradient><linearGradient id="ir2mTGS" x1="23.5" x2="21.031" y1="14.797" y2="10.391" gradientUnits="userSpaceOnUse"><stop class="tx8rsiv4m"/><stop offset="1" class="lohqf-b1b"/></linearGradient><linearGradient id="isJpAAc" x1="5.469" x2="8.656" y1="16.195" y2="22.828" gradientUnits="userSpaceOnUse"><stop class="norwhxbmc"/><stop offset="1" class="ez4l67b7b"/></linearGradient><linearGradient id="iUsALte" x1="3.505" x2="7.247" y1="18.063" y2="26.183" gradientUnits="userSpaceOnUse"><stop offset=".298" class="norwhxbmc"/><stop offset="1" class="ez4l67b7b"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:waving-hand-medium" /></template>
<style>
.a_3turbnx {
  stop-color: var(--svg-color--9f806a, #9F806A);
  stop-opacity: 0;
}

.akz-xebip {
  stop-color: var(--svg-color--725a4e, #725A4E);
  stop-opacity: 0;
}

.b_lanbb4s {
  stop-color: var(--svg-color--ae8e74, #AE8E74);
}

.b6l-5mbrj {
  cx: 28.164px;
  cy: 11.32px;
  rx: 0.773px;
  ry: 1.106px;
}

.bc-j2cvty {
  stop-color: var(--svg-color--a27570, #A27570);
}

.c5f8q6bth {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M18.64 4.207c1.75.059 5.016 1.574 4.899 5.621");
}

.cdl2eclmr {
  stop-color: var(--svg-color--cea78d, #CEA78D);
  stop-opacity: 0;
}

.cmhqf5b8y {
  stop-color: var(--svg-color--ae8e74, #AE8E74);
  stop-opacity: 0;
}

.dhhq2noev {
  stop-color: var(--svg-color--8d5d5d, #8D5D5D);
  stop-opacity: 0;
}

.e27bo2hjb {
  fill: var(--svg-color--b18378, #B18378);
  d: path("M19.145 6.2a2.09 2.09 0 0 1 2.01 1.516c.8 2.323 2.25 5.629 3.327 7.123a7 7 0 0 0 .389-1.652c.02-.188.152-1.41.336-1.956c.221-.658.678-1.224 1.364-1.446c1.117-.36 2.33.3 2.71 1.477q.053.162.08.326c.13.56.04 1.073-.014 1.412a61 61 0 0 0-.359 2.625a19.6 19.6 0 0 0 .125 4.781c.3 1.413.219 2.912.14 3.485c-.86 6.31-7.847 6.78-9.812 5.85c-1.339-.435-2.758-1.47-4.71-3.468c-2.283-2.335-4.368-4.905-5.529-6.643a2.067 2.067 0 0 1 2.276-3.216c-.377-.735-.68-1.377-.917-2.087a2.067 2.067 0 0 1 3.534-2.007c-.12-.267-.835-2.032-.96-2.854a2.089 2.089 0 0 1 6.01-3.266");
}

.eidlcumqs {
  fill: var(--svg-color--c8a08b, #C8A08B);
  d: path("M14.739 22.893a54 54 0 0 1-3.514-4.318a.696.696 0 0 1 .14-.953a.72.72 0 0 1 1.011.112l2.504 3.113c.012.9-.089 1.74-.141 2.046");
}

.elyy913hw {
  stop-color: var(--svg-color--b18378, #B18378);
}

.essb3qbce {
  stop-color: var(--svg-color--8b6d5f, #8B6D5F);
  stop-opacity: 0;
}

.ez4l67b7b {
  stop-color: var(--svg-color--0d5194, #0D5194);
}

.f694gm54t {
  stop-color: var(--svg-color--725a4e, #725A4E);
}

.fleblv_-n {
  stop-color: var(--svg-color--805546, #805546);
}

.fqq1f6-ge {
  stop-color: var(--svg-color--a57b68, #A57B68);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyn7nub_u {
  stop-color: var(--svg-color--906f59, #906F59);
}

.gsqd3fbuc {
  stop-color: var(--svg-color--85544f, #85544F);
  stop-opacity: 0;
}

.h46ghk6cn {
  d: path("M11.478 16.414a2.067 2.067 0 0 0-2.276 3.216c1.004 1.503 2.7 3.629 4.616 5.687c2.378-1.114 2.166-3.38 1.76-3.861c-.007.022-2.024-2.79-3.004-4.034l-.049-.062c-.303-.387-.666-.85-1.04-.946c-.145-.265-.146-.272-.007 0");
}

.hej7y5urj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-7px, 0.7px);
  d: path("M21.14 10.438c.344.802 1.17 2.909 2.344 4.609");
}

.hm7ovmbun {
  stop-color: var(--svg-color--966562, #966562);
}

.ho-p919zk {
  d: path("M24.845 16.936c.506.759 2.301 1.622 3.405 1.86c.458 1.22 1.219 6.813-2.156 9.032c.785-1.374 1.335-6.449-1.25-10.892");
}

.hs0rixbhx {
  stop-color: var(--svg-color--82574b, #82574B);
  stop-opacity: 0;
}

.htzqp4bmx {
  stop-color: var(--svg-color--ac8c73, #AC8C73);
}

.i2g5lq_8h {
  d: path("M17.056 8.263c.029.248.102.566.252.956q.097.257.237.643c.445 1.22 1.206 3.308 2.25 5.21c.393.716 1.11 1.22 1.927 1.181c1.076-.05 2.312-.405 2.786-1.464l-.003-.01l-.023.06c-1.077-1.494-2.527-4.8-3.327-7.123a2.09 2.09 0 0 0-4.099.547");
}

.ih52_ybrt {
  stop-color: var(--svg-color--906f59, #906F59);
  stop-opacity: 0;
}

.ivt52iv4f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M4.379 16.195c-.2 2.47 1.191 5.22 4.676 5.797");
}

.iwd5b1dfm {
  stop-color: var(--svg-color--cea48e, #CEA48E);
  stop-opacity: 0;
}

.jzzifgbmv {
  stroke: var(--svg-color--b9917f, #B9917F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M18.875 16.948c.27-.195.559-.414.938-.84");
}

.k54ioxb9c {
  stop-color: var(--svg-color--a57b68, #A57B68);
}

.kqivx2rtg {
  stroke: var(--svg-color--cea58e, #CEA58E);
  stroke-linecap: round;
  d: path("M19.813 7.39c.53 2.282 2.515 6.079 3.671 7.86");
}

.kzdh98h8q {
  stop-color: var(--svg-color--16579c, #16579C);
}

.l3gxjyh7l {
  stroke: var(--svg-color--1b99e7, #1B99E7);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M20.812 2.629c1.758.125 4.641 1.598 4.547 5.363");
}

.l96_08dtf {
  stop-color: var(--svg-color--0e5196, #0E5196);
  stop-opacity: 0;
}

.lj6-6xbkg {
  stop-color: var(--svg-color--966562, #966562);
  stop-opacity: 0;
}

.lohqf-b1b {
  stop-color: var(--svg-color--bd9684, #BD9684);
  stop-opacity: 0;
}

.mes48ob5k {
  stop-color: var(--svg-color--0e5196, #0E5196);
}

.mo74wksyz {
  stop-color: var(--svg-color--805546, #805546);
  stop-opacity: 0;
}

.n3cg72bca {
  stop-color: var(--svg-color--a27570, #A27570);
  stop-opacity: 0;
}

.norwhxbmc {
  stop-color: var(--svg-color--1679c5, #1679C5);
}

.o2t390wlc {
  fill: var(--svg-color--c8a08b, #C8A08B);
  d: path("M16.177 19.5c-1.701-2.814-2.796-4.85-3.41-5.896a.577.577 0 0 1 .167-.768a.555.555 0 0 1 .792.182l1.369 2.377l1.686 3.058c-.187.5-.406.89-.604 1.047");
}

.p6i82d7hq {
  fill: var(--svg-color--b18378, #B18378);
  d: path("m24.478 14.834l.004.005c.19-.492.329-1.11.389-1.652l.002-.018c.026-.238.156-1.407.334-1.938c.221-.658.678-1.224 1.364-1.446c1.117-.36 2.33.3 2.71 1.477q.053.163.08.326c.126.538.047 1.034-.007 1.373l-.006.039a61 61 0 0 0-.36 2.625c-.094.9-.153 2.327.02 3.967c-2.27.437-3.664-.998-4.135-1.826c-.509-.896-.614-2.598-.395-2.932");
}

.pjl-eibvn {
  stop-color: var(--svg-color--cea78d, #CEA78D);
}

.ps9b87bmr {
  stop-color: var(--svg-color--85544f, #85544F);
}

.pwfr29imc {
  fill: var(--svg-color--b5897b, #B5897B);
  d: path("M28.164 19.484a4.5 4.5 0 0 1-3.5-4.062c-.469.208-1 1.86-.64 2.969c.702 2.17 2.984 2.823 3.609 2.843z");
}

.q5mwj2bpq {
  stroke: var(--svg-color--1b99e7, #1B99E7);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M18.64 4.207c1.75.059 5.016 1.574 4.899 5.621");
}

.rrrpenbho {
  d: path("m24.478 14.834l.004.005c.19-.492.329-1.11.389-1.652l.002-.018c.026-.238.156-1.407.334-1.938c.221-.658.678-1.224 1.364-1.446c1.117-.36 2.33.3 2.71 1.477q.053.163.08.326c.126.538.047 1.034-.007 1.373l-.006.039a61 61 0 0 0-.36 2.625c-.094.9-.153 2.327.02 3.967c-2.27.437-3.664-.998-4.135-1.826c-.509-.896-.614-2.598-.395-2.932");
}

.ry489_bsm {
  stop-color: var(--svg-color--805d48, #805D48);
  stop-opacity: 0;
}

.s5u211w7l {
  stop-color: var(--svg-color--9b5c8b, #9B5C8B);
}

.t68_d7h5n {
  stop-color: var(--svg-color--16579c, #16579C);
  stop-opacity: 0;
}

.tg0ay4bgk {
  stop-color: var(--svg-color--b18378, #B18378);
  stop-opacity: 0;
}

.tx8rsiv4m {
  stop-color: var(--svg-color--bd9684, #BD9684);
}

.ubfibhb8p {
  stop-color: var(--svg-color--cea48e, #CEA48E);
}

.v0t-ucb-b {
  stop-color: var(--svg-color--805d48, #805D48);
}

.vn9j6bcji {
  stop-color: var(--svg-color--8d5d5d, #8D5D5D);
}

.w8ik5kb4l {
  d: path("M10.565 14.327a2.067 2.067 0 0 1 3.514-2.03c1.034 2.086 2.309 4.519 3.276 5.937c-1.23 1.672-1.526 2.516-1.78 3.235c-.782-1.089-2.416-3.305-3-4.047c-.314-.398-.696-.906-1.09-1.008a13 13 0 0 1-.92-2.087");
}

.wiry0-bwi {
  fill: var(--svg-color--a17867, #A17867);
  d: path("M14.515 22.582a.5.5 0 0 0 .97.242zm8.427-6.446a.5.5 0 0 0-.134-.99zm-7.457 6.688c.278-1.113 1.361-2.688 2.822-4.061c1.46-1.371 3.178-2.429 4.635-2.627l-.134-.99c-1.762.239-3.668 1.462-5.186 2.888c-1.515 1.424-2.76 3.16-3.107 4.548z");
}

.wjpozccyw {
  d: path("M13.994 12.081c.745 1.601 1.672 3.594 2.832 5.315c.207.308.58.464.924.325a5.2 5.2 0 0 0 2.047-1.542c.238-.297.23-.71.045-1.042c-.842-1.505-2.043-4.166-2.799-6.876a2.067 2.067 0 0 0-3.908 1.205c.104.688.623 2.037.859 2.615");
}

.x9diso5po {
  stop-color: var(--svg-color--7f4f48, #7F4F48);
  stop-opacity: 0;
}

.xol3sj3nk {
  stop-color: var(--svg-color--7f4f48, #7F4F48);
}

.y1bncpb2x {
  stop-color: var(--svg-color--9b5c8b, #9B5C8B);
  stop-opacity: 0;
}

.y2uoumjad {
  stroke: var(--svg-color--bb9581, #BB9581);
  stroke-linecap: round;
  d: path("M16 8.484c.323 1.125 1.76 5.365 3.281 7.797");
}

.ymcz05bgh {
  d: path("M19.145 6.2a2.09 2.09 0 0 1 2.01 1.516c.8 2.323 2.25 5.629 3.327 7.123a7 7 0 0 0 .389-1.652c.02-.188.152-1.41.336-1.956c.221-.658.678-1.224 1.364-1.446c1.117-.36 2.33.3 2.71 1.477q.053.162.08.326c.13.56.04 1.073-.014 1.412a61 61 0 0 0-.359 2.625a19.6 19.6 0 0 0 .125 4.781c.3 1.413.219 2.912.14 3.485c-.86 6.31-7.847 6.78-9.812 5.85c-1.339-.435-2.758-1.47-4.71-3.468c-2.283-2.335-4.368-4.905-5.529-6.643a2.067 2.067 0 0 1 2.276-3.216c-.377-.735-.68-1.377-.917-2.087a2.067 2.067 0 0 1 3.534-2.007c-.12-.267-.835-2.032-.96-2.854a2.089 2.089 0 0 1 6.01-3.266");
}

.yy1sefn2s {
  stop-color: var(--svg-color--9f806a, #9F806A);
}

.z5pol9bvk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M20.812 2.629c1.758.125 4.641 1.598 4.547 5.363");
}

.zjmnh5tuh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M2.469 18.063c-.235 2.468 1.398 4.984 4.46 5.398");
}

.zt52bkbqx {
  stop-color: var(--svg-color--82574b, #82574B);
}

</style>
