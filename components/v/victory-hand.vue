<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ijEgW5d)"><path class="ta_4dsb9l"/><path fill="url(#iD4DqXc)" class="bpv1clbme"/></g><g filter="url(#iSmHdzb)" class="shc-aubwp"><path class="vmgbtnwjz"/><path class="njsiwjbhp"/></g><path fill="url(#iSFVZLe)" class="eyd7wbbjh"/><path fill="url(#iJthL4W)" class="eyd7wbbjh"/><path fill="url(#ikzNcob)" class="eyd7wbbjh"/><path fill="url(#iolXRTy)" class="eyd7wbbjh"/><path fill="url(#ia4MbSM)" class="j7vtllbex"/><path fill="url(#isKEUse)" class="j7vtllbex"/><path fill="url(#iCXVmbb)" class="j7vtllbex"/><g filter="url(#iXYO8Uc)"><path class="lpnbpe3pb"/></g><path class="twejx-g5n"/><path fill="url(#i9PKrde)" class="rfta13yrc"/><path fill="url(#inB8fGQ)" class="rfta13yrc"/><path fill="url(#iqsLsoc)" class="rfta13yrc"/><path fill="url(#iD9Xmze)" class="bpv1clbme"/><path fill="url(#iSr16gd)" class="bpv1clbme"/><path fill="url(#iqbG39d)" class="bpv1clbme"/><path fill="url(#id5vzeG)" class="bpv1clbme"/><path fill="url(#iYjbRre)" class="bpv1clbme"/><path fill="url(#iKK9qsd)" class="bpv1clbme"/><path fill="url(#iUQJYjc)" class="bpv1clbme"/><g filter="url(#i0iNK3d)"><path class="yad7sobtt"/></g><g filter="url(#iyYkzTP)"><path class="hov7o_jho"/></g><g filter="url(#iNHe8Ce)"><path stroke="url(#iU0Wufc)" class="kzcrzjbku"/></g><defs><radialGradient id="iD4DqXc" cx="0" cy="0" r="1" gradientTransform="matrix(6.46875 0 0 17.6975 6.435 20.688)" gradientUnits="userSpaceOnUse"><stop class="kmymw26su"/><stop offset="1" class="mtgzb8bzw"/></radialGradient><radialGradient id="iSFVZLe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40393 0 0 -8.45019 9.292 14.555)" gradientUnits="userSpaceOnUse"><stop class="jkk-xsb9b"/><stop offset="1" class="s82_ytp1j"/></radialGradient><radialGradient id="iJthL4W" cx="0" cy="0" r="1" gradientTransform="rotate(-117.91 9.564 5.034)scale(5.9652 9.82892)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w4f-f8gin"/><stop offset=".967" class="nhmaq9_ex"/></radialGradient><radialGradient id="ikzNcob" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.59375 -6.05121 0 8.486 10.781)" gradientUnits="userSpaceOnUse"><stop offset=".774" class="t714y9bsh"/><stop offset="1" class="zs67g1hyu"/></radialGradient><radialGradient id="ia4MbSM" cx="0" cy="0" r="1" gradientTransform="matrix(-4.39249 0 0 -12.4392 14.967 13.29)" gradientUnits="userSpaceOnUse"><stop class="nimcgqevu"/><stop offset="1" class="wbg6vsbgl"/></radialGradient><radialGradient id="isKEUse" cx="0" cy="0" r="1" gradientTransform="rotate(-119.055 11.285 3.385)scale(5.8514 5.77771)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mr8vw0b5p"/><stop offset="1" class="rcwxbub4r"/></radialGradient><radialGradient id="iCXVmbb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.17783 8.6004 -6.2624 -1.5858 14.082 9.93)" gradientUnits="userSpaceOnUse"><stop offset=".733" class="nol5yzbtg"/><stop offset="1" class="nue1pbcqe"/></radialGradient><radialGradient id="i9PKrde" cx="0" cy="0" r="1" gradientTransform="matrix(5.13234 -6.0845 6.49403 5.47779 18.511 24.524)" gradientUnits="userSpaceOnUse"><stop offset=".602" class="mg0fgeeql"/><stop offset="1" class="efamoh3_s"/></radialGradient><radialGradient id="inB8fGQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.41565 -3.58984 5.09216 2.0081 18.963 22.585)" gradientUnits="userSpaceOnUse"><stop offset=".414" class="ev9kxtf1w"/><stop offset="1" class="gnyxf5bhu"/></radialGradient><radialGradient id="iqsLsoc" cx="0" cy="0" r="1" gradientTransform="matrix(3.02303 1.65321 -2.7655 5.05693 16.035 17.153)" gradientUnits="userSpaceOnUse"><stop class="qq7swqg4c"/><stop offset="1" class="zwtfjqb1k"/></radialGradient><radialGradient id="iD9Xmze" cx="0" cy="0" r="1" gradientTransform="matrix(23.58865 .10771 -.13271 29.0642 1.257 19.493)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="p5_utlbxl"/><stop offset="1" class="wbgshgbmf"/></radialGradient><radialGradient id="iSr16gd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.55653 4.50733 -4.94959 -5.00361 22.284 15.974)" gradientUnits="userSpaceOnUse"><stop class="xsg9vwb1s"/><stop offset="1" class="t_t6-ha7d"/></radialGradient><radialGradient id="iqbG39d" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.8125 -.62699 -.07195 20.107 10.156)" gradientUnits="userSpaceOnUse"><stop offset=".499" class="lbwdgze-s"/><stop offset="1" class="pit_nyb4a"/></radialGradient><radialGradient id="id5vzeG" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29254 2.31576 -2.63568 -1.4711 18.68 2.69)" gradientUnits="userSpaceOnUse"><stop class="i7q65hbym"/><stop offset="1" class="l0_fn5b0x"/></radialGradient><radialGradient id="iYjbRre" cx="0" cy="0" r="1" gradientTransform="matrix(1.1875 .375 -2.39876 7.59612 21.685 7.344)" gradientUnits="userSpaceOnUse"><stop class="lnvkp4bsl"/><stop offset="1" class="r-hrjcb_m"/></radialGradient><radialGradient id="iKK9qsd" cx="0" cy="0" r="1" gradientTransform="matrix(.52265 1.28652 -1.98532 .80654 23.523 4.528)" gradientUnits="userSpaceOnUse"><stop class="jooz5vbnh"/><stop offset="1" class="dqglc6onq"/></radialGradient><radialGradient id="iUQJYjc" cx="0" cy="0" r="1" gradientTransform="rotate(132.709 12.124 8.467)scale(2.85839 3.24493)" gradientUnits="userSpaceOnUse"><stop class="i7q65hbym"/><stop offset="1" class="l0_fn5b0x"/></radialGradient><filter id="ijEgW5d" width="21.725" height="28.865" x="5.935" y="1.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.501961 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2056"/></filter><filter id="iSmHdzb" width="8.711" height="8.678" x="6.101" y="10.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2056" stdDeviation=".5"/></filter><filter id="iXYO8Uc" width="10.68" height="9.724" x="13.981" y="16.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2056" stdDeviation=".5"/></filter><filter id="i0iNK3d" width="6.362" height="14.817" x="14.825" y=".909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2056" stdDeviation="1"/></filter><filter id="iyYkzTP" width="7.975" height="13.121" x="20.379" y="4.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2056" stdDeviation="1"/></filter><filter id="iNHe8Ce" width="9.146" height="7.828" x="16.618" y="15.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2056" stdDeviation=".75"/></filter><linearGradient id="iolXRTy" x1="10.854" x2="9.507" y1="14.316" y2="14.316" gradientUnits="userSpaceOnUse"><stop class="mwtcr1vhb"/><stop offset="1" class="y1oagzdpx"/></linearGradient><linearGradient id="iU0Wufc" x1="18.899" x2="24.045" y1="17.063" y2="20.408" gradientUnits="userSpaceOnUse"><stop class="s05ajackq"/><stop offset="1" class="pp8v3-b-z"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:victory-hand" /></template>
<style>
.bpv1clbme {
  d: path("m14.76 16.055l-8.825-.634s0 3.596.371 6.61c.782 5.157 4.583 7.875 8.703 7.875c7.688 0 10.502-5.906 10.127-9.955c-.376-4.05-.485-4.834 0-6.193l1.849-5.678c.312-.844.42-2.778-1.58-3.453s-3.053.984-3.339 1.765l-1.903 5.667c-.18.289-.398.086-.398-.055c-.094-1.73-.287-5.658-.487-7.658c-.189-1.887-1.943-2.37-2.777-2.298c-1.725.125-2.46 1.781-2.381 2.531z");
}

.dqglc6onq {
  stop-color: var(--svg-color--d3ae52, #D3AE52);
  stop-opacity: 0;
}

.efamoh3_s {
  stop-color: var(--svg-color--ffe444, #FFE444);
}

.ev9kxtf1w {
  stop-color: var(--svg-color--f5863b, #F5863B);
}

.eyd7wbbjh {
  d: path("M5.931 13.368c0-1.85 1.204-2.798 2.688-2.798s2.422 1.253 2.422 2.798v2.248c0 1.545-.938 2.447-2.422 2.447S5.93 17.16 5.93 15.616z");
}

.ft5dv1b6b {
  fill: none;
}

.gnyxf5bhu {
  stop-color: var(--svg-color--f5863b, #F5863B);
  stop-opacity: 0;
}

.hov7o_jho {
  stroke: var(--svg-color--ffe746, #FFE746);
  stroke-linecap: round;
  d: path("m25.854 6.74l-2.975 8.12");
}

.i7q65hbym {
  stop-color: var(--svg-color--ffe847, #FFE847);
}

.j7vtllbex {
  d: path("M10.008 12.69c0-2.377 1.21-3.174 2.701-3.174c1.493 0 2.702 1.14 2.702 3.174v2.55c0 1.753-1.21 2.948-2.702 2.948s-2.701-1.195-2.701-2.948z");
}

.jkk-xsb9b {
  stop-color: var(--svg-color--ffd237, #FFD237);
}

.jooz5vbnh {
  stop-color: var(--svg-color--d3ae52, #D3AE52);
}

.kmymw26su {
  stop-color: var(--svg-color--ffbf36, #FFBF36);
}

.kzcrzjbku {
  stroke-linecap: round;
  d: path("M18.618 17.071c1.367-.093 4.31.54 5.146 3.82");
}

.l0_fn5b0x {
  stop-color: var(--svg-color--ffe847, #FFE847);
  stop-opacity: 0;
}

.lbwdgze-s {
  stop-color: var(--svg-color--cd9028, #CD9028);
}

.lnvkp4bsl {
  stop-color: var(--svg-color--d19532, #D19532);
}

.lpnbpe3pb {
  fill: var(--svg-color--eb872f, #EB872F);
  d: path("M17.197 21.873c1.889 0 4.045-.044 4.526 2.093c.45 1.999 2.324.5 1.866-2.093c-.579-3.274-3.138-4.836-6.392-4.699c-1.726.073-2.216 1.513-2.216 2.234c0 .72.328 2.465 2.216 2.465");
}

.mg0fgeeql {
  stop-color: var(--svg-color--ffe444, #FFE444);
  stop-opacity: 0;
}

.mr8vw0b5p {
  stop-color: var(--svg-color--de9e44, #DE9E44);
  stop-opacity: 0;
}

.mtgzb8bzw {
  stop-color: var(--svg-color--ffc736, #FFC736);
  stop-opacity: 0;
}

.mwtcr1vhb {
  stop-color: var(--svg-color--c3832a, #C3832A);
}

.nhmaq9_ex {
  stop-color: var(--svg-color--f2af43, #F2AF43);
}

.nimcgqevu {
  stop-color: var(--svg-color--ffe73f, #FFE73F);
}

.njsiwjbhp {
  d: path("M7.101 14.175c0-1.775.904-2.37 2.018-2.37c1.115 0 2.018.852 2.018 2.37v1.905c0 1.309-.903 2.201-2.018 2.201s-2.018-.892-2.018-2.201z");
}

.nol5yzbtg {
  stop-color: var(--svg-color--e9823b, #E9823B);
  stop-opacity: 0;
}

.nue1pbcqe {
  stop-color: var(--svg-color--e9823b, #E9823B);
}

.p5_utlbxl {
  stop-color: var(--svg-color--ffc53b, #FFC53B);
  stop-opacity: 0;
}

.pit_nyb4a {
  stop-color: var(--svg-color--cd9028, #CD9028);
  stop-opacity: 0;
}

.pp8v3-b-z {
  stop-color: var(--svg-color--ffe746, #FFE746);
  stop-opacity: 0;
}

.qq7swqg4c {
  stop-color: var(--svg-color--eeae11, #EEAE11);
}

.r-hrjcb_m {
  stop-color: var(--svg-color--d19532, #D19532);
  stop-opacity: 0;
}

.rcwxbub4r {
  stop-color: var(--svg-color--de9e44, #DE9E44);
}

.rfta13yrc {
  d: path("M18.088 20.828c2.05 0 3.163 1.684 3.686 4c.488 2.168 3.749-1.187 3.251-4c-.627-3.549-3.405-5.243-6.937-5.094c-1.874.08-2.407 1.641-2.407 2.422s.357 2.672 2.407 2.672");
}

.s05ajackq {
  stop-color: var(--svg-color--ffe746, #FFE746);
}

.s82_ytp1j {
  stop-color: var(--svg-color--ffba32, #FFBA32);
}

.shc-aubwp {
  fill: var(--svg-color--cd6322, #CD6322);
}

.t_t6-ha7d {
  stop-color: var(--svg-color--ffd131, #FFD131);
  stop-opacity: 0;
}

.t714y9bsh {
  stop-color: var(--svg-color--f58e33, #F58E33);
  stop-opacity: 0;
}

.ta_4dsb9l {
  fill: var(--svg-color--fb4, #FB4);
  d: path("m14.76 16.055l-8.825-.634s0 3.596.371 6.61c.782 5.157 4.583 7.875 8.703 7.875c7.688 0 10.502-5.906 10.127-9.955c-.376-4.05-.485-4.834 0-6.193l1.849-5.678c.312-.844.42-2.778-1.58-3.453s-3.053.984-3.339 1.765l-1.903 5.667c-.18.289-.398.086-.398-.055c-.094-1.73-.287-5.658-.487-7.658c-.189-1.887-1.943-2.37-2.777-2.298c-1.725.125-2.46 1.781-2.381 2.531z");
}

.twejx-g5n {
  fill: var(--svg-color--fb4, #FB4);
  d: path("M18.088 20.828c2.05 0 3.163 1.684 3.686 4c.488 2.168 3.749-1.187 3.251-4c-.627-3.549-3.405-5.243-6.937-5.094c-1.874.08-2.407 1.641-2.407 2.422s.357 2.672 2.407 2.672");
}

.vmgbtnwjz {
  d: path("M9.65 14.25c0-1.831.932-2.445 2.081-2.445s2.081.878 2.081 2.444v1.964c0 1.35-.932 2.27-2.08 2.27c-1.15 0-2.081-.92-2.081-2.27z");
}

.w4f-f8gin {
  stop-color: var(--svg-color--f2af43, #F2AF43);
  stop-opacity: 0;
}

.wbg6vsbgl {
  stop-color: var(--svg-color--eda220, #EDA220);
}

.wbgshgbmf {
  stop-color: var(--svg-color--ffc53b, #FFC53B);
}

.xsg9vwb1s {
  stop-color: var(--svg-color--ffd131, #FFD131);
}

.y1oagzdpx {
  stop-color: var(--svg-color--c3832a, #C3832A);
  stop-opacity: 0;
}

.yad7sobtt {
  stroke: var(--svg-color--ffe746, #FFE746);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.575 3.66l.862 9.316");
}

.zs67g1hyu {
  stop-color: var(--svg-color--f58e33, #F58E33);
}

.zwtfjqb1k {
  stop-color: var(--svg-color--eeae11, #EEAE11);
  stop-opacity: 0;
}

</style>
