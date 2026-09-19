<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmv0oy0qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-note" /></template>
<style>
.fmv0oy0qj {
  fill: currentColor;
  d: path("m22 10l-6-6H2v16h20zm-7-4.5l5.5 5.5H15z");
}

</style>
