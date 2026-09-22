<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-q9imjes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-spark-outline-sharp" /></template>
<style>
.s-q9imjes {
  fill: currentColor;
  d: path("M4 6v6.077v-.194V18zm12 8.692l2.558-2.558l-.608-.632l-1.508 1.488v-2.682h-.884v2.683l-1.508-1.489l-.608.633zm-10.192 0h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884V9.308H5.808zm12.596-5q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.387-1.359q-.15-.05-.15-.2q0-.175.15-.2q1.39-.362 2.387-1.359t1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.36q.15.024.15.2q0 .15-.15.2q-1.39.36-2.388 1.358q-.997.997-1.358 2.387q-.025.15-.2.15M3 19V5h8.917v1H4v12h16v-6.117h1V19z");
}

</style>
