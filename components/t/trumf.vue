<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y4osi0ynf"/><path class="d92wl78-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trumf" /></template>
<style>
.d92wl78-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.632 14.268v16.52a2.945 2.945 0 0 0 2.945 2.944h.883m-6.92-15.606h6.184");
}

.y4osi0ynf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.997 5.513c-10.218 0-18.5 8.282-18.5 18.5v18.5h18.5c10.217 0 18.5-8.283 18.5-18.5s-8.283-18.5-18.5-18.5");
}

</style>
