<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykwimr7ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tube" /></template>
<style>
.ykwimr7ks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 2L14 2C14.5523 2 15 2.4477 15 3L15 19C15 20.6569 13.6569 22 12 22C10.3431 22 9 20.6569 9 19L9 3C9 2.4477 9.4477 2 10 2ZM8 2L16 2M9 14L15 14");
}

</style>
