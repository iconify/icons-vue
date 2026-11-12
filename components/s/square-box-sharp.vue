<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbyobpray"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-box-sharp" /></template>
<style>
.pbyobpray {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18v18H3Zm9 4l4.5 2.222v5.556L12 17l-4.5-2.222V9.222zM7.5 9.222l4.5 2.222l4.5-2.222M12 11.444V17");
}

</style>
