<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umb8qabuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-file-download-off" /></template>
<style>
.umb8qabuw {
  fill: currentColor;
  d: path("M9 6.17V3h6v6h4l-3.59 3.59zm12.19 15.02L2.81 2.81L1.39 4.22L6.17 9H5l7 7l.59-.59L15.17 18H5v2h12.17l2.61 2.61z");
}

</style>
