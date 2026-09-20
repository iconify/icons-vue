<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dyw09yb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:power-20-regular" /></template>
<style>
.dyw09yb_u {
  fill: currentColor;
  d: path("M10.5 2.5a.5.5 0 0 0-1 0v6a.5.5 0 0 0 1 0zM13.743 4a.5.5 0 1 0-.499.867a6.5 6.5 0 1 1-6.494.004a.5.5 0 1 0-.5-.866A7.5 7.5 0 1 0 13.743 4");
}

</style>
