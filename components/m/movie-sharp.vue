<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg7k-kxmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:movie-sharp" /></template>
<style>
.wg7k-kxmt {
  fill: currentColor;
  d: path("M2 20V4h2l2 4h3L7 4h2l2 4h3l-2-4h2l2 4h3l-2-4h5v16z");
}

</style>
