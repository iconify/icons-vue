<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pej17cc2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-48-regular" /></template>
<style>
.pej17cc2e {
  fill: currentColor;
  d: path("M33.75 4A6.25 6.25 0 0 1 40 10.25v27.5A6.25 6.25 0 0 1 33.75 44h-19.5A6.25 6.25 0 0 1 8 37.75v-27.5A6.25 6.25 0 0 1 14.25 4zm-19.5 2.5a3.75 3.75 0 0 0-3.75 3.75v27.5a3.75 3.75 0 0 0 3.75 3.75h19.5a3.75 3.75 0 0 0 3.75-3.75v-27.5a3.75 3.75 0 0 0-3.75-3.75zM19 20.004c0-1.92 2.074-3.123 3.74-2.171l6.997 3.998c1.68.96 1.68 3.382 0 4.342L22.74 30.17C21.074 31.122 19 29.92 19 28z");
}

</style>
