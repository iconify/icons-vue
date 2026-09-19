<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i4evxCE)" class="j011grbjm"/><path fill="url(#icraEGc)" class="j011grbjm"/><path fill="url(#iJer4Ae)" class="j011grbjm"/><path fill="url(#iy3x6kb)" class="rcjtxcc-s"/><path fill="url(#ij69FBc)" class="rcjtxcc-s"/><path fill="url(#iEIxoXF)" class="rcjtxcc-s"/><path fill="url(#iPEOoGK)" class="uh5hm0kpa"/><path fill="url(#inowEjd)" class="uh5hm0kpa"/><path fill="url(#iId9Vob)" class="uh5hm0kpa"/><g filter="url(#i63d7Eb)"><path fill="url(#iWhS5uc)" class="jqzc5ybeo"/></g><g filter="url(#iXKuzod)"><path fill="url(#ig8TZNb)" class="i6-0xgbbw"/></g><g filter="url(#iSVonAF)"><path fill="url(#iwQpnKb)" class="r1zfpzbzv"/></g><path fill="url(#ibcmN5d)" class="s84f-ybpk"/><path fill="url(#iOebVTc)" class="eav-t2qyr"/><path fill="url(#iFtf7ke)" class="eav-t2qyr"/><path fill="url(#ih3vNJc)" class="n9937ybmt"/><path fill="url(#i7gN01c)" class="n9937ybmt"/><path fill="url(#idLDU0d)" class="n9937ybmt"/><path fill="url(#iSYzSOU)" class="emf1bqbor"/><g filter="url(#iXszGRm)"><path stroke="url(#iNIpJJd)" class="u4ej8mbpf"/></g><g filter="url(#iAMvUGI)"><path stroke="url(#iyPKqQk)" class="kj9ytn4do"/></g><g filter="url(#i2vfdgc)"><path stroke="url(#iHYpUqe)" class="bgfx75bsg"/></g><g filter="url(#ijNXtPd)"><path stroke="url(#iaxbCnm)" class="yatd8-03g"/></g><g filter="url(#iqaCNqc)"><path stroke="url(#is6uC5d)" class="vdg6bxbcj"/></g><defs><linearGradient id="i4evxCE" x1="7.784" x2="9.858" y1="15.688" y2="17.769" gradientUnits="userSpaceOnUse"><stop class="fqzilqbpa"/><stop offset="1" class="dl5139yax"/></linearGradient><linearGradient id="icraEGc" x1="11.539" x2="10.845" y1="20.178" y2="19.472" gradientUnits="userSpaceOnUse"><stop class="as8-f8b_t"/><stop offset="1" class="w6sq89b0m"/></linearGradient><linearGradient id="iy3x6kb" x1="11.002" x2="13.784" y1="17.969" y2="21" gradientUnits="userSpaceOnUse"><stop class="fqzilqbpa"/><stop offset="1" class="dl5139yax"/></linearGradient><linearGradient id="ij69FBc" x1="16.455" x2="15.805" y1="23.582" y2="22.923" gradientUnits="userSpaceOnUse"><stop offset=".052" class="as8-f8b_t"/><stop offset="1" class="w6sq89b0m"/></linearGradient><linearGradient id="iPEOoGK" x1="16.034" x2="18.502" y1="22.531" y2="25.094" gradientUnits="userSpaceOnUse"><stop class="fqzilqbpa"/><stop offset="1" class="dl5139yax"/></linearGradient><linearGradient id="inowEjd" x1="22.377" x2="21.112" y1="27.453" y2="26.156" gradientUnits="userSpaceOnUse"><stop offset=".052" class="as8-f8b_t"/><stop offset="1" class="w6sq89b0m"/></linearGradient><linearGradient id="iWhS5uc" x1="11.409" x2="17.159" y1="14.5" y2="8.75" gradientUnits="userSpaceOnUse"><stop class="sqfv3yvvc"/><stop offset="1" class="bresl47vt"/></linearGradient><linearGradient id="ig8TZNb" x1="15.759" x2="21.509" y1="18.49" y2="12.74" gradientUnits="userSpaceOnUse"><stop class="sqfv3yvvc"/><stop offset="1" class="bresl47vt"/></linearGradient><linearGradient id="iwQpnKb" x1="19.749" x2="25.499" y1="22.84" y2="17.09" gradientUnits="userSpaceOnUse"><stop class="sqfv3yvvc"/><stop offset="1" class="bresl47vt"/></linearGradient><linearGradient id="ibcmN5d" x1="27.424" x2="26.01" y1="9.672" y2="9.172" gradientUnits="userSpaceOnUse"><stop class="vm4647fep"/><stop offset="1" class="f3ksyacap"/></linearGradient><linearGradient id="ih3vNJc" x1="24.784" x2="30" y1="3.781" y2="4.344" gradientUnits="userSpaceOnUse"><stop class="c7zx3cksj"/><stop offset=".745" class="g6u09qa-r"/><stop offset="1" class="we1rycbkb"/></linearGradient><linearGradient id="i7gN01c" x1="27.288" x2="27.288" y1="6.141" y2="5.749" gradientUnits="userSpaceOnUse"><stop class="zgdheybwc"/><stop offset="1" class="nbwwmb4dc"/></linearGradient><linearGradient id="idLDU0d" x1="27.877" x2="27.877" y1="1.969" y2="2.5" gradientUnits="userSpaceOnUse"><stop class="aq44g_bhz"/><stop offset="1" class="h7irysb4b"/></linearGradient><linearGradient id="iSYzSOU" x1="26.815" x2="26.19" y1="2.67" y2="5.969" gradientUnits="userSpaceOnUse"><stop class="g-kz03upj"/><stop offset="1" class="tn_gpqb-m"/></linearGradient><linearGradient id="iNIpJJd" x1="29.706" x2="27.374" y1="2.522" y2="2.351" gradientUnits="userSpaceOnUse"><stop class="hb662vr6x"/><stop offset="1" class="nca8yqbjd"/></linearGradient><linearGradient id="iyPKqQk" x1="26.924" x2="26.469" y1="10.281" y2="6.844" gradientUnits="userSpaceOnUse"><stop class="emrf7fbkb"/><stop offset="1" class="vtyb507lt"/></linearGradient><radialGradient id="iJer4Ae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56248 2.50001 -1.9557 -1.2223 16.784 12.156)" gradientUnits="userSpaceOnUse"><stop class="gg6f3hb2a"/><stop offset="1" class="re512acxj"/></radialGradient><radialGradient id="iEIxoXF" cx="0" cy="0" r="1" gradientTransform="rotate(116.764 6.602 14.214)scale(3.63874 3.16524)" gradientUnits="userSpaceOnUse"><stop class="gg6f3hb2a"/><stop offset="1" class="re512acxj"/></radialGradient><radialGradient id="iId9Vob" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 3.4375 -2.98 -1.00236 25.502 20.406)" gradientUnits="userSpaceOnUse"><stop class="gg6f3hb2a"/><stop offset="1" class="re512acxj"/></radialGradient><radialGradient id="iOebVTc" cx="0" cy="0" r="1" gradientTransform="rotate(-43.091 28.85 -24.293)scale(2.65312 1.53839)" gradientUnits="userSpaceOnUse"><stop class="a9v_6_b1o"/><stop offset="1" class="bssbofdfc"/></radialGradient><radialGradient id="iFtf7ke" cx="0" cy="0" r="1" gradientTransform="matrix(1.4132 .37061 -.85081 3.2443 24.46 10.52)" gradientUnits="userSpaceOnUse"><stop class="tojlolbvi"/><stop offset="1" class="dg1c6wbtb"/></radialGradient><radialGradient id="iHYpUqe" cx="0" cy="0" r="1" gradientTransform="matrix(1.71876 -.47656 13.3473 48.13857 16.4 10.398)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="r89_u5b7d"/><stop offset=".928" class="oupzb32iw"/></radialGradient><radialGradient id="iaxbCnm" cx="0" cy="0" r="1" gradientTransform="matrix(1.71876 -.47656 13.3473 48.13857 20.783 14.328)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="r89_u5b7d"/><stop offset=".928" class="oupzb32iw"/></radialGradient><radialGradient id="is6uC5d" cx="0" cy="0" r="1" gradientTransform="matrix(1.71876 -.47656 13.3473 48.13857 24.74 18.703)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="r89_u5b7d"/><stop offset=".928" class="oupzb32iw"/></radialGradient><filter id="i63d7Eb" width="6.718" height="7.632" x="10.923" y="7.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.372549 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5918"/></filter><filter id="iXKuzod" width="6.718" height="7.632" x="15.273" y="11.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.372549 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5918"/></filter><filter id="iSVonAF" width="6.718" height="7.632" x="19.263" y="15.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.372549 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5918"/></filter><filter id="iXszGRm" width="2.813" height=".75" x="27.01" y="2.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5918" stdDeviation=".125"/></filter><filter id="iAMvUGI" width=".863" height="3.317" x="26.286" y="6.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5918" stdDeviation=".075"/></filter><filter id="i2vfdgc" width="1.142" height="3.855" x="16.422" y="8.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5918" stdDeviation=".05"/></filter><filter id="ijNXtPd" width="1.142" height="3.855" x="20.805" y="12.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5918" stdDeviation=".05"/></filter><filter id="iqaCNqc" width="1.142" height="3.855" x="24.762" y="16.404" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5918" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:nail-polish" /></template>
<style>
.a9v_6_b1o {
  stop-color: var(--svg-color--a843b3, #A843B3);
}

.aq44g_bhz {
  stop-color: var(--svg-color--9774c5, #9774C5);
}

.as8-f8b_t {
  stop-color: var(--svg-color--d57300, #D57300);
}

.bgfx75bsg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.952 8.25c.62.844.727 2.406-.38 3.555");
}

.bresl47vt {
  stop-color: var(--svg-color--9f5fc3, #9F5FC3);
}

.bssbofdfc {
  stop-color: var(--svg-color--a16bed, #A16BED);
}

.c7zx3cksj {
  stop-color: var(--svg-color--9361c0, #9361C0);
}

.dg1c6wbtb {
  stop-color: var(--svg-color--885aa8, #885AA8);
  stop-opacity: 0;
}

.dl5139yax {
  stop-color: var(--svg-color--ffc53c, #FFC53C);
}

.eav-t2qyr {
  d: path("M24.47 10.53v.5c0 .83-.15 1.41-.27 1.73c-.05.15.06.31.22.31c1.364 0 3.14-1.024 3.14-2.55h-3.09z");
}

.emf1bqbor {
  d: path("M26.172 2.991a.394.394 0 0 1 .774.145l-.375 1.995a.394.394 0 1 1-.774-.145z");
}

.emrf7fbkb {
  stop-color: var(--svg-color--63497a, #63497A);
}

.f3ksyacap {
  stop-color: var(--svg-color--4a285a, #4A285A);
}

.fqzilqbpa {
  stop-color: var(--svg-color--e9a72a, #E9A72A);
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

.gg6f3hb2a {
  stop-color: var(--svg-color--ffdd48, #FFDD48);
}

.h7irysb4b {
  stop-color: var(--svg-color--9774c5, #9774C5);
  stop-opacity: 0;
}

.hb662vr6x {
  stop-color: var(--svg-color--c197fd, #C197FD);
}

.i6-0xgbbw {
  d: path("M15.85 18.39c-.77-.77-.77-2.01 0-2.78l4.02-4.02c.34-.34.88-.34 1.22 0c1.2 1.2 1.2 3.14 0 4.34l-2.46 2.46c-.77.77-2.01.77-2.78 0");
}

.j011grbjm {
  d: path("m2.01 29.45l14.12-14.12a2.95 2.95 0 0 0 0-4.17a2.95 2.95 0 0 0-4.17 0l-9.95 9.96z");
}

.jqzc5ybeo {
  d: path("M11.5 14.4c-.77-.77-.77-2.01 0-2.78l4.02-4.02c.34-.34.88-.34 1.22 0c1.2 1.2 1.2 3.14 0 4.34l-2.46 2.46c-.77.77-2.01.77-2.78 0");
}

.kj9ytn4do {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m26.924 6.688l-.396 2.11a1 1 0 0 0 .14.723l.022.034");
}

.n9937ybmt {
  d: path("M25.167 2.428a.5.5 0 0 1 .49-.406H29.5a.5.5 0 0 1 .49.594l-.58 3.024a.5.5 0 0 1-.492.406h-3.842a.5.5 0 0 1-.491-.595z");
}

.nbwwmb4dc {
  stop-color: var(--svg-color--944eea, #944EEA);
  stop-opacity: 0;
}

.nca8yqbjd {
  stop-color: var(--svg-color--c197fd, #C197FD);
  stop-opacity: 0;
}

.oupzb32iw {
  stop-color: var(--svg-color--c690ef, #C690EF);
}

.r1zfpzbzv {
  d: path("M19.84 22.74c-.77-.77-.77-2.01 0-2.78l4.02-4.02c.34-.34.88-.34 1.22 0c1.2 1.2 1.2 3.14 0 4.34l-2.46 2.46c-.77.77-2.01.77-2.78 0");
}

.r89_u5b7d {
  stop-color: var(--svg-color--c690ef, #C690EF);
  stop-opacity: 0;
}

.rcjtxcc-s {
  d: path("M21.69 13.94a2.95 2.95 0 0 0-4.17 0L2.01 29.45V30H9.8l11.89-11.89a2.95 2.95 0 0 0 0-4.17");
}

.re512acxj {
  stop-color: var(--svg-color--ffdd48, #FFDD48);
  stop-opacity: 0;
}

.s84f-ybpk {
  d: path("m26.57 4.94l-.687 3.974a.28.28 0 0 1-.218.218a1.55 1.55 0 0 0-1.195 1.398h3.08a1.55 1.55 0 0 0-.431-.964c-.175-.18-.3-.42-.257-.668l.688-3.958z");
}

.sqfv3yvvc {
  stop-color: var(--svg-color--c659c7, #C659C7);
}

.tn_gpqb-m {
  stop-color: var(--svg-color--fcd0ff, #FCD0FF);
  stop-opacity: 0;
}

.tojlolbvi {
  stop-color: var(--svg-color--885aa8, #885AA8);
}

.u4ej8mbpf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M27.385 2.469h2.063");
}

.uh5hm0kpa {
  d: path("M24.47 19.5a2.95 2.95 0 0 0-4.17 0L9.8 30h8.34l6.33-6.33a2.95 2.95 0 0 0 0-4.17");
}

.vdg6bxbcj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M25.292 16.554c.62.844.727 2.407-.38 3.555");
}

.vm4647fep {
  stop-color: var(--svg-color--63487e, #63487E);
}

.vtyb507lt {
  stop-color: var(--svg-color--63497a, #63497A);
  stop-opacity: 0;
}

.w6sq89b0m {
  stop-color: var(--svg-color--d57300, #D57300);
  stop-opacity: 0;
}

.we1rycbkb {
  stop-color: var(--svg-color--a07ddf, #A07DDF);
}

.yatd8-03g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M21.335 12.179c.62.844.727 2.407-.38 3.555");
}

.zgdheybwc {
  stop-color: var(--svg-color--944eea, #944EEA);
}

</style>
