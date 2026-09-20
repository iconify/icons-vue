<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc2g1n4hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:orders-outline" /></template>
<style>
.bc2g1n4hn {
  fill: currentColor;
  d: path("M5 19V8.1L3.242 4.234l.916-.426L6.084 8.05h11.832l1.926-4.242l.916.427L19 8.1V19zm5-6.5h4q.213 0 .356-.144t.144-.357t-.144-.356T14 11.5h-4q-.213 0-.356.144t-.144.357t.144.356t.356.143M6 18h12V9.05H6zm0 0V9.05z");
}

</style>
