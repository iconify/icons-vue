<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j67d9nbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-move-after-sharp" /></template>
<style>
.j67d9nbvc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 6L20 3L2 3L2 21L20 21L20 18M11 3L11 21M15 12L22 12M18.7071 8.7071L22 12L18.7071 15.2929");
}

</style>
