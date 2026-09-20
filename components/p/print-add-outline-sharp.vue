<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnd39bc8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:print-add-outline-sharp" /></template>
<style>
.bnd39bc8e {
  fill: currentColor;
  d: path("M4 10h16zm2 11v-4H2V8h20v3.75q-.45-.25-.95-.425t-1.05-.25V10H4v5h2v-2h8.5q-.4.425-.725.925T13.25 15H8v4h5.1q.175.55.425 1.05t.6.95zM16 8V5H8v3H6V3h12v5zm2 13v-3h-3v-2h3v-3h2v3h3v2h-3v3z");
}

</style>
