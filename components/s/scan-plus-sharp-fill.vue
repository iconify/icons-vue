<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy_evw8uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-plus-sharp-fill" /></template>
<style>
.vy_evw8uh {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9L3 3L9 3M15 3L21 3L21 9M9 21L3 21L3 15M18 14L18 22M14 18L22 18");
}

</style>
