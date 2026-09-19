<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iiirHIc)" class="qu5voya8o"/><path fill="url(#iAwuqBd)" class="qu5voya8o"/><path fill="url(#iUKJDGD)" class="qu5voya8o"/><path fill="url(#iDPIqie)" class="qu5voya8o"/><path fill="url(#iDRayum)" class="qu5voya8o"/><path fill="url(#iiwAjRC)" class="y5u_j5rso"/><path fill="url(#iQHTRre)" class="y5u_j5rso"/><path fill="url(#il6BPed)" class="y5u_j5rso"/><path fill="url(#iyXYz2c)" class="y5u_j5rso"/><path fill="url(#iLebEYd)" class="y5u_j5rso"/><path fill="url(#ieXtRzd)" class="y5u_j5rso"/><path fill="url(#i5c6p5d)" class="y5u_j5rso"/><path fill="url(#iP1cawc)" class="y5u_j5rso"/><g filter="url(#iaj1xEc)"><path class="lckybkg5g"/><path class="p6e5n3bcu"/></g><path class="maykwybgb"/><path fill="url(#iM4V2CD)" class="wo3jsrw2m"/><g filter="url(#i62Asqc)"><path class="m90s3hnxq"/><path class="hon6cgu_l"/></g><path class="jvoe26b7g"/><path fill="url(#iykXWCd)" class="pawe65rni"/><defs><linearGradient id="iiirHIc" x1="1.688" x2="25.938" y1="18.469" y2="18.438" gradientUnits="userSpaceOnUse"><stop offset=".015" class="tnpymlgve"/><stop offset=".049" class="cs353mbgh"/><stop offset=".077" class="h7mfw3b7k"/><stop offset=".142" class="l676qob2p"/><stop offset=".521" class="z8iswmb7c"/><stop offset=".915" class="q6nc0omxm"/></linearGradient><linearGradient id="iAwuqBd" x1="14" x2="15.558" y1="21.688" y2="26.813" gradientUnits="userSpaceOnUse"><stop offset=".782" class="i4hy8lcrx"/><stop offset=".886" class="c61dhpbjm"/><stop offset=".927" class="ebnk667oh"/></linearGradient><linearGradient id="iUKJDGD" x1="19.875" x2="21" y1="15.188" y2="19.25" gradientUnits="userSpaceOnUse"><stop offset=".261" class="xedsjixih"/><stop offset=".76" class="qnbdxq_1c"/><stop offset=".919" class="tscj5d0co"/></linearGradient><linearGradient id="iDPIqie" x1="15.558" x2="16.438" y1="8.063" y2="11.188" gradientUnits="userSpaceOnUse"><stop offset=".261" class="xedsjixih"/><stop offset=".76" class="qnbdxq_1c"/><stop offset=".919" class="tscj5d0co"/></linearGradient><linearGradient id="iDRayum" x1="2.073" x2="4" y1="20.5" y2="20.5" gradientUnits="userSpaceOnUse"><stop class="pwxy-eizd"/><stop offset=".578" class="u6259ibup"/><stop offset="1" class="cu__cxb3r"/></linearGradient><linearGradient id="iiwAjRC" x1="10.969" x2="17.625" y1="3.469" y2="26" gradientUnits="userSpaceOnUse"><stop class="j2_am0__f"/><stop offset=".256" class="j2_am0__f"/><stop offset=".298" class="fkesu-b4f"/><stop offset=".322" class="ky7rzsbeq"/><stop offset=".547" class="v14plrb6f"/><stop offset=".604" class="q71f29bnp"/><stop offset=".621" class="ynqlszbpr"/><stop offset=".972" class="thmjssb2w"/><stop offset="1" class="d-onb_brf"/></linearGradient><linearGradient id="iQHTRre" x1="1.942" x2="3.688" y1="21.625" y2="21.625" gradientUnits="userSpaceOnUse"><stop class="itp2b9afh"/><stop offset=".141" class="odoxxhb1p"/><stop offset="1" class="sswdflbtl"/></linearGradient><linearGradient id="il6BPed" x1="8.5" x2="8.953" y1="6.547" y2="7.031" gradientUnits="userSpaceOnUse"><stop class="e8kn6qben"/><stop offset=".816" class="bwknrcc-h"/></linearGradient><linearGradient id="iyXYz2c" x1="21.297" x2="21.219" y1="3.672" y2="4.023" gradientUnits="userSpaceOnUse"><stop class="e8kn6qben"/><stop offset=".816" class="bwknrcc-h"/></linearGradient><linearGradient id="ieXtRzd" x1="30" x2="27.563" y1="12.856" y2="12.856" gradientUnits="userSpaceOnUse"><stop class="vej6ftbdu"/><stop offset=".042" class="f8q2_bb0q"/><stop offset=".192" class="p_-rz5b3z"/><stop offset="1" class="xto3wnb7f"/></linearGradient><linearGradient id="i5c6p5d" x1="27.609" x2="28.531" y1="20.984" y2="23.219" gradientUnits="userSpaceOnUse"><stop offset=".293" class="e7n2r1brp"/><stop offset=".589" class="gr2coupad"/><stop offset=".945" class="jrkxnkbrl"/></linearGradient><radialGradient id="iLebEYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.61319 -3.0625 0 28.938 12.856)" gradientUnits="userSpaceOnUse"><stop class="crksc3cfg"/><stop offset="1" class="cwrfz72rj"/></radialGradient><radialGradient id="iP1cawc" cx="0" cy="0" r="1" gradientTransform="rotate(87.991 3.45 10.505)scale(1.78235 4.40613)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="ad3g2_yyf"/><stop offset="1" class="mq5bexrjh"/></radialGradient><radialGradient id="iM4V2CD" cx="0" cy="0" r="1" gradientTransform="rotate(113.864 6.995 6.957)scale(4.48002 4.65688)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="imzt59bbw"/><stop offset=".521" class="mhtzu9buv"/><stop offset="1" class="d6ejbbr8l"/></radialGradient><radialGradient id="iykXWCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.28362 -2.07009 0 16.41 3.348)" gradientUnits="userSpaceOnUse"><stop class="tv2k5qbdq"/><stop offset=".901" class="je6_hvbfi"/></radialGradient><filter id="iaj1xEc" width="5.206" height="5.199" x="11.772" y="2.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28590" stdDeviation=".05"/></filter><filter id="i62Asqc" width="3.439" height="3.985" x="14.514" y="1.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28590" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:shortcake" /></template>
<style>
.ad3g2_yyf {
  stop-color: var(--svg-color--b28162, #B28162);
}

.bwknrcc-h {
  stop-color: var(--svg-color--cfb18c, #CFB18C);
  stop-opacity: 0;
}

.c61dhpbjm {
  stop-color: var(--svg-color--ff9c81, #FF9C81);
}

.crksc3cfg {
  stop-color: var(--svg-color--ffded3, #FFDED3);
}

.cs353mbgh {
  stop-color: var(--svg-color--ffb4a4, #FFB4A4);
}

.cu__cxb3r {
  stop-color: var(--svg-color--ffceb1, #FFCEB1);
  stop-opacity: 0;
}

.cwrfz72rj {
  stop-color: var(--svg-color--ffded5, #FFDED5);
  stop-opacity: 0;
}

.d-onb_brf {
  stop-color: var(--svg-color--f9aae0, #F9AAE0);
}

.d6ejbbr8l {
  stop-color: var(--svg-color--f32f59, #F32F59);
  stop-opacity: 0;
}

.e7n2r1brp {
  stop-color: var(--svg-color--ffd6e3, #FFD6E3);
  stop-opacity: 0;
}

.e8kn6qben {
  stop-color: var(--svg-color--b7a287, #B7A287);
}

.ebnk667oh {
  stop-color: var(--svg-color--f67f9d, #F67F9D);
}

.f8q2_bb0q {
  stop-color: var(--svg-color--f6d4bc, #F6D4BC);
}

.fkesu-b4f {
  stop-color: var(--svg-color--fff0cb, #FFF0CB);
}

.ft5dv1b6b {
  fill: none;
}

.gr2coupad {
  stop-color: var(--svg-color--f4a8dc, #F4A8DC);
  stop-opacity: 0;
}

.h7mfw3b7k {
  stop-color: var(--svg-color--ffd6b0, #FFD6B0);
}

.hon6cgu_l {
  fill: var(--svg-color--672a17, #672A17);
  d: path("M16.898 4.469c-.44-.495-.356-1.27-.356-1.27s-.694-.016-1.042-.394c-2.292-2.29.506-.76 1.227-.118c.937.836 1.101 2.305 1.101 2.305c-.078.095.156.492-.094.352s-.836-.875-.836-.875");
}

.i4hy8lcrx {
  stop-color: var(--svg-color--ffb37b, #FFB37B);
  stop-opacity: 0;
}

.imzt59bbw {
  stop-color: var(--svg-color--ff6a83, #FF6A83);
}

.itp2b9afh {
  stop-color: var(--svg-color--c69c9b, #C69C9B);
}

.j2_am0__f {
  stop-color: var(--svg-color--f3cfa2, #F3CFA2);
}

.je6_hvbfi {
  stop-color: var(--svg-color--afea63, #AFEA63);
  stop-opacity: 0;
}

.jrkxnkbrl {
  stop-color: var(--svg-color--e596dd, #E596DD);
}

.jvoe26b7g {
  fill: var(--svg-color--8dc527, #8DC527);
  d: path("M16.94 4.372c-.44-.495-.32-1.25-.32-1.25s-.714 0-1.062-.38l-1.193-1.235c-.064-.088 0-.183.088-.248c0 0 .701-.531 1.789.16c.602.444 1.746 1.862 2.036 2.458c.527.9-.146 1.673-.146 1.673c-.077.095-.167.122-.276 0z");
}

.ky7rzsbeq {
  stop-color: var(--svg-color--ffd5ce, #FFD5CE);
}

.l676qob2p {
  stop-color: var(--svg-color--ffd9b0, #FFD9B0);
}

.lckybkg5g {
  fill: var(--svg-color--d52d26, #D52D26);
  d: path("M12.664 7.578c-.64 0-.86-.36-.773-1.024c.665-9.505 8.843 1.024 2.736 1.024z");
}

.m90s3hnxq {
  fill: var(--svg-color--8dc527, #8DC527);
  d: path("M16.898 4.469c-.44-.495-.356-1.27-.356-1.27s-.694-.016-1.042-.394c-2.292-2.29.506-.76 1.227-.118c.937.836 1.101 2.305 1.101 2.305c-.078.095.156.492-.094.352s-.836-.875-.836-.875");
}

.maykwybgb {
  fill: var(--svg-color--d52d26, #D52D26);
  d: path("M12.024 4.517c.126-.628.335-2.402 2.516-2.836l2.356 1.207l.858 2.575C16.95 7.624 15.29 7.47 14.627 7.47h-1.963c-.64 0-1.004-.364-.916-1.033z");
}

.mhtzu9buv {
  stop-color: var(--svg-color--ee2d47, #EE2D47);
}

.mq5bexrjh {
  stop-color: var(--svg-color--c29a79, #C29A79);
  stop-opacity: 0;
}

.odoxxhb1p {
  stop-color: var(--svg-color--dda4b5, #DDA4B5);
}

.p_-rz5b3z {
  stop-color: var(--svg-color--ffded4, #FFDED4);
}

.p6e5n3bcu {
  fill: var(--svg-color--a23828, #A23828);
  d: path("M12.664 7.578c-.64 0-.86-.36-.773-1.024c.665-9.505 8.843 1.024 2.736 1.024z");
}

.pawe65rni {
  d: path("M16.94 4.372c-.44-.495-.32-1.25-.32-1.25s-.714 0-1.062-.38l-1.193-1.235c-.064-.088 0-.183.088-.248c0 0 .701-.531 1.789.16c.602.444 1.746 1.862 2.036 2.458c.527.9-.146 1.673-.146 1.673c-.077.095-.167.122-.276 0z");
}

.pwxy-eizd {
  stop-color: var(--svg-color--c29677, #C29677);
}

.q6nc0omxm {
  stop-color: var(--svg-color--ff9d50, #FF9D50);
}

.q71f29bnp {
  stop-color: var(--svg-color--fffee2, #FFFEE2);
}

.qnbdxq_1c {
  stop-color: var(--svg-color--e4794b, #E4794B);
}

.qu5voya8o {
  d: path("m3.627 29.82l24.63-7.068l.787-.724V7.978l-1.022-1.98l-25.95 7.345v14.944c0 1.225.496 1.785 1.555 1.532");
}

.sswdflbtl {
  stop-color: var(--svg-color--f8b6d3, #F8B6D3);
  stop-opacity: 0;
}

.thmjssb2w {
  stop-color: var(--svg-color--ffe3e3, #FFE3E3);
}

.tnpymlgve {
  stop-color: var(--svg-color--ca957f, #CA957F);
}

.tscj5d0co {
  stop-color: var(--svg-color--e4794b, #E4794B);
  stop-opacity: 0;
}

.tv2k5qbdq {
  stop-color: var(--svg-color--b1eb67, #B1EB67);
}

.u6259ibup {
  stop-color: var(--svg-color--feb3a3, #FEB3A3);
}

.v14plrb6f {
  stop-color: var(--svg-color--ffd6cf, #FFD6CF);
}

.vej6ftbdu {
  stop-color: var(--svg-color--d6c0aa, #D6C0AA);
}

.wo3jsrw2m {
  d: path("M12.024 4.517c.126-.628.335-2.402 2.516-2.836l2.356 1.207l.858 2.575C16.95 7.624 15.29 7.47 14.627 7.47h-1.963c-.64 0-1.004-.364-.916-1.033z");
}

.xedsjixih {
  stop-color: var(--svg-color--f08456, #F08456);
  stop-opacity: 0;
}

.xto3wnb7f {
  stop-color: var(--svg-color--ffded3, #FFDED3);
  stop-opacity: 0;
}

.y5u_j5rso {
  d: path("m13.034 2.508l-9.97 9.223c-1.946 1.662-.935 2.811.934 2.399l23.026-6.606c.592-.14.966-.186.966.499v4.02c0 .687.064 1.045-.374 1.183c0 0-22.205 6.694-22.683 6.824s-1.54.328-1.87.28c-.329-.048-.747-.28-.934-.28s-.187.108-.187.623v2.167c0 .163.14.268.14.268a2.48 2.48 0 0 0 1.916.307l23.245-6.73c.373-.094.747.156.747.623v5.298c0 .322.195.339.332.322c.992-.286 1.678-.873 1.678-1.881V8.023c0-.853-.617-2.278-2.01-2.71L16.96 2.725c-1.047-.218-3.072-.88-3.926-.218");
}

.ynqlszbpr {
  stop-color: var(--svg-color--ffe4e5, #FFE4E5);
}

.z8iswmb7c {
  stop-color: var(--svg-color--ffc18a, #FFC18A);
}

</style>
