<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3m13panc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trending-down-bulk-round" /></template>
<style>
.r3m13panc {
  fill: currentColor;
  d: path("M7.707 10.293a1.83 1.83 0 0 0 2.586 0a3.826 3.826 0 0 1 5.414 0L20 14.586V11a1 1 0 0 1 2 0v6a.997.997 0 0 1-1 1h-6a1 1 0 0 1 0-2h3.586l-4.293-4.293a1.83 1.83 0 0 0-2.586 0a3.826 3.826 0 0 1-5.414 0l-4-4a.999.999 0 1 1 1.414-1.414Z");
}

</style>
