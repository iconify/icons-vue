<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ixCafAc)" class="t9m2tabyw"/><path fill="url(#i8wQ5He)" class="t9m2tabyw"/><path fill="url(#ial5pCd)" class="t9m2tabyw"/><g filter="url(#iAJd2Yd)"><rect fill="url(#irpLjAe)" class="c_43tpblx"/></g><path fill="url(#i6QJdrc)" class="izpxl7s0a"/><path fill="url(#iqUUNFc)" class="w_imipasv"/><path fill="url(#ixqbZKd)" class="w_imipasv"/><path fill="url(#iELkfQe)" class="w_imipasv"/><path fill="url(#ibN5g8Z)" class="w_imipasv"/><path fill="url(#ir23hKb)" class="wo4v9geer"/><path fill="url(#i5mcugc)" class="tyagfjbyl"/><path fill="url(#iskQ5Pe)" class="tyagfjbyl"/><path fill="url(#iX1g6hb)" class="x7e4nwb0n"/><path fill="url(#iUhBHWb)" class="a6xwq6bgj"/><path fill="url(#iN68kvC)" class="a6xwq6bgj"/><path fill="url(#iVTHSud)" class="ztsjqz8tp"/><path fill="url(#iApbfeb)" class="ztsjqz8tp"/><path fill="url(#igHo4Lb)" class="m75n41u5b"/><g filter="url(#iEuOpjc)"><path fill="url(#i8U5aye)" class="sd6j40bfx"/><path fill="url(#i8NlNDe)" class="sd6j40bfx"/></g><g filter="url(#i6IWAzc)"><path fill="url(#iheJbdb)" class="l5_5tj9hk"/></g><path fill="url(#iTuw1Rq)" clip-rule="evenodd" class="qiseqqbjl"/><path fill="url(#ivOrBXd)" class="djfoq9bql"/><path fill="url(#i0SNM5b)" clip-rule="evenodd" class="h_73dybug"/><path fill="url(#iVdXgtc)" clip-rule="evenodd" class="h_73dybug"/><path fill="url(#iTbH2Pb)" clip-rule="evenodd" class="nwsc8db8p"/><path fill="url(#ieKpiZF)" clip-rule="evenodd" class="nwsc8db8p"/><g filter="url(#ixZrWxc)"><path class="ty8wnebue"/></g><g filter="url(#ibriX6d)"><ellipse class="ktkvyvbpg"/></g><g filter="url(#iZxIXBj)"><path stroke="url(#ibAN32Y)" class="lkz77qgxt"/></g><g filter="url(#iNsYHJd)"><path class="wct-0abdm"/><path fill="url(#iw0XR2c)" class="cspq55lxy"/></g><g filter="url(#iipXjDe)"><path stroke="url(#iVbhmOc)" class="bs6-lp06i"/></g><defs><linearGradient id="ixCafAc" x1="16" x2="16" y1="26.061" y2=".464" gradientUnits="userSpaceOnUse"><stop class="nl2orebih"/><stop offset="0" class="nl2orebih"/><stop offset="1" class="dzca75iiv"/></linearGradient><linearGradient id="i8wQ5He" x1="-1.731" x2="5.3" y1="20.315" y2="20.315" gradientUnits="userSpaceOnUse"><stop class="rcgbucecq"/><stop offset="1" class="o1u7ztjhk"/></linearGradient><linearGradient id="ial5pCd" x1="17.18" x2="17.18" y1="31.59" y2="27.281" gradientUnits="userSpaceOnUse"><stop offset=".127" class="pic8qkb9r"/><stop offset="1" class="siq704zhl"/></linearGradient><linearGradient id="irpLjAe" x1="27.16" x2="27.16" y1="4.146" y2="26.707" gradientUnits="userSpaceOnUse"><stop class="kw9odfpmw"/><stop offset="1" class="wh-x3498z"/></linearGradient><linearGradient id="ixqbZKd" x1="20.619" x2="20.619" y1="23.505" y2="24.411" gradientUnits="userSpaceOnUse"><stop class="c5kjlfbnv"/><stop offset="1" class="b5at55eqz"/></linearGradient><linearGradient id="iELkfQe" x1="14.34" x2="16.872" y1="28.505" y2="28.505" gradientUnits="userSpaceOnUse"><stop class="own5ppb3t"/><stop offset="1" class="ma3bxrbma"/></linearGradient><linearGradient id="ibN5g8Z" x1="14.819" x2="15.071" y1="27.442" y2="27.442" gradientUnits="userSpaceOnUse"><stop class="iblwlqk_p"/><stop offset="1" class="ieshobb-j"/></linearGradient><linearGradient id="i8U5aye" x1="14.872" x2="25.284" y1="23.255" y2="23.255" gradientUnits="userSpaceOnUse"><stop class="x94ug12_a"/><stop offset="1" class="to6o7ac7u"/></linearGradient><linearGradient id="iTuw1Rq" x1="6.274" x2="6.274" y1="26.649" y2="27.441" gradientUnits="userSpaceOnUse"><stop class="r8yp1bv_n"/><stop offset="1" class="ll6rpoekf"/></linearGradient><linearGradient id="ivOrBXd" x1="1.488" x2="1.488" y1="14.572" y2="27.445" gradientUnits="userSpaceOnUse"><stop offset=".011" class="f401pjpsv"/><stop offset="1" class="p2mf6j0rl"/></linearGradient><linearGradient id="i0SNM5b" x1="7.209" x2="7.209" y1="15.826" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="ec1br1_um"/><stop offset="1" class="vec8dqb6n"/></linearGradient><linearGradient id="iVdXgtc" x1="7.843" x2="7.51" y1="24.25" y2="24.25" gradientUnits="userSpaceOnUse"><stop class="ry9lmxu4g"/><stop offset="1" class="z8g7lub4q"/></linearGradient><linearGradient id="iTbH2Pb" x1="10.059" x2="10.059" y1="25.933" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="nj0olibng"/><stop offset="1" class="vec8dqb6n"/></linearGradient><linearGradient id="ieKpiZF" x1="10.693" x2="10.36" y1="27.362" y2="27.362" gradientUnits="userSpaceOnUse"><stop class="ho1s2vb9z"/><stop offset="1" class="mqbt94tlj"/></linearGradient><linearGradient id="ibAN32Y" x1="7.724" x2="7.724" y1="15.902" y2="29.609" gradientUnits="userSpaceOnUse"><stop class="sm9d97bha"/><stop offset="1" class="hn5hvtb_j"/></linearGradient><linearGradient id="iw0XR2c" x1="7.156" x2="7.156" y1="16.016" y2="13.168" gradientUnits="userSpaceOnUse"><stop class="atx0ff_7i"/><stop offset="1" class="s5-m8hqju"/></linearGradient><linearGradient id="iVbhmOc" x1="4.718" x2="4.718" y1="15.756" y2="26.609" gradientUnits="userSpaceOnUse"><stop class="s4o78oh0m"/><stop offset="1" class="c2ud8uxvs"/></linearGradient><radialGradient id="i6QJdrc" cx="0" cy="0" r="1" gradientTransform="rotate(135.891 10.115 8.612)scale(8.53051 8.82679)" gradientUnits="userSpaceOnUse"><stop class="qiscp8o9q"/><stop offset="1" class="n30-wbb-q"/></radialGradient><radialGradient id="iqUUNFc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.80737 0 0 -14.0682 25.42 26.988)" gradientUnits="userSpaceOnUse"><stop class="c5pv1nh-q"/><stop offset="1" class="u44wassix"/></radialGradient><radialGradient id="ir23hKb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.21876 1.46873 -1.46873 -2.21875 21.59 14.911)" gradientUnits="userSpaceOnUse"><stop class="ebkdepbyt"/><stop offset="1" class="t983ddcge"/></radialGradient><radialGradient id="i5mcugc" cx="0" cy="0" r="1" gradientTransform="rotate(133.721 6.492 12.608)scale(2.89191 2.8919)" gradientUnits="userSpaceOnUse"><stop class="qlwwsxbgk"/><stop offset="1" class="n6pr48bye"/></radialGradient><radialGradient id="iskQ5Pe" cx="0" cy="0" r="1" gradientTransform="rotate(140.967 7.001 12.844)scale(1.53035 1.53034)" gradientUnits="userSpaceOnUse"><stop class="lulk5nb4u"/><stop offset="1" class="xja_uk7ez"/></radialGradient><radialGradient id="iX1g6hb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.21876 1.46873 -1.46873 -2.21875 22.87 17.251)" gradientUnits="userSpaceOnUse"><stop class="ebkdepbyt"/><stop offset="1" class="f8euzi8rv"/></radialGradient><radialGradient id="iUhBHWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.62502 2.555 -2.555 -.62501 18.684 19.38)" gradientUnits="userSpaceOnUse"><stop class="slr76ub-d"/><stop offset="1" class="pqrpgo9jl"/></radialGradient><radialGradient id="iN68kvC" cx="0" cy="0" r="1" gradientTransform="rotate(140.388 5.932 13.913)scale(1.70371 1.7037)" gradientUnits="userSpaceOnUse"><stop class="ykcggybze"/><stop offset="1" class="yx6wobbdp"/></radialGradient><radialGradient id="iVTHSud" cx="0" cy="0" r="1" gradientTransform="matrix(-.62502 2.555 -2.555 -.62501 21.244 19.38)" gradientUnits="userSpaceOnUse"><stop class="qave3fpis"/><stop offset="1" class="el3svabtg"/></radialGradient><radialGradient id="iApbfeb" cx="0" cy="0" r="1" gradientTransform="rotate(140.388 7.212 14.374)scale(1.70371 1.7037)" gradientUnits="userSpaceOnUse"><stop class="m5ukiiedy"/><stop offset="1" class="zyhisjivl"/></radialGradient><radialGradient id="igHo4Lb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.21876 1.46873 -1.46873 -2.21875 24.15 19.811)" gradientUnits="userSpaceOnUse"><stop class="ebkdepbyt"/><stop offset="1" class="t983ddcge"/></radialGradient><radialGradient id="i8NlNDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.19 -9.7525 0 20.624 23.815)" gradientUnits="userSpaceOnUse"><stop class="tvmei6b5w"/><stop offset="1" class="rklqzibla"/></radialGradient><radialGradient id="iheJbdb" cx="0" cy="0" r="1" gradientTransform="matrix(1.64757 -1.08772 .99445 1.5063 19.625 27.1)" gradientUnits="userSpaceOnUse"><stop class="yq03qmqlv"/><stop offset="1" class="qy6t-undj"/></radialGradient><filter id="iAJd2Yd" width="7.055" height="27.561" x="23.633" y="1.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_1126" stdDeviation="1.25"/></filter><filter id="iEuOpjc" width="14.87" height="2.58" x="13.189" y="21.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.478431 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1126"/></filter><filter id="i6IWAzc" width="2.38" height="2.38" x="19.379" y="25.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.387018 0 0 0 0 0.299444 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1126"/></filter><filter id="ixZrWxc" width="6.571" height="11.434" x="9.429" y="13.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.623529 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1126"/></filter><filter id="ibriX6d" width="8.745" height="1.76" x="19.164" y="21.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_1126" stdDeviation=".3"/></filter><filter id="iZxIXBj" width=".75" height="15.4" x="6.849" y="14.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_1126" stdDeviation=".125"/></filter><filter id="iNsYHJd" width="8.542" height="11.534" x="6.569" y="4.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.870588 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1126"/></filter><filter id="iipXjDe" width="1.746" height="12.915" x="3.886" y="14.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_1126" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:moon-viewing-ceremony" /></template>
<style>
.a6xwq6bgj {
  d: path("M18.06 21.935a1.65 1.65 0 1 0-.001-3.3a1.65 1.65 0 0 0 0 3.3");
}

.atx0ff_7i {
  stop-color: var(--svg-color--dba044, #DBA044);
}

.b5at55eqz {
  stop-color: var(--svg-color--d67774, #D67774);
  stop-opacity: 0;
}

.bs6-lp06i {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M4.428 14.811c.193.068.58.41.58 1.228v10.57");
}

.c_43tpblx {
  width: 2.055px;
  height: 22.561px;
  x: 26.133px;
  y: 4.146px;
  rx: 1.027px;
}

.c2ud8uxvs {
  stop-color: var(--svg-color--59896f, #59896F);
}

.c5kjlfbnv {
  stop-color: var(--svg-color--d67774, #D67774);
}

.c5pv1nh-q {
  stop-color: var(--svg-color--ffd6a6, #FFD6A6);
}

.cspq55lxy {
  d: path("M14.45 4.425h-3.98c-2.16 0-3.9 1.75-3.9 3.9v6.45c0 .34.25.64.59.68c.39.04.72-.27.72-.65v-2.5c0-.43.35-.78.78-.78h1.73c.34 0 .64-.25.68-.59a.655.655 0 0 0-.65-.72H8.68c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h3.83c.34 0 .64-.25.68-.59a.655.655 0 0 0-.65-.72H9.96c-1.01 0-1.08-1.52-.07-1.58h4.54c.34 0 .64-.25.68-.59a.665.665 0 0 0-.66-.71");
}

.djfoq9bql {
  d: path("M3.92 14.105v11.68c0 .92.74 1.66 1.66 1.66v-11.68c0-.92-.74-1.66-1.66-1.66");
}

.dzca75iiv {
  stop-color: var(--svg-color--1c1c1d, #1C1C1D);
}

.ebkdepbyt {
  stop-color: var(--svg-color--fcf6fe, #FCF6FE);
}

.ec1br1_um {
  stop-color: var(--svg-color--6b9f3c, #6B9F3C);
}

.el3svabtg {
  stop-color: var(--svg-color--bfb5bf, #BFB5BF);
}

.f401pjpsv {
  stop-color: var(--svg-color--70a738, #70A738);
}

.f8euzi8rv {
  stop-color: var(--svg-color--c3bbc2, #C3BBC2);
}

.ft5dv1b6b {
  fill: none;
}

.h_73dybug {
  fill-rule: evenodd;
  d: path("M6.675 29.985v-16.29h1.069v16.29z");
}

.hn5hvtb_j {
  stop-color: var(--svg-color--45746f, #45746F);
}

.ho1s2vb9z {
  stop-color: var(--svg-color--779968, #779968);
}

.iblwlqk_p {
  stop-color: var(--svg-color--ae797d, #AE797D);
}

.ieshobb-j {
  stop-color: var(--svg-color--ae797d, #AE797D);
  stop-opacity: 0;
}

.izpxl7s0a {
  d: path("M20.619 15.165a5.47 5.47 0 1 0 0-10.94a5.47 5.47 0 0 0 0 10.94");
}

.ktkvyvbpg {
  cx: 23.537px;
  cy: 22.245px;
  fill: var(--svg-color--b07f78, #B07F78);
  rx: 3.773px;
  ry: 0.28px;
}

.kw9odfpmw {
  stop-color: var(--svg-color--514e55, #514E55);
}

.l5_5tj9hk {
  d: path("M20.619 27.345a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.lkz77qgxt {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.224 14.709v14.9");
}

.ll6rpoekf {
  stop-color: var(--svg-color--4e6c6f, #4E6C6F);
}

.lulk5nb4u {
  stop-color: var(--svg-color--aea5ad, #AEA5AD);
}

.m5ukiiedy {
  stop-color: var(--svg-color--b0a7b1, #B0A7B1);
}

.m75n41u5b {
  d: path("M23.179 21.935a1.65 1.65 0 1 0 0-3.3a1.65 1.65 0 0 0 0 3.3");
}

.ma3bxrbma {
  stop-color: var(--svg-color--b06f53, #B06F53);
  stop-opacity: 0;
}

.mqbt94tlj {
  stop-color: var(--svg-color--779968, #779968);
  stop-opacity: 0;
}

.n30-wbb-q {
  stop-color: var(--svg-color--f7bc88, #F7BC88);
}

.n6pr48bye {
  stop-color: var(--svg-color--b1a8b1, #B1A8B1);
}

.nj0olibng {
  stop-color: var(--svg-color--5e874b, #5E874B);
}

.nl2orebih {
  stop-color: var(--svg-color--8a52b9, #8A52B9);
}

.nwsc8db8p {
  fill-rule: evenodd;
  d: path("M9.525 29.985v-7.45h1.069v7.45z");
}

.o1u7ztjhk {
  stop-color: var(--svg-color--5e2e91, #5E2E91);
  stop-opacity: 0;
}

.own5ppb3t {
  stop-color: var(--svg-color--b06f53, #B06F53);
}

.p2mf6j0rl {
  stop-color: var(--svg-color--406c74, #406C74);
}

.pic8qkb9r {
  stop-color: var(--svg-color--5d328d, #5D328D);
}

.pqrpgo9jl {
  stop-color: var(--svg-color--b1a8af, #B1A8AF);
}

.qave3fpis {
  stop-color: var(--svg-color--d9d4dc, #D9D4DC);
}

.qiscp8o9q {
  stop-color: var(--svg-color--fff8d2, #FFF8D2);
}

.qiseqqbjl {
  fill-rule: evenodd;
  d: path("M6.98 27.441H5.57v-.792h1.41z");
}

.qlwwsxbgk {
  stop-color: var(--svg-color--d9d2dc, #D9D2DC);
}

.qy6t-undj {
  stop-color: var(--svg-color--c46e5a, #C46E5A);
}

.r8yp1bv_n {
  stop-color: var(--svg-color--4c7f42, #4C7F42);
}

.rcgbucecq {
  stop-color: var(--svg-color--181818, #181818);
}

.rklqzibla {
  stop-color: var(--svg-color--833c62, #833C62);
  stop-opacity: 0;
}

.ry9lmxu4g {
  stop-color: var(--svg-color--7fa270, #7FA270);
}

.s4o78oh0m {
  stop-color: var(--svg-color--85b35c, #85B35C);
}

.s5-m8hqju {
  stop-color: var(--svg-color--dba044, #DBA044);
  stop-opacity: 0;
}

.sd6j40bfx {
  d: path("M26.77 23.815H14.48c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29h12.29c.71 0 1.29.58 1.29 1.29s-.58 1.29-1.29 1.29");
}

.siq704zhl {
  stop-color: var(--svg-color--5d328d, #5D328D);
  stop-opacity: 0;
}

.slr76ub-d {
  stop-color: var(--svg-color--cec7cf, #CEC7CF);
}

.sm9d97bha {
  stop-color: var(--svg-color--7fab56, #7FAB56);
}

.t983ddcge {
  stop-color: var(--svg-color--c3bac3, #C3BAC3);
}

.t9m2tabyw {
  d: path("M26.305 2.015H5.695c-2.03 0-3.68 1.65-3.68 3.68v20.61c0 2.03 1.65 3.68 3.68 3.68h20.61c2.03 0 3.68-1.65 3.68-3.68V5.695c0-2.03-1.64-3.68-3.68-3.68");
}

.to6o7ac7u {
  stop-color: var(--svg-color--925f54, #925F54);
}

.tvmei6b5w {
  stop-color: var(--svg-color--833c62, #833C62);
}

.ty8wnebue {
  fill: var(--svg-color--ecbb45, #ECBB45);
  d: path("M15.34 14.025h-2.01c-2.16 0-3.9 1.75-3.9 3.9v6.45c0 .34.25.64.59.68c.39.04.72-.27.72-.65v-2.5c0-.43.35-.78.78-.78h1.58c.34 0 .64-.25.68-.59a.655.655 0 0 0-.65-.72h-1.59c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h2.47c.34 0 .64-.25.68-.59a.655.655 0 0 0-.65-.72h-1.22c-1.01 0-1.08-1.52-.07-1.58h2.57c.34 0 .64-.25.68-.59a.666.666 0 0 0-.66-.71");
}

.tyagfjbyl {
  d: path("M19.34 19.375a1.65 1.65 0 1 0 0-3.3a1.65 1.65 0 0 0 0 3.3");
}

.u44wassix {
  stop-color: var(--svg-color--d88772, #D88772);
}

.vec8dqb6n {
  stop-color: var(--svg-color--34686b, #34686B);
}

.w_imipasv {
  d: path("M26.42 22.525h-11.6v7.46h11.6z");
}

.wct-0abdm {
  fill: var(--svg-color--f0c341, #F0C341);
  d: path("M14.45 4.425h-3.98c-2.16 0-3.9 1.75-3.9 3.9v6.45c0 .34.25.64.59.68c.39.04.72-.27.72-.65v-2.5c0-.43.35-.78.78-.78h1.73c.34 0 .64-.25.68-.59a.655.655 0 0 0-.65-.72H8.68c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h3.83c.34 0 .64-.25.68-.59a.655.655 0 0 0-.65-.72H9.96c-1.01 0-1.08-1.52-.07-1.58h4.54c.34 0 .64-.25.68-.59a.665.665 0 0 0-.66-.71");
}

.wh-x3498z {
  stop-color: var(--svg-color--9f6ad1, #9F6AD1);
}

.wo4v9geer {
  d: path("M20.619 17.035a1.65 1.65 0 1 0 0-3.3a1.65 1.65 0 0 0 0 3.3");
}

.x7e4nwb0n {
  d: path("M21.899 19.375a1.65 1.65 0 1 0 0-3.3a1.65 1.65 0 0 0 0 3.3");
}

.x94ug12_a {
  stop-color: var(--svg-color--694544, #694544);
}

.xja_uk7ez {
  stop-color: var(--svg-color--aea5ad, #AEA5AD);
  stop-opacity: 0;
}

.ykcggybze {
  stop-color: var(--svg-color--9b9299, #9B9299);
}

.yq03qmqlv {
  stop-color: var(--svg-color--cc8862, #CC8862);
}

.yx6wobbdp {
  stop-color: var(--svg-color--9b9299, #9B9299);
  stop-opacity: 0;
}

.z8g7lub4q {
  stop-color: var(--svg-color--7fa270, #7FA270);
  stop-opacity: 0;
}

.ztsjqz8tp {
  d: path("M20.619 21.935a1.65 1.65 0 1 0 0-3.3a1.65 1.65 0 0 0 0 3.3");
}

.zyhisjivl {
  stop-color: var(--svg-color--b0a7b1, #B0A7B1);
  stop-opacity: 0;
}

</style>
