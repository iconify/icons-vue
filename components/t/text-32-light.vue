<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qq86web5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-32-light" /></template>
<style>
.qq86web5i {
  fill: currentColor;
  d: path("M6 4.5a.5.5 0 0 1 .5-.5h19a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-1 0V5h-8.5v22h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3V5H7v3.5a.5.5 0 0 1-1 0z");
}

</style>
