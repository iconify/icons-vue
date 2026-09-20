<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzwbs2bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:right-panel-open-outline-sharp" /></template>
<style>
.qzwbs2bus {
  fill: currentColor;
  d: path("M11.5 16V8l-4 4zm4.5 3h3V5h-3zM5 19h9V5H5zm11 0h3zM3 21V3h18v18z");
}

</style>
