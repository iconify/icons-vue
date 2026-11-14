<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ftuj_0fvz"/><path class="ab5kg0bmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:overstock" /></template>
<style>
.ab5kg0bmh {
  d: path("M6.5 18H7a.751.751 0 0 1 .495 1.317l-1.178 1.031A.794.794 0 0 1 5 19.75v-.25A1.5 1.5 0 0 1 6.5 18m11 0H17a.751.751 0 0 0-.495 1.317l1.178 1.031A.794.794 0 0 0 19 19.75v-.25a1.5 1.5 0 0 0-1.5-1.5M8 11h8a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 16 15H8a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 8 11m.5-4h7A1.5 1.5 0 0 1 17 8.5v1a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 9.5v-1A1.5 1.5 0 0 1 8.5 7M9 3h6a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 15 7H9a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 9 3m3 0v1.5");
}

.ftuj_0fvz {
  d: path("M4 15h16a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 20 18H4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 4 15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
