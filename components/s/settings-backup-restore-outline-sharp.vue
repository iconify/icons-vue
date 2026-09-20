<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4iugrbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-backup-restore-outline-sharp" /></template>
<style>
.j4iugrbyg {
  fill: currentColor;
  d: path("M11.962 13q-.402 0-.701-.299t-.3-.701t.3-.701t.7-.299t.702.299t.299.701t-.3.701t-.7.299m0 7q-3.052 0-5.314-1.999T4.031 13h1.011q.408 2.58 2.361 4.29T11.962 19q2.925 0 4.962-2.037T18.962 12t-2.038-4.963T11.962 5q-1.553 0-2.918.656q-1.365.655-2.41 1.805h2.481v1H4.962V4.309h1v2.388q1.16-1.273 2.718-1.984T11.962 4q1.663 0 3.118.626t2.542 1.714t1.714 2.542t.626 3.118t-.626 3.118t-1.714 2.542t-2.542 1.714t-3.118.626");
}

</style>
