<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ie_rsebwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-unknown-12-regular" /></template>
<style>
.ie_rsebwe {
  fill: currentColor;
  d: path("M6 1.5a4.5 4.5 0 1 0 0 9a4.5 4.5 0 0 0 0-9M0 6a6 6 0 1 1 12 0A6 6 0 0 1 0 6");
}

</style>
