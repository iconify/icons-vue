<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_p5ezbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mountain-range" /></template>
<style>
.i_p5ezbmk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.15 19.33l3.45-7.91q.4-.92.94-.08l1.52 2.42q.54.84.88-.1l2.97-8.22q.34-.94.76-.03l2.91 6.18q.42.91 1.29.41h.01q.87-.5 1.14.46l1.96 6.83q.27.96-.73.96H3.75q-1 0-.6-.92M9.6 14.6l3.6 5.65");
}

</style>
