<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uigiw4bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-rtl-20-regular" /></template>
<style>
.uigiw4bzv {
  fill: currentColor;
  d: path("M17 5.5a1 1 0 1 1 0-2a1 1 0 0 1 0 2m-3-1a.5.5 0 0 0-.5-.5h-11a.5.5 0 0 0 0 1h11a.5.5 0 0 0 .5-.5m0 5a.5.5 0 0 0-.5-.5h-11a.5.5 0 0 0 0 1h11a.5.5 0 0 0 .5-.5m-.5 4.5a.5.5 0 0 1 0 1h-11a.5.5 0 0 1 0-1zm2.5.5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1-4a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

</style>
