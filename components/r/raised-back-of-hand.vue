<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i8au7Hd)"><path class="ccskepyip"/><path fill="url(#i3J3yFx)" class="abfxg6bra"/></g><path fill="url(#itaI3ie)" class="dv5imlbth"/><g filter="url(#iVZo2hH)"><path fill="url(#idr56fb)" class="k7c3f8bdf"/></g><path fill="url(#iabSpFe)" class="u1t2jlsul"/><path fill="url(#iZMJM8o)" class="u1t2jlsul"/><path fill="url(#irKzn6b)" class="u1t2jlsul"/><path fill="url(#ihkRJAb)" class="u1t2jlsul"/><path fill="url(#imFxIWb)" class="u1t2jlsul"/><path fill="url(#i0n7ZPe)" class="w0dw_0bdo"/><path fill="url(#iS3iIZD)" class="w0dw_0bdo"/><path fill="url(#irQJapb)" class="w0dw_0bdo"/><g filter="url(#i5BufHe)"><path fill="url(#iuoNDNb)" class="eb34ghr1d"/></g><g filter="url(#i1MgWLd)"><path fill="url(#iASFkHh)" class="zy6exmbxs"/></g><path fill="url(#iMBA4hd)" class="g66p2ga2k"/><path fill="url(#iJRVrbd)" class="g66p2ga2k"/><path fill="url(#iZC2Cxd)" class="g66p2ga2k"/><g filter="url(#idz5Lte)"><path fill="url(#iAWr3ae)" class="cz8lm5b3o"/></g><path fill="url(#igG7Nhd)" class="abfxg6bra"/><path fill="url(#i1yLt1F)" class="abfxg6bra"/><path fill="url(#i86O6ae)" class="abfxg6bra"/><path fill="url(#iTV5ltc)" class="abfxg6bra"/><path fill="url(#iNGBTFn)" class="abfxg6bra"/><g filter="url(#iwOjYfc)"><path fill="url(#iLJ62Vc)" class="uwy_aytpo"/></g><path fill="url(#izA2fhb)" class="vu3n41b6p"/><path fill="url(#iNXaGtb)" class="vu3n41b6p"/><path fill="url(#izns6Lc)" class="vu3n41b6p"/><g filter="url(#ijWl8pe)"><path fill="url(#ixJtzHe)" class="b2sv8sbru"/></g><defs><linearGradient id="idr56fb" x1="6.898" x2="11.207" y1="13.586" y2="20.376" gradientUnits="userSpaceOnUse"><stop class="jtnx86cjw"/><stop offset="1" class="ekl-imb0v"/></linearGradient><linearGradient id="iabSpFe" x1="9.127" x2="11.783" y1="12.014" y2="11.889" gradientUnits="userSpaceOnUse"><stop class="orufkg0hg"/><stop offset="1" class="p9n6xmbwa"/></linearGradient><linearGradient id="iZMJM8o" x1="14.549" x2="13.565" y1="11.061" y2="11.076" gradientUnits="userSpaceOnUse"><stop class="orufkg0hg"/><stop offset="1" class="p9n6xmbwa"/></linearGradient><linearGradient id="ihkRJAb" x1="11.995" x2="11.377" y1="16.779" y2="14.779" gradientUnits="userSpaceOnUse"><stop offset=".236" class="nww4t-_fs"/><stop offset="1" class="c7yj80b3b"/></linearGradient><linearGradient id="i0n7ZPe" x1="13.221" x2="16.299" y1="9.889" y2="9.836" gradientUnits="userSpaceOnUse"><stop class="orufkg0hg"/><stop offset="1" class="p9n6xmbwa"/></linearGradient><linearGradient id="iS3iIZD" x1="15.752" x2="15.957" y1="17.076" y2="14.145" gradientUnits="userSpaceOnUse"><stop class="nww4t-_fs"/><stop offset="1" class="c7yj80b3b"/></linearGradient><linearGradient id="iuoNDNb" x1="12.861" x2="17.831" y1="6.264" y2="9.495" gradientUnits="userSpaceOnUse"><stop class="ajy94lmoi"/><stop offset="1" class="qv9ps82hb"/></linearGradient><linearGradient id="iASFkHh" x1="18.189" x2="26.82" y1="2.139" y2="8.302" gradientUnits="userSpaceOnUse"><stop class="fd5f_40kf"/><stop offset="1" class="n9b89c0tl"/></linearGradient><linearGradient id="iMBA4hd" x1="18.124" x2="20.908" y1="10.823" y2="10.771" gradientUnits="userSpaceOnUse"><stop class="orufkg0hg"/><stop offset="1" class="p9n6xmbwa"/></linearGradient><linearGradient id="iJRVrbd" x1="19.939" x2="20.469" y1="15.889" y2="13.15" gradientUnits="userSpaceOnUse"><stop class="nww4t-_fs"/><stop offset="1" class="c7yj80b3b"/></linearGradient><linearGradient id="iAWr3ae" x1="22.329" x2="22.329" y1="5.451" y2="19.014" gradientUnits="userSpaceOnUse"><stop class="fd5f_40kf"/><stop offset="1" class="n9b89c0tl"/></linearGradient><linearGradient id="igG7Nhd" x1="27.839" x2="22.484" y1="22.599" y2="22.599" gradientUnits="userSpaceOnUse"><stop class="a4xw1tbvv"/><stop offset="1" class="qdu1srbuh"/></linearGradient><linearGradient id="iLJ62Vc" x1="27.68" x2="24.711" y1="16.131" y2="16.025" gradientUnits="userSpaceOnUse"><stop class="fd5f_40kf"/><stop offset="1" class="n9b89c0tl"/></linearGradient><linearGradient id="izA2fhb" x1="22.21" x2="24.537" y1="12.609" y2="12.855" gradientUnits="userSpaceOnUse"><stop class="y55yekevi"/><stop offset="1" class="khi66bwdx"/></linearGradient><linearGradient id="iNXaGtb" x1="23.439" x2="24.38" y1="16.951" y2="15.366" gradientUnits="userSpaceOnUse"><stop class="n2bed9_du"/><stop offset="1" class="j1n7p7evk"/></linearGradient><linearGradient id="ixJtzHe" x1="26.51" x2="26.261" y1="8.524" y2="22.084" gradientUnits="userSpaceOnUse"><stop class="fd5f_40kf"/><stop offset="1" class="n9b89c0tl"/></linearGradient><radialGradient id="i3J3yFx" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 -2.625 9.42008 18.39159 9.97 27.076)" gradientUnits="userSpaceOnUse"><stop class="euz8abcjt"/><stop offset="1" class="ad1_yac2x"/></radialGradient><radialGradient id="itaI3ie" cx="0" cy="0" r="1" gradientTransform="rotate(146.31 2.975 9.3)scale(1.33802 3.89834)" gradientUnits="userSpaceOnUse"><stop class="hjwn5ebmr"/><stop offset="1" class="tzetmabbl"/></radialGradient><radialGradient id="irKzn6b" cx="0" cy="0" r="1" gradientTransform="rotate(157.319 6.683 4.045)scale(1.13462 1.78724)" gradientUnits="userSpaceOnUse"><stop class="d2ehy6bmf"/><stop offset="1" class="f-4cx2bph"/></radialGradient><radialGradient id="imFxIWb" cx="0" cy="0" r="1" gradientTransform="matrix(.97056 1.68398 -3.94738 2.27506 10.533 3.795)" gradientUnits="userSpaceOnUse"><stop class="ssvds_4xk"/><stop offset="1" class="yroe2bb2g"/></radialGradient><radialGradient id="irQJapb" cx="0" cy="0" r="1" gradientTransform="matrix(.87499 1.62144 -2.44595 1.31993 15.127 2.017)" gradientUnits="userSpaceOnUse"><stop class="ssvds_4xk"/><stop offset="1" class="yroe2bb2g"/></radialGradient><radialGradient id="iZC2Cxd" cx="0" cy="0" r="1" gradientTransform="matrix(.79135 1.354 -2.12907 1.24435 19.848 4.25)" gradientUnits="userSpaceOnUse"><stop class="ssvds_4xk"/><stop offset="1" class="yroe2bb2g"/></radialGradient><radialGradient id="i1yLt1F" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 -2.2675 1.77572 -.14684 13.19 16)" gradientUnits="userSpaceOnUse"><stop class="wbodvl63i"/><stop offset="1" class="qoii0hbkb"/></radialGradient><radialGradient id="i86O6ae" cx="0" cy="0" r="1" gradientTransform="matrix(-.09377 -2.17374 2.00449 -.08647 17.909 16)" gradientUnits="userSpaceOnUse"><stop class="wbodvl63i"/><stop offset="1" class="qoii0hbkb"/></radialGradient><radialGradient id="iTV5ltc" cx="0" cy="0" r="1" gradientTransform="rotate(-91.909 18.742 -2.418)scale(1.87604)" gradientUnits="userSpaceOnUse"><stop class="wbodvl63i"/><stop offset="1" class="qoii0hbkb"/></radialGradient><radialGradient id="iNGBTFn" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 -1.06245 1.39986 -2.79985 25.313 16.483)" gradientUnits="userSpaceOnUse"><stop class="wbodvl63i"/><stop offset="1" class="qoii0hbkb"/></radialGradient><radialGradient id="izns6Lc" cx="0" cy="0" r="1" gradientTransform="matrix(.84085 1.7617 -4.7063 2.2463 23.908 6.639)" gradientUnits="userSpaceOnUse"><stop class="ssvds_4xk"/><stop offset="1" class="yroe2bb2g"/></radialGradient><filter id="i8au7Hd" width="23.289" height="28.965" x="4.413" y="1.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.4634 0 0 0 0 0.315 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1220"/></filter><filter id="iVZo2hH" width="5.458" height="7.823" x="5.398" y="12.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1220" stdDeviation=".375"/></filter><filter id="i5BufHe" width="3.424" height="13.25" x="11.203" y="4.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1220" stdDeviation=".375"/></filter><filter id="i1MgWLd" width="4.064" height="15.808" x="15.472" y="1.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1220" stdDeviation=".5"/></filter><filter id="idz5Lte" width="3.555" height="13.094" x="20.118" y="4.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1220" stdDeviation=".5"/></filter><filter id="iwOjYfc" width="6.11" height="21.827" x="21.961" y="6.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1220" stdDeviation=".5"/></filter><filter id="ijWl8pe" width="3.521" height="13.092" x="24.275" y="7.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1220" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:raised-back-of-hand" /></template>
<style>
.a4xw1tbvv {
  stop-color: var(--svg-color--ffca40, #FFCA40);
}

.abfxg6bra {
  d: path("M14.088 4.49a2.406 2.406 0 0 1 4.809-.135l.027.945a2.406 2.406 0 0 1 4.393 1.4l-.026 1.37a2.406 2.406 0 0 1 4.16 1.736l-.336 8.822c-.005 1.33-.149 3.695-1.003 5.76c-1.208 3.267-4.341 5.595-8.016 5.595c-3.715 0-6.877-2.379-8.055-5.701c-.888-2.11-2.361-4.283-2.986-5.206l-.042-.06l-2.098-2.82a2.536 2.536 0 0 1 4.05-3.054l1.088 1.424l-.343-7.953a2.385 2.385 0 0 1 4.399-1.378z");
}

.ad1_yac2x {
  stop-color: var(--svg-color--ef9833, #EF9833);
  stop-opacity: 0;
}

.ajy94lmoi {
  stop-color: var(--svg-color--fbc931, #FBC931);
}

.b2sv8sbru {
  d: path("M26.133 8.517a.673.673 0 0 0-.688.664c-.026 2.142-.091 7.103-.17 9.627c-.013.433.283.794.66.8c.37.007.676-.333.684-.76l.177-9.644a.675.675 0 0 0-.663-.687");
}

.c7yj80b3b {
  stop-color: var(--svg-color--ffc040, #FFC040);
  stop-opacity: 0;
}

.ccskepyip {
  fill: var(--svg-color--ffc040, #FFC040);
  d: path("M14.088 4.49a2.406 2.406 0 0 1 4.809-.135l.027.945a2.406 2.406 0 0 1 4.393 1.4l-.026 1.37a2.406 2.406 0 0 1 4.16 1.736l-.336 8.822c-.005 1.33-.149 3.695-1.003 5.76c-1.208 3.267-4.341 5.595-8.016 5.595c-3.715 0-6.877-2.379-8.055-5.701c-.888-2.11-2.361-4.283-2.986-5.206l-.042-.06l-2.098-2.82a2.536 2.536 0 0 1 4.05-3.054l1.088 1.424l-.343-7.953a2.385 2.385 0 0 1 4.399-1.378z");
}

.cz8lm5b3o {
  d: path("M21.896 5.451c-.432 0-.78.35-.778.782c.015 2.195.043 7.039.007 9.523a.776.776 0 0 0 .775.789a.77.77 0 0 0 .773-.772V6.228a.777.777 0 0 0-.777-.777");
}

.d2ehy6bmf {
  stop-color: var(--svg-color--9b5c19, #9B5C19);
}

.dv5imlbth {
  d: path("m5.357 12.708l.078-.06a2.536 2.536 0 0 1 3.53.494l1.084 1.419l.162 4.512z");
}

.eb34ghr1d {
  d: path("m11.953 5.921l.174 10.905l1.75-.218l-.261-10.72a.831.831 0 0 0-1.663.033");
}

.ekl-imb0v {
  stop-color: var(--svg-color--ffc737, #FFC737);
  stop-opacity: 0;
}

.euz8abcjt {
  stop-color: var(--svg-color--ef9833, #EF9833);
}

.f-4cx2bph {
  stop-color: var(--svg-color--9b5c19, #9B5C19);
  stop-opacity: 0;
}

.fd5f_40kf {
  stop-color: var(--svg-color--ffe747, #FFE747);
}

.ft5dv1b6b {
  fill: none;
}

.g66p2ga2k {
  d: path("m18.927 5.295l-.019 12.156h4.188l.196-9.383l-.001.002l.026-1.37a2.406 2.406 0 0 0-4.39-1.405");
}

.hjwn5ebmr {
  stop-color: var(--svg-color--b46810, #B46810);
}

.j1n7p7evk {
  stop-color: var(--svg-color--ffc642, #FFC642);
  stop-opacity: 0;
}

.jtnx86cjw {
  stop-color: var(--svg-color--ffc737, #FFC737);
}

.k7c3f8bdf {
  d: path("M10.105 16.317v3.101l-3.76-4.823a.93.93 0 0 1 1.457-1.152z");
}

.khi66bwdx {
  stop-color: var(--svg-color--f1a71c, #F1A71C);
  stop-opacity: 0;
}

.n2bed9_du {
  stop-color: var(--svg-color--ffc642, #FFC642);
}

.n9b89c0tl {
  stop-color: var(--svg-color--ffe747, #FFE747);
  stop-opacity: 0;
}

.nww4t-_fs {
  stop-color: var(--svg-color--ffc040, #FFC040);
}

.orufkg0hg {
  stop-color: var(--svg-color--e7942e, #E7942E);
}

.p9n6xmbwa {
  stop-color: var(--svg-color--e7942e, #E7942E);
  stop-opacity: 0;
}

.qdu1srbuh {
  stop-color: var(--svg-color--ffca40, #FFCA40);
  stop-opacity: 0;
}

.qoii0hbkb {
  stop-color: var(--svg-color--ffcd3f, #FFCD3F);
  stop-opacity: 0;
}

.qv9ps82hb {
  stop-color: var(--svg-color--fbc931, #FBC931);
  stop-opacity: 0;
}

.ssvds_4xk {
  stop-color: var(--svg-color--d79d3a, #D79D3A);
}

.tzetmabbl {
  stop-color: var(--svg-color--b46810, #B46810);
  stop-opacity: 0;
}

.u1t2jlsul {
  d: path("m10.039 14.547l.12 2.78l4.124-1.72l-.177-10.377A2.384 2.384 0 0 0 9.71 6.613l.343 7.953z");
}

.uwy_aytpo {
  d: path("M26.672 20.014c-.17 3.648-1.908 6.402-3.71 7.568l1.881-19.827c2.015 0 2.252 1.511 2.227 2.452c-.053 1.961-.228 6.16-.398 9.807");
}

.vu3n41b6p {
  d: path("m23.3 8.06l-.267 8.548l4.156.343l.262-7.145a2.406 2.406 0 0 0-4.15-1.747");
}

.w0dw_0bdo {
  d: path("m18.925 5.298l-.001.002l-.027-.945a2.406 2.406 0 0 0-4.809-.022l.008.455l.013.447l-.005-.008l.172 12.6h4.687z");
}

.wbodvl63i {
  stop-color: var(--svg-color--ffcd3f, #FFCD3F);
}

.y55yekevi {
  stop-color: var(--svg-color--f1a71c, #F1A71C);
}

.yroe2bb2g {
  stop-color: var(--svg-color--d79d3a, #D79D3A);
  stop-opacity: 0;
}

.zy6exmbxs {
  d: path("M16.97 5.18c0-.302-.06-.581-.186-.81c-.209-.38-.43-.856-.239-1.245c.153-.311.51-.486.819-.33c1.065.542 1.196 1.67 1.17 2.384v10.594a.77.77 0 0 1-.773.772a.776.776 0 0 1-.776-.788c.048-3.492-.014-9.664-.014-10.578");
}

</style>
