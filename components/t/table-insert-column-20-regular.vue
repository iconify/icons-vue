<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wxaw9vb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-insert-column-20-regular" /></template>
<style>
.wxaw9vb0z {
  fill: currentColor;
  d: path("M4 3.5a.5.5 0 0 0-1 0v13a.5.5 0 0 0 1 0zm13 0a.5.5 0 0 0-1 0v13a.5.5 0 0 0 1 0zM9 3a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2zm-1 9V8h4v4zm4-7v2H8V5a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1m-4 8h4v2a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1z");
}

</style>
