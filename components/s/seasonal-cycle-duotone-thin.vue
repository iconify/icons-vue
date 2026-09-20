<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qlh7h_mau"/><path class="iomp1sbmd"/><path class="h06k0cc0f"/><path class="oh3qc3kah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:seasonal-cycle-duotone-thin" /></template>
<style>
.h06k0cc0f {
  d: path("M3 12a4 4 0 0 1 8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iomp1sbmd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 12a4 4 0 0 1 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oh3qc3kah {
  d: path("M19 12a4 4 0 0 1 -8 0");
}

.qlh7h_mau {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
