<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9u66cb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-spark-outline-rounded" /></template>
<style>
.j9u66cb4x {
  fill: currentColor;
  d: path("m12 11l7.692-5H4.308zm-7.384 8q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v5.196q0 .213-.143.356t-.357.144t-.357-.144t-.143-.356V6.904l-7.123 4.638q-.404.262-.877.262t-.877-.262L4 6.904v10.48q0 .27.173.443t.443.173h6.813q.213 0 .357.143t.143.357t-.143.357t-.357.143zm13.788 3.5q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.387-1.36q-.15-.05-.15-.2q0-.174.15-.2q1.39-.36 2.387-1.358q.997-.997 1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.359q.15.025.15.2q0 .15-.15.2q-1.39.362-2.388 1.359t-1.358 2.387q-.025.15-.2.15");
}

</style>
