<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuYoj4c)" class="t-ewcibwr"/><path fill="url(#iimggiL)" class="t-ewcibwr"/><path fill="url(#iLW611b)" class="t-ewcibwr"/><path fill="url(#iECPKWv)" class="t-ewcibwr"/><g filter="url(#ikq2sEe)"><path class="ig5t5ibfv"/></g><path fill="url(#i9c74fc)" class="ecoiz7bwo"/><path fill="url(#indpQPd)" class="ecoiz7bwo"/><path fill="url(#iNytZAc)" class="ecoiz7bwo"/><path fill="url(#iu2LJOe)" class="elyr3nl1z"/><path fill="url(#ia5Muab)" class="elyr3nl1z"/><path fill="url(#iZhdG3c)" class="mdakssb_w"/><path fill="url(#izhpiAe)" class="mdakssb_w"/><g filter="url(#ifY97rb)"><path fill="url(#iPac9ad)" class="d37r4nbxs"/></g><path fill="url(#ikafs5w)" class="zluf9m47e"/><path fill="url(#iHQnXnb)" class="zluf9m47e"/><path fill="url(#ixVpJie)" class="vy_xtm9xd"/><path class="zll4d6bcr"/><path fill="url(#i03N66d)" class="vy_xtm9xd"/><path fill="url(#iKPhoBe)" class="vy_xtm9xd"/><g filter="url(#iLcn2zb)"><rect class="qd2mwo6-o"/></g><g filter="url(#iwG1Juj)"><rect class="fqmce-z9q"/></g><g filter="url(#iVDPx3c)"><rect class="yudbzvbqh"/></g><g filter="url(#ie16pBb)"><rect class="rx1nm4bmu"/></g><g filter="url(#ihXXjKb)"><rect class="f10hwmb-k"/></g><defs><linearGradient id="iuYoj4c" x1="28.49" x2="9.783" y1="31" y2="26.116" gradientUnits="userSpaceOnUse"><stop class="wr7rxybje"/><stop offset=".897" class="vc--wpv5i"/><stop offset=".981" class="zaeth0b6d"/></linearGradient><linearGradient id="iimggiL" x1="15.137" x2="29.99" y1="12.978" y2="12.978" gradientUnits="userSpaceOnUse"><stop class="ddwhd3njp"/><stop offset="1" class="xxi0jj7bl"/></linearGradient><linearGradient id="iLW611b" x1="21.99" x2="21.99" y1="9" y2="9.499" gradientUnits="userSpaceOnUse"><stop class="hlulhbl9m"/><stop offset="1" class="m68abprqf"/></linearGradient><linearGradient id="iECPKWv" x1="14.569" x2="14.951" y1="12.898" y2="13.008" gradientUnits="userSpaceOnUse"><stop offset=".099" class="yirirrb0e"/><stop offset="1" class="lj8b7k5do"/></linearGradient><linearGradient id="i9c74fc" x1="3.035" x2="29.99" y1="20.858" y2="20.858" gradientUnits="userSpaceOnUse"><stop class="yjy29ubiv"/><stop offset="1" class="pwdidtbhm"/></linearGradient><linearGradient id="indpQPd" x1="16.089" x2="16.089" y1="16" y2="17.276" gradientUnits="userSpaceOnUse"><stop class="kwn92lbxp"/><stop offset="1" class="bd0za3fix"/></linearGradient><linearGradient id="iNytZAc" x1="3.38" x2="4.43" y1="21.202" y2="20.875" gradientUnits="userSpaceOnUse"><stop class="by_t_9bjm"/><stop offset="1" class="bxryao4cr"/></linearGradient><linearGradient id="iu2LJOe" x1="15.848" x2="15.848" y1="23" y2="30" gradientUnits="userSpaceOnUse"><stop class="raz9t3e5y"/><stop offset="1" class="kh5clfd3i"/></linearGradient><linearGradient id="ia5Muab" x1="5.308" x2="6.17" y1="26.851" y2="26.627" gradientUnits="userSpaceOnUse"><stop class="pfsk-dodt"/><stop offset="1" class="uv_4h5pqg"/></linearGradient><linearGradient id="iZhdG3c" x1="8.753" x2="26.18" y1="15.5" y2="15.5" gradientUnits="userSpaceOnUse"><stop class="j7jln9b8d"/><stop offset="1" class="b8yc707yj"/></linearGradient><linearGradient id="izhpiAe" x1="4.99" x2="5.911" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="y8whyv3eq"/><stop offset="1" class="bq8mbsbre"/></linearGradient><linearGradient id="iPac9ad" x1="18.839" x2="18.839" y1="30.29" y2="28.125" gradientUnits="userSpaceOnUse"><stop class="k00xq4gkf"/><stop offset="1" class="m0c_xfqep"/></linearGradient><linearGradient id="ikafs5w" x1="26.99" x2="21.802" y1="5.375" y2="5.375" gradientUnits="userSpaceOnUse"><stop class="dkxrc2bnw"/><stop offset="1" class="aotnamevc"/></linearGradient><linearGradient id="iHQnXnb" x1="26.99" x2="26.49" y1="5.469" y2="5.469" gradientUnits="userSpaceOnUse"><stop class="yu5fi06_g"/><stop offset="1" class="vig8evb6a"/></linearGradient><linearGradient id="ixVpJie" x1="22.99" x2="16.037" y1="18" y2="13.699" gradientUnits="userSpaceOnUse"><stop class="wr7rxybje"/><stop offset=".833" class="vc--wpv5i"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="i03N66d" x1="21.017" x2="21.302" y1="7.465" y2="7.66" gradientUnits="userSpaceOnUse"><stop class="td7xmlb6i"/><stop offset="1" class="b-v_bobwh"/></linearGradient><linearGradient id="iKPhoBe" x1="26.99" x2="26.459" y1="8.312" y2="8.312" gradientUnits="userSpaceOnUse"><stop class="ykecqybjn"/><stop offset="1" class="nddh7cbsz"/></linearGradient><filter id="ikq2sEe" width="8.033" height="2.3" x="13.957" y="11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.623529 0 0 0 0 0.894118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12457"/></filter><filter id="ifY97rb" width="28.61" height="2.92" x="1.39" y="27.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.67451 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12457"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12457" result="effect2_innerShadow_18_12457"/></filter><filter id="iLcn2zb" width="2.6" height="2.4" x="13.14" y="18.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.698039 0 0 0 0 0.964706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12457"/></filter><filter id="iwG1Juj" width="2.6" height="2.4" x="17.14" y="18.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.698039 0 0 0 0 0.964706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12457"/></filter><filter id="iVDPx3c" width="2.6" height="2.4" x="21.14" y="18.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.698039 0 0 0 0 0.964706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12457"/></filter><filter id="ie16pBb" width="2.6" height="2.4" x="25.14" y="18.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.698039 0 0 0 0 0.964706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12457"/></filter><filter id="ihXXjKb" width="2.6" height="2.6" x="23.14" y="11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0.607843 0 0 0 0 0.945098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12457"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ship" /></template>
<style>
.aotnamevc {
  stop-color: var(--svg-color--484050, #484050);
}

.b-v_bobwh {
  stop-color: var(--svg-color--b5b1b8, #B5B1B8);
  stop-opacity: 0;
}

.b8yc707yj {
  stop-color: var(--svg-color--725d87, #725D87);
}

.bd0za3fix {
  stop-color: var(--svg-color--e7e3ea, #E7E3EA);
  stop-opacity: 0;
}

.bq8mbsbre {
  stop-color: var(--svg-color--3d3940, #3D3940);
  stop-opacity: 0;
}

.bxryao4cr {
  stop-color: var(--svg-color--8e8b9c, #8E8B9C);
  stop-opacity: 0;
}

.by_t_9bjm {
  stop-color: var(--svg-color--8e8b9c, #8E8B9C);
}

.d37r4nbxs {
  d: path("M30 27.68c-1.75 0-1.75 1.12-3.51 1.12c-1.75 0-1.75-1.12-3.51-1.12c-1.75 0-1.75 1.12-3.5 1.12s-1.75-1.12-3.5-1.12s-1.75 1.12-3.5 1.12s-1.75-1.12-3.5-1.12s-1.75 1.12-3.49 1.12c-1.75 0-1.75-1.12-3.5-1.12V30h28z");
}

.ddwhd3njp {
  stop-color: var(--svg-color--e3dbe9, #E3DBE9);
}

.dkxrc2bnw {
  stop-color: var(--svg-color--6d5882, #6D5882);
}

.ecoiz7bwo {
  d: path("M29.99 16H3.203c-.675 0-1.158.642-.977 1.284L3.99 23h26z");
}

.elyr3nl1z {
  d: path("m3.99 23l1.801 6.273c.12.428.517.727.965.727h22.229a1 1 0 0 0 1.005-.996V23z");
}

.f10hwmb-k {
  width: 2px;
  height: 2px;
  x: 23.74px;
  y: 11px;
  fill: var(--svg-color--63faff, #63FAFF);
  rx: 0.5px;
}

.fqmce-z9q {
  width: 2px;
  height: 2px;
  x: 17.74px;
  y: 18.719px;
  fill: var(--svg-color--63faff, #63FAFF);
  rx: 0.5px;
}

.ft5dv1b6b {
  fill: none;
}

.hlulhbl9m {
  stop-color: var(--svg-color--f0ebf3, #F0EBF3);
}

.ig5t5ibfv {
  fill: var(--svg-color--56e6ff, #56E6FF);
  d: path("M21.99 12c0 1 0-1 0 0c0-1-.46-1-1-1h-5.876l-.558 2h6.434c.54-.01 1 0 1-1");
}

.j7jln9b8d {
  stop-color: var(--svg-color--58525b, #58525B);
}

.k00xq4gkf {
  stop-color: var(--svg-color--4f96f2, #4F96F2);
}

.kh5clfd3i {
  stop-color: var(--svg-color--df4375, #DF4375);
}

.kwn92lbxp {
  stop-color: var(--svg-color--e7e3ea, #E7E3EA);
}

.lj8b7k5do {
  stop-color: var(--svg-color--a49fa7, #A49FA7);
  stop-opacity: 0;
}

.m0c_xfqep {
  stop-color: var(--svg-color--5092eb, #5092EB);
}

.m68abprqf {
  stop-color: var(--svg-color--f0ebf3, #F0EBF3);
  stop-opacity: 0;
}

.mdakssb_w {
  d: path("M29.99 16h-25v-.414c0-.323.26-.586.58-.586h24.42z");
}

.nddh7cbsz {
  stop-color: var(--svg-color--fbf8fe, #FBF8FE);
  stop-opacity: 0;
}

.pfsk-dodt {
  stop-color: var(--svg-color--883757, #883757);
}

.pwdidtbhm {
  stop-color: var(--svg-color--e1d8ea, #E1D8EA);
}

.qd2mwo6-o {
  width: 2px;
  height: 2px;
  x: 13.74px;
  y: 18.719px;
  fill: var(--svg-color--63faff, #63FAFF);
  rx: 0.5px;
}

.raz9t3e5y {
  stop-color: var(--svg-color--fb4659, #FB4659);
}

.rx1nm4bmu {
  width: 2px;
  height: 2px;
  x: 25.74px;
  y: 18.719px;
  fill: var(--svg-color--63faff, #63FAFF);
  rx: 0.5px;
}

.t-ewcibwr {
  d: path("M16.125 9H29.99v6h-16l1.565-5.56a.59.59 0 0 1 .57-.44");
}

.td7xmlb6i {
  stop-color: var(--svg-color--b5b1b8, #B5B1B8);
}

.uv_4h5pqg {
  stop-color: var(--svg-color--883757, #883757);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vig8evb6a {
  stop-color: var(--svg-color--836e98, #836E98);
  stop-opacity: 0;
}

.vy_xtm9xd {
  d: path("m21.99 6l-2 3h7V6z");
}

.wr7rxybje {
  stop-color: var(--svg-color--d3d2d2, #D3D2D2);
}

.xxi0jj7bl {
  stop-color: var(--svg-color--e6dded, #E6DDED);
}

.y8whyv3eq {
  stop-color: var(--svg-color--3d3940, #3D3940);
}

.yirirrb0e {
  stop-color: var(--svg-color--a49fa7, #A49FA7);
}

.yjy29ubiv {
  stop-color: var(--svg-color--cfc9d9, #CFC9D9);
}

.ykecqybjn {
  stop-color: var(--svg-color--fbf8fe, #FBF8FE);
}

.yu5fi06_g {
  stop-color: var(--svg-color--836e98, #836E98);
}

.yudbzvbqh {
  width: 2px;
  height: 2px;
  x: 21.74px;
  y: 18.719px;
  fill: var(--svg-color--63faff, #63FAFF);
  rx: 0.5px;
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zll4d6bcr {
  fill: var(--svg-color--e1d9e7, #E1D9E7);
  d: path("m21.99 6l-2 3h7V6z");
}

.zluf9m47e {
  d: path("M26.98 4.412A.405.405 0 0 0 26.586 4h-2.33c-.587 0-1.055.289-1.433.844L21.99 6h5V4.412z");
}

</style>
