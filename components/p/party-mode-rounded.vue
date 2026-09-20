<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpjkabceb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:party-mode-rounded" /></template>
<style>
.fpjkabceb {
  fill: currentColor;
  d: path("M4.616 20q-.691 0-1.153-.462T3 18.384V7.616q0-.691.463-1.153T4.615 6h2.958l1.366-1.485q.217-.242.527-.379Q9.777 4 10.125 4h3.75q.348 0 .659.137q.31.136.527.379L16.428 6h2.958q.69 0 1.153.463T21 7.616v10.769q0 .69-.462 1.153T19.385 20zm7.39-3.27q1.55 0 2.637-1.089q1.088-1.089 1.088-2.641q0-.213-.143-.357t-.357-.143t-.357.143t-.143.357q0 1.125-.771 1.928q-.772.803-1.902.803h-1.344q-.255 0-.316.25t.168.39q.324.193.687.276t.753.084m-2.874-3.374q.143-.143.143-.357q0-1.125.771-1.928t1.902-.803h1.344q.254 0 .316-.25t-.167-.39q-.325-.192-.688-.276T12 9.269q-1.55 0-2.637 1.09Q8.275 11.448 8.275 13q0 .214.143.357t.357.143t.357-.143");
}

</style>
