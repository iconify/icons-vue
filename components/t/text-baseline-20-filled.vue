<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ty6ejb1-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-baseline-20-filled" /></template>
<style>
.ty6ejb1-v {
  fill: currentColor;
  d: path("M10.698 3.475a.75.75 0 0 0-1.395 0l-3.75 9.5a.75.75 0 0 0 1.395.55L8.142 10.5h3.717l1.194 3.025a.75.75 0 0 0 1.395-.55zM11.266 9H8.734l1.267-3.207zM2.5 16a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1z");
}

</style>
