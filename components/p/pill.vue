<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xvfhz8biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pill" /></template>
<style>
.xvfhz8biq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.778 39.536c-3.953 3.952-10.361 3.952-14.314 0s-3.952-10.361 0-14.314L25.222 8.464c3.953-3.952 10.361-3.952 14.314 0s3.952 10.361 0 14.314zm8.688-8.688L17.152 16.534");
}

</style>
