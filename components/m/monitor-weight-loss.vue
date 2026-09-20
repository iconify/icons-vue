<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt5ri2bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:monitor-weight-loss" /></template>
<style>
.mt5ri2bom {
  fill: currentColor;
  d: path("M15.5 19.5v-1h7v1zm-1.644-8.649q.76-.764.76-1.856q0-1.091-.765-1.85q-.764-.76-1.856-.76q-1.091 0-1.85.764t-.76 1.856t.764 1.85t1.856.76q1.091 0 1.85-.764M10.15 9.35Q10 9.2 10 9t.15-.35t.35-.15t.35.15T11 9t-.15.35t-.35.15t-.35-.15m1.5 0Q11.5 9.2 11.5 9t.15-.35t.35-.15t.35.15t.15.35t-.15.35t-.35.15t-.35-.15m1.5 0Q13 9.2 13 9t.15-.35t.35-.15t.35.15T14 9t-.15.35t-.35.15t-.35-.15M5.616 20q-.667 0-1.141-.475T4 18.386V5.615q0-.666.475-1.14T5.615 4h12.77q.666 0 1.14.475T20 5.615v7.62q-.25-.06-.5-.09t-.5-.03q-2.452 0-4.168 1.717T13.116 19q0 .25.03.5t.088.5z");
}

</style>
