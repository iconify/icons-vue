<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uhpt9bcwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-circle-1-32-regular" /></template>
<style>
.uhpt9bcwx {
  fill: currentColor;
  d: path("M4 16C4 9.373 9.373 4 16 4s12 5.373 12 12s-5.373 12-12 12S4 22.627 4 16M16 2C8.268 2 2 8.268 2 16s6.268 14 14 14s14-6.268 14-14S23.732 2 16 2m2 7a1 1 0 0 0-1.96-.277l-.001.001l-.006.02l-.03.09a9 9 0 0 1-.74 1.593c-.57.967-1.444 2.033-2.705 2.655a1 1 0 1 0 .884 1.794c1.073-.529 1.913-1.273 2.558-2.037V22a1 1 0 1 0 2 0z");
}

</style>
