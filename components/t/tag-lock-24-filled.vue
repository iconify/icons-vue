<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8r2f8dpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tag-lock-24-filled" /></template>
<style>
.m8r2f8dpx {
  fill: currentColor;
  d: path("M19.75 2A2.25 2.25 0 0 1 22 4.25v5.462a3.25 3.25 0 0 1-.952 2.298l-.42.42A3.5 3.5 0 0 0 14 14v.05a2.5 2.5 0 0 0-2 2.45v4.453a3.256 3.256 0 0 1-4.05-.439L3.49 16.06a3.25 3.25 0 0 1-.005-4.596l8.5-8.51a3.25 3.25 0 0 1 2.3-.953zM17 5.502a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3M15 15h-.5a1.5 1.5 0 0 0-1.5 1.5v5a1.5 1.5 0 0 0 1.5 1.5h6a1.5 1.5 0 0 0 1.5-1.5v-5a1.5 1.5 0 0 0-1.5-1.5H20v-1a2.5 2.5 0 0 0-5 0zm1.5-1a1 1 0 1 1 2 0v1h-2zm2 5a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

</style>
