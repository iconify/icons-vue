<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlftzkbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-chart-outline-sharp" /></template>
<style>
.jlftzkbos {
  fill: currentColor;
  d: path("M3 21V3h18v18zM5 8h14V5H5zm0 11h2.5v-9H5zm11.5 0H19v-9h-2.5zm-7 0h5v-9h-5z");
}

</style>
