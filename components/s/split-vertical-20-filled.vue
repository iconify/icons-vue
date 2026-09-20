<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zvtl5ccpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:split-vertical-20-filled" /></template>
<style>
.zvtl5ccpl {
  fill: currentColor;
  d: path("M10 2.5a.5.5 0 0 0-1 0v15a.5.5 0 0 0 1 0zM2 6a2 2 0 0 1 2-2h4v12H4a2 2 0 0 1-2-2zm9 10h4a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-4z");
}

</style>
