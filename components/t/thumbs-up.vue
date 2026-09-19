<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ixj1Bjd)"><path fill="url(#ityz05d)" class="e2ai06eco"/></g><path fill="url(#i4CTH8b)" class="e2ai06eco"/><path fill="url(#iZuCuIC)" class="e2ai06eco"/><path fill="url(#iKnCuke)" class="e2ai06eco"/><path fill="url(#iHcoLsb)" class="e2ai06eco"/><g filter="url(#ieG5A6b)"><path fill="url(#inivkfd)" class="ohy4jqbmw"/></g><g filter="url(#iH1Tgld)"><rect fill="url(#iPYZLGc)" transform="rotate(90 25.957 10.73)" class="v8ibqcaeo"/><rect fill="url(#iJZyCme)" transform="rotate(90 25.957 10.73)" class="v8ibqcaeo"/></g><g filter="url(#ipOa8ac)"><rect fill="url(#iLOGYHC)" transform="rotate(90 25.657 24.015)" class="p07oq3bel"/><rect fill="url(#ite3kNc)" transform="rotate(90 25.657 24.015)" class="p07oq3bel"/><rect fill="url(#i2H4EuE)" transform="rotate(90 25.657 24.015)" class="p07oq3bel"/></g><rect fill="url(#izfsSgC)" transform="rotate(90 25.657 24.015)" class="p07oq3bel"/><rect fill="url(#iDXbKRd)" transform="rotate(90 25.657 24.015)" class="p07oq3bel"/><g filter="url(#isa9TPd)"><rect fill="url(#iXN6iPd)" class="wdoxaob3r"/></g><rect transform="rotate(90 26.955 19.735)" class="z3npx_frm"/><g filter="url(#iLZTKCe)"><rect fill="url(#ihcVdjb)" transform="rotate(90 26.955 19.735)" class="iwupi3beh"/><rect fill="url(#iVVKwfe)" transform="rotate(90 26.955 19.735)" class="iwupi3beh"/><rect fill="url(#iI1oi7d)" transform="rotate(90 26.955 19.735)" class="iwupi3beh"/></g><g filter="url(#iCeVtue)"><rect fill="url(#iFKZRXd)" class="by14cw_qd"/></g><g filter="url(#ipm0JQP)"><rect fill="url(#izOJTjH)" transform="rotate(90 26.91 15.285)" class="f4oers0gg"/><rect fill="url(#izkdipc)" transform="rotate(90 26.91 15.285)" class="f4oers0gg"/></g><path fill="url(#iRp6dhc)" class="fwpdxpbjc"/><path fill="url(#iTfAwlb)" class="fwpdxpbjc"/><path class="tdmwrvbij"/><path fill="url(#iE5WWgc)" class="hqcl-vzby"/><g filter="url(#i6Fr6Hd)"><rect fill="url(#iUzrVvd)" class="ktasc7zrm"/></g><g filter="url(#iuJcC9b)"><rect fill="url(#iY88EPE)" class="jks6u7z3d"/></g><g filter="url(#i6ag4yc)"><rect fill="url(#idAAzKR)" class="z5vpqeowo"/></g><defs><radialGradient id="i4CTH8b" cx="0" cy="0" r="1" gradientTransform="rotate(141.116 9.365 6.03)scale(5.01564 14.8034)" gradientUnits="userSpaceOnUse"><stop class="lphk9jbzr"/><stop offset="1" class="xee5n8d6p"/></radialGradient><radialGradient id="iZuCuIC" cx="0" cy="0" r="1" gradientTransform="rotate(125.191 1.565 10.819)scale(7.43021 5.38256)" gradientUnits="userSpaceOnUse"><stop class="nb89uyb9s"/><stop offset="1" class="qggtboxli"/></radialGradient><radialGradient id="iKnCuke" cx="0" cy="0" r="1" gradientTransform="matrix(-13.53897 8.8789 -15.5384 -23.69368 19.37 18.131)" gradientUnits="userSpaceOnUse"><stop offset=".681" class="qhwtfhb5a"/><stop offset="1" class="xvszieb-l"/></radialGradient><radialGradient id="iJZyCme" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40872 1.84473 -1.2348 -.94296 31.447 18.303)" gradientUnits="userSpaceOnUse"><stop class="ykqh_glys"/><stop offset="1" class="xmuni2m_c"/></radialGradient><radialGradient id="ite3kNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.31347 2.78222 0 31.32 31.081)" gradientUnits="userSpaceOnUse"><stop class="qj7fahb-k"/><stop offset="1" class="osusk3qff"/></radialGradient><radialGradient id="i2H4EuE" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.4169 1.99096 0 26.65 31.432)" gradientUnits="userSpaceOnUse"><stop class="noi-bdcoy"/><stop offset="1" class="jw0t1zqrv"/></radialGradient><radialGradient id="iDXbKRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.60324 8.4227 0 28.488 34.049)" gradientUnits="userSpaceOnUse"><stop class="yns97uu-r"/><stop offset="1" class="hyh7rnt0z"/></radialGradient><radialGradient id="iVVKwfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.38517 2.92967 0 32.919 27.836)" gradientUnits="userSpaceOnUse"><stop class="qj7fahb-k"/><stop offset="1" class="osusk3qff"/></radialGradient><radialGradient id="iI1oi7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.50376 2.09648 0 28.002 28.239)" gradientUnits="userSpaceOnUse"><stop class="noi-bdcoy"/><stop offset="1" class="jw0t1zqrv"/></radialGradient><radialGradient id="izkdipc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.50067 2.44847 0 32.037 23.307)" gradientUnits="userSpaceOnUse"><stop class="qj7fahb-k"/><stop offset="1" class="osusk3qff"/></radialGradient><radialGradient id="iRp6dhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.36013 -2.36143 0 12.537 4.844)" gradientUnits="userSpaceOnUse"><stop class="wpewydbyx"/><stop offset="1" class="ucm0isb3w"/></radialGradient><radialGradient id="iTfAwlb" cx="0" cy="0" r="1" gradientTransform="matrix(2.32995 2.17252 -3.28739 3.5256 10.68 9.032)" gradientUnits="userSpaceOnUse"><stop class="ogbo-yewc"/><stop offset="1" class="khw1w9bau"/></radialGradient><radialGradient id="iE5WWgc" cx="0" cy="0" r="1" gradientTransform="rotate(-168.366 7.22 1.513)scale(1.63946 3.57849)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="aqcknacdb"/><stop offset="1" class="nhawtwabj"/></radialGradient><linearGradient id="ityz05d" x1="19.254" x2="9.191" y1="6.639" y2="27.827" gradientUnits="userSpaceOnUse"><stop class="aa1yoduhc"/><stop offset="1" class="zo92c5b5h"/></linearGradient><linearGradient id="iHcoLsb" x1="14.19" x2="14.19" y1="25.562" y2="30.663" gradientUnits="userSpaceOnUse"><stop class="rztix1f5s"/><stop offset="1" class="w6h02tb3h"/></linearGradient><linearGradient id="inivkfd" x1="20.1" x2="20.1" y1="12.157" y2="25.445" gradientUnits="userSpaceOnUse"><stop class="is342tcxo"/><stop offset="1" class="xy9jd9uqw"/></linearGradient><linearGradient id="iPYZLGc" x1="28.867" x2="28.867" y1="10.73" y2="19.774" gradientUnits="userSpaceOnUse"><stop class="u_fdktclv"/><stop offset="1" class="daaldshuu"/></linearGradient><linearGradient id="iLOGYHC" x1="28.488" x2="28.488" y1="24.791" y2="32.876" gradientUnits="userSpaceOnUse"><stop class="u_fdktclv"/><stop offset="1" class="daaldshuu"/></linearGradient><linearGradient id="izfsSgC" x1="31.904" x2="30.072" y1="28.446" y2="28.446" gradientUnits="userSpaceOnUse"><stop class="ds4srib7s"/><stop offset="1" class="v7cqpudbj"/></linearGradient><linearGradient id="iXN6iPd" x1="24.713" x2="18.924" y1="26.103" y2="26.103" gradientUnits="userSpaceOnUse"><stop class="h6a-ozyxn"/><stop offset="1" class="evpp02brg"/></linearGradient><linearGradient id="ihcVdjb" x1="29.937" x2="29.937" y1="20.625" y2="29.894" gradientUnits="userSpaceOnUse"><stop class="u_fdktclv"/><stop offset="1" class="daaldshuu"/></linearGradient><linearGradient id="iFKZRXd" x1="25.607" x2="18.359" y1="22.233" y2="22.233" gradientUnits="userSpaceOnUse"><stop class="h6a-ozyxn"/><stop offset="1" class="evpp02brg"/></linearGradient><linearGradient id="izOJTjH" x1="29.826" x2="29.826" y1="15.285" y2="25.398" gradientUnits="userSpaceOnUse"><stop class="u_fdktclv"/><stop offset="1" class="daaldshuu"/></linearGradient><linearGradient id="iUzrVvd" x1="24.673" x2="18.059" y1="12.214" y2="12.214" gradientUnits="userSpaceOnUse"><stop class="h6a-ozyxn"/><stop offset="1" class="evpp02brg"/></linearGradient><linearGradient id="iY88EPE" x1="25.584" x2="17.853" y1="16.69" y2="16.69" gradientUnits="userSpaceOnUse"><stop class="h6a-ozyxn"/><stop offset="1" class="evpp02brg"/></linearGradient><linearGradient id="idAAzKR" x1="17.867" x2="14.778" y1="5.305" y2="5.305" gradientUnits="userSpaceOnUse"><stop class="h6a-ozyxn"/><stop offset="1" class="evpp02brg"/></linearGradient><filter id="ixj1Bjd" width="19.048" height="27.809" x="4.917" y="1.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.458824 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2909"/></filter><filter id="ieG5A6b" width="12.909" height="20.615" x="13.646" y="10.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2909" stdDeviation="1"/></filter><filter id="iH1Tgld" width="9.543" height="5.82" x="16.913" y="10.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2909"/></filter><filter id="ipOa8ac" width="9.361" height="6.164" x="16.796" y="23.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.643137 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2909"/></filter><filter id="isa9TPd" width="7.87" height="3.976" x="18.372" y="24.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2909" stdDeviation=".625"/></filter><filter id="iLZTKCe" width="10.659" height="6.464" x="16.796" y="19.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.643137 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2909"/></filter><filter id="iCeVtue" width="9.225" height="3.976" x="17.982" y="20.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2909" stdDeviation=".625"/></filter><filter id="ipm0JQP" width="10.614" height="6.333" x="16.796" y="14.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.643137 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2909"/></filter><filter id="i6Fr6Hd" width="8.636" height="5.016" x="17.606" y="10.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2909" stdDeviation=".625"/></filter><filter id="iuJcC9b" width="9.672" height="5.016" x="17.535" y="14.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2909" stdDeviation=".625"/></filter><filter id="i6ag4yc" width="5.365" height="10.497" x="13.9" y="1.862" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2909" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:thumbs-up" /></template>
<style>
.aa1yoduhc {
  stop-color: var(--svg-color--ffca44, #FFCA44);
}

.aqcknacdb {
  stop-color: var(--svg-color--ccb28b, #CCB28B);
  stop-opacity: 0;
}

.by14cw_qd {
  width: 6.725px;
  height: 1.476px;
  x: 19.232px;
  y: 21.829px;
  rx: 0.738px;
}

.daaldshuu {
  stop-color: var(--svg-color--f9a928, #F9A928);
}

.ds4srib7s {
  stop-color: var(--svg-color--dc7c6a, #DC7C6A);
}

.e2ai06eco {
  d: path("M12.268 5.158a3.289 3.289 0 1 1 6.577 0v3.785q.001.483-.073.966q-.029.176-.047.352c-.036.37.008.854.26 1.18l-.602.58a9.34 9.34 0 0 1 5.081 8.326a9.4 9.4 0 0 1-.432 2.825l-.997 6.507h-8.101v-.003c-5.003-.108-9.017-3.37-9.017-9.33c0-3.502 1.677-6.322 4.214-7.912l-.006-.005c.173-.12.377-.243.595-.374h.002c.72-.432 1.6-.96 2.063-1.822c.403-.747.48-1.96.48-2.523h.003z");
}

.evpp02brg {
  stop-color: var(--svg-color--fff166, #FFF166);
  stop-opacity: 0;
}

.f4oers0gg {
  width: 5.833px;
  height: 10.114px;
  x: 26.909px;
  y: 15.285px;
  rx: 2.91px;
}

.ft5dv1b6b {
  fill: none;
}

.fwpdxpbjc {
  d: path("M15.556 1.87a3.29 3.29 0 0 0-3.288 3.288v2.553l-.002-.001c0 .562-.078 1.776-.48 2.523c-.465.863-1.344 1.39-2.064 1.821c-.22.132-.424.254-.597.374c.995.797 3.032 2.39 3.082 2.352a363 363 0 0 1 3.484-1.86l-.048-.69a3.29 3.29 0 0 0 3.202-3.287V5.158a3.29 3.29 0 0 0-3.289-3.288");
}

.h6a-ozyxn {
  stop-color: var(--svg-color--fff166, #FFF166);
}

.hqcl-vzby {
  d: path("M13.476 2.611a3.28 3.28 0 0 0-1.208 2.547v.192h1.486a6.4 6.4 0 0 0-.086-1.148l-.017-.091c-.082-.448-.176-.96-.175-1.5");
}

.hyh7rnt0z {
  stop-color: var(--svg-color--e38811, #E38811);
  stop-opacity: 0;
}

.is342tcxo {
  stop-color: var(--svg-color--d1730b, #D1730B);
}

.iwupi3beh {
  width: 5.964px;
  height: 10.159px;
  x: 26.955px;
  y: 19.735px;
  rx: 2.91px;
}

.jks6u7z3d {
  width: 7.172px;
  height: 2.516px;
  x: 18.785px;
  y: 16px;
  rx: 1.258px;
}

.jw0t1zqrv {
  stop-color: var(--svg-color--ffb610, #FFB610);
  stop-opacity: 0;
}

.khw1w9bau {
  stop-color: var(--svg-color--cda25e, #CDA25E);
  stop-opacity: 0;
}

.ktasc7zrm {
  width: 6.136px;
  height: 2.516px;
  x: 18.856px;
  y: 11.524px;
  rx: 1.258px;
}

.lphk9jbzr {
  stop-color: var(--svg-color--ffe34c, #FFE34C);
}

.nb89uyb9s {
  stop-color: var(--svg-color--ffca2e, #FFCA2E);
}

.nhawtwabj {
  stop-color: var(--svg-color--ccb28b, #CCB28B);
}

.noi-bdcoy {
  stop-color: var(--svg-color--da810b, #DA810B);
}

.ogbo-yewc {
  stop-color: var(--svg-color--cda25e, #CDA25E);
}

.ohy4jqbmw {
  d: path("M23.679 14.709a2.55 2.55 0 0 0-2.552-2.552h-2.826a2.552 2.552 0 0 0-1.638 4.509a2.557 2.557 0 0 0-.116 3.992a2.55 2.55 0 0 0-.901 1.947v.125c0 .7.28 1.333.736 1.794a2.483 2.483 0 0 0 1.746 4.248h2.804a2.483 2.483 0 0 0 2.15-3.728a2.55 2.55 0 0 0 1.472-2.314v-.125c0-.79-.358-1.496-.922-1.964a2.56 2.56 0 0 0-.587-4.249a2.54 2.54 0 0 0 .634-1.683");
}

.osusk3qff {
  stop-color: var(--svg-color--f29545, #F29545);
  stop-opacity: 0;
}

.p07oq3bel {
  width: 5.664px;
  height: 8.861px;
  x: 25.657px;
  y: 24.015px;
  rx: 2.832px;
}

.qggtboxli {
  stop-color: var(--svg-color--ffca2e, #FFCA2E);
  stop-opacity: 0;
}

.qhwtfhb5a {
  stop-color: var(--svg-color--e18e3f, #E18E3F);
  stop-opacity: 0;
}

.qj7fahb-k {
  stop-color: var(--svg-color--f29545, #F29545);
}

.rztix1f5s {
  stop-color: var(--svg-color--d8796f, #D8796F);
  stop-opacity: 0;
}

.tdmwrvbij {
  fill: var(--svg-color--ffbf71, #FFBF71);
  d: path("M13.476 2.611a3.28 3.28 0 0 0-1.208 2.547v.192h1.486a6.4 6.4 0 0 0-.086-1.148l-.017-.091c-.082-.448-.176-.96-.175-1.5");
}

.u_fdktclv {
  stop-color: var(--svg-color--ffdb44, #FFDB44);
}

.ucm0isb3w {
  stop-color: var(--svg-color--f3a52a, #F3A52A);
  stop-opacity: 0;
}

.v7cqpudbj {
  stop-color: var(--svg-color--dc7c6a, #DC7C6A);
  stop-opacity: 0;
}

.v8ibqcaeo {
  width: 5.82px;
  height: 9.043px;
  x: 25.957px;
  y: 10.73px;
  rx: 2.91px;
}

.w6h02tb3h {
  stop-color: var(--svg-color--d8796f, #D8796F);
}

.wdoxaob3r {
  width: 5.37px;
  height: 1.476px;
  x: 19.622px;
  y: 25.699px;
  rx: 0.738px;
}

.wpewydbyx {
  stop-color: var(--svg-color--f3a52a, #F3A52A);
}

.xee5n8d6p {
  stop-color: var(--svg-color--ffe34c, #FFE34C);
  stop-opacity: 0;
}

.xmuni2m_c {
  stop-color: var(--svg-color--d98320, #D98320);
  stop-opacity: 0;
}

.xvszieb-l {
  stop-color: var(--svg-color--e18e3f, #E18E3F);
}

.xy9jd9uqw {
  stop-color: var(--svg-color--e27d47, #E27D47);
}

.ykqh_glys {
  stop-color: var(--svg-color--d98320, #D98320);
}

.yns97uu-r {
  stop-color: var(--svg-color--e38811, #E38811);
}

.z3npx_frm {
  width: 5.964px;
  height: 10.159px;
  x: 26.955px;
  y: 19.735px;
  fill: var(--svg-color--c4c4c4, #C4C4C4);
  fill-opacity: var(--svg-fill-opacity--0-66, 0.66);
  rx: 2.982px;
}

.z5vpqeowo {
  width: 2.865px;
  height: 7.997px;
  x: 15.15px;
  y: 3.112px;
  rx: 1.433px;
}

.zo92c5b5h {
  stop-color: var(--svg-color--f8a528, #F8A528);
}

</style>
