<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft4_pbe6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown" /></template>
<style>
.ft4_pbe6b {
  fill: currentColor;
  d: path("m16 14.692l2.558-2.557l-.608-.633l-1.508 1.489V9.308h-.884v3.683l-1.508-1.489l-.608.633zM4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm1.192-4.308h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884V10q0-.31-.191-.501T11 9.308H6.5q-.31 0-.501.191q-.191.192-.191.501z");
}

</style>
