<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftzhrcb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:videogame-asset-sharp" /></template>
<style>
.ftzhrcb6b {
  fill: currentColor;
  d: path("M2 18V6h20v12zm5-3h2v-2h2v-2H9V9H7v2H5v2h2zm8.563-.437Q16 14.125 16 13.5t-.437-1.062T14.5 12t-1.062.438T13 13.5t.438 1.063T14.5 15t1.063-.437m3-3Q19 11.125 19 10.5t-.437-1.062T17.5 9t-1.062.438T16 10.5t.438 1.063T17.5 12t1.063-.437");
}

</style>
