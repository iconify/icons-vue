<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnx4-7bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-label" /></template>
<style>
.xnx4-7bft {
  fill: currentColor;
  d: path("M17.03 5L3 5.01v13.98l14.03.01L22 12z");
}

</style>
