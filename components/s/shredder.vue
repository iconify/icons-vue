<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi_nftbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shredder" /></template>
<style>
.wi_nftbha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 12L4 6C4 3.7909 5.7909 2 8 2L14 2L20 8L20 12M14 2L14 5C14 6.6569 15.3431 8 17 8L20 8M2 12L22 12M6 16L6 22M10 16L10 20M14 16L14 22M18 16L18 20");
}

</style>
