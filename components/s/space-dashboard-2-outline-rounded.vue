<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw2zuacts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:space-dashboard-2-outline-rounded" /></template>
<style>
.bw2zuacts {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm0-1H13.5V5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192m8.885 0h3.885q.23 0 .423-.192t.192-.424V12.5h-4.5zm0-7.5H19V5.616q0-.231-.192-.424T18.384 5H14.5z");
}

</style>
