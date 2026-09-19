<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iv9zOdc)"><path fill="url(#iM4RFTd)" class="xt0_fab9o"/><path fill="url(#iUJprqI)" class="xt0_fab9o"/></g><path fill="url(#i6ToUNM)" class="xt0_fab9o"/><path fill="url(#iZ9WR5M)" class="xt0_fab9o"/><path fill="url(#itWfX2c)" class="xt0_fab9o"/><g filter="url(#iURRMBc)"><path class="vtud7utwn"/></g><g filter="url(#iXfReFe)"><path class="cc51v-bzh"/></g><rect fill="url(#ixULWPH)" transform="rotate(-90 6.896 21.784)" class="ofm555bhr"/><rect fill="url(#izvvMhc)" transform="rotate(-90 6.896 21.784)" class="ofm555bhr"/><rect fill="url(#i7gHTGe)" transform="rotate(-90 6.896 21.784)" class="ofm555bhr"/><rect fill="url(#iKeXXdJ)" transform="rotate(-90 6.896 21.784)" class="ofm555bhr"/><rect fill="url(#iqCrBPD)" transform="rotate(-90 6.896 21.784)" class="ofm555bhr"/><rect fill="url(#ir9s6Jd)" transform="rotate(-90 7.194 8.582)" class="d0qggttjw"/><rect fill="url(#iXyIzae)" transform="rotate(-90 7.194 8.582)" class="d0qggttjw"/><rect fill="url(#iaCrgHd)" transform="rotate(-90 7.194 8.582)" class="d0qggttjw"/><rect fill="url(#ibVDWRN)" transform="rotate(-90 7.194 8.582)" class="d0qggttjw"/><rect fill="url(#ie5stOd)" transform="rotate(-90 5.904 12.836)" class="lgd-iz8gr"/><rect fill="url(#iZSMpdb)" transform="rotate(-90 5.904 12.836)" class="lgd-iz8gr"/><rect fill="url(#iHrwfCd)" transform="rotate(-90 5.904 12.836)" class="lgd-iz8gr"/><rect fill="url(#ib6OXjo)" transform="rotate(-90 5.904 12.836)" class="lgd-iz8gr"/><rect fill="url(#idKd1he)" transform="rotate(-90 5.949 17.258)" class="z0ph4v_hh"/><rect fill="url(#ig3MyDd)" transform="rotate(-90 5.949 17.258)" class="z0ph4v_hh"/><rect fill="url(#iQi9Bcc)" transform="rotate(-90 5.949 17.258)" class="z0ph4v_hh"/><rect fill="url(#iX4puFe)" transform="rotate(-90 5.949 17.258)" class="z0ph4v_hh"/><defs><radialGradient id="iUJprqI" cx="0" cy="0" r="1" gradientTransform="rotate(-63.938 23.462 -6.05)scale(7.24207 13.4771)" gradientUnits="userSpaceOnUse"><stop class="kmo462q3f"/><stop offset="1" class="ewjcumb6a"/></radialGradient><radialGradient id="i6ToUNM" cx="0" cy="0" r="1" gradientTransform="matrix(-6.09874 3.46893 -3.9808 -6.99866 24.688 8.339)" gradientUnits="userSpaceOnUse"><stop class="dbftm2jnp"/><stop offset="1" class="f3un_zgua"/></radialGradient><radialGradient id="iZ9WR5M" cx="0" cy="0" r="1" gradientTransform="matrix(4.64396 0 0 9.96517 20.089 26.855)" gradientUnits="userSpaceOnUse"><stop class="i88we0b2w"/><stop offset="1" class="nl506xlja"/></radialGradient><radialGradient id="itWfX2c" cx="0" cy="0" r="1" gradientTransform="scale(12.9389 20.0228)rotate(90 .401 .95)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="epspzefmp"/><stop offset="1" class="t5eaj7bhl"/></radialGradient><radialGradient id="i7gHTGe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.58086 2.00356 0 10.449 29.427)" gradientUnits="userSpaceOnUse"><stop class="jbqcexb-p"/><stop offset="1" class="lzf0gobgh"/></radialGradient><radialGradient id="iKeXXdJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.17279 -7.31561 8.00204 -.189 9.788 29.1)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="tt6l6i3qr"/><stop offset="1" class="j8sqz220e"/></radialGradient><radialGradient id="iqCrBPD" cx="0" cy="0" r="1" gradientTransform="matrix(-.9313 0 0 -4.89838 11.409 25.72)" gradientUnits="userSpaceOnUse"><stop class="nqixi72kg"/><stop offset="1" class="u1y6-_pri"/></radialGradient><radialGradient id="iXyIzae" cx="0" cy="0" r="1" gradientTransform="matrix(1.06838 0 0 4.40184 8.078 12.896)" gradientUnits="userSpaceOnUse"><stop class="z0frnac3v"/><stop offset="1" class="ph8jbx6co"/></radialGradient><radialGradient id="iaCrgHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.78495 2.38236 0 10.98 15.77)" gradientUnits="userSpaceOnUse"><stop class="gogvizlag"/><stop offset="1" class="c2l184cai"/></radialGradient><radialGradient id="ibVDWRN" cx="0" cy="0" r="1" gradientTransform="matrix(-.16817 -7.16786 7.78679 -.18269 10.008 15.75)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="ckp22gtxp"/><stop offset="1" class="hwybwackz"/></radialGradient><radialGradient id="iZSMpdb" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 0 0 5.04687 6.835 17.783)" gradientUnits="userSpaceOnUse"><stop class="ba9ei44qj"/><stop offset="1" class="zmf4_ct-d"/></radialGradient><radialGradient id="iHrwfCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.68226 2.10732 0 9.43 20.999)" gradientUnits="userSpaceOnUse"><stop class="jpm_4dbzn"/><stop offset="1" class="w96v8ubph"/></radialGradient><radialGradient id="ib6OXjo" cx="0" cy="0" r="1" gradientTransform="matrix(-.17705 -8.21822 8.20018 -.17667 8.867 21.054)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="jzrs0wbgy"/><stop offset="1" class="sovlmvb0c"/><stop offset="1" class="jwq3jcb5x"/></radialGradient><radialGradient id="ig3MyDd" cx="0" cy="0" r="1" gradientTransform="matrix(2.38035 0 0 7.9345 5.694 20.803)" gradientUnits="userSpaceOnUse"><stop class="o55npvdbo"/><stop offset="1" class="d5juoxabb"/></radialGradient><radialGradient id="iQi9Bcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.6702 2.06121 0 9.398 25.384)" gradientUnits="userSpaceOnUse"><stop class="yy3dc6bhz"/><stop offset="1" class="wutcr5bxn"/></radialGradient><radialGradient id="iX4puFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.17323 -8.18127 8.02085 -.16983 8.847 25.44)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="hcoee76cy"/><stop offset="1" class="a7n8dsbew"/></radialGradient><linearGradient id="iM4RFTd" x1="26.78" x2="12.286" y1="8.877" y2="30.59" gradientUnits="userSpaceOnUse"><stop class="p0qg12wpm"/><stop offset="1" class="b9-6lxb8p"/></linearGradient><linearGradient id="ixULWPH" x1="9.788" x2="9.788" y1="21.784" y2="30.772" gradientUnits="userSpaceOnUse"><stop class="vgqn6gb-w"/><stop offset="1" class="yjd7yw6rl"/></linearGradient><linearGradient id="izvvMhc" x1="6.543" x2="8.42" y1="26.278" y2="26.278" gradientUnits="userSpaceOnUse"><stop class="ovij9-0aw"/><stop offset="1" class="t23s3jbmo"/></linearGradient><linearGradient id="ir9s6Jd" x1="8.538" x2="10.883" y1="9.49" y2="16.594" gradientUnits="userSpaceOnUse"><stop class="e9-p9yq2s"/><stop offset="1" class="z0tsohb6n"/></linearGradient><linearGradient id="ie5stOd" x1="7.319" x2="10.194" y1="13.877" y2="21.877" gradientUnits="userSpaceOnUse"><stop class="h5vbqhb-i"/><stop offset="1" class="mtluwubov"/></linearGradient><linearGradient id="idKd1he" x1="8.847" x2="8.847" y1="17.258" y2="26.287" gradientUnits="userSpaceOnUse"><stop class="zrlgyusta"/><stop offset="1" class="uj6f8nb6s"/></linearGradient><filter id="iv9zOdc" width="18.933" height="27.637" x="9.373" y="2.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3061"/></filter><filter id="iURRMBc" width="12.677" height="20.87" x="5.131" y="2.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3061" stdDeviation="1"/></filter><filter id="iXfReFe" width="12.088" height="5.26" x="12.396" y="15.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3061" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:thumbs-down-medium-dark" /></template>
<style>
.a7n8dsbew {
  stop-color: var(--svg-color--85655c, #85655C);
}

.b9-6lxb8p {
  stop-color: var(--svg-color--784c4d, #784C4D);
}

.ba9ei44qj {
  stop-color: var(--svg-color--623d32, #623D32);
}

.c2l184cai {
  stop-color: var(--svg-color--a68072, #A68072);
  stop-opacity: 0;
}

.cc51v-bzh {
  fill: var(--svg-color--764757, #764757);
  d: path("M22.984 19.755c-3.643-2.24-7.3-.667-8.247 0l-.84-1.08c5.38-2.563 8.246-.361 9.087 1.08");
}

.ckp22gtxp {
  stop-color: var(--svg-color--816157, #816157);
  stop-opacity: 0;
}

.d0qggttjw {
  width: 5.629px;
  height: 8.806px;
  x: 7.194px;
  y: 8.582px;
  rx: 2.814px;
}

.d5juoxabb {
  stop-color: var(--svg-color--6e3a51, #6E3A51);
  stop-opacity: 0;
}

.dbftm2jnp {
  stop-color: var(--svg-color--b58b7c, #B58B7C);
}

.e9-p9yq2s {
  stop-color: var(--svg-color--69473f, #69473F);
}

.epspzefmp {
  stop-color: var(--svg-color--7b3f6b, #7B3F6B);
  stop-opacity: 0;
}

.ewjcumb6a {
  stop-color: var(--svg-color--7e4f57, #7E4F57);
  stop-opacity: 0;
}

.f3un_zgua {
  stop-color: var(--svg-color--a47e71, #A47E71);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gogvizlag {
  stop-color: var(--svg-color--a68072, #A68072);
}

.h5vbqhb-i {
  stop-color: var(--svg-color--6d4946, #6D4946);
}

.hcoee76cy {
  stop-color: var(--svg-color--85655c, #85655C);
  stop-opacity: 0;
}

.hwybwackz {
  stop-color: var(--svg-color--816157, #816157);
}

.i88we0b2w {
  stop-color: var(--svg-color--9e726b, #9E726B);
}

.j8sqz220e {
  stop-color: var(--svg-color--836059, #836059);
}

.jbqcexb-p {
  stop-color: var(--svg-color--a07d74, #A07D74);
}

.jpm_4dbzn {
  stop-color: var(--svg-color--a68173, #A68173);
}

.jwq3jcb5x {
  stop-color: var(--svg-color--84655a, #84655A);
}

.jzrs0wbgy {
  stop-color: var(--svg-color--84655a, #84655A);
  stop-opacity: 0;
}

.kmo462q3f {
  stop-color: var(--svg-color--7e4f57, #7E4F57);
}

.lgd-iz8gr {
  width: 5.927px;
  height: 10.097px;
  x: 5.904px;
  y: 12.836px;
  rx: 2.91px;
}

.lzf0gobgh {
  stop-color: var(--svg-color--a07d74, #A07D74);
  stop-opacity: 0;
}

.mtluwubov {
  stop-color: var(--svg-color--926b5a, #926B5A);
}

.nl506xlja {
  stop-color: var(--svg-color--9e726b, #9E726B);
  stop-opacity: 0;
}

.nqixi72kg {
  stop-color: var(--svg-color--5d2f31, #5D2F31);
}

.o55npvdbo {
  stop-color: var(--svg-color--6e3a51, #6E3A51);
}

.ofm555bhr {
  width: 5.784px;
  height: 8.988px;
  x: 6.896px;
  y: 21.784px;
  rx: 2.892px;
}

.ovij9-0aw {
  stop-color: var(--svg-color--79406a, #79406A);
}

.p0qg12wpm {
  stop-color: var(--svg-color--976f5e, #976F5E);
}

.ph8jbx6co {
  stop-color: var(--svg-color--6e4638, #6E4638);
  stop-opacity: 0;
}

.sovlmvb0c {
  stop-color: var(--svg-color--574744, #574744);
}

.t23s3jbmo {
  stop-color: var(--svg-color--79406a, #79406A);
  stop-opacity: 0;
}

.t5eaj7bhl {
  stop-color: var(--svg-color--7b3f6b, #7B3F6B);
}

.tt6l6i3qr {
  stop-color: var(--svg-color--836059, #836059);
  stop-opacity: 0;
}

.u1y6-_pri {
  stop-color: var(--svg-color--5d2f31, #5D2F31);
  stop-opacity: 0;
}

.uj6f8nb6s {
  stop-color: var(--svg-color--916959, #916959);
}

.vgqn6gb-w {
  stop-color: var(--svg-color--6e4947, #6E4947);
}

.vtud7utwn {
  fill: var(--svg-color--62433b, #62433B);
  d: path("M8.24 6.69c0 .469.122.908.336 1.283c-.855.429-1.445 1.34-1.445 2.395c0 .82.356 1.553.917 2.04a2.64 2.64 0 0 0-.878 1.98c0 1.039.585 1.935 1.431 2.35a2.65 2.65 0 0 0-.618 1.71c0 1.431 1.113 2.591 2.486 2.591h2.753c1.373 0 2.485-1.16 2.485-2.59a2.63 2.63 0 0 0-.89-1.988a2.63 2.63 0 0 0 .99-2.073a2.64 2.64 0 0 0-.897-1.997c.55-.487.898-1.213.898-2.023c0-.728-.281-1.387-.736-1.867c.454-.458.736-1.1.736-1.81c0-1.393-1.083-2.522-2.419-2.522h-2.73c-1.337 0-2.42 1.13-2.42 2.521");
}

.w96v8ubph {
  stop-color: var(--svg-color--a68173, #A68173);
  stop-opacity: 0;
}

.wutcr5bxn {
  stop-color: var(--svg-color--a68175, #A68175);
  stop-opacity: 0;
}

.xt0_fab9o {
  d: path("M20.5 27.322a3.268 3.268 0 0 1-6.536 0v-3.761q-.001-.48.072-.96a6 6 0 0 0 .047-.35c.036-.368-.008-.85-.258-1.172l.598-.577a9.28 9.28 0 0 1-5.05-8.274c0-.98.15-1.923.43-2.809l.99-6.466h8.051v.003c4.973.107 8.962 3.35 8.962 9.272c0 3.48-1.667 6.284-4.189 7.864l.006.005c-.172.12-.374.24-.591.37l-.002.002c-.715.428-1.59.953-2.05 1.81c-.4.742-.478 1.948-.478 2.507H20.5z");
}

.yjd7yw6rl {
  stop-color: var(--svg-color--93675c, #93675C);
}

.yy3dc6bhz {
  stop-color: var(--svg-color--a68175, #A68175);
}

.z0frnac3v {
  stop-color: var(--svg-color--6e4638, #6E4638);
}

.z0ph4v_hh {
  width: 5.797px;
  height: 10.051px;
  x: 5.949px;
  y: 17.258px;
  rx: 2.899px;
}

.z0tsohb6n {
  stop-color: var(--svg-color--936e5d, #936E5D);
}

.zmf4_ct-d {
  stop-color: var(--svg-color--623d32, #623D32);
  stop-opacity: 0;
}

.zrlgyusta {
  stop-color: var(--svg-color--704d47, #704D47);
}

</style>
