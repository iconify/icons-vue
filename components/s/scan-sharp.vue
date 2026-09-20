<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx-ciib0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scan-sharp" /></template>
<style>
.cx-ciib0v {
  fill: currentColor;
  d: path("M14 8h4l-4-4zM5 21v-4.5h14V21zm-3.423-6.5v-1h20.846v1zM5 11.5V3h9.5L19 7.5v4z");
}

</style>
