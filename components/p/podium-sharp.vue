<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr4a1nbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:podium-sharp" /></template>
<style>
.tr4a1nbdn {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1 17.25L23 17.25M4 17.25L4 13.75L9 13.75L9 10.25L14 10.25L14 6.75L20 6.75L20 17.25L4 17.25Z");
}

</style>
