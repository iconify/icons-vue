<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax-d3mttd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-edit-corner-fill" /></template>
<style>
.ax-d3mttd {
  fill: currentColor;
  d: path("M2 6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm5.01 0H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M12 18c0-.265.105-.52.293-.707l5-5a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 16 22h-3a1 1 0 0 1-1-1Zm-3-5a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3Zm-1.99 3H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
