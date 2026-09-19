<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="muy2bmusi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vibulkij" /></template>
<style>
.muy2bmusi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.249 23.569v17.52H13.944V23.866m0-12.892V6.91H34.25v4.063m8.251 0H30.615L24 21.072l-6.615-10.097H5.5L24 39.22z");
}

</style>
