<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="r8klnybcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:omega-28-regular" /></template>
<style>
.r8klnybcu {
  fill: currentColor;
  d: path("M14 2c6.627 0 12 5.373 12 12c0 3.006-1.402 5.555-2.89 7.42a19.7 19.7 0 0 1-3.105 3.08h5.245a.75.75 0 0 1 0 1.5h-6.016c-.64 0-1.168-.487-1.231-1.111l-.007-.126l.01-.153c.042-.349.229-.662.514-.867c.53-.38 2.044-1.537 3.418-3.259C23.315 18.758 24.5 16.533 24.5 14c0-5.799-4.701-10.5-10.5-10.5S3.5 8.201 3.5 14c0 2.533 1.185 4.759 2.563 6.484a18 18 0 0 0 3.416 3.26c.327.233.525.61.525 1.019c0 .683-.555 1.237-1.238 1.237H2.75a.75.75 0 0 1 0-1.5h5.245a19.7 19.7 0 0 1-3.104-3.08C3.4 19.555 2 17.006 2 14C2 7.373 7.373 2 14 2");
}

</style>
