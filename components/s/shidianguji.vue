<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kuff7bbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shidianguji" /></template>
<style>
.kuff7bbdn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.135 42.5H10.5a5 5 0 0 1-5-5v-27a5 5 0 0 1 5-5h1.635m11.867 0h1.635a5 5 0 0 1 5 5v27a5 5 0 0 1-5 5h-1.635m11.863-37H37.5a5 5 0 0 1 5 5v27a5 5 0 0 1-5 5h-1.635");
}

</style>
