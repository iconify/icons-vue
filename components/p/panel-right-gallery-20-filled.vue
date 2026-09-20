<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fcddh14nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-right-gallery-20-filled" /></template>
<style>
.fcddh14nc {
  fill: currentColor;
  d: path("M18 6a3 3 0 0 0-3-3H5a3 3 0 0 0-3 3v7a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3v-1h-5v3H5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h8v3h5zm0 2h-5v3h5z");
}

</style>
