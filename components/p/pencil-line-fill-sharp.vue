<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtl97gbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-line-fill-sharp" /></template>
<style>
.wtl97gbmm {
  fill: currentColor;
  d: path("m12 6.586l3.293-3.293a1 1 0 0 1 1.414 0l4 4a1 1 0 0 1 0 1.414L17.414 12ZM3 16c0-.265.105-.52.293-.707L10.586 8L16 13.414L10.414 19H20a1 1 0 0 1 0 2H4a1 1 0 0 1-1-1Z");
}

</style>
