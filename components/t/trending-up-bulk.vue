<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h459qjbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trending-up-bulk" /></template>
<style>
.h459qjbzo {
  fill: currentColor;
  d: path("M21 6a.997.997 0 0 1 1 1v6a1 1 0 0 1-2 0V9.414l-5.293 5.293a2.414 2.414 0 0 1-3.414 0l-2-2a.414.414 0 0 0-.586 0l-5 5a.999.999 0 1 1-1.414-1.414l5-5a2.414 2.414 0 0 1 3.414 0l2 2a.414.414 0 0 0 .586 0L18.586 8H15a1 1 0 0 1 0-2Z");
}

</style>
