<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1mlctbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:quiz-sharp" /></template>
<style>
.z1mlctbny {
  fill: currentColor;
  d: path("M14.045 14.303q.236-.236.236-.545t-.236-.545t-.545-.236t-.545.236t-.236.545t.236.545t.545.236t.545-.236m-.987-2.58h.884q.039-.629.198-.947q.16-.318.768-.888q.634-.576.884-1.03q.25-.452.25-1.039q0-1.01-.72-1.683q-.72-.674-1.822-.674q-.833 0-1.48.45t-.985 1.227l.811.357q.283-.586.69-.88t.964-.293q.716 0 1.187.424q.47.424.47 1.095q0 .408-.228.759q-.229.351-.787.845q-.632.552-.858 1.013t-.226 1.264M6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>
