<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k6nj2fbya"/><path class="g54o33why"/><path class="g0fpbbc_s"/><path class="pt0xyi7kd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pii-redact-outline-bold" /></template>
<style>
.g0fpbbc_s {
  d: path("M18 11h3");
}

.g54o33why {
  d: path("M3 11a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.pt0xyi7kd {
  d: path("M3 17h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
