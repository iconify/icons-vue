<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jgzo8i0ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:waterminder" /></template>
<style>
.jgzo8i0ql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.49 29.01C38.49 18.36 24 4.5 24 4.5S9.51 18.36 9.51 29.01c0 8.003 6.488 14.49 14.49 14.49s14.49-6.487 14.49-14.49");
}

</style>
