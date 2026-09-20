<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itvcc32fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:toolbar-outline-sharp" /></template>
<style>
.itvcc32fg {
  fill: currentColor;
  d: path("M3 21V3h18v18zM5 8h14V5H5zm14 2H5v9h14zM5 8v2zm0 0V5zm0 2v9z");
}

</style>
