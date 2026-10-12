<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="agjyaybtv"/><path class="hw0hnpbei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:peak-snow" /></template>
<style>
.agjyaybtv {
  d: path("m12.6 4.59l8.05 14.57q.6 1.09-.65 1.09H4q-1.25 0-.65-1.09L11.4 4.59q.6-1.09 1.2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hw0hnpbei {
  d: path("m12.36 4.16l3.18 5.78q.36.66-.21 1.15l-.51.42q-.57.49-1.16.03l-1.07-.83q-.59-.46-1.18 0l-1.07.83q-.59.46-1.16-.03l-.51-.42q-.57-.49-.21-1.15l3.18-5.78q.36-.66.72 0");
}

</style>
