<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j64debr6q"/><path class="k6nj2fbya"/><path class="g54o33why"/><path class="g0fpbbc_s"/><path class="pt0xyi7kd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pii-redact-duotone-thin" /></template>
<style>
.g0fpbbc_s {
  d: path("M18 11h3");
}

.g54o33why {
  d: path("M3 11a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j64debr6q {
  fill: currentColor;
  d: path("M3 11a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.pt0xyi7kd {
  d: path("M3 17h10");
}

</style>
