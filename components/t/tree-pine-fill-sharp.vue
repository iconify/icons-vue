<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul84m5saa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tree-pine-fill-sharp" /></template>
<style>
.ul84m5saa {
  fill: currentColor;
  d: path("m12.625 2.219l5 4A1.002 1.002 0 0 1 17 8h-.586l3.293 3.293A1 1 0 0 1 19 13h-1.586l4.293 4.293A1 1 0 0 1 21 19h-8v2a1 1 0 0 1-2 0v-2H3a1.002 1.002 0 0 1-.707-1.707L6.586 13H5a1.002 1.002 0 0 1-.707-1.707L7.586 8H7a1 1 0 0 1-.625-1.781l5-4a1 1 0 0 1 1.25 0");
}

</style>
