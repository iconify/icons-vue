<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y8j09ueov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sound-assistant" /></template>
<style>
.y8j09ueov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.321 10.786a5.286 5.286 0 1 1-10.571 0a5.286 5.286 0 0 1 10.571 0M37.214 24a5.286 5.286 0 1 1-10.571 0a5.286 5.286 0 0 1 10.571 0m-7.928 13.214a5.286 5.286 0 1 1-10.572 0a5.286 5.286 0 0 1 10.572 0m0 0h12.553m-35.678 0h12.553M37.214 24h4.625M6.161 24h20.482m-1.322-13.214h16.518m-35.678 0h8.589");
}

</style>
