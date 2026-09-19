<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iSe11jc)"><path fill="url(#iPJ8TCe)" class="lx3glwb1b"/><path fill="url(#i8zvRwd)" class="lx3glwb1b"/><path fill="url(#iHpKu3d)" class="lx3glwb1b"/></g><path fill="url(#iTGWGPe)" class="tn3edfbno"/><path fill="url(#iDZHTyb)" class="tn3edfbno"/><path fill="url(#i25snRd)" class="tn3edfbno"/><rect fill="url(#iUGvVdd)" class="q7h9g6bki"/><rect fill="url(#ibV5VKk)" class="q7h9g6bki"/><rect fill="url(#iTZ9goc)" class="q7h9g6bki"/><path fill="url(#ibq6Lrb)" class="fzcwmf9bu"/><path fill="url(#ifV653b)" class="fzcwmf9bu"/><g filter="url(#iDHu7ad)"><path stroke="url(#i2ZmQAc)" class="su_j375kk"/></g><g filter="url(#iz3SLPd)"><path fill="url(#ig7j0Cx)" class="ftokoof_m"/><path fill="url(#idnRoDv)" class="ftokoof_m"/><path fill="url(#iSst5ge)" class="ftokoof_m"/><path fill="url(#igKhYQb)" class="ftokoof_m"/></g><path fill="url(#ixKOUUd)" class="ftokoof_m"/><path fill="url(#ijPeNPc)" class="ftokoof_m"/><path fill="url(#imtO5Jd)" class="ri12kgbds"/><path fill="url(#iXsQUJc)" class="e4svvibki"/><path fill="url(#ioUTSAe)" class="e4svvibki"/><path fill="url(#iEAt31d)" class="w79k2acia"/><path fill="url(#iZsgCZb)" class="w79k2acia"/><path fill="url(#i83tsoc)" class="w79k2acia"/><path fill="url(#i9L0p6b)" class="n22n_obox"/><g filter="url(#ibByxnd)"><path fill="url(#i9aROtb)" class="zn4my7bbd"/></g><path fill="url(#isUmX8Q)" class="dd0jy3bvw"/><path fill="url(#iNxKwzb)" class="dd0jy3bvw"/><path fill="url(#ivupGve)" class="dd0jy3bvw"/><g filter="url(#iZwaeEb)"><path stroke="url(#ih80rUn)" class="henyrkb1a"/></g><defs><linearGradient id="iPJ8TCe" x1="12.229" x2="5.3" y1="9.853" y2="21.762" gradientUnits="userSpaceOnUse"><stop class="j9rc9t_lz"/><stop offset="1" class="uz02ehbzl"/></linearGradient><linearGradient id="iHpKu3d" x1="3.702" x2="4.555" y1="16.743" y2="17.283" gradientUnits="userSpaceOnUse"><stop class="m5qh6ub8b"/><stop offset="1" class="rt2_uz8wy"/></linearGradient><linearGradient id="iTGWGPe" x1="16.529" x2="23.094" y1="24.288" y2="30.41" gradientUnits="userSpaceOnUse"><stop class="zy_2q-jqi"/><stop offset="1" class="qj9odc_am"/></linearGradient><linearGradient id="iDZHTyb" x1="30.064" x2="28.992" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="dettpebyq"/><stop offset="1" class="z94p-_exj"/></linearGradient><linearGradient id="iTZ9goc" x1="9.333" x2="11.13" y1="27.262" y2="27.262" gradientUnits="userSpaceOnUse"><stop class="dqig249xg"/><stop offset="1" class="ca1i0m00z"/></linearGradient><linearGradient id="i2ZmQAc" x1="10.097" x2="18.224" y1="22.631" y2="8.382" gradientUnits="userSpaceOnUse"><stop class="gjt4qpb9s"/><stop offset="1" class="no-oxqbvh"/></linearGradient><linearGradient id="ig7j0Cx" x1="17.949" x2="28.389" y1="13.474" y2="23.983" gradientUnits="userSpaceOnUse"><stop class="ih4eukvrc"/><stop offset="1" class="wv0x-1pad"/></linearGradient><linearGradient id="igKhYQb" x1="24.375" x2="23.375" y1="13.844" y2="15.781" gradientUnits="userSpaceOnUse"><stop class="m5xscubrj"/><stop offset="1" class="ojn4qgbgh"/></linearGradient><linearGradient id="ixKOUUd" x1="23.814" x2="22.001" y1="14.125" y2="17.875" gradientUnits="userSpaceOnUse"><stop class="ocf0fwqhu"/><stop offset="1" class="jtid8uogd"/></linearGradient><linearGradient id="ijPeNPc" x1="30.376" x2="27.814" y1="21.188" y2="21.188" gradientUnits="userSpaceOnUse"><stop class="ocf0fwqhu"/><stop offset="1" class="jtid8uogd"/></linearGradient><linearGradient id="iXsQUJc" x1="15.539" x2="19.525" y1="4.487" y2="6.501" gradientUnits="userSpaceOnUse"><stop class="x-50qsb-j"/><stop offset="1" class="man8xwalw"/></linearGradient><linearGradient id="ioUTSAe" x1="20.896" x2="19.969" y1="7.453" y2="6.875" gradientUnits="userSpaceOnUse"><stop class="si_znv48i"/><stop offset="1" class="bf59mn5sh"/><stop offset="1" class="cl7hn_59i"/></linearGradient><linearGradient id="iEAt31d" x1="4.939" x2="6.215" y1="27.964" y2="28.351" gradientUnits="userSpaceOnUse"><stop class="p557anbfl"/><stop offset="1" class="yymlc5b6t"/></linearGradient><linearGradient id="iZsgCZb" x1="7.69" x2="6.257" y1="29.509" y2="28.682" gradientUnits="userSpaceOnUse"><stop class="wzqb9gbrp"/><stop offset="1" class="cnr5izb-c"/></linearGradient><linearGradient id="i83tsoc" x1="6.531" x2="6.353" y1="27.031" y2="27.32" gradientUnits="userSpaceOnUse"><stop class="ym6ziioow"/><stop offset="1" class="tys9rybzz"/></linearGradient><linearGradient id="i9L0p6b" x1="4.942" x2="5.44" y1="29.424" y2="29.824" gradientUnits="userSpaceOnUse"><stop class="w4zixqbms"/><stop offset="1" class="wq3kgrbvi"/><stop offset="1" class="eo-bkb0sn"/></linearGradient><linearGradient id="i9aROtb" x1="14.855" x2="31.23" y1="22.715" y2="23.25" gradientUnits="userSpaceOnUse"><stop class="jq9e5d-ak"/><stop offset="1" class="dwwwipb2q"/></linearGradient><linearGradient id="isUmX8Q" x1="10.564" x2="13.345" y1="19.781" y2="22.65" gradientUnits="userSpaceOnUse"><stop class="inm3cibvj"/><stop offset="1" class="x_wna8b6t"/></linearGradient><linearGradient id="ih80rUn" x1="21.428" x2="18.719" y1="4.078" y2="2.596" gradientUnits="userSpaceOnUse"><stop class="toj8k1b6u"/><stop offset=".339" class="k1mtvqaqb"/><stop offset="1" class="toj8k1b6u"/></linearGradient><radialGradient id="i8zvRwd" cx="0" cy="0" r="1" gradientTransform="rotate(151.144 5.93 6.87)scale(2.4229 2.39271)" gradientUnits="userSpaceOnUse"><stop class="ccabpbbfr"/><stop offset="1" class="w2x_8yxpr"/></radialGradient><radialGradient id="i25snRd" cx="0" cy="0" r="1" gradientTransform="matrix(1.10752 -.52992 1.23905 2.58958 14.502 26.291)" gradientUnits="userSpaceOnUse"><stop class="x0rhptc7w"/><stop offset="1" class="rrdf1tb9d"/></radialGradient><radialGradient id="iUGvVdd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.38708 3.92266 -4.72646 -2.87622 14.026 25.954)" gradientUnits="userSpaceOnUse"><stop class="yaddi-bgh"/><stop offset="1" class="v3t2mxb5a"/></radialGradient><radialGradient id="ibV5VKk" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.4973 -3.95465 0 12.349 25.55)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="wsjm7obid"/><stop offset="1" class="rp0g791ql"/></radialGradient><radialGradient id="ibq6Lrb" cx="0" cy="0" r="1" gradientTransform="matrix(9.03508 -16.18294 6.82694 3.81154 9.78 21.496)" gradientUnits="userSpaceOnUse"><stop class="unnkx0b5i"/><stop offset="1" class="p-rdzgbpt"/></radialGradient><radialGradient id="ifV653b" cx="0" cy="0" r="1" gradientTransform="matrix(2.78125 -4.4375 3.06055 1.91824 12.442 21.745)" gradientUnits="userSpaceOnUse"><stop class="z1fqdib6i"/><stop offset="1" class="qo3lb7hwm"/></radialGradient><radialGradient id="idnRoDv" cx="0" cy="0" r="1" gradientTransform="matrix(-6.99141 -6.95223 4.42821 -4.45317 22.776 30.354)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="ajklhrb2n"/><stop offset="1" class="ivupz0bxa"/></radialGradient><radialGradient id="iSst5ge" cx="0" cy="0" r="1" gradientTransform="rotate(149.931 11.96 13)scale(5.17395 1.57367)" gradientUnits="userSpaceOnUse"><stop class="eju2vgt4d"/><stop offset="1" class="bxw6lab7o"/></radialGradient><radialGradient id="imtO5Jd" cx="0" cy="0" r="1" gradientTransform="rotate(-45.605 30.782 -5.494)scale(7.31574 8.64406)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="m261m_boe"/><stop offset=".561" class="v98elou1m"/><stop offset="1" class="pi9myfbec"/></radialGradient><radialGradient id="iNxKwzb" cx="0" cy="0" r="1" gradientTransform="matrix(3.73694 -2.5625 3.33108 4.85777 8.67 25.969)" gradientUnits="userSpaceOnUse"><stop class="wx8no8lpc"/><stop offset="1" class="da3_inbdr"/></radialGradient><radialGradient id="ivupGve" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 -1.6875 2.0981 1.9427 12.031 28.031)" gradientUnits="userSpaceOnUse"><stop class="onzqjjixs"/><stop offset="1" class="fje43bhwd"/></radialGradient><filter id="iSe11jc" width="15.189" height="15.507" x="1.78" y="7.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.372549 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6350"/></filter><filter id="iDHu7ad" width="12.051" height="18.937" x="6.69" y="6.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6350" stdDeviation=".5"/></filter><filter id="iz3SLPd" width="21.213" height="16.921" x="8.671" y="11.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.462745 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6350"/></filter><filter id="ibByxnd" width="20.805" height="8.91" x="9.824" y="18.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6350" stdDeviation="1"/></filter><filter id="iZwaeEb" width="3.598" height="2.487" x="18.344" y="2.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6350" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:writing-hand-medium-light" /></template>
<style>
.ajklhrb2n {
  stop-color: var(--svg-color--bc7588, #BC7588);
}

.bf59mn5sh {
  stop-color: var(--svg-color--d4c5de, #D4C5DE);
  stop-opacity: 0;
}

.bxw6lab7o {
  stop-color: var(--svg-color--ffd0a8, #FFD0A8);
  stop-opacity: 0;
}

.ca1i0m00z {
  stop-color: var(--svg-color--d69983, #D69983);
  stop-opacity: 0;
}

.ccabpbbfr {
  stop-color: var(--svg-color--c28a69, #C28A69);
}

.cl7hn_59i {
  stop-color: var(--svg-color--9c979a, #9C979A);
  stop-opacity: 0;
}

.cnr5izb-c {
  stop-color: var(--svg-color--e086a3, #E086A3);
  stop-opacity: 0;
}

.da3_inbdr {
  stop-color: var(--svg-color--ba7a7b, #BA7A7B);
  stop-opacity: 0;
}

.dd0jy3bvw {
  d: path("m13.118 19.936l1.758-1.103a5.25 5.25 0 0 1 3.498-.757l1.468.2l-1.939 6.723l-.01-.016a.91.91 0 0 0-1.263-.313l-3.53 2.173c-1.33.82-3.169.432-4.005-.89c-.815-1.289-.413-3.048.838-3.922l3.178-2.082z");
}

.dettpebyq {
  stop-color: var(--svg-color--e0b7a0, #E0B7A0);
}

.dqig249xg {
  stop-color: var(--svg-color--d69983, #D69983);
}

.dwwwipb2q {
  stop-color: var(--svg-color--ffd3ac, #FFD3AC);
}

.e4svvibki {
  d: path("m16 5.995l1.073-1.869l3.823 2.225l-1.07 1.87z");
}

.eju2vgt4d {
  stop-color: var(--svg-color--ffd0a8, #FFD0A8);
}

.eo-bkb0sn {
  stop-color: var(--svg-color--3f0c46, #3F0C46);
}

.fje43bhwd {
  stop-color: var(--svg-color--b66f8a, #B66F8A);
  stop-opacity: 0;
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

.henyrkb1a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m18.719 2.503l2.848 1.737");
}

.ih4eukvrc {
  stop-color: var(--svg-color--fdbd96, #FDBD96);
}

.inm3cibvj {
  stop-color: var(--svg-color--dd8b63, #DD8B63);
}

.ivupz0bxa {
  stop-color: var(--svg-color--bc7588, #BC7588);
  stop-opacity: 0;
}

.j9rc9t_lz {
  stop-color: var(--svg-color--d9a485, #D9A485);
}

.jq9e5d-ak {
  stop-color: var(--svg-color--ffccb3, #FFCCB3);
}

.jtid8uogd {
  stop-color: var(--svg-color--eebf97, #EEBF97);
  stop-opacity: 0;
}

.k1mtvqaqb {
  stop-color: var(--svg-color--ff756d, #FF756D);
}

.lx3glwb1b {
  d: path("M7.457 11.257a5 5 0 0 1 6.632-1.75l2.88 1.565l-4.305 7.08l-1.415-3.54l-4.317 7.519a2.535 2.535 0 0 1-3.49.922l-.116-.069a2.535 2.535 0 0 1-.88-3.494l3.62-5.986l-.005-.004l.28-.451l.584-.964c.17-.283.338-.556.532-.828");
}

.m261m_boe {
  stop-color: var(--svg-color--c78173, #C78173);
}

.m5qh6ub8b {
  stop-color: var(--svg-color--d9a484, #D9A484);
}

.m5xscubrj {
  stop-color: var(--svg-color--f1c198, #F1C198);
}

.man8xwalw {
  stop-color: var(--svg-color--d9ccec, #D9CCEC);
}

.n22n_obox {
  d: path("m5.859 29.488l-.817.405c-.162.08-.298 0-.306-.18l-.058-.906z");
}

.no-oxqbvh {
  stop-color: var(--svg-color--e98d53, #E98D53);
  stop-opacity: 0;
}

.ocf0fwqhu {
  stop-color: var(--svg-color--eebf97, #EEBF97);
}

.ojn4qgbgh {
  stop-color: var(--svg-color--f1c198, #F1C198);
  stop-opacity: 0;
}

.onzqjjixs {
  stop-color: var(--svg-color--b66f8a, #B66F8A);
}

.p-rdzgbpt {
  stop-color: var(--svg-color--f14e4b, #F14E4B);
}

.p557anbfl {
  stop-color: var(--svg-color--ce8c7f, #CE8C7F);
}

.pi9myfbec {
  stop-color: var(--svg-color--ba6857, #BA6857);
  stop-opacity: 0;
}

.q7h9g6bki {
  width: 4.832px;
  height: 6.985px;
  x: 9.933px;
  y: 22.892px;
  rx: 2.416px;
}

.qj9odc_am {
  stop-color: var(--svg-color--b37197, #B37197);
}

.qo3lb7hwm {
  stop-color: var(--svg-color--b94d0b, #B94D0B);
  stop-opacity: 0;
}

.ri12kgbds {
  d: path("m16.925 13.287l-3.807 6.65l1.758-1.104a5.25 5.25 0 0 1 3.498-.757l2.431.33z");
}

.rp0g791ql {
  stop-color: var(--svg-color--b46d8c, #B46D8C);
}

.rrdf1tb9d {
  stop-color: var(--svg-color--a26160, #A26160);
  stop-opacity: 0;
}

.rt2_uz8wy {
  stop-color: var(--svg-color--d9a484, #D9A484);
  stop-opacity: 0;
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.su_j375kk {
  stroke-linecap: round;
  d: path("M17.241 8.382L8.19 24.319");
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

.uz02ehbzl {
  stop-color: var(--svg-color--ce8b7d, #CE8B7D);
}

.v3t2mxb5a {
  stop-color: var(--svg-color--b47079, #B47079);
}

.v98elou1m {
  stop-color: var(--svg-color--ba6857, #BA6857);
}

.w2x_8yxpr {
  stop-color: var(--svg-color--c28a69, #C28A69);
  stop-opacity: 0;
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

.wsjm7obid {
  stop-color: var(--svg-color--b46d8c, #B46D8C);
  stop-opacity: 0;
}

.wv0x-1pad {
  stop-color: var(--svg-color--e4a998, #E4A998);
}

.wx8no8lpc {
  stop-color: var(--svg-color--ba7a7b, #BA7A7B);
}

.wzqb9gbrp {
  stop-color: var(--svg-color--e086a3, #E086A3);
}

.x_wna8b6t {
  stop-color: var(--svg-color--dd8b63, #DD8B63);
  stop-opacity: 0;
}

.x-50qsb-j {
  stop-color: var(--svg-color--9e999f, #9E999F);
}

.x0rhptc7w {
  stop-color: var(--svg-color--a26160, #A26160);
}

.yaddi-bgh {
  stop-color: var(--svg-color--9f5a57, #9F5A57);
}

.ym6ziioow {
  stop-color: var(--svg-color--eb947f, #EB947F);
}

.yymlc5b6t {
  stop-color: var(--svg-color--e79196, #E79196);
}

.z1fqdib6i {
  stop-color: var(--svg-color--b94d0b, #B94D0B);
}

.z94p-_exj {
  stop-color: var(--svg-color--e0b7a0, #E0B7A0);
  stop-opacity: 0;
}

.zn4my7bbd {
  d: path("m17.818 20.62l-5.632 3.042a.69.69 0 1 0 .66 1.212l5.062-2.772a2 2 0 0 1 1.624-.132l9.097 3.2v-4.91h-9.385a3 3 0 0 0-1.426.36");
}

.zy_2q-jqi {
  stop-color: var(--svg-color--c8817c, #C8817C);
}

</style>
