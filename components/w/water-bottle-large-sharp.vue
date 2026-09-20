<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu-ew2bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:water-bottle-large-sharp" /></template>
<style>
.xu-ew2bqk {
  fill: currentColor;
  d: path("M5 22v-6h2v-5H5V5h5V4H9V2h6v2h-1v1h5v6h-2v5h2v6z");
}

</style>
