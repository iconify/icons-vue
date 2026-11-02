<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf1gphbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trending-down-fill" /></template>
<style>
.rf1gphbex {
  fill: currentColor;
  d: path("M8.707 11.293a.414.414 0 0 0 .586 0l2-2a2.414 2.414 0 0 1 3.414 0L20 14.586V11a1 1 0 0 1 2 0v6a.997.997 0 0 1-1 1h-6a1 1 0 0 1 0-2h3.586l-5.293-5.293a.414.414 0 0 0-.586 0l-2 2a2.414 2.414 0 0 1-3.414 0l-5-5a.999.999 0 1 1 1.414-1.414Z");
}

</style>
