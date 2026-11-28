<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt7p3cc_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mouse-lock" /></template>
<style>
.pt7p3cc_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 18.3178C6.3682 17.3675 6 16.2267 6 15L6 9C6 5.6863 8.6863 3 12 3C14.973 3 17.441 5.1623 17.917 8M12 7L12 8M12 16L17 16C17.5523 16 18 16.4477 18 17L18 20C18 20.5523 17.5523 21 17 21L12 21C11.4477 21 11 20.5523 11 20L11 17C11 16.4477 11.4477 16 12 16ZM12.5 16L12.5 14C12.5 12.8954 13.3954 12 14.5 12C15.6046 12 16.5 12.8954 16.5 14L16.5 16");
}

</style>
