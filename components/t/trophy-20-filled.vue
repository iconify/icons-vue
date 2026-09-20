<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g3gb5ljaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:trophy-20-filled" /></template>
<style>
.g3gb5ljaw {
  fill: currentColor;
  d: path("M5.5 4a2 2 0 0 1 2-1.998h5A2 2 0 0 1 14.5 4h.996a1.5 1.5 0 0 1 1.5 1.5v1.505a2.996 2.996 0 0 1-2.601 2.97a4.5 4.5 0 0 1-3.894 3.498v1.495h2.003a2 2 0 0 1 2 2v.5a.5.5 0 0 1-.5.5h-8a.5.5 0 0 1-.5-.5v-.5a2 2 0 0 1 2-2h1.997v-1.495a4.5 4.5 0 0 1-3.895-3.501a3.006 3.006 0 0 1-2.61-2.974V5.5a1.5 1.5 0 0 1 1.5-1.5zm9 4.937a1.996 1.996 0 0 0 1.496-1.932V5.5a.5.5 0 0 0-.5-.5h-.995zM5.5 5H4.497a.5.5 0 0 0-.5.5v1.498c0 .93.64 1.713 1.505 1.936z");
}

</style>
