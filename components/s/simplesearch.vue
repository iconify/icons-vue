<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ka5uxvbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simplesearch" /></template>
<style>
.ka5uxvbwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.54 9.53a13.77 13.77 0 0 1 19.46 0a13.77 13.77 0 0 1 .74 18.67l.52.51H32l10.5 10.5l-3.28 3.29L28.72 32v-1.73l-.52-.52A13.77 13.77 0 0 1 9.53 9.54Zm3.05 3.06a9.45 9.45 0 1 0 13.37 0a9.46 9.46 0 0 0-13.37 0m17.16 15.62l-1.55 1.54");
}

</style>
