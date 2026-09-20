<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dscm1lbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-multiple-16-regular" /></template>
<style>
.dscm1lbwx {
  fill: currentColor;
  d: path("M6 4a1 1 0 1 1-2 0a1 1 0 0 1 2 0M2 4a3 3 0 0 1 3-3h6a3 3 0 1 1 0 6H5a3 3 0 0 1-3-3m3-2a2 2 0 1 0 0 4h6a2 2 0 1 0 0-4zm6 10a1 1 0 1 0 0-2a1 1 0 0 0 0 2m-9-1a3 3 0 0 1 3-3h6a3 3 0 1 1 0 6H5a3 3 0 0 1-3-3m3-2a2 2 0 1 0 0 4h6a2 2 0 1 0 0-4z");
}

</style>
