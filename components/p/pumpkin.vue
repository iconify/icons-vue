<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dqnufji0e"/><path class="nnczenz6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pumpkin" /></template>
<style>
.dqnufji0e {
  d: path("M12 7c1.5-.75 3.5-1 5.25-.25c2.75 1.25 4 4 4 7s-1.5 6-4.5 6.75C15 21 13.5 20.75 12 20c-1.5.75-3 1-4.75.5c-3-.75-4.5-3.5-4.5-6.75s1.25-5.75 4-7C8.5 6 10.5 6.25 12 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nnczenz6t {
  d: path("M12 7V4.75c0-1 .5-1.5 1.5-2m-4.75 4.5C7.25 9.25 7 11.5 7 13.75s.5 4.5 1.75 6m6.5-12.5c1.5 2 1.75 4.25 1.75 6.5s-.5 4.5-1.75 6");
}

</style>
