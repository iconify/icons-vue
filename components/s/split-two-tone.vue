<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcvf0jbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:split-two-tone" /></template>
<style>
.tcvf0jbnz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21L12 16C12 14.3431 10.6569 13 9 13C7.3431 13 6 11.6569 6 10L6 3M12 16C12 14.3431 13.3431 13 15 13C16.6569 13 18 11.6569 18 10L18 3M3 6L6 3L9 6M15 6L18 3L21 6");
}

</style>
