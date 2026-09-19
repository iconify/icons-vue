<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iv7tS1c)" class="voez7_7eo"/><path fill="url(#irEFgWV)" class="voez7_7eo"/><path fill="url(#iboETod)" class="voez7_7eo"/><path fill="url(#ipDvDAb)" class="voez7_7eo"/><g filter="url(#izeVgCc)"><path fill="url(#iNNbnmx)" class="ojyw-7bhv"/><path fill="url(#igyBYMc)" class="ojyw-7bhv"/><path fill="url(#ibqGb3k)" class="ojyw-7bhv"/></g><path fill="url(#iGLTtde)" class="ojyw-7bhv"/><g filter="url(#ixPQ0Lc)"><path fill="url(#i74BxOc)" class="j_j7ocf2t"/></g><path fill="url(#iIuXrPr)" class="d7_eu_rpl"/><path fill="url(#iLowKHc)" class="d7_eu_rpl"/><path fill="url(#ihqb2ed)" class="keyelmbae"/><path fill="url(#iApb9me)" class="kwwhxlbpu"/><path fill="url(#izoQ7td)" class="kwwhxlbpu"/><g filter="url(#itrmZse)"><rect class="cszhxkb1i"/></g><g filter="url(#ifj8eTM)"><rect class="dkisfnbtl"/></g><g filter="url(#ifYBBIK)"><path class="eag3h4dnl"/></g><g filter="url(#ixKfc7c)"><rect fill="url(#iXGySMb)" class="k7gew3uhp"/><rect fill="url(#iq3mtMc)" class="k7gew3uhp"/><rect fill="url(#itZRPLb)" class="k7gew3uhp"/></g><g filter="url(#ifiwEte)"><path fill="url(#iL4AxZb)" class="gzvr8tw0t"/><path fill="url(#i69bYBe)" class="gzvr8tw0t"/><path fill="url(#ibjajqd)" class="gzvr8tw0t"/></g><g filter="url(#iPvwkYA)"><path fill="url(#i4UIH2T)" class="r3xk2i_xp"/><path fill="url(#iJsm9yb)" class="r3xk2i_xp"/><path fill="url(#iC79XFc)" class="r3xk2i_xp"/></g><g filter="url(#izlyy6d)"><path fill="url(#icneuGe)" class="tw602mtxn"/><path fill="url(#imJ72zd)" class="tw602mtxn"/><path fill="url(#iSVCIxe)" class="tw602mtxn"/></g><g filter="url(#ileDBtd)"><path fill="url(#i6b20ae)" class="hav_5lqbk"/><path fill="url(#iDR7xTc)" class="hav_5lqbk"/><path fill="url(#iajNOXb)" class="hav_5lqbk"/></g><defs><radialGradient id="iv7tS1c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25247 -1.95587 2.24001 -1.43442 13.788 29.82)" gradientUnits="userSpaceOnUse"><stop offset=".338" class="uv9fw_bow"/><stop offset="1" class="gv2icvbhu"/></radialGradient><radialGradient id="irEFgWV" cx="0" cy="0" r="1" gradientTransform="matrix(2.4271 .3095 -.34827 2.7312 11.982 28.898)" gradientUnits="userSpaceOnUse"><stop offset=".631" class="b08doi50s"/><stop offset="1" class="qi6zpjzjq"/></radialGradient><radialGradient id="iboETod" cx="0" cy="0" r="1" gradientTransform="rotate(-74.407 26.572 6.556)scale(1.54896 .61917)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="of08xnbgh"/><stop offset="1" class="b_3elspxv"/></radialGradient><radialGradient id="ipDvDAb" cx="0" cy="0" r="1" gradientTransform="matrix(.85937 -.20313 .2583 1.09278 11.09 29.874)" gradientUnits="userSpaceOnUse"><stop offset=".672" class="ctnrgnbyt"/><stop offset=".846" class="co89d-sus"/></radialGradient><radialGradient id="iNNbnmx" cx="0" cy="0" r="1" gradientTransform="matrix(0 23.8125 -32.6082 0 21.254 1.304)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="p-_4qwrxu"/><stop offset="1" class="l_6w7vugn"/></radialGradient><radialGradient id="igyBYMc" cx="0" cy="0" r="1" gradientTransform="rotate(-27.693 58.04 -2.026)scale(12.776 16.6012)" gradientUnits="userSpaceOnUse"><stop class="lifjxtbat"/><stop offset="1" class="cgjqu2k0h"/></radialGradient><radialGradient id="ibqGb3k" cx="0" cy="0" r="1" gradientTransform="matrix(-11.2854 0 0 -5.97903 26.058 14.09)" gradientUnits="userSpaceOnUse"><stop class="z5duhrbsp"/><stop offset="1" class="gxik_obou"/></radialGradient><radialGradient id="i74BxOc" cx="0" cy="0" r="1" gradientTransform="matrix(2.88349 -18.8125 4.89318 .75 17.465 28.678)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="d9jo6s4pg"/><stop offset="1" class="uyavxvb7h"/></radialGradient><radialGradient id="iIuXrPr" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -3.18368 20.012 29.757)" gradientUnits="userSpaceOnUse"><stop class="jc10fq4fu"/><stop offset="1" class="o00p-zggv"/></radialGradient><radialGradient id="iLowKHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.72864 0 0 -.73638 20.031 30)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="kd0ge0bij"/><stop offset="1" class="yyek0xbmr"/></radialGradient><radialGradient id="ihqb2ed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69121 0 0 -1.74037 21.508 29.878)" gradientUnits="userSpaceOnUse"><stop class="rlfn4ab9y"/><stop offset="1" class="lag7-hbjo"/></radialGradient><radialGradient id="iApb9me" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07101 0 0 -.91715 11.328 29.687)" gradientUnits="userSpaceOnUse"><stop class="s6lo_dz1s"/><stop offset="1" class="xmojfdb3m"/></radialGradient><radialGradient id="izoQ7td" cx="0" cy="0" r="1" gradientTransform="matrix(.69531 0 0 .52896 9.715 30.046)" gradientUnits="userSpaceOnUse"><stop class="bi3wb-lzc"/><stop offset="1" class="n7-2lvb2c"/></radialGradient><radialGradient id="iq3mtMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7796 -5.30132 0 14.809 4.928)" gradientUnits="userSpaceOnUse"><stop class="sms71ibmt"/><stop offset="1" class="os37q3hum"/></radialGradient><radialGradient id="i69bYBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7796 -8.12117 0 14.896 13.897)" gradientUnits="userSpaceOnUse"><stop class="sms71ibmt"/><stop offset="1" class="os37q3hum"/></radialGradient><radialGradient id="iJsm9yb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.125 -12.79 0 28.434 8.936)" gradientUnits="userSpaceOnUse"><stop class="b2n4qk4qa"/><stop offset="1" class="lpg15ab9e"/></radialGradient><radialGradient id="imJ72zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.125 -7.13996 0 21.17 18.787)" gradientUnits="userSpaceOnUse"><stop class="sms71ibmt"/><stop offset="1" class="os37q3hum"/></radialGradient><radialGradient id="iDR7xTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.125 -5.32045 0 17.554 24.795)" gradientUnits="userSpaceOnUse"><stop class="sms71ibmt"/><stop offset="1" class="os37q3hum"/></radialGradient><linearGradient id="iGLTtde" x1="27.715" x2="27.715" y1=".303" y2="2.616" gradientUnits="userSpaceOnUse"><stop class="psdfwqovm"/><stop offset="1" class="eyupatunw"/></linearGradient><linearGradient id="iXGySMb" x1="7.469" x2="15.201" y1="5.085" y2="5.085" gradientUnits="userSpaceOnUse"><stop class="u2gsknesm"/><stop offset="1" class="u8tt1se-f"/></linearGradient><linearGradient id="itZRPLb" x1="16.465" x2="15.184" y1="5.366" y2="5.366" gradientUnits="userSpaceOnUse"><stop class="m_f0evbyx"/><stop offset="1" class="g4udvybro"/></linearGradient><linearGradient id="iL4AxZb" x1="3.652" x2="15.498" y1="14.053" y2="14.053" gradientUnits="userSpaceOnUse"><stop class="u2gsknesm"/><stop offset="1" class="u8tt1se-f"/></linearGradient><linearGradient id="ibjajqd" x1="17.434" x2="15.471" y1="14.335" y2="14.335" gradientUnits="userSpaceOnUse"><stop class="m_f0evbyx"/><stop offset="1" class="g4udvybro"/></linearGradient><linearGradient id="i4UIH2T" x1="19.57" x2="28.908" y1="9.093" y2="9.093" gradientUnits="userSpaceOnUse"><stop class="u2gsknesm"/><stop offset="1" class="u8tt1se-f"/></linearGradient><linearGradient id="iC79XFc" x1="30.434" x2="28.886" y1="9.374" y2="9.374" gradientUnits="userSpaceOnUse"><stop class="vy8p5ebfq"/><stop offset="1" class="qsbizomcr"/></linearGradient><linearGradient id="icneuGe" x1="15.566" x2="21.469" y1="18.944" y2="18.944" gradientUnits="userSpaceOnUse"><stop class="u2gsknesm"/><stop offset="1" class="u8tt1se-f"/></linearGradient><linearGradient id="iSVCIxe" x1="22.434" x2="21.456" y1="19.225" y2="19.225" gradientUnits="userSpaceOnUse"><stop class="m_f0evbyx"/><stop offset="1" class="g4udvybro"/></linearGradient><linearGradient id="i6b20ae" x1="13.379" x2="17.777" y1="24.951" y2="24.951" gradientUnits="userSpaceOnUse"><stop class="u2gsknesm"/><stop offset="1" class="u8tt1se-f"/></linearGradient><linearGradient id="iajNOXb" x1="18.496" x2="17.767" y1="25.233" y2="25.233" gradientUnits="userSpaceOnUse"><stop class="m_f0evbyx"/><stop offset="1" class="g4udvybro"/></linearGradient><filter id="izeVgCc" width="28.5" height="28.5" x="1.566" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.509804 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15245"/></filter><filter id="ixPQ0Lc" width="9.133" height="16.438" x="12.715" y="14.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15245" stdDeviation=".75"/></filter><filter id="itrmZse" width="12.996" height="5.938" x="3.581" y="3.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15245" stdDeviation="1"/></filter><filter id="ifj8eTM" width="12.996" height="5.938" x="15.935" y="7.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15245" stdDeviation="1"/></filter><filter id="ifYBBIK" width="10.092" height="5.938" x="12.577" y="17.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15245" stdDeviation="1"/></filter><filter id="ixKfc7c" width="9.246" height="2.188" x="7.469" y="3.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.454902 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15245"/></filter><filter id="ifiwEte" width="14.031" height="2.188" x="3.652" y="12.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.454902 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15245"/></filter><filter id="iPvwkYA" width="11.113" height="2.188" x="19.57" y="7.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.454902 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15245"/></filter><filter id="izlyy6d" width="7.117" height="2.188" x="15.566" y="17.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.454902 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15245"/></filter><filter id="ileDBtd" width="5.367" height="2.188" x="13.379" y="23.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.454902 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15245"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tornado" /></template>
<style>
.b_3elspxv {
  stop-color: var(--svg-color--878189, #878189);
  stop-opacity: 0;
}

.b08doi50s {
  stop-color: var(--svg-color--b6b4b6, #B6B4B6);
  stop-opacity: 0;
}

.b2n4qk4qa {
  stop-color: var(--svg-color--d2d0d5, #D2D0D5);
}

.bi3wb-lzc {
  stop-color: var(--svg-color--837589, #837589);
}

.cgjqu2k0h {
  stop-color: var(--svg-color--8b8191, #8B8191);
  stop-opacity: 0;
}

.co89d-sus {
  stop-color: var(--svg-color--7b777d, #7B777D);
  stop-opacity: 0;
}

.cszhxkb1i {
  width: 8.996px;
  height: 1.938px;
  x: 5.581px;
  y: 5.668px;
  fill: var(--svg-color--b0a9b3, #B0A9B3);
  rx: 0.969px;
}

.ctnrgnbyt {
  stop-color: var(--svg-color--7b777d, #7B777D);
}

.d7_eu_rpl {
  d: path("M20.715 30c0-1.1-.9-2-2-2s-2 .9-2 2");
}

.d9jo6s4pg {
  stop-color: var(--svg-color--d2ccd4, #D2CCD4);
}

.dkisfnbtl {
  width: 8.996px;
  height: 1.938px;
  x: 17.936px;
  y: 9.983px;
  fill: var(--svg-color--b0a9b3, #B0A9B3);
  rx: 0.969px;
}

.eag3h4dnl {
  fill: var(--svg-color--9f98a2, #9F98A2);
  d: path("M14.577 20.452a.97.97 0 0 1 .969-.969H19.7a.969.969 0 1 1 0 1.938h-4.154a.97.97 0 0 1-.969-.969");
}

.eyupatunw {
  stop-color: var(--svg-color--cfccd0, #CFCCD0);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g4udvybro {
  stop-color: var(--svg-color--ecebed, #ECEBED);
  stop-opacity: 0;
}

.gv2icvbhu {
  stop-color: var(--svg-color--807b83, #807B83);
}

.gxik_obou {
  stop-color: var(--svg-color--aba5ae, #ABA5AE);
  stop-opacity: 0;
}

.gzvr8tw0t {
  d: path("M3.652 14.054a.97.97 0 0 1 .97-.97h11.843a.969.969 0 1 1 0 1.938H4.62a.97.97 0 0 1-.969-.969");
}

.hav_5lqbk {
  d: path("M13.379 24.952a.97.97 0 0 1 .969-.97h3.18a.969.969 0 0 1 0 1.938h-3.18a.97.97 0 0 1-.97-.969");
}

.j_j7ocf2t {
  d: path("M14.215 15.991c4.375 5.688 2.916 11.563 1.875 13.438h1.25c3.65-5.75 3.229-11.521 2.562-13.438z");
}

.jc10fq4fu {
  stop-color: var(--svg-color--dad8db, #DAD8DB);
}

.k7gew3uhp {
  width: 8.996px;
  height: 1.938px;
  x: 7.469px;
  y: 4.116px;
  rx: 0.969px;
}

.kd0ge0bij {
  stop-color: var(--svg-color--716b73, #716B73);
}

.keyelmbae {
  d: path("M21.715 30c0-.55-.45-1-1-1s-1 .45-1 1");
}

.kwwhxlbpu {
  d: path("M11.715 30c0-.55-.45-1-1-1s-1 .45-1 1");
}

.l_6w7vugn {
  stop-color: var(--svg-color--afa5b3, #AFA5B3);
}

.lag7-hbjo {
  stop-color: var(--svg-color--78707b, #78707B);
}

.lifjxtbat {
  stop-color: var(--svg-color--8b8191, #8B8191);
}

.lpg15ab9e {
  stop-color: var(--svg-color--d2d0d5, #D2D0D5);
  stop-opacity: 0;
}

.m_f0evbyx {
  stop-color: var(--svg-color--ecebed, #ECEBED);
}

.n7-2lvb2c {
  stop-color: var(--svg-color--837589, #837589);
  stop-opacity: 0;
}

.o00p-zggv {
  stop-color: var(--svg-color--766f7c, #766F7C);
}

.of08xnbgh {
  stop-color: var(--svg-color--878189, #878189);
}

.ojyw-7bhv {
  d: path("M3.006 2c-.8 0-1.44.65-1.44 1.44V5c0 8.2 6.61 11.72 10 14.66c5 4.34 3.62 7.75 2 10.34h4c5.74-8.5 2.5-10.15 5-13.99c1.97-3.02 7-4.01 7-11.01V3.44c0-.8-.65-1.44-1.44-1.44z");
}

.os37q3hum {
  stop-color: var(--svg-color--d6d5d7, #D6D5D7);
  stop-opacity: 0;
}

.p-_4qwrxu {
  stop-color: var(--svg-color--e7e3e9, #E7E3E9);
}

.psdfwqovm {
  stop-color: var(--svg-color--cfccd0, #CFCCD0);
}

.qi6zpjzjq {
  stop-color: var(--svg-color--b6b4b6, #B6B4B6);
}

.qsbizomcr {
  stop-color: var(--svg-color--d2cdd4, #D2CDD4);
  stop-opacity: 0;
}

.r3xk2i_xp {
  d: path("M19.57 9.093a.97.97 0 0 1 .97-.97h8.925a.969.969 0 1 1 0 1.937h-8.926a.97.97 0 0 1-.969-.967");
}

.rlfn4ab9y {
  stop-color: var(--svg-color--e0dee1, #E0DEE1);
}

.s6lo_dz1s {
  stop-color: var(--svg-color--c3c0c5, #C3C0C5);
}

.sms71ibmt {
  stop-color: var(--svg-color--d6d5d7, #D6D5D7);
}

.tw602mtxn {
  d: path("M15.566 18.944a.97.97 0 0 1 .97-.97h4.929a.969.969 0 1 1 0 1.938h-4.93a.97.97 0 0 1-.969-.968");
}

.u2gsknesm {
  stop-color: var(--svg-color--888689, #888689);
}

.u8tt1se-f {
  stop-color: var(--svg-color--c7c7c8, #C7C7C8);
}

.uv9fw_bow {
  stop-color: var(--svg-color--a19aa4, #A19AA4);
}

.uyavxvb7h {
  stop-color: var(--svg-color--d2ccd4, #D2CCD4);
  stop-opacity: 0;
}

.voez7_7eo {
  d: path("M14.715 30c0-1.1-.9-2-2-2s-2 .9-2 2");
}

.vy8p5ebfq {
  stop-color: var(--svg-color--d2cdd4, #D2CDD4);
}

.xmojfdb3m {
  stop-color: var(--svg-color--8b858e, #8B858E);
}

.yyek0xbmr {
  stop-color: var(--svg-color--716b73, #716B73);
  stop-opacity: 0;
}

.z5duhrbsp {
  stop-color: var(--svg-color--aba5ae, #ABA5AE);
}

</style>
