<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oe0p9ac1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:road-20-regular" /></template>
<style>
.oe0p9ac1o {
  fill: currentColor;
  d: path("M5 2.5a.5.5 0 0 0-1 0v15a.5.5 0 0 0 1 0zm11 0a.5.5 0 0 0-1 0v15a.5.5 0 0 0 1 0zm-5.5 0a.5.5 0 0 0-1 0v3a.5.5 0 0 0 1 0zm-1 9a.5.5 0 0 0 1 0v-3a.5.5 0 0 0-1 0zm0 3a.5.5 0 0 1 1 0v3a.5.5 0 0 1-1 0z");
}

</style>
