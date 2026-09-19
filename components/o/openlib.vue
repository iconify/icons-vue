<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iqz1plbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openlib" /></template>
<style>
.iqz1plbld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.4 5v14.25l3.2-4.222l3.2 4.222V5M12 43h24a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4H12a4 4 0 0 0-4 4v30a4 4 0 0 0 4 4");
}

</style>
