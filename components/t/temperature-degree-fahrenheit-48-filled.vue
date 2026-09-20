<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x85wxjbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:temperature-degree-fahrenheit-48-filled" /></template>
<style>
.x85wxjbzx {
  fill: currentColor;
  d: path("M8 15a4 4 0 1 1 8 0a4 4 0 0 1-8 0m4-7a7 7 0 1 0 0 14a7 7 0 0 0 0-14m12.5 0A1.5 1.5 0 0 0 23 9.5v29a1.5 1.5 0 0 0 3 0V25h12.5a1.5 1.5 0 0 0 0-3H26V11h14.5a1.5 1.5 0 0 0 0-3z");
}

</style>
