<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i355Llc)" transform="rotate(30 17.206 21.114)" class="pffl8xbkn"/><path fill="url(#ijPdoyd)" transform="rotate(30 17.206 21.114)" class="pffl8xbkn"/><path fill="url(#iNiipIb)" transform="rotate(30 17.206 21.114)" class="pffl8xbkn"/><g filter="url(#ivWFxRX)"><path fill="url(#iJ1sqje)" class="j7hwwypke"/><path fill="url(#iLpVHsc)" class="j7hwwypke"/></g><path fill="url(#i5zb49d)" class="i580vh2cf"/><path fill="url(#i2OIE1c)" class="i580vh2cf"/><path fill="url(#isxR2zb)" class="i580vh2cf"/><path fill="url(#iH0vpEe)" class="i580vh2cf"/><g filter="url(#inJ40we)"><path fill="url(#ipMmShe)" class="kmwckgbky"/></g><g filter="url(#ifwt9bb)"><circle fill="url(#iXpiFPd)" class="vxwksyblw"/></g><g filter="url(#iLUbihd)"><circle fill="url(#iX2UnYm)" class="xro8q_8mx"/></g><g filter="url(#iUK4Apf)"><circle fill="url(#iYfzVMy)" class="f-gwwpb-f"/></g><g filter="url(#imgZlHY)"><circle fill="url(#ihfvSpo)" class="ppnh_0hgw"/></g><circle fill="url(#i9H1ODe)" class="vl2gqni1g"/><circle fill="url(#irhnlce)" class="vl2gqni1g"/><g filter="url(#iCFBHHw)"><circle fill="url(#iO94Mtb)" class="e5-9tzcfy"/></g><circle fill="url(#iVfjqYc)" class="s5b71olgm"/><circle fill="url(#iUJBhlb)" class="s5b71olgm"/><g filter="url(#iUpC4tb)"><circle fill="url(#i6FFGXm)" class="xhh6a1m7t"/></g><path fill="url(#ifPCVJc)" class="om0xlfhzs"/><path fill="url(#iToBtCd)" class="om0xlfhzs"/><path fill="url(#iST6JMd)" class="om0xlfhzs"/><path fill="url(#i55OJ6b)" class="om0xlfhzs"/><path fill="url(#igswd4z)" class="om0xlfhzs"/><circle fill="url(#iEebd3b)" class="q3ufn-1jy"/><circle fill="url(#iN9Rv1d)" class="q3ufn-1jy"/><circle fill="url(#i6hlFjc)" class="q3ufn-1jy"/><g filter="url(#igrtZec)"><circle stroke="url(#iECwnQc)" class="cs37y3bbp"/></g><g filter="url(#iXE877c)"><circle stroke="url(#ic45Dzb)" class="emlxpwb3y"/></g><circle fill="url(#izjccBe)" class="zpx0vabtp"/><g filter="url(#isIWpNd)"><circle fill="url(#iAt1zrQ)" class="ioohk9m8c"/></g><defs><radialGradient id="i355Llc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.44285 -3.028 5.03878 -4.06506 19.104 23.572)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="gu2-71plr"/><stop offset="1" class="gg9nsrbxn"/></radialGradient><radialGradient id="iJ1sqje" cx="0" cy="0" r="1" gradientTransform="rotate(130.079 7.028 13.834)scale(9.29016 8.30635)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="kigs-vdaz"/><stop offset="1" class="yo-g6tbho"/></radialGradient><radialGradient id="iLpVHsc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.54035 -1.21828 .84658 -3.15507 20.979 13.883)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="uwhbldblx"/><stop offset="1" class="c2eeg5blb"/></radialGradient><radialGradient id="i2OIE1c" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -.4375 .34008 1.3603 24.754 12.441)" gradientUnits="userSpaceOnUse"><stop class="e8wr6m1jr"/><stop offset="1" class="ijsxj-cof"/></radialGradient><radialGradient id="isxR2zb" cx="0" cy="0" r="1" gradientTransform="matrix(9.23065 .09185 -.08779 8.82245 5.253 5.124)" gradientUnits="userSpaceOnUse"><stop class="ne9u15b3m"/><stop offset="1" class="rnw650k3z"/></radialGradient><radialGradient id="i9H1ODe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.83763 2.33038 -1.51409 -2.49337 13.486 5.42)" gradientUnits="userSpaceOnUse"><stop class="l__3lzboo"/><stop offset="1" class="kpm_48blk"/></radialGradient><radialGradient id="irhnlce" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.9785 -4.47883 0 11.684 4.227)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="r0jizu5wg"/><stop offset="1" class="flkjetb6i"/></radialGradient><radialGradient id="iVfjqYc" cx="0" cy="0" r="1" gradientTransform="rotate(148.732 10.451 9.706)scale(3.68833 2.39637)" gradientUnits="userSpaceOnUse"><stop class="l__3lzboo"/><stop offset=".938" class="smv3_qass"/><stop offset="1" class="tztm-1bmo"/></radialGradient><radialGradient id="iUJBhlb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.08982 -3.67935 0 22.941 11.6)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="r0jizu5wg"/><stop offset="1" class="flkjetb6i"/></radialGradient><radialGradient id="ifPCVJc" cx="0" cy="0" r="1" gradientTransform="matrix(2.53125 2.46875 -1.88174 1.92938 17.785 26.223)" gradientUnits="userSpaceOnUse"><stop class="mtn-ihv0n"/><stop offset="1" class="rbdf-x3gv"/></radialGradient><radialGradient id="i55OJ6b" cx="0" cy="0" r="1" gradientTransform="rotate(74.936 -9.917 22.302)scale(3.59219 3.60781)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="yfqrywb9m"/><stop offset="1" class="xewe24fkl"/></radialGradient><radialGradient id="igswd4z" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 0 0 -.625 23.52 28.535)" gradientUnits="userSpaceOnUse"><stop class="gqhe0ubwc"/><stop offset="1" class="cv-21ldlw"/></radialGradient><radialGradient id="iEebd3b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.65624 1.87502 -1.71032 -2.42292 17.473 24.629)" gradientUnits="userSpaceOnUse"><stop class="hy06t8x4y"/><stop offset="1" class="c730igbjb"/></radialGradient><radialGradient id="iN9Rv1d" cx="0" cy="0" r="1" gradientTransform="rotate(90 -4.164 20.309)scale(3.07812)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="oy_lb_wsb"/><stop offset="1" class="jxhqlnvcp"/></radialGradient><radialGradient id="i6hlFjc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -4.12032 18.645 25.215)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="qlhrhsl_l"/><stop offset="1" class="wqho-7zfx"/></radialGradient><radialGradient id="izjccBe" cx="0" cy="0" r="1" gradientTransform="rotate(135.387 3.25 15.812)scale(1.63522 1.6017)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="zxn61fzgd"/><stop offset="1" class="l75e8t48c"/></radialGradient><linearGradient id="ijPdoyd" x1="21.236" x2="18.448" y1="20.248" y2="22.795" gradientUnits="userSpaceOnUse"><stop class="ure75eedr"/><stop offset="1" class="ty1vchb2j"/></linearGradient><linearGradient id="iNiipIb" x1="17.219" x2="18.583" y1="22.603" y2="22.591" gradientUnits="userSpaceOnUse"><stop class="mpupwzbcr"/><stop offset="1" class="zc3848bes"/></linearGradient><linearGradient id="i5zb49d" x1="20.629" x2="16.129" y1="9.262" y2="15.66" gradientUnits="userSpaceOnUse"><stop class="wtqs4fpem"/><stop offset="1" class="g_2fpba8i"/></linearGradient><linearGradient id="iH0vpEe" x1="12.469" x2="14.265" y1="14.578" y2="9.67" gradientUnits="userSpaceOnUse"><stop offset=".111" class="diic9znof"/><stop offset="1" class="oq216yulu"/></linearGradient><linearGradient id="ipMmShe" x1="25.151" x2="13.918" y1="12.767" y2="3.792" gradientUnits="userSpaceOnUse"><stop class="tzvbfxhio"/><stop offset=".554" class="heby3r06z"/><stop offset="1" class="tzvbfxhio"/></linearGradient><linearGradient id="iXpiFPd" x1="14.129" x2="8.904" y1="5.997" y2="6.525" gradientUnits="userSpaceOnUse"><stop class="r1w0-tbwy"/><stop offset="1" class="zidv-cbxv"/></linearGradient><linearGradient id="iX2UnYm" x1="9.773" x2="13.67" y1="7.449" y2="5.215" gradientUnits="userSpaceOnUse"><stop class="ucmt4407b"/><stop offset="1" class="ae9ny3bqs"/></linearGradient><linearGradient id="iYfzVMy" x1="24.748" x2="21.355" y1="12.6" y2="15.407" gradientUnits="userSpaceOnUse"><stop class="t6hpihbkj"/><stop offset="1" class="toir6zbvy"/></linearGradient><linearGradient id="ihfvSpo" x1="21.371" x2="24.574" y1="14.246" y2="12.41" gradientUnits="userSpaceOnUse"><stop class="ucmt4407b"/><stop offset="1" class="ae9ny3bqs"/></linearGradient><linearGradient id="iO94Mtb" x1="13.198" x2="10.169" y1="5.389" y2="6.988" gradientUnits="userSpaceOnUse"><stop class="mq43_kbrh"/><stop offset="1" class="my4is0xtv"/></linearGradient><linearGradient id="i6FFGXm" x1="23.953" x2="21.93" y1="12.709" y2="13.777" gradientUnits="userSpaceOnUse"><stop class="f1cp_ew4h"/><stop offset="1" class="t-yjx6b0j"/></linearGradient><linearGradient id="iToBtCd" x1="14.195" x2="15.41" y1="28.879" y2="28.879" gradientUnits="userSpaceOnUse"><stop class="yfqrywb9m"/><stop offset="1" class="xewe24fkl"/></linearGradient><linearGradient id="iST6JMd" x1="19.129" x2="19.129" y1="30.191" y2="28.91" gradientUnits="userSpaceOnUse"><stop class="rans2gb5a"/><stop offset="1" class="sibisgb3f"/></linearGradient><linearGradient id="iECwnQc" x1="16.716" x2="15.545" y1="24.877" y2="25.929" gradientUnits="userSpaceOnUse"><stop class="qfleuzzqm"/><stop offset="1" class="l_h6z9u-o"/></linearGradient><linearGradient id="ic45Dzb" x1="15.559" x2="16.824" y1="25.645" y2="24.285" gradientUnits="userSpaceOnUse"><stop class="o7vi4obpf"/><stop offset="1" class="g2jp2pgmi"/></linearGradient><linearGradient id="iAt1zrQ" x1="16.539" x2="15.805" y1="24.828" y2="25.656" gradientUnits="userSpaceOnUse"><stop class="wx9i0eb9j"/><stop offset="1" class="kg_slabrq"/></linearGradient><filter id="ivWFxRX" width="10.394" height="11.587" x="16.157" y="11.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.05"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4421"/></filter><filter id="inJ40we" width="10.969" height="8.282" x="12.932" y="4.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4421" stdDeviation=".5"/></filter><filter id="ifwt9bb" width="5.39" height="5.39" x="8.988" y="3.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4421" stdDeviation=".125"/></filter><filter id="iLUbihd" width="4.458" height="4.458" x="9.455" y="4.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4421" stdDeviation=".05"/></filter><filter id="iUK4Apf" width="4.549" height="4.549" x="20.667" y="11.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4421" stdDeviation=".125"/></filter><filter id="imgZlHY" width="3.7" height="3.7" x="21.091" y="11.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4421" stdDeviation=".05"/></filter><filter id="iCFBHHw" width="3.529" height="3.529" x="9.919" y="4.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4421" stdDeviation=".125"/></filter><filter id="iUpC4tb" width="2.522" height="2.522" x="21.68" y="12.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4421" stdDeviation=".125"/></filter><filter id="igrtZec" width="2.511" height="2.511" x="14.931" y="23.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4421" stdDeviation=".125"/></filter><filter id="iXE877c" width="1.744" height="1.744" x="15.273" y="24.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4421" stdDeviation=".025"/></filter><filter id="isIWpNd" width="1.192" height="1.192" x="15.548" y="24.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4421" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mechanical-leg" /></template>
<style>
.ae9ny3bqs {
  stop-color: var(--svg-color--75707a, #75707A);
  stop-opacity: 0;
}

.c2eeg5blb {
  stop-color: var(--svg-color--635d6a, #635D6A);
  stop-opacity: 0;
}

.c730igbjb {
  stop-color: var(--svg-color--8d8893, #8D8893);
}

.cs37y3bbp {
  cx: 16.186px;
  cy: 25.173px;
  r: 0.88px;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
}

.cv-21ldlw {
  stop-color: var(--svg-color--c0bec4, #C0BEC4);
  stop-opacity: 0;
}

.diic9znof {
  stop-color: var(--svg-color--7b6591, #7B6591);
}

.e5-9tzcfy {
  cx: 11.684px;
  cy: 6.398px;
  r: 1.514px;
}

.e8wr6m1jr {
  stop-color: var(--svg-color--d0cfd1, #D0CFD1);
}

.emlxpwb3y {
  cx: 16.145px;
  cy: 25.215px;
  r: 0.809px;
  stroke-width: var(--svg-stroke-width--0-025px, 0.025px);
}

.f-gwwpb-f {
  cx: 22.941px;
  cy: 13.383px;
  r: 2.025px;
}

.f1cp_ew4h {
  stop-color: var(--svg-color--c1bdc6, #C1BDC6);
}

.flkjetb6i {
  stop-color: var(--svg-color--907ea2, #907EA2);
}

.ft5dv1b6b {
  fill: none;
}

.g_2fpba8i {
  stop-color: var(--svg-color--7f7589, #7F7589);
}

.g2jp2pgmi {
  stop-color: var(--svg-color--797280, #797280);
  stop-opacity: 0;
}

.gg9nsrbxn {
  stop-color: var(--svg-color--89878c, #89878C);
}

.gqhe0ubwc {
  stop-color: var(--svg-color--c0bec4, #C0BEC4);
}

.gu2-71plr {
  stop-color: var(--svg-color--cdc9d3, #CDC9D3);
}

.heby3r06z {
  stop-color: var(--svg-color--cfced1, #CFCED1);
}

.hy06t8x4y {
  stop-color: var(--svg-color--cbc8cd, #CBC8CD);
}

.i580vh2cf {
  d: path("M12.738 2.152a4.39 4.39 0 0 0-5.535 4.233a4.37 4.37 0 0 0 1.278 3.094c1.058 1.138 3.854 2.637 4.265 2.845c1.062.538 2.029.467 2.712.417l.147-.01l.126-.01c.49-.035.902-.065 1.32.252c.127.096.517.384 1.023.757c.932.688 2.26 1.667 3.07 2.282c.796.603 2.422.773 3.626-.04v-.006a3.01 3.01 0 0 0 1.372-2.414c.063-1.704-.855-2.573-1.497-3.032c-1.132-.81-6.474-4.818-8.907-6.672c-.614-.47-1.925-1.43-3-1.696");
}

.ijsxj-cof {
  stop-color: var(--svg-color--d0cfd1, #D0CFD1);
  stop-opacity: 0;
}

.ioohk9m8c {
  cx: 16.145px;
  cy: 25.215px;
  r: 0.496px;
}

.j7hwwypke {
  d: path("M19.395 12.77c.761-1.32 2.341-1.887 3.766-1.519c.586.151 1.008.629 1.3 1.159l1.34 2.422l-3.577 6.22a3.251 3.251 0 0 1-5.631-3.252z");
}

.jxhqlnvcp {
  stop-color: var(--svg-color--836a9a, #836A9A);
}

.kg_slabrq {
  stop-color: var(--svg-color--b1a9b9, #B1A9B9);
}

.kigs-vdaz {
  stop-color: var(--svg-color--b0abb7, #B0ABB7);
}

.kmwckgbky {
  d: path("m22.63 11.04l-6.715-4.86a1.25 1.25 0 1 0-1.458 2.03l2.014 1.436c.343.243.785.296 1.175.14c.39-.157.833-.104 1.175.14l3.044 2.176a.655.655 0 0 0 .765-1.063");
}

.kpm_48blk {
  stop-color: var(--svg-color--8e8894, #8E8894);
}

.l__3lzboo {
  stop-color: var(--svg-color--e5e4e6, #E5E4E6);
}

.l_h6z9u-o {
  stop-color: var(--svg-color--88818f, #88818F);
}

.l75e8t48c {
  stop-color: var(--svg-color--9a90a5, #9A90A5);
}

.mpupwzbcr {
  stop-color: var(--svg-color--8e8d90, #8E8D90);
}

.mq43_kbrh {
  stop-color: var(--svg-color--c1bec5, #C1BEC5);
}

.mtn-ihv0n {
  stop-color: var(--svg-color--c5c2c9, #C5C2C9);
}

.my4is0xtv {
  stop-color: var(--svg-color--b8b4bc, #B8B4BC);
}

.ne9u15b3m {
  stop-color: var(--svg-color--726e77, #726E77);
}

.o7vi4obpf {
  stop-color: var(--svg-color--797280, #797280);
}

.om0xlfhzs {
  d: path("m14.195 24.973l3.29-1.196l4.073 3.683a1.5 1.5 0 0 0 1.006.388h.46a1.04 1.04 0 1 1 0 2.078h-7.529a1.3 1.3 0 0 1-1.3-1.3z");
}

.oq216yulu {
  stop-color: var(--svg-color--7b6591, #7B6591);
  stop-opacity: 0;
}

.oy_lb_wsb {
  stop-color: var(--svg-color--836a9a, #836A9A);
  stop-opacity: 0;
}

.pffl8xbkn {
  d: path("M17.206 21.114h2.124v3.57h-2.124z");
}

.ppnh_0hgw {
  cx: 22.941px;
  cy: 13.383px;
  r: 1.75px;
}

.q3ufn-1jy {
  cx: 16.145px;
  cy: 25.215px;
  r: 2px;
}

.qfleuzzqm {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
}

.qlhrhsl_l {
  stop-color: var(--svg-color--7d7982, #7D7982);
  stop-opacity: 0;
}

.r0jizu5wg {
  stop-color: var(--svg-color--907ea2, #907EA2);
  stop-opacity: 0;
}

.r1w0-tbwy {
  stop-color: var(--svg-color--a3a1a5, #A3A1A5);
}

.rans2gb5a {
  stop-color: var(--svg-color--83669c, #83669C);
}

.rbdf-x3gv {
  stop-color: var(--svg-color--a6a0ad, #A6A0AD);
}

.rnw650k3z {
  stop-color: var(--svg-color--726e77, #726E77);
  stop-opacity: 0;
}

.s5b71olgm {
  cx: 22.941px;
  cy: 13.383px;
  r: 1.672px;
}

.sibisgb3f {
  stop-color: var(--svg-color--83669c, #83669C);
  stop-opacity: 0;
}

.smv3_qass {
  stop-color: var(--svg-color--8e8994, #8E8994);
}

.t-yjx6b0j {
  stop-color: var(--svg-color--b4aeba, #B4AEBA);
}

.t6hpihbkj {
  stop-color: var(--svg-color--b3b2b4, #B3B2B4);
}

.toir6zbvy {
  stop-color: var(--svg-color--736c79, #736C79);
}

.ty1vchb2j {
  stop-color: var(--svg-color--a397af, #A397AF);
  stop-opacity: 0;
}

.tztm-1bmo {
  stop-color: var(--svg-color--908998, #908998);
}

.tzvbfxhio {
  stop-color: var(--svg-color--cfced1, #CFCED1);
  stop-opacity: 0;
}

.ucmt4407b {
  stop-color: var(--svg-color--75707a, #75707A);
}

.ure75eedr {
  stop-color: var(--svg-color--a397af, #A397AF);
}

.uwhbldblx {
  stop-color: var(--svg-color--635d6a, #635D6A);
}

.vl2gqni1g {
  cx: 11.684px;
  cy: 6.398px;
  r: 2.035px;
}

.vxwksyblw {
  cx: 11.684px;
  cy: 6.398px;
  r: 2.445px;
}

.wqho-7zfx {
  stop-color: var(--svg-color--7d7982, #7D7982);
}

.wtqs4fpem {
  stop-color: var(--svg-color--bfbebf, #BFBEBF);
}

.wx9i0eb9j {
  stop-color: var(--svg-color--c3bfc9, #C3BFC9);
}

.xewe24fkl {
  stop-color: var(--svg-color--70667b, #70667B);
  stop-opacity: 0;
}

.xhh6a1m7t {
  cx: 22.941px;
  cy: 13.383px;
  r: 1.011px;
}

.xro8q_8mx {
  cx: 11.684px;
  cy: 6.398px;
  r: 2.129px;
}

.yfqrywb9m {
  stop-color: var(--svg-color--70667b, #70667B);
}

.yo-g6tbho {
  stop-color: var(--svg-color--776f80, #776F80);
}

.zc3848bes {
  stop-color: var(--svg-color--8e8d90, #8E8D90);
  stop-opacity: 0;
}

.zidv-cbxv {
  stop-color: var(--svg-color--6f6b73, #6F6B73);
}

.zpx0vabtp {
  cx: 16.145px;
  cy: 25.215px;
  r: 0.797px;
}

.zxn61fzgd {
  stop-color: var(--svg-color--d8d5dc, #D8D5DC);
}

</style>
