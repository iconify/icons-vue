<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9u8h44os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wifi-calling-bar-2" /></template>
<style>
.y9u8h44os {
  fill: currentColor;
  d: path("M15.788 10.713Q15.5 10.425 15.5 10t.288-.712T16.5 9t.713.288t.287.712t-.288.713T16.5 11t-.712-.288M14 8.55L12.95 7.5q.725-.725 1.638-1.112T16.5 6t1.913.388T20.05 7.5L19 8.55q-.5-.5-1.137-.775T16.5 7.5t-1.362.275T14 8.55M19.95 21q-3.125 0-6.175-1.362t-5.55-3.863t-3.862-5.55T3 4.05q0-.45.3-.75t.75-.3H8.1q.35 0 .625.238t.325.562l.65 3.5q.05.4-.025.675T9.4 8.45L6.975 10.9q.5.925 1.187 1.787t1.513 1.663q.775.775 1.625 1.438T13.1 17l2.35-2.35q.225-.225.588-.337t.712-.063l3.45.7q.35.1.575.363T21 15.9v4.05q0 .45-.3.75t-.75.3");
}

</style>
