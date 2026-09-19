<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iYKwEfC)" class="d3z1l-bvx"/><path fill="url(#isnrH9d)" class="d3z1l-bvx"/><path fill="url(#ifAEnmk)" class="d3z1l-bvx"/><path fill="url(#iAtjq3c)" class="iogx_reim"/><path fill="url(#iVfvKyc)" class="iogx_reim"/><path fill="url(#iQQLY2K)" class="iogx_reim"/><g filter="url(#iu5OxTc)"><path fill="url(#imx54ob)" class="sudyg6b8u"/><path fill="url(#i8gIP4c)" class="sudyg6b8u"/><path fill="url(#iIxrmRd)" class="sudyg6b8u"/><path fill="url(#i5N0OGe)" class="sudyg6b8u"/><path fill="url(#iNRQXae)" class="sudyg6b8u"/></g><g filter="url(#iCZLxfc)"><path fill="url(#iSzRDOb)" class="e-7o89b3n"/><path fill="url(#iaUMiFb)" class="e-7o89b3n"/></g><path fill="url(#ilDxLpe)" class="npyp6cbis"/><g filter="url(#ijQucVJ)"><path fill="url(#ikXHCqi)" class="gk0etlbwy"/><path fill="url(#iLntKrM)" class="gk0etlbwy"/></g><path fill="url(#iqK90YP)" class="qmxqddxwy"/><path fill="url(#iM0X1Cc)" class="qmxqddxwy"/><path fill="url(#igiu6oe)" class="qmxqddxwy"/><path fill="url(#ih0DNud)" class="v7wijnblg"/><path fill="url(#iYQZoRd)" class="v7wijnblg"/><path fill="url(#iQ2uooc)" class="v7wijnblg"/><path fill="url(#iTLxAWc)" class="ditajhc2t"/><path fill="url(#iOMCo7r)" class="ditajhc2t"/><path fill="url(#imxNlAW)" class="ditajhc2t"/><path fill="url(#iUhM8bd)" class="ditajhc2t"/><g filter="url(#icuGEbc)"><path fill="url(#i8SVR4d)" class="xqanwb9ff"/></g></g><defs><radialGradient id="isnrH9d" cx="0" cy="0" r="1" gradientTransform="matrix(7.52114 -2.73117 .46436 1.27875 2.398 17.063)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="up-a58x3d"/><stop offset="1" class="dsn-yabsm"/></radialGradient><radialGradient id="iVfvKyc" cx="0" cy="0" r="1" gradientTransform="rotate(86.482 -4.515 18.853)scale(7.63907 6.58606)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="x3yi8cciw"/><stop offset=".951" class="w1ix35bye"/></radialGradient><radialGradient id="iQQLY2K" cx="0" cy="0" r="1" gradientTransform="matrix(2.84378 -4.43748 1.94916 1.24913 13.454 26.234)" gradientUnits="userSpaceOnUse"><stop class="gav2uu2qh"/><stop offset="1" class="tkio3kb3p"/></radialGradient><radialGradient id="i8gIP4c" cx="0" cy="0" r="1" gradientTransform="matrix(-13.22128 -10.16449 19.10663 -24.85262 23.97 21.577)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="kjjeu1b7n"/><stop offset="1" class="fotxynbjy"/></radialGradient><radialGradient id="iIxrmRd" cx="0" cy="0" r="1" gradientTransform="matrix(5.34972 -8.21554 3.86123 2.51432 9.181 21.31)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="lpq47wb7s"/><stop offset="1" class="rzpy97s9g"/></radialGradient><radialGradient id="i5N0OGe" cx="0" cy="0" r="1" gradientTransform="rotate(-73.625 16.594 5.807)scale(8.69119 1.4727)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="xn5-hibsa"/><stop offset="1" class="uht1csa4u"/></radialGradient><radialGradient id="iNRQXae" cx="0" cy="0" r="1" gradientTransform="matrix(-9.68 8.93746 -2.77498 -3.00553 27.11 7.11)" gradientUnits="userSpaceOnUse"><stop class="f4za6vbvd"/><stop offset="1" class="w2pucn1kk"/></radialGradient><radialGradient id="iaUMiFb" cx="0" cy="0" r="1" gradientTransform="rotate(90 5.04 16.102)scale(3.35938)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="ukllbtb1c"/><stop offset="1" class="pn2wqob6x"/></radialGradient><radialGradient id="ilDxLpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84559 4.45626 0 21.14 13.388)" gradientUnits="userSpaceOnUse"><stop class="njd359bdg"/><stop offset=".738" class="x4e7_jb9m"/><stop offset="1" class="ditn90bdp"/></radialGradient><radialGradient id="ikXHCqi" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10578 4.10578 -3.22724 -3.22724 8.191 24.247)" gradientUnits="userSpaceOnUse"><stop class="gr4yobclw"/><stop offset="1" class="up5sbwbok"/></radialGradient><radialGradient id="iLntKrM" cx="0" cy="0" r="1" gradientTransform="matrix(-4.72447 -5.39938 5.69005 -4.9788 8.304 28.97)" gradientUnits="userSpaceOnUse"><stop offset=".871" class="ljqipwbpm"/><stop offset="1" class="ydnli6bru"/></radialGradient><radialGradient id="iM0X1Cc" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 1.59375 -1.40812 .30371 6.83 21.453)" gradientUnits="userSpaceOnUse"><stop class="w2r1q81dk"/><stop offset="1" class="d23c3dvjn"/></radialGradient><radialGradient id="igiu6oe" cx="0" cy="0" r="1" gradientTransform="matrix(4.16202 4.61197 -2.4175 2.18165 7.207 22.418)" gradientUnits="userSpaceOnUse"><stop offset=".86" class="i85ji08og"/><stop offset="1" class="nx09lbclh"/></radialGradient><radialGradient id="iYQZoRd" cx="0" cy="0" r="1" gradientTransform="rotate(135 13.469 8.126)scale(8.24677 1.9797)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="onwaqhuoa"/><stop offset="1" class="y6-tobyfr"/></radialGradient><radialGradient id="iOMCo7r" cx="0" cy="0" r="1" gradientTransform="matrix(6.96875 -2.65623 .69538 1.82436 6.236 19.422)" gradientUnits="userSpaceOnUse"><stop class="gpq_u0fxt"/><stop offset="1" class="dkj6ctx_d"/></radialGradient><radialGradient id="imxNlAW" cx="0" cy="0" r="1" gradientTransform="matrix(3.27669 3.24305 -.95797 .9679 5.398 20.308)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="mdqnnspup"/><stop offset="1" class="onrgslklk"/></radialGradient><radialGradient id="iUhM8bd" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 7.375 -7.85914 .73263 11.58 19.14)" gradientUnits="userSpaceOnUse"><stop offset=".832" class="wscwbb96t"/><stop offset="1" class="hay-ctbfq"/></radialGradient><linearGradient id="iYKwEfC" x1="8.111" x2="3.111" y1="17.308" y2="16.484" gradientUnits="userSpaceOnUse"><stop class="d22q2zbhx"/><stop offset="1" class="jgslamj0f"/></linearGradient><linearGradient id="ifAEnmk" x1="4.905" x2="5.72" y1="19.733" y2="18.938" gradientUnits="userSpaceOnUse"><stop offset=".491" class="evz7_bcap"/><stop offset="1" class="t8_abfbhd"/></linearGradient><linearGradient id="iAtjq3c" x1="17.892" x2="11.674" y1="21.672" y2="26.551" gradientUnits="userSpaceOnUse"><stop class="scff6ihfv"/><stop offset="1" class="pe2b78dkd"/></linearGradient><linearGradient id="imx54ob" x1="13.486" x2="22.298" y1="8.672" y2="17.547" gradientUnits="userSpaceOnUse"><stop class="uihwb0b-w"/><stop offset="1" class="o66quiqmk"/></linearGradient><linearGradient id="iSzRDOb" x1="17.781" x2="24.5" y1="10.491" y2="11.062" gradientUnits="userSpaceOnUse"><stop class="v3d8d-moj"/><stop offset="1" class="sukq5_z5i"/></linearGradient><linearGradient id="iqK90YP" x1="5.798" x2="11.298" y1="21.953" y2="27.359" gradientUnits="userSpaceOnUse"><stop class="wagvrhine"/><stop offset="1" class="loyql_onf"/></linearGradient><linearGradient id="ih0DNud" x1="29.177" x2="25.501" y1="2.876" y2="6.552" gradientUnits="userSpaceOnUse"><stop class="vg8c8edzy"/><stop offset="1" class="a2w3f4bfg"/></linearGradient><linearGradient id="iQ2uooc" x1="25.822" x2="26.189" y1="6.797" y2="6.414" gradientUnits="userSpaceOnUse"><stop class="dbu50acbc"/><stop offset="1" class="zzlt2utle"/></linearGradient><linearGradient id="iTLxAWc" x1="15.16" x2="8.674" y1="17.065" y2="23.551" gradientUnits="userSpaceOnUse"><stop class="b953p6brg"/><stop offset="1" class="s_ddprw4n"/></linearGradient><linearGradient id="i8SVR4d" x1="13.986" x2="9.861" y1="18.109" y2="22.422" gradientUnits="userSpaceOnUse"><stop class="tsqaqmbea"/><stop offset="1" class="j2iz61b_x"/></linearGradient><filter id="iu5OxTc" width="22.396" height="22.659" x="6.095" y="3.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.772549 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13076"/></filter><filter id="iCZLxfc" width="8.719" height="8.719" x="16.781" y="6.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.764706 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13076"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13076" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.690196 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_13076"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.560784 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_13076" result="effect3_innerShadow_18_13076"/></filter><filter id="ijQucVJ" width="7.574" height="7.217" x="2.088" y="22.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.505882 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13076"/></filter><filter id="icuGEbc" width="7.625" height="8.438" x="8.205" y="16.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13076" stdDeviation=".5"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rocket" /></template>
<style>
.a2w3f4bfg {
  stop-color: var(--svg-color--ed224b, #ED224B);
}

.b953p6brg {
  stop-color: var(--svg-color--ff2644, #FF2644);
}

.d22q2zbhx {
  stop-color: var(--svg-color--ee2452, #EE2452);
}

.d23c3dvjn {
  stop-color: var(--svg-color--8e839a, #8E839A);
  stop-opacity: 0;
}

.d3z1l-bvx {
  d: path("M10.582 13.718c1.2-.442 2.367.725 1.925 1.926L9.89 22.758a1 1 0 0 1-1.646.362l-5.138-5.138a1 1 0 0 1 .362-1.645z");
}

.dbu50acbc {
  stop-color: var(--svg-color--d2575e, #D2575E);
}

.ditajhc2t {
  d: path("M13.582 16.718c1.2-.442 2.367.725 1.925 1.926l-2.618 7.114a1 1 0 0 1-1.646.362l-5.138-5.138a1 1 0 0 1 .362-1.645z");
}

.ditn90bdp {
  stop-color: var(--svg-color--3b57f4, #3B57F4);
}

.dkj6ctx_d {
  stop-color: var(--svg-color--ff95af, #FF95AF);
  stop-opacity: 0;
}

.dsn-yabsm {
  stop-color: var(--svg-color--ff8db0, #FF8DB0);
  stop-opacity: 0;
}

.e-7o89b3n {
  d: path("M24.5 11.062a3.36 3.36 0 1 1-6.719 0a3.36 3.36 0 0 1 6.719 0");
}

.evz7_bcap {
  stop-color: var(--svg-color--dd467c, #DD467C);
}

.f4za6vbvd {
  stop-color: var(--svg-color--faecf1, #FAECF1);
}

.fotxynbjy {
  stop-color: var(--svg-color--e7e5e5, #E7E5E5);
}

.ft5dv1b6b {
  fill: none;
}

.gav2uu2qh {
  stop-color: var(--svg-color--ff5898, #FF5898);
}

.gk0etlbwy {
  d: path("M2.423 29.533C1.716 28.826 2 23.922 4.5 22.922c0 0 2.5-1 4.111.6s.889 3.4.889 3.4c-.707 2.121-3.717 2.964-4.071 2.61c-.195-.195.156-.55 0-.706c-.156-.157-.398.022-1.06.353c-.472.236-1.663.637-1.946.354");
}

.gpq_u0fxt {
  stop-color: var(--svg-color--ff95af, #FF95AF);
}

.gr4yobclw {
  stop-color: var(--svg-color--d46213, #D46213);
}

.hay-ctbfq {
  stop-color: var(--svg-color--e67bc7, #E67BC7);
}

.i85ji08og {
  stop-color: var(--svg-color--6175b9, #6175B9);
  stop-opacity: 0;
}

.iogx_reim {
  d: path("M16.582 19.718c1.2-.442 2.367.725 1.925 1.926l-2.619 7.114a1 1 0 0 1-1.645.362l-5.138-5.138a1 1 0 0 1 .362-1.645z");
}

.j2iz61b_x {
  stop-color: var(--svg-color--ff5794, #FF5794);
}

.jgslamj0f {
  stop-color: var(--svg-color--f63e7a, #F63E7A);
}

.kjjeu1b7n {
  stop-color: var(--svg-color--e7e5e5, #E7E5E5);
  stop-opacity: 0;
}

.ljqipwbpm {
  stop-color: var(--svg-color--ffc484, #FFC484);
  stop-opacity: 0;
}

.loyql_onf {
  stop-color: var(--svg-color--51509f, #51509F);
}

.lpq47wb7s {
  stop-color: var(--svg-color--b5a3a5, #B5A3A5);
}

.mdqnnspup {
  stop-color: var(--svg-color--e14678, #E14678);
}

.njd359bdg {
  stop-color: var(--svg-color--72cdff, #72CDFF);
}

.npyp6cbis {
  d: path("M23.466 11.062a2.326 2.326 0 1 1-4.651 0a2.326 2.326 0 0 1 4.651 0");
}

.nx09lbclh {
  stop-color: var(--svg-color--6175b9, #6175B9);
}

.o66quiqmk {
  stop-color: var(--svg-color--ead2ec, #EAD2EC);
}

.onrgslklk {
  stop-color: var(--svg-color--e14678, #E14678);
  stop-opacity: 0;
}

.onwaqhuoa {
  stop-color: var(--svg-color--ff5971, #FF5971);
}

.pe2b78dkd {
  stop-color: var(--svg-color--ff3190, #FF3190);
}

.pn2wqob6x {
  stop-color: var(--svg-color--93859b, #93859B);
  stop-opacity: 0;
}

.qmxqddxwy {
  d: path("M6.06 20.982a1.5 1.5 0 0 1 2.122 0l3.535 3.536a1.5 1.5 0 0 1-2.12 2.121L6.06 23.104a1.5 1.5 0 0 1 0-2.122");
}

.rzpy97s9g {
  stop-color: var(--svg-color--b5a3a5, #B5A3A5);
  stop-opacity: 0;
}

.s_ddprw4n {
  stop-color: var(--svg-color--ff2982, #FF2982);
}

.scff6ihfv {
  stop-color: var(--svg-color--f83267, #F83267);
}

.sudyg6b8u {
  d: path("M22.4 3.55a.15.15 0 0 1 .162.034l5.885 5.93a.15.15 0 0 1 .033.162c-1.41 3.46-3.353 7.14-5.954 9.742c-2.534 2.534-6.82 4.693-10.69 6.281l-5.491-5.492c1.588-3.87 3.747-8.155 6.281-10.689c2.61-2.61 6.304-4.557 9.773-5.967");
}

.sukq5_z5i {
  stop-color: var(--svg-color--a5959f, #A5959F);
}

.t8_abfbhd {
  stop-color: var(--svg-color--dd467c, #DD467C);
  stop-opacity: 0;
}

.tkio3kb3p {
  stop-color: var(--svg-color--ff5898, #FF5898);
  stop-opacity: 0;
}

.tsqaqmbea {
  stop-color: var(--svg-color--ff5970, #FF5970);
}

.uht1csa4u {
  stop-color: var(--svg-color--b28f96, #B28F96);
  stop-opacity: 0;
}

.uihwb0b-w {
  stop-color: var(--svg-color--ccbbc0, #CCBBC0);
}

.ukllbtb1c {
  stop-color: var(--svg-color--93859b, #93859B);
}

.up-a58x3d {
  stop-color: var(--svg-color--ff8db0, #FF8DB0);
}

.up5sbwbok {
  stop-color: var(--svg-color--ff9542, #FF9542);
}

.v3d8d-moj {
  stop-color: var(--svg-color--a796a0, #A796A0);
}

.v7wijnblg {
  d: path("M29.172 2.871c-.947-.947-2.608-.84-3.818-.424a58 58 0 0 0-2.714 1.007a.1.1 0 0 0-.034.163l5.81 5.849a.1.1 0 0 0 .162-.033a58 58 0 0 0 1.019-2.743c.41-1.194.74-2.654-.425-3.819");
}

.vg8c8edzy {
  stop-color: var(--svg-color--ff3745, #FF3745);
}

.w1ix35bye {
  stop-color: var(--svg-color--e76cbe, #E76CBE);
}

.w2pucn1kk {
  stop-color: var(--svg-color--faecf1, #FAECF1);
  stop-opacity: 0;
}

.w2r1q81dk {
  stop-color: var(--svg-color--8e839a, #8E839A);
}

.wagvrhine {
  stop-color: var(--svg-color--452860, #452860);
}

.wscwbb96t {
  stop-color: var(--svg-color--e67bc7, #E67BC7);
  stop-opacity: 0;
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.x3yi8cciw {
  stop-color: var(--svg-color--e76cbe, #E76CBE);
  stop-opacity: 0;
}

.x4e7_jb9m {
  stop-color: var(--svg-color--66acff, #66ACFF);
}

.xn5-hibsa {
  stop-color: var(--svg-color--b28f96, #B28F96);
}

.xqanwb9ff {
  d: path("m9.205 22.047l5.625-4.407l-3.625 6.438z");
}

.y6-tobyfr {
  stop-color: var(--svg-color--ff5971, #FF5971);
  stop-opacity: 0;
}

.ydnli6bru {
  stop-color: var(--svg-color--ffc484, #FFC484);
}

.zzlt2utle {
  stop-color: var(--svg-color--f93251, #F93251);
  stop-opacity: 0;
}

</style>
