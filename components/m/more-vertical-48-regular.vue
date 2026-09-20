<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="um8r-mbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-vertical-48-regular" /></template>
<style>
.um8r-mbfp {
  fill: currentColor;
  d: path("M24.002 15.75a3.25 3.25 0 1 1 0-6.5a3.25 3.25 0 0 1 0 6.5m0 11.5a3.25 3.25 0 1 1 0-6.5a3.25 3.25 0 0 1 0 6.5m-3.25 8.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 0 0-6.5 0");
}

</style>
