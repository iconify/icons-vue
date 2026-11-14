<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca1q3xpfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plasters-box" /></template>
<style>
.ca1q3xpfa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.172 3.515l11.313 11.313a2 2 0 0 1 0 2.829l-2.828 2.828a2 2 0 0 1-2.829 0L3.515 9.172a2 2 0 0 1 0-2.829l2.828-2.828a2 2 0 0 1 2.829 0Zm3.535 3.535L7.05 12.707m9.9-1.414l-5.657 5.657M12 12h.01");
}

</style>
