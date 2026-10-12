<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zaq7qe48h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pine-tree" /></template>
<style>
.zaq7qe48h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.55 3.46l3.4 4.33q.55.71-.32.71q-.88 0-.34.72l2.67 3.56q.54.72-.36.72h-.45q-.9 0-.34.7l2.88 3.6q.56.7-.34.7H4.65q-.9 0-.34-.7l2.88-3.6q.56-.7-.34-.7H6.4q-.9 0-.36-.72l2.67-3.56q.54-.72-.33-.72q-.88 0-.33-.71l3.4-4.33q.55-.71 1.1 0M12 18.5v2.75");
}

</style>
