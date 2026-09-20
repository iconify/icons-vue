<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4m-kz1ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:volume-down" /></template>
<style>
.i4m-kz1ho {
  fill: currentColor;
  d: path("M6 14v-4h3.423L13 6.423v11.154L9.423 14zm9.77 1.308V8.642q.817.525 1.273 1.424q.457.898.457 1.934t-.457 1.91t-1.274 1.398");
}

</style>
