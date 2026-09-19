<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uffpc9b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:optumrx" /></template>
<style>
.uffpc9b3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.036 16.964L16.964 31.036m5.744-22.4l16.657 16.656c4.062 4.063 4.194 10.468.294 14.368c-3.896 3.9-10.304 3.767-14.367-.295L8.635 22.708C4.573 18.645 4.441 12.24 8.341 8.34s10.305-3.768 14.367.294Z");
}

</style>
