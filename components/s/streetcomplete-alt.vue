<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rxopnvbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:streetcomplete-alt" /></template>
<style>
.rxopnvbba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.86 7.788H10.83L6.5 12.184l4.33 4.395h18.03ZM15.893 19.581H37.17l4.33 4.41l-4.33 4.41H15.893ZM24.001 4.5l.003 3.288m-.007 8.791v3.002M23.996 43.5l.001-15.098");
}

</style>
