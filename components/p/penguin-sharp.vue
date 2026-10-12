<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="o0ik-ex9d"/><path class="t8zye1bbu"/><path class="tw_ibeb9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:penguin-sharp" /></template>
<style>
.o0ik-ex9d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c3.5 0 5.5 3 5.5 6.75v4c0 4.25-2.25 7.75-5.5 7.75s-5.5-3.5-5.5-7.75v-4c0-3.75 2-6.75 5.5-6.75ZM6.5 11.5l-2.75 3.75M17.5 11.5l2.75 3.75");
}

.t8zye1bbu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11.75c1.6 0 2.75 1.4 2.75 3.25c0 2.25-1.15 3.5-2.75 3.5S9.25 17.25 9.25 15c0-1.85 1.15-3.25 2.75-3.25Zm-.75-4h1.5l-.75 1Z");
}

.tw_ibeb9a {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 5.75h.01m4.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
