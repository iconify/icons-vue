<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="um2akwbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rectangle-portrait-48-regular" /></template>
<style>
.um2akwbne {
  fill: currentColor;
  d: path("M14.25 44A6.25 6.25 0 0 1 8 37.75v-27.5A6.25 6.25 0 0 1 14.25 4h19.5A6.25 6.25 0 0 1 40 10.25v27.5A6.25 6.25 0 0 1 33.75 44zm-3.75-6.25a3.75 3.75 0 0 0 3.75 3.75h19.5a3.75 3.75 0 0 0 3.75-3.75v-27.5a3.75 3.75 0 0 0-3.75-3.75h-19.5a3.75 3.75 0 0 0-3.75 3.75z");
}

</style>
