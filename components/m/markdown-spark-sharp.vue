<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um46yqbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-spark-sharp" /></template>
<style>
.um46yqbtx {
  fill: currentColor;
  d: path("M5.808 14.692h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884V9.308H5.808zM3 19V5h8.964q-.03.25-.048.5t.013.5q.125 1.785 1.115 3.218t2.514 2.195v1.577l-1.508-1.488l-.608.633L16 14.692l2.621-2.62q.627-.031 1.223-.179q.596-.147 1.156-.399V19zm15.404-9.308q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.387-1.359q-.15-.05-.15-.2q0-.175.15-.2q1.39-.362 2.387-1.359t1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.362 1.39 1.359 2.387t2.387 1.36q.15.024.15.2q0 .15-.15.2q-1.39.36-2.387 1.358q-.997.997-1.36 2.387q-.024.15-.2.15");
}

</style>
