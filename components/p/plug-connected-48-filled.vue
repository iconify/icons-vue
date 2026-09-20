<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y5-75dbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:plug-connected-48-filled" /></template>
<style>
.y5-75dbli {
  fill: currentColor;
  d: path("m21.515 9.514l-1.27 1.27a4.25 4.25 0 0 0 0 6.01l10.96 10.96a4.25 4.25 0 0 0 6.01 0l1.27-1.27c4.388-4.387 4.667-11.327.839-16.04l4.31-4.31a1.25 1.25 0 1 0-1.768-1.768l-4.31 4.31c-4.713-3.83-11.654-3.55-16.041.838m6.24 27.701l-1.27 1.27c-4.387 4.388-11.328 4.668-16.04.839l-4.311 4.31a1.25 1.25 0 1 1-1.768-1.768l4.31-4.31c-3.828-4.713-3.549-11.653.839-16.041l1.27-1.27a4.25 4.25 0 0 1 6.01 0l10.96 10.96a4.25 4.25 0 0 1 0 6.01");
}

</style>
