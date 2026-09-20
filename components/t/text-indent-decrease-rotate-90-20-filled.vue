<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mri-f9bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-decrease-rotate-90-20-filled" /></template>
<style>
.mri-f9bpl {
  fill: currentColor;
  d: path("M10.97 4.78a.75.75 0 1 0 1.06-1.06l-1.5-1.5a.75.75 0 0 0-1.06 0l-1.5 1.5a.75.75 0 0 0 1.06 1.06l.97-.97zM6.25 7.75a.75.75 0 0 0-1.5 0v6.5a.75.75 0 0 0 1.5 0zm9 0a.75.75 0 0 0-1.5 0v6.5a.75.75 0 0 0 1.5 0zM10 7a.75.75 0 0 1 .75.75v9.5a.75.75 0 0 1-1.5 0v-9.5A.75.75 0 0 1 10 7");
}

</style>
