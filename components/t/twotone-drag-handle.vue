<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twhymzbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-drag-handle" /></template>
<style>
.twhymzbxt {
  fill: currentColor;
  d: path("M4 9h16v2H4zm0 4h16v2H4z");
}

</style>
