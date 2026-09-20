<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex1p8jb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pen-size-1-outline-sharp" /></template>
<style>
.ex1p8jb2q {
  fill: currentColor;
  d: path("M5.187 18.814q-.13-.13-.13-.31t.13-.317l13-13q.136-.13.317-.13t.31.13q.128.129.128.31t-.128.317l-13 13q-.136.128-.317.128t-.31-.128");
}

</style>
