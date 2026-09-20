<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgqa2dbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:save" /></template>
<style>
.cgqa2dbkx {
  fill: currentColor;
  d: path("M20 7.423v10.962q0 .69-.462 1.153T18.384 20H5.616q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h10.961zm-6.587 8.529q.587-.586.587-1.414t-.587-1.413T12 12.539t-1.413.586T10 14.538t.587 1.414t1.413.586t1.414-.586M6.768 9.769h7.423v-3H6.77z");
}

</style>
