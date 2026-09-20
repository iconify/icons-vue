<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sx-35t9kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:refrigerator-20-regular" /></template>
<style>
.sx-35t9kh {
  fill: currentColor;
  d: path("M13.154 2.004A3 3 0 0 1 16 5v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6zM5 15a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V9H5zm1.5-5a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-1 0v-3a.5.5 0 0 1 .5-.5M7 3a2 2 0 0 0-2 2v3h10V5a2 2 0 0 0-1.796-1.99L13 3zm-.5 1a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0v-2a.5.5 0 0 1 .5-.5");
}

</style>
