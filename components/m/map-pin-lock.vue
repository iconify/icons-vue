<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk9nndofv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-pin-lock" /></template>
<style>
.rk9nndofv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.509 22.067Q3.75 15.342 3.75 9.5q0-3.417 2.416-5.834T12 1.25t5.834 2.416Q20.25 6.083 20.25 9.5q0 5.842-7.759 12.567q-.051.044-.108.078q-.058.034-.121.058q-.063.023-.129.035T12 22.25t-.133-.012t-.129-.035q-.063-.024-.121-.058t-.108-.078M11.25 8.75h1.5V8.5q0-.75-.75-.75t-.75.75zm3 .25v-.5q0-2.25-2.25-2.25T9.75 8.5V9q-1 .5-1 2v.5q0 2.25 2.25 2.25h2q2.25 0 2.25-2.25V11q0-1.5-1-2");
}

</style>
