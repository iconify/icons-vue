<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hthzk1a1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-ltr-90-20-regular" /></template>
<style>
.hthzk1a1g {
  fill: currentColor;
  d: path("M14.5 3a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 3a.5.5 0 0 1 .5.5v11a.5.5 0 0 1-1 0v-11a.5.5 0 0 1 .5-.5m-5 0a.5.5 0 0 1 .5.5v11a.5.5 0 0 1-1 0v-11a.5.5 0 0 1 .5-.5M6 6.5a.5.5 0 0 0-1 0v11a.5.5 0 0 0 1 0zM5.5 4a1 1 0 1 1 0-2a1 1 0 0 1 0 2m4-1a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
