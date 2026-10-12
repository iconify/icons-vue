<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jkg3fab5e"/><path class="obsnj8b-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:secure-file" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkg3fab5e {
  d: path("M6 2.75h7.25L18.5 8v11.25a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V4.75a2 2 0 0 1 2-2");
}

.obsnj8b-f {
  d: path("M13 2.75V6.5A1.5 1.5 0 0 0 14.5 8h4m-11 4h4m-4 3h3m7.42-2.12l2.41.99q.92.38.92 1.38v1.06q0 1-.73 1.68l-2.79 2.58q-.73.68-1.46 0l-2.79-2.58q-.73-.68-.73-1.68v-1.06q0-1 .92-1.38l2.41-.99q.92-.38 1.84 0");
}

</style>
