<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_bfuvq9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:type" /></template>
<style>
.l_bfuvq9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 6L4 5C4 3.8954 4.8954 3 6 3L18 3C19.1046 3 20 3.8954 20 5L20 6M12 3L12 21M8 21L16 21");
}

</style>
