<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-u8imbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-2-dot" /></template>
<style>
.y-u8imbsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3L5 3C3.3431 3 2 4.3431 2 6L2 14C2 15.6569 3.3431 17 5 17L19 17C20.6569 17 22 15.6569 22 14L22 13M12 17L12 21M8 21L16 21M22 6C22 7.6569 20.6569 9 19 9C17.3431 9 16 7.6569 16 6C16 4.3431 17.3431 3 19 3C20.6569 3 22 4.3431 22 6Z");
}

</style>
