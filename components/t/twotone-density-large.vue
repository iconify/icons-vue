<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjqp-tjxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-density-large" /></template>
<style>
.fjqp-tjxv {
  fill: currentColor;
  d: path("M3 3h18v2H3zm0 16h18v2H3z");
}

</style>
