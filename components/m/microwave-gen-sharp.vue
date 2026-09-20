<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgkahhb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:microwave-gen-sharp" /></template>
<style>
.sgkahhb1a {
  fill: currentColor;
  d: path("M2 20V4h20v16zm3-3h10V7H5zm2-2V9h6v6zm10-6h2V7h-2zm0 4h2v-2h-2zm0 4h2v-2h-2z");
}

</style>
