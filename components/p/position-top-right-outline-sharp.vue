<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqnvmhzbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:position-top-right-outline-sharp" /></template>
<style>
.zqnvmhzbc {
  fill: currentColor;
  d: path("M9 10h9V7H9zM3 21V3h18v18zm2-2h14V5H5zM5 5v14z");
}

</style>
