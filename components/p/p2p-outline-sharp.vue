<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqrjhzkob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:p2p-outline-sharp" /></template>
<style>
.kqrjhzkob {
  fill: currentColor;
  d: path("M13.192 21v-5.712h1V20H21V5.885h-6.808V8.73h-1V4.885H22V21zM2 19.116V3h8.808v5.73h-1V4H3v14.116h6.808v-2.828h1v3.827zM18.066 8.449q.184-.186.184-.47t-.186-.468t-.47-.184t-.468.186t-.184.47t.186.468t.47.184t.468-.186M6.874 6.564q.184-.186.184-.47q0-.285-.186-.468t-.47-.184t-.468.186t-.184.47q0 .285.186.468t.47.184q.284 0 .468-.186M3 18.116V4zM21 20V5.885zM7.634 12.52q-.211-.209-.211-.52t.21-.52t.52-.21t.521.21q.21.209.21.52t-.21.52t-.52.21t-.52-.21m3.846 0q-.21-.209-.21-.52t.21-.52q.209-.21.52-.21t.52.21q.21.209.21.52t-.21.52q-.209.21-.52.21t-.52-.21m3.827 0q-.21-.209-.21-.52t.209-.52t.52-.21t.521.21q.21.209.21.52t-.21.52q-.209.21-.52.21q-.31 0-.52-.21");
}

</style>
