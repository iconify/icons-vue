<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iIwZr4c)"><path class="myaverbrx"/><path fill="url(#irOSEbe)" class="fqe7ixbng"/><path fill="url(#iYfmkyd)" class="fqe7ixbng"/></g><path fill="url(#iwhWLdd)" class="la18v8bdt"/><g filter="url(#i8T3Ixc)"><path fill="url(#ieqSpSc)" class="yafcvbc6z"/></g><path fill="url(#iKOI7Fd)" class="oq92pq7ha"/><path fill="url(#inUMoTc)" class="oq92pq7ha"/><path fill="url(#imIAvZG)" class="oq92pq7ha"/><path fill="url(#idIdflb)" class="oq92pq7ha"/><path fill="url(#i9o1tOb)" class="oq92pq7ha"/><g filter="url(#iPHBo8d)"><path class="o-l2tcc9s"/></g><path fill="url(#i3zpXGz)" class="va8v2kriz"/><path fill="url(#iWoLSTb)" class="va8v2kriz"/><path fill="url(#igUyavd)" class="va8v2kriz"/><path fill="url(#i88pkPd)" class="va8v2kriz"/><g filter="url(#iUE5ced)"><path fill="url(#ittZABd)" class="pc_ypn7fw"/></g><path fill="url(#iB7dQOh)" class="jrl5b5bpz"/><path fill="url(#igbG0Zc)" class="jrl5b5bpz"/><path fill="url(#ivm1Q7r)" class="jrl5b5bpz"/><path fill="url(#ikWgRQb)" class="jrl5b5bpz"/><g filter="url(#iYbgDKd)"><path fill="url(#iUMBqZb)" class="ii-m4hu2w"/></g><path fill="url(#iYg6tNc)" class="fqe7ixbng"/><path fill="url(#iVtabYc)" class="fqe7ixbng"/><path fill="url(#i1sCOpd)" class="fqe7ixbng"/><path fill="url(#iQbbIHb)" class="fqe7ixbng"/><path fill="url(#iTBGm5b)" class="fqe7ixbng"/><path fill="url(#iQsmwmb)" class="fqe7ixbng"/><g filter="url(#ipr9qQg)"><path fill="url(#indpRVt)" class="p3kpdx-jh"/></g><path fill="url(#i8SPDCe)" class="t2y--rbpl"/><path fill="url(#ig3OTOC)" class="t2y--rbpl"/><path fill="url(#iQ0w0Dc)" class="t2y--rbpl"/><g filter="url(#irH71pe)"><path fill="url(#iUzo6Kd)" class="e88yeyaxk"/></g><defs><linearGradient id="ieqSpSc" x1="6.372" x2="10.681" y1="13.586" y2="20.376" gradientUnits="userSpaceOnUse"><stop class="y5q2h9u3l"/><stop offset="1" class="h4i43fe5d"/></linearGradient><linearGradient id="iKOI7Fd" x1="8.999" x2="11.049" y1="11.845" y2="11.733" gradientUnits="userSpaceOnUse"><stop class="watd7bysj"/><stop offset="1" class="x0acfmbue"/></linearGradient><linearGradient id="inUMoTc" x1="14.023" x2="13.039" y1="11.061" y2="11.076" gradientUnits="userSpaceOnUse"><stop class="p0gxu-byn"/><stop offset="1" class="amv1ddc3a"/></linearGradient><linearGradient id="idIdflb" x1="11.47" x2="10.851" y1="16.779" y2="14.779" gradientUnits="userSpaceOnUse"><stop offset=".236" class="lyot_fbwv"/><stop offset="1" class="d95nnob8o"/></linearGradient><linearGradient id="i3zpXGz" x1="12.695" x2="15.774" y1="9.889" y2="9.836" gradientUnits="userSpaceOnUse"><stop class="bftq_gu9d"/><stop offset="1" class="ygn_swb3b"/></linearGradient><linearGradient id="igUyavd" x1="18.877" x2="17.669" y1="9.515" y2="9.515" gradientUnits="userSpaceOnUse"><stop class="pa7rlh4ga"/><stop offset="1" class="toh0blbdh"/></linearGradient><linearGradient id="i88pkPd" x1="15.226" x2="15.431" y1="17.076" y2="14.145" gradientUnits="userSpaceOnUse"><stop class="lyot_fbwv"/><stop offset="1" class="d95nnob8o"/></linearGradient><linearGradient id="ittZABd" x1="17.53" x2="27.096" y1=".178" y2="7.009" gradientUnits="userSpaceOnUse"><stop class="g73iv-bvy"/><stop offset="1" class="alsobs70x"/></linearGradient><linearGradient id="iB7dQOh" x1="17.598" x2="20.382" y1="10.823" y2="10.771" gradientUnits="userSpaceOnUse"><stop class="cjq0uac_s"/><stop offset="1" class="t4u30fdub"/></linearGradient><linearGradient id="igbG0Zc" x1="23.511" x2="22.04" y1="10.851" y2="10.861" gradientUnits="userSpaceOnUse"><stop class="liqnqtkwv"/><stop offset="1" class="j_6_xlabe"/></linearGradient><linearGradient id="ivm1Q7r" x1="19.414" x2="19.943" y1="15.889" y2="13.15" gradientUnits="userSpaceOnUse"><stop class="lyot_fbwv"/><stop offset="1" class="d95nnob8o"/></linearGradient><linearGradient id="iUMBqZb" x1="21.803" x2="21.803" y1="5.451" y2="19.014" gradientUnits="userSpaceOnUse"><stop class="ztm_gzbze"/><stop offset="1" class="ruy-7mtyv"/></linearGradient><linearGradient id="iYg6tNc" x1="27.313" x2="21.959" y1="22.599" y2="22.599" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="ubibb2bhq"/></linearGradient><linearGradient id="indpRVt" x1="27.154" x2="24.185" y1="16.131" y2="16.025" gradientUnits="userSpaceOnUse"><stop class="m2qxnw_1z"/><stop offset="1" class="xce4m4bva"/></linearGradient><linearGradient id="i8SPDCe" x1="21.684" x2="24.011" y1="12.609" y2="12.855" gradientUnits="userSpaceOnUse"><stop class="tax34cc_t"/><stop offset="1" class="y36ypgcnp"/></linearGradient><linearGradient id="ig3OTOC" x1="24.328" x2="24.517" y1="16.951" y2="13.458" gradientUnits="userSpaceOnUse"><stop class="ypyl71b0u"/><stop offset="1" class="dl3-s1bsu"/></linearGradient><linearGradient id="iUzo6Kd" x1="25.984" x2="25.735" y1="8.524" y2="22.084" gradientUnits="userSpaceOnUse"><stop class="j3x50rbgd"/><stop offset="1" class="vybx3-bqw"/></linearGradient><radialGradient id="irOSEbe" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 -2.625 9.42008 18.39159 9.445 27.076)" gradientUnits="userSpaceOnUse"><stop class="pty4jtb4p"/><stop offset="1" class="hwxb5d_9d"/></radialGradient><radialGradient id="iYfmkyd" cx="0" cy="0" r="1" gradientTransform="matrix(.4595 2.43885 -3.85022 .7254 5.843 12.077)" gradientUnits="userSpaceOnUse"><stop class="vvabwacyo"/><stop offset="1" class="b3q492gve"/></radialGradient><radialGradient id="iwhWLdd" cx="0" cy="0" r="1" gradientTransform="rotate(146.31 2.712 9.22)scale(1.33802 3.89834)" gradientUnits="userSpaceOnUse"><stop class="dgkitw09n"/><stop offset="1" class="xouzk_bmd"/></radialGradient><radialGradient id="imIAvZG" cx="0" cy="0" r="1" gradientTransform="rotate(157.319 6.42 3.993)scale(1.13462 1.78724)" gradientUnits="userSpaceOnUse"><stop class="aw2urnbyz"/><stop offset="1" class="ytovt-b_k"/></radialGradient><radialGradient id="i9o1tOb" cx="0" cy="0" r="1" gradientTransform="matrix(1.14882 2.36578 -4.48154 2.17624 10.32 4.036)" gradientUnits="userSpaceOnUse"><stop class="na5i0acdf"/><stop offset="1" class="tpk1djbrc"/></radialGradient><radialGradient id="iWoLSTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.14425 2.08638 -4.22794 2.31876 14.602 2.018)" gradientUnits="userSpaceOnUse"><stop class="ohs1s4bqc"/><stop offset="1" class="eiy6wfbug"/></radialGradient><radialGradient id="ikWgRQb" cx="0" cy="0" r="1" gradientTransform="matrix(.79135 1.354 -2.12907 1.24435 19.322 4.25)" gradientUnits="userSpaceOnUse"><stop class="ggalksyuq"/><stop offset="1" class="qkgve9byl"/></radialGradient><radialGradient id="iVtabYc" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 -2.2675 1.77572 -.14684 12.664 16)" gradientUnits="userSpaceOnUse"><stop class="twl_i-b2r"/><stop offset="1" class="jofbdab8p"/></radialGradient><radialGradient id="i1sCOpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.09377 -2.17374 2.00449 -.08647 17.383 16)" gradientUnits="userSpaceOnUse"><stop class="twl_i-b2r"/><stop offset="1" class="jofbdab8p"/></radialGradient><radialGradient id="iQbbIHb" cx="0" cy="0" r="1" gradientTransform="rotate(-91.909 18.479 -2.164)scale(1.87604)" gradientUnits="userSpaceOnUse"><stop class="twl_i-b2r"/><stop offset="1" class="jofbdab8p"/></radialGradient><radialGradient id="iTBGm5b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 -1.06245 1.39986 -2.79985 24.789 16.484)" gradientUnits="userSpaceOnUse"><stop class="twl_i-b2r"/><stop offset="1" class="jofbdab8p"/></radialGradient><radialGradient id="iQsmwmb" cx="0" cy="0" r="1" gradientTransform="rotate(-27.758 49.749 -5.793)scale(3.03562 12.0503)" gradientUnits="userSpaceOnUse"><stop class="m6-hzbe_o"/><stop offset="1" class="nxfhb4lzv"/></radialGradient><radialGradient id="iQ0w0Dc" cx="0" cy="0" r="1" gradientTransform="matrix(.84085 1.7617 -4.7063 2.2463 23.383 6.639)" gradientUnits="userSpaceOnUse"><stop class="frr5f9b7s"/><stop offset="1" class="uy7s3ts9t"/></radialGradient><filter id="iIwZr4c" width="23.039" height="28.965" x="3.888" y="1.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.486275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1241"/></filter><filter id="i8T3Ixc" width="5.458" height="7.823" x="4.872" y="12.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1241" stdDeviation=".375"/></filter><filter id="iPHBo8d" width="3.414" height="12.102" x="10.68" y="4.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1241" stdDeviation=".5"/></filter><filter id="iUE5ced" width="4.064" height="15.808" x="14.813" y="1.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1241" stdDeviation=".5"/></filter><filter id="iYbgDKd" width="3.555" height="13.094" x="19.593" y="4.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1241" stdDeviation=".5"/></filter><filter id="ipr9qQg" width="6.11" height="21.827" x="21.436" y="6.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1241" stdDeviation=".5"/></filter><filter id="irH71pe" width="3.521" height="13.092" x="23.749" y="7.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1241" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:raised-back-of-hand-light" /></template>
<style>
.alsobs70x {
  stop-color: var(--svg-color--ffe2c5, #FFE2C5);
  stop-opacity: 0;
}

.amv1ddc3a {
  stop-color: var(--svg-color--d59779, #D59779);
  stop-opacity: 0;
}

.aw2urnbyz {
  stop-color: var(--svg-color--c59074, #C59074);
}

.b3q492gve {
  stop-color: var(--svg-color--ddab8f, #DDAB8F);
  stop-opacity: 0;
}

.bftq_gu9d {
  stop-color: var(--svg-color--d79b80, #D79B80);
}

.cjq0uac_s {
  stop-color: var(--svg-color--f1b094, #F1B094);
}

.d95nnob8o {
  stop-color: var(--svg-color--fbc5b2, #FBC5B2);
  stop-opacity: 0;
}

.dgkitw09n {
  stop-color: var(--svg-color--c2886c, #C2886C);
}

.dl3-s1bsu {
  stop-color: var(--svg-color--efba9a, #EFBA9A);
  stop-opacity: 0;
}

.e88yeyaxk {
  d: path("M25.607 8.517a.673.673 0 0 0-.687.664c-.027 2.142-.092 7.103-.17 9.627c-.014.433.282.794.658.8c.37.007.677-.333.685-.76l.177-9.644a.675.675 0 0 0-.663-.687");
}

.eiy6wfbug {
  stop-color: var(--svg-color--d4a78c, #D4A78C);
  stop-opacity: 0;
}

.fqe7ixbng {
  d: path("M13.562 4.49a2.406 2.406 0 0 1 4.81-.135l.026.945a2.406 2.406 0 0 1 4.393 1.4l-.026 1.37a2.406 2.406 0 0 1 4.16 1.736l-.335 8.822c-.005 1.33-.15 3.695-1.004 5.76c-1.208 3.267-4.34 5.595-8.016 5.595c-3.715 0-6.876-2.379-8.055-5.701c-.888-2.11-2.361-4.283-2.986-5.206l-.041-.06l-2.098-2.82a2.536 2.536 0 0 1 4.05-3.054l1.088 1.424l-.344-7.953a2.385 2.385 0 0 1 4.399-1.378z");
}

.frr5f9b7s {
  stop-color: var(--svg-color--efb896, #EFB896);
}

.ft5dv1b6b {
  fill: none;
}

.g73iv-bvy {
  stop-color: var(--svg-color--ffe2c5, #FFE2C5);
}

.ggalksyuq {
  stop-color: var(--svg-color--e4af90, #E4AF90);
}

.h4i43fe5d {
  stop-color: var(--svg-color--f9cab7, #F9CAB7);
  stop-opacity: 0;
}

.hwxb5d_9d {
  stop-color: var(--svg-color--d59d93, #D59D93);
  stop-opacity: 0;
}

.ii-m4hu2w {
  d: path("M21.37 5.451c-.432 0-.78.35-.777.782c.015 2.195.042 7.039.006 9.523a.776.776 0 0 0 .776.789a.77.77 0 0 0 .772-.772V6.228a.777.777 0 0 0-.777-.777");
}

.j_6_xlabe {
  stop-color: var(--svg-color--ffcdb0, #FFCDB0);
  stop-opacity: 0;
}

.j3x50rbgd {
  stop-color: var(--svg-color--ffe1c5, #FFE1C5);
}

.jofbdab8p {
  stop-color: var(--svg-color--fecbb6, #FECBB6);
  stop-opacity: 0;
}

.jrl5b5bpz {
  d: path("m18.401 5.295l-.018 12.156h4.187l.197-9.383l-.002.002l.026-1.37a2.406 2.406 0 0 0-4.39-1.405");
}

.la18v8bdt {
  d: path("m4.83 12.708l.08-.06a2.536 2.536 0 0 1 3.53.494l1.084 1.419l.162 4.512z");
}

.liqnqtkwv {
  stop-color: var(--svg-color--ffcdb0, #FFCDB0);
}

.lyot_fbwv {
  stop-color: var(--svg-color--fbc5b2, #FBC5B2);
}

.m2qxnw_1z {
  stop-color: var(--svg-color--ffddc3, #FFDDC3);
}

.m6-hzbe_o {
  stop-color: var(--svg-color--d59c93, #D59C93);
}

.myaverbrx {
  fill: var(--svg-color--fbc5b2, #FBC5B2);
  d: path("M13.562 4.49a2.406 2.406 0 0 1 4.81-.135l.026.945a2.406 2.406 0 0 1 4.393 1.4l-.026 1.37a2.406 2.406 0 0 1 4.16 1.736l-.335 8.822c-.005 1.33-.15 3.695-1.004 5.76c-1.208 3.267-4.34 5.595-8.016 5.595c-3.715 0-6.876-2.379-8.055-5.701c-.888-2.11-2.361-4.283-2.986-5.206l-.041-.06l-2.098-2.82a2.536 2.536 0 0 1 4.05-3.054l1.088 1.424l-.344-7.953a2.385 2.385 0 0 1 4.399-1.378z");
}

.na5i0acdf {
  stop-color: var(--svg-color--d8a88d, #D8A88D);
}

.nxfhb4lzv {
  stop-color: var(--svg-color--d59c93, #D59C93);
  stop-opacity: 0;
}

.o-l2tcc9s {
  fill: var(--svg-color--ffd0bb, #FFD0BB);
  d: path("m11.68 6.118l.13 9.484l1.284-.188l-.194-9.317a.61.61 0 0 0-1.22.021");
}

.ohs1s4bqc {
  stop-color: var(--svg-color--d4a78c, #D4A78C);
}

.oq92pq7ha {
  d: path("m9.513 14.547l.12 2.78l4.125-1.72L13.58 5.23a2.384 2.384 0 0 0-4.396 1.383l.344 7.953z");
}

.p0gxu-byn {
  stop-color: var(--svg-color--d59779, #D59779);
}

.p3kpdx-jh {
  d: path("M26.147 20.014c-.17 3.648-1.909 6.402-3.711 7.568l1.882-19.827c2.014 0 2.252 1.511 2.226 2.452c-.053 1.961-.228 6.16-.397 9.807");
}

.pa7rlh4ga {
  stop-color: var(--svg-color--f5b69a, #F5B69A);
}

.pc_ypn7fw {
  d: path("M16.311 5.196c0-.302-.06-.58-.186-.81c-.209-.38-.43-.855-.24-1.244c.153-.311.51-.487.82-.33c1.064.542 1.196 1.67 1.169 2.384v10.593a.773.773 0 0 1-.773.773a.776.776 0 0 1-.776-.788c.049-3.493-.014-9.664-.014-10.578");
}

.pty4jtb4p {
  stop-color: var(--svg-color--d59d93, #D59D93);
}

.qkgve9byl {
  stop-color: var(--svg-color--e4af90, #E4AF90);
  stop-opacity: 0;
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.ruy-7mtyv {
  stop-color: var(--svg-color--ffe5c9, #FFE5C9);
  stop-opacity: 0;
}

.t2y--rbpl {
  d: path("m22.775 8.06l-.267 8.548l4.156.343l.26-7.145a2.406 2.406 0 0 0-4.149-1.747");
}

.t4u30fdub {
  stop-color: var(--svg-color--f1b094, #F1B094);
  stop-opacity: 0;
}

.tax34cc_t {
  stop-color: var(--svg-color--f2b69f, #F2B69F);
}

.toh0blbdh {
  stop-color: var(--svg-color--f5b69a, #F5B69A);
  stop-opacity: 0;
}

.tpk1djbrc {
  stop-color: var(--svg-color--d8a88d, #D8A88D);
  stop-opacity: 0;
}

.twl_i-b2r {
  stop-color: var(--svg-color--fecbb6, #FECBB6);
}

.ubibb2bhq {
  stop-color: var(--svg-color--efbf9c, #EFBF9C);
  stop-opacity: 0;
}

.uy7s3ts9t {
  stop-color: var(--svg-color--efb896, #EFB896);
  stop-opacity: 0;
}

.va8v2kriz {
  d: path("m18.399 5.298l-.001.002l-.027-.945a2.406 2.406 0 0 0-4.808-.022l.007.455l.013.447l-.005-.008l.172 12.6h4.687z");
}

.vvabwacyo {
  stop-color: var(--svg-color--ddab8f, #DDAB8F);
}

.vybx3-bqw {
  stop-color: var(--svg-color--ffe1c5, #FFE1C5);
  stop-opacity: 0;
}

.watd7bysj {
  stop-color: var(--svg-color--d9a08a, #D9A08A);
}

.x0acfmbue {
  stop-color: var(--svg-color--d9a08a, #D9A08A);
  stop-opacity: 0;
}

.xce4m4bva {
  stop-color: var(--svg-color--ffddc3, #FFDDC3);
  stop-opacity: 0;
}

.xouzk_bmd {
  stop-color: var(--svg-color--c2886c, #C2886C);
  stop-opacity: 0;
}

.y36ypgcnp {
  stop-color: var(--svg-color--f2b69f, #F2B69F);
  stop-opacity: 0;
}

.y5q2h9u3l {
  stop-color: var(--svg-color--f9cab7, #F9CAB7);
}

.yafcvbc6z {
  d: path("M9.58 16.317v3.101l-3.762-4.823a.93.93 0 0 1 1.458-1.152z");
}

.ygn_swb3b {
  stop-color: var(--svg-color--d79b80, #D79B80);
  stop-opacity: 0;
}

.ypyl71b0u {
  stop-color: var(--svg-color--fdcdb7, #FDCDB7);
}

.ytovt-b_k {
  stop-color: var(--svg-color--c59074, #C59074);
  stop-opacity: 0;
}

.ztm_gzbze {
  stop-color: var(--svg-color--ffe5c9, #FFE5C9);
}

</style>
