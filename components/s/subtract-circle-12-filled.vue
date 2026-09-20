<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yzgpkpu7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:subtract-circle-12-filled" /></template>
<style>
.yzgpkpu7t {
  fill: currentColor;
  d: path("M1 6a5 5 0 1 1 10 0A5 5 0 0 1 1 6m3-.5a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1z");
}

</style>
