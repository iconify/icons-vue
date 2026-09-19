<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ujh7qlb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:periodic-table-alt" /></template>
<style>
.ujh7qlb-p {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M4.5 9v21h3v-6h3v6h33V9h-3v3h-10v6h-20v-6h-3V9zm6 24v6h27v-6z");
}

</style>
