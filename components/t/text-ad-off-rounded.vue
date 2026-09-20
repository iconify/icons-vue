<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4t3gr2va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-ad-off-rounded" /></template>
<style>
.n4t3gr2va {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5H5l1 1H4.573L2.234 3.661q-.145-.146-.155-.347t.156-.366t.356-.165q.192 0 .357.165l18.516 18.516q.146.146.155.344t-.155.363t-.357.165t-.357-.165L17.573 19zm10.696-6.5h2.457q.214 0 .357-.143t.143-.357t-.143-.357t-.357-.143h-3.457l-2.385-2.384H14q.214 0 .357-.144q.143-.143.143-.356q0-.214-.143-.357T14 8.116h-3.073L9.184 6.373q-.378-.379-.173-.876T9.756 5h9.629q.69 0 1.153.463T21 6.616v9.628q0 .54-.497.746q-.497.204-.876-.174zm-9.438 3.241q.143.144.357.144h8.227l-1-1H6.23q-.214 0-.357.143t-.143.357t.143.356m0-3.384q.143.143.357.143h4.842l-1-1H6.231q-.214 0-.357.143T5.731 12t.143.357m0-4.098q.143-.144.357-.144h.458l1 1H6.23q-.214 0-.357-.143t-.143-.357t.143-.356");
}

</style>
