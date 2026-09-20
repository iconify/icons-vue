<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="si0ttcbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:record-20-filled" /></template>
<style>
.si0ttcbyj {
  fill: currentColor;
  d: path("M2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0m8 4.5a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9");
}

</style>
