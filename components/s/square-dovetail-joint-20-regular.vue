<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zw8mrreil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-dovetail-joint-20-regular" /></template>
<style>
.zw8mrreil {
  fill: currentColor;
  d: path("M14 3H6a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3M4 14V6a2 2 0 0 1 2-2h2v4.227a.5.5 0 0 0 .673.469L12 7.467v5.061l-3.324-1.247a.5.5 0 0 0-.676.468v4.25H6a2 2 0 0 1-2-2zm12 0a2 2 0 0 1-2 2H9v-3.528l3.324 1.247a.5.5 0 0 0 .676-.468v-6.5a.5.5 0 0 0-.673-.469L9 7.511V4.002h5a2 2 0 0 1 2 2v8z");
}

</style>
