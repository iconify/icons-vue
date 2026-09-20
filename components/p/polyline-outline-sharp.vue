<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2mrf2btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:polyline-outline-sharp" /></template>
<style>
.z2mrf2btb {
  fill: currentColor;
  d: path("M15.5 21.5v-2.308L8.116 15.5H3.5v-5h4.03l2.97-3.408V2.5h5v5h-4.03L8.5 10.908v3.65l7 3.5V16.5h5v5zm-4-15h3v-3h-3zm-7 8h3v-3h-3zm12 6h3v-3h-3zM18 19");
}

</style>
