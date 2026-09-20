<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sii2j5bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-rotate-90-20-regular" /></template>
<style>
.sii2j5bvp {
  fill: currentColor;
  d: path("M4.5 4a1 1 0 1 0 0-2a1 1 0 0 0 0 2ZM10 4a1 1 0 1 0 0-2a1 1 0 0 0 0 2Zm6.5-1a1 1 0 1 1-2 0a1 1 0 0 1 2 0ZM5 5.5a.5.5 0 0 0-1 0v12a.5.5 0 0 0 1 0v-12Zm5-.5a.5.5 0 0 1 .5.5v12a.5.5 0 0 1-1 0v-12A.5.5 0 0 1 10 5Zm6 .5a.5.5 0 0 0-1 0v12a.5.5 0 0 0 1 0v-12Z");
}

</style>
