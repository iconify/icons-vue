<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jp9ecpztv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:selcom-pesa" /></template>
<style>
.jp9ecpztv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 34.5v4c0 2.216 1.784 4 4 4h29c2.216 0 4-1.784 4-4v-21H21a3 3 0 0 0-3 3v.5a3 3 0 0 0 3 3h6a3 3 0 0 1 3 3v.5a3 3 0 0 1-3 3H5.5v-21c0-2.216 1.784-4 4-4h29c2.216 0 4 1.784 4 4v4");
}

</style>
