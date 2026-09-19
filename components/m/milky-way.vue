<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="xcrs--45o"/><path fill="url(#isgiCvd)" class="vbc9yyfud"/><path fill="url(#iebOsFb)" class="vbc9yyfud"/><path fill="url(#i3ky9nb)" class="vbc9yyfud"/><path fill="url(#it2IV1b)" class="n_9f0nnxt"/><path class="caqc3eqtn"/><path fill="url(#isSBCNu)" class="jv39uac5o"/><path fill="url(#i1RbOFm)" class="gzm03e-es"/><path fill="url(#iw2dyhe)" class="u-s9317hb"/><path fill="url(#iRpLdje)" class="b3vki_bjh"/><path fill="url(#iPNoD6d)" class="owa7_gbfb"/><path fill="url(#iq2DdBd)" class="q_73r71-a"/><g filter="url(#iOTiRwd)"><path class="d2tfxii7a"/><path fill="url(#i6ZyhSJ)" class="lfbcb6bqh"/><path fill="url(#i2tPF1A)" class="lfbcb6bqh"/></g><g filter="url(#ifY4dYd)"><path class="e0rc1ilan"/><path fill="url(#iCOvfZb)" class="vesnnli1n"/><path fill="url(#ifye1oc)" class="vesnnli1n"/></g><g filter="url(#i3mN3Jd)"><path class="au5k2201j"/><path fill="url(#ixHeVwZ)" class="yrpy8sl-s"/><path fill="url(#iv5SanS)" class="yrpy8sl-s"/></g><path class="e19sb_bsb"/><path fill="url(#iZO9zWX)" class="nk_m853kh"/><path fill="url(#itkWAjM)" class="s21h4ccji"/><path fill="url(#ivosbHc)" class="s21h4ccji"/><path fill="url(#iRcgbvb)" class="fjntksbar"/><path fill="url(#iKtFIud)" class="fjntksbar"/><path fill="url(#icysVVO)" class="ap-b76wez"/><path fill="url(#iH4JZDM)" class="z1gv9sboz"/><path fill="url(#itZO71c)" class="fkg7-3_6n"/><path fill="url(#iqMupud)" class="fkg7-3_6n"/><defs><radialGradient id="isSBCNu" cx="0" cy="0" r="1" gradientTransform="matrix(7.855 -1.65312 2.26488 10.76186 14.29 29.607)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="piraz3bxw"/><stop offset="1" class="v58ciiben"/></radialGradient><radialGradient id="i1RbOFm" cx="0" cy="0" r="1" gradientTransform="rotate(117.35 2.252 4.978)scale(.78755)" gradientUnits="userSpaceOnUse"><stop class="oisjbygzv"/><stop offset="1" class="qt089z6es"/></radialGradient><radialGradient id="iw2dyhe" cx="0" cy="0" r="1" gradientTransform="rotate(117.35 6.992 17.455)scale(.78755)" gradientUnits="userSpaceOnUse"><stop class="oisjbygzv"/><stop offset="1" class="qt089z6es"/></radialGradient><radialGradient id="iRpLdje" cx="0" cy="0" r="1" gradientTransform="rotate(117.35 3.666 19.543)scale(.78755)" gradientUnits="userSpaceOnUse"><stop class="oisjbygzv"/><stop offset="1" class="qt089z6es"/></radialGradient><radialGradient id="iPNoD6d" cx="0" cy="0" r="1" gradientTransform="rotate(117.35 6.47 20.564)scale(.78755)" gradientUnits="userSpaceOnUse"><stop class="oisjbygzv"/><stop offset="1" class="qt089z6es"/></radialGradient><radialGradient id="iq2DdBd" cx="0" cy="0" r="1" gradientTransform="rotate(117.35 -.77 6.565)scale(.78755)" gradientUnits="userSpaceOnUse"><stop class="oisjbygzv"/><stop offset="1" class="qt089z6es"/></radialGradient><radialGradient id="i6ZyhSJ" cx="0" cy="0" r="1" gradientTransform="rotate(131.677 1.07 11.644)scale(1.21695 1.59973)" gradientUnits="userSpaceOnUse"><stop offset=".438" class="h35cgjaov"/><stop offset="1" class="inh6ngu7g"/></radialGradient><radialGradient id="i2tPF1A" cx="0" cy="0" r="1" gradientTransform="matrix(.5145 .40683 -.7093 .89703 8.674 18.526)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="s-9rk6g6c"/><stop offset="1" class="p4t1z1b8e"/></radialGradient><radialGradient id="iCOvfZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.54058 .60774 -.79882 -.71055 15.652 8.384)" gradientUnits="userSpaceOnUse"><stop offset=".438" class="h35cgjaov"/><stop offset="1" class="inh6ngu7g"/></radialGradient><radialGradient id="ifye1oc" cx="0" cy="0" r="1" gradientTransform="matrix(.34372 .27201 -.47434 .5994 14.446 8.344)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="s-9rk6g6c"/><stop offset="1" class="p4t1z1b8e"/></radialGradient><radialGradient id="ixHeVwZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.54058 .60774 -.79882 -.71055 21.652 17.384)" gradientUnits="userSpaceOnUse"><stop offset=".438" class="h35cgjaov"/><stop offset="1" class="inh6ngu7g"/></radialGradient><radialGradient id="iv5SanS" cx="0" cy="0" r="1" gradientTransform="matrix(.34372 .27201 -.47434 .5994 20.445 17.344)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="s-9rk6g6c"/><stop offset="1" class="p4t1z1b8e"/></radialGradient><radialGradient id="iZO9zWX" cx="0" cy="0" r="1" gradientTransform="matrix(-.54472 .64901 -.71153 -.5972 10.797 13.352)" gradientUnits="userSpaceOnUse"><stop class="ysafao63f"/><stop offset="1" class="gzjf_-pzf"/></radialGradient><radialGradient id="itkWAjM" cx="0" cy="0" r="1" gradientTransform="rotate(122.112 -3.517 13.189)scale(1.03233)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="mq-u2eb8n"/><stop offset="1" class="cy0j78bji"/></radialGradient><radialGradient id="ivosbHc" cx="0" cy="0" r="1" gradientTransform="rotate(17.723 -72.697 27.54)scale(.79557)" gradientUnits="userSpaceOnUse"><stop class="gnzat4efe"/><stop offset="1" class="b08w2krju"/></radialGradient><radialGradient id="iRcgbvb" cx="0" cy="0" r="1" gradientTransform="rotate(117.81 9.95 13.661)scale(.80378)" gradientUnits="userSpaceOnUse"><stop class="iukwxty_h"/><stop offset="1" class="w-rxa4bnp"/></radialGradient><radialGradient id="iKtFIud" cx="0" cy="0" r="1" gradientTransform="rotate(17.723 -23.714 88.887)scale(.79557)" gradientUnits="userSpaceOnUse"><stop class="aktq4kbcu"/><stop offset="1" class="hoa_1fzis"/></radialGradient><radialGradient id="icysVVO" cx="0" cy="0" r="1" gradientTransform="matrix(-.54472 .64901 -.71153 -.5972 18.797 23.352)" gradientUnits="userSpaceOnUse"><stop class="ysafao63f"/><stop offset="1" class="gzjf_-pzf"/></radialGradient><radialGradient id="iH4JZDM" cx="0" cy="0" r="1" gradientTransform="matrix(-.54472 .64901 -.71153 -.5972 18.798 11.352)" gradientUnits="userSpaceOnUse"><stop class="ysafao63f"/><stop offset="1" class="gzjf_-pzf"/></radialGradient><radialGradient id="itZO71c" cx="0" cy="0" r="1" gradientTransform="rotate(117.81 9.863 8.154)scale(.80378)" gradientUnits="userSpaceOnUse"><stop class="iukwxty_h"/><stop offset="1" class="w-rxa4bnp"/></radialGradient><radialGradient id="iqMupud" cx="0" cy="0" r="1" gradientTransform="rotate(17.723 -.558 68.852)scale(.79557)" gradientUnits="userSpaceOnUse"><stop class="aktq4kbcu"/><stop offset="1" class="hoa_1fzis"/></radialGradient><linearGradient id="isgiCvd" x1="30" x2="26.264" y1="18.98" y2="18.98" gradientUnits="userSpaceOnUse"><stop offset=".355" class="jjm2tbbgh"/><stop offset="1" class="ow_to1hej"/></linearGradient><linearGradient id="iebOsFb" x1="18.046" x2="18.046" y1="30.693" y2="24.837" gradientUnits="userSpaceOnUse"><stop class="l0--glbwc"/><stop offset="1" class="kg12jzbyc"/></linearGradient><linearGradient id="i3ky9nb" x1="2" x2="6.049" y1="15.39" y2="15.39" gradientUnits="userSpaceOnUse"><stop offset=".445" class="ltdta3b0i"/><stop offset="1" class="yr87mgbob"/></linearGradient><linearGradient id="it2IV1b" x1="30.232" x2="2" y1="24.081" y2="24.081" gradientUnits="userSpaceOnUse"><stop offset=".706" class="dvt-pn54k"/><stop offset="1" class="w1s773bpu"/></linearGradient><filter id="iOTiRwd" width="2.998" height="3.18" x="7.995" y="17.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.67451 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14896"/></filter><filter id="ifY4dYd" width="2.002" height="2.192" x="13.992" y="7.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.67451 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14896"/></filter><filter id="i3mN3Jd" width="2.002" height="2.192" x="19.992" y="16.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.67451 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14896"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:milky-way" /></template>
<style>
.aktq4kbcu {
  stop-color: var(--svg-color--8998a8, #8998A8);
}

.ap-b76wez {
  d: path("M18.49 24a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.au5k2201j {
  fill: var(--svg-color--e8bd41, #E8BD41);
  d: path("m21.86 17.79l-.37-.18a.2.2 0 0 1-.11-.11l-.18-.37c-.09-.18-.34-.18-.42 0l-.16.34c-.02.05-.06.09-.11.11l-.39.19c-.17.09-.17.34 0 .42l.36.17c.05.02.09.06.11.11l.19.39c.09.17.33.17.42 0l.18-.37c.02-.05.06-.09.11-.11l.37-.18c.18-.08.18-.33 0-.41");
}

.b08w2krju {
  stop-color: var(--svg-color--949198, #949198);
  stop-opacity: 0;
}

.b3vki_bjh {
  d: path("M22.49 26a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.caqc3eqtn {
  fill: var(--svg-color--3c94c6, #3C94C6);
  d: path("M14.29 30h4.1c2.2-9.32 6.49-15.01 11.61-18.94v-4.9C23.16 10.64 17.01 17.53 14.29 30");
}

.cy0j78bji {
  stop-color: var(--svg-color--b48cd9, #B48CD9);
}

.d2tfxii7a {
  fill: var(--svg-color--e8bd41, #E8BD41);
  d: path("m10.79 19.18l-.56-.27a.3.3 0 0 1-.16-.16l-.26-.55c-.13-.26-.51-.26-.63 0l-.24.52c-.03.07-.09.13-.16.16l-.59.29c-.26.13-.26.5 0 .63l.53.25c.07.03.13.09.16.16l.29.58c.13.26.5.26.63 0l.27-.56c.03-.07.09-.13.16-.16l.56-.27c.27-.12.27-.5 0-.62");
}

.dvt-pn54k {
  stop-color: var(--svg-color--3391c5, #3391C5);
}

.e0rc1ilan {
  fill: var(--svg-color--e8bd41, #E8BD41);
  d: path("m15.86 8.79l-.37-.18a.2.2 0 0 1-.11-.11l-.18-.37c-.09-.18-.34-.18-.42 0l-.16.34c-.02.05-.06.09-.11.11l-.39.19c-.17.09-.17.34 0 .42l.36.17c.05.02.09.06.11.11l.19.39c.09.17.33.17.42 0l.18-.37c.02-.05.06-.09.11-.11l.37-.18c.18-.08.18-.33 0-.41");
}

.e19sb_bsb {
  fill: var(--svg-color--4cf0f8, #4CF0F8);
  d: path("m14.86 16.79l-.37-.18a.2.2 0 0 1-.11-.11l-.18-.37c-.09-.18-.34-.18-.42 0l-.16.34c-.02.05-.06.09-.11.11l-.39.19c-.17.09-.17.34 0 .42l.36.17c.05.02.09.06.11.11l.19.39c.09.17.33.17.42 0l.18-.37c.02-.05.06-.09.11-.11l.37-.18c.18-.08.18-.33 0-.41m8-10l-.37-.18a.2.2 0 0 1-.11-.11l-.18-.37c-.09-.18-.34-.18-.42 0l-.16.34c-.02.05-.06.09-.11.11l-.39.19c-.17.09-.17.34 0 .42l.36.17c.05.02.09.06.11.11l.19.39c.09.17.33.17.42 0l.18-.37c.02-.05.06-.09.11-.11l.37-.18c.18-.08.18-.33 0-.41");
}

.fjntksbar {
  d: path("M26.49 12a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.fkg7-3_6n {
  d: path("M21.49 4a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.ft5dv1b6b {
  fill: none;
}

.gnzat4efe {
  stop-color: var(--svg-color--949198, #949198);
}

.gzjf_-pzf {
  stop-color: var(--svg-color--4b9fec, #4B9FEC);
}

.gzm03e-es {
  d: path("M7.49 6a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.h35cgjaov {
  stop-color: var(--svg-color--ffe64d, #FFE64D);
}

.hoa_1fzis {
  stop-color: var(--svg-color--8998a8, #8998A8);
  stop-opacity: 0;
}

.inh6ngu7g {
  stop-color: var(--svg-color--ffe64d, #FFE64D);
  stop-opacity: 0;
}

.iukwxty_h {
  stop-color: var(--svg-color--fffff8, #FFFFF8);
}

.jjm2tbbgh {
  stop-color: var(--svg-color--453f46, #453F46);
}

.jv39uac5o {
  d: path("M14.29 30h4.1c2.2-9.32 6.49-15.01 11.61-18.94v-4.9C23.16 10.64 17.01 17.53 14.29 30");
}

.kg12jzbyc {
  stop-color: var(--svg-color--4b286a, #4B286A);
  stop-opacity: 0;
}

.l0--glbwc {
  stop-color: var(--svg-color--4b286a, #4B286A);
}

.lfbcb6bqh {
  d: path("m10.79 19.18l-.56-.27a.3.3 0 0 1-.16-.16l-.26-.55c-.13-.26-.51-.26-.63 0l-.24.52c-.03.07-.09.13-.16.16l-.59.29c-.26.13-.26.5 0 .63l.53.25c.07.03.13.09.16.16l.29.58c.13.26.5.26.63 0l.27-.56c.03-.07.09-.13.16-.16l.56-.27c.27-.12.27-.5 0-.62");
}

.ltdta3b0i {
  stop-color: var(--svg-color--2c2632, #2C2632);
}

.mq-u2eb8n {
  stop-color: var(--svg-color--e3dce0, #E3DCE0);
}

.n_9f0nnxt {
  d: path("M29.753 4.343A3.67 3.67 0 0 0 26.33 2H16.5c-3 2.93-5.04 5.81-6.83 8.34c-2.39 3.39-4.23 5.99-7.67 7.98v8.01a3.66 3.66 0 0 0 1.04 2.56c8.05-3.25 11.48-8.08 14.8-12.78c2.88-4.08 5.61-7.94 11.91-11.75z");
}

.nk_m853kh {
  d: path("M10.49 14a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.oisjbygzv {
  stop-color: var(--svg-color--5f93d4, #5F93D4);
}

.ow_to1hej {
  stop-color: var(--svg-color--453f46, #453F46);
  stop-opacity: 0;
}

.owa7_gbfb {
  d: path("M27.49 25a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.p4t1z1b8e {
  stop-color: var(--svg-color--c4a638, #C4A638);
  stop-opacity: 0;
}

.piraz3bxw {
  stop-color: var(--svg-color--40295d, #40295D);
}

.q_73r71-a {
  d: path("M4.49 11a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.qt089z6es {
  stop-color: var(--svg-color--244bb0, #244BB0);
}

.s-9rk6g6c {
  stop-color: var(--svg-color--c4a638, #C4A638);
}

.s21h4ccji {
  d: path("M5.49 24a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.u-s9317hb {
  d: path("M25.49 20a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.v58ciiben {
  stop-color: var(--svg-color--40295d, #40295D);
  stop-opacity: 0;
}

.vbc9yyfud {
  d: path("M26.33 30H5.67C3.64 30 2 28.36 2 26.33V5.67C2 3.64 3.64 2 5.67 2h20.66C28.36 2 30 3.64 30 5.67v20.66c0 2.03-1.64 3.67-3.67 3.67");
}

.vesnnli1n {
  d: path("m15.86 8.79l-.37-.18a.2.2 0 0 1-.11-.11l-.18-.37c-.09-.18-.34-.18-.42 0l-.16.34c-.02.05-.06.09-.11.11l-.39.19c-.17.09-.17.34 0 .42l.36.17c.05.02.09.06.11.11l.19.39c.09.17.33.17.42 0l.18-.37c.02-.05.06-.09.11-.11l.37-.18c.18-.08.18-.33 0-.41");
}

.w-rxa4bnp {
  stop-color: var(--svg-color--9c7fc3, #9C7FC3);
}

.w1s773bpu {
  stop-color: var(--svg-color--3391c5, #3391C5);
  stop-opacity: 0;
}

.xcrs--45o {
  fill: var(--svg-color--37313b, #37313B);
  d: path("M26.33 30H5.67C3.64 30 2 28.36 2 26.33V5.67C2 3.64 3.64 2 5.67 2h20.66C28.36 2 30 3.64 30 5.67v20.66c0 2.03-1.64 3.67-3.67 3.67");
}

.yr87mgbob {
  stop-color: var(--svg-color--2c2632, #2C2632);
  stop-opacity: 0;
}

.yrpy8sl-s {
  d: path("m21.86 17.79l-.37-.18a.2.2 0 0 1-.11-.11l-.18-.37c-.09-.18-.34-.18-.42 0l-.16.34c-.02.05-.06.09-.11.11l-.39.19c-.17.09-.17.34 0 .42l.36.17c.05.02.09.06.11.11l.19.39c.09.17.33.17.42 0l.18-.37c.02-.05.06-.09.11-.11l.37-.18c.18-.08.18-.33 0-.41");
}

.ysafao63f {
  stop-color: var(--svg-color--65f1f8, #65F1F8);
}

.z1gv9sboz {
  d: path("M18.49 12a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

</style>
