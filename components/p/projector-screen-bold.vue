<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ozno0vnwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:projector-screen-bold" /></template>
<style>
.ozno0vnwx {
  fill: currentColor;
  d: path("M236 72V48a20 20 0 0 0-20-20H40a20 20 0 0 0-20 20v24a20 20 0 0 0 16 19.6V164h-4a12 12 0 0 0 0 24h84v23.22a24 24 0 1 0 24 0V188h84a12 12 0 0 0 0-24h-4V91.6A20 20 0 0 0 236 72M44 52h168v16H44Zm16 112V92h136v72Z");
}

</style>
