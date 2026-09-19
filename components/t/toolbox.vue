<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZbNsSb)"><path stroke="url(#iaY5bNb)" class="wm8axyb1u"/></g><g filter="url(#ig4Hlic)" class="xl966_bbg"><path stroke="url(#iQWiyLe)" class="w5f5h2c8y"/><path stroke="url(#iCAxWoY)" class="w5f5h2c8y"/></g><g filter="url(#iC4Mnhd)"><path fill="url(#isAvGfb)" class="anndcmbei"/></g><g filter="url(#itBlDBc)"><path class="u96bnhnnt"/></g><g filter="url(#izVGUTc)"><rect class="cqq7uubeq"/></g><g filter="url(#il9rayc)"><rect class="f38kj415i"/><rect fill="url(#iwtQjQc)" class="j5e9fdc1u"/></g><g filter="url(#i4mt58d)"><rect class="j-7duf5zc"/></g><g filter="url(#iVevGDd)"><path stroke="url(#irQqBMd)" class="j_m6a2bnf"/></g><g filter="url(#imEhefe)"><path class="w0xmc0xvr"/><path fill="url(#iQtKjne)" class="fsq2-mbru"/><path fill="url(#ivvQ5pd)" class="fsq2-mbru"/></g><g filter="url(#iRPGpmz)"><path class="e3ys_ccqb"/><path fill="url(#iTBnXad)" class="krkw-8pps"/><path fill="url(#ieGruyg)" class="krkw-8pps"/></g><g filter="url(#igxkkbc)"><path stroke="url(#icZK0fd)" class="b4wj2gklw"/></g><g filter="url(#i7Hwmec)"><path stroke="url(#igFERJe)" class="jggwz76tw"/></g><g filter="url(#ijVEQpE)"><rect fill="url(#ilWwHOb)" class="oey99b63q"/></g><defs><filter id="iZbNsSb" width="11.984" height="5.703" x="9.91" y="5.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.160784 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24749"/></filter><filter id="ig4Hlic" width="11.731" height="5.679" x="10.135" y="5.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24749" stdDeviation=".3"/></filter><filter id="iC4Mnhd" width="29.781" height="21.344" x="2.019" y="9.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.282353 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24749"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.164706 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_24749" result="effect2_innerShadow_18_24749"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.223529 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_24749" result="effect3_innerShadow_18_24749"/></filter><filter id="itBlDBc" width="6.984" height="6.938" x="18.824" y="14.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24749" stdDeviation=".75"/></filter><filter id="izVGUTc" width="19.945" height="1.292" x="5.925" y="22.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.627451 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24749"/></filter><filter id="il9rayc" width="28.25" height="1.242" x="1.785" y="17.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.101961 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24749"/></filter><filter id="i4mt58d" width="19.945" height="1.292" x="5.925" y="25.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.627451 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24749"/></filter><filter id="iVevGDd" width="24.294" height=".7" x="5.732" y="17.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24749" stdDeviation=".125"/></filter><filter id="imEhefe" width="4.484" height="4.438" x="6.925" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.592157 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24749"/></filter><filter id="iRPGpmz" width="4.484" height="4.438" x="20.894" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.592157 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24749"/></filter><filter id="igxkkbc" width="19.526" height=".6" x="6.226" y="23.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24749" stdDeviation=".1"/></filter><filter id="i7Hwmec" width="19.526" height=".6" x="6.226" y="26.052" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24749" stdDeviation=".1"/></filter><filter id="ijVEQpE" width="24.664" height="5.255" x="5.026" y="10.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24749" stdDeviation=".75"/></filter><linearGradient id="iaY5bNb" x1="15.902" x2="15.902" y1="6.688" y2="11.172" gradientUnits="userSpaceOnUse"><stop class="kjgp_qbtb"/><stop offset="1" class="qjflxubqh"/></linearGradient><linearGradient id="iQWiyLe" x1="21.275" x2="13.053" y1="7.458" y2="10.023" gradientUnits="userSpaceOnUse"><stop class="oja805bnd"/><stop offset="1" class="khe1oibhj"/></linearGradient><linearGradient id="iCAxWoY" x1="11.035" x2="12.467" y1="10.566" y2="6.836" gradientUnits="userSpaceOnUse"><stop class="oja805bnd"/><stop offset="1" class="khe1oibhj"/></linearGradient><linearGradient id="isAvGfb" x1="15.91" x2="15.91" y1="15.688" y2="29.875" gradientUnits="userSpaceOnUse"><stop class="fop7ejbxc"/><stop offset="1" class="qe2iy-bgs"/></linearGradient><linearGradient id="iwtQjQc" x1="2.05" x2="7.363" y1="18" y2="18" gradientUnits="userSpaceOnUse"><stop class="d8tg2hgog"/><stop offset="1" class="wn4po7-al"/></linearGradient><linearGradient id="irQqBMd" x1="29.113" x2="10.425" y1="17.25" y2="17.25" gradientUnits="userSpaceOnUse"><stop class="jx_4c3kmr"/><stop offset="1" class="fba-q2bdg"/></linearGradient><linearGradient id="icZK0fd" x1="25.001" x2="4.663" y1="23.209" y2="23.209" gradientUnits="userSpaceOnUse"><stop class="zkroagb7a"/><stop offset="1" class="gb367kdel"/></linearGradient><linearGradient id="igFERJe" x1="25.001" x2="4.663" y1="26.196" y2="26.196" gradientUnits="userSpaceOnUse"><stop class="zkroagb7a"/><stop offset="1" class="gb367kdel"/></linearGradient><linearGradient id="ilWwHOb" x1="28.19" x2="3.599" y1="13.611" y2="13.611" gradientUnits="userSpaceOnUse"><stop class="o8hify2hp"/><stop offset="1" class="bf_jq17la"/></linearGradient><radialGradient id="iQtKjne" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.05159 -3.79105 0 8.917 16.886)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="j-e7u7b_m"/><stop offset="1" class="ti1dz_avj"/></radialGradient><radialGradient id="ivvQ5pd" cx="0" cy="0" r="1" gradientTransform="rotate(135.956 2.192 10.273)scale(1.62184 .44544)" gradientUnits="userSpaceOnUse"><stop class="ykffvac5d"/><stop offset="1" class="om3_icb-a"/></radialGradient><radialGradient id="iTBnXad" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.05159 -3.79105 0 22.886 16.886)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="j-e7u7b_m"/><stop offset="1" class="ti1dz_avj"/></radialGradient><radialGradient id="ieGruyg" cx="0" cy="0" r="1" gradientTransform="rotate(135.956 9.176 13.098)scale(1.62184 .44544)" gradientUnits="userSpaceOnUse"><stop class="ykffvac5d"/><stop offset="1" class="om3_icb-a"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:toolbox" /></template>
<style>
.anndcmbei {
  d: path("M2.019 13.531a3.5 3.5 0 0 1 3.5-3.5H26.3a3.5 3.5 0 0 1 3.5 3.5v14.344a2 2 0 0 1-2 2H4.02a2 2 0 0 1-2-2z");
}

.b4wj2gklw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.526 23.366h18.926");
}

.bf_jq17la {
  stop-color: var(--svg-color--ff6891, #FF6891);
  stop-opacity: 0;
}

.cqq7uubeq {
  width: 19.945px;
  height: 0.992px;
  x: 5.925px;
  y: 22.977px;
  fill: var(--svg-color--c1aeca, #C1AECA);
  rx: 0.496px;
}

.d8tg2hgog {
  stop-color: var(--svg-color--b14757, #B14757);
}

.e3ys_ccqb {
  fill: var(--svg-color--c4b3d4, #C4B3D4);
  d: path("M20.894 16.75a.75.75 0 0 1 .75-.75h2.484a.75.75 0 0 1 .75.75v1.195a1.992 1.992 0 1 1-3.984 0z");
}

.f38kj415i {
  width: 28.25px;
  height: 0.992px;
  x: 1.785px;
  y: 17.008px;
  fill: var(--svg-color--cb236c, #CB236C);
  rx: 0.4px;
}

.fba-q2bdg {
  stop-color: var(--svg-color--e65f7c, #E65F7C);
  stop-opacity: 0;
}

.fop7ejbxc {
  stop-color: var(--svg-color--ff417d, #FF417D);
}

.fsq2-mbru {
  d: path("M6.925 16.75a.75.75 0 0 1 .75-.75h2.485a.75.75 0 0 1 .75.75v1.195a1.992 1.992 0 0 1-3.985 0z");
}

.ft5dv1b6b {
  fill: none;
}

.gb367kdel {
  stop-color: var(--svg-color--c1adcc, #C1ADCC);
}

.j_m6a2bnf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M29.675 17.406H6.082");
}

.j-7duf5zc {
  width: 19.945px;
  height: 0.992px;
  x: 5.925px;
  y: 25.961px;
  fill: var(--svg-color--c1aeca, #C1AECA);
  rx: 0.496px;
}

.j-e7u7b_m {
  stop-color: var(--svg-color--c5b4d5, #C5B4D5);
  stop-opacity: 0;
}

.j5e9fdc1u {
  width: 28.25px;
  height: 0.992px;
  x: 1.785px;
  y: 17.008px;
  rx: 0.4px;
}

.jggwz76tw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.526 26.352h18.926");
}

.jx_4c3kmr {
  stop-color: var(--svg-color--e65f7c, #E65F7C);
}

.khe1oibhj {
  stop-color: var(--svg-color--7b6c89, #7B6C89);
  stop-opacity: 0;
}

.kjgp_qbtb {
  stop-color: var(--svg-color--5c486e, #5C486E);
}

.krkw-8pps {
  d: path("M20.894 16.75a.75.75 0 0 1 .75-.75h2.484a.75.75 0 0 1 .75.75v1.195a1.992 1.992 0 1 1-3.984 0z");
}

.o8hify2hp {
  stop-color: var(--svg-color--ff6891, #FF6891);
}

.oey99b63q {
  width: 21.664px;
  height: 2.255px;
  x: 6.526px;
  y: 11.893px;
  rx: 1.128px;
}

.oja805bnd {
  stop-color: var(--svg-color--7b6c89, #7B6C89);
}

.om3_icb-a {
  stop-color: var(--svg-color--ded3e3, #DED3E3);
  stop-opacity: 0;
}

.qe2iy-bgs {
  stop-color: var(--svg-color--f2295e, #F2295E);
}

.qjflxubqh {
  stop-color: var(--svg-color--4b3341, #4B3341);
}

.ti1dz_avj {
  stop-color: var(--svg-color--b474b3, #B474B3);
}

.u96bnhnnt {
  fill: var(--svg-color--de2356, #DE2356);
  d: path("M20.324 17.06a.75.75 0 0 1 .75-.75h2.485a.75.75 0 0 1 .75.75v1.195a1.992 1.992 0 0 1-3.985 0z");
}

.w0xmc0xvr {
  fill: var(--svg-color--c4b3d4, #C4B3D4);
  d: path("M6.925 16.75a.75.75 0 0 1 .75-.75h2.485a.75.75 0 0 1 .75.75v1.195a1.992 1.992 0 0 1-3.985 0z");
}

.w5f5h2c8y {
  d: path("M11.035 10.796v-2.53c0-.792.64-1.434 1.428-1.434h7.074c.789 0 1.428.642 1.428 1.435v2.744");
}

.wm8axyb1u {
  stroke-width: var(--svg-stroke-width--2-25px, 2.25px);
  d: path("M11.035 10.962V8.494a1.4 1.4 0 0 1 1.4-1.4h6.934a1.4 1.4 0 0 1 1.4 1.4v2.678");
}

.wn4po7-al {
  stop-color: var(--svg-color--b14757, #B14757);
  stop-opacity: 0;
}

.xl966_bbg {
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
}

.ykffvac5d {
  stop-color: var(--svg-color--ded3e3, #DED3E3);
}

.zkroagb7a {
  stop-color: var(--svg-color--d6c7de, #D6C7DE);
}

</style>
