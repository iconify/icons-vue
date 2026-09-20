<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xobsgnbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:treasure-chest-bold" /></template>
<style>
.xobsgnbgp {
  fill: currentColor;
  d: path("M184 36H72a60.07 60.07 0 0 0-60 60v96a20 20 0 0 0 20 20h192a20 20 0 0 0 20-20V96a60.07 60.07 0 0 0-60-60m36 60v4h-28V60.91A36.05 36.05 0 0 1 220 96m-92 60a12 12 0 0 0 12-12v-20h28v64H88v-64h28v20a12 12 0 0 0 12 12m12-56v-4a12 12 0 0 0-24 0v4H88V60h80v40ZM64 60.91V100H36v-4a36.05 36.05 0 0 1 28-35.09M36 124h28v64H36Zm156 64v-64h28v64Z");
}

</style>
