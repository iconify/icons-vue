<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="qs1wvvble"/><path class="t2vi0ol3b"/><path class="l177unbjo"/><circle class="qa1vi5bxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seal-marine" /></template>
<style>
.l177unbjo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 15.5q.75 2.25 3 3");
}

.qa1vi5bxv {
  cx: 17.75px;
  cy: 4.75px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qs1wvvble {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 21.25c-1.5 0-2.5-1-2.5-2.25c0-4 2.5-6 4.75-8.5C9.5 9 9.75 7.5 11 6.75s3 0 3.5 1.25l2 .5l-1.75 1.25c-.75 1.5-2 2.75-2.5 4.5c-.5 2.5 0 4.75 1.5 7Z");
}

.t2vi0ol3b {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.25 8.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
