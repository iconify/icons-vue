<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhuu5lhir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sim-card-download-sharp" /></template>
<style>
.rhuu5lhir {
  fill: currentColor;
  d: path("m12 17l4-4l-1.4-1.4l-1.6 1.55V9h-2v4.15L9.4 11.6L8 13zm-8 5V8l6-6h10v20z");
}

</style>
