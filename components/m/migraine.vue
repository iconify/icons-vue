<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ocyf5ip6z"/><path class="mqkg_y10m"/><path class="txlyv1b_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:migraine" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mqkg_y10m {
  fill: currentColor;
  d: path("m13.902 5.914l-1.938 3.7a.605.605 0 0 0 .536.886a.76.76 0 0 1 .732.964l-.357 1.286a.407.407 0 0 0 .725.344l2.25-3.176A.582.582 0 0 0 15.375 9a.762.762 0 0 1-.707-1.045l.803-2.009A.508.508 0 0 0 15 5.25a1.24 1.24 0 0 0-1.098.664");
}

.ocyf5ip6z {
  d: path("M8 21.5v-4c-2.5-1.75-3.5-4.25-3.5-7C4.5 6.25 7.75 3 12 3c4 0 7 2.75 7 6.75l1.5 3.5c.25.5-.1 1-.75 1H19v2.25c0 1.1-.9 2-2 2h-2v3");
}

.txlyv1b_n {
  d: path("M7.75 10C9 9.75 9.5 11.75 8 12.25m9.25-2.5h.01");
}

</style>
