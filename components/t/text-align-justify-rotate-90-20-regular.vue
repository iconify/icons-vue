<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rtxz4eb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-justify-rotate-90-20-regular" /></template>
<style>
.rtxz4eb0o {
  fill: currentColor;
  d: path("M15.5 2a.5.5 0 0 1 .5.5v15a.5.5 0 0 1-1 0v-15a.5.5 0 0 1 .5-.5m-5 0a.5.5 0 0 1 .5.5v15a.5.5 0 0 1-1 0v-15a.5.5 0 0 1 .5-.5M6 2.5a.5.5 0 0 0-1 0v15a.5.5 0 0 0 1 0z");
}

</style>
