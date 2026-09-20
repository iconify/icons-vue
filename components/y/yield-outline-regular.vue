<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku3-8yb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:yield-outline-regular" /></template>
<style>
.ku3-8yb7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21V3m0 4L7 2m5 5 5 -5m-5 9L7 6m5 5 5 -5m-5 9 -5 -5m5 5 5 -5");
}

</style>
