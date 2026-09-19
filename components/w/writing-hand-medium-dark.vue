<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iiGHGye)"><path fill="url(#iu2YCyb)" class="i98t-7btg"/><path fill="url(#i7vGp1l)" class="i98t-7btg"/><path fill="url(#ivMxXFe)" class="i98t-7btg"/></g><path fill="url(#ijLPvEF)" class="tn3edfbno"/><path fill="url(#iBI1Bed)" class="tn3edfbno"/><path fill="url(#iEnLIDc)" class="tn3edfbno"/><rect fill="url(#iPVlqOd)" class="q7h9g6bki"/><rect fill="url(#i3m2VzW)" class="q7h9g6bki"/><rect fill="url(#iKXwW7b)" class="q7h9g6bki"/><path fill="url(#iof0IGb)" class="cowi8hvle"/><path fill="url(#ifV653b)" class="cowi8hvle"/><g filter="url(#ikmBK0b)"><path stroke="url(#i2ZmQAc)" class="su_j375kk"/></g><g filter="url(#ikVmSds)"><path fill="url(#ij0tU2c)" class="ftokoof_m"/><path fill="url(#i0LoGGe)" class="ftokoof_m"/><path fill="url(#inOXJ5A)" class="ftokoof_m"/><path fill="url(#iNiHCDc)" class="ftokoof_m"/></g><path fill="url(#iEPUn6d)" class="ftokoof_m"/><path fill="url(#iilru3d)" class="ftokoof_m"/><path fill="url(#i8DREJd)" class="ri12kgbds"/><path fill="url(#imwvmgb)" class="e4svvibki"/><path fill="url(#ioUTSAe)" class="e4svvibki"/><path fill="url(#iEAt31d)" class="w79k2acia"/><path fill="url(#iZsgCZb)" class="w79k2acia"/><path fill="url(#i83tsoc)" class="w79k2acia"/><path fill="url(#i9L0p6b)" class="n22n_obox"/><g filter="url(#i3Ieulr)"><path class="ini0sbbwd"/></g><path fill="url(#iI7YWVb)" class="dd0jy3bvw"/><path fill="url(#iC6xD1d)" class="dd0jy3bvw"/><path fill="url(#iGBgYce)" class="dd0jy3bvw"/><g filter="url(#iEdZxBc)"><path stroke="url(#ih80rUn)" class="henyrkb1a"/></g><defs><linearGradient id="iu2YCyb" x1="11.914" x2="4.985" y1="10.071" y2="21.98" gradientUnits="userSpaceOnUse"><stop class="zh6g_rbhx"/><stop offset="1" class="r0yxdcbwz"/></linearGradient><linearGradient id="ivMxXFe" x1="3.388" x2="4.09" y1="16.961" y2="17.362" gradientUnits="userSpaceOnUse"><stop class="hwdkzcb7b"/><stop offset="1" class="j16v93btb"/></linearGradient><linearGradient id="ijLPvEF" x1="16.529" x2="22.193" y1="24.288" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="dkhzdbbmg"/><stop offset="1" class="zlgf74bzk"/></linearGradient><linearGradient id="iBI1Bed" x1="30.064" x2="28.992" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="fkacmuq9i"/><stop offset="1" class="av7r-hnha"/></linearGradient><linearGradient id="i2ZmQAc" x1="10.097" x2="18.224" y1="22.631" y2="8.382" gradientUnits="userSpaceOnUse"><stop class="gjt4qpb9s"/><stop offset="1" class="no-oxqbvh"/></linearGradient><linearGradient id="ij0tU2c" x1="17.139" x2="28.784" y1="13.161" y2="24.614" gradientUnits="userSpaceOnUse"><stop class="b6-6biqux"/><stop offset="1" class="iy_62gb7c"/></linearGradient><linearGradient id="iNiHCDc" x1="24.375" x2="23.375" y1="13.844" y2="15.781" gradientUnits="userSpaceOnUse"><stop class="motml0dud"/><stop offset="1" class="xv0f92bag"/></linearGradient><linearGradient id="iEPUn6d" x1="23.814" x2="22.001" y1="14.125" y2="17.875" gradientUnits="userSpaceOnUse"><stop class="pktn1mbpq"/><stop offset="1" class="x8pg59vat"/></linearGradient><linearGradient id="iilru3d" x1="30.376" x2="27.814" y1="21.188" y2="21.188" gradientUnits="userSpaceOnUse"><stop class="pktn1mbpq"/><stop offset="1" class="x8pg59vat"/></linearGradient><linearGradient id="imwvmgb" x1="16.345" x2="19.525" y1="5.063" y2="6.501" gradientUnits="userSpaceOnUse"><stop class="x-50qsb-j"/><stop offset="1" class="man8xwalw"/></linearGradient><linearGradient id="ioUTSAe" x1="20.896" x2="19.969" y1="7.453" y2="6.875" gradientUnits="userSpaceOnUse"><stop class="si_znv48i"/><stop offset="1" class="bf59mn5sh"/><stop offset="1" class="cl7hn_59i"/></linearGradient><linearGradient id="iEAt31d" x1="4.939" x2="6.215" y1="27.964" y2="28.351" gradientUnits="userSpaceOnUse"><stop class="p557anbfl"/><stop offset="1" class="yymlc5b6t"/></linearGradient><linearGradient id="iZsgCZb" x1="7.69" x2="6.257" y1="29.509" y2="28.682" gradientUnits="userSpaceOnUse"><stop class="wzqb9gbrp"/><stop offset="1" class="cnr5izb-c"/></linearGradient><linearGradient id="i83tsoc" x1="6.531" x2="6.353" y1="27.031" y2="27.32" gradientUnits="userSpaceOnUse"><stop class="ym6ziioow"/><stop offset="1" class="tys9rybzz"/></linearGradient><linearGradient id="i9L0p6b" x1="4.942" x2="5.44" y1="29.424" y2="29.824" gradientUnits="userSpaceOnUse"><stop class="w4zixqbms"/><stop offset="1" class="wq3kgrbvi"/><stop offset="1" class="eo-bkb0sn"/></linearGradient><linearGradient id="iI7YWVb" x1="10.564" x2="13.345" y1="19.781" y2="22.65" gradientUnits="userSpaceOnUse"><stop class="tde6edcpz"/><stop offset="1" class="pm8hrpbrw"/></linearGradient><linearGradient id="ih80rUn" x1="21.428" x2="18.719" y1="4.078" y2="2.596" gradientUnits="userSpaceOnUse"><stop class="toj8k1b6u"/><stop offset=".339" class="k1mtvqaqb"/><stop offset="1" class="toj8k1b6u"/></linearGradient><radialGradient id="i7vGp1l" cx="0" cy="0" r="1" gradientTransform="rotate(151.144 5.744 6.939)scale(2.4229 2.39271)" gradientUnits="userSpaceOnUse"><stop class="zjodyhixa"/><stop offset="1" class="yzfufx_or"/><stop offset="1" class="ibbj0d-_r"/></radialGradient><radialGradient id="iEnLIDc" cx="0" cy="0" r="1" gradientTransform="matrix(1.10752 -.52992 1.23905 2.58958 14.502 26.291)" gradientUnits="userSpaceOnUse"><stop class="pe3hw-b2h"/><stop offset="1" class="kgerrxm9v"/></radialGradient><radialGradient id="iPVlqOd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.38708 3.92266 -4.72646 -2.87622 14.026 25.954)" gradientUnits="userSpaceOnUse"><stop class="c2sqojc3v"/><stop offset="1" class="inwztnbst"/></radialGradient><radialGradient id="i3m2VzW" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.66523 -4.10231 0 12.349 25.55)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="z7j99qk1m"/><stop offset="1" class="tmatlkbru"/></radialGradient><radialGradient id="iKXwW7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.0274 0 0 3.9567 9.676 27.262)" gradientUnits="userSpaceOnUse"><stop class="stml5__7l"/><stop offset="1" class="aiigfib-y"/></radialGradient><radialGradient id="iof0IGb" cx="0" cy="0" r="1" gradientTransform="matrix(9.03508 -16.18294 6.82694 3.81154 9.78 21.496)" gradientUnits="userSpaceOnUse"><stop class="unnkx0b5i"/><stop offset="1" class="qa0-0pbog"/></radialGradient><radialGradient id="ifV653b" cx="0" cy="0" r="1" gradientTransform="matrix(2.78125 -4.4375 3.06055 1.91824 12.442 21.745)" gradientUnits="userSpaceOnUse"><stop class="z1fqdib6i"/><stop offset="1" class="qo3lb7hwm"/></radialGradient><radialGradient id="i0LoGGe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.99141 -6.95223 4.42821 -4.45317 22.776 30.354)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="o8mbnkbuu"/><stop offset="1" class="d3z31rbxx"/></radialGradient><radialGradient id="inOXJ5A" cx="0" cy="0" r="1" gradientTransform="rotate(149.931 11.96 13)scale(5.17395 1.57367)" gradientUnits="userSpaceOnUse"><stop class="w4sdv4bzg"/><stop offset="1" class="zfsl7gtim"/></radialGradient><radialGradient id="i8DREJd" cx="0" cy="0" r="1" gradientTransform="rotate(-45.605 30.782 -5.494)scale(7.31574 8.64406)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="jqg627buf"/><stop offset=".561" class="hcwp80bzi"/><stop offset="1" class="qqkkt1bww"/></radialGradient><radialGradient id="iC6xD1d" cx="0" cy="0" r="1" gradientTransform="matrix(3.73694 -2.5625 3.33108 4.85777 8.67 25.969)" gradientUnits="userSpaceOnUse"><stop class="uo-9_o-sh"/><stop offset="1" class="qkf3v8b3b"/></radialGradient><radialGradient id="iGBgYce" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 -1.6875 2.0981 1.9427 12.031 28.031)" gradientUnits="userSpaceOnUse"><stop class="d86t_t1ez"/><stop offset=".978" class="eg22wvirx"/></radialGradient><filter id="iiGHGye" width="15.189" height="15.507" x="1.465" y="8.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.152941 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6320"/></filter><filter id="ikmBK0b" width="12.051" height="18.937" x="6.69" y="6.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6320" stdDeviation=".5"/></filter><filter id="ikVmSds" width="21.213" height="16.921" x="8.671" y="11.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.32549 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6320"/></filter><filter id="i3Ieulr" width="20.805" height="8.91" x="9.824" y="18.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6320" stdDeviation="1"/></filter><filter id="iEdZxBc" width="3.598" height="2.487" x="18.344" y="2.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6320" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:writing-hand-medium-dark" /></template>
<style>
.aiigfib-y {
  stop-color: var(--svg-color--825c57, #825C57);
  stop-opacity: 0;
}

.av7r-hnha {
  stop-color: var(--svg-color--9d807a, #9D807A);
  stop-opacity: 0;
}

.b6-6biqux {
  stop-color: var(--svg-color--996b5b, #996B5B);
}

.bf59mn5sh {
  stop-color: var(--svg-color--d4c5de, #D4C5DE);
  stop-opacity: 0;
}

.c2sqojc3v {
  stop-color: var(--svg-color--582a38, #582A38);
}

.cl7hn_59i {
  stop-color: var(--svg-color--9c979a, #9C979A);
  stop-opacity: 0;
}

.cnr5izb-c {
  stop-color: var(--svg-color--e086a3, #E086A3);
  stop-opacity: 0;
}

.cowi8hvle {
  d: path("M18.14 2.266a.5.5 0 0 1 .684-.184l2.963 1.71a.5.5 0 0 1 .184.682L8.43 28.119a.5.5 0 0 1-.211.199l-3.176 1.575c-.162.08-.298 0-.306-.18l-.226-3.541a.5.5 0 0 1 .065-.273z");
}

.d3z31rbxx {
  stop-color: var(--svg-color--7a3f69, #7A3F69);
  stop-opacity: 0;
}

.d86t_t1ez {
  stop-color: var(--svg-color--793e64, #793E64);
}

.dd0jy3bvw {
  d: path("m13.118 19.936l1.758-1.103a5.25 5.25 0 0 1 3.498-.757l1.468.2l-1.939 6.723l-.01-.016a.91.91 0 0 0-1.263-.313l-3.53 2.173c-1.33.82-3.169.432-4.005-.89c-.815-1.289-.413-3.048.838-3.922l3.178-2.082z");
}

.dkhzdbbmg {
  stop-color: var(--svg-color--6e4048, #6E4048);
}

.e4svvibki {
  d: path("m16 5.995l1.073-1.869l3.823 2.225l-1.07 1.87z");
}

.eg22wvirx {
  stop-color: var(--svg-color--793e64, #793E64);
  stop-opacity: 0;
}

.eo-bkb0sn {
  stop-color: var(--svg-color--3f0c46, #3F0C46);
}

.fkacmuq9i {
  stop-color: var(--svg-color--9d807a, #9D807A);
}

.ft5dv1b6b {
  fill: none;
}

.ftokoof_m {
  d: path("M9.933 22.03c-1.251.875-1.653 2.634-.838 3.924c.836 1.321 2.674 1.709 4.005.89l3.53-2.174a.91.91 0 0 1 1.263.313a6.84 6.84 0 0 0 6.588 3.321l3.832-.394a1.75 1.75 0 0 0 1.57-1.741v-7.13a2.81 2.81 0 0 0-1.736-2.585c-2.227-.928-6.282-2.689-10.295-4.785l-4.741 8.28z");
}

.gjt4qpb9s {
  stop-color: var(--svg-color--e98d53, #E98D53);
}

.hcwp80bzi {
  stop-color: var(--svg-color--5f3231, #5F3231);
}

.henyrkb1a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m18.719 2.503l2.848 1.737");
}

.hwdkzcb7b {
  stop-color: var(--svg-color--82645a, #82645A);
}

.i98t-7btg {
  d: path("M7.143 11.475a5 5 0 0 1 6.632-1.75l2.88 1.565l-4.306 7.08l-1.415-3.54l-4.317 7.519a2.535 2.535 0 0 1-3.49.922l-.116-.069a2.535 2.535 0 0 1-.88-3.494l3.62-5.986l-.005-.004l.281-.451l.583-.964c.171-.283.338-.556.533-.828");
}

.ibbj0d-_r {
  stop-color: var(--svg-color--6b473d, #6B473D);
  stop-opacity: 0;
}

.ini0sbbwd {
  fill: var(--svg-color--af837b, #AF837B);
  d: path("m17.818 20.62l-5.632 3.042a.69.69 0 1 0 .66 1.212l5.062-2.772a2 2 0 0 1 1.624-.132l9.097 3.2v-4.91h-9.385a3 3 0 0 0-1.426.36");
}

.inwztnbst {
  stop-color: var(--svg-color--713a59, #713A59);
}

.iy_62gb7c {
  stop-color: var(--svg-color--946660, #946660);
}

.j16v93btb {
  stop-color: var(--svg-color--82645a, #82645A);
  stop-opacity: 0;
}

.jqg627buf {
  stop-color: var(--svg-color--6f474b, #6F474B);
}

.k1mtvqaqb {
  stop-color: var(--svg-color--ff756d, #FF756D);
}

.kgerrxm9v {
  stop-color: var(--svg-color--542b34, #542B34);
  stop-opacity: 0;
}

.man8xwalw {
  stop-color: var(--svg-color--d9ccec, #D9CCEC);
}

.motml0dud {
  stop-color: var(--svg-color--9b7c6f, #9B7C6F);
}

.n22n_obox {
  d: path("m5.859 29.488l-.817.405c-.162.08-.298 0-.306-.18l-.058-.906z");
}

.no-oxqbvh {
  stop-color: var(--svg-color--e98d53, #E98D53);
  stop-opacity: 0;
}

.o8mbnkbuu {
  stop-color: var(--svg-color--7a3f69, #7A3F69);
}

.p557anbfl {
  stop-color: var(--svg-color--ce8c7f, #CE8C7F);
}

.pe3hw-b2h {
  stop-color: var(--svg-color--542b34, #542B34);
}

.pktn1mbpq {
  stop-color: var(--svg-color--986b5e, #986B5E);
}

.pm8hrpbrw {
  stop-color: var(--svg-color--81503c, #81503C);
  stop-opacity: 0;
}

.q7h9g6bki {
  width: 4.832px;
  height: 6.985px;
  x: 9.933px;
  y: 22.892px;
  rx: 2.416px;
}

.qa0-0pbog {
  stop-color: var(--svg-color--ec5047, #EC5047);
}

.qkf3v8b3b {
  stop-color: var(--svg-color--74464d, #74464D);
  stop-opacity: 0;
}

.qo3lb7hwm {
  stop-color: var(--svg-color--b94d0b, #B94D0B);
  stop-opacity: 0;
}

.qqkkt1bww {
  stop-color: var(--svg-color--5f3231, #5F3231);
  stop-opacity: 0;
}

.r0yxdcbwz {
  stop-color: var(--svg-color--6e3b44, #6E3B44);
}

.ri12kgbds {
  d: path("m16.925 13.287l-3.807 6.65l1.758-1.104a5.25 5.25 0 0 1 3.498-.757l2.431.33z");
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.stml5__7l {
  stop-color: var(--svg-color--825c57, #825C57);
}

.su_j375kk {
  stroke-linecap: round;
  d: path("M17.241 8.382L8.19 24.319");
}

.tde6edcpz {
  stop-color: var(--svg-color--81503c, #81503C);
}

.tmatlkbru {
  stop-color: var(--svg-color--473046, #473046);
}

.tn3edfbno {
  d: path("m15.173 27.117l-.671-1.725l1.352-1.986h14.03v4.579a2 2 0 0 1-2 2h-8.517a4.5 4.5 0 0 1-4.194-2.869");
}

.toj8k1b6u {
  stop-color: var(--svg-color--ff756d, #FF756D);
  stop-opacity: 0;
}

.tys9rybzz {
  stop-color: var(--svg-color--eb947f, #EB947F);
  stop-opacity: 0;
}

.unnkx0b5i {
  stop-color: var(--svg-color--da7838, #DA7838);
}

.uo-9_o-sh {
  stop-color: var(--svg-color--74464d, #74464D);
}

.w4sdv4bzg {
  stop-color: var(--svg-color--a78071, #A78071);
}

.w4zixqbms {
  stop-color: var(--svg-color--3b1a3b, #3B1A3B);
}

.w79k2acia {
  d: path("M8.386 28.182a.5.5 0 0 1-.168.136l-3.176 1.575c-.162.08-.298 0-.306-.18l-.226-3.541a.5.5 0 0 1 .02-.169z");
}

.wq3kgrbvi {
  stop-color: var(--svg-color--5a1870, #5A1870);
}

.wzqb9gbrp {
  stop-color: var(--svg-color--e086a3, #E086A3);
}

.x-50qsb-j {
  stop-color: var(--svg-color--9e999f, #9E999F);
}

.x8pg59vat {
  stop-color: var(--svg-color--986b5e, #986B5E);
  stop-opacity: 0;
}

.xv0f92bag {
  stop-color: var(--svg-color--9b7c6f, #9B7C6F);
  stop-opacity: 0;
}

.ym6ziioow {
  stop-color: var(--svg-color--eb947f, #EB947F);
}

.yymlc5b6t {
  stop-color: var(--svg-color--e79196, #E79196);
}

.yzfufx_or {
  stop-color: var(--svg-color--433230, #433230);
  stop-opacity: 0;
}

.z1fqdib6i {
  stop-color: var(--svg-color--b94d0b, #B94D0B);
}

.z7j99qk1m {
  stop-color: var(--svg-color--473046, #473046);
  stop-opacity: 0;
}

.zfsl7gtim {
  stop-color: var(--svg-color--a78071, #A78071);
  stop-opacity: 0;
}

.zh6g_rbhx {
  stop-color: var(--svg-color--7b584b, #7B584B);
}

.zjodyhixa {
  stop-color: var(--svg-color--6b473d, #6B473D);
}

.zlgf74bzk {
  stop-color: var(--svg-color--844f80, #844F80);
}

</style>
