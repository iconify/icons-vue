<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iS4Tv9d)"><path fill="url(#iXYbL1b)" class="lx3glwb1b"/><path fill="url(#iYjaR5d)" class="lx3glwb1b"/><path fill="url(#ijfXwpN)" class="lx3glwb1b"/></g><path fill="url(#irUBMEc)" class="r_8lwibym"/><path fill="url(#iBI1Bed)" class="r_8lwibym"/><path fill="url(#iNpH2wb)" class="r_8lwibym"/><rect fill="url(#itb7Poe)" class="q7h9g6bki"/><rect fill="url(#iRjPIcH)" class="q7h9g6bki"/><rect fill="url(#i946NKd)" class="q7h9g6bki"/><path fill="url(#ibq6Lrb)" class="cowi8hvle"/><path fill="url(#ifV653b)" class="cowi8hvle"/><g filter="url(#iAKtZue)"><path stroke="url(#i2ZmQAc)" class="su_j375kk"/></g><g filter="url(#ic0LHFc)"><path fill="url(#iR0iVab)" class="ftokoof_m"/><path fill="url(#igqLGZE)" class="ftokoof_m"/><path fill="url(#icsscub)" class="ftokoof_m"/><path fill="url(#iXXAxBe)" class="ftokoof_m"/></g><path fill="url(#i23phDe)" class="ftokoof_m"/><path fill="url(#iBf9zme)" class="ftokoof_m"/><path fill="url(#iuoz5fd)" class="ri12kgbds"/><path fill="url(#imwvmgb)" class="e4svvibki"/><path fill="url(#ioUTSAe)" class="e4svvibki"/><path fill="url(#iEAt31d)" class="w79k2acia"/><path fill="url(#iZsgCZb)" class="w79k2acia"/><path fill="url(#i83tsoc)" class="w79k2acia"/><path fill="url(#i9L0p6b)" class="n22n_obox"/><g filter="url(#iDnR29c)"><path fill="url(#iZQZulb)" class="zn4my7bbd"/></g><path fill="url(#ilfM8sb)" class="dd0jy3bvw"/><path fill="url(#idPqEla)" class="dd0jy3bvw"/><path fill="url(#ifFZsic)" class="dd0jy3bvw"/><g filter="url(#iKgnHSd)"><path stroke="url(#ih80rUn)" class="henyrkb1a"/></g><defs><linearGradient id="iXYbL1b" x1="12.229" x2="5.3" y1="9.853" y2="21.762" gradientUnits="userSpaceOnUse"><stop class="y2jjn6byj"/><stop offset="1" class="tl5nzpboc"/></linearGradient><linearGradient id="ijfXwpN" x1="3.702" x2="4.555" y1="16.743" y2="17.283" gradientUnits="userSpaceOnUse"><stop class="gxadmabbx"/><stop offset="1" class="qysgrwbxe"/></linearGradient><linearGradient id="irUBMEc" x1="16.529" x2="22.193" y1="24.288" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="s5dc3-ban"/><stop offset="1" class="vh-rt8bez"/></linearGradient><linearGradient id="iBI1Bed" x1="30.064" x2="28.992" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="fkacmuq9i"/><stop offset="1" class="av7r-hnha"/></linearGradient><linearGradient id="i2ZmQAc" x1="10.097" x2="18.224" y1="22.631" y2="8.382" gradientUnits="userSpaceOnUse"><stop class="gjt4qpb9s"/><stop offset="1" class="no-oxqbvh"/></linearGradient><linearGradient id="iR0iVab" x1="17.949" x2="28.389" y1="13.474" y2="23.983" gradientUnits="userSpaceOnUse"><stop class="eqox4ubze"/><stop offset="1" class="fss4frbqk"/></linearGradient><linearGradient id="iXXAxBe" x1="24.375" x2="23.375" y1="13.844" y2="15.781" gradientUnits="userSpaceOnUse"><stop class="p9utle1sv"/><stop offset="1" class="rtekxutof"/></linearGradient><linearGradient id="i23phDe" x1="23.814" x2="22.001" y1="14.125" y2="17.875" gradientUnits="userSpaceOnUse"><stop class="g8y54dbuj"/><stop offset="1" class="ov2d-rbnh"/></linearGradient><linearGradient id="iBf9zme" x1="30.376" x2="27.814" y1="21.188" y2="21.188" gradientUnits="userSpaceOnUse"><stop class="g8y54dbuj"/><stop offset="1" class="ov2d-rbnh"/></linearGradient><linearGradient id="imwvmgb" x1="16.345" x2="19.525" y1="5.063" y2="6.501" gradientUnits="userSpaceOnUse"><stop class="x-50qsb-j"/><stop offset="1" class="man8xwalw"/></linearGradient><linearGradient id="ioUTSAe" x1="20.896" x2="19.969" y1="7.453" y2="6.875" gradientUnits="userSpaceOnUse"><stop class="si_znv48i"/><stop offset="1" class="bf59mn5sh"/><stop offset="1" class="cl7hn_59i"/></linearGradient><linearGradient id="iEAt31d" x1="4.939" x2="6.215" y1="27.964" y2="28.351" gradientUnits="userSpaceOnUse"><stop class="p557anbfl"/><stop offset="1" class="yymlc5b6t"/></linearGradient><linearGradient id="iZsgCZb" x1="7.69" x2="6.257" y1="29.509" y2="28.682" gradientUnits="userSpaceOnUse"><stop class="wzqb9gbrp"/><stop offset="1" class="cnr5izb-c"/></linearGradient><linearGradient id="i83tsoc" x1="6.531" x2="6.353" y1="27.031" y2="27.32" gradientUnits="userSpaceOnUse"><stop class="ym6ziioow"/><stop offset="1" class="tys9rybzz"/></linearGradient><linearGradient id="i9L0p6b" x1="4.942" x2="5.44" y1="29.424" y2="29.824" gradientUnits="userSpaceOnUse"><stop class="w4zixqbms"/><stop offset="1" class="wq3kgrbvi"/><stop offset="1" class="eo-bkb0sn"/></linearGradient><linearGradient id="iZQZulb" x1="14.855" x2="31.23" y1="22.715" y2="23.25" gradientUnits="userSpaceOnUse"><stop class="u-zsrabbz"/><stop offset="1" class="exnvjpbfr"/></linearGradient><linearGradient id="ilfM8sb" x1="10.564" x2="13.345" y1="19.781" y2="22.65" gradientUnits="userSpaceOnUse"><stop class="dmppjggti"/><stop offset="1" class="s93qowbtm"/></linearGradient><linearGradient id="ih80rUn" x1="21.428" x2="18.719" y1="4.078" y2="2.596" gradientUnits="userSpaceOnUse"><stop class="toj8k1b6u"/><stop offset=".339" class="k1mtvqaqb"/><stop offset="1" class="toj8k1b6u"/></linearGradient><radialGradient id="iYjaR5d" cx="0" cy="0" r="1" gradientTransform="rotate(151.144 5.93 6.87)scale(2.4229 2.39271)" gradientUnits="userSpaceOnUse"><stop class="u3j0zcffd"/><stop offset="1" class="yzfufx_or"/><stop offset="1" class="pl-74t4bu"/></radialGradient><radialGradient id="iNpH2wb" cx="0" cy="0" r="1" gradientTransform="matrix(1.10752 -.52992 1.23905 2.58958 14.502 26.291)" gradientUnits="userSpaceOnUse"><stop class="j95o_qbbw"/><stop offset="1" class="n0w9m93ow"/></radialGradient><radialGradient id="itb7Poe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.38708 3.92266 -4.72646 -2.87622 14.026 25.954)" gradientUnits="userSpaceOnUse"><stop class="nv1ltbkif"/><stop offset="1" class="qafkwysiq"/></radialGradient><radialGradient id="iRjPIcH" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.4973 -3.95465 0 12.349 25.55)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="wu5c56bgy"/><stop offset="1" class="c1ya-0b9c"/></radialGradient><radialGradient id="i946NKd" cx="0" cy="0" r="1" gradientTransform="matrix(2.0274 0 0 3.9567 9.676 27.262)" gradientUnits="userSpaceOnUse"><stop class="p8n82wb4d"/><stop offset="1" class="u-z91lbht"/></radialGradient><radialGradient id="ibq6Lrb" cx="0" cy="0" r="1" gradientTransform="matrix(9.03508 -16.18294 6.82694 3.81154 9.78 21.496)" gradientUnits="userSpaceOnUse"><stop class="unnkx0b5i"/><stop offset="1" class="p-rdzgbpt"/></radialGradient><radialGradient id="ifV653b" cx="0" cy="0" r="1" gradientTransform="matrix(2.78125 -4.4375 3.06055 1.91824 12.442 21.745)" gradientUnits="userSpaceOnUse"><stop class="z1fqdib6i"/><stop offset="1" class="qo3lb7hwm"/></radialGradient><radialGradient id="igqLGZE" cx="0" cy="0" r="1" gradientTransform="matrix(-6.99141 -6.95223 4.42821 -4.45317 22.776 30.354)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="v3_85qbzf"/><stop offset="1" class="y-vqgbrgt"/></radialGradient><radialGradient id="icsscub" cx="0" cy="0" r="1" gradientTransform="rotate(149.931 11.96 13)scale(5.17395 1.57367)" gradientUnits="userSpaceOnUse"><stop class="xww5wh4hk"/><stop offset="1" class="xnyo3n3mk"/></radialGradient><radialGradient id="iuoz5fd" cx="0" cy="0" r="1" gradientTransform="rotate(-45.605 30.782 -5.494)scale(7.31574 8.64406)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="ecvqtciyi"/><stop offset=".561" class="nvso99rmu"/><stop offset="1" class="abccfub_s"/></radialGradient><radialGradient id="idPqEla" cx="0" cy="0" r="1" gradientTransform="matrix(3.73694 -2.5625 3.33108 4.85777 8.67 25.969)" gradientUnits="userSpaceOnUse"><stop class="wa1xjvnqe"/><stop offset="1" class="xi48ykl2h"/></radialGradient><radialGradient id="ifFZsic" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 -1.6875 2.0981 1.9427 12.031 28.031)" gradientUnits="userSpaceOnUse"><stop class="i0-yftyki"/><stop offset=".978" class="eg22wvirx"/><stop offset="1" class="ucd5rachp"/></radialGradient><filter id="iS4Tv9d" width="15.189" height="15.507" x="1.78" y="7.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.207843 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6335"/></filter><filter id="iAKtZue" width="12.051" height="18.937" x="6.69" y="6.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6335" stdDeviation=".5"/></filter><filter id="ic0LHFc" width="21.213" height="16.921" x="8.671" y="11.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.396078 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6335"/></filter><filter id="iDnR29c" width="20.805" height="8.91" x="9.824" y="18.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6335" stdDeviation="1"/></filter><filter id="iKgnHSd" width="3.598" height="2.487" x="18.344" y="2.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6335" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:writing-hand-medium" /></template>
<style>
.abccfub_s {
  stop-color: var(--svg-color--7d4544, #7D4544);
  stop-opacity: 0;
}

.av7r-hnha {
  stop-color: var(--svg-color--9d807a, #9D807A);
  stop-opacity: 0;
}

.bf59mn5sh {
  stop-color: var(--svg-color--d4c5de, #D4C5DE);
  stop-opacity: 0;
}

.c1ya-0b9c {
  stop-color: var(--svg-color--985785, #985785);
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

.dd0jy3bvw {
  d: path("m13.118 19.936l1.758-1.103a5.25 5.25 0 0 1 3.498-.757l1.468.2l-1.939 6.723l-.01-.016a.91.91 0 0 0-1.263-.313l-3.53 2.173c-1.33.82-3.169.432-4.005-.89c-.815-1.289-.413-3.048.838-3.922l3.178-2.082z");
}

.dmppjggti {
  stop-color: var(--svg-color--b0613a, #B0613A);
}

.e4svvibki {
  d: path("m16 5.995l1.073-1.869l3.823 2.225l-1.07 1.87z");
}

.ecvqtciyi {
  stop-color: var(--svg-color--8d5b5d, #8D5B5D);
}

.eg22wvirx {
  stop-color: var(--svg-color--793e64, #793E64);
  stop-opacity: 0;
}

.eo-bkb0sn {
  stop-color: var(--svg-color--3f0c46, #3F0C46);
}

.eqox4ubze {
  stop-color: var(--svg-color--c4977c, #C4977C);
}

.exnvjpbfr {
  stop-color: var(--svg-color--d4afa2, #D4AFA2);
}

.fkacmuq9i {
  stop-color: var(--svg-color--9d807a, #9D807A);
}

.fss4frbqk {
  stop-color: var(--svg-color--ca9e85, #CA9E85);
}

.ft5dv1b6b {
  fill: none;
}

.ftokoof_m {
  d: path("M9.933 22.03c-1.251.875-1.653 2.634-.838 3.924c.836 1.321 2.674 1.709 4.005.89l3.53-2.174a.91.91 0 0 1 1.263.313a6.84 6.84 0 0 0 6.588 3.321l3.832-.394a1.75 1.75 0 0 0 1.57-1.741v-7.13a2.81 2.81 0 0 0-1.736-2.585c-2.227-.928-6.282-2.689-10.295-4.785l-4.741 8.28z");
}

.g8y54dbuj {
  stop-color: var(--svg-color--c29a7c, #C29A7C);
}

.gjt4qpb9s {
  stop-color: var(--svg-color--e98d53, #E98D53);
}

.gxadmabbx {
  stop-color: var(--svg-color--977866, #977866);
}

.henyrkb1a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m18.719 2.503l2.848 1.737");
}

.i0-yftyki {
  stop-color: var(--svg-color--98577d, #98577D);
}

.j95o_qbbw {
  stop-color: var(--svg-color--704149, #704149);
}

.k1mtvqaqb {
  stop-color: var(--svg-color--ff756d, #FF756D);
}

.lx3glwb1b {
  d: path("M7.457 11.257a5 5 0 0 1 6.632-1.75l2.88 1.565l-4.305 7.08l-1.415-3.54l-4.317 7.519a2.535 2.535 0 0 1-3.49.922l-.116-.069a2.535 2.535 0 0 1-.88-3.494l3.62-5.986l-.005-.004l.28-.451l.584-.964c.17-.283.338-.556.532-.828");
}

.man8xwalw {
  stop-color: var(--svg-color--d9ccec, #D9CCEC);
}

.n0w9m93ow {
  stop-color: var(--svg-color--704149, #704149);
  stop-opacity: 0;
}

.n22n_obox {
  d: path("m5.859 29.488l-.817.405c-.162.08-.298 0-.306-.18l-.058-.906z");
}

.no-oxqbvh {
  stop-color: var(--svg-color--e98d53, #E98D53);
  stop-opacity: 0;
}

.nv1ltbkif {
  stop-color: var(--svg-color--6f3c48, #6F3C48);
}

.nvso99rmu {
  stop-color: var(--svg-color--7d4544, #7D4544);
}

.ov2d-rbnh {
  stop-color: var(--svg-color--c29a7c, #C29A7C);
  stop-opacity: 0;
}

.p-rdzgbpt {
  stop-color: var(--svg-color--f14e4b, #F14E4B);
}

.p557anbfl {
  stop-color: var(--svg-color--ce8c7f, #CE8C7F);
}

.p8n82wb4d {
  stop-color: var(--svg-color--9b6f66, #9B6F66);
}

.p9utle1sv {
  stop-color: var(--svg-color--be9c82, #BE9C82);
}

.pl-74t4bu {
  stop-color: var(--svg-color--835c49, #835C49);
  stop-opacity: 0;
}

.q7h9g6bki {
  width: 4.832px;
  height: 6.985px;
  x: 9.933px;
  y: 22.892px;
  rx: 2.416px;
}

.qafkwysiq {
  stop-color: var(--svg-color--8b5961, #8B5961);
}

.qo3lb7hwm {
  stop-color: var(--svg-color--b94d0b, #B94D0B);
  stop-opacity: 0;
}

.qysgrwbxe {
  stop-color: var(--svg-color--977866, #977866);
  stop-opacity: 0;
}

.r_8lwibym {
  d: path("m15.173 27.116l-.671-1.724l1.352-1.986h14.03v4.579a2 2 0 0 1-2 2h-8.517a4.5 4.5 0 0 1-4.194-2.869");
}

.ri12kgbds {
  d: path("m16.925 13.287l-3.807 6.65l1.758-1.104a5.25 5.25 0 0 1 3.498-.757l2.431.33z");
}

.rtekxutof {
  stop-color: var(--svg-color--be9c82, #BE9C82);
  stop-opacity: 0;
}

.s5dc3-ban {
  stop-color: var(--svg-color--8d595f, #8D595F);
}

.s93qowbtm {
  stop-color: var(--svg-color--b0613a, #B0613A);
  stop-opacity: 0;
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.su_j375kk {
  stroke-linecap: round;
  d: path("M17.241 8.382L8.19 24.319");
}

.tl5nzpboc {
  stop-color: var(--svg-color--98605f, #98605F);
}

.toj8k1b6u {
  stop-color: var(--svg-color--ff756d, #FF756D);
  stop-opacity: 0;
}

.tys9rybzz {
  stop-color: var(--svg-color--eb947f, #EB947F);
  stop-opacity: 0;
}

.u-z91lbht {
  stop-color: var(--svg-color--9b6f66, #9B6F66);
  stop-opacity: 0;
}

.u-zsrabbz {
  stop-color: var(--svg-color--cea393, #CEA393);
}

.u3j0zcffd {
  stop-color: var(--svg-color--835c49, #835C49);
}

.ucd5rachp {
  stop-color: var(--svg-color--98577d, #98577D);
  stop-opacity: 0;
}

.unnkx0b5i {
  stop-color: var(--svg-color--da7838, #DA7838);
}

.v3_85qbzf {
  stop-color: var(--svg-color--95547a, #95547A);
}

.vh-rt8bez {
  stop-color: var(--svg-color--9e6192, #9E6192);
}

.w4zixqbms {
  stop-color: var(--svg-color--3b1a3b, #3B1A3B);
}

.w79k2acia {
  d: path("M8.386 28.182a.5.5 0 0 1-.168.136l-3.176 1.575c-.162.08-.298 0-.306-.18l-.226-3.541a.5.5 0 0 1 .02-.169z");
}

.wa1xjvnqe {
  stop-color: var(--svg-color--8f5a6b, #8F5A6B);
}

.wq3kgrbvi {
  stop-color: var(--svg-color--5a1870, #5A1870);
}

.wu5c56bgy {
  stop-color: var(--svg-color--985785, #985785);
  stop-opacity: 0;
}

.wzqb9gbrp {
  stop-color: var(--svg-color--e086a3, #E086A3);
}

.x-50qsb-j {
  stop-color: var(--svg-color--9e999f, #9E999F);
}

.xi48ykl2h {
  stop-color: var(--svg-color--8f5a6b, #8F5A6B);
  stop-opacity: 0;
}

.xnyo3n3mk {
  stop-color: var(--svg-color--d1a98d, #D1A98D);
  stop-opacity: 0;
}

.xww5wh4hk {
  stop-color: var(--svg-color--d1a98d, #D1A98D);
}

.y-vqgbrgt {
  stop-color: var(--svg-color--95547a, #95547A);
  stop-opacity: 0;
}

.y2jjn6byj {
  stop-color: var(--svg-color--a37e67, #A37E67);
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

.zn4my7bbd {
  d: path("m17.818 20.62l-5.632 3.042a.69.69 0 1 0 .66 1.212l5.062-2.772a2 2 0 0 1 1.624-.132l9.097 3.2v-4.91h-9.385a3 3 0 0 0-1.426.36");
}

</style>
