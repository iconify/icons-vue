<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wjm179syi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-insert-column-20-filled" /></template>
<style>
.wjm179syi {
  fill: currentColor;
  d: path("M4 3.5a.5.5 0 0 0-1 0v13a.5.5 0 0 0 1 0zm13 0a.5.5 0 0 0-1 0v13a.5.5 0 0 0 1 0zM9 3a2 2 0 0 0-2 2v2h6V5a2 2 0 0 0-2-2zm-2 9V8h6v4zm0 1h6v2a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2z");
}

</style>
