<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z2lk721tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:setup-and-transfer" /></template>
<style>
.z2lk721tn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.692 22.488l3.942 3.916l8.67-8.614m-7.699 23.215h2.79m-4.31-34.634h5.825M13.065 38.594h21.87M13.069 8.408H34.93M18.425 4.5h11.15c2.971 0 5.36 1.78 5.36 3.992v31.017c0 2.21-2.389 3.991-5.36 3.991h-11.15c-2.971 0-5.36-1.776-5.36-3.991V8.492c0-2.212 2.389-3.992 5.36-3.992");
}

</style>
