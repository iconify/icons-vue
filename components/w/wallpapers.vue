<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dla9fvb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wallpapers" /></template>
<style>
.dla9fvb3c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33 5.5H15a2 2 0 0 0-2 2v33a2 2 0 0 0 2 2h18a2 2 0 0 0 2-2v-33a2 2 0 0 0-2-2m-20 34H8c-1.1 0-2-.9-2-2v-27c0-1.1.9-2 2-2h5m22 0h6c1.1 0 2 .9 2 2v27c0 1.1-.9 2-2 2h-6");
}

</style>
