<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfl_lb8us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-girl" /></template>
<style>
.pfl_lb8us {
  fill: currentColor;
  d: path("M12 7.5c.97 0 1.75-.78 1.75-1.75S12.97 4 12 4s-1.75.78-1.75 1.75S11.03 7.5 12 7.5m2 8.5v4h-4v-4H8l2.38-6.38a1.733 1.733 0 0 1 3.24 0L16 16z");
}

</style>
