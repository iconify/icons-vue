<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut5cefb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:transition-chop-outline-rounded" /></template>
<style>
.ut5cefb9v {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zM4 17.185l11.589-3.058q.25-.077.375-.289t.067-.461L14.119 6H4.616q-.231 0-.424.192T4 6.616zm.817.815h14.568q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6h-4.23L17 13.133q.162.646-.164 1.233t-.972.75zM4 6");
}

</style>
