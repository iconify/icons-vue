<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3dq3ccxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-data-object" /></template>
<style>
.d3dq3ccxv {
  fill: currentColor;
  d: path("M4 10H2v4h2v6h6v-2H6v-5.5H4v-1h2V6h4V4H4zm16 0V4h-6v2h4v5.5h2v1h-2V18h-4v2h6v-6h2v-4z");
}

</style>
