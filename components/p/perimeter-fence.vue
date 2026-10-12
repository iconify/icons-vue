<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg9trs9rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:perimeter-fence" /></template>
<style>
.bg9trs9rh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 21.25V8.75l2.5-3.5m5.25 16V8.75l2.5-3.5m5.25 16V8.75l2.5-3.5m-18 7.5h15.5M3.25 17h15.5m-13-11.75h15.5");
}

</style>
