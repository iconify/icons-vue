<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k-gvc7bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-page-header-20-filled" /></template>
<style>
.k-gvc7bgc {
  fill: currentColor;
  d: path("M5 4a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v1H5zm0 2v10a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V6z");
}

</style>
