<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iNaPPJd)" class="ulwmo6bxz"/><path fill="url(#idcdfEb)" class="ulwmo6bxz"/><path fill="url(#iuHUfyb)" class="ulwmo6bxz"/><path fill="url(#i395Jte)" class="ikzz9fb4x"/><path fill="url(#i9jY6fb)" class="ikzz9fb4x"/><path fill="url(#ih8W9cd)" class="dfbslvbac"/><path fill="url(#iuUUl5a)" class="agocj7bfn"/><path fill="url(#ig6gNJc)" class="qyh7nfgpa"/><path fill="url(#ioyqPim)" class="qyh7nfgpa"/><path fill="url(#iVCNafb)" class="qyh7nfgpa"/><path fill="url(#ivkhAed)" class="qyh7nfgpa"/><path fill="url(#i5tAGvw)" class="akg06fbkn"/><path fill="url(#iLnt1VF)" class="akg06fbkn"/><path fill="url(#icjrD2d)" class="x6wp9zbzj"/><path fill="url(#ibqBjhc)" class="gh_-ny9mt"/><path fill="url(#iRW6YEe)" class="rerf-jboy"/><path fill="url(#iqpQT2d)" class="moynzsvez"/><path fill="url(#ipdoa9c)" class="moynzsvez"/><path fill="url(#iIdyEBe)" class="moynzsvez"/><g filter="url(#iQ7nx9b)"><path fill="url(#iJUZ99c)" class="s5-l99swo"/><path fill="url(#iB2cl9d)" class="s5-l99swo"/><path fill="url(#iOqhVBb)" class="s5-l99swo"/><path fill="url(#iJuAuAd)" class="s5-l99swo"/><path fill="url(#ieUMtNc)" class="s5-l99swo"/><path fill="url(#iypjgJd)" class="s5-l99swo"/></g><path fill="url(#iLWZz5g)" class="yoofqfgby"/><path fill="url(#i1u628d)" class="yoofqfgby"/><path fill="url(#i3lqG6d)" class="yoofqfgby"/><defs><radialGradient id="iuHUfyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39454 -2.60333 0 9.95 28.601)" gradientUnits="userSpaceOnUse"><stop class="yal9kjbgf"/><stop offset="1" class="nay6h2b9z"/></radialGradient><radialGradient id="i395Jte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14996 0 0 -9.77722 9.656 17.154)" gradientUnits="userSpaceOnUse"><stop class="b73xv5beq"/><stop offset="1" class="bvt1qmbzw"/></radialGradient><radialGradient id="ih8W9cd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.28963 0 0 -4.04398 10 14.697)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="tr_ue7bak"/><stop offset="1" class="kx0p6c2jo"/></radialGradient><radialGradient id="iuUUl5a" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12257 0 0 -4.09517 9.604 9.373)" gradientUnits="userSpaceOnUse"><stop class="zhwi49rhe"/><stop offset="1" class="cekb2pb3e"/></radialGradient><radialGradient id="ivkhAed" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39454 -2.60333 0 25.03 28.601)" gradientUnits="userSpaceOnUse"><stop class="yal9kjbgf"/><stop offset="1" class="nay6h2b9z"/></radialGradient><radialGradient id="i5tAGvw" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14996 0 0 -9.77722 24.656 17.154)" gradientUnits="userSpaceOnUse"><stop class="b73xv5beq"/><stop offset="1" class="bvt1qmbzw"/></radialGradient><radialGradient id="icjrD2d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.28963 0 0 -4.04398 25 14.697)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="tr_ue7bak"/><stop offset="1" class="kx0p6c2jo"/></radialGradient><radialGradient id="ibqBjhc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12257 0 0 -4.09517 24.604 9.373)" gradientUnits="userSpaceOnUse"><stop class="zhwi49rhe"/><stop offset="1" class="cekb2pb3e"/></radialGradient><radialGradient id="ipdoa9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.8125 -.9375 0 27.466 4.625)" gradientUnits="userSpaceOnUse"><stop class="jp-6wtctt"/><stop offset="1" class="g2v66m8sz"/></radialGradient><radialGradient id="iIdyEBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.44958 -1.7557 0 4 4.996)" gradientUnits="userSpaceOnUse"><stop class="p6kuz8k9z"/><stop offset="1" class="n2vlirbvg"/></radialGradient><radialGradient id="iOqhVBb" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 0 0 .44285 2.997 4.297)" gradientUnits="userSpaceOnUse"><stop class="iasetzrnx"/><stop offset="1" class="i5emp6_wo"/></radialGradient><radialGradient id="iJuAuAd" cx="0" cy="0" r="1" gradientTransform="rotate(141.842 14.446 5.924)scale(2.98068 1.89559)" gradientUnits="userSpaceOnUse"><stop class="ivlsnmbhp"/><stop offset="1" class="vr6v9cpbm"/></radialGradient><radialGradient id="ieUMtNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29254 .92325 0 27.215 5.303)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="okja3flis"/><stop offset="1" class="b5j21_atw"/></radialGradient><radialGradient id="iypjgJd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.69865 0 0 -.47746 28.572 4.213)" gradientUnits="userSpaceOnUse"><stop class="zq3v6pxcy"/><stop offset="1" class="xirjgbz0k"/></radialGradient><radialGradient id="i3lqG6d" cx="0" cy="0" r="1" gradientTransform="rotate(161.98 13.948 7.391)scale(1.50074 1.33979)" gradientUnits="userSpaceOnUse"><stop class="kzg7vobdh"/><stop offset="1" class="qyklnjsij"/></radialGradient><linearGradient id="iNaPPJd" x1="6.279" x2="10.425" y1="29.695" y2="29.695" gradientUnits="userSpaceOnUse"><stop class="slaf_cbkc"/><stop offset="1" class="ap_9_ebfl"/></linearGradient><linearGradient id="idcdfEb" x1="8.5" x2="8.5" y1="27.771" y2="28.406" gradientUnits="userSpaceOnUse"><stop class="mg-ugnbzk"/><stop offset="1" class="vj-r49jbv"/></linearGradient><linearGradient id="i9jY6fb" x1="9.707" x2="9.707" y1="28.466" y2="25.702" gradientUnits="userSpaceOnUse"><stop class="q_qaabbbo"/><stop offset="1" class="fvhue48tp"/></linearGradient><linearGradient id="ig6gNJc" x1="21.075" x2="26.075" y1="28.996" y2="28.996" gradientUnits="userSpaceOnUse"><stop class="cko6ucm3i"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="ioyqPim" x1="21.358" x2="25.505" y1="29.695" y2="29.695" gradientUnits="userSpaceOnUse"><stop class="slaf_cbkc"/><stop offset="1" class="ap_9_ebfl"/></linearGradient><linearGradient id="iVCNafb" x1="23.58" x2="23.58" y1="27.771" y2="28.406" gradientUnits="userSpaceOnUse"><stop class="mg-ugnbzk"/><stop offset="1" class="vj-r49jbv"/></linearGradient><linearGradient id="iLnt1VF" x1="24.707" x2="24.707" y1="28.466" y2="25.702" gradientUnits="userSpaceOnUse"><stop class="q_qaabbbo"/><stop offset="1" class="fvhue48tp"/></linearGradient><linearGradient id="iRW6YEe" x1="16.977" x2="15.313" y1="9.996" y2="6.996" gradientUnits="userSpaceOnUse"><stop class="dqglpybgs"/><stop offset="1" class="ryj5gmedk"/></linearGradient><linearGradient id="iqpQT2d" x1="16" x2="16" y1="5.281" y2="6.996" gradientUnits="userSpaceOnUse"><stop class="y-d0p_vic"/><stop offset="1" class="kqh5_g32j"/></linearGradient><linearGradient id="iJUZ99c" x1="2.005" x2="30.005" y1="3.496" y2="3.496" gradientUnits="userSpaceOnUse"><stop class="ez-gcueob"/><stop offset="1" class="lt9xnibvn"/></linearGradient><linearGradient id="iB2cl9d" x1="1.997" x2="4.41" y1="4.428" y2="4.428" gradientUnits="userSpaceOnUse"><stop class="qe5ng0b7q"/><stop offset="1" class="plsvfdb7l"/></linearGradient><linearGradient id="iLWZz5g" x1="16" x2="16" y1="10.996" y2="11.996" gradientUnits="userSpaceOnUse"><stop class="dh_foxr1s"/><stop offset="1" class="y96xt8bob"/></linearGradient><linearGradient id="i1u628d" x1="2.177" x2="3.14" y1="11.996" y2="11.996" gradientUnits="userSpaceOnUse"><stop class="drf2hybij"/><stop offset="1" class="frmc-jcqk"/></linearGradient><filter id="iQ7nx9b" width="28.006" height="3.096" x="1.997" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7403"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:shinto-shrine" /></template>
<style>
.agocj7bfn {
  d: path("M10 6.996H7v3h3z");
}

.akg06fbkn {
  d: path("M25 11.996h-3v16h3z");
}

.ap_9_ebfl {
  stop-color: var(--svg-color--6a587a, #6A587A);
}

.b5j21_atw {
  stop-color: var(--svg-color--6e5d7e, #6E5D7E);
  stop-opacity: 0;
}

.b73xv5beq {
  stop-color: var(--svg-color--ff7a42, #FF7A42);
}

.bvt1qmbzw {
  stop-color: var(--svg-color--d73828, #D73828);
}

.cekb2pb3e {
  stop-color: var(--svg-color--d83c16, #D83C16);
}

.cko6ucm3i {
  stop-color: var(--svg-color--513469, #513469);
}

.dfbslvbac {
  d: path("M10 11.996H7v3h3z");
}

.dh_foxr1s {
  stop-color: var(--svg-color--f97331, #F97331);
}

.dqglpybgs {
  stop-color: var(--svg-color--5e4055, #5E4055);
}

.drf2hybij {
  stop-color: var(--svg-color--c04731, #C04731);
}

.ez-gcueob {
  stop-color: var(--svg-color--443e4a, #443E4A);
}

.frmc-jcqk {
  stop-color: var(--svg-color--c04731, #C04731);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvhue48tp {
  stop-color: var(--svg-color--ed2a3e, #ED2A3E);
  stop-opacity: 0;
}

.g2v66m8sz {
  stop-color: var(--svg-color--ff8d3a, #FF8D3A);
  stop-opacity: 0;
}

.gh_-ny9mt {
  d: path("M25 6.996h-3v3h3z");
}

.i5emp6_wo {
  stop-color: var(--svg-color--2d1c2d, #2D1C2D);
  stop-opacity: 0;
}

.iasetzrnx {
  stop-color: var(--svg-color--2d1c2d, #2D1C2D);
}

.ikzz9fb4x {
  d: path("M10 11.996H7v16h3z");
}

.ivlsnmbhp {
  stop-color: var(--svg-color--705f80, #705F80);
}

.jp-6wtctt {
  stop-color: var(--svg-color--ff8d3a, #FF8D3A);
}

.kqh5_g32j {
  stop-color: var(--svg-color--d51f28, #D51F28);
}

.kx0p6c2jo {
  stop-color: var(--svg-color--30212d, #30212D);
}

.kzg7vobdh {
  stop-color: var(--svg-color--ff8948, #FF8948);
}

.lt9xnibvn {
  stop-color: var(--svg-color--554464, #554464);
}

.mg-ugnbzk {
  stop-color: var(--svg-color--562e43, #562E43);
}

.moynzsvez {
  d: path("M26.43 6.996H5.58c-.87 0-1.58-.71-1.58-1.58v-.42h24v.42c0 .87-.7 1.58-1.57 1.58");
}

.n2vlirbvg {
  stop-color: var(--svg-color--ba402c, #BA402C);
  stop-opacity: 0;
}

.nay6h2b9z {
  stop-color: var(--svg-color--63566e, #63566E);
  stop-opacity: 0;
}

.okja3flis {
  stop-color: var(--svg-color--6e5d7e, #6E5D7E);
}

.p6kuz8k9z {
  stop-color: var(--svg-color--ba402c, #BA402C);
}

.plsvfdb7l {
  stop-color: var(--svg-color--29272c, #29272C);
  stop-opacity: 0;
}

.q_qaabbbo {
  stop-color: var(--svg-color--ed2a3e, #ED2A3E);
}

.qe5ng0b7q {
  stop-color: var(--svg-color--29272c, #29272C);
}

.qyh7nfgpa {
  d: path("M26.08 29.996h-5v-1.16c0-.46.38-.84.84-.84h3.32c.46 0 .84.38.84.84z");
}

.qyklnjsij {
  stop-color: var(--svg-color--ff8948, #FF8948);
  stop-opacity: 0;
}

.rerf-jboy {
  d: path("M18 6.996h-4v3h4z");
}

.ryj5gmedk {
  stop-color: var(--svg-color--301925, #301925);
}

.s5-l99swo {
  d: path("M29.99 2.416v-.02c-.03-.25-.25-.43-.49-.39c-8.69 1.22-18.31 1.22-27 0a.44.44 0 0 0-.49.39v.02c-.11.88.48 1.68 1.33 1.79c.22.03.44.05.66.07v.72h24v-.72c.22-.03.44-.05.66-.07c.85-.11 1.44-.91 1.33-1.79");
}

.slaf_cbkc {
  stop-color: var(--svg-color--2e2a33, #2E2A33);
}

.tr_ue7bak {
  stop-color: var(--svg-color--5e4f69, #5E4F69);
}

.ulwmo6bxz {
  d: path("M11 29.996H6v-1.16c0-.46.38-.84.84-.84h3.32c.46 0 .84.38.84.84z");
}

.vj-r49jbv {
  stop-color: var(--svg-color--562e43, #562E43);
  stop-opacity: 0;
}

.vr6v9cpbm {
  stop-color: var(--svg-color--705f80, #705F80);
  stop-opacity: 0;
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.x6wp9zbzj {
  d: path("M25 11.996h-3v3h3z");
}

.xirjgbz0k {
  stop-color: var(--svg-color--4f2e54, #4F2E54);
  stop-opacity: 0;
}

.y-d0p_vic {
  stop-color: var(--svg-color--fb762f, #FB762F);
}

.y96xt8bob {
  stop-color: var(--svg-color--d52030, #D52030);
}

.yal9kjbgf {
  stop-color: var(--svg-color--63566e, #63566E);
}

.yoofqfgby {
  d: path("M29 11.996H3c-.55 0-1-.45-1-1s.45-1 1-1h26c.55 0 1 .45 1 1s-.44 1-1 1");
}

.zhwi49rhe {
  stop-color: var(--svg-color--ff863a, #FF863A);
}

.zq3v6pxcy {
  stop-color: var(--svg-color--4f2e54, #4F2E54);
}

</style>
