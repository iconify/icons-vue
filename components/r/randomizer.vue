<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="a5yn8zuyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:randomizer" /></template>
<style>
.a5yn8zuyb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.852 13.644a4.213 4.213 0 1 1-8.426 0a4.213 4.213 0 0 1 8.426 0m12.296 20.712a4.213 4.213 0 0 1 4.213-4.213h0a4.213 4.213 0 1 1-4.213 4.213M19.787 24A4.213 4.213 0 0 1 24 19.787h0A4.213 4.213 0 0 1 28.213 24h0A4.213 4.213 0 0 1 24 28.213h0A4.213 4.213 0 0 1 19.787 24");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

</style>
