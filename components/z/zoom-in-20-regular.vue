<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dlryi3mjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:zoom-in-20-regular" /></template>
<style>
.dlryi3mjj {
  fill: currentColor;
  d: path("M8.5 5.5A.5.5 0 0 1 9 6v2h2a.5.5 0 0 1 0 1H9v2a.5.5 0 0 1-1 0V9H6a.5.5 0 0 1 0-1h2V6a.5.5 0 0 1 .5-.5m0-3.5a6.5 6.5 0 0 1 4.937 10.73l3.417 3.416a.5.5 0 0 1-.638.765l-.07-.058l-3.417-3.417A6.5 6.5 0 1 1 8.5 2m0 1a5.5 5.5 0 1 0 0 11a5.5 5.5 0 0 0 0-11");
}

</style>
