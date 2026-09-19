<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfrw_dbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-calendar-today" /></template>
<style>
.bfrw_dbmt {
  fill: currentColor;
  d: path("M22 3h-3V1h-2v2H7V1H5v2H2v20h20zm-2 18H4V8h16z");
}

</style>
