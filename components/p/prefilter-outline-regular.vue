<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m6o3bac1v"/><path class="o062g1b0a"/><path class="o0ozwgb-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:prefilter-outline-regular" /></template>
<style>
.m6o3bac1v {
  d: path("M3 3h18l-7 7v5h-4v-5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o062g1b0a {
  d: path("M12.5 17.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.o0ozwgb-f {
  d: path("m18 20 2 2");
}

</style>
