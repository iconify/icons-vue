<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxiwfu_6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-delete" /></template>
<style>
.cxiwfu_6h {
  fill: currentColor;
  d: path("M6 21h12V7H6zM19 4h-3.5l-1-1h-5l-1 1H5v2h14z");
}

</style>
