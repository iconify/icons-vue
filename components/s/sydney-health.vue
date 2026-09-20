<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="fmn8yub-d"><path class="et5fg7b7p"/><path class="wtjeqybsl"/><path class="b4heybb8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sydney-health" /></template>
<style>
.b4heybb8z {
  d: path("m38.67 34.506l-4.137-2.739l-.042.054a9.5 9.5 0 0 0 1.024-4.228c0-5.879-5.485-10.644-12.25-10.644s-12.25 4.766-12.249 10.644S16.5 38.236 23.265 38.237c3.241-.01 6.343-1.135 8.66-3.133z");
}

.et5fg7b7p {
  d: path("M24.015 7.687c-9.08 0-16.44 7.303-16.44 16.312c0 2.76.694 5.36 1.914 7.638l-4.343 2.735c-.859.54-.625 1.711.474 1.805l8.309.704a16.45 16.45 0 0 0 10.086 3.432a16.44 16.44 0 0 0 10.11-3.455l-.014.016l8.389-.684c.966-.079 1.177-1.29.403-1.79l-4.34-2.799l-.01.012a16.14 16.14 0 0 0 1.9-7.614c0-9.01-7.359-16.312-16.438-16.312");
}

.fmn8yub-d {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wtjeqybsl {
  d: path("M20.413 25.36a2.047 1.894 0 0 1-2.047 1.894a2.047 1.894 0 0 1-2.048-1.894a2.047 1.894 0 0 1 2.048-1.894a2.047 1.894 0 0 1 2.047 1.894m9.854 0a2.047 1.894 0 0 1-2.047 1.894a2.047 1.894 0 0 1-2.047-1.894a2.047 1.894 0 0 1 2.047-1.894a2.047 1.894 0 0 1 2.047 1.894m-4.759 4.328c-.251 1.166-1.165 1.986-2.215 1.986s-1.964-.82-2.215-1.986z");
}

</style>
