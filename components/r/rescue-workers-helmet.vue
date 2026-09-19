<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#iUezsDc)" class="d2kvgvbvc"><path class="pzbijyppr"/><path fill="url(#im2zlge)" class="r95ssrbci"/><path fill="url(#iFjSvcc)" class="r95ssrbci"/></g><g filter="url(#iN8HkCb)"><path fill="url(#iaihfee)" class="ab_e_tb0z"/><path fill="url(#iBVaGjd)" class="ab_e_tb0z"/><path fill="url(#iqVpCSd)" class="ab_e_tb0z"/><path fill="url(#iR647Cb)" class="ab_e_tb0z"/></g><g filter="url(#iwoK45Q)"><path fill="url(#ixu80Ub)" class="tudv18gti"/><path fill="url(#iunt0xe)" class="tudv18gti"/><path fill="url(#iXRL44c)" class="tudv18gti"/></g><path fill="url(#iSWaO0c)" class="tudv18gti"/><path fill="url(#iAQaLFe)" class="tudv18gti"/><g filter="url(#itzzcWc)"><rect fill="url(#ilLZP1b)" class="f0bk8fbfs"/><rect fill="url(#iXV1pcv)" class="f0bk8fbfs"/><rect fill="url(#iBhhAWd)" class="f0bk8fbfs"/></g><path fill="url(#izBp6me)" class="u7r8cui5n"/><path fill="url(#ik3BFQd)" class="z76n4tbau"/><path fill="url(#ivMDv6d)" class="ca18m1rcx"/><path fill="url(#iyqKOnQ)" class="azoue1ovg"/><g filter="url(#iX8YUFc)"><path class="d11mowbkb"/></g><g filter="url(#izcllBb)"><path class="z5qhdnb4i"/></g><path fill="url(#ie6PYOc)" class="xs4bcy-ik"/><path fill="url(#i6J9SUd)" class="xs4bcy-ik"/><g filter="url(#ijXFUGb)"><path stroke="url(#iLzo7ge)" class="mfhindlfi"/></g><defs><radialGradient id="im2zlge" cx="0" cy="0" r="1" gradientTransform="rotate(-157.788 14.243 10.478)scale(2.02529 9.55412)" gradientUnits="userSpaceOnUse"><stop class="bu01nbb_r"/><stop offset="1" class="r3s1d60mx"/></radialGradient><radialGradient id="iBVaGjd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.125 7.34375 0 22.516 15.375)" gradientUnits="userSpaceOnUse"><stop class="f705yac7f"/><stop offset="1" class="sq9hfxf1r"/></radialGradient><radialGradient id="iqVpCSd" cx="0" cy="0" r="1" gradientTransform="matrix(5.4375 -2 1.6937 4.60476 20.828 9.531)" gradientUnits="userSpaceOnUse"><stop class="jrlax700j"/><stop offset="1" class="ay4v0bbmz"/></radialGradient><radialGradient id="iR647Cb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.1875 -3.21326 0 12.453 8.438)" gradientUnits="userSpaceOnUse"><stop class="rpva18bpx"/><stop offset="1" class="bla4ydb_m"/></radialGradient><radialGradient id="iXRL44c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 2.83259 0 19.203 9.531)" gradientUnits="userSpaceOnUse"><stop class="kp81rabeu"/><stop offset="1" class="nmfn8rqzk"/></radialGradient><radialGradient id="iSWaO0c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8125 1.46874 -2.52845 -3.12027 20.484 3.188)" gradientUnits="userSpaceOnUse"><stop class="izdpmq3br"/><stop offset="1" class="kguto3rwr"/></radialGradient><radialGradient id="iAQaLFe" cx="0" cy="0" r="1" gradientTransform="matrix(1.64062 .51562 -1.22311 3.89171 11.016 3.813)" gradientUnits="userSpaceOnUse"><stop class="oah2tf3jc"/><stop offset="1" class="sd5phsbht"/></radialGradient><radialGradient id="iXV1pcv" cx="0" cy="0" r="1" gradientTransform="matrix(-6.79687 0 0 -1.0625 22.672 16.313)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="kp81rabeu"/><stop offset="1" class="nmfn8rqzk"/></radialGradient><radialGradient id="iBhhAWd" cx="0" cy="0" r="1" gradientTransform="rotate(38.66 -19.016 14.1)scale(6.60322 11.5569)" gradientUnits="userSpaceOnUse"><stop class="b5-5c4m7v"/><stop offset="1" class="elf9w8b3x"/></radialGradient><radialGradient id="ie6PYOc" cx="0" cy="0" r="1" gradientTransform="rotate(33.982 -38.07 26.366)scale(2.62779 8.59237)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="ryfge55yv"/><stop offset="1" class="y6_nbs_0t"/></radialGradient><radialGradient id="i6J9SUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01563 1.0625 -.74832 -.7153 22.203 25.125)" gradientUnits="userSpaceOnUse"><stop class="jwe04vgtq"/><stop offset="1" class="oh34xcbbr"/></radialGradient><linearGradient id="iFjSvcc" x1="15.828" x2="15.828" y1="18.313" y2="21.516" gradientUnits="userSpaceOnUse"><stop class="movk704km"/><stop offset="1" class="slblbqb7a"/></linearGradient><linearGradient id="iaihfee" x1="21.078" x2="11.859" y1="13.5" y2="13.5" gradientUnits="userSpaceOnUse"><stop class="zstr-2b3h"/><stop offset="1" class="vqd2o9bjj"/></linearGradient><linearGradient id="ixu80Ub" x1="15.938" x2="15.938" y1="2.109" y2="14.969" gradientUnits="userSpaceOnUse"><stop class="qhoe4ug1b"/><stop offset="1" class="c_eztsj_x"/></linearGradient><linearGradient id="iunt0xe" x1="15.938" x2="15.938" y1="2.109" y2="4.219" gradientUnits="userSpaceOnUse"><stop class="epdbjab-w"/><stop offset="1" class="o7umo_ezg"/></linearGradient><linearGradient id="ilLZP1b" x1="15.875" x2="16.172" y1="14.969" y2="18.938" gradientUnits="userSpaceOnUse"><stop offset=".398" class="ltjlrdl2g"/><stop offset="1" class="jhasufb8d"/></linearGradient><linearGradient id="izBp6me" x1="17.152" x2="15.281" y1="11.753" y2="11.753" gradientUnits="userSpaceOnUse"><stop class="jnbrpkb3b"/><stop offset=".918" class="u99501b6b"/></linearGradient><linearGradient id="ik3BFQd" x1="14.273" x2="14.273" y1="11.304" y2="8.874" gradientUnits="userSpaceOnUse"><stop class="onf_p2kru"/><stop offset="1" class="eyc6_naky"/></linearGradient><linearGradient id="ivMDv6d" x1="17.152" x2="15.281" y1="8.424" y2="8.424" gradientUnits="userSpaceOnUse"><stop class="jnbrpkb3b"/><stop offset=".918" class="u99501b6b"/></linearGradient><linearGradient id="iyqKOnQ" x1="17.592" x2="17.592" y1="11.304" y2="8.874" gradientUnits="userSpaceOnUse"><stop class="onf_p2kru"/><stop offset="1" class="eyc6_naky"/></linearGradient><linearGradient id="iLzo7ge" x1="11.141" x2="23.203" y1="25.906" y2="26.813" gradientUnits="userSpaceOnUse"><stop class="dx98p0bqm"/><stop offset="1" class="r-dv870qv"/></linearGradient><filter id="iUezsDc" width="16.509" height="15.994" x="7.573" y="14.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.556863 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17601"/></filter><filter id="iN8HkCb" width="21.063" height="12.938" x="5.828" y="3.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.290196 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17601"/></filter><filter id="iwoK45Q" width="10.344" height="15.766" x="11.391" y="1.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-.5"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.184314 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17601"/></filter><filter id="itzzcWc" width="24.531" height="4.319" x="3.609" y="14.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.356863 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17601"/></filter><filter id="iX8YUFc" width="4.612" height="7.792" x="20.171" y="19.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17601" stdDeviation=".5"/></filter><filter id="izcllBb" width="13.858" height="6.983" x="8.902" y="24.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.172549 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17601"/></filter><filter id="ijXFUGb" width="11.369" height="3.472" x="10.316" y="24.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17601" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rescue-workers-helmet" /></template>
<style>
.ab_e_tb0z {
  d: path("M5.828 10.563c0-4.688 3.265-6.657 6.578-6.657h6.781c3.314 0 6.704 1.735 6.704 6.656v6.282H5.828z");
}

.ay4v0bbmz {
  stop-color: var(--svg-color--ff5c7e, #FF5C7E);
  stop-opacity: 0;
}

.azoue1ovg {
  d: path("m17.146 11.304l-1.228-1.215l1.234-1.215h.9a1.215 1.215 0 1 1 0 2.43z");
}

.b5-5c4m7v {
  stop-color: var(--svg-color--b14c4c, #B14C4C);
}

.bla4ydb_m {
  stop-color: var(--svg-color--a91726, #A91726);
  stop-opacity: 0;
}

.bu01nbb_r {
  stop-color: var(--svg-color--e4dcec, #E4DCEC);
}

.c_eztsj_x {
  stop-color: var(--svg-color--f62437, #F62437);
}

.ca18m1rcx {
  d: path("m17.152 8.88l-1.23 1.209l-1.2-1.214v-.9a1.215 1.215 0 1 1 2.43 0z");
}

.d11mowbkb {
  stroke: var(--svg-color--e6deeb, #E6DEEB);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M23.457 20.585c.007 1.03-.376 3.5-1.961 5.141");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dx98p0bqm {
  stop-color: var(--svg-color--83515b, #83515B);
}

.elf9w8b3x {
  stop-color: var(--svg-color--c8292a, #C8292A);
  stop-opacity: 0;
}

.epdbjab-w {
  stop-color: var(--svg-color--e75050, #E75050);
}

.eyc6_naky {
  stop-color: var(--svg-color--dbd6df, #DBD6DF);
}

.f0bk8fbfs {
  width: 24.531px;
  height: 3.969px;
  x: 3.609px;
  y: 14.969px;
  rx: 1.984px;
}

.f705yac7f {
  stop-color: var(--svg-color--ff394a, #FF394A);
}

.ft5dv1b6b {
  fill: none;
}

.izdpmq3br {
  stop-color: var(--svg-color--ff6262, #FF6262);
}

.jhasufb8d {
  stop-color: var(--svg-color--f71b54, #F71B54);
}

.jnbrpkb3b {
  stop-color: var(--svg-color--d2d0d6, #D2D0D6);
}

.jrlax700j {
  stop-color: var(--svg-color--ff5c7e, #FF5C7E);
}

.jwe04vgtq {
  stop-color: var(--svg-color--9b7173, #9B7173);
}

.kguto3rwr {
  stop-color: var(--svg-color--ff6262, #FF6262);
  stop-opacity: 0;
}

.kp81rabeu {
  stop-color: var(--svg-color--ff5a5a, #FF5A5A);
}

.ltjlrdl2g {
  stop-color: var(--svg-color--fe2324, #FE2324);
}

.mfhindlfi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M11.14 25.625c1.573 1.375 5.72 3.3 9.72 0");
}

.movk704km {
  stop-color: var(--svg-color--a68fa9, #A68FA9);
}

.nmfn8rqzk {
  stop-color: var(--svg-color--ff5a5a, #FF5A5A);
  stop-opacity: 0;
}

.o7umo_ezg {
  stop-color: var(--svg-color--e75050, #E75050);
  stop-opacity: 0;
}

.oah2tf3jc {
  stop-color: var(--svg-color--b56e6e, #B56E6E);
}

.oh34xcbbr {
  stop-color: var(--svg-color--9b7173, #9B7173);
  stop-opacity: 0;
}

.onf_p2kru {
  stop-color: var(--svg-color--e9e8eb, #E9E8EB);
}

.pzbijyppr {
  fill: var(--svg-color--c7b8ce, #C7B8CE);
  d: path("M7.573 14.019h16.51v6.739a8.255 8.255 0 0 1-16.51 0zm1.9 1.9v4.839a6.355 6.355 0 0 0 12.71 0v-4.84z");
}

.qhoe4ug1b {
  stop-color: var(--svg-color--fb2626, #FB2626);
}

.r-dv870qv {
  stop-color: var(--svg-color--83515b, #83515B);
  stop-opacity: 0;
}

.r3s1d60mx {
  stop-color: var(--svg-color--e4dcec, #E4DCEC);
  stop-opacity: 0;
}

.r95ssrbci {
  d: path("M7.573 14.019h16.51v6.739a8.255 8.255 0 0 1-16.51 0zm1.9 1.9v4.839a6.355 6.355 0 0 0 12.71 0v-4.84z");
}

.rpva18bpx {
  stop-color: var(--svg-color--a91726, #A91726);
}

.ryfge55yv {
  stop-color: var(--svg-color--5e393f, #5E393F);
}

.sd5phsbht {
  stop-color: var(--svg-color--b56e6e, #B56E6E);
  stop-opacity: 0;
}

.slblbqb7a {
  stop-color: var(--svg-color--a68fa9, #A68FA9);
  stop-opacity: 0;
}

.sq9hfxf1r {
  stop-color: var(--svg-color--ff394a, #FF394A);
  stop-opacity: 0;
}

.tudv18gti {
  d: path("M11.39 4.91a2.8 2.8 0 0 1 2.8-2.8h3.494a2.8 2.8 0 0 1 2.8 2.8v12.465h-9.093z");
}

.u7r8cui5n {
  d: path("m17.152 11.297l-1.23-1.208l-1.2 1.214v.9a1.215 1.215 0 0 0 2.43 0z");
}

.u99501b6b {
  stop-color: var(--svg-color--e9e7ec, #E9E7EC);
}

.vqd2o9bjj {
  stop-color: var(--svg-color--b82048, #B82048);
}

.xs4bcy-ik {
  d: path("M8.973 25.355c-.137.575-.099 1.23.311 1.682c1.694 1.868 3.906 2.825 6.537 2.825c2.627 0 4.856-.954 6.552-2.825c.414-.456.45-1.128.319-1.685l-1.485-1.215c-.495-.004-.964.054-1.488.515c-1.203 1.145-2.231 1.61-3.898 1.61c-1.662 0-2.789-.563-3.894-1.606c-.41-.41-.951-.551-1.473-.523z");
}

.y6_nbs_0t {
  stop-color: var(--svg-color--5e393f, #5E393F);
  stop-opacity: 0;
}

.z5qhdnb4i {
  fill: var(--svg-color--813470, #813470);
  d: path("M8.973 25.355c-.137.575-.099 1.23.311 1.682c1.694 1.868 3.906 2.825 6.537 2.825c2.627 0 4.856-.954 6.552-2.825c.414-.456.45-1.128.319-1.685l-1.485-1.215c-.495-.004-.964.054-1.488.515c-1.203 1.145-2.231 1.61-3.898 1.61c-1.662 0-2.789-.563-3.894-1.606c-.41-.41-.951-.551-1.473-.523z");
}

.z76n4tbau {
  d: path("m14.73 11.304l1.207-1.23l-1.214-1.2h-.9a1.215 1.215 0 1 0 0 2.43z");
}

.zstr-2b3h {
  stop-color: var(--svg-color--ff3b57, #FF3B57);
}

</style>
