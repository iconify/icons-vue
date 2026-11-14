<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adruuiy8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:object-storage" /></template>
<style>
.adruuiy8j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 11q.001-3.831 2.71-6.539T12 1.753t6.54 2.708T21.25 11q0 .069-.012.136l-.001.004v.001l-2 10.499q-.012.064-.035.125t-.056.117t-.076.105t-.092.091q-.05.041-.106.073q-.057.033-.118.055t-.125.033t-.129.011h-13q-.065 0-.129-.011t-.125-.033t-.118-.055t-.106-.073q-.05-.042-.092-.091q-.043-.049-.076-.105t-.056-.117t-.035-.125l-2-10.499v-.001q-.013-.069-.013-.14m1.532-.75h3.044q-.076-.337-.076-.75v-1q0-2.25 2.25-2.25h1q.951 0 1.5.402q.549-.402 1.5-.402h1q2.25 0 2.25 2.25v1q0 .413-.076.75h3.044q-.239-2.729-2.239-4.728Q15.209 3.253 12 3.253T6.521 5.522q-2 1.999-2.239 4.728");
}

</style>
