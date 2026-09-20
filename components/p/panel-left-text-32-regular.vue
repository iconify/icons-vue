<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f5wlwlbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-text-32-regular" /></template>
<style>
.f5wlwlbdp {
  fill: currentColor;
  d: path("M6.5 9a1 1 0 0 0 0 2h2a1 1 0 1 0 0-2zm-1 7a1 1 0 0 1 1-1h2a1 1 0 1 1 0 2h-2a1 1 0 0 1-1-1m1 5a1 1 0 1 0 0 2h2a1 1 0 1 0 0-2zm0-17A4.5 4.5 0 0 0 2 8.5v15A4.5 4.5 0 0 0 6.5 28h19a4.5 4.5 0 0 0 4.5-4.5v-15A4.5 4.5 0 0 0 25.5 4zM13 26V6h12.5A2.5 2.5 0 0 1 28 8.5v15a2.5 2.5 0 0 1-2.5 2.5zM6.5 6H11v20H6.5A2.5 2.5 0 0 1 4 23.5v-15A2.5 2.5 0 0 1 6.5 6");
}

</style>
