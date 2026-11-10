<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkn_p6qhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rotate-ccw-square-sharp" /></template>
<style>
.lkn_p6qhd {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.688 1.73L12 4.25L14.716 6.8M12 4.25H20V10M15 22V11H4V22H15Z");
}

</style>
