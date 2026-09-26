<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6ktl0qlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-sharp" /></template>
<style>
.k6ktl0qlu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 11C19 15.4184 15.4184 19 11 19C6.5816 19 3 15.4184 3 11C3 6.5816 6.5816 3 11 3C15.4184 3 19 6.5816 19 11ZM16.6569 16.6569L21.2929 21.2929");
}

</style>
