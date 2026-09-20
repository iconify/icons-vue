<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov3s02b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tooltip-sharp" /></template>
<style>
.ov3s02b9d {
  fill: currentColor;
  d: path("m12 21l-2.29-3.5H3V3h18v14.5h-6.71z");
}

</style>
