<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8fmf-iqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-bag-alt-fill-sharp" /></template>
<style>
.a8fmf-iqn {
  fill: currentColor;
  d: path("M2 20V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1M15.685 9.557A4 4 0 0 0 16 8a1 1 0 0 0-2 0a2 2 0 1 1-4 0a1 1 0 0 0-2 0a4 4 0 0 0 3.999 4c1.607 0 3.06-.963 3.686-2.443");
}

</style>
