<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i2XTHdb)" class="b3es9kbcu"/><path fill="url(#is3fHhc)" class="b3es9kbcu"/><path fill="url(#i8kJHIc)" class="b3es9kbcu"/><path fill="url(#i1PpDpe)" class="b3es9kbcu"/><path fill="url(#iFENQMe)" class="b3es9kbcu"/><path fill="url(#idhuaPb)" class="o8upe8hkw"/><path fill="url(#iJWwHfc)" class="o8upe8hkw"/><path fill="url(#iNueKre)" class="o8upe8hkw"/><path fill="url(#irNtKxd)" class="o8upe8hkw"/><path fill="url(#iARdOPe)" class="ilylrfb9a"/><path fill="url(#iUIjaGe)" class="fsd-3ybrm"/><g filter="url(#iJb54jc)"><path fill="url(#i3IiK4d)" class="pqr1blqlv"/></g><g filter="url(#ip828sc)"><path fill="url(#ipqbl5d)" class="enzr6iboq"/><path fill="url(#iQGUsVd)" class="enzr6iboq"/></g><g filter="url(#iWL3kqe)"><path fill="url(#iCxyWsc)" class="b56_b6bus"/></g><g filter="url(#iR43uss)"><path fill="url(#iM3Hhyb)" class="zcoc9pbcm"/><path fill="url(#iUJNR1d)" class="zcoc9pbcm"/></g><path fill="url(#iFM4o3b)" class="key106bgx"/><g filter="url(#ieKxvBd)"><path fill="url(#iTpT09c)" class="zb3t99b7s"/></g><g filter="url(#i3BE2qb)"><path fill="url(#izojS9p)" class="xyr0rcscc"/><path fill="url(#i1py1er)" class="xyr0rcscc"/></g><g filter="url(#iZLShqz)"><path class="fx-6t84hb"/></g><path fill="url(#iaOh1gd)" class="qk6y4di2j"/><path fill="url(#iMdF2Oc)" class="qk6y4di2j"/><path fill="url(#i0fk3Xd)" class="qk6y4di2j"/><path fill="url(#iYO6AGc)" class="zv9b7da5r"/><path fill="url(#iBu4Ukb)" class="zv9b7da5r"/><path fill="url(#iyCTq9d)" class="zv9b7da5r"/><defs><linearGradient id="i2XTHdb" x1="3.5" x2="28.313" y1="19.502" y2="19.502" gradientUnits="userSpaceOnUse"><stop class="vnkouh1wn"/><stop offset=".181" class="z2c4zqolj"/><stop offset=".456" class="yn7246c_r"/><stop offset=".688" class="hzkhwsb_i"/><stop offset=".872" class="l2oob-bjc"/><stop offset=".995" class="a9zy8cc4w"/></linearGradient><linearGradient id="is3fHhc" x1="16" x2="16" y1="21.938" y2="30.5" gradientUnits="userSpaceOnUse"><stop offset=".153" class="lfdyrirrg"/><stop offset=".628" class="zlmevj4js"/><stop offset=".701" class="kjtbkhboi"/></linearGradient><linearGradient id="i8kJHIc" x1="16" x2="16" y1="11.002" y2="28.002" gradientUnits="userSpaceOnUse"><stop class="l0wn-xb4s"/><stop offset=".014" class="mh358hkmc"/></linearGradient><linearGradient id="idhuaPb" x1="2" x2="30" y1="30.002" y2="30.002" gradientUnits="userSpaceOnUse"><stop class="z4pv4zb-b"/><stop offset=".388" class="l0xltgb4j"/><stop offset="1" class="m11o35bcd"/></linearGradient><linearGradient id="iJWwHfc" x1="16" x2="16" y1="28.002" y2="30.002" gradientUnits="userSpaceOnUse"><stop offset=".436" class="n97hgbbox"/><stop offset=".874" class="cwbkvwbfs"/></linearGradient><linearGradient id="iARdOPe" x1="17.313" x2="14.813" y1="6.031" y2="5.746" gradientUnits="userSpaceOnUse"><stop offset=".11" class="d30voiupv"/><stop offset=".653" class="mpupwzbcr"/></linearGradient><linearGradient id="iUIjaGe" x1="11.813" x2="9.313" y1="6.031" y2="5.746" gradientUnits="userSpaceOnUse"><stop offset=".11" class="mgna67bef"/><stop offset=".524" class="mpupwzbcr"/></linearGradient><linearGradient id="i3IiK4d" x1="11.25" x2="9.391" y1="6.359" y2="6.031" gradientUnits="userSpaceOnUse"><stop class="yekdy5qds"/><stop offset="1" class="l-kepb-pg"/></linearGradient><linearGradient id="iCxyWsc" x1="16.775" x2="14.915" y1="6.359" y2="6.031" gradientUnits="userSpaceOnUse"><stop class="yekdy5qds"/><stop offset="1" class="l-kepb-pg"/></linearGradient><linearGradient id="iFM4o3b" x1="22.813" x2="20.313" y1="6.031" y2="5.746" gradientUnits="userSpaceOnUse"><stop offset=".11" class="kd_5wtboo"/><stop offset="1" class="mpupwzbcr"/></linearGradient><linearGradient id="iTpT09c" x1="22.267" x2="20.408" y1="6.359" y2="6.031" gradientUnits="userSpaceOnUse"><stop class="s-orhz3ls"/><stop offset="1" class="mwnobkb0x"/></linearGradient><linearGradient id="iMdF2Oc" x1="10.328" x2="9.438" y1="13.547" y2="14.875" gradientUnits="userSpaceOnUse"><stop offset=".325" class="k8v91sbvo"/><stop offset=".807" class="ka1tqfbxt"/></linearGradient><linearGradient id="i0fk3Xd" x1="12.156" x2="10.938" y1="17.067" y2="17.067" gradientUnits="userSpaceOnUse"><stop offset=".325" class="ozhr43byz"/><stop offset=".807" class="ka1tqfbxt"/></linearGradient><linearGradient id="iYO6AGc" x1="8.25" x2="9.75" y1="13.313" y2="13.313" gradientUnits="userSpaceOnUse"><stop offset=".125" class="o7c0k8efl"/><stop offset=".667" class="q4obb8-kj"/><stop offset="1" class="o_8fzwbaa"/></linearGradient><radialGradient id="i1PpDpe" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 .90405 -4.8125 -.16637 5.312 11.002)" gradientUnits="userSpaceOnUse"><stop class="vc-j5jbuh"/><stop offset="1" class="q52v_wtyz"/></radialGradient><radialGradient id="iFENQMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .48438 -13 0 26.375 11.781)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="iNueKre" cx="0" cy="0" r="1" gradientTransform="matrix(0 .625 -10.25 0 24.688 28.625)" gradientUnits="userSpaceOnUse"><stop class="q07huxb0o"/><stop offset="1" class="tpo2tiogs"/></radialGradient><radialGradient id="irNtKxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.1875 -8.4906 0 2.625 29.5)" gradientUnits="userSpaceOnUse"><stop class="geo6hdk6b"/><stop offset="1" class="zw-zynb6r"/></radialGradient><radialGradient id="ipqbl5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -3.08036 0 11.375 2.594)" gradientUnits="userSpaceOnUse"><stop class="n89wzeaip"/><stop offset="1" class="vo8nxhb-a"/></radialGradient><radialGradient id="iQGUsVd" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 -4.44452 3.65086 .9241 11.25 10.219)" gradientUnits="userSpaceOnUse"><stop class="n89wzeaip"/><stop offset="1" class="vo8nxhb-a"/></radialGradient><radialGradient id="iM3Hhyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -3.08036 0 16.8 2.594)" gradientUnits="userSpaceOnUse"><stop class="n89wzeaip"/><stop offset="1" class="vo8nxhb-a"/></radialGradient><radialGradient id="iUJNR1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 -4.44452 3.65086 .9241 16.675 10.219)" gradientUnits="userSpaceOnUse"><stop class="n89wzeaip"/><stop offset="1" class="vo8nxhb-a"/></radialGradient><radialGradient id="izojS9p" cx="0" cy="0" r="1" gradientTransform="matrix(-.26135 3.18048 -2.61253 -.21468 22.293 2.594)" gradientUnits="userSpaceOnUse"><stop class="m7vwy9x8t"/><stop offset="1" class="vo8nxhb-a"/></radialGradient><radialGradient id="i1py1er" cx="0" cy="0" r="1" gradientTransform="rotate(-79.392 17.239 -8.243)scale(4.5218 3.71433)" gradientUnits="userSpaceOnUse"><stop class="lwu9q8b0r"/><stop offset="1" class="vo8nxhb-a"/></radialGradient><radialGradient id="iaOh1gd" cx="0" cy="0" r="1" gradientTransform="rotate(87.673 -2.65 14.21)scale(7.97532 6.06003)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="qi0dguski"/><stop offset="1" class="fb-n-vb6a"/></radialGradient><radialGradient id="iBu4Ukb" cx="0" cy="0" r="1" gradientTransform="rotate(101.976 .288 9.292)scale(1.0542 .69526)" gradientUnits="userSpaceOnUse"><stop class="g1_8labcv"/><stop offset="1" class="rk0-f3bss"/></radialGradient><radialGradient id="iyCTq9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -3.0759 0 9 15.969)" gradientUnits="userSpaceOnUse"><stop class="xkcrylo1t"/><stop offset="1" class="efdco_bys"/></radialGradient><filter id="iJb54jc" width="3.269" height="8.021" x="8.891" y="1.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27637" stdDeviation=".25"/></filter><filter id="ip828sc" width="2.242" height="7.627" x="9.767" y="1.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27637" stdDeviation=".125"/></filter><filter id="iWL3kqe" width="3.269" height="8.021" x="14.415" y="1.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27637" stdDeviation=".25"/></filter><filter id="iR43uss" width="2.242" height="7.627" x="15.192" y="1.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27637" stdDeviation=".125"/></filter><filter id="ieKxvBd" width="3.269" height="8.021" x="19.908" y="1.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27637" stdDeviation=".25"/></filter><filter id="i3BE2qb" width="2.242" height="7.627" x="20.684" y="1.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27637" stdDeviation=".125"/></filter><filter id="iZLShqz" width="6.016" height="7.797" x="6.031" y="13.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27637" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:teacup-without-handle" /></template>
<style>
.a9zy8cc4w {
  stop-color: var(--svg-color--eceaf4, #ECEAF4);
}

.b3es9kbcu {
  d: path("M21.44 28.002H10.56c-3.62 0-6.56-2.94-6.56-6.56v-9.5c0-.52.42-.94.94-.94h22.12c.52 0 .94.42.94.94v9.5c0 3.62-2.94 6.56-6.56 6.56");
}

.b56_b6bus {
  d: path("M16.257 9.133c.014.18-.129.2-.2.11c-.28-.34-1.141-1.113-1.141-2.743c0-1.42 1.695-1.902 1.695-4.094c.014-.19.182-.164.258 0c.234.508.412.866.257 2.196c-.216 1.93-1.328 1.992-.869 4.53");
}

.cwbkvwbfs {
  stop-color: var(--svg-color--7b4568, #7B4568);
}

.d30voiupv {
  stop-color: var(--svg-color--c0c1c5, #C0C1C5);
}

.efdco_bys {
  stop-color: var(--svg-color--a492bb, #A492BB);
  stop-opacity: 0;
}

.enzr6iboq {
  d: path("M10.79 9.281c.028.355-.9-1.031-.759-2.297c.14-1.265 1-1.484 1.227-4.773c.414.75.553 1.491.484 2.422c-.069.93-1.513 2.14-.953 4.648");
}

.fb-n-vb6a {
  stop-color: var(--svg-color--6ca75c, #6CA75C);
}

.fsd-3ybrm {
  d: path("M10.93 9.242c.03.18-.17.31-.32.22c-.58-.34-1.61-1.18-1.61-2.81c0-1.42 1.69-2.52 1.96-4.47c.03-.19.28-.25.39-.09c.37.55.85 1.57.53 2.9c-.45 1.93-1.33 1.69-.95 4.25");
}

.ft5dv1b6b {
  fill: none;
}

.fx-6t84hb {
  fill: var(--svg-color--938dac, #938DAC);
  d: path("m9.031 13.875l-2.33 1.165c-.26.17-.42.47-.42.78v4.75c0 .35.009.477.349.477l4.401.125c.35 0 .766-.262.766-.602l-.427-4.75c0-.31-.079-.61-.339-.78z");
}

.g1_8labcv {
  stop-color: var(--svg-color--e7e4ef, #E7E4EF);
}

.geo6hdk6b {
  stop-color: var(--svg-color--7f5977, #7F5977);
}

.hzkhwsb_i {
  stop-color: var(--svg-color--f9f2ff, #F9F2FF);
}

.ilylrfb9a {
  d: path("M16.43 9.242c.03.18-.17.31-.32.22c-.58-.34-1.61-1.18-1.61-2.81c0-1.42 1.69-2.52 1.96-4.47c.03-.19.28-.25.39-.09c.37.55.85 1.57.53 2.9c-.45 1.93-1.33 1.69-.95 4.25");
}

.k8v91sbvo {
  stop-color: var(--svg-color--8dde60, #8DDE60);
}

.ka1tqfbxt {
  stop-color: var(--svg-color--8ee060, #8EE060);
  stop-opacity: 0;
}

.kd_5wtboo {
  stop-color: var(--svg-color--c4c4c6, #C4C4C6);
}

.key106bgx {
  d: path("M21.93 9.242c.03.18-.17.31-.32.22c-.58-.34-1.61-1.18-1.61-2.81c0-1.42 1.69-2.52 1.96-4.47c.03-.19.28-.25.39-.09c.37.55.85 1.57.53 2.9c-.45 1.93-1.33 1.69-.95 4.25");
}

.kjtbkhboi {
  stop-color: var(--svg-color--3e3d40, #3E3D40);
}

.l-kepb-pg {
  stop-color: var(--svg-color--9a98a0, #9A98A0);
}

.l0wn-xb4s {
  stop-color: var(--svg-color--c1c2c3, #C1C2C3);
}

.l0xltgb4j {
  stop-color: var(--svg-color--724842, #724842);
}

.l2oob-bjc {
  stop-color: var(--svg-color--faf5ff, #FAF5FF);
}

.lfdyrirrg {
  stop-color: var(--svg-color--d0bee6, #D0BEE6);
  stop-opacity: 0;
}

.lwu9q8b0r {
  stop-color: var(--svg-color--dfe0e4, #DFE0E4);
}

.m11o35bcd {
  stop-color: var(--svg-color--825057, #825057);
}

.m7vwy9x8t {
  stop-color: var(--svg-color--f1f0f6, #F1F0F6);
}

.mgna67bef {
  stop-color: var(--svg-color--b3b4b7, #B3B4B7);
}

.mh358hkmc {
  stop-color: var(--svg-color--c4c4c4, #C4C4C4);
  stop-opacity: 0;
}

.mpupwzbcr {
  stop-color: var(--svg-color--8e8d90, #8E8D90);
}

.mwnobkb0x {
  stop-color: var(--svg-color--b1b0b8, #B1B0B8);
}

.n89wzeaip {
  stop-color: var(--svg-color--e5e5e5, #E5E5E5);
}

.n97hgbbox {
  stop-color: var(--svg-color--7b4359, #7B4359);
  stop-opacity: 0;
}

.o_8fzwbaa {
  stop-color: var(--svg-color--bdb9c8, #BDB9C8);
}

.o7c0k8efl {
  stop-color: var(--svg-color--88838f, #88838F);
}

.o8upe8hkw {
  d: path("M29 28.002H3c-.55 0-1 .45-1 1s.45 1 1 1h26c.55 0 1-.45 1-1s-.45-1-1-1");
}

.ozhr43byz {
  stop-color: var(--svg-color--99e77d, #99E77D);
}

.pqr1blqlv {
  d: path("M10.732 9.133c.015.18-.128.2-.2.11c-.28-.34-1.141-1.113-1.141-2.743c0-1.42 1.695-1.902 1.695-4.094c.014-.19.182-.164.258 0c.234.508.412.866.258 2.196c-.217 1.93-1.329 1.992-.87 4.53");
}

.q07huxb0o {
  stop-color: var(--svg-color--a17c77, #A17C77);
}

.q4obb8-kj {
  stop-color: var(--svg-color--cec8d8, #CEC8D8);
}

.q52v_wtyz {
  stop-color: var(--svg-color--99989e, #99989E);
  stop-opacity: 0;
}

.qi0dguski {
  stop-color: var(--svg-color--76c058, #76C058);
}

.qk6y4di2j {
  d: path("m9 13.132l-2.58 1.72c-.26.17-.42.47-.42.78v4.75c0 .35.28.62.62.62h4.74c.35 0 .62-.28.62-.62v-4.75c0-.31-.16-.61-.42-.78z");
}

.rk0-f3bss {
  stop-color: var(--svg-color--bab8c0, #BAB8C0);
  stop-opacity: 0;
}

.s-orhz3ls {
  stop-color: var(--svg-color--bfbfc3, #BFBFC3);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.tpo2tiogs {
  stop-color: var(--svg-color--9f7a76, #9F7A76);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vc-j5jbuh {
  stop-color: var(--svg-color--a3a3a7, #A3A3A7);
}

.vnkouh1wn {
  stop-color: var(--svg-color--aca9b3, #ACA9B3);
}

.vo8nxhb-a {
  stop-color: var(--svg-color--e5e5e5, #E5E5E5);
  stop-opacity: 0;
}

.xkcrylo1t {
  stop-color: var(--svg-color--828194, #828194);
}

.xyr0rcscc {
  d: path("M21.707 9.281c.028.355-.899-1.031-.758-2.297c.14-1.265.957-1.515 1.226-4.773c.415.75.554 1.491.485 2.422c-.07.93-1.514 2.14-.953 4.648");
}

.yekdy5qds {
  stop-color: var(--svg-color--bbbbc1, #BBBBC1);
}

.yn7246c_r {
  stop-color: var(--svg-color--dbceed, #DBCEED);
}

.z2c4zqolj {
  stop-color: var(--svg-color--ada0c1, #ADA0C1);
}

.z4pv4zb-b {
  stop-color: var(--svg-color--634340, #634340);
}

.zb3t99b7s {
  d: path("M21.75 9.133c.014.18-.13.2-.201.11c-.28-.34-1.141-1.113-1.141-2.743c0-1.42 1.695-1.902 1.695-4.094c.015-.19.182-.164.258 0c.235.508.412.866.258 2.196c-.217 1.93-1.328 1.992-.87 4.53");
}

.zcoc9pbcm {
  d: path("M16.214 9.281c.029.355-.898-1.031-.758-2.297c.141-1.265 1.013-1.515 1.227-4.773c.414.75.553 1.491.484 2.422c-.069.93-1.513 2.14-.953 4.648");
}

.zlmevj4js {
  stop-color: var(--svg-color--7c7982, #7C7982);
}

.zv9b7da5r {
  d: path("M9 16.002c-.41 0-.75-.34-.75-.75v-4.5c0-.41.34-.75.75-.75s.75.34.75.75v4.5c0 .41-.34.75-.75.75");
}

.zw-zynb6r {
  stop-color: var(--svg-color--72575a, #72575A);
  stop-opacity: 0;
}

</style>
