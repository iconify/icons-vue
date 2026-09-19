<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vgx390b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:winbank" /></template>
<style>
.vgx390b9p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.896 36.026L4.5 11.974h7.303l8.185 24.083Zm8.092.031l4.137-12.228l-3.857-11.855l-4.105 12.197m4.105-12.197l7.557-.031l8.248 24.083h-7.744l-4.204-12.197m11.948 12.197L43.5 11.943h-7.24l-4.105 12.01");
}

</style>
