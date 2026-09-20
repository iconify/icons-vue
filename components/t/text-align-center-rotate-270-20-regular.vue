<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zp9_z_e7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-center-rotate-270-20-regular" /></template>
<style>
.zp9_z_e7g {
  fill: currentColor;
  d: path("M4.5 16a.5.5 0 0 1-.5-.5v-11a.5.5 0 0 1 1 0v11a.5.5 0 0 1-.5.5m5 2a.5.5 0 0 1-.5-.5v-15a.5.5 0 0 1 1 0v15a.5.5 0 0 1-.5.5m4.5-4.5a.5.5 0 0 0 1 0v-7a.5.5 0 0 0-1 0z");
}

</style>
