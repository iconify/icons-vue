<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fhvjqwado"/><path class="j3myukbcg"/><path class="gl3dr304z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:slippery-floor" /></template>
<style>
.fhvjqwado {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.98 4.99l7.29 13.02q.98 1.74-1.02 1.74H4.75q-2 0-1.02-1.74l7.29-13.02q.98-1.74 1.96 0");
}

.gl3dr304z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.25 10.75l-1.5 2.5l3.75-1m-2.75-.67L9.25 11M7.5 16.75c1.5 0 1.5-.75 3-.75s1.5.75 3 .75s1.5-.75 3-.75");
}

.j3myukbcg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.75 9h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
