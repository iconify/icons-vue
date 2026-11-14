<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hxwyanh8t"/><path class="z9gvyp8il"/><path class="b_le361vp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reorganization" /></template>
<style>
.b_le361vp {
  d: path("M5.25 6.25L7 4.5l1.75 1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxwyanh8t {
  d: path("M11.25 2.5h1.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 9.5 4.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-7 14h1.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-1.5a1.75 1.75 0 0 1-1.75-1.75v-.5a1.75 1.75 0 0 1 1.75-1.75m14 0h1.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-1.5a1.75 1.75 0 0 1-1.75-1.75v-.5a1.75 1.75 0 0 1 1.75-1.75M17 4.5c2 1 2.75 5 2 9");
}

.z9gvyp8il {
  d: path("M17.25 11.75L19 13.5l1.75-1.75M14 18.5h-4m1.75-1.75L10 18.5l1.75 1.75M5 13.5c-.75-4 0-8 2-9");
}

</style>
