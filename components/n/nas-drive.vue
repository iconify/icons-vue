<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czon9gb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nas-drive" /></template>
<style>
.czon9gb1l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.5h10A3.5 3.5 0 0 1 20.5 6v1a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 7V6A3.5 3.5 0 0 1 7 2.5m0 10.75h10a3.5 3.5 0 0 1 3.5 3.5v1a3.5 3.5 0 0 1-3.5 3.5H7a3.5 3.5 0 0 1-3.5-3.5v-1a3.5 3.5 0 0 1 3.5-3.5m.5-6.75h.01M7.5 17.25h.01M12.5 6.5h4m-4 10.75h4");
}

</style>
