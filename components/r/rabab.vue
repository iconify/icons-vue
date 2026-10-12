<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7135w2yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rabab" /></template>
<style>
.g7135w2yw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75V10M9.5 4H12m0 1.5h2.5M9.5 7H12m-2.75 3h5.5a.75.75 0 0 1 .75.75v.5c0 .6-.4 1.1-.95 1.35a4.45 4.45 0 1 1-5.1 0c-.55-.25-.95-.75-.95-1.35v-.5a.75.75 0 0 1 .75-.75m0 6.5h5.5m-2.75 0V19");
}

</style>
