<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="okud9xj_d"/><path class="eq1nrcbpl"/><path class="w2atjyb_m"/><path class="ey3upmocl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:organ-donor-outline-regular" /></template>
<style>
.eq1nrcbpl {
  d: path("M4 11a2 2 0 0 1 4 0 2 2 0 0 1 4 0l-4 4Z");
}

.ey3upmocl {
  d: path("M14 14h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.okud9xj_d {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.w2atjyb_m {
  d: path("M14 10h6");
}

</style>
