<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b7bgk8hdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-stack-right-20-regular" /></template>
<style>
.b7bgk8hdf {
  fill: currentColor;
  d: path("M16.5 3a.5.5 0 0 1 .5.5v13a.5.5 0 0 1-1 0v-13a.5.5 0 0 1 .5-.5m-5 0a.5.5 0 0 1 .5.5v13a.5.5 0 0 1-.5.5H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2zM7 4H5a1 1 0 0 0-1 1v2h3zm-3 8h3V8H4zm0 1v2a1 1 0 0 0 1 1h2v-3zm4 0v3h3v-3zm3-1V8H8v4zm0-8H8v3h3z");
}

</style>
