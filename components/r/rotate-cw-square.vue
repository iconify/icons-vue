<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd1_55bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rotate-cw-square" /></template>
<style>
.gd1_55bdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.6 2L12 4.25L9.6 6.5M12 4.25H5.6C4.7164 4.25 4 4.92 4 5.75V9M9 20V13C9 11.9 9.8954 11 11 11H18C19.1046 11 20 11.9 20 13V20C20 21.1 19.1046 22 18 22H11C9.8954 22 9 21.1 9 20Z");
}

</style>
