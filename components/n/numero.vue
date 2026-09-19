<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mxlorvbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:numero" /></template>
<style>
.mxlorvbgd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 8.48v20.694c0 5.714-4.141 10.346-9.25 10.346S24 34.889 24 29.173V18.827c0-5.715-4.141-10.348-9.25-10.348S5.5 13.112 5.5 18.826V39.52");
}

</style>
