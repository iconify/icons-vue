<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="giuayy5yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pentagon-20-regular" /></template>
<style>
.giuayy5yj {
  fill: currentColor;
  d: path("M8.392 1.648a2.5 2.5 0 0 1 3.37.01l5.43 4.98a2.5 2.5 0 0 1 .68 2.64l-2.027 6.02a2.5 2.5 0 0 1-2.37 1.701H6.65a2.5 2.5 0 0 1-2.351-1.65l-2.15-5.947A2.5 2.5 0 0 1 2.822 6.7zm2.693.747a1.5 1.5 0 0 0-2.021-.006L3.492 7.44a1.5 1.5 0 0 0-.403 1.62l2.15 5.948a1.5 1.5 0 0 0 1.41.99h6.827a1.5 1.5 0 0 0 1.421-1.02l2.027-6.02a1.5 1.5 0 0 0-.408-1.583z");
}

</style>
