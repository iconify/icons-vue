<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbol6-bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:workflow" /></template>
<style>
.dbol6-bfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6C3 4.8954 3.8954 4 5 4L9 4C10.1046 4 11 4.8954 11 6L11 8C11 9.1046 10.1046 10 9 10L5 10C3.8954 10 3 9.1046 3 8L3 6ZM13 16C13 14.8954 13.8954 14 15 14L19 14C20.1046 14 21 14.8954 21 16L21 18C21 19.1046 20.1046 20 19 20L15 20C13.8954 20 13 19.1046 13 18L13 16ZM7 10L7 14C7 15.6569 8.3431 17 10 17L13 17");
}

</style>
