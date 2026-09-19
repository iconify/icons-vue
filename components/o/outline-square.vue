<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xugrx5b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-square" /></template>
<style>
.xugrx5b8f {
  fill: currentColor;
  d: path("M3 3v18h18V3zm16 16H5V5h14z");
}

</style>
