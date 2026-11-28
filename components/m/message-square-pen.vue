<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h73tcebcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-pen" /></template>
<style>
.h73tcebcu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3L6 3C4.3431 3 3 4.3431 3 6L3 21L7 17L18 17C19.6569 17 21 15.6569 21 14L21 12M11 13L15.1248 11.3501L20.4874 5.9874C21.1709 5.304 21.1709 4.196 20.4874 3.5126C19.804 2.8291 18.696 2.8291 18.0126 3.5126L12.6499 8.8752Z");
}

</style>
