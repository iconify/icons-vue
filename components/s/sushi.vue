<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i2FgEQd)" class="ury959b6j"/><path fill="url(#iWrapNd)" class="ury959b6j"/><path fill="url(#iGzynld)" class="ury959b6j"/><path fill="url(#iDUUxiB)" class="ury959b6j"/><path fill="url(#i1JzHcb)" class="uiw-0pbgf"/><path fill="url(#i2evc3c)" class="uiw-0pbgf"/><g filter="url(#iZgkZ2c)"><path fill="url(#idYpUEc)" class="pkl6pq23c"/></g><path fill="url(#iObdwwe)" class="ccnx5kyii"/><path fill="url(#ibqFbWd)" class="hl9-ukbxk"/><path class="fomw39bjd"/><path fill="url(#iuJt7RN)" class="tej2_hb7i"/><path fill="url(#iDaqdzb)" class="sfn4kiwym"/><path fill="url(#iMm5dGx)" class="sfn4kiwym"/><path fill="url(#iivkbJc)" class="sfn4kiwym"/><path fill="url(#iIjMXAb)" class="drid9tbps"/><path fill="url(#iStNRwe)" class="drid9tbps"/><g filter="url(#idjizKe)"><path fill="url(#iyMSP0c)" class="p2lzeebvv"/></g><path fill="url(#iEqEmZb)" class="y26726bnc"/><path fill="url(#iW0pcxc)" class="fu6j1ab5b"/><path class="ydo7x1e7s"/><g filter="url(#iTZKi6n)"><path fill="url(#ilYMoed)" class="djyog0b1j"/></g><g filter="url(#in8Ca9d)"><path fill="url(#icO6S6d)" class="h3a06nkgi"/></g><defs><radialGradient id="iWrapNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.5 -11.3221 0 17.99 13.875)" gradientUnits="userSpaceOnUse"><stop class="g5ar-4byl"/><stop offset="1" class="tr9pcwbue"/></radialGradient><radialGradient id="iGzynld" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.93498 -26.4899 0 17.99 13.02)" gradientUnits="userSpaceOnUse"><stop offset=".47" class="d1bnmeb9j"/><stop offset=".692" class="l8tu6bely"/></radialGradient><radialGradient id="iDUUxiB" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.33908 -23.0452 0 17.99 12.491)" gradientUnits="userSpaceOnUse"><stop offset=".564" class="e2zl2_bmu"/><stop offset="1" class="ob-n6kbla"/></radialGradient><radialGradient id="i1JzHcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.73 -32 0 25.25 9.52)" gradientUnits="userSpaceOnUse"><stop class="q-tr5q5tm"/><stop offset=".349" class="sd-j8mb_j"/><stop offset=".554" class="e8-qv0blc"/><stop offset=".818" class="o7s14nhqr"/></radialGradient><radialGradient id="i2evc3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -28.6763 0 17.99 14.125)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="hc2xxvb0t"/><stop offset=".59" class="y5j-5bbuk"/><stop offset="1" class="pwcszbcey"/></radialGradient><radialGradient id="iMm5dGx" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.88388 -26.4899 0 13.98 23.89)" gradientUnits="userSpaceOnUse"><stop offset=".47" class="lo-qm822w"/><stop offset=".692" class="l8tu6bely"/></radialGradient><radialGradient id="iivkbJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.32169 -23.0452 0 13.98 23.368)" gradientUnits="userSpaceOnUse"><stop offset=".564" class="oyhszfswm"/><stop offset="1" class="ob-n6kbla"/></radialGradient><radialGradient id="iIjMXAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.496 -32 0 21.24 20.46)" gradientUnits="userSpaceOnUse"><stop class="tphqz2b6i"/><stop offset=".349" class="saihjoenv"/><stop offset=".485" class="l1pcjkwgt"/><stop offset=".698" class="frkil9ztd"/></radialGradient><radialGradient id="iStNRwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.31747 -28.6763 0 13.98 24.986)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="gp8d2862p"/><stop offset=".59" class="m4a9j4bgf"/><stop offset="1" class="hshwajzbe"/></radialGradient><radialGradient id="ilYMoed" cx="0" cy="0" r="1" gradientTransform="rotate(149.454 12.94 9.306)scale(3.2657 3.50125)" gradientUnits="userSpaceOnUse"><stop class="axtl9rbpb"/><stop offset="1" class="ilkw2x0sl"/></radialGradient><radialGradient id="icO6S6d" cx="0" cy="0" r="1" gradientTransform="rotate(149.454 9.334 14.154)scale(3.2657 3.50125)" gradientUnits="userSpaceOnUse"><stop class="idv5u3biq"/><stop offset="1" class="g5mnk54lz"/></radialGradient><linearGradient id="i2FgEQd" x1="17.99" x2="17.99" y1="13.02" y2="19.18" gradientUnits="userSpaceOnUse"><stop class="t89btdb3g"/><stop offset=".504" class="t89btdb3g"/><stop offset=".877" class="ndd74q9hb"/><stop offset="1" class="srsddqbgb"/></linearGradient><linearGradient id="idYpUEc" x1="27.563" x2="15.75" y1="9.313" y2="9.313" gradientUnits="userSpaceOnUse"><stop class="tyxwx-hfn"/><stop offset="1" class="xd3bm-bqy"/></linearGradient><linearGradient id="iObdwwe" x1="12.38" x2="12.38" y1="6" y2="9.6" gradientUnits="userSpaceOnUse"><stop class="sroz69b8v"/><stop offset=".204" class="uyllwtboy"/><stop offset="1" class="tx-07obkj"/></linearGradient><linearGradient id="ibqFbWd" x1="17.99" x2="17.99" y1="6" y2="9.6" gradientUnits="userSpaceOnUse"><stop class="miowtilkp"/><stop offset=".204" class="zqya1jabo"/><stop offset="1" class="zx5vthbhg"/></linearGradient><linearGradient id="iuJt7RN" x1="23.61" x2="23.61" y1="6" y2="9.6" gradientUnits="userSpaceOnUse"><stop class="y55sf1_tn"/><stop offset=".204" class="h5vgyhsab"/><stop offset="1" class="qlgjn8bzi"/></linearGradient><linearGradient id="iDaqdzb" x1="13.98" x2="13.98" y1="23.89" y2="29.97" gradientUnits="userSpaceOnUse"><stop class="qgga-pb2b"/><stop offset=".504" class="kbzg1sbsx"/><stop offset=".877" class="vaw1yebfx"/><stop offset="1" class="omn18gbrg"/></linearGradient><linearGradient id="iyMSP0c" x1="23.62" x2="11.807" y1="20.167" y2="20.167" gradientUnits="userSpaceOnUse"><stop class="ooq_cq89f"/><stop offset="1" class="qe41edbmh"/></linearGradient><linearGradient id="iEqEmZb" x1="8.37" x2="8.37" y1="17" y2="20.6" gradientUnits="userSpaceOnUse"><stop class="d7iwhve1u"/><stop offset=".295" class="souq7y-6y"/><stop offset="1" class="cphs98sss"/></linearGradient><linearGradient id="iW0pcxc" x1="13.98" x2="13.98" y1="17" y2="20.6" gradientUnits="userSpaceOnUse"><stop class="d7iwhve1u"/><stop offset=".174" class="bv477lbjy"/><stop offset="1" class="a9oys8j-s"/></linearGradient><filter id="iZgkZ2c" width="21.38" height="7.333" x="9.063" y="5.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28116" stdDeviation=".75"/></filter><filter id="idjizKe" width="21.38" height="7.333" x="5.12" y="16.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28116" stdDeviation=".75"/></filter><filter id="iTZKi6n" width="5.246" height="4.802" x="25" y="7.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28116" stdDeviation=".5"/></filter><filter id="in8Ca9d" width="5.246" height="4.802" x="20.754" y="18.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28116" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sushi" /></template>
<style>
.a9oys8j-s {
  stop-color: var(--svg-color--ff7882, #FF7882);
}

.axtl9rbpb {
  stop-color: var(--svg-color--ffac70, #FFAC70);
}

.bv477lbjy {
  stop-color: var(--svg-color--f4646e, #F4646E);
}

.ccnx5kyii {
  d: path("M12.38 9.6c-.4 0-.72-.32-.72-.72V6h1.44v2.88c0 .4-.32.72-.72.72");
}

.cphs98sss {
  stop-color: var(--svg-color--ff646f, #FF646F);
}

.d1bnmeb9j {
  stop-color: var(--svg-color--e6c2d3, #E6C2D3);
}

.d7iwhve1u {
  stop-color: var(--svg-color--e54851, #E54851);
}

.djyog0b1j {
  d: path("M29 10.626c.7-.664-.219-1.927-1.187-2.282c0 .276.187 1.274-.313 1.511s-1.208.1-1.5 0v1.186c.708.138 2.3.249 3-.415");
}

.drid9tbps {
  d: path("M20.82 17H7.14C4.3 17 2 19.3 2 22.14v.24c0 .85.69 1.54 1.54 1.54h20.88c.85 0 1.54-.69 1.54-1.54v-.24c.01-2.84-2.3-5.14-5.14-5.14");
}

.e2zl2_bmu {
  stop-color: var(--svg-color--b66a8a, #B66A8A);
}

.e8-qv0blc {
  stop-color: var(--svg-color--ff451e, #FF451E);
}

.fomw39bjd {
  fill: var(--svg-color--ff9631, #FF9631);
  d: path("M23.61 9.6c-.4 0-.72-.32-.72-.72V6h1.44v2.88a.73.73 0 0 1-.72.72");
}

.frkil9ztd {
  stop-color: var(--svg-color--ab342e, #AB342E);
}

.ft5dv1b6b {
  fill: none;
}

.fu6j1ab5b {
  d: path("M13.98 20.6c-.4 0-.72-.32-.72-.72V17h1.44v2.88c0 .4-.32.72-.72.72");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.g5ar-4byl {
  stop-color: var(--svg-color--cfa3c4, #CFA3C4);
}

.g5mnk54lz {
  stop-color: var(--svg-color--ff718e, #FF718E);
  stop-opacity: 0;
}

.gp8d2862p {
  stop-color: var(--svg-color--b25167, #B25167);
}

.h3a06nkgi {
  d: path("M24.754 21.481c.7-.664-.219-1.926-1.188-2.282c0 .277.188 1.274-.312 1.512c-.5.237-1.208.098-1.5 0v1.185c.708.138 2.3.249 3-.415");
}

.h5vgyhsab {
  stop-color: var(--svg-color--ff9431, #FF9431);
}

.hc2xxvb0t {
  stop-color: var(--svg-color--d05956, #D05956);
}

.hl9-ukbxk {
  d: path("M17.99 9.6c-.4 0-.72-.32-.72-.72V6h1.44v2.88c0 .4-.32.72-.72.72");
}

.hshwajzbe {
  stop-color: var(--svg-color--dc294c, #DC294C);
  stop-opacity: 0;
}

.idv5u3biq {
  stop-color: var(--svg-color--ff7490, #FF7490);
}

.ilkw2x0sl {
  stop-color: var(--svg-color--ffac70, #FFAC70);
  stop-opacity: 0;
}

.kbzg1sbsx {
  stop-color: var(--svg-color--cbb6df, #CBB6DF);
}

.l1pcjkwgt {
  stop-color: var(--svg-color--ef2b35, #EF2B35);
}

.l8tu6bely {
  stop-color: var(--svg-color--e7c5d4, #E7C5D4);
  stop-opacity: 0;
}

.lo-qm822w {
  stop-color: var(--svg-color--ddcbe5, #DDCBE5);
}

.m4a9j4bgf {
  stop-color: var(--svg-color--bf314f, #BF314F);
}

.miowtilkp {
  stop-color: var(--svg-color--e47f2a, #E47F2A);
}

.ndd74q9hb {
  stop-color: var(--svg-color--c09cd0, #C09CD0);
}

.o7s14nhqr {
  stop-color: var(--svg-color--b44333, #B44333);
}

.ob-n6kbla {
  stop-color: var(--svg-color--b36b8a, #B36B8A);
  stop-opacity: 0;
}

.omn18gbrg {
  stop-color: var(--svg-color--b498cd, #B498CD);
}

.ooq_cq89f {
  stop-color: var(--svg-color--f8486e, #F8486E);
}

.oyhszfswm {
  stop-color: var(--svg-color--a46d93, #A46D93);
}

.p2lzeebvv {
  d: path("M22.995 21.73H6.62v-1.5h14.812c-.125-.855-.187-2.563.563-2.563c.937 0 3.125 2.5 3 3.687c-.1.95-1.375.646-2 .375");
}

.pkl6pq23c {
  d: path("M26.938 10.875H10.563v-1.5h14.812c-.125-.854-.187-2.562.563-2.562c.937 0 3.125 2.5 3 3.687c-.1.95-1.375.646-2 .375");
}

.pwcszbcey {
  stop-color: var(--svg-color--f85930, #F85930);
  stop-opacity: 0;
}

.q-tr5q5tm {
  stop-color: var(--svg-color--ff8928, #FF8928);
}

.qe41edbmh {
  stop-color: var(--svg-color--f5466c, #F5466C);
  stop-opacity: 0;
}

.qgga-pb2b {
  stop-color: var(--svg-color--cebae1, #CEBAE1);
}

.qlgjn8bzi {
  stop-color: var(--svg-color--ff9531, #FF9531);
}

.saihjoenv {
  stop-color: var(--svg-color--f62c56, #F62C56);
}

.sd-j8mb_j {
  stop-color: var(--svg-color--ff6722, #FF6722);
}

.sfn4kiwym {
  d: path("M21.64 29.97H6.32a2.76 2.76 0 0 1-2.76-2.76v-3.32H24.4v3.32a2.76 2.76 0 0 1-2.76 2.76");
}

.souq7y-6y {
  stop-color: var(--svg-color--fe6a74, #FE6A74);
}

.sroz69b8v {
  stop-color: var(--svg-color--e37e29, #E37E29);
}

.srsddqbgb {
  stop-color: var(--svg-color--af86cb, #AF86CB);
}

.t89btdb3g {
  stop-color: var(--svg-color--d5b2d6, #D5B2D6);
}

.tej2_hb7i {
  d: path("M23.61 9.6c-.4 0-.72-.32-.72-.72V6h1.44v2.88a.73.73 0 0 1-.72.72");
}

.tphqz2b6i {
  stop-color: var(--svg-color--fd3163, #FD3163);
}

.tr9pcwbue {
  stop-color: var(--svg-color--cfa4c4, #CFA4C4);
  stop-opacity: 0;
}

.tx-07obkj {
  stop-color: var(--svg-color--f7872a, #F7872A);
}

.tyxwx-hfn {
  stop-color: var(--svg-color--ff9841, #FF9841);
}

.uiw-0pbgf {
  d: path("M24.83 6H11.15c-2.84 0-5.14 2.3-5.14 5.14v.36c0 .85.69 1.54 1.54 1.54h20.88c.85 0 1.54-.69 1.54-1.54v-.36C29.98 8.3 27.67 6 24.83 6");
}

.ury959b6j {
  d: path("M25.65 19.18H10.33a2.76 2.76 0 0 1-2.76-2.76v-3.4h20.84v3.4c0 1.53-1.23 2.76-2.76 2.76");
}

.uyllwtboy {
  stop-color: var(--svg-color--f8892a, #F8892A);
}

.vaw1yebfx {
  stop-color: var(--svg-color--bca3d2, #BCA3D2);
}

.xd3bm-bqy {
  stop-color: var(--svg-color--ff8340, #FF8340);
  stop-opacity: 0;
}

.y26726bnc {
  d: path("M8.37 20.6c-.4 0-.72-.32-.72-.72V17h1.44v2.88c0 .4-.32.72-.72.72");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.y55sf1_tn {
  stop-color: var(--svg-color--f68938, #F68938);
}

.y5j-5bbuk {
  stop-color: var(--svg-color--e2483b, #E2483B);
}

.ydo7x1e7s {
  fill: var(--svg-color--ff6e8a, #FF6E8A);
  d: path("M19.6 20.6c-.4 0-.72-.32-.72-.72V17h1.44v2.88a.73.73 0 0 1-.72.72");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.zqya1jabo {
  stop-color: var(--svg-color--f6882a, #F6882A);
}

.zx5vthbhg {
  stop-color: var(--svg-color--f9892a, #F9892A);
}

</style>
