<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7f_un4xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mouse-lock-sharp-two-tone" /></template>
<style>
.g7f_un4xr {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.2 18.6C6.4211 17.5614 6 16.2982 6 15L6 9C6 5.6863 8.6863 3 12 3C15.3137 3 18 5.6863 18 9M12 6L12 9M11 16L18 16L18 21L11 21ZM12.5 16L12.5 14C12.5 12.8954 13.3954 12 14.5 12C15.6046 12 16.5 12.8954 16.5 14L16.5 16");
}

</style>
