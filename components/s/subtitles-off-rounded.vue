<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv-dopazn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subtitles-off-rounded" /></template>
<style>
.sv-dopazn {
  fill: currentColor;
  d: path("M7.434 11.703q.143-.143.143-.357q0-.213-.143-.356t-.357-.144t-.357.144t-.143.356t.143.357t.357.143t.357-.143M21 6.616v9.782q0 .54-.497.745t-.876-.174l-5.123-5.123h2.419q.214 0 .357-.143t.143-.357t-.143-.356t-.357-.144h-3.42L9.032 6.373q-.379-.379-.174-.876T9.602 5h9.783q.69 0 1.153.463T21 6.616M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h.193l6.769 6.77h-1.415L2.735 4.341q-.14-.14-.15-.344t.15-.364t.354-.159t.353.16l16.27 16.269q.14.14.153.341t-.153.366q-.16.16-.354.16t-.354-.16L17.38 19zm8.188-4.577H7.077q-.213 0-.357.143t-.143.357t.143.357t.357.143h6.727z");
}

</style>
