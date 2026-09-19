<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iTDuquq)"><path class="klf2kwbnr"/><path fill="url(#i76l5Fb)" class="i49u0jb4h"/><path fill="url(#i3PeE0c)" class="i49u0jb4h"/></g><path fill="url(#i4YorRb)" class="d94ttnbbo"/><g filter="url(#iueg8yc)"><path fill="url(#iUWYlac)" class="afuvsp37i"/></g><path fill="url(#i2EFsme)" class="o8rsn9ban"/><path fill="url(#iblKE9c)" class="o8rsn9ban"/><path fill="url(#itdnkQO)" class="o8rsn9ban"/><path fill="url(#ielELye)" class="o8rsn9ban"/><path fill="url(#iDRR0ye)" class="o8rsn9ban"/><g filter="url(#ih3Ba0d)"><path class="cp6wnkwvq"/></g><path fill="url(#ilzlbTc)" class="jlkxt1b-o"/><path fill="url(#i4p5cAb)" class="jlkxt1b-o"/><path fill="url(#iz6pSHe)" class="jlkxt1b-o"/><path fill="url(#iDzefrd)" class="jlkxt1b-o"/><g filter="url(#ijETymc)"><path fill="url(#i3CrOld)" class="axi07m1ej"/></g><path fill="url(#i2sN2Je)" class="vqw4gwb7s"/><path fill="url(#id2wlRd)" class="vqw4gwb7s"/><path fill="url(#i2JfAte)" class="vqw4gwb7s"/><path fill="url(#iQS18Dc)" class="vqw4gwb7s"/><g filter="url(#iR0r29b)"><path fill="url(#i3ewpsG)" class="vbaxtlbwt"/></g><path fill="url(#iGaHOLb)" class="i49u0jb4h"/><path fill="url(#iCpkBve)" class="i49u0jb4h"/><path fill="url(#ieHZSAe)" class="i49u0jb4h"/><path fill="url(#idCLCcb)" class="i49u0jb4h"/><path fill="url(#i0xsbAc)" class="i49u0jb4h"/><path fill="url(#i8AeQrn)" class="i49u0jb4h"/><g filter="url(#iXb1r4c)"><path fill="url(#iic2g2c)" class="mddybub0i"/></g><path fill="url(#iVNhmic)" class="aggo5pb1z"/><path fill="url(#izp8lFe)" class="aggo5pb1z"/><path fill="url(#i1L3cXc)" class="aggo5pb1z"/><g filter="url(#iCPNUTd)"><path fill="url(#isjCzFe)" class="n18ry-xel"/></g><defs><linearGradient id="iUWYlac" x1="18.414" x2="11.624" y1="6.372" y2="10.681" gradientUnits="userSpaceOnUse"><stop class="y5q2h9u3l"/><stop offset="1" class="h4i43fe5d"/></linearGradient><linearGradient id="i2EFsme" x1="20.155" x2="20.267" y1="8.999" y2="11.049" gradientUnits="userSpaceOnUse"><stop class="watd7bysj"/><stop offset="1" class="x0acfmbue"/></linearGradient><linearGradient id="iblKE9c" x1="20.939" x2="20.924" y1="14.023" y2="13.039" gradientUnits="userSpaceOnUse"><stop class="p0gxu-byn"/><stop offset="1" class="amv1ddc3a"/></linearGradient><linearGradient id="ielELye" x1="15.221" x2="17.221" y1="11.47" y2="10.851" gradientUnits="userSpaceOnUse"><stop offset=".236" class="lyot_fbwv"/><stop offset="1" class="d95nnob8o"/></linearGradient><linearGradient id="ilzlbTc" x1="22.111" x2="22.164" y1="12.695" y2="15.774" gradientUnits="userSpaceOnUse"><stop class="bftq_gu9d"/><stop offset="1" class="ygn_swb3b"/></linearGradient><linearGradient id="iz6pSHe" x1="22.485" x2="22.485" y1="18.877" y2="17.669" gradientUnits="userSpaceOnUse"><stop class="pa7rlh4ga"/><stop offset="1" class="toh0blbdh"/></linearGradient><linearGradient id="iDzefrd" x1="14.924" x2="17.855" y1="15.226" y2="15.431" gradientUnits="userSpaceOnUse"><stop class="lyot_fbwv"/><stop offset="1" class="d95nnob8o"/></linearGradient><linearGradient id="i3CrOld" x1="31.822" x2="24.991" y1="17.53" y2="27.096" gradientUnits="userSpaceOnUse"><stop class="g73iv-bvy"/><stop offset="1" class="alsobs70x"/></linearGradient><linearGradient id="i2sN2Je" x1="21.177" x2="21.229" y1="17.598" y2="20.382" gradientUnits="userSpaceOnUse"><stop class="cjq0uac_s"/><stop offset="1" class="t4u30fdub"/></linearGradient><linearGradient id="id2wlRd" x1="21.149" x2="21.139" y1="23.511" y2="22.04" gradientUnits="userSpaceOnUse"><stop class="liqnqtkwv"/><stop offset="1" class="j_6_xlabe"/></linearGradient><linearGradient id="i2JfAte" x1="16.111" x2="18.85" y1="19.414" y2="19.943" gradientUnits="userSpaceOnUse"><stop class="lyot_fbwv"/><stop offset="1" class="d95nnob8o"/></linearGradient><linearGradient id="i3ewpsG" x1="26.549" x2="12.986" y1="21.803" y2="21.803" gradientUnits="userSpaceOnUse"><stop class="ztm_gzbze"/><stop offset="1" class="ruy-7mtyv"/></linearGradient><linearGradient id="iGaHOLb" x1="9.401" x2="9.401" y1="27.313" y2="21.959" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="ubibb2bhq"/></linearGradient><linearGradient id="iic2g2c" x1="15.869" x2="15.975" y1="27.154" y2="24.185" gradientUnits="userSpaceOnUse"><stop class="m2qxnw_1z"/><stop offset="1" class="xce4m4bva"/></linearGradient><linearGradient id="iVNhmic" x1="19.391" x2="19.145" y1="21.684" y2="24.011" gradientUnits="userSpaceOnUse"><stop class="tax34cc_t"/><stop offset="1" class="y36ypgcnp"/></linearGradient><linearGradient id="izp8lFe" x1="15.049" x2="18.542" y1="24.328" y2="24.517" gradientUnits="userSpaceOnUse"><stop class="ypyl71b0u"/><stop offset="1" class="dl3-s1bsu"/></linearGradient><linearGradient id="isjCzFe" x1="23.477" x2="9.916" y1="25.984" y2="25.735" gradientUnits="userSpaceOnUse"><stop class="j3x50rbgd"/><stop offset="1" class="vybx3-bqw"/></linearGradient><radialGradient id="i76l5Fb" cx="0" cy="0" r="1" gradientTransform="matrix(2.62497 5.12502 -18.39164 9.41998 4.924 9.445)" gradientUnits="userSpaceOnUse"><stop class="pty4jtb4p"/><stop offset="1" class="hwxb5d_9d"/></radialGradient><radialGradient id="i3PeE0c" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 9.689 3.852)scale(2.48176 3.91796)" gradientUnits="userSpaceOnUse"><stop class="vvabwacyo"/><stop offset="1" class="b3q492gve"/></radialGradient><radialGradient id="i4YorRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7422 -1.1133 3.24362 -2.1624 16.611 10.083)" gradientUnits="userSpaceOnUse"><stop class="dgkitw09n"/><stop offset="1" class="xouzk_bmd"/></radialGradient><radialGradient id="itdnkQO" cx="0" cy="0" r="1" gradientTransform="rotate(-112.681 18.022 -1.981)scale(1.13462 1.78724)" gradientUnits="userSpaceOnUse"><stop class="aw2urnbyz"/><stop offset="1" class="ytovt-b_k"/></radialGradient><radialGradient id="iDRR0ye" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36578 1.14881 -2.17622 -4.48155 27.964 10.32)" gradientUnits="userSpaceOnUse"><stop class="na5i0acdf"/><stop offset="1" class="tpk1djbrc"/></radialGradient><radialGradient id="i4p5cAb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.08638 1.14425 -2.31876 -4.22794 29.983 14.601)" gradientUnits="userSpaceOnUse"><stop class="ohs1s4bqc"/><stop offset="1" class="eiy6wfbug"/></radialGradient><radialGradient id="iQS18Dc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.354 .79135 -1.24433 -2.12908 27.75 19.322)" gradientUnits="userSpaceOnUse"><stop class="ggalksyuq"/><stop offset="1" class="qkgve9byl"/></radialGradient><radialGradient id="iCpkBve" cx="0" cy="0" r="1" gradientTransform="matrix(2.2675 -.1875 .14684 1.77572 16 12.664)" gradientUnits="userSpaceOnUse"><stop class="twl_i-b2r"/><stop offset="1" class="jofbdab8p"/></radialGradient><radialGradient id="ieHZSAe" cx="0" cy="0" r="1" gradientTransform="matrix(2.17374 -.09375 .08645 2.00449 16 17.383)" gradientUnits="userSpaceOnUse"><stop class="twl_i-b2r"/><stop offset="1" class="jofbdab8p"/></radialGradient><radialGradient id="idCLCcb" cx="0" cy="0" r="1" gradientTransform="rotate(-1.909 645.796 -462.53)scale(1.87604)" gradientUnits="userSpaceOnUse"><stop class="twl_i-b2r"/><stop offset="1" class="jofbdab8p"/></radialGradient><radialGradient id="i0xsbAc" cx="0" cy="0" r="1" gradientTransform="rotate(-63.435 27.813 -.16)scale(2.37582 3.13027)" gradientUnits="userSpaceOnUse"><stop class="twl_i-b2r"/><stop offset="1" class="jofbdab8p"/></radialGradient><radialGradient id="i8AeQrn" cx="0" cy="0" r="1" gradientTransform="rotate(62.242 -2.228 12.076)scale(3.03562 12.0503)" gradientUnits="userSpaceOnUse"><stop class="m6-hzbe_o"/><stop offset="1" class="nxfhb4lzv"/></radialGradient><radialGradient id="i1L3cXc" cx="0" cy="0" r="1" gradientTransform="rotate(154.485 10.034 14.562)scale(1.95209 5.21489)" gradientUnits="userSpaceOnUse"><stop class="frr5f9b7s"/><stop offset="1" class="uy7s3ts9t"/></radialGradient><filter id="iTDuquq" width="27.965" height="24.039" x="2.017" y="2.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.486275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6519"/></filter><filter id="iueg8yc" width="7.823" height="5.458" x="11.832" y="4.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6519" stdDeviation=".375"/></filter><filter id="ih3Ba0d" width="12.102" height="3.414" x="15.398" y="10.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6519" stdDeviation=".5"/></filter><filter id="ijETymc" width="15.808" height="4.064" x="14.438" y="14.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6519" stdDeviation=".5"/></filter><filter id="iR0r29b" width="13.094" height="3.555" x="14.455" y="19.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6519" stdDeviation=".5"/></filter><filter id="iXb1r4c" width="21.827" height="6.11" x="3.418" y="21.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6519" stdDeviation=".5"/></filter><filter id="iCPNUTd" width="13.092" height="3.521" x="11.391" y="23.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6519" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rightwards-hand-light" /></template>
<style>
.afuvsp37i {
  d: path("M15.683 9.58h-3.1l4.822-3.762a.93.93 0 0 1 1.152 1.458z");
}

.aggo5pb1z {
  d: path("m23.94 22.775l-8.548-.267l-.343 4.156l7.145.26a2.406 2.406 0 0 0 1.747-4.149");
}

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

.axi07m1ej {
  d: path("M26.804 16.311c.302 0 .58-.06.81-.186c.38-.21.855-.43 1.244-.24c.311.153.487.51.33.82c-.542 1.064-1.67 1.196-2.384 1.169H16.211a.773.773 0 0 1-.773-.773c0-.433.355-.782.788-.776c3.493.049 9.664-.014 10.578-.014");
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

.cp6wnkwvq {
  fill: var(--svg-color--ffd0bb, #FFD0BB);
  d: path("m25.882 11.68l-9.484.129l.189 1.285l9.316-.194a.61.61 0 0 0-.021-1.22");
}

.d94ttnbbo {
  d: path("m19.292 4.831l.06.079a2.536 2.536 0 0 1-.494 3.53l-1.419 1.084l-4.512.162z");
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

.eiy6wfbug {
  stop-color: var(--svg-color--d4a78c, #D4A78C);
  stop-opacity: 0;
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

.i49u0jb4h {
  d: path("M27.51 13.562a2.406 2.406 0 0 1 .135 4.81l-.945.026a2.406 2.406 0 0 1-1.4 4.393l-1.37-.026a2.406 2.406 0 0 1-1.736 4.16l-8.822-.335c-1.33-.005-3.695-.15-5.76-1.004c-3.267-1.207-5.595-4.34-5.595-8.016c0-3.715 2.379-6.876 5.701-8.054c2.11-.889 4.284-2.362 5.206-2.987l.06-.041l2.82-2.098a2.536 2.536 0 0 1 3.054 4.05l-1.424 1.088l7.953-.344a2.385 2.385 0 0 1 1.378 4.4z");
}

.j_6_xlabe {
  stop-color: var(--svg-color--ffcdb0, #FFCDB0);
  stop-opacity: 0;
}

.j3x50rbgd {
  stop-color: var(--svg-color--ffe1c5, #FFE1C5);
}

.jlkxt1b-o {
  d: path("m26.702 18.4l-.002-.002l.945-.026a2.406 2.406 0 0 0 .022-4.81l-.455.008l-.447.013l.008-.005l-12.6.172v4.687z");
}

.jofbdab8p {
  stop-color: var(--svg-color--fecbb6, #FECBB6);
  stop-opacity: 0;
}

.klf2kwbnr {
  fill: var(--svg-color--fbc5b2, #FBC5B2);
  d: path("M27.51 13.562a2.406 2.406 0 0 1 .135 4.81l-.945.026a2.406 2.406 0 0 1-1.4 4.393l-1.37-.026a2.406 2.406 0 0 1-1.736 4.16l-8.822-.335c-1.33-.005-3.695-.15-5.76-1.004c-3.267-1.207-5.595-4.34-5.595-8.016c0-3.715 2.379-6.876 5.701-8.054c2.11-.889 4.284-2.362 5.206-2.987l.06-.041l2.82-2.098a2.536 2.536 0 0 1 3.054 4.05l-1.424 1.088l7.953-.344a2.385 2.385 0 0 1 1.378 4.4z");
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

.mddybub0i {
  d: path("M11.986 26.147c-3.648-.17-6.402-1.909-7.568-3.711l19.827 1.882c0 2.014-1.511 2.252-2.452 2.226c-1.961-.053-6.16-.228-9.807-.398");
}

.n18ry-xel {
  d: path("M23.483 25.607a.673.673 0 0 0-.664-.687c-2.142-.027-7.103-.092-9.627-.17c-.433-.014-.794.282-.8.659c-.007.37.333.677.76.684l9.644.177c.373.007.68-.29.687-.663");
}

.na5i0acdf {
  stop-color: var(--svg-color--d8a88d, #D8A88D);
}

.nxfhb4lzv {
  stop-color: var(--svg-color--d59c93, #D59C93);
  stop-opacity: 0;
}

.o8rsn9ban {
  d: path("m17.453 9.513l-2.78.12l1.72 4.125l10.377-.178a2.384 2.384 0 0 0-1.383-4.396l-7.953.344z");
}

.ohs1s4bqc {
  stop-color: var(--svg-color--d4a78c, #D4A78C);
}

.p0gxu-byn {
  stop-color: var(--svg-color--d59779, #D59779);
}

.pa7rlh4ga {
  stop-color: var(--svg-color--f5b69a, #F5B69A);
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

.vbaxtlbwt {
  d: path("M26.549 21.37c0-.432-.35-.78-.782-.777c-2.195.015-7.039.042-9.523.006a.776.776 0 0 0-.789.776c0 .426.346.772.772.772h9.545a.777.777 0 0 0 .777-.777");
}

.vqw4gwb7s {
  d: path("m26.705 18.401l-12.156-.018v4.187l9.383.197l-.002-.002l1.37.026a2.406 2.406 0 0 0 1.405-4.39");
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
