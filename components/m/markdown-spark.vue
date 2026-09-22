<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ook0lrb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-spark" /></template>
<style>
.ook0lrb4w {
  fill: currentColor;
  d: path("M5.808 14.692h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884V10q0-.31-.191-.501T11 9.308H6.5q-.31 0-.501.191q-.191.192-.191.501zM4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h7.349q-.03.25-.048.5t.013.5q.125 1.785 1.115 3.218t2.514 2.195v1.577l-1.508-1.488l-.608.633L16 14.692l2.621-2.62q.627-.031 1.223-.179q.596-.147 1.156-.399v5.89q0 .691-.462 1.154T19.385 19zm13.788-9.308q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.387-1.359q-.15-.05-.15-.2q0-.175.15-.2q1.39-.362 2.387-1.359t1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.36q.15.024.15.2q0 .15-.15.2q-1.39.36-2.388 1.358q-.997.997-1.358 2.387q-.025.15-.2.15");
}

</style>
