<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eog6oy8hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:monitor-weight" /></template>
<style>
.eog6oy8hx {
  fill: currentColor;
  d: path("M12.005 11.616q1.091 0 1.85-.765q.76-.764.76-1.856q0-1.091-.764-1.85t-1.856-.76t-1.85.764t-.76 1.856t.764 1.85t1.856.76M10.15 9.35Q10 9.2 10 9t.15-.35t.35-.15t.35.15T11 9t-.15.35t-.35.15t-.35-.15m1.5 0Q11.5 9.2 11.5 9t.15-.35t.35-.15t.35.15t.15.35t-.15.35t-.35.15t-.35-.15m1.5 0Q13 9.2 13 9t.15-.35t.35-.15t.35.15T14 9t-.15.35t-.35.15t-.35-.15M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
