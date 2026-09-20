<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nik2-7snr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:safety-check-rounded" /></template>
<style>
.nik2-7snr {
  fill: currentColor;
  d: path("M14.836 14.855Q16 13.69 16 12.019t-1.164-2.835T12 8.019T9.165 9.184T8 12.019t1.165 2.836T12 16.019t2.836-1.164m-2.452-2.997l1.539 1.538q.111.112.121.263t-.121.283t-.273.131t-.273-.13l-1.52-1.52q-.13-.13-.186-.27t-.055-.301V9.519q0-.161.111-.273q.112-.112.273-.112t.273.112t.112.273zm-.67 8.96q-.15-.026-.281-.076q-2.952-1.125-4.692-3.816T5 11.1V6.817q0-.51.295-.923t.755-.6l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.46.187.755.6t.295.923V11.1q0 3.135-1.74 5.826t-4.693 3.816q-.13.05-.28.075t-.287.025t-.287-.025");
}

</style>
