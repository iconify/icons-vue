<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ig4i06f4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-t-48-filled" /></template>
<style>
.ig4i06f4s {
  fill: currentColor;
  d: path("M10 9.5A1.5 1.5 0 0 1 11.5 8h25A1.5 1.5 0 0 1 38 9.5v4a1.5 1.5 0 0 1-3 0V11h-9.5v26h3a1.5 1.5 0 0 1 0 3h-9a1.5 1.5 0 0 1 0-3h3V11H13v2.5a1.5 1.5 0 0 1-3 0z");
}

</style>
