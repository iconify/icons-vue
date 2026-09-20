<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":49,"height":48};
const content = `<g class="ft5dv1b6b"><path class="g1c0bfrvr"/><path class="e9yjoky3w"/><path class="ccxz6jbik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-48-regular" /></template>
<style>
.ccxz6jbik {
  d: path("M35.502 27.25a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5z");
  fill: currentColor;
}

.e9yjoky3w {
  d: path("M27.252 24a3.25 3.25 0 1 1-6.5 0a3.25 3.25 0 0 1 6.5 0z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.g1c0bfrvr {
  d: path("M15.752 24a3.25 3.25 0 1 1-6.5 0a3.25 3.25 0 0 1 6.5 0z");
  fill: currentColor;
}

</style>
