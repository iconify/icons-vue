<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1tv0u0om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:monitor-heart-outline-rounded" /></template>
<style>
.i1tv0u0om {
  fill: currentColor;
  d: path("M3 6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616V9q0 .213-.144.356t-.357.144t-.356-.144T20 9V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616V9q0 .213-.144.356t-.357.144t-.356-.144T3 9zM4.616 19q-.691 0-1.153-.462T3 17.384V15q0-.213.144-.356t.357-.144t.356.144T4 15v2.385q0 .23.192.423t.423.192h14.77q.23 0 .423-.192t.192-.424V15q0-.213.144-.356t.357-.144t.356.144T21 15v2.385q0 .69-.462 1.152T19.385 19zm5.651-2.57q.127-.07.19-.21L14 9.134l1.542 3.084q.064.14.191.21T16 12.5h4.5q.213 0 .356-.144t.144-.357t-.144-.356t-.356-.143h-4.183l-1.86-3.72q-.059-.126-.178-.178q-.12-.052-.27-.052t-.276.052t-.19.179L10 14.866L8.458 11.78q-.064-.14-.191-.21T8 11.5H3.5q-.213 0-.356.144T3 12.001t.144.356t.356.143h4.183l1.86 3.72q.063.14.19.21t.268.07t.266-.07M12 12");
}

</style>
