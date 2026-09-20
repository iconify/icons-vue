<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="lq4xfdcfn"/><path class="kxtxo-z3x"/><path class="t7jj5pbcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:target-32-filled" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kxtxo-z3x {
  d: path("M16 8.75a7.25 7.25 0 1 0 0 14.5a7.25 7.25 0 0 0 0-14.5M11.25 16a4.75 4.75 0 1 1 9.5 0a4.75 4.75 0 0 1-9.5 0");
}

.lq4xfdcfn {
  d: path("M16 13.75a2.25 2.25 0 1 0 0 4.5a2.25 2.25 0 0 0 0-4.5");
}

.t7jj5pbcv {
  d: path("M16.001 3.75C9.235 3.75 3.75 9.235 3.75 16.001s5.485 12.252 12.251 12.252S28.253 22.767 28.253 16S22.767 3.75 16 3.75M6.25 16.001c0-5.385 4.366-9.751 9.751-9.751c5.386 0 9.752 4.366 9.752 9.751c0 5.386-4.366 9.752-9.752 9.752c-5.385 0-9.751-4.366-9.751-9.752");
}

</style>
