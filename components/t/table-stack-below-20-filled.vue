<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zd5ep1vge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-stack-below-20-filled" /></template>
<style>
.zd5ep1vge {
  fill: currentColor;
  d: path("M16.5 17a.5.5 0 0 0 0-1h-13a.5.5 0 0 0 0 1zM5 3h2v4H3V5a2 2 0 0 1 2-2M3 8h4v4H3.5a.5.5 0 0 1-.5-.5zm5 0v4h4V8zm4-5H8v4h4zm1 9V8h4v3.5a.5.5 0 0 1-.5.5zm0-9h2a2 2 0 0 1 2 2v2h-4z");
}

</style>
