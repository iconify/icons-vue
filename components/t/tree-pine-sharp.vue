<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9pogjbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tree-pine-sharp" /></template>
<style>
.q9pogjbsx {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18H19L14 13H18L14 8H17L12 2L7 8H10L6 13H10L5 18H12ZM12 18V23");
}

</style>
