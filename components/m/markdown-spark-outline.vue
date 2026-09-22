<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p57akh95u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-spark-outline" /></template>
<style>
.p57akh95u {
  fill: currentColor;
  d: path("M4 6v6.077v-.194V18zm12 8.692l2.558-2.558l-.608-.632l-1.508 1.488v-2.682h-.884v2.683l-1.508-1.489l-.608.633zm-10.192 0h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884V10q0-.31-.191-.501T11 9.308H6.5q-.31 0-.501.191q-.191.192-.191.501zm12.596-5q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.387-1.359q-.15-.05-.15-.2q0-.175.15-.2q1.39-.362 2.387-1.359t1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.36q.15.024.15.2q0 .15-.15.2q-1.39.36-2.388 1.358q-.997.997-1.358 2.387q-.025.15-.2.15M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h7.302v1H4.616q-.231 0-.424.192T4 6.616v10.769q0 .23.192.423t.423.192h14.77q.23 0 .423-.192t.192-.423v-5.502h1v5.502q0 .69-.462 1.153T19.385 19z");
}

</style>
