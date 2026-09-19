<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ib26UFe)"><path fill="url(#iDg8qpd)" class="qeh5ncbyw"/></g><path fill="url(#iFmRp9b)" class="qeh5ncbyw"/><path fill="url(#i0XcOQc)" class="qeh5ncbyw"/><path fill="url(#iglYpAd)" class="qeh5ncbyw"/><path fill="url(#iizc5fb)" class="qeh5ncbyw"/><path fill="url(#ibHgYac)" class="qeh5ncbyw"/><path fill="url(#iFn8H2b)" class="qeh5ncbyw"/><g filter="url(#i05flPb)"><path fill="url(#ihJPZKd)" class="a6vpb3wgj"/></g><g filter="url(#iQvAe7b)"><rect fill="url(#iAXtWFV)" transform="rotate(90 26.311 10.956)" class="nulv6tb5a"/><rect fill="url(#iXlz1hc)" transform="rotate(90 26.311 10.956)" class="nulv6tb5a"/></g><g filter="url(#iqpP3bb)"><rect fill="url(#iLP0LNd)" class="w25b19b4p"/></g><g filter="url(#i7gft4c)"><rect fill="url(#iQH433b)" transform="rotate(90 26.01 24.241)" class="kyccnjggu"/><rect fill="url(#iLkq4zd)" transform="rotate(90 26.01 24.241)" class="kyccnjggu"/><rect fill="url(#iK3uDdc)" transform="rotate(90 26.01 24.241)" class="kyccnjggu"/></g><g filter="url(#iNadtfD)"><rect fill="url(#iiqYwId)" class="r1mt1hjkq"/></g><g filter="url(#i1YkOHb)"><rect fill="url(#iCOKlGd)" transform="rotate(90 27.31 19.96)" class="pio5ct8ci"/><rect fill="url(#iSwAqLc)" transform="rotate(90 27.31 19.96)" class="pio5ct8ci"/><rect fill="url(#i4I7HYw)" transform="rotate(90 27.31 19.96)" class="pio5ct8ci"/></g><g filter="url(#i3ZBYNe)"><rect fill="url(#iQ1OOZc)" class="grgqambzq"/></g><g filter="url(#iPmEPoe)"><rect fill="url(#ieSPLLe)" transform="rotate(90 27.264 15.51)" class="c98xuu6bx"/><rect fill="url(#igqgrpe)" transform="rotate(90 27.264 15.51)" class="c98xuu6bx"/></g><g filter="url(#igTRFQc)"><rect fill="url(#iPaPiOb)" class="i1jeh-bor"/></g><path fill="url(#iYRSz8d)" class="uigkqbban"/><g filter="url(#i0ufoPe)"><rect fill="url(#it7DNnb)" class="s5-scvkfs"/></g><defs><radialGradient id="iFmRp9b" cx="0" cy="0" r="1" gradientTransform="rotate(138.27 8.294 5.52)scale(4.15174 3.36548)" gradientUnits="userSpaceOnUse"><stop class="w9bdepy6n"/><stop offset="1" class="eqmqbzb2b"/></radialGradient><radialGradient id="i0XcOQc" cx="0" cy="0" r="1" gradientTransform="rotate(133.564 1.942 10.305)scale(7.41221 5.36952)" gradientUnits="userSpaceOnUse"><stop class="m2me9cuwe"/><stop offset="1" class="idzsd9bzw"/></radialGradient><radialGradient id="iglYpAd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.66242 7.45294 -4.59455 -4.72369 20.294 16.89)" gradientUnits="userSpaceOnUse"><stop class="e-084nbmr"/><stop offset="1" class="g9t6yqb5s"/></radialGradient><radialGradient id="iizc5fb" cx="0" cy="0" r="1" gradientTransform="matrix(4.1316 -9.88413 13.06853 5.4627 13.525 30.794)" gradientUnits="userSpaceOnUse"><stop class="hzfezx06y"/><stop offset="1" class="pb57axbbu"/></radialGradient><radialGradient id="ibHgYac" cx="0" cy="0" r="1" gradientTransform="matrix(-15.534 0 0 -23.9075 20.588 20.869)" gradientUnits="userSpaceOnUse"><stop offset=".864" class="o2jbv56ay"/><stop offset="1" class="e681q9jvi"/></radialGradient><radialGradient id="iFn8H2b" cx="0" cy="0" r="1" gradientTransform="matrix(1.21582 .98104 -1.29196 1.60114 18.72 11.382)" gradientUnits="userSpaceOnUse"><stop class="jbmqwib8t"/><stop offset="1" class="jy3ft5-bv"/></radialGradient><radialGradient id="iXlz1hc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40872 1.84473 -1.2348 -.94296 31.8 18.529)" gradientUnits="userSpaceOnUse"><stop class="u113t5obb"/><stop offset="1" class="g7w3mob8m"/></radialGradient><radialGradient id="iLkq4zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.31347 2.78222 0 31.674 31.307)" gradientUnits="userSpaceOnUse"><stop class="t5eaj7bhl"/><stop offset="1" class="epspzefmp"/></radialGradient><radialGradient id="iK3uDdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.4169 1.66759 0 27.005 31.658)" gradientUnits="userSpaceOnUse"><stop class="r7m44x6bs"/><stop offset="1" class="aa384_i6u"/></radialGradient><radialGradient id="iSwAqLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.21683 3.27876 0 33.273 28.062)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="yioqrj9eg"/><stop offset="1" class="nczaidcka"/></radialGradient><radialGradient id="i4I7HYw" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.50376 2.09648 0 28.356 28.464)" gradientUnits="userSpaceOnUse"><stop class="y3a3ubcbb"/><stop offset="1" class="q4fiegbdf"/></radialGradient><radialGradient id="igqgrpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.09375 3.75685 0 33.097 23.056)" gradientUnits="userSpaceOnUse"><stop class="wig6o1brk"/><stop offset="1" class="drvywtbim"/></radialGradient><radialGradient id="iYRSz8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.57369 -2.59444 0 12.706 5.858)" gradientUnits="userSpaceOnUse"><stop class="ovcn17b3h"/><stop offset="1" class="aqkzz_n3u"/></radialGradient><linearGradient id="iDg8qpd" x1="17.875" x2="9.546" y1="10.601" y2="28.053" gradientUnits="userSpaceOnUse"><stop class="nrso79iyq"/><stop offset="1" class="kjqnqibar"/></linearGradient><linearGradient id="ihJPZKd" x1="21.393" x2="18.664" y1="10.936" y2="26.364" gradientUnits="userSpaceOnUse"><stop class="y3195fbjr"/><stop offset="1" class="ql_pggbwo"/></linearGradient><linearGradient id="iAXtWFV" x1="29.221" x2="29.221" y1="10.956" y2="18.218" gradientUnits="userSpaceOnUse"><stop class="ofhcu-b3u"/><stop offset="1" class="m602hdc5h"/></linearGradient><linearGradient id="iLP0LNd" x1="25.027" x2="18.413" y1="13.072" y2="13.072" gradientUnits="userSpaceOnUse"><stop class="a6uau22wc"/><stop offset="1" class="f2pe0tyio"/></linearGradient><linearGradient id="iQH433b" x1="28.843" x2="28.843" y1="25.017" y2="33.102" gradientUnits="userSpaceOnUse"><stop class="ct1rz8h9o"/><stop offset="1" class="a7aq1ubmx"/></linearGradient><linearGradient id="iiqYwId" x1="25.067" x2="19.278" y1="26.329" y2="26.329" gradientUnits="userSpaceOnUse"><stop class="lun1rzujg"/><stop offset="1" class="n7j-lccxy"/></linearGradient><linearGradient id="iCOKlGd" x1="30.291" x2="30.291" y1="20.851" y2="30.12" gradientUnits="userSpaceOnUse"><stop class="did4aib0e"/><stop offset="1" class="tkjrbhuit"/></linearGradient><linearGradient id="iQ1OOZc" x1="25.962" x2="18.713" y1="22.459" y2="22.459" gradientUnits="userSpaceOnUse"><stop class="t8pekqyir"/><stop offset="1" class="jayc8mbcm"/></linearGradient><linearGradient id="ieSPLLe" x1="30.18" x2="30.18" y1="15.511" y2="25.624" gradientUnits="userSpaceOnUse"><stop class="wj-6zublk"/><stop offset="1" class="kisr_h6dy"/></linearGradient><linearGradient id="iPaPiOb" x1="25.939" x2="18.208" y1="17.425" y2="17.425" gradientUnits="userSpaceOnUse"><stop class="n1eyhb-al"/><stop offset="1" class="v-7wawbns"/></linearGradient><linearGradient id="it7DNnb" x1="18.221" x2="15.133" y1="5.531" y2="5.531" gradientUnits="userSpaceOnUse"><stop class="hme6epbcf"/><stop offset="1" class="e_55ol2tc"/></linearGradient><filter id="ib26UFe" width="19.048" height="27.809" x="5.271" y="2.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.360784 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2941"/></filter><filter id="i05flPb" width="12.909" height="20.615" x="14" y="10.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2941" stdDeviation="1"/></filter><filter id="iQvAe7b" width="9.543" height="5.82" x="17.268" y="10.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.258824 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2941"/></filter><filter id="iqpP3bb" width="8.636" height="5.016" x="17.96" y="11.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2941" stdDeviation=".625"/></filter><filter id="i7gft4c" width="9.361" height="6.164" x="17.15" y="24.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.235294 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2941"/></filter><filter id="iNadtfD" width="7.87" height="3.976" x="18.726" y="24.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2941" stdDeviation=".625"/></filter><filter id="i1YkOHb" width="10.659" height="6.964" x="17.15" y="19.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.435294 0 0 0 0 0.301961 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2941"/></filter><filter id="i3ZBYNe" width="9.225" height="3.976" x="18.336" y="20.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2941" stdDeviation=".625"/></filter><filter id="iPmEPoe" width="10.614" height="6.333" x="17.15" y="15.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.435294 0 0 0 0 0.301961 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2941"/></filter><filter id="igTRFQc" width="9.672" height="5.016" x="17.889" y="15.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2941" stdDeviation=".625"/></filter><filter id="i0ufoPe" width="5.365" height="10.497" x="14.255" y="2.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2941" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:thumbs-up-medium-dark" /></template>
<style>
.a6uau22wc {
  stop-color: var(--svg-color--a17c71, #A17C71);
}

.a6vpb3wgj {
  d: path("M24.033 14.935a2.55 2.55 0 0 0-2.552-2.552h-2.826a2.552 2.552 0 0 0-1.638 4.508a2.557 2.557 0 0 0-.115 3.993A2.55 2.55 0 0 0 16 22.83v.126c0 .7.281 1.333.737 1.794a2.483 2.483 0 0 0 1.746 4.248h2.804a2.483 2.483 0 0 0 2.148-3.729a2.55 2.55 0 0 0 1.474-2.313v-.126c0-.79-.36-1.495-.922-1.963a2.56 2.56 0 0 0-.587-4.249c.394-.45.633-1.039.633-1.684");
}

.a7aq1ubmx {
  stop-color: var(--svg-color--6c4646, #6C4646);
}

.aa384_i6u {
  stop-color: var(--svg-color--532e2d, #532E2D);
  stop-opacity: 0;
}

.aqkzz_n3u {
  stop-color: var(--svg-color--734e48, #734E48);
  stop-opacity: 0;
}

.c98xuu6bx {
  width: 5.833px;
  height: 10.114px;
  x: 27.264px;
  y: 15.511px;
  rx: 2.91px;
}

.ct1rz8h9o {
  stop-color: var(--svg-color--966962, #966962);
}

.did4aib0e {
  stop-color: var(--svg-color--9c7365, #9C7365);
}

.drvywtbim {
  stop-color: var(--svg-color--744157, #744157);
  stop-opacity: 0;
}

.e_55ol2tc {
  stop-color: var(--svg-color--a17c70, #A17C70);
  stop-opacity: 0;
}

.e-084nbmr {
  stop-color: var(--svg-color--624543, #624543);
}

.e681q9jvi {
  stop-color: var(--svg-color--846059, #846059);
}

.epspzefmp {
  stop-color: var(--svg-color--7b3f6b, #7B3F6B);
  stop-opacity: 0;
}

.eqmqbzb2b {
  stop-color: var(--svg-color--a07a69, #A07A69);
  stop-opacity: 0;
}

.f2pe0tyio {
  stop-color: var(--svg-color--a17c71, #A17C71);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g7w3mob8m {
  stop-color: var(--svg-color--4f2e2b, #4F2E2B);
  stop-opacity: 0;
}

.g9t6yqb5s {
  stop-color: var(--svg-color--624543, #624543);
  stop-opacity: 0;
}

.grgqambzq {
  width: 6.725px;
  height: 1.476px;
  x: 19.586px;
  y: 22.054px;
  rx: 0.738px;
}

.hme6epbcf {
  stop-color: var(--svg-color--a17c70, #A17C70);
}

.hzfezx06y {
  stop-color: var(--svg-color--794069, #794069);
}

.i1jeh-bor {
  width: 7.172px;
  height: 2.516px;
  x: 19.139px;
  y: 16.735px;
  rx: 1.258px;
}

.idzsd9bzw {
  stop-color: var(--svg-color--7d594c, #7D594C);
  stop-opacity: 0;
}

.jayc8mbcm {
  stop-color: var(--svg-color--a37e74, #A37E74);
  stop-opacity: 0;
}

.jbmqwib8t {
  stop-color: var(--svg-color--957466, #957466);
}

.jy3ft5-bv {
  stop-color: var(--svg-color--957466, #957466);
  stop-opacity: 0;
}

.kisr_h6dy {
  stop-color: var(--svg-color--744e49, #744E49);
}

.kjqnqibar {
  stop-color: var(--svg-color--835060, #835060);
}

.kyccnjggu {
  width: 5.664px;
  height: 8.861px;
  x: 26.011px;
  y: 24.241px;
  rx: 2.832px;
}

.lun1rzujg {
  stop-color: var(--svg-color--997570, #997570);
}

.m2me9cuwe {
  stop-color: var(--svg-color--7d594c, #7D594C);
}

.m602hdc5h {
  stop-color: var(--svg-color--6f4a47, #6F4A47);
}

.n1eyhb-al {
  stop-color: var(--svg-color--a68074, #A68074);
}

.n7j-lccxy {
  stop-color: var(--svg-color--997570, #997570);
  stop-opacity: 0;
}

.nczaidcka {
  stop-color: var(--svg-color--77405b, #77405B);
  stop-opacity: 0;
}

.nrso79iyq {
  stop-color: var(--svg-color--997363, #997363);
}

.nulv6tb5a {
  width: 5.82px;
  height: 9.043px;
  x: 26.311px;
  y: 10.956px;
  rx: 2.91px;
}

.o2jbv56ay {
  stop-color: var(--svg-color--846059, #846059);
  stop-opacity: 0;
}

.ofhcu-b3u {
  stop-color: var(--svg-color--9b7766, #9B7766);
}

.ovcn17b3h {
  stop-color: var(--svg-color--734e48, #734E48);
}

.pb57axbbu {
  stop-color: var(--svg-color--794069, #794069);
  stop-opacity: 0;
}

.pio5ct8ci {
  width: 5.964px;
  height: 10.159px;
  x: 27.309px;
  y: 19.961px;
  rx: 2.91px;
}

.q4fiegbdf {
  stop-color: var(--svg-color--663b39, #663B39);
  stop-opacity: 0;
}

.qeh5ncbyw {
  d: path("M12.622 5.384a3.289 3.289 0 1 1 6.577 0v3.784q.002.484-.072.967c-.018.117-.037.235-.048.352c-.036.37.008.854.26 1.179l-.602.58a9.34 9.34 0 0 1 5.082 8.326c0 .985-.152 1.935-.433 2.826l-.996 6.507h-8.102v-.003c-5.003-.108-9.017-3.37-9.017-9.33c0-3.503 1.677-6.323 4.215-7.913l-.007-.005c.173-.12.377-.242.596-.373l.001-.001c.72-.431 1.6-.959 2.063-1.821c.403-.748.481-1.961.481-2.523h.002z");
}

.ql_pggbwo {
  stop-color: var(--svg-color--6e3657, #6E3657);
}

.r1mt1hjkq {
  width: 5.37px;
  height: 1.476px;
  x: 19.976px;
  y: 25.924px;
  rx: 0.738px;
}

.r7m44x6bs {
  stop-color: var(--svg-color--532e2d, #532E2D);
}

.s5-scvkfs {
  width: 2.865px;
  height: 7.997px;
  x: 15.505px;
  y: 3.338px;
  rx: 1.433px;
}

.t5eaj7bhl {
  stop-color: var(--svg-color--7b3f6b, #7B3F6B);
}

.t8pekqyir {
  stop-color: var(--svg-color--a37e74, #A37E74);
}

.tkjrbhuit {
  stop-color: var(--svg-color--754f4c, #754F4C);
}

.u113t5obb {
  stop-color: var(--svg-color--4f2e2b, #4F2E2B);
}

.uigkqbban {
  d: path("M15.922 2.095a3.29 3.29 0 0 0-3.289 3.289v2.552h-.002c0 .562-.078 1.775-.48 2.523c-.464.862-1.344 1.39-2.063 1.82c-.22.132-.424.255-.597.375c.995.797 3.032 2.39 3.082 2.352s2.344-1.255 3.484-1.86l-.048-.69a3.29 3.29 0 0 0 3.201-3.288V5.384a3.29 3.29 0 0 0-3.288-3.289");
}

.v-7wawbns {
  stop-color: var(--svg-color--a68074, #A68074);
  stop-opacity: 0;
}

.w25b19b4p {
  width: 6.136px;
  height: 2.516px;
  x: 19.21px;
  y: 12.383px;
  rx: 1.258px;
}

.w9bdepy6n {
  stop-color: var(--svg-color--a07a69, #A07A69);
}

.wig6o1brk {
  stop-color: var(--svg-color--744157, #744157);
}

.wj-6zublk {
  stop-color: var(--svg-color--9c7563, #9C7563);
}

.y3195fbjr {
  stop-color: var(--svg-color--482826, #482826);
}

.y3a3ubcbb {
  stop-color: var(--svg-color--663b39, #663B39);
}

.yioqrj9eg {
  stop-color: var(--svg-color--77405b, #77405B);
}

</style>
