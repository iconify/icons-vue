<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s0vufrbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-description-32-regular" /></template>
<style>
.s0vufrbry {
  fill: currentColor;
  d: path("M3 6a1 1 0 0 0 0 2h26a1 1 0 1 0 0-2zm0 6a1 1 0 1 0 0 2h26a1 1 0 1 0 0-2zm-1 7a1 1 0 0 0 1 1h26a1 1 0 1 0 0-2H3a1 1 0 0 0-1 1m1 5a1 1 0 1 0 0 2h17a1 1 0 1 0 0-2z");
}

</style>
