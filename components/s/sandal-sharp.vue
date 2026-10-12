<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq8woqlbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sandal-sharp" /></template>
<style>
.aq8woqlbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c3.5 0 5 2.5 5 6c0 3-1 4.5-1 7.5S14.5 21 12 21s-4-1.75-4-4.75s-1-4.5-1-7.5c0-3.5 1.5-6 5-6Zm0 2.75V8m0 0l-3.25 4.25M12 8l3.25 4.25");
}

</style>
