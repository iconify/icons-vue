<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w9pxo_j_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-move-right-20-regular" /></template>
<style>
.w9pxo_j_h {
  fill: currentColor;
  d: path("M16.5 3a.5.5 0 0 1 .5.5v13a.5.5 0 0 1-1 0v-13a.5.5 0 0 1 .5-.5m-4.5.5v3.882l-.06.057a1.5 1.5 0 0 0-.355.561H8v4h3.585a1.5 1.5 0 0 0 .415.618V16.5a.5.5 0 0 1-.5.5H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h6.5a.5.5 0 0 1 .5.5M7 4H5a1 1 0 0 0-1 1v2h3zm-3 8h3V8H4zm0 1v2a1 1 0 0 0 1 1h2v-3zm4 0v3h3v-3zm3-9H8v3h3zm1.646 7.146a.5.5 0 0 0 .708.708l1.5-1.5a.5.5 0 0 0 0-.708l-1.5-1.5a.5.5 0 0 0-.708.708l.647.646H10.5a.5.5 0 0 0 0 1h2.793z");
}

</style>
