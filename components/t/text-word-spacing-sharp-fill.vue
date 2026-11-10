<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu648obmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-word-spacing-sharp-fill" /></template>
<style>
.iu648obmy {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 3H22M15 9H22M2 15H9M2 21H13M2 3H13M2 9H6M8 9H13M11 15H22");
}

</style>
