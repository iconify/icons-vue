<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-t0prnfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-chart-outline-rounded" /></template>
<style>
.v-t0prnfm {
  fill: currentColor;
  d: path("M18.385 20H5.615q-.69 0-1.152-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20M5 8.5h14V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616zm2.885 1H5v8.885q0 .23.192.423t.423.192h2.27zm8.23 0V19h2.27q.23 0 .423-.192t.192-.424V9.5zm-1 0h-6.23V19h6.23z");
}

</style>
