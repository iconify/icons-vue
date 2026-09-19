<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xkzwiobig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shareme" /></template>
<style>
.xkzwiobig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.4 17.33a9.43 9.43 0 1 1 6.67 16.1c-5.21 0-7.42-4.95-10.07-9.43c-2.83-4.78-4.86-9.43-10.07-9.43a9.43 9.43 0 1 0 6.6 16.16");
}

</style>
