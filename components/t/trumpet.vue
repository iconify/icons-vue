<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iomfAHQ)"><path fill="url(#i2sDtnb)" class="tb9-v2e9r"/></g><g filter="url(#ikIYAfb)"><path fill="url(#ikrtxTd)" class="ky2w5pbgj"/></g><g filter="url(#isCoOBc)"><path fill="url(#iZHRsIp)" class="evdy8mbba"/></g><g filter="url(#iAZTOgb)"><rect fill="url(#iuiM8gd)" transform="rotate(-43.089 14.664 11.656)" class="h9cutwb2t"/></g><g filter="url(#iuz7pVZ)"><rect fill="url(#i5i7G0D)" transform="rotate(-43.089 11.726 14.61)" class="ec0e5jwci"/></g><g filter="url(#iXyq0jb)"><rect fill="url(#iucItFc)" transform="rotate(-43.089 8.52 17.375)" class="f934moalc"/></g><rect fill="url(#inNqqkc)" transform="rotate(-41.578 2.436 25.127)" class="f1_y9htks"/><rect fill="url(#iicmoEW)" transform="rotate(-41.578 2.436 25.127)" class="f1_y9htks"/><rect fill="url(#iPja8Je)" transform="rotate(-41.578 2.436 25.127)" class="f1_y9htks"/><path fill="url(#i5kfyhc)" clip-rule="evenodd" class="irp3ufb-v"/><path fill="url(#iQeQ1vd)" clip-rule="evenodd" class="irp3ufb-v"/><g filter="url(#iPEVxue)"><path fill="url(#inRLSzb)" class="ooxrn8b4v"/><path fill="url(#iQD3cwd)" class="ooxrn8b4v"/></g><g filter="url(#if66JRS)"><path fill="url(#iS33Yvd)" class="tu-2bitzv"/><path fill="url(#iwtkDdd)" class="tu-2bitzv"/></g><g filter="url(#iAdmRNt)"><path fill="url(#iZiGv1b)" class="o8f32ty3p"/><path fill="url(#ixLLsjc)" class="o8f32ty3p"/></g><g filter="url(#iSO5qsb)"><rect stroke="url(#iMafuIW)" transform="rotate(48.972 20.918 11.318)" class="bhwwqeq2f"/></g><path fill="url(#iff45Yc)" class="nynkixb_z"/><path fill="url(#iff45Yc)" class="nynkixb_z"/><path fill="url(#i9jSsVc)" class="nynkixb_z"/><path fill="url(#iPoCHfd)" class="nynkixb_z"/><g filter="url(#iX1dIDb)"><rect fill="url(#iI6jfXb)" transform="rotate(-42.417 1.51 24.733)" class="fqfytqbqi"/><rect fill="url(#ihuycCb)" transform="rotate(-42.417 1.51 24.733)" class="fqfytqbqi"/><rect fill="url(#ikPqYrK)" transform="rotate(-42.417 1.51 24.733)" class="fqfytqbqi"/></g><path fill="url(#ie9BBKd)" class="mowjkhb3v"/><path fill="url(#iWq84ub)" class="mowjkhb3v"/><path fill="url(#iHmDyDc)" class="mowjkhb3v"/><path fill="url(#iUk473d)" class="mowjkhb3v"/><path fill="url(#izQzbox)" class="mowjkhb3v"/><g filter="url(#ingNo1d)"><path fill="url(#iiAccyd)" class="h8xmgi99c"/></g><defs><linearGradient id="i2sDtnb" x1="9.236" x2="14.455" y1="17.28" y2="27.436" gradientUnits="userSpaceOnUse"><stop class="nt2uw8wtd"/><stop offset=".919" class="y8sel0bsx"/></linearGradient><linearGradient id="ikrtxTd" x1="12.423" x2="17.642" y1="14.482" y2="24.638" gradientUnits="userSpaceOnUse"><stop class="nt2uw8wtd"/><stop offset=".919" class="y8sel0bsx"/></linearGradient><linearGradient id="iZHRsIp" x1="15.414" x2="20.633" y1="11.628" y2="21.784" gradientUnits="userSpaceOnUse"><stop class="nt2uw8wtd"/><stop offset="1" class="xck726hzd"/></linearGradient><linearGradient id="iuiM8gd" x1="14.902" x2="14.958" y1="11.656" y2="24.126" gradientUnits="userSpaceOnUse"><stop class="eyw2pys3m"/><stop offset="1" class="rpfk_owzt"/></linearGradient><linearGradient id="i5i7G0D" x1="11.964" x2="12.02" y1="14.61" y2="27.079" gradientUnits="userSpaceOnUse"><stop class="eyw2pys3m"/><stop offset="1" class="rpfk_owzt"/></linearGradient><linearGradient id="iucItFc" x1="8.757" x2="8.813" y1="17.375" y2="29.844" gradientUnits="userSpaceOnUse"><stop class="eyw2pys3m"/><stop offset="1" class="rpfk_owzt"/></linearGradient><linearGradient id="inNqqkc" x1="10.937" x2="10.883" y1="25.777" y2="28.569" gradientUnits="userSpaceOnUse"><stop class="fnhp6thqe"/><stop offset="1" class="a50eunb-t"/></linearGradient><linearGradient id="iPja8Je" x1="11.022" x2="11.03" y1="24.975" y2="25.86" gradientUnits="userSpaceOnUse"><stop offset=".188" class="nw11jfb7x"/><stop offset="1" class="w83uymbnj"/></linearGradient><linearGradient id="i5kfyhc" x1="24.298" x2="9.973" y1="13.844" y2="27.59" gradientUnits="userSpaceOnUse"><stop class="wfg3efbvz"/><stop offset="1" class="yvwq2tbwv"/></linearGradient><linearGradient id="inRLSzb" x1="7.383" x2="9.822" y1="18.798" y2="16.471" gradientUnits="userSpaceOnUse"><stop class="jrf_tzbop"/><stop offset="1" class="ami2ewvnn"/></linearGradient><linearGradient id="iS33Yvd" x1="10.57" x2="13.009" y1="16" y2="13.673" gradientUnits="userSpaceOnUse"><stop class="jrf_tzbop"/><stop offset="1" class="ami2ewvnn"/></linearGradient><linearGradient id="iZiGv1b" x1="13.561" x2="16" y1="13.146" y2="10.819" gradientUnits="userSpaceOnUse"><stop class="jrf_tzbop"/><stop offset="1" class="ami2ewvnn"/></linearGradient><linearGradient id="iMafuIW" x1="25.437" x2="25.437" y1="11.318" y2="28.815" gradientUnits="userSpaceOnUse"><stop class="zpfdj26wi"/><stop offset=".369" class="riz--lbps"/><stop offset=".688" class="riz--lbps"/><stop offset="1" class="axqjf_b_a"/></linearGradient><linearGradient id="iff45Yc" x1="22.733" x2="10.389" y1="9.837" y2="20.447" gradientUnits="userSpaceOnUse"><stop offset=".489" class="he1ydcbvy"/><stop offset="1" class="h-p-56b_f"/></linearGradient><linearGradient id="i9jSsVc" x1="12.539" x2="13.111" y1="15.731" y2="16.39" gradientUnits="userSpaceOnUse"><stop class="ua-zg2b5l"/><stop offset="1" class="ox99d9b1r"/></linearGradient><linearGradient id="iI6jfXb" x1="2.587" x2="2.587" y1="24.733" y2="29.866" gradientUnits="userSpaceOnUse"><stop offset=".196" class="uwfzz2bfl"/><stop offset="1" class="mn1khbb2q"/></linearGradient><linearGradient id="ie9BBKd" x1="25.645" x2="21.138" y1="7.208" y2="11.015" gradientUnits="userSpaceOnUse"><stop class="xkehbbq-k"/><stop offset="1" class="xl6tgabbb"/></linearGradient><linearGradient id="iUk473d" x1="27.883" x2="26.164" y1="6.409" y2="7.909" gradientUnits="userSpaceOnUse"><stop offset=".14" class="x0c96bbbj"/><stop offset="1" class="n7950obcd"/></linearGradient><linearGradient id="iiAccyd" x1="20.999" x2="11.152" y1="11.015" y2="18.991" gradientUnits="userSpaceOnUse"><stop class="a0rzizb6p"/><stop offset=".44" class="y7jkm9brp"/><stop offset="1" class="a0rzizb6p"/></linearGradient><filter id="iomfAHQ" width="11.245" height="11.957" x="7.723" y="16.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.415686 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18749"/></filter><filter id="ikIYAfb" width="11.351" height="11.957" x="10.805" y="14.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.415686 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18749"/></filter><filter id="isCoOBc" width="11.295" height="11.957" x="13.851" y="11.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.415686 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18749"/></filter><filter id="iAZTOgb" width="11.134" height="11.787" x="14.162" y="10.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18749" stdDeviation=".3"/></filter><filter id="iuz7pVZ" width="11.134" height="11.787" x="11.225" y="13.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18749" stdDeviation=".3"/></filter><filter id="iXyq0jb" width="11.134" height="11.787" x="8.018" y="16.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18749" stdDeviation=".3"/></filter><filter id="iPEVxue" width="3.191" height="2.98" x="6.831" y="15.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.835294 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18749"/></filter><filter id="if66JRS" width="3.191" height="2.98" x="10.019" y="13.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.835294 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18749"/></filter><filter id="iAdmRNt" width="3.191" height="2.98" x="13.009" y="10.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.835294 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18749"/></filter><filter id="iSO5qsb" width="17.92" height="17.091" x="8.325" y="11.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18749" stdDeviation=".375"/></filter><filter id="iX1dIDb" width="4.363" height="4.553" x="1.755" y="23.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.623529 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18749"/></filter><filter id="ingNo1d" width="16.477" height="19.37" x="8.002" y="7.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18749" stdDeviation=".25"/></filter><radialGradient id="iicmoEW" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62173 2.0605 -1.13141 -1.43958 7.962 27.482)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="hmmff53bl"/><stop offset="1" class="zduzb0d0g"/></radialGradient><radialGradient id="iQeQ1vd" cx="0" cy="0" r="1" gradientTransform="rotate(105.871 2.25 14.27)scale(14.5636 18.2113)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="s_2q_qb9r"/><stop offset=".971" class="oftcxfb3a"/></radialGradient><radialGradient id="iQD3cwd" cx="0" cy="0" r="1" gradientTransform="matrix(-.82813 .76562 -.27524 -.29771 9.008 16.83)" gradientUnits="userSpaceOnUse"><stop class="nz-77tbyu"/><stop offset="1" class="gdb1ukm5c"/></radialGradient><radialGradient id="iwtkDdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.82813 .76562 -.27524 -.29771 12.195 14.033)" gradientUnits="userSpaceOnUse"><stop class="nz-77tbyu"/><stop offset="1" class="gdb1ukm5c"/></radialGradient><radialGradient id="ixLLsjc" cx="0" cy="0" r="1" gradientTransform="matrix(-.82813 .76562 -.27524 -.29771 15.186 11.179)" gradientUnits="userSpaceOnUse"><stop class="nz-77tbyu"/><stop offset="1" class="gdb1ukm5c"/></radialGradient><radialGradient id="iPoCHfd" cx="0" cy="0" r="1" gradientTransform="rotate(-173.577 9.313 11.124)scale(10.5378 25.922)" gradientUnits="userSpaceOnUse"><stop offset=".872" class="ox99d9b1r"/><stop offset="1" class="ua-zg2b5l"/></radialGradient><radialGradient id="ihuycCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00859 -5.23402 4.90502 -.00805 2.628 29.014)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="iiosszbfi"/><stop offset="1" class="hmdqxi0fk"/></radialGradient><radialGradient id="ikPqYrK" cx="0" cy="0" r="1" gradientTransform="matrix(.07804 2.92182 -1.53546 .04101 3.091 27.76)" gradientUnits="userSpaceOnUse"><stop class="uap5-nrke"/><stop offset="1" class="yqq7uleeg"/></radialGradient><radialGradient id="iWq84ub" cx="0" cy="0" r="1" gradientTransform="matrix(3.2334 1.94174 -2.44329 4.06857 19.881 5.537)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="egr8sbo9c"/><stop offset="1" class="i2s4ycx-s"/></radialGradient><radialGradient id="iHmDyDc" cx="0" cy="0" r="1" gradientTransform="rotate(-100.466 17.782 -5.77)scale(3.81778 4.58644)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="y-4ilmjiy"/><stop offset="1" class="pgryq9bam"/></radialGradient><radialGradient id="izQzbox" cx="0" cy="0" r="1" gradientTransform="matrix(1.98438 2.1875 -.40919 .3712 27.148 6.643)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="aikg0vbrl"/><stop offset="1" class="x8szwm4er"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:trumpet" /></template>
<style>
.a0rzizb6p {
  stop-color: var(--svg-color--d9b244, #D9B244);
  stop-opacity: 0;
}

.a50eunb-t {
  stop-color: var(--svg-color--c56d79, #C56D79);
}

.aikg0vbrl {
  stop-color: var(--svg-color--edd261, #EDD261);
}

.ami2ewvnn {
  stop-color: var(--svg-color--b1a3a5, #B1A3A5);
}

.axqjf_b_a {
  stop-color: var(--svg-color--eaa760, #EAA760);
}

.bhwwqeq2f {
  width: 9.037px;
  height: 17.497px;
  x: 20.918px;
  y: 11.318px;
  rx: 4.518px;
}

.ec0e5jwci {
  width: 0.476px;
  height: 14.322px;
  x: 11.726px;
  y: 14.61px;
  rx: 0.238px;
}

.egr8sbo9c {
  stop-color: var(--svg-color--dcc579, #DCC579);
}

.evdy8mbba {
  d: path("m13.851 12.893l1.951-1.463l9.02 9.678a1.207 1.207 0 0 1-1.766 1.646z");
}

.eyw2pys3m {
  stop-color: var(--svg-color--c79d4b, #C79D4B);
}

.f1_y9htks {
  width: 17.555px;
  height: 3.065px;
  x: 2.436px;
  y: 25.127px;
  rx: 1.532px;
}

.f934moalc {
  width: 0.476px;
  height: 14.322px;
  x: 8.52px;
  y: 17.375px;
  rx: 0.238px;
}

.fnhp6thqe {
  stop-color: var(--svg-color--c8792d, #C8792D);
}

.fqfytqbqi {
  width: 2.153px;
  height: 5.133px;
  x: 1.51px;
  y: 24.733px;
  rx: 1.077px;
}

.ft5dv1b6b {
  fill: none;
}

.gdb1ukm5c {
  stop-color: var(--svg-color--c2b6bd, #C2B6BD);
  stop-opacity: 0;
}

.h-p-56b_f {
  stop-color: var(--svg-color--cca837, #CCA837);
  stop-opacity: 0;
}

.h8xmgi99c {
  d: path("m10.524 19.96l-.328-.378zm.328.377L23.979 8.92l-.657-.755l-13.126 11.417zm-.385 5.542a3.93 3.93 0 0 1 .385-5.543l-.657-.754a4.93 4.93 0 0 0-.482 6.953z");
}

.h9cutwb2t {
  width: 0.476px;
  height: 14.322px;
  x: 14.664px;
  y: 11.656px;
  rx: 0.238px;
}

.he1ydcbvy {
  stop-color: var(--svg-color--cca837, #CCA837);
}

.hmdqxi0fk {
  stop-color: var(--svg-color--d9d2df, #D9D2DF);
}

.hmmff53bl {
  stop-color: var(--svg-color--c1622e, #C1622E);
}

.i2s4ycx-s {
  stop-color: var(--svg-color--dcc579, #DCC579);
  stop-opacity: 0;
}

.iiosszbfi {
  stop-color: var(--svg-color--d9d2df, #D9D2DF);
  stop-opacity: 0;
}

.irp3ufb-v {
  fill-rule: evenodd;
  d: path("M15.793 13.253a6.029 6.029 0 0 1 7.915 9.096l-6.32 5.5a6.029 6.029 0 0 1-7.915-9.097zm6.091 2.691a2.83 2.83 0 0 0-3.99-.277l-6.32 5.5a2.829 2.829 0 1 0 3.714 4.267l6.32-5.499a2.83 2.83 0 0 0 .276-3.99");
}

.jrf_tzbop {
  stop-color: var(--svg-color--b29abb, #B29ABB);
}

.ky2w5pbgj {
  d: path("m10.805 15.721l2.007-1.437l9.02 9.678a1.207 1.207 0 0 1-1.767 1.646z");
}

.mn1khbb2q {
  stop-color: var(--svg-color--c09cdb, #C09CDB);
}

.mowjkhb3v {
  d: path("m28.848 10.635l.004.004c-2.154-.894-5.036-.138-6.734 1.358c-.018.015-.14.074-.154.085l-2.083-2.388c.706-.547 1.642-1.426 1.953-3.412c.292-1.862.2-2.95.126-3.378a.914.914 0 0 1 1.566-.849l6.284 7.102a.914.914 0 0 1-.962 1.478");
}

.n7950obcd {
  stop-color: var(--svg-color--c9a540, #C9A540);
  stop-opacity: 0;
}

.nt2uw8wtd {
  stop-color: var(--svg-color--b88525, #B88525);
}

.nw11jfb7x {
  stop-color: var(--svg-color--dca77b, #DCA77B);
}

.nynkixb_z {
  d: path("m10.524 19.96l-1.05-1.208zm1.05 1.206L24.7 9.75l-2.1-2.415L9.474 18.752zm-.277 3.991a2.83 2.83 0 0 1 .277-3.99l-2.1-2.415a6.03 6.03 0 0 0-.591 8.506z");
}

.nz-77tbyu {
  stop-color: var(--svg-color--c2b6bd, #C2B6BD);
}

.o8f32ty3p {
  d: path("M13.193 12.929c.257.276.69.29.966.034l1.624-1.514a.683.683 0 0 0-.932-1l-1.624 1.514a.683.683 0 0 0-.034.966");
}

.oftcxfb3a {
  stop-color: var(--svg-color--cf6262, #CF6262);
}

.ooxrn8b4v {
  d: path("M7.015 18.58c.257.277.69.292.965.035L9.604 17.1a.683.683 0 1 0-.931-1l-1.624 1.514a.683.683 0 0 0-.034.966");
}

.ox99d9b1r {
  stop-color: var(--svg-color--dab570, #DAB570);
  stop-opacity: 0;
}

.pgryq9bam {
  stop-color: var(--svg-color--c58f37, #C58F37);
  stop-opacity: 0;
}

.riz--lbps {
  stop-color: var(--svg-color--eaa760, #EAA760);
  stop-opacity: 0;
}

.rpfk_owzt {
  stop-color: var(--svg-color--da9c57, #DA9C57);
}

.s_2q_qb9r {
  stop-color: var(--svg-color--cf6262, #CF6262);
  stop-opacity: 0;
}

.tb9-v2e9r {
  d: path("m7.723 18.608l1.901-1.525l9.02 9.677a1.207 1.207 0 0 1-1.766 1.646z");
}

.tu-2bitzv {
  d: path("M10.202 15.783c.258.276.69.29.966.034l1.624-1.514a.683.683 0 0 0-.932-1l-1.624 1.514a.683.683 0 0 0-.034.966");
}

.ua-zg2b5l {
  stop-color: var(--svg-color--dab570, #DAB570);
}

.uap5-nrke {
  stop-color: var(--svg-color--d0bddd, #D0BDDD);
}

.uwfzz2bfl {
  stop-color: var(--svg-color--baaac7, #BAAAC7);
}

.w83uymbnj {
  stop-color: var(--svg-color--c97839, #C97839);
  stop-opacity: 0;
}

.wfg3efbvz {
  stop-color: var(--svg-color--d7ae30, #D7AE30);
}

.x0c96bbbj {
  stop-color: var(--svg-color--e0c93a, #E0C93A);
}

.x8szwm4er {
  stop-color: var(--svg-color--d9be3e, #D9BE3E);
  stop-opacity: 0;
}

.xck726hzd {
  stop-color: var(--svg-color--ce7f27, #CE7F27);
}

.xkehbbq-k {
  stop-color: var(--svg-color--c9a640, #C9A640);
}

.xl6tgabbb {
  stop-color: var(--svg-color--cea939, #CEA939);
}

.y-4ilmjiy {
  stop-color: var(--svg-color--c58f37, #C58F37);
}

.y7jkm9brp {
  stop-color: var(--svg-color--d9b244, #D9B244);
}

.y8sel0bsx {
  stop-color: var(--svg-color--cf6a2c, #CF6A2C);
}

.yqq7uleeg {
  stop-color: var(--svg-color--bd9cd8, #BD9CD8);
  stop-opacity: 0;
}

.yvwq2tbwv {
  stop-color: var(--svg-color--db7f28, #DB7F28);
}

.zduzb0d0g {
  stop-color: var(--svg-color--c1622e, #C1622E);
  stop-opacity: 0;
}

.zpfdj26wi {
  stop-color: var(--svg-color--f3d663, #F3D663);
}

</style>
