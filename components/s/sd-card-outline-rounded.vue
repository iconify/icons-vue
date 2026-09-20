<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7w5p2rvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sd-card-outline-rounded" /></template>
<style>
.d7w5p2rvo {
  fill: currentColor;
  d: path("M10.434 10.626q.143-.143.143-.357V7.846q0-.213-.143-.356t-.357-.144t-.357.144t-.143.356v2.423q0 .214.143.357t.357.143t.357-.143m2.807 0q.144-.143.144-.357V7.846q0-.213-.144-.356t-.356-.144t-.357.144t-.144.356v2.423q0 .214.144.357q.143.143.357.143q.213 0 .356-.143m2.808 0q.143-.143.143-.357V7.846q0-.213-.143-.356t-.357-.144t-.357.144t-.143.356v2.423q0 .214.143.357t.357.143t.357-.143M6.616 21q-.691 0-1.153-.462T5 19.385V9.095q0-.324.13-.629q.132-.304.349-.522L9.944 3.48q.217-.218.522-.348q.305-.131.628-.131h6.29q.691 0 1.154.463T19 4.615v14.77q0 .69-.462 1.152T17.384 21zm0-1h10.769q.23 0 .423-.192t.192-.424V4.616q0-.231-.192-.424T17.384 4H10.85L6 8.85v10.535q0 .23.192.423t.423.192m0 0H6h12z");
}

</style>
