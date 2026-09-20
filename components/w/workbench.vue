<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w42fmcekj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:workbench" /></template>
<style>
.w42fmcekj {
  fill: currentColor;
  d: path("M2 22V8.5L12 2l10 6.5V22l-10-7Zm10-9.4l6.325-4.1L12 4.4L5.675 8.5Z");
}

</style>
