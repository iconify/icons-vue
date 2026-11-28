<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr2zicbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:type-variable" /></template>
<style>
.nr2zicbcp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 6L6 5C6 3.8954 6.8954 3 8 3L16 3C17.1046 3 18 3.8954 18 5L18 6M12 3L12 11M9 11L15 11M3 18L13 18M21 18L17 18M17 15L17 21");
}

</style>
