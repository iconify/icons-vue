<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iJeR0He)"><path stroke="url(#ikaxh0d)" class="s81267brp"/></g><g filter="url(#itECbKc)"><path stroke="url(#iQKGShd)" class="qsqngv7hy"/></g><path fill="url(#ibQFcQQ)" class="r1mpw12ha"/><path fill="url(#isncbit)" class="r1mpw12ha"/><path fill="url(#irWWpzb)" class="r1mpw12ha"/><path fill="url(#ijdh88b)" class="r1mpw12ha"/><path fill="url(#i39V3xd)" class="r1mpw12ha"/><path fill="url(#iYGrQ7b)" class="bu0sklw7w"/><g filter="url(#iUPsUTY)"><rect fill="url(#iUu97Td)" class="t_u095pqs"/><rect fill="url(#iDkuMvc)" class="t_u095pqs"/><rect fill="url(#izh9xFc)" class="t_u095pqs"/></g><rect fill="url(#i8dOBfd)" class="t_u095pqs"/><path fill="url(#i8yb4Ma)" class="fe0lhc7ya"/><path fill="url(#i3D5CNe)" class="fe0lhc7ya"/><path fill="url(#ihcLlnL)" class="a9l6kxb9t"/><path fill="url(#iNaZYzk)" class="a9l6kxb9t"/><g clip-rule="evenodd" filter="url(#iTkMsZc)" class="d2kvgvbvc"><path class="ctslpi9xf"/><path fill="url(#iTHQeXd)" class="d32nvabwo"/></g><path fill="url(#irKnpre)" class="vu-f6hbmd"/><g filter="url(#irXQdrd)"><rect fill="url(#iuJyp6Q)" class="mdzomlsas"/><rect fill="url(#iBZ481d)" class="mdzomlsas"/><rect fill="url(#iMjQWUb)" class="mdzomlsas"/><rect fill="url(#iaThQ9d)" class="mdzomlsas"/></g><g filter="url(#i8SrZKe)"><ellipse fill="url(#iZaGqvc)" class="cejd3_uzq"/></g><g filter="url(#iSQF9Sd)"><ellipse fill="url(#iqjFREb)" class="r-c4lrb0o"/></g><g filter="url(#iqsLj4c)"><circle stroke="url(#iMcQX4R)" class="zvjij3b1m"/></g><defs><radialGradient id="ibQFcQQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.8726 -8.9457 0 15.006 10.92)" gradientUnits="userSpaceOnUse"><stop offset=".318" class="aexyk5bdt"/><stop offset="1" class="rz8w5acwk"/></radialGradient><radialGradient id="irWWpzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .73438 -6.21875 0 13.728 19.516)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="z2ktkrxly"/><stop offset="1" class="ixprkzb_o"/></radialGradient><radialGradient id="ijdh88b" cx="0" cy="0" r="1" gradientTransform="matrix(-10.25008 11.5 -10.47145 -9.33333 16.759 13.547)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="wwn5t1bef"/><stop offset="1" class="j3qdeu5ep"/></radialGradient><radialGradient id="i39V3xd" cx="0" cy="0" r="1" gradientTransform="rotate(140.826 .105 12.58)scale(1.08838 .91252)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="r5d7w3htd"/><stop offset="1" class="gc4k_obxv"/></radialGradient><radialGradient id="iYGrQ7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -5.72222 0 14.946 20.735)" gradientUnits="userSpaceOnUse"><stop class="bssts16sf"/><stop offset="1" class="wy3u-kbnl"/></radialGradient><radialGradient id="iDkuMvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59375 14.0625 0 12.259 29.922)" gradientUnits="userSpaceOnUse"><stop class="ckpk1zbfo"/><stop offset="1" class="o44433b6a"/></radialGradient><radialGradient id="izh9xFc" cx="0" cy="0" r="1" gradientTransform="matrix(-13.5397 0 0 -4.56879 15.298 27.329)" gradientUnits="userSpaceOnUse"><stop offset=".82" class="k83ro35ns"/><stop offset="1" class="fbrohtl6b"/></radialGradient><radialGradient id="i8yb4Ma" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -6.0625 0 14.946 13.141)" gradientUnits="userSpaceOnUse"><stop offset=".408" class="bssts16sf"/><stop offset="1" class="wy3u-kbnl"/></radialGradient><radialGradient id="i3D5CNe" cx="0" cy="0" r="1" gradientTransform="rotate(142.745 7.039 10.003)scale(2.78756 .55737)" gradientUnits="userSpaceOnUse"><stop class="whmlqxjmm"/><stop offset="1" class="mj_h4gboi"/></radialGradient><radialGradient id="ihcLlnL" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -6.0625 0 14.946 15.672)" gradientUnits="userSpaceOnUse"><stop offset=".408" class="bssts16sf"/><stop offset="1" class="wy3u-kbnl"/></radialGradient><radialGradient id="iNaZYzk" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60938 1.24999 -.2451 -.31557 15.024 16.391)" gradientUnits="userSpaceOnUse"><stop class="whmlqxjmm"/><stop offset="1" class="mj_h4gboi"/></radialGradient><radialGradient id="iTHQeXd" cx="0" cy="0" r="1" gradientTransform="rotate(173.367 5.717 10.232)scale(1.3528 .41465)" gradientUnits="userSpaceOnUse"><stop class="ta_ttccqj"/><stop offset="1" class="g6cz7mfmj"/></radialGradient><radialGradient id="irKnpre" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -6.0625 0 14.946 18.204)" gradientUnits="userSpaceOnUse"><stop offset=".408" class="bssts16sf"/><stop offset="1" class="wy3u-kbnl"/></radialGradient><radialGradient id="iBZ481d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59375 14.0625 0 12.259 11.547)" gradientUnits="userSpaceOnUse"><stop class="ckpk1zbfo"/><stop offset="1" class="o44433b6a"/></radialGradient><radialGradient id="iMjQWUb" cx="0" cy="0" r="1" gradientTransform="matrix(-13.5397 0 0 -4.56879 15.298 8.954)" gradientUnits="userSpaceOnUse"><stop offset=".82" class="k83ro35ns"/><stop offset="1" class="fbrohtl6b"/></radialGradient><radialGradient id="iaThQ9d" cx="0" cy="0" r="1" gradientTransform="rotate(64.546 6.238 11.92)scale(12.4322 18.7456)" gradientUnits="userSpaceOnUse"><stop offset=".851" class="hh13o8xxv"/><stop offset=".957" class="b-2zpmtyk"/></radialGradient><radialGradient id="iZaGqvc" cx="0" cy="0" r="1" gradientTransform="matrix(-11.3693 0 0 -1.92656 20.346 8.14)" gradientUnits="userSpaceOnUse"><stop class="m9e_aac3i"/><stop offset="1" class="jbtnvf6al"/></radialGradient><radialGradient id="iqjFREb" cx="0" cy="0" r="1" gradientTransform="matrix(-11.3693 0 0 -1.92656 20.346 26.523)" gradientUnits="userSpaceOnUse"><stop class="m9e_aac3i"/><stop offset="1" class="jbtnvf6al"/></radialGradient><filter id="iJeR0He" width="8.153" height="11.662" x="18.112" y="3.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.380392 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4353"/></filter><filter id="itECbKc" width="5.388" height="4.926" x="20.782" y="3.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4353" stdDeviation=".2"/></filter><filter id="iUPsUTY" width="19.313" height="5.188" x="2.603" y="24.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.662745 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4353"/></filter><filter id="iTkMsZc" width="22.045" height="18.589" x="7.936" y="4.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.419608 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4353"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.572549 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4353" result="effect2_innerShadow_18_4353"/></filter><filter id="irXQdrd" width="19.313" height="5.188" x="2.603" y="6.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.662745 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4353"/></filter><filter id="i8SrZKe" width="14.51" height="4.921" x="7.727" y="5.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4353" stdDeviation=".625"/></filter><filter id="iSQF9Sd" width="14.51" height="4.921" x="7.727" y="24.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4353" stdDeviation=".625"/></filter><filter id="iqsLj4c" width="4.455" height="4.455" x="25.822" y="4.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4353" stdDeviation=".25"/></filter><linearGradient id="ikaxh0d" x1="25.321" x2="20.696" y1="5.047" y2="14.922" gradientUnits="userSpaceOnUse"><stop class="v_a0om-aj"/><stop offset="1" class="yf-t06bbm"/></linearGradient><linearGradient id="iQKGShd" x1="25.415" x2="20.54" y1="7.641" y2="3.922" gradientUnits="userSpaceOnUse"><stop class="gr5-dbbbi"/><stop offset="1" class="hwx58uf5j"/></linearGradient><linearGradient id="isncbit" x1="12.259" x2="12.259" y1="11.468" y2="11.906" gradientUnits="userSpaceOnUse"><stop class="r7iwa5b6b"/><stop offset="1" class="secqv3bvp"/></linearGradient><linearGradient id="iUu97Td" x1="7.134" x2="21.915" y1="28.797" y2="28.797" gradientUnits="userSpaceOnUse"><stop class="bhzg1ebhx"/><stop offset="1" class="zzs2m_bvn"/></linearGradient><linearGradient id="i8dOBfd" x1="12.259" x2="12.259" y1="30.563" y2="28.438" gradientUnits="userSpaceOnUse"><stop class="ieupqyokn"/><stop offset="1" class="slskt7qdx"/></linearGradient><linearGradient id="iuJyp6Q" x1="7.134" x2="21.915" y1="10.422" y2="10.422" gradientUnits="userSpaceOnUse"><stop class="bhzg1ebhx"/><stop offset="1" class="zzs2m_bvn"/></linearGradient><linearGradient id="iMcQX4R" x1="29.278" x2="26.465" y1="5.728" y2="7.864" gradientUnits="userSpaceOnUse"><stop class="y_0t0gb-g"/><stop offset=".312" class="ofbul0bbu"/><stop offset=".764" class="ofbul0bbu"/><stop offset="1" class="y_0t0gb-g"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:thread" /></template>
<style>
.a9l6kxb9t {
  d: path("M5.23 17.329v-1.282h14.057v1.282z");
}

.aexyk5bdt {
  stop-color: var(--svg-color--45b3ff, #45B3FF);
}

.b-2zpmtyk {
  stop-color: var(--svg-color--b17273, #B17273);
}

.bhzg1ebhx {
  stop-color: var(--svg-color--d28241, #D28241);
}

.bssts16sf {
  stop-color: var(--svg-color--347ae9, #347AE9);
}

.bu0sklw7w {
  d: path("M5.23 22.391V21.11h14.057v1.281z");
}

.cejd3_uzq {
  cx: 14.982px;
  cy: 8.141px;
  rx: 6.005px;
  ry: 1.211px;
}

.ckpk1zbfo {
  stop-color: var(--svg-color--c1675c, #C1675C);
}

.ctslpi9xf {
  fill: var(--svg-color--c7b7d8, #C7B7D8);
  d: path("M29.98 6.98c-.01 1.243-1.007 2.242-2.224 2.231a2.2 2.2 0 0 1-.91-.208a.21.21 0 0 0-.22.02L8.82 22.78a.542.542 0 0 1-.7-.83l17.2-14.17l.206-.177a.25.25 0 0 0 .081-.232a2.3 2.3 0 0 1-.036-.43c.01-1.242 1.007-2.24 2.224-2.23s2.196 1.027 2.185 2.27m-1.47-.012a.743.743 0 0 1-.741.743a.74.74 0 0 1-.728-.756a.74.74 0 0 1 .741-.744a.743.743 0 0 1 .728.757");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d32nvabwo {
  d: path("M29.98 6.98c-.01 1.243-1.007 2.242-2.224 2.231a2.2 2.2 0 0 1-.91-.208a.21.21 0 0 0-.22.02L8.82 22.78a.542.542 0 0 1-.7-.83l17.2-14.17l.206-.177a.25.25 0 0 0 .081-.232a2.3 2.3 0 0 1-.036-.43c.01-1.242 1.007-2.24 2.224-2.23s2.196 1.027 2.185 2.27m-1.47-.012a.743.743 0 0 1-.741.743a.74.74 0 0 1-.728-.756a.74.74 0 0 1 .741-.744a.743.743 0 0 1 .728.757");
}

.fbrohtl6b {
  stop-color: var(--svg-color--a65841, #A65841);
}

.fe0lhc7ya {
  d: path("M5.23 14.797v-1.28h14.057v1.28z");
}

.ft5dv1b6b {
  fill: none;
}

.g6cz7mfmj {
  stop-color: var(--svg-color--9d72bd, #9D72BD);
  stop-opacity: 0;
}

.gc4k_obxv {
  stop-color: var(--svg-color--2c5ab2, #2C5AB2);
  stop-opacity: 0;
}

.gr5-dbbbi {
  stop-color: var(--svg-color--619ffa, #619FFA);
}

.hh13o8xxv {
  stop-color: var(--svg-color--b17273, #B17273);
  stop-opacity: 0;
}

.hwx58uf5j {
  stop-color: var(--svg-color--619ffa, #619FFA);
  stop-opacity: 0;
}

.ieupqyokn {
  stop-color: var(--svg-color--c3517c, #C3517C);
}

.ixprkzb_o {
  stop-color: var(--svg-color--193ebb, #193EBB);
  stop-opacity: 0;
}

.j3qdeu5ep {
  stop-color: var(--svg-color--2e5eae, #2E5EAE);
}

.jbtnvf6al {
  stop-color: var(--svg-color--ffd88c, #FFD88C);
  stop-opacity: 0;
}

.k83ro35ns {
  stop-color: var(--svg-color--a65841, #A65841);
  stop-opacity: 0;
}

.m9e_aac3i {
  stop-color: var(--svg-color--ffd88c, #FFD88C);
}

.mdzomlsas {
  width: 19.313px;
  height: 5.188px;
  x: 2.603px;
  y: 6.36px;
  rx: 2.594px;
}

.mj_h4gboi {
  stop-color: var(--svg-color--2658a2, #2658A2);
  stop-opacity: 0;
}

.o44433b6a {
  stop-color: var(--svg-color--c1675c, #C1675C);
  stop-opacity: 0;
}

.ofbul0bbu {
  stop-color: var(--svg-color--e6e2ec, #E6E2EC);
  stop-opacity: 0;
}

.qsqngv7hy {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M21.196 3.922c1.021.115 3.657 1.094 4.453 3.97");
}

.r-c4lrb0o {
  cx: 14.982px;
  cy: 26.523px;
  rx: 6.005px;
  ry: 1.211px;
}

.r1mpw12ha {
  d: path("M5.23 10.672h14.057V26.11H5.23z");
}

.r5d7w3htd {
  stop-color: var(--svg-color--2c5ab2, #2C5AB2);
}

.r7iwa5b6b {
  stop-color: var(--svg-color--535fae, #535FAE);
}

.rz8w5acwk {
  stop-color: var(--svg-color--3079d4, #3079D4);
}

.s81267brp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-2px, 1.2px);
  d: path("M20.127 3.945a5.163 5.163 0 0 1 .603 10.307h-2.018");
}

.secqv3bvp {
  stop-color: var(--svg-color--535fae, #535FAE);
  stop-opacity: 0;
}

.slskt7qdx {
  stop-color: var(--svg-color--c3517c, #C3517C);
  stop-opacity: 0;
}

.t_u095pqs {
  width: 19.313px;
  height: 5.188px;
  x: 2.603px;
  y: 24.735px;
  rx: 2.594px;
}

.ta_ttccqj {
  stop-color: var(--svg-color--9d72bd, #9D72BD);
}

.v_a0om-aj {
  stop-color: var(--svg-color--3c7ce1, #3C7CE1);
}

.vu-f6hbmd {
  d: path("M5.23 19.86v-1.281h14.057v1.28z");
}

.whmlqxjmm {
  stop-color: var(--svg-color--2658a2, #2658A2);
}

.wwn5t1bef {
  stop-color: var(--svg-color--2e5eae, #2E5EAE);
  stop-opacity: 0;
}

.wy3u-kbnl {
  stop-color: var(--svg-color--2c569f, #2C569F);
}

.y_0t0gb-g {
  stop-color: var(--svg-color--e6e2ec, #E6E2EC);
}

.yf-t06bbm {
  stop-color: var(--svg-color--3464c6, #3464C6);
}

.z2ktkrxly {
  stop-color: var(--svg-color--193ebb, #193EBB);
}

.zvjij3b1m {
  cx: 28.049px;
  cy: 6.813px;
  r: 1.478px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.zzs2m_bvn {
  stop-color: var(--svg-color--e7af70, #E7AF70);
}

</style>
