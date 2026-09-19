<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i8fZI1c)"><circle fill="url(#i5tEo3c)" class="m94-_1bwh"/><circle fill="url(#iPb0Yql)" class="m94-_1bwh"/><circle fill="url(#iBKkxlc)" class="m94-_1bwh"/></g><circle fill="url(#iOY8OOc)" class="gdsnxpbwe"/><g filter="url(#ia2xFdb)"><path fill="url(#iYzFoVc)" clip-rule="evenodd" class="h_4b95bof"/></g><g filter="url(#imtQtmd)"><path clip-rule="evenodd" class="ouhonbcph"/></g><g filter="url(#ia2xFdb)"><path fill="url(#iBZ7Orb)" clip-rule="evenodd" class="h_4b95bof"/></g><defs><filter id="i8fZI1c" width="28.5" height="28" x="2" y="2.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.266667 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3371"/></filter><filter id="ia2xFdb" width="5.3" height="8.362" x="13.35" y="11.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0980392 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3371"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.298039 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3371" result="effect2_innerShadow_18_3371"/></filter><filter id="imtQtmd" width="5.5" height="8.498" x="13.031" y="11.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3371" stdDeviation=".125"/></filter><radialGradient id="iPb0Yql" cx="0" cy="0" r="1" gradientTransform="rotate(90 2.672 13.328)scale(19.375)" gradientUnits="userSpaceOnUse"><stop offset=".697" class="zp08yr_rh"/><stop offset="1" class="k2-wkr5lz"/></radialGradient><radialGradient id="iBKkxlc" cx="0" cy="0" r="1" gradientTransform="matrix(7.19617 -6.08899 5.58507 6.60062 19.165 13.516)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="zcwc-cbli"/><stop offset=".931" class="p82-_kq_i"/></radialGradient><radialGradient id="iOY8OOc" cx="0" cy="0" r="1" gradientTransform="rotate(122.836 6.186 11.333)scale(12.7942 14.7118)" gradientUnits="userSpaceOnUse"><stop offset=".119" class="nqpl1bcpq"/><stop offset=".967" class="zo-9mjbxj"/></radialGradient><linearGradient id="i5tEo3c" x1="14.183" x2="24.046" y1="24.536" y2="4.709" gradientUnits="userSpaceOnUse"><stop class="ycttvpyhm"/><stop offset="1" class="r-43eebbp"/></linearGradient><linearGradient id="iYzFoVc" x1="18.5" x2="15" y1="13.031" y2="19.406" gradientUnits="userSpaceOnUse"><stop class="herb3ytbu"/><stop offset="1" class="hzgrc4bmp"/></linearGradient><linearGradient id="iBZ7Orb" x1="18.5" x2="15" y1="13.031" y2="19.406" gradientUnits="userSpaceOnUse"><stop class="herb3ytbu"/><stop offset=".902" class="hzgrc4bmp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pool-8-ball" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gdsnxpbwe {
  cx: 16px;
  cy: 16.031px;
  r: 7px;
}

.h_4b95bof {
  fill-rule: evenodd;
  d: path("M13.824 12.99c.37-.603 1.067-1.02 2.176-1.02c1.084 0 1.79.364 2.17.955c.331.514.33 1.145.33 1.558v.048c0 .523-.189 1.045-.637 1.43a.072.072 0 0 0 0 .109q.18.156.307.355c.331.514.33 1.145.33 1.558v.048c0 .523-.189 1.045-.637 1.43c-.44.376-1.07.57-1.863.57c-.82 0-1.457-.19-1.893-.575c-.445-.392-.607-.919-.607-1.425v-.034c0-.355-.001-.978.324-1.507q.12-.195.287-.355a.12.12 0 0 0-.004-.179c-.445-.392-.607-.919-.607-1.425v-.034c0-.355-.001-.978.324-1.507m3.508 1.29c0 .691-.504 1.168-1.332 1.168s-1.3-.477-1.3-1.167s.472-1.195 1.3-1.195s1.332.505 1.332 1.195m0 3.5c0 .691-.504 1.192-1.332 1.192s-1.3-.5-1.3-1.191c0-.69.472-1.205 1.3-1.205s1.332.514 1.332 1.205");
}

.herb3ytbu {
  stop-color: var(--svg-color--46315b, #46315B);
}

.hzgrc4bmp {
  stop-color: var(--svg-color--2b193c, #2B193C);
}

.k2-wkr5lz {
  stop-color: var(--svg-color--492b65, #492B65);
}

.m94-_1bwh {
  cx: 16px;
  cy: 16.031px;
  r: 14px;
}

.nqpl1bcpq {
  stop-color: var(--svg-color--d6d0dd, #D6D0DD);
}

.ouhonbcph {
  fill: var(--svg-color--756386, #756386);
  fill-rule: evenodd;
  d: path("M13.605 13.201c.37-.598 1.066-1.013 2.176-1.013c1.084 0 1.79.363 2.17.949c.331.51.33 1.135.33 1.546v.047c0 .519-.189 1.037-.637 1.418a.072.072 0 0 0 0 .109q.18.154.307.352c.331.51.33 1.136.33 1.546v.047c0 .519-.189 1.037-.637 1.418c-.44.374-1.07.566-1.863.566c-.82 0-1.457-.189-1.893-.57c-.446-.389-.607-.912-.607-1.414v-.034c0-.352-.001-.97.324-1.494q.12-.194.286-.353a.12.12 0 0 0-.003-.177c-.446-.39-.607-.912-.607-1.414v-.034c0-.352-.001-.97.324-1.495m3.508 1.28c0 .686-.504 1.159-1.332 1.159s-1.3-.473-1.3-1.158s.471-1.186 1.3-1.186c.828 0 1.332.5 1.332 1.186m0 3.473c0 .685-.504 1.182-1.332 1.182s-1.3-.497-1.3-1.182s.471-1.195 1.3-1.195c.828 0 1.332.51 1.332 1.195");
}

.p82-_kq_i {
  stop-color: var(--svg-color--625c6b, #625C6B);
  stop-opacity: 0;
}

.r-43eebbp {
  stop-color: var(--svg-color--362c41, #362C41);
}

.ycttvpyhm {
  stop-color: var(--svg-color--2b2435, #2B2435);
}

.zcwc-cbli {
  stop-color: var(--svg-color--625c6b, #625C6B);
}

.zo-9mjbxj {
  stop-color: var(--svg-color--a593b9, #A593B9);
}

.zp08yr_rh {
  stop-color: var(--svg-color--492b65, #492B65);
  stop-opacity: 0;
}

</style>
