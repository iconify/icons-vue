<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g21x4li4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tree-palm" /></template>
<style>
.g21x4li4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8C9.875 4.211 4.241 4.837 3 9Zm9 1c-1.241-4.163-6.875-4.789-9-1Zm-9-1a7.52 7.52 0 0 0-7 8Zm7 8a7.52 7.52 0 0 0-7-8Zm-7 5V8");
}

</style>
