<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqzr8eb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-close-sharp" /></template>
<style>
.jqzr8eb0j {
  fill: currentColor;
  d: path("m11.9 13.5l2.1-2.1l2.1 2.1l1.4-1.4l-2.1-2.1l2.1-2.1l-1.4-1.4L14 8.6l-2.1-2.1l-1.4 1.4l2.1 2.1l-2.1 2.1zM6 18V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
