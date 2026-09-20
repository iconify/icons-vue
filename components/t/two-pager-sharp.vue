<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcr7bgbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:two-pager-sharp" /></template>
<style>
.bcr7bgbkq {
  fill: currentColor;
  d: path("M2 20V4h20v16zm11-2h7V6h-7zm-8-2h5v-2H5zm0-3h5v-2H5zm0-3h5V8H5zm9 6h5v-2h-5zm0-3h5v-2h-5zm0-3h5V8h-5z");
}

</style>
