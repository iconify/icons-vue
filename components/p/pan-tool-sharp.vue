<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax_5wmfhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pan-tool-sharp" /></template>
<style>
.ax_5wmfhj {
  fill: currentColor;
  d: path("M8.475 23L1.2 12.375l1.725-1.65L7 13.575V3h2v9h2V1h2v11h2V2h2v10h2V4h2v19z");
}

</style>
