<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iqvhPWd)"><path fill="url(#iZ1Lb1b)" class="ajl0ikidv"/><path fill="url(#iAQ24Qd)" class="ajl0ikidv"/></g><path fill="url(#iota0zc)" class="tn3edfbno"/><path fill="url(#iyKwRGe)" class="tn3edfbno"/><rect fill="url(#ihNI5qb)" class="q7h9g6bki"/><rect fill="url(#i3m2VzW)" class="q7h9g6bki"/><rect fill="url(#i5rjHyq)" class="q7h9g6bki"/><path fill="url(#iZMFZVb)" class="fzcwmf9bu"/><path fill="url(#ifV653b)" class="fzcwmf9bu"/><g filter="url(#iXlKVqb)"><path stroke="url(#i2ZmQAc)" class="su_j375kk"/></g><g filter="url(#iWiYi3Z)"><path fill="url(#igfYuOe)" class="ftokoof_m"/><path fill="url(#iYMMbjd)" class="ftokoof_m"/><path fill="url(#iETTPYb)" class="ftokoof_m"/><path fill="url(#i14l4Jd)" class="ftokoof_m"/></g><path fill="url(#iyJTHbd)" class="ftokoof_m"/><path fill="url(#iObwmHd)" class="ftokoof_m"/><path fill="url(#iAeDQae)" class="ri12kgbds"/><path fill="url(#iYwKo0t)" class="e4svvibki"/><path fill="url(#iTMmIdc)" class="e4svvibki"/><path fill="url(#izn0qGc)" class="w79k2acia"/><path fill="url(#iJb0YGS)" class="w79k2acia"/><path fill="url(#iDiVvfd)" class="w79k2acia"/><path fill="url(#i9L0p6b)" class="n22n_obox"/><g filter="url(#iR2x5bc)"><path class="to-4c6bpr"/></g><path fill="url(#icPwDqd)" class="dd0jy3bvw"/><path fill="url(#iwUWzJc)" class="dd0jy3bvw"/><g filter="url(#ipZd3rc)"><path stroke="url(#ih80rUn)" class="henyrkb1a"/></g><defs><linearGradient id="iZ1Lb1b" x1="11.914" x2="4.985" y1="10.071" y2="21.98" gradientUnits="userSpaceOnUse"><stop class="u_pi4nbrf"/><stop offset="1" class="e3szmybxd"/></linearGradient><linearGradient id="iota0zc" x1="16.529" x2="20.534" y1="24.288" y2="29.334" gradientUnits="userSpaceOnUse"><stop class="ujyma_bra"/><stop offset="1" class="sba2bdbbu"/></linearGradient><linearGradient id="iyKwRGe" x1="30.064" x2="28.992" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="byty_gb0s"/><stop offset="1" class="vi5m5cbtn"/></linearGradient><linearGradient id="i2ZmQAc" x1="10.097" x2="18.224" y1="22.631" y2="8.382" gradientUnits="userSpaceOnUse"><stop class="gjt4qpb9s"/><stop offset="1" class="no-oxqbvh"/></linearGradient><linearGradient id="igfYuOe" x1="17.139" x2="28.784" y1="13.161" y2="24.614" gradientUnits="userSpaceOnUse"><stop class="uhdj5gb6f"/><stop offset="1" class="bjb8jwbqd"/></linearGradient><linearGradient id="i14l4Jd" x1="24.375" x2="23.375" y1="13.844" y2="15.781" gradientUnits="userSpaceOnUse"><stop class="id19h77qj"/><stop offset="1" class="v6h3qtb9x"/></linearGradient><linearGradient id="iyJTHbd" x1="23.814" x2="22.001" y1="14.125" y2="17.875" gradientUnits="userSpaceOnUse"><stop class="gu7zfbc4m"/><stop offset="1" class="ui2k__lzg"/></linearGradient><linearGradient id="iObwmHd" x1="30.376" x2="27.814" y1="21.188" y2="21.188" gradientUnits="userSpaceOnUse"><stop class="gu7zfbc4m"/><stop offset="1" class="ui2k__lzg"/></linearGradient><linearGradient id="iYwKo0t" x1="16.345" x2="20.896" y1="5.063" y2="7.563" gradientUnits="userSpaceOnUse"><stop class="x-50qsb-j"/><stop offset="1" class="x11r1_b1l"/></linearGradient><linearGradient id="iTMmIdc" x1="20.454" x2="20.126" y1="7.211" y2="7.031" gradientUnits="userSpaceOnUse"><stop class="si_znv48i"/><stop offset="1" class="bf59mn5sh"/><stop offset="1" class="cl7hn_59i"/></linearGradient><linearGradient id="izn0qGc" x1="4.939" x2="6.215" y1="27.964" y2="28.351" gradientUnits="userSpaceOnUse"><stop class="ha81s-bfu"/><stop offset="1" class="wcszqj8in"/></linearGradient><linearGradient id="iJb0YGS" x1="7.69" x2="6.257" y1="29.509" y2="28.682" gradientUnits="userSpaceOnUse"><stop class="p_q4-abgm"/><stop offset="1" class="nx31evb6j"/></linearGradient><linearGradient id="iDiVvfd" x1="6.531" x2="6.353" y1="27.031" y2="27.32" gradientUnits="userSpaceOnUse"><stop class="qmabrhbbc"/><stop offset="1" class="mio1ctbpy"/></linearGradient><linearGradient id="i9L0p6b" x1="4.942" x2="5.44" y1="29.424" y2="29.824" gradientUnits="userSpaceOnUse"><stop class="w4zixqbms"/><stop offset="1" class="wq3kgrbvi"/><stop offset="1" class="eo-bkb0sn"/></linearGradient><linearGradient id="icPwDqd" x1="10.564" x2="13.345" y1="19.781" y2="22.65" gradientUnits="userSpaceOnUse"><stop class="jleb8rbag"/><stop offset="1" class="nh_-1-bqx"/></linearGradient><linearGradient id="ih80rUn" x1="21.428" x2="18.719" y1="4.078" y2="2.596" gradientUnits="userSpaceOnUse"><stop class="toj8k1b6u"/><stop offset=".339" class="k1mtvqaqb"/><stop offset="1" class="toj8k1b6u"/></linearGradient><radialGradient id="iAQ24Qd" cx="0" cy="0" r="1" gradientTransform="rotate(151.144 5.744 6.939)scale(2.4229 2.39271)" gradientUnits="userSpaceOnUse"><stop class="ceyyf_-jw"/><stop offset="1" class="yzfufx_or"/></radialGradient><radialGradient id="ihNI5qb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7323 1.68053 -2.0249 -2.08727 13.972 26.384)" gradientUnits="userSpaceOnUse"><stop class="equb0mbzx"/><stop offset="1" class="pjotexbsk"/></radialGradient><radialGradient id="i3m2VzW" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.66523 -4.10231 0 12.349 25.55)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="z7j99qk1m"/><stop offset="1" class="tmatlkbru"/></radialGradient><radialGradient id="i5rjHyq" cx="0" cy="0" r="1" gradientTransform="matrix(1.5309 1.62182 -2.36979 2.23692 9.933 26.75)" gradientUnits="userSpaceOnUse"><stop class="xje_oac3l"/><stop offset="1" class="jb-9vog8s"/></radialGradient><radialGradient id="iZMFZVb" cx="0" cy="0" r="1" gradientTransform="matrix(9.03508 -16.18294 6.82694 3.81154 9.78 21.496)" gradientUnits="userSpaceOnUse"><stop class="ql1-pb6va"/><stop offset="1" class="qa0-0pbog"/></radialGradient><radialGradient id="ifV653b" cx="0" cy="0" r="1" gradientTransform="matrix(2.78125 -4.4375 3.06055 1.91824 12.442 21.745)" gradientUnits="userSpaceOnUse"><stop class="z1fqdib6i"/><stop offset="1" class="qo3lb7hwm"/></radialGradient><radialGradient id="iYMMbjd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.99141 -6.95223 4.42821 -4.45317 22.776 30.354)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6zi2m8nh"/><stop offset="1" class="iv84fxbaf"/></radialGradient><radialGradient id="iETTPYb" cx="0" cy="0" r="1" gradientTransform="rotate(149.931 11.96 13)scale(5.17395 1.57367)" gradientUnits="userSpaceOnUse"><stop class="khtztbcsi"/><stop offset="1" class="rokujeq1y"/></radialGradient><radialGradient id="iAeDQae" cx="0" cy="0" r="1" gradientTransform="rotate(-45.605 30.782 -5.494)scale(7.31574 8.64406)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="htbu2bcgk"/><stop offset=".561" class="xft90lbbl"/><stop offset="1" class="jbpxozbpt"/></radialGradient><radialGradient id="iwUWzJc" cx="0" cy="0" r="1" gradientTransform="matrix(3.73694 -2.5625 3.33108 4.85777 8.67 25.969)" gradientUnits="userSpaceOnUse"><stop class="jleb8rbag"/><stop offset="1" class="nh_-1-bqx"/></radialGradient><filter id="iqvhPWd" width="15.189" height="15.507" x="1.465" y="8.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.145098 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6305"/></filter><filter id="iXlKVqb" width="12.051" height="18.937" x="6.69" y="6.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6305" stdDeviation=".5"/></filter><filter id="iWiYi3Z" width="21.213" height="16.921" x="8.671" y="11.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.254902 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6305"/></filter><filter id="iR2x5bc" width="20.805" height="8.91" x="9.824" y="18.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6305" stdDeviation="1"/></filter><filter id="ipZd3rc" width="3.598" height="2.487" x="18.344" y="2.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6305" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:writing-hand-dark" /></template>
<style>
.ajl0ikidv {
  d: path("m6.784 12.051l.359-.576a5 5 0 0 1 6.632-1.75l2.88 1.565l-4.306 7.08l-1.415-3.54l-4.317 7.519a2.535 2.535 0 0 1-3.49.922l-.116-.069a2.535 2.535 0 0 1-.88-3.494l3.62-5.986l-.005-.004l.281-.451l.583-.964q.08-.133.174-.252");
}

.bf59mn5sh {
  stop-color: var(--svg-color--d4c5de, #D4C5DE);
  stop-opacity: 0;
}

.bjb8jwbqd {
  stop-color: var(--svg-color--472c33, #472C33);
}

.byty_gb0s {
  stop-color: var(--svg-color--635455, #635455);
}

.ceyyf_-jw {
  stop-color: var(--svg-color--433230, #433230);
}

.cl7hn_59i {
  stop-color: var(--svg-color--9c979a, #9C979A);
  stop-opacity: 0;
}

.dd0jy3bvw {
  d: path("m13.118 19.936l1.758-1.103a5.25 5.25 0 0 1 3.498-.757l1.468.2l-1.939 6.723l-.01-.016a.91.91 0 0 0-1.263-.313l-3.53 2.173c-1.33.82-3.169.432-4.005-.89c-.815-1.289-.413-3.048.838-3.922l3.178-2.082z");
}

.e3szmybxd {
  stop-color: var(--svg-color--3c2229, #3C2229);
}

.e4svvibki {
  d: path("m16 5.995l1.073-1.869l3.823 2.225l-1.07 1.87z");
}

.eo-bkb0sn {
  stop-color: var(--svg-color--3f0c46, #3F0C46);
}

.equb0mbzx {
  stop-color: var(--svg-color--361c2c, #361C2C);
}

.ft5dv1b6b {
  fill: none;
}

.ftokoof_m {
  d: path("M9.933 22.03c-1.251.875-1.653 2.634-.838 3.924c.836 1.321 2.674 1.709 4.005.89l3.53-2.174a.91.91 0 0 1 1.263.313a6.84 6.84 0 0 0 6.588 3.321l3.832-.394a1.75 1.75 0 0 0 1.57-1.741v-7.13a2.81 2.81 0 0 0-1.736-2.585c-2.227-.928-6.282-2.689-10.295-4.785l-4.741 8.28z");
}

.fzcwmf9bu {
  d: path("M18.14 2.266a.5.5 0 0 1 .684-.184l2.963 1.71a.5.5 0 0 1 .184.681L8.43 28.12a.5.5 0 0 1-.211.199l-3.176 1.575c-.162.08-.298 0-.306-.18l-.226-3.541a.5.5 0 0 1 .065-.273z");
}

.gjt4qpb9s {
  stop-color: var(--svg-color--e98d53, #E98D53);
}

.gu7zfbc4m {
  stop-color: var(--svg-color--563b39, #563B39);
}

.ha81s-bfu {
  stop-color: var(--svg-color--bf8971, #BF8971);
}

.henyrkb1a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m18.719 2.503l2.848 1.737");
}

.htbu2bcgk {
  stop-color: var(--svg-color--402f31, #402F31);
}

.id19h77qj {
  stop-color: var(--svg-color--62504d, #62504D);
}

.iv84fxbaf {
  stop-color: var(--svg-color--3c2034, #3C2034);
  stop-opacity: 0;
}

.jb-9vog8s {
  stop-color: var(--svg-color--493634, #493634);
  stop-opacity: 0;
}

.jbpxozbpt {
  stop-color: var(--svg-color--2f1819, #2F1819);
  stop-opacity: 0;
}

.jleb8rbag {
  stop-color: var(--svg-color--3a222b, #3A222B);
}

.k1mtvqaqb {
  stop-color: var(--svg-color--ff756d, #FF756D);
}

.khtztbcsi {
  stop-color: var(--svg-color--67514e, #67514E);
}

.mio1ctbpy {
  stop-color: var(--svg-color--de9e82, #DE9E82);
  stop-opacity: 0;
}

.n22n_obox {
  d: path("m5.859 29.488l-.817.405c-.162.08-.298 0-.306-.18l-.058-.906z");
}

.nh_-1-bqx {
  stop-color: var(--svg-color--3a222b, #3A222B);
  stop-opacity: 0;
}

.no-oxqbvh {
  stop-color: var(--svg-color--e98d53, #E98D53);
  stop-opacity: 0;
}

.nx31evb6j {
  stop-color: var(--svg-color--c4848c, #C4848C);
  stop-opacity: 0;
}

.p_q4-abgm {
  stop-color: var(--svg-color--c4848c, #C4848C);
}

.pjotexbsk {
  stop-color: var(--svg-color--271b1e, #271B1E);
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

.ql1-pb6va {
  stop-color: var(--svg-color--db7c3c, #DB7C3C);
}

.qmabrhbbc {
  stop-color: var(--svg-color--de9e82, #DE9E82);
}

.qo3lb7hwm {
  stop-color: var(--svg-color--b94d0b, #B94D0B);
  stop-opacity: 0;
}

.ri12kgbds {
  d: path("m16.925 13.287l-3.807 6.65l1.758-1.104a5.25 5.25 0 0 1 3.498-.757l2.431.33z");
}

.rokujeq1y {
  stop-color: var(--svg-color--67514e, #67514E);
  stop-opacity: 0;
}

.sba2bdbbu {
  stop-color: var(--svg-color--4c354d, #4C354D);
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.su_j375kk {
  stroke-linecap: round;
  d: path("M17.241 8.382L8.19 24.319");
}

.tmatlkbru {
  stop-color: var(--svg-color--473046, #473046);
}

.tn3edfbno {
  d: path("m15.173 27.117l-.671-1.725l1.352-1.986h14.03v4.579a2 2 0 0 1-2 2h-8.517a4.5 4.5 0 0 1-4.194-2.869");
}

.to-4c6bpr {
  fill: var(--svg-color--685352, #685352);
  d: path("m17.818 20.62l-5.632 3.042a.69.69 0 1 0 .66 1.212l5.062-2.772a2 2 0 0 1 1.624-.132l9.097 3.2v-4.91h-9.385a3 3 0 0 0-1.426.36");
}

.toj8k1b6u {
  stop-color: var(--svg-color--ff756d, #FF756D);
  stop-opacity: 0;
}

.u_pi4nbrf {
  stop-color: var(--svg-color--462f2d, #462F2D);
}

.u6zi2m8nh {
  stop-color: var(--svg-color--3c2034, #3C2034);
}

.uhdj5gb6f {
  stop-color: var(--svg-color--593e3a, #593E3A);
}

.ui2k__lzg {
  stop-color: var(--svg-color--563b39, #563B39);
  stop-opacity: 0;
}

.ujyma_bra {
  stop-color: var(--svg-color--3b2629, #3B2629);
}

.v6h3qtb9x {
  stop-color: var(--svg-color--62504d, #62504D);
  stop-opacity: 0;
}

.vi5m5cbtn {
  stop-color: var(--svg-color--635455, #635455);
  stop-opacity: 0;
}

.w4zixqbms {
  stop-color: var(--svg-color--3b1a3b, #3B1A3B);
}

.w79k2acia {
  d: path("M8.386 28.182a.5.5 0 0 1-.168.136l-3.176 1.575c-.162.08-.298 0-.306-.18l-.226-3.541a.5.5 0 0 1 .02-.169z");
}

.wcszqj8in {
  stop-color: var(--svg-color--d28f7f, #D28F7F);
}

.wq3kgrbvi {
  stop-color: var(--svg-color--5a1870, #5A1870);
}

.x-50qsb-j {
  stop-color: var(--svg-color--9e999f, #9E999F);
}

.x11r1_b1l {
  stop-color: var(--svg-color--d2ccdd, #D2CCDD);
}

.xft90lbbl {
  stop-color: var(--svg-color--2f1819, #2F1819);
}

.xje_oac3l {
  stop-color: var(--svg-color--493634, #493634);
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

</style>
