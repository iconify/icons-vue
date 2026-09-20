<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrqm9q-1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:satellite-sharp" /></template>
<style>
.zrqm9q-1a {
  fill: currentColor;
  d: path("M6 17h12l-3.75-5l-3 4L9 13zm0-5q2.5 0 4.25-1.75T12 6h-1.7q0 1.8-1.25 3.05T6 10.3zm0-3.4q1.075 0 1.813-.763T8.55 6H6zM3 21V3h18v18z");
}

</style>
