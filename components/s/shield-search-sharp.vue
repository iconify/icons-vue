<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrhxmib0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-search-sharp" /></template>
<style>
.wrhxmib0r {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 5.3088L20 15.778L18.612 17.5729C17.4097 19.1277 15.5033 20.8703 12.8298 21.8525C12.2945 22.0492 11.7055 22.0492 11.1702 21.8525C8.4967 20.8703 6.5903 19.1277 5.388 17.5729L4 15.7778L4 5.3088L5.1825 5.1684C7.8303 4.8543 9.8295 3.5322 11.0242 2.3731C11.537 1.8756 12.463 1.8756 12.9758 2.3731C14.1705 3.5322 16.1697 4.8543 18.8175 5.1684L20 5.3088ZM14 11C14 12.3807 12.8807 13.5 11.5 13.5C10.1193 13.5 9 12.3807 9 11C9 9.6193 10.1193 8.5 11.5 8.5C12.8807 8.5 14 9.6193 14 11ZM13.2678 12.7678L15.2929 14.7929");
}

</style>
