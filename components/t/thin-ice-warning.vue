<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="al7vc_bxn"/><path class="w58075boy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:thin-ice-warning" /></template>
<style>
.al7vc_bxn {
  d: path("M15.226 16H4.833q-.102 0-.202-.012q-.101-.011-.2-.035q-.099-.023-.194-.058q-.096-.034-.187-.08q-.09-.045-.175-.101q-.085-.055-.163-.12t-.148-.139t-.131-.155t-.112-.169t-.092-.181t-.07-.19t-.048-.197t-.024-.201t-.002-.203q.006-.101.023-.201q.017-.101.045-.198l2.48-8.5q.039-.135.1-.263q.061-.127.141-.243t.178-.218t.211-.186t.238-.15t.259-.11t.273-.067t.28-.023h11.854q.102 0 .202.012q.101.011.2.035q.099.023.194.058q.096.034.187.08q.09.045.175.101q.085.055.163.12t.148.139t.131.155t.112.169t.092.181q.04.093.07.19t.048.197t.024.201q.007.102.002.203q-.006.101-.023.201q-.017.101-.045.198l-1.657 5.679");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w58075boy {
  d: path("m12 4l-1.5 4l3 3l-2 5m6.5-1.5V18m0 3h.01");
}

</style>
