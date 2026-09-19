<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lpwl6gboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:osmand" /></template>
<style>
.lpwl6gboa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.66 3.2c-6.1 1.61-12.34 8.13-13.77 14.28A19.64 19.64 0 0 0 19 41.13a3 3 0 0 1 1.4.87l3.24 3.41a.5.5 0 0 0 .7 0h0L27.59 42a3 3 0 0 1 1.41-.86A19.66 19.66 0 0 0 18.66 3.2M24 33.88a11.7 11.7 0 1 1 .06 0Z");
}

</style>
