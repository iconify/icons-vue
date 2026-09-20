<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsojpnb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:monitor-weight-loss-sharp" /></template>
<style>
.wsojpnb1y {
  fill: currentColor;
  d: path("M15.5 18.5h7v1h-7zm-1.644-7.649q.76-.764.76-1.856q0-1.091-.765-1.85q-.764-.76-1.856-.76q-1.091 0-1.85.764t-.76 1.856t.764 1.85t1.856.76q1.091 0 1.85-.764M4 20V4h16v9.235q-.25-.06-.5-.09t-.5-.03q-2.452 0-4.168 1.717T13.116 19q0 .25.03.5t.088.5zm6-10.5v-1h1v1zm1.5 0v-1h1v1zm1.5 0v-1h1v1z");
}

</style>
