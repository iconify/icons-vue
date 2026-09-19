<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7ix-fbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-panorama" /></template>
<style>
.h7ix-fbmf {
  fill: currentColor;
  d: path("M23 20V4H1v16zM8.5 12.5l2.5 3.01L14.5 11l4.5 6H5z");
}

</style>
