<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkv9adxxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-upload-fill" /></template>
<style>
.rkv9adxxq {
  fill: currentColor;
  d: path("M6 3h12a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3m5.293 3.293l-3 3a.999.999 0 1 0 1.414 1.414L11 9.414V14a1 1 0 0 0 2 0V9.414l1.293 1.293a.999.999 0 1 0 1.414-1.414l-3-3a1 1 0 0 0-1.414 0M9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
