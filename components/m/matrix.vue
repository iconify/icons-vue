<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j0_a6jo9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:matrix" /></template>
<style>
.j0_a6jo9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 8.5h-8v31h8m23 0h8v-31h-8m-23 13.631a5.75 5.75 0 0 1 11.5 0v9.488M12.5 16.381v15.238M24 22.131a5.75 5.75 0 0 1 11.5 0v9.488");
}

</style>
