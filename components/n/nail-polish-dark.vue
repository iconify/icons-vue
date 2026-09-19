<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iCeQv5d)" class="sq7f8ubae"/><path fill="url(#iwUYbUb)" class="sq7f8ubae"/><path fill="url(#izqhasc)" class="sq7f8ubae"/><path fill="url(#ie02Lub)" class="q9athqbmo"/><path fill="url(#iKjOA5b)" class="q9athqbmo"/><path fill="url(#ik5oaUd)" class="q9athqbmo"/><g filter="url(#iFQRFFd)"><path class="hnvoafffu"/></g><path fill="url(#i3mQ9Fb)" class="zppdw8bsm"/><path fill="url(#iytDccd)" class="zppdw8bsm"/><path fill="url(#ijSOvdb)" class="zppdw8bsm"/><g filter="url(#imnXozd)"><path class="mz5t27b8z"/></g><g filter="url(#iwlEJvd)"><path class="zghepjbnl"/></g><g filter="url(#iy8wSMb)"><path fill="url(#iWEYY9c)" class="mgbnx5e4n"/></g><g filter="url(#i7x9Gkc)"><path fill="url(#iwwG7gd)" class="f812ambgt"/></g><g filter="url(#ihEILiK)"><path fill="url(#iKGB0Qd)" class="k3u1_8jwh"/></g><path fill="url(#iKz3cDd)" class="sv8tenb0u"/><path fill="url(#i0HsOSd)" class="wejjc0b2m"/><path fill="url(#itAQqEc)" class="wejjc0b2m"/><path fill="url(#imcu1lb)" class="wswmq3b9g"/><path fill="url(#iilyrNU)" class="wswmq3b9g"/><path fill="url(#iDQCSLd)" class="wswmq3b9g"/><path fill="url(#iq5FDrc)" class="fix-e51fa"/><g filter="url(#ipBlQNd)"><path stroke="url(#iPU07pD)" class="xcrwndl2x"/></g><g filter="url(#iAi2IPV)"><path stroke="url(#iCEMRPc)" class="vvdh2vbxz"/></g><g filter="url(#i35QtBe)"><path stroke="url(#i2xzySb)" class="ceu8-bbke"/></g><g filter="url(#icVdSRr)"><path stroke="url(#iNFtyBc)" class="l1vouxb_t"/></g><g filter="url(#idjsLyd)"><path stroke="url(#is5Cc7c)" class="jdigj6b0e"/></g><defs><linearGradient id="iCeQv5d" x1="16.386" x2="18.854" y1="22.531" y2="25.094" gradientUnits="userSpaceOnUse"><stop class="bns21slrd"/><stop offset="1" class="mrapryg6g"/></linearGradient><linearGradient id="iwUYbUb" x1="22.729" x2="21.464" y1="27.453" y2="26.156" gradientUnits="userSpaceOnUse"><stop offset=".052" class="c6-94vbwc"/><stop offset="1" class="k3vhuof5y"/></linearGradient><linearGradient id="ie02Lub" x1="8.136" x2="10.21" y1="15.688" y2="17.769" gradientUnits="userSpaceOnUse"><stop class="d271c5pvt"/><stop offset="1" class="x9eopbbkh"/></linearGradient><linearGradient id="iKjOA5b" x1="11.891" x2="10.986" y1="20.178" y2="19.256" gradientUnits="userSpaceOnUse"><stop class="s8mjdcbzp"/><stop offset="1" class="vtjxhabnn"/></linearGradient><linearGradient id="i3mQ9Fb" x1="11.354" x2="14.136" y1="17.969" y2="21" gradientUnits="userSpaceOnUse"><stop class="eyld6bcsl"/><stop offset="1" class="x9eopbbkh"/></linearGradient><linearGradient id="iytDccd" x1="16.807" x2="15.868" y1="23.582" y2="22.64" gradientUnits="userSpaceOnUse"><stop offset=".052" class="qw6b0obtg"/><stop offset="1" class="dfrf4w9wg"/></linearGradient><linearGradient id="iWEYY9c" x1="11.761" x2="17.511" y1="14.5" y2="8.75" gradientUnits="userSpaceOnUse"><stop class="amm6xmmaz"/><stop offset="1" class="ymfuz3h0p"/></linearGradient><linearGradient id="iwwG7gd" x1="16.111" x2="21.861" y1="18.49" y2="12.74" gradientUnits="userSpaceOnUse"><stop class="amm6xmmaz"/><stop offset="1" class="ymfuz3h0p"/></linearGradient><linearGradient id="iKGB0Qd" x1="20.101" x2="25.851" y1="22.84" y2="17.09" gradientUnits="userSpaceOnUse"><stop class="amm6xmmaz"/><stop offset="1" class="ymfuz3h0p"/></linearGradient><linearGradient id="iKz3cDd" x1="27.776" x2="26.363" y1="9.672" y2="9.172" gradientUnits="userSpaceOnUse"><stop class="vm4647fep"/><stop offset="1" class="f3ksyacap"/></linearGradient><linearGradient id="imcu1lb" x1="25.136" x2="30.352" y1="3.781" y2="4.344" gradientUnits="userSpaceOnUse"><stop class="c7zx3cksj"/><stop offset=".745" class="g6u09qa-r"/><stop offset="1" class="we1rycbkb"/></linearGradient><linearGradient id="iilyrNU" x1="27.64" x2="27.64" y1="6.141" y2="5.749" gradientUnits="userSpaceOnUse"><stop class="zgdheybwc"/><stop offset="1" class="nbwwmb4dc"/></linearGradient><linearGradient id="iDQCSLd" x1="28.229" x2="28.229" y1="1.969" y2="2.5" gradientUnits="userSpaceOnUse"><stop class="aq44g_bhz"/><stop offset="1" class="h7irysb4b"/></linearGradient><linearGradient id="iq5FDrc" x1="27.167" x2="26.542" y1="2.67" y2="5.969" gradientUnits="userSpaceOnUse"><stop class="g-kz03upj"/><stop offset="1" class="tn_gpqb-m"/></linearGradient><linearGradient id="iPU07pD" x1="30.058" x2="27.726" y1="2.522" y2="2.351" gradientUnits="userSpaceOnUse"><stop class="hb662vr6x"/><stop offset="1" class="nca8yqbjd"/></linearGradient><linearGradient id="iCEMRPc" x1="27.276" x2="26.822" y1="10.281" y2="6.844" gradientUnits="userSpaceOnUse"><stop class="emrf7fbkb"/><stop offset="1" class="vtyb507lt"/></linearGradient><filter id="iFQRFFd" width="6.017" height="4.554" x="19.365" y="19.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5934" stdDeviation=".125"/></filter><filter id="imnXozd" width="6.072" height="5.32" x="11.15" y="10.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5934" stdDeviation=".125"/></filter><filter id="iwlEJvd" width="6.913" height="5.32" x="15.485" y="14.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5934" stdDeviation=".125"/></filter><filter id="iy8wSMb" width="6.718" height="7.632" x="11.275" y="7.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.474597 0 0 0 0 0.295208 0 0 0 0 0.65 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5934"/></filter><filter id="i7x9Gkc" width="6.718" height="7.632" x="15.625" y="11.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.474597 0 0 0 0 0.295208 0 0 0 0 0.65 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5934"/></filter><filter id="ihEILiK" width="6.718" height="7.632" x="19.615" y="15.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.474597 0 0 0 0 0.295208 0 0 0 0 0.65 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5934"/></filter><filter id="ipBlQNd" width="2.813" height=".75" x="27.362" y="2.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5934" stdDeviation=".125"/></filter><filter id="iAi2IPV" width=".863" height="3.317" x="26.638" y="6.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5934" stdDeviation=".075"/></filter><filter id="i35QtBe" width="1.142" height="3.855" x="16.774" y="8.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5934" stdDeviation=".05"/></filter><filter id="icVdSRr" width="1.142" height="3.855" x="21.157" y="12.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5934" stdDeviation=".05"/></filter><filter id="idjsLyd" width="1.142" height="3.855" x="25.114" y="16.404" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5934" stdDeviation=".05"/></filter><radialGradient id="izqhasc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 3.4375 -2.98 -1.00236 25.854 20.406)" gradientUnits="userSpaceOnUse"><stop class="vy3a6n4ty"/><stop offset="1" class="vscc-5lzn"/></radialGradient><radialGradient id="ik5oaUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56248 2.50001 -1.9557 -1.2223 17.136 12.156)" gradientUnits="userSpaceOnUse"><stop class="qu-d_ya5h"/><stop offset="1" class="ni_yscb0i"/></radialGradient><radialGradient id="ijSOvdb" cx="0" cy="0" r="1" gradientTransform="rotate(116.764 6.778 14.322)scale(3.63874 3.16524)" gradientUnits="userSpaceOnUse"><stop class="f6tprvbek"/><stop offset="1" class="dy5hzybvf"/></radialGradient><radialGradient id="i0HsOSd" cx="0" cy="0" r="1" gradientTransform="matrix(1.9375 -1.8125 1.05096 1.12344 24.73 13.156)" gradientUnits="userSpaceOnUse"><stop class="a9v_6_b1o"/><stop offset="1" class="bssbofdfc"/></radialGradient><radialGradient id="itAQqEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4132 .37061 -.85081 3.2443 24.813 10.52)" gradientUnits="userSpaceOnUse"><stop class="tojlolbvi"/><stop offset="1" class="dg1c6wbtb"/></radialGradient><radialGradient id="i2xzySb" cx="0" cy="0" r="1" gradientTransform="matrix(1.71876 -.47656 13.3473 48.13857 16.752 10.398)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="b7o2e9b5s"/><stop offset=".928" class="kjz5qz64y"/></radialGradient><radialGradient id="iNFtyBc" cx="0" cy="0" r="1" gradientTransform="matrix(1.71876 -.47656 13.3473 48.13857 21.135 14.328)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="b7o2e9b5s"/><stop offset=".928" class="kjz5qz64y"/></radialGradient><radialGradient id="is5Cc7c" cx="0" cy="0" r="1" gradientTransform="matrix(1.71876 -.47656 13.3473 48.13857 25.092 18.703)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="b7o2e9b5s"/><stop offset=".928" class="kjz5qz64y"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:nail-polish-dark" /></template>
<style>
.a9v_6_b1o {
  stop-color: var(--svg-color--a843b3, #A843B3);
}

.amm6xmmaz {
  stop-color: var(--svg-color--9a4da9, #9A4DA9);
}

.aq44g_bhz {
  stop-color: var(--svg-color--9774c5, #9774C5);
}

.b7o2e9b5s {
  stop-color: var(--svg-color--b68fde, #B68FDE);
  stop-opacity: 0;
}

.bns21slrd {
  stop-color: var(--svg-color--372020, #372020);
}

.bssbofdfc {
  stop-color: var(--svg-color--a16bed, #A16BED);
}

.c6-94vbwc {
  stop-color: var(--svg-color--56404e, #56404E);
}

.c7zx3cksj {
  stop-color: var(--svg-color--9361c0, #9361C0);
}

.ceu8-bbke {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.304 8.25c.62.844.727 2.406-.38 3.555");
}

.d271c5pvt {
  stop-color: var(--svg-color--43312e, #43312E);
}

.dfrf4w9wg {
  stop-color: var(--svg-color--1b0b0c, #1B0B0C);
  stop-opacity: 0;
}

.dg1c6wbtb {
  stop-color: var(--svg-color--885aa8, #885AA8);
  stop-opacity: 0;
}

.dy5hzybvf {
  stop-color: var(--svg-color--5f4e4d, #5F4E4D);
  stop-opacity: 0;
}

.emrf7fbkb {
  stop-color: var(--svg-color--63497a, #63497A);
}

.eyld6bcsl {
  stop-color: var(--svg-color--301b19, #301B19);
}

.f3ksyacap {
  stop-color: var(--svg-color--4a285a, #4A285A);
}

.f6tprvbek {
  stop-color: var(--svg-color--5f4e4d, #5F4E4D);
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

.h7irysb4b {
  stop-color: var(--svg-color--9774c5, #9774C5);
  stop-opacity: 0;
}

.hb662vr6x {
  stop-color: var(--svg-color--c197fd, #C197FD);
}

.hnvoafffu {
  fill: var(--svg-color--3c2228, #3C2228);
  d: path("M20.17 20.33c-.74.74-.74 1.93 0 2.67s1.93.74 2.67 0l1.641-1.593c1.237-1.2.314-1.484.4-1.6c-.137-.375-.691.823-.991.523a2.84 2.84 0 0 0-2.948-.668z");
}

.jdigj6b0e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M25.644 16.554c.62.844.727 2.407-.38 3.555");
}

.k3u1_8jwh {
  d: path("M20.193 22.74c-.77-.77-.77-2.01 0-2.78l4.02-4.02c.34-.34.88-.34 1.22 0c1.2 1.2 1.2 3.14 0 4.34l-2.46 2.46c-.77.77-2.01.77-2.78 0");
}

.k3vhuof5y {
  stop-color: var(--svg-color--56404e, #56404E);
  stop-opacity: 0;
}

.kjz5qz64y {
  stop-color: var(--svg-color--b68fde, #B68FDE);
}

.l1vouxb_t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M21.687 12.179c.62.844.727 2.407-.38 3.555");
}

.mgbnx5e4n {
  d: path("M11.853 14.4c-.77-.77-.77-2.01 0-2.78l4.02-4.02c.34-.34.88-.34 1.22 0c1.2 1.2 1.2 3.14 0 4.34l-2.46 2.46c-.77.77-2.01.77-2.78 0");
}

.mrapryg6g {
  stop-color: var(--svg-color--4f3439, #4F3439);
}

.mz5t27b8z {
  fill: var(--svg-color--3c2228, #3C2228);
  d: path("M11.954 11.926c-.74.74-.74 1.93 0 2.67s1.931.74 2.671 0l2.059-2.078a3 3 0 0 0 .287-.333a2.835 2.835 0 0 0-3.603-1.693z");
}

.nbwwmb4dc {
  stop-color: var(--svg-color--944eea, #944EEA);
  stop-opacity: 0;
}

.nca8yqbjd {
  stop-color: var(--svg-color--c197fd, #C197FD);
  stop-opacity: 0;
}

.ni_yscb0i {
  stop-color: var(--svg-color--5f4b4a, #5F4B4A);
  stop-opacity: 0;
}

.q9athqbmo {
  d: path("m2.362 29.45l14.12-14.12a2.95 2.95 0 0 0 0-4.17a2.95 2.95 0 0 0-4.17 0l-9.95 9.96z");
}

.qu-d_ya5h {
  stop-color: var(--svg-color--5f4b4a, #5F4B4A);
}

.qw6b0obtg {
  stop-color: var(--svg-color--1b0b0c, #1B0B0C);
}

.s8mjdcbzp {
  stop-color: var(--svg-color--221010, #221010);
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

.vm4647fep {
  stop-color: var(--svg-color--63487e, #63487E);
}

.vscc-5lzn {
  stop-color: var(--svg-color--614d4c, #614D4C);
  stop-opacity: 0;
}

.vtjxhabnn {
  stop-color: var(--svg-color--221010, #221010);
  stop-opacity: 0;
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

.vy3a6n4ty {
  stop-color: var(--svg-color--614d4c, #614D4C);
}

.we1rycbkb {
  stop-color: var(--svg-color--a07ddf, #A07DDF);
}

.wejjc0b2m {
  d: path("M24.822 10.53v.5c0 .83-.15 1.41-.27 1.73c-.05.15.06.31.22.31c1.365 0 3.14-1.024 3.14-2.55h-3.09z");
}

.wswmq3b9g {
  d: path("M25.519 2.428a.5.5 0 0 1 .49-.406h3.843a.5.5 0 0 1 .49.594l-.58 3.024a.5.5 0 0 1-.492.406h-3.842a.5.5 0 0 1-.491-.595z");
}

.x9eopbbkh {
  stop-color: var(--svg-color--4f3539, #4F3539);
}

.xcrwndl2x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M27.737 2.469H29.8");
}

.ymfuz3h0p {
  stop-color: var(--svg-color--835ab3, #835AB3);
}

.zgdheybwc {
  stop-color: var(--svg-color--944eea, #944EEA);
}

.zghepjbnl {
  fill: var(--svg-color--3c2228, #3C2228);
  d: path("M16.29 16.008c-.74.74-.74 1.93 0 2.67s1.931.74 2.67 0l2.06-2.078c1.237-1.2 1.042-1.91 1.128-2.026c-.137-.374-1.197.968-1.497.668a2.84 2.84 0 0 0-2.947-.668z");
}

.zppdw8bsm {
  d: path("M22.043 13.94a2.95 2.95 0 0 0-4.17 0L2.362 29.45V30h7.79l11.89-11.89a2.95 2.95 0 0 0 0-4.17");
}

</style>
