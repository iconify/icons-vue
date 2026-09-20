<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w4228yggk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:split-hint-20-regular" /></template>
<style>
.w4228yggk {
  fill: currentColor;
  d: path("M9.5 2a.5.5 0 0 1 .5.5v15a.5.5 0 0 1-1 0v-15a.5.5 0 0 1 .5-.5M2 6a2 2 0 0 1 2-2h4v1H4a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h4v1H4a2 2 0 0 1-2-2zm13-1a1 1 0 0 1 1 1v.5a.5.5 0 0 0 1 0V6a2 2 0 0 0-2-2h-.5a.5.5 0 0 0 0 1zm0 10a1 1 0 0 0 1-1v-.5a.5.5 0 0 1 1 0v.5a2 2 0 0 1-2 2h-.5a.5.5 0 0 1 0-1zm1.5-7a.5.5 0 0 0-.5.5v3a.5.5 0 0 0 1 0v-3a.5.5 0 0 0-.5-.5m-4-4a.5.5 0 0 1 0 1h-1a.5.5 0 0 1 0-1zm.5 11.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0 0 1h1a.5.5 0 0 0 .5-.5");
}

</style>
