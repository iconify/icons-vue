<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="got74ghtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rectangle-portrait-48-filled" /></template>
<style>
.got74ghtl {
  fill: currentColor;
  d: path("M14.25 44A6.25 6.25 0 0 1 8 37.75v-27.5A6.25 6.25 0 0 1 14.25 4h19.5A6.25 6.25 0 0 1 40 10.25v27.5A6.25 6.25 0 0 1 33.75 44z");
}

</style>
