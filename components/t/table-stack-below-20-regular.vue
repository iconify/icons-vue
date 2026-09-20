<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fkiswqi6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-stack-below-20-regular" /></template>
<style>
.fkiswqi6m {
  fill: currentColor;
  d: path("M17 16.5a.5.5 0 0 1-.5.5h-13a.5.5 0 0 1 0-1h13a.5.5 0 0 1 .5.5m0-5a.5.5 0 0 1-.5.5h-13a.5.5 0 0 1-.5-.5V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2zM16 7V5a1 1 0 0 0-1-1h-2v3zM8 4v3h4V4zM7 4H5a1 1 0 0 0-1 1v2h3zm0 4H4v3h3zm1 3h4V8H8zm8 0V8h-3v3z");
}

</style>
