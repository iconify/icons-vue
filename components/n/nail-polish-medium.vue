<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iJ9WZ2c)" class="sq7f8ubae"/><path fill="url(#iEt6xdL)" class="sq7f8ubae"/><path fill="url(#iyw4Hre)" class="sq7f8ubae"/><path fill="url(#iw4JCQc)" class="q9athqbmo"/><path fill="url(#i2y1UVc)" class="q9athqbmo"/><path fill="url(#iEGrxab)" class="q9athqbmo"/><g filter="url(#i2FfUkc)"><path class="nhq2od9_y"/></g><path fill="url(#i0xsz4d)" class="zppdw8bsm"/><path fill="url(#iU8AFod)" class="zppdw8bsm"/><path fill="url(#i2t8fCd)" class="zppdw8bsm"/><g filter="url(#ipOozzb)"><path class="vezs9bbou"/></g><g filter="url(#i0GgqPz)"><path class="jvvvfh74o"/></g><g filter="url(#ivUKTOc)"><path fill="url(#i6HCczc)" class="mgbnx5e4n"/></g><g filter="url(#iqBA9xe)"><path fill="url(#imy8Pob)" class="f812ambgt"/></g><g filter="url(#ipfOTfd)"><path fill="url(#iXxuEWb)" class="k3u1_8jwh"/></g><path fill="url(#iKz3cDd)" class="sv8tenb0u"/><path fill="url(#i0HsOSd)" class="wejjc0b2m"/><path fill="url(#itAQqEc)" class="wejjc0b2m"/><path fill="url(#imcu1lb)" class="wswmq3b9g"/><path fill="url(#iilyrNU)" class="wswmq3b9g"/><path fill="url(#iDQCSLd)" class="wswmq3b9g"/><path fill="url(#i2m008c)" class="wswmq3b9g"/><path fill="url(#iq5FDrc)" class="fix-e51fa"/><g filter="url(#i7fSCNd)"><path stroke="url(#iPU07pD)" class="xcrwndl2x"/></g><g filter="url(#i26luqb)"><path stroke="url(#iCEMRPc)" class="vvdh2vbxz"/></g><g filter="url(#iIS01Qd)"><path stroke="url(#i2xzySb)" class="ceu8-bbke"/></g><g filter="url(#i14L2Qc)"><path stroke="url(#iNFtyBc)" class="l1vouxb_t"/></g><g filter="url(#iUgGukR)"><path stroke="url(#is5Cc7c)" class="jdigj6b0e"/></g><defs><linearGradient id="iJ9WZ2c" x1="16.188" x2="20.313" y1="21.625" y2="26.375" gradientUnits="userSpaceOnUse"><stop class="dreia_slh"/><stop offset="1" class="mawnvmblk"/></linearGradient><linearGradient id="iEt6xdL" x1="22.729" x2="21.464" y1="27.453" y2="26.156" gradientUnits="userSpaceOnUse"><stop offset=".052" class="q8bprqbvo"/><stop offset="1" class="oe9sqgghd"/></linearGradient><linearGradient id="iw4JCQc" x1="7.5" x2="11.375" y1="14.625" y2="18.75" gradientUnits="userSpaceOnUse"><stop class="yi6o7vaed"/><stop offset="1" class="ur6qzhb5b"/></linearGradient><linearGradient id="i2y1UVc" x1="11.891" x2="10.986" y1="20.178" y2="19.256" gradientUnits="userSpaceOnUse"><stop class="m6wrivj2u"/><stop offset="1" class="mmop06f6b"/></linearGradient><linearGradient id="i0xsz4d" x1="11.438" x2="15.5" y1="17.75" y2="22.125" gradientUnits="userSpaceOnUse"><stop class="mz_pbgb6v"/><stop offset="1" class="yk_5kub0s"/></linearGradient><linearGradient id="iU8AFod" x1="16.984" x2="15.844" y1="23.75" y2="22.594" gradientUnits="userSpaceOnUse"><stop offset=".168" class="nk_3gujzc"/><stop offset="1" class="oaxipr_1e"/></linearGradient><linearGradient id="i6HCczc" x1="11.761" x2="15.806" y1="14.5" y2="10.396" gradientUnits="userSpaceOnUse"><stop class="jnoylobpn"/><stop offset="1" class="kvylnhzzr"/></linearGradient><linearGradient id="imy8Pob" x1="16.111" x2="20.156" y1="18.49" y2="14.386" gradientUnits="userSpaceOnUse"><stop class="jnoylobpn"/><stop offset="1" class="kvylnhzzr"/></linearGradient><linearGradient id="iXxuEWb" x1="20.101" x2="24.146" y1="22.84" y2="18.736" gradientUnits="userSpaceOnUse"><stop class="jnoylobpn"/><stop offset="1" class="kvylnhzzr"/></linearGradient><linearGradient id="iKz3cDd" x1="27.776" x2="26.363" y1="9.672" y2="9.172" gradientUnits="userSpaceOnUse"><stop class="vm4647fep"/><stop offset="1" class="f3ksyacap"/></linearGradient><linearGradient id="imcu1lb" x1="25.136" x2="30.352" y1="3.781" y2="4.344" gradientUnits="userSpaceOnUse"><stop class="c7zx3cksj"/><stop offset=".745" class="g6u09qa-r"/><stop offset="1" class="we1rycbkb"/></linearGradient><linearGradient id="iilyrNU" x1="27.64" x2="27.64" y1="6.141" y2="5.749" gradientUnits="userSpaceOnUse"><stop class="zgdheybwc"/><stop offset="1" class="nbwwmb4dc"/></linearGradient><linearGradient id="iDQCSLd" x1="28.229" x2="28.229" y1="1.969" y2="2.5" gradientUnits="userSpaceOnUse"><stop class="aq44g_bhz"/><stop offset="1" class="h7irysb4b"/></linearGradient><linearGradient id="i2m008c" x1="25.24" x2="25.683" y1="5.026" y2="5.078" gradientUnits="userSpaceOnUse"><stop class="cl2qvmb0f"/><stop offset="1" class="sos54zbse"/></linearGradient><linearGradient id="iq5FDrc" x1="27.167" x2="26.542" y1="2.67" y2="5.969" gradientUnits="userSpaceOnUse"><stop class="g-kz03upj"/><stop offset="1" class="tn_gpqb-m"/></linearGradient><linearGradient id="iPU07pD" x1="30.058" x2="27.726" y1="2.522" y2="2.351" gradientUnits="userSpaceOnUse"><stop class="hb662vr6x"/><stop offset="1" class="nca8yqbjd"/></linearGradient><linearGradient id="iCEMRPc" x1="27.276" x2="26.822" y1="10.281" y2="6.844" gradientUnits="userSpaceOnUse"><stop class="emrf7fbkb"/><stop offset="1" class="vtyb507lt"/></linearGradient><filter id="i2FfUkc" width="6.017" height="4.554" x="19.497" y="19.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5972" stdDeviation=".125"/></filter><filter id="ipOozzb" width="6.072" height="5.32" x="11.102" y="10.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5972" stdDeviation=".125"/></filter><filter id="i0GgqPz" width="6.913" height="5.32" x="15.486" y="13.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5972" stdDeviation=".125"/></filter><filter id="ivUKTOc" width="6.718" height="7.632" x="11.275" y="7.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.474597 0 0 0 0 0.295208 0 0 0 0 0.65 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5972"/></filter><filter id="iqBA9xe" width="6.718" height="7.632" x="15.625" y="11.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.474597 0 0 0 0 0.295208 0 0 0 0 0.65 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5972"/></filter><filter id="ipfOTfd" width="6.718" height="7.632" x="19.615" y="15.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.474597 0 0 0 0 0.295208 0 0 0 0 0.65 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5972"/></filter><filter id="i7fSCNd" width="2.813" height=".75" x="27.362" y="2.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5972" stdDeviation=".125"/></filter><filter id="i26luqb" width=".863" height="3.317" x="26.638" y="6.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5972" stdDeviation=".075"/></filter><filter id="iIS01Qd" width="1.142" height="3.855" x="16.774" y="8.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5972" stdDeviation=".05"/></filter><filter id="i14L2Qc" width="1.142" height="3.855" x="21.157" y="12.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5972" stdDeviation=".05"/></filter><filter id="iUgGukR" width="1.142" height="3.855" x="25.114" y="16.404" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5972" stdDeviation=".05"/></filter><radialGradient id="iyw4Hre" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 3.4375 -2.98 -1.00236 25.854 20.406)" gradientUnits="userSpaceOnUse"><stop class="b5e_facvp"/><stop offset="1" class="wj0_vcbzm"/></radialGradient><radialGradient id="iEGrxab" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56248 2.50001 -1.9557 -1.2223 17.136 12.156)" gradientUnits="userSpaceOnUse"><stop class="yrfobccjy"/><stop offset="1" class="y9fhw5bke"/></radialGradient><radialGradient id="i2t8fCd" cx="0" cy="0" r="1" gradientTransform="rotate(116.764 6.778 14.322)scale(3.63874 3.16524)" gradientUnits="userSpaceOnUse"><stop class="xtqg5_k8b"/><stop offset="1" class="h0w3-36bh"/></radialGradient><radialGradient id="i0HsOSd" cx="0" cy="0" r="1" gradientTransform="matrix(1.9375 -1.8125 1.05096 1.12344 24.73 13.156)" gradientUnits="userSpaceOnUse"><stop class="a9v_6_b1o"/><stop offset="1" class="bssbofdfc"/></radialGradient><radialGradient id="itAQqEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4132 .37061 -.85081 3.2443 24.813 10.52)" gradientUnits="userSpaceOnUse"><stop class="tojlolbvi"/><stop offset="1" class="dg1c6wbtb"/></radialGradient><radialGradient id="i2xzySb" cx="0" cy="0" r="1" gradientTransform="matrix(1.71876 -.47656 13.3473 48.13857 16.752 10.398)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="b7o2e9b5s"/><stop offset=".928" class="kjz5qz64y"/></radialGradient><radialGradient id="iNFtyBc" cx="0" cy="0" r="1" gradientTransform="matrix(1.71876 -.47656 13.3473 48.13857 21.135 14.328)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="b7o2e9b5s"/><stop offset=".928" class="kjz5qz64y"/></radialGradient><radialGradient id="is5Cc7c" cx="0" cy="0" r="1" gradientTransform="matrix(1.71876 -.47656 13.3473 48.13857 25.092 18.703)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="b7o2e9b5s"/><stop offset=".928" class="kjz5qz64y"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:nail-polish-medium" /></template>
<style>
.a9v_6_b1o {
  stop-color: var(--svg-color--a843b3, #A843B3);
}

.aq44g_bhz {
  stop-color: var(--svg-color--9774c5, #9774C5);
}

.b5e_facvp {
  stop-color: var(--svg-color--c9a18c, #C9A18C);
}

.b7o2e9b5s {
  stop-color: var(--svg-color--b68fde, #B68FDE);
  stop-opacity: 0;
}

.bssbofdfc {
  stop-color: var(--svg-color--a16bed, #A16BED);
}

.c7zx3cksj {
  stop-color: var(--svg-color--9361c0, #9361C0);
}

.ceu8-bbke {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.304 8.25c.62.844.727 2.406-.38 3.555");
}

.cl2qvmb0f {
  stop-color: var(--svg-color--8a6aa9, #8A6AA9);
}

.dg1c6wbtb {
  stop-color: var(--svg-color--885aa8, #885AA8);
  stop-opacity: 0;
}

.dreia_slh {
  stop-color: var(--svg-color--7c5140, #7C5140);
}

.emrf7fbkb {
  stop-color: var(--svg-color--63497a, #63497A);
}

.f3ksyacap {
  stop-color: var(--svg-color--4a285a, #4A285A);
}

.f812ambgt {
  d: path("M16.203 18.39c-.77-.77-.77-2.01 0-2.78l4.02-4.02c.34-.34.88-.34 1.22 0c1.2 1.2 1.2 3.14 0 4.34l-2.46 2.46c-.77.77-2.01.77-2.78 0");
}

.fix-e51fa {
  d: path("M26.524 2.991a.394.394 0 1 1 .774.145l-.375 1.995a.394.394 0 1 1-.774-.145z");
}

.ft5dv1b6b {
  fill: none;
}

.g-kz03upj {
  stop-color: var(--svg-color--fcd0ff, #FCD0FF);
}

.g6u09qa-r {
  stop-color: var(--svg-color--b07af9, #B07AF9);
}

.h0w3-36bh {
  stop-color: var(--svg-color--c6a08d, #C6A08D);
  stop-opacity: 0;
}

.h7irysb4b {
  stop-color: var(--svg-color--9774c5, #9774C5);
  stop-opacity: 0;
}

.hb662vr6x {
  stop-color: var(--svg-color--c197fd, #C197FD);
}

.jdigj6b0e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M25.644 16.554c.62.844.727 2.407-.38 3.555");
}

.jnoylobpn {
  stop-color: var(--svg-color--9f4db5, #9F4DB5);
}

.jvvvfh74o {
  fill: var(--svg-color--673c37, #673C37);
  d: path("M16.29 15.828a1.885 1.885 0 0 0 0 2.67c.74.74 1.932.74 2.671 0l2.06-2.078c1.236-1.2 1.041-1.91 1.128-2.026c-.137-.374-1.197.968-1.497.668a2.84 2.84 0 0 0-2.947-.668z");
}

.k3u1_8jwh {
  d: path("M20.193 22.74c-.77-.77-.77-2.01 0-2.78l4.02-4.02c.34-.34.88-.34 1.22 0c1.2 1.2 1.2 3.14 0 4.34l-2.46 2.46c-.77.77-2.01.77-2.78 0");
}

.kjz5qz64y {
  stop-color: var(--svg-color--b68fde, #B68FDE);
}

.kvylnhzzr {
  stop-color: var(--svg-color--875abb, #875ABB);
}

.l1vouxb_t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M21.687 12.179c.62.844.727 2.407-.38 3.555");
}

.m6wrivj2u {
  stop-color: var(--svg-color--694637, #694637);
}

.mawnvmblk {
  stop-color: var(--svg-color--b98581, #B98581);
}

.mgbnx5e4n {
  d: path("M11.853 14.4c-.77-.77-.77-2.01 0-2.78l4.02-4.02c.34-.34.88-.34 1.22 0c1.2 1.2 1.2 3.14 0 4.34l-2.46 2.46c-.77.77-2.01.77-2.78 0");
}

.mmop06f6b {
  stop-color: var(--svg-color--694637, #694637);
  stop-opacity: 0;
}

.mz_pbgb6v {
  stop-color: var(--svg-color--845b4a, #845B4A);
}

.nbwwmb4dc {
  stop-color: var(--svg-color--944eea, #944EEA);
  stop-opacity: 0;
}

.nca8yqbjd {
  stop-color: var(--svg-color--c197fd, #C197FD);
  stop-opacity: 0;
}

.nhq2od9_y {
  fill: var(--svg-color--673c37, #673C37);
  d: path("M20.302 20.15c-.74.74-.74 1.931 0 2.67c.74.74 1.931.74 2.67 0l1.642-1.593c1.237-1.2.313-1.484.4-1.6c-.138-.374-.692.823-.992.523a2.84 2.84 0 0 0-2.947-.667z");
}

.nk_3gujzc {
  stop-color: var(--svg-color--754b3f, #754B3F);
}

.oaxipr_1e {
  stop-color: var(--svg-color--754b3f, #754B3F);
  stop-opacity: 0;
}

.oe9sqgghd {
  stop-color: var(--svg-color--ae7d8c, #AE7D8C);
  stop-opacity: 0;
}

.q8bprqbvo {
  stop-color: var(--svg-color--ae7d8c, #AE7D8C);
}

.q9athqbmo {
  d: path("m2.362 29.45l14.12-14.12a2.95 2.95 0 0 0 0-4.17a2.95 2.95 0 0 0-4.17 0l-9.95 9.96z");
}

.sos54zbse {
  stop-color: var(--svg-color--8a6aa9, #8A6AA9);
  stop-opacity: 0;
}

.sq7f8ubae {
  d: path("M24.823 19.5a2.95 2.95 0 0 0-4.17 0L10.153 30h8.34l6.33-6.33a2.95 2.95 0 0 0 0-4.17");
}

.sv8tenb0u {
  d: path("m26.923 4.94l-.688 3.974a.28.28 0 0 1-.218.218a1.55 1.55 0 0 0-1.194 1.398h3.08a1.55 1.55 0 0 0-.432-.964c-.175-.18-.3-.42-.257-.668l.689-3.958z");
}

.tn_gpqb-m {
  stop-color: var(--svg-color--fcd0ff, #FCD0FF);
  stop-opacity: 0;
}

.tojlolbvi {
  stop-color: var(--svg-color--885aa8, #885AA8);
}

.ur6qzhb5b {
  stop-color: var(--svg-color--b6857f, #B6857F);
}

.vezs9bbou {
  fill: var(--svg-color--7f4f65, #7F4F65);
  d: path("M11.907 11.926c-.74.74-.74 1.93 0 2.67s1.931.74 2.67 0l2.06-2.078a3 3 0 0 0 .287-.333a2.835 2.835 0 0 0-3.603-1.693z");
}

.vm4647fep {
  stop-color: var(--svg-color--63487e, #63487E);
}

.vtyb507lt {
  stop-color: var(--svg-color--63497a, #63497A);
  stop-opacity: 0;
}

.vvdh2vbxz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m27.276 6.688l-.395 2.11a1 1 0 0 0 .14.723l.02.034");
}

.we1rycbkb {
  stop-color: var(--svg-color--a07ddf, #A07DDF);
}

.wejjc0b2m {
  d: path("M24.822 10.53v.5c0 .83-.15 1.41-.27 1.73c-.05.15.06.31.22.31c1.365 0 3.14-1.024 3.14-2.55h-3.09z");
}

.wj0_vcbzm {
  stop-color: var(--svg-color--c9a18c, #C9A18C);
  stop-opacity: 0;
}

.wswmq3b9g {
  d: path("M25.519 2.428a.5.5 0 0 1 .49-.406h3.843a.5.5 0 0 1 .49.594l-.58 3.024a.5.5 0 0 1-.492.406h-3.842a.5.5 0 0 1-.491-.595z");
}

.xcrwndl2x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M27.737 2.469H29.8");
}

.xtqg5_k8b {
  stop-color: var(--svg-color--c6a08d, #C6A08D);
}

.y9fhw5bke {
  stop-color: var(--svg-color--bf9887, #BF9887);
  stop-opacity: 0;
}

.yi6o7vaed {
  stop-color: var(--svg-color--8e715d, #8E715D);
}

.yk_5kub0s {
  stop-color: var(--svg-color--b6837f, #B6837F);
}

.yrfobccjy {
  stop-color: var(--svg-color--bf9887, #BF9887);
}

.zgdheybwc {
  stop-color: var(--svg-color--944eea, #944EEA);
}

.zppdw8bsm {
  d: path("M22.043 13.94a2.95 2.95 0 0 0-4.17 0L2.362 29.45V30h7.79l11.89-11.89a2.95 2.95 0 0 0 0-4.17");
}

</style>
