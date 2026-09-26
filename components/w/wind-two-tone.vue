<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm33t25yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wind-two-tone" /></template>
<style>
.wm33t25yo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 6L12 6C13.1046 6 14 5.1046 14 4C14 2.8954 13.1046 2 12 2C11.4696 2 10.9609 2.2107 10.5858 2.5858M6 12L20 12C21.1046 12 22 11.1046 22 10C22 8.8954 21.1046 8 20 8C19.4696 8 18.9609 8.2107 18.5858 8.5858M2 18L15 18C16.1046 18 17 18.8954 17 20C17 21.1046 16.1046 22 15 22C14.4696 22 13.9609 21.7893 13.5858 21.4142");
}

</style>
