<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ojkae0bje"/><path class="cgw4zmbur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tea-leaves" /></template>
<style>
.cgw4zmbur {
  d: path("M12 13q4-5.12 0-10.25Q8 7.88 12 13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ojkae0bje {
  d: path("M12 21.25V14m0 1q-1.31-7.89-9.25-7q1.31 7.89 9.25 7m0 0q7.94.89 9.25-7q-7.94-.89-9.25 7m-1.5-1.25L6 10.5m7.5 3.25L18 10.5");
}

</style>
