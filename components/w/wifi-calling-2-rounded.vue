<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t282hobdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wifi-calling-2-rounded" /></template>
<style>
.t282hobdj {
  fill: currentColor;
  d: path("M15.788 10.713Q15.5 10.425 15.5 10t.288-.712T16.5 9t.713.288t.287.712t-.288.713T16.5 11t-.712-.288m-.3-3.062q-.488.15-.913.425q-.275.175-.587.163t-.513-.213q-.225-.225-.212-.525t.262-.5q.65-.5 1.413-.75T16.5 6t1.563.25t1.412.75q.25.2.263.5t-.213.525q-.2.2-.512.213t-.588-.163Q18 7.8 17.512 7.65T16.5 7.5t-1.012.15M19.95 21q-3.125 0-6.175-1.362t-5.55-3.863t-3.862-5.55T3 4.05q0-.45.3-.75t.75-.3H8.1q.35 0 .625.238t.325.562l.65 3.5q.05.4-.025.675T9.4 8.45L6.975 10.9q.5.925 1.187 1.787t1.513 1.663q.775.775 1.625 1.438T13.1 17l2.35-2.35q.225-.225.588-.337t.712-.063l3.45.7q.35.1.575.363T21 15.9v4.05q0 .45-.3.75t-.75.3");
}

</style>
