<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e-9b8vbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:thehindu" /></template>
<style>
.e-9b8vbhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4m-29.297-27h11.263m-5.631 17v-17m11.637 0v17m11.262-17v17m-11.262-8.532h11.262M13.772 32.5h2.125m9.512 0h2.125m9.138 0h2.125m-13.388-17h2.125m9.138 0h2.125m-18.331 0v1.063M9.203 15.5v1.063");
}

</style>
