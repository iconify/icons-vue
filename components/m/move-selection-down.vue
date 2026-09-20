<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aexnd4hgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:move-selection-down" /></template>
<style>
.aexnd4hgf {
  fill: currentColor;
  d: path("M6 22V10h12v12zM6 8V6h2v2zm10 0V6h2v2zM6 4V2h2v2zm5 0V2h2v2zm5 0V2h2v2z");
}

</style>
