<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itkj75bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-battery-std" /></template>
<style>
.itkj75bfr {
  fill: currentColor;
  d: path("M17 4h-3V2h-4v2H7v18h10z");
}

</style>
