<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iccPS6u)"><path class="c0r8clb0n"/><path fill="url(#id9dmle)" class="hcn2ui65h"/><path fill="url(#ivEeq0d)" class="hcn2ui65h"/></g><path fill="url(#iQS4qte)" class="q5naa1bek"/><g filter="url(#iKIZvcd)"><path fill="url(#ivTtZEb)" class="a9fvh1mgi"/></g><path fill="url(#i0HuKOc)" class="ms54ti_zu"/><path fill="url(#i44QH4d)" class="ms54ti_zu"/><path fill="url(#iwLpEZb)" class="ms54ti_zu"/><path fill="url(#iI5hmlc)" class="ms54ti_zu"/><path fill="url(#iPD8hEd)" class="ms54ti_zu"/><g filter="url(#iVZBDkt)"><path class="smm0qgb9k"/></g><path fill="url(#iFosBwb)" class="a968q_bev"/><path fill="url(#iylKHfe)" class="a968q_bev"/><path fill="url(#iwMhFCc)" class="a968q_bev"/><path fill="url(#iBjbQAb)" class="a968q_bev"/><g filter="url(#i4l9xFv)"><path fill="url(#ikO4Oja)" class="ex11pkbkf"/></g><path fill="url(#iBnDohH)" class="vromuxb8f"/><path fill="url(#idw4bgb)" class="vromuxb8f"/><path fill="url(#iwlX2Me)" class="vromuxb8f"/><path fill="url(#ivx9HEd)" class="vromuxb8f"/><g filter="url(#iZC2w5d)"><path fill="url(#i6FzOEI)" class="ved82obog"/></g><path fill="url(#i03LWie)" class="hcn2ui65h"/><path fill="url(#iyzWbFd)" class="hcn2ui65h"/><path fill="url(#i7gluQb)" class="hcn2ui65h"/><path fill="url(#iwjhBWb)" class="hcn2ui65h"/><path fill="url(#ifzN0Ae)" class="hcn2ui65h"/><path fill="url(#iM83kkd)" class="hcn2ui65h"/><g filter="url(#iLx1eAf)"><path fill="url(#itFHLde)" class="dwbovs-mq"/></g><path fill="url(#i4Wdrhe)" class="tx4xrfj_p"/><path fill="url(#iFLoxFd)" class="tx4xrfj_p"/><path fill="url(#iszcPyb)" class="tx4xrfj_p"/><g filter="url(#i7l45oc)"><path fill="url(#izjtPxd)" class="feef1vb2f"/></g><defs><linearGradient id="ivTtZEb" x1="6.013" x2="10.321" y1="13.586" y2="20.376" gradientUnits="userSpaceOnUse"><stop class="h23j5l7wg"/><stop offset="1" class="iqtd7_e4j"/></linearGradient><linearGradient id="i0HuKOc" x1="8.639" x2="10.689" y1="11.845" y2="11.733" gradientUnits="userSpaceOnUse"><stop class="a61ui5bws"/><stop offset="1" class="i7h39qb_i"/></linearGradient><linearGradient id="i44QH4d" x1="13.663" x2="12.679" y1="11.061" y2="11.076" gradientUnits="userSpaceOnUse"><stop class="ecqussste"/><stop offset="1" class="oi3x9iuvd"/></linearGradient><linearGradient id="iI5hmlc" x1="11.11" x2="10.492" y1="16.779" y2="14.779" gradientUnits="userSpaceOnUse"><stop offset=".236" class="qj6gmdbak"/><stop offset="1" class="fqq1wfb3b"/></linearGradient><linearGradient id="iFosBwb" x1="12.335" x2="15.414" y1="9.889" y2="9.836" gradientUnits="userSpaceOnUse"><stop class="t5m624b_w"/><stop offset="1" class="c38bebani"/></linearGradient><linearGradient id="iwMhFCc" x1="18.517" x2="17.31" y1="9.515" y2="9.515" gradientUnits="userSpaceOnUse"><stop class="xtkuzf2ei"/><stop offset="1" class="eizovsb1f"/></linearGradient><linearGradient id="iBjbQAb" x1="14.867" x2="15.071" y1="17.076" y2="14.145" gradientUnits="userSpaceOnUse"><stop class="qj6gmdbak"/><stop offset="1" class="fqq1wfb3b"/></linearGradient><linearGradient id="ikO4Oja" x1="17.17" x2="25.801" y1="2.156" y2="8.318" gradientUnits="userSpaceOnUse"><stop class="icjbfbcsz"/><stop offset="1" class="l9j77zbpn"/></linearGradient><linearGradient id="iBnDohH" x1="17.238" x2="20.022" y1="10.823" y2="10.771" gradientUnits="userSpaceOnUse"><stop class="lf7vr6vni"/><stop offset="1" class="a1pfh5noq"/></linearGradient><linearGradient id="idw4bgb" x1="23.152" x2="21.68" y1="10.851" y2="10.861" gradientUnits="userSpaceOnUse"><stop class="r8e3pjzpw"/><stop offset="1" class="kpujw3iqu"/></linearGradient><linearGradient id="iwlX2Me" x1="19.054" x2="19.583" y1="15.889" y2="13.15" gradientUnits="userSpaceOnUse"><stop class="qj6gmdbak"/><stop offset="1" class="fqq1wfb3b"/></linearGradient><linearGradient id="i6FzOEI" x1="21.444" x2="21.444" y1="5.451" y2="19.014" gradientUnits="userSpaceOnUse"><stop class="chfuwtbnr"/><stop offset="1" class="kr0fi1udo"/></linearGradient><linearGradient id="i03LWie" x1="26.953" x2="21.599" y1="22.599" y2="22.599" gradientUnits="userSpaceOnUse"><stop class="lbtd6zbkm"/><stop offset="1" class="ubibb2bhq"/></linearGradient><linearGradient id="itFHLde" x1="26.794" x2="23.825" y1="16.131" y2="16.025" gradientUnits="userSpaceOnUse"><stop class="l_r-rkb0i"/><stop offset="1" class="prsh4r1dj"/></linearGradient><linearGradient id="i4Wdrhe" x1="21.325" x2="23.651" y1="12.609" y2="12.855" gradientUnits="userSpaceOnUse"><stop class="oi7g8dknq"/><stop offset="1" class="le_j5cb3p"/></linearGradient><linearGradient id="iFLoxFd" x1="23.968" x2="24.158" y1="16.951" y2="13.458" gradientUnits="userSpaceOnUse"><stop class="yvwph9bfk"/><stop offset="1" class="dl3-s1bsu"/></linearGradient><linearGradient id="izjtPxd" x1="25.624" x2="25.376" y1="8.524" y2="22.084" gradientUnits="userSpaceOnUse"><stop class="zw1k0-prr"/><stop offset="1" class="g6mty-b8t"/></linearGradient><radialGradient id="id9dmle" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 -2.625 9.42008 18.39159 9.085 27.076)" gradientUnits="userSpaceOnUse"><stop class="h1sgtxtqh"/><stop offset="1" class="uo_inwq3m"/></radialGradient><radialGradient id="ivEeq0d" cx="0" cy="0" r="1" gradientTransform="matrix(.4595 2.43885 -3.85022 .7254 5.483 12.077)" gradientUnits="userSpaceOnUse"><stop class="aflb6lbgt"/><stop offset="1" class="l02kk_bos"/></radialGradient><radialGradient id="iQS4qte" cx="0" cy="0" r="1" gradientTransform="rotate(146.31 2.532 9.166)scale(1.33802 3.89834)" gradientUnits="userSpaceOnUse"><stop class="h41yutqjs"/><stop offset="1" class="uxe06abat"/></radialGradient><radialGradient id="iwLpEZb" cx="0" cy="0" r="1" gradientTransform="rotate(157.319 6.24 3.957)scale(1.13462 1.78724)" gradientUnits="userSpaceOnUse"><stop class="z_uwteb1p"/><stop offset="1" class="zaw1ewbji"/></radialGradient><radialGradient id="iPD8hEd" cx="0" cy="0" r="1" gradientTransform="matrix(1.14882 2.36578 -4.48154 2.17624 9.961 4.036)" gradientUnits="userSpaceOnUse"><stop class="eenwi56gr"/><stop offset="1" class="xaai3vbav"/></radialGradient><radialGradient id="iylKHfe" cx="0" cy="0" r="1" gradientTransform="matrix(1.14425 2.08638 -4.22794 2.31876 14.241 2.017)" gradientUnits="userSpaceOnUse"><stop class="a94a7rh-y"/><stop offset="1" class="zshydrbec"/></radialGradient><radialGradient id="ivx9HEd" cx="0" cy="0" r="1" gradientTransform="matrix(.79135 1.354 -2.12907 1.24435 18.962 4.25)" gradientUnits="userSpaceOnUse"><stop class="w14svvb0t"/><stop offset="1" class="qyy62abgt"/></radialGradient><radialGradient id="iyzWbFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 -2.2675 1.77572 -.14684 12.304 16)" gradientUnits="userSpaceOnUse"><stop class="kw5vl0jtb"/><stop offset="1" class="p0p4x4g6v"/></radialGradient><radialGradient id="i7gluQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.09377 -2.17374 2.00449 -.08647 17.023 16)" gradientUnits="userSpaceOnUse"><stop class="kw5vl0jtb"/><stop offset="1" class="p0p4x4g6v"/></radialGradient><radialGradient id="iwjhBWb" cx="0" cy="0" r="1" gradientTransform="rotate(-91.909 18.3 -1.99)scale(1.87604)" gradientUnits="userSpaceOnUse"><stop class="kw5vl0jtb"/><stop offset="1" class="p0p4x4g6v"/></radialGradient><radialGradient id="ifzN0Ae" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 -1.06245 1.39986 -2.79985 24.43 16.483)" gradientUnits="userSpaceOnUse"><stop class="kw5vl0jtb"/><stop offset="1" class="p0p4x4g6v"/></radialGradient><radialGradient id="iM83kkd" cx="0" cy="0" r="1" gradientTransform="rotate(-27.758 49.569 -5.065)scale(3.03562 12.0503)" gradientUnits="userSpaceOnUse"><stop class="dogyjmbix"/><stop offset="1" class="h1t291b3h"/></radialGradient><radialGradient id="iszcPyb" cx="0" cy="0" r="1" gradientTransform="matrix(.84085 1.7617 -4.7063 2.2463 23.023 6.639)" gradientUnits="userSpaceOnUse"><stop class="w-t4tqbjy"/><stop offset="1" class="holmj9bgg"/></radialGradient><filter id="iccPS6u" width="23.039" height="28.965" x="3.528" y="1.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.454902 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1255"/></filter><filter id="iKIZvcd" width="5.458" height="7.823" x="4.512" y="12.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1255" stdDeviation=".375"/></filter><filter id="iVZBDkt" width="3.414" height="12.102" x="10.32" y="4.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1255" stdDeviation=".5"/></filter><filter id="i4l9xFv" width="4.064" height="15.808" x="14.453" y="1.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1255" stdDeviation=".5"/></filter><filter id="iZC2w5d" width="3.555" height="13.094" x="19.233" y="4.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1255" stdDeviation=".5"/></filter><filter id="iLx1eAf" width="6.11" height="21.827" x="21.076" y="6.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1255" stdDeviation=".5"/></filter><filter id="i7l45oc" width="3.521" height="13.092" x="23.389" y="7.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1255" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:raised-back-of-hand-medium-light" /></template>
<style>
.a1pfh5noq {
  stop-color: var(--svg-color--d89671, #D89671);
  stop-opacity: 0;
}

.a61ui5bws {
  stop-color: var(--svg-color--bd8465, #BD8465);
}

.a94a7rh-y {
  stop-color: var(--svg-color--c79a78, #C79A78);
}

.a968q_bev {
  d: path("m18.04 5.298l-.002.002l-.026-.945a2.406 2.406 0 0 0-4.81-.022l.009.455l.012.447l-.005-.008l.172 12.6h4.688z");
}

.a9fvh1mgi {
  d: path("M9.22 16.317v3.101l-3.761-4.823a.93.93 0 0 1 1.457-1.152z");
}

.aflb6lbgt {
  stop-color: var(--svg-color--c99f80, #C99F80);
}

.c0r8clb0n {
  fill: var(--svg-color--e7ad97, #E7AD97);
  d: path("M13.202 4.49a2.406 2.406 0 0 1 4.81-.135l.026.945a2.406 2.406 0 0 1 4.393 1.4l-.026 1.37a2.406 2.406 0 0 1 4.16 1.736l-.335 8.822c-.005 1.33-.15 3.695-1.004 5.76c-1.207 3.267-4.34 5.595-8.016 5.595c-3.715 0-6.876-2.379-8.054-5.701c-.889-2.11-2.362-4.283-2.987-5.206l-.04-.06l-2.1-2.82a2.536 2.536 0 0 1 4.05-3.054l1.089 1.424l-.344-7.953a2.385 2.385 0 0 1 4.4-1.378z");
}

.c38bebani {
  stop-color: var(--svg-color--c68869, #C68869);
  stop-opacity: 0;
}

.chfuwtbnr {
  stop-color: var(--svg-color--fcc9a8, #FCC9A8);
}

.dl3-s1bsu {
  stop-color: var(--svg-color--efba9a, #EFBA9A);
  stop-opacity: 0;
}

.dogyjmbix {
  stop-color: var(--svg-color--c88c7e, #C88C7E);
}

.dwbovs-mq {
  d: path("M25.787 20.014c-.17 3.648-1.909 6.402-3.711 7.568l1.882-19.827c2.014 0 2.252 1.511 2.226 2.452c-.053 1.961-.228 6.16-.397 9.807");
}

.ecqussste {
  stop-color: var(--svg-color--cc8e6e, #CC8E6E);
}

.eenwi56gr {
  stop-color: var(--svg-color--c89d7c, #C89D7C);
}

.eizovsb1f {
  stop-color: var(--svg-color--db9b77, #DB9B77);
  stop-opacity: 0;
}

.ex11pkbkf {
  d: path("M15.952 5.196c0-.302-.062-.58-.187-.81c-.209-.38-.43-.855-.24-1.244c.153-.311.51-.487.82-.33c1.065.542 1.196 1.67 1.169 2.384v10.593a.77.77 0 0 1-.773.773a.776.776 0 0 1-.775-.788c.048-3.493-.014-9.664-.014-10.578");
}

.feef1vb2f {
  d: path("M25.248 8.517a.673.673 0 0 0-.688.664c-.026 2.142-.092 7.103-.17 9.627c-.014.433.282.794.659.8c.37.007.677-.333.684-.76l.177-9.644a.675.675 0 0 0-.663-.687");
}

.fqq1wfb3b {
  stop-color: var(--svg-color--e7ad97, #E7AD97);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g6mty-b8t {
  stop-color: var(--svg-color--fecea7, #FECEA7);
  stop-opacity: 0;
}

.h1sgtxtqh {
  stop-color: var(--svg-color--c98f80, #C98F80);
}

.h1t291b3h {
  stop-color: var(--svg-color--c88c7e, #C88C7E);
  stop-opacity: 0;
}

.h23j5l7wg {
  stop-color: var(--svg-color--eeb99a, #EEB99A);
}

.h41yutqjs {
  stop-color: var(--svg-color--a9775c, #A9775C);
}

.hcn2ui65h {
  d: path("M13.202 4.49a2.406 2.406 0 0 1 4.81-.135l.026.945a2.406 2.406 0 0 1 4.393 1.4l-.026 1.37a2.406 2.406 0 0 1 4.16 1.736l-.335 8.822c-.005 1.33-.15 3.695-1.004 5.76c-1.207 3.267-4.34 5.595-8.016 5.595c-3.715 0-6.876-2.379-8.054-5.701c-.889-2.11-2.362-4.283-2.987-5.206l-.04-.06l-2.1-2.82a2.536 2.536 0 0 1 4.05-3.054l1.089 1.424l-.344-7.953a2.385 2.385 0 0 1 4.4-1.378z");
}

.holmj9bgg {
  stop-color: var(--svg-color--ce9e7b, #CE9E7B);
  stop-opacity: 0;
}

.i7h39qb_i {
  stop-color: var(--svg-color--bd8465, #BD8465);
  stop-opacity: 0;
}

.icjbfbcsz {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
}

.iqtd7_e4j {
  stop-color: var(--svg-color--eeb99a, #EEB99A);
  stop-opacity: 0;
}

.kpujw3iqu {
  stop-color: var(--svg-color--e2aa80, #E2AA80);
  stop-opacity: 0;
}

.kr0fi1udo {
  stop-color: var(--svg-color--fcc9a8, #FCC9A8);
  stop-opacity: 0;
}

.kw5vl0jtb {
  stop-color: var(--svg-color--f0b998, #F0B998);
}

.l_r-rkb0i {
  stop-color: var(--svg-color--fdc8a8, #FDC8A8);
}

.l02kk_bos {
  stop-color: var(--svg-color--c99f80, #C99F80);
  stop-opacity: 0;
}

.l9j77zbpn {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
  stop-opacity: 0;
}

.lbtd6zbkm {
  stop-color: var(--svg-color--efbf9c, #EFBF9C);
}

.le_j5cb3p {
  stop-color: var(--svg-color--db9b79, #DB9B79);
  stop-opacity: 0;
}

.lf7vr6vni {
  stop-color: var(--svg-color--d89671, #D89671);
}

.ms54ti_zu {
  d: path("m9.154 14.547l.119 2.78l4.125-1.72L13.22 5.23a2.384 2.384 0 0 0-4.396 1.383l.344 7.953z");
}

.oi3x9iuvd {
  stop-color: var(--svg-color--cc8e6e, #CC8E6E);
  stop-opacity: 0;
}

.oi7g8dknq {
  stop-color: var(--svg-color--db9b79, #DB9B79);
}

.p0p4x4g6v {
  stop-color: var(--svg-color--f0b998, #F0B998);
  stop-opacity: 0;
}

.prsh4r1dj {
  stop-color: var(--svg-color--fdc8a8, #FDC8A8);
  stop-opacity: 0;
}

.q5naa1bek {
  d: path("m4.471 12.708l.079-.06a2.536 2.536 0 0 1 3.53.494l1.084 1.419l.162 4.512z");
}

.qj6gmdbak {
  stop-color: var(--svg-color--e7ad97, #E7AD97);
}

.qyy62abgt {
  stop-color: var(--svg-color--cf9f7b, #CF9F7B);
  stop-opacity: 0;
}

.r8e3pjzpw {
  stop-color: var(--svg-color--e2aa80, #E2AA80);
}

.smm0qgb9k {
  fill: var(--svg-color--ecb99e, #ECB99E);
  d: path("m11.32 6.118l.13 9.484l1.284-.188l-.194-9.317a.61.61 0 0 0-1.22.021");
}

.t5m624b_w {
  stop-color: var(--svg-color--c68869, #C68869);
}

.tx4xrfj_p {
  d: path("m22.415 8.06l-.267 8.548l4.156.343l.261-7.145a2.406 2.406 0 0 0-4.15-1.747");
}

.ubibb2bhq {
  stop-color: var(--svg-color--efbf9c, #EFBF9C);
  stop-opacity: 0;
}

.uo_inwq3m {
  stop-color: var(--svg-color--c98f80, #C98F80);
  stop-opacity: 0;
}

.uxe06abat {
  stop-color: var(--svg-color--a9775c, #A9775C);
  stop-opacity: 0;
}

.ved82obog {
  d: path("M21.01 5.451c-.431 0-.78.35-.777.782c.015 2.195.043 7.039.006 9.523a.776.776 0 0 0 .776.789a.77.77 0 0 0 .772-.772V6.228a.777.777 0 0 0-.777-.777");
}

.vromuxb8f {
  d: path("m18.041 5.295l-.018 12.156h4.187l.197-9.383l-.002.002l.026-1.37a2.406 2.406 0 0 0-4.39-1.405");
}

.w-t4tqbjy {
  stop-color: var(--svg-color--ce9e7b, #CE9E7B);
}

.w14svvb0t {
  stop-color: var(--svg-color--cf9f7b, #CF9F7B);
}

.xaai3vbav {
  stop-color: var(--svg-color--c59878, #C59878);
  stop-opacity: 0;
}

.xtkuzf2ei {
  stop-color: var(--svg-color--db9b77, #DB9B77);
}

.yvwph9bfk {
  stop-color: var(--svg-color--efba9a, #EFBA9A);
}

.z_uwteb1p {
  stop-color: var(--svg-color--ae7956, #AE7956);
}

.zaw1ewbji {
  stop-color: var(--svg-color--ae7956, #AE7956);
  stop-opacity: 0;
}

.zshydrbec {
  stop-color: var(--svg-color--c79a78, #C79A78);
  stop-opacity: 0;
}

.zw1k0-prr {
  stop-color: var(--svg-color--fecea7, #FECEA7);
}

</style>
