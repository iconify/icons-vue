<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g717scbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:video-frame-copy" /></template>
<style>
.g717scbmi {
  fill: currentColor;
  d: path("M3.616 19.77q-.672 0-1.144-.473Q2 18.825 2 18.154V8.077h1v10.077q0 .269.173.442t.443.173H18v1zM21 8V5.616q0-.231-.192-.424T20.385 5H18V4h2.385q.69 0 1.152.463T22 5.616V8zM5 8V5.616q0-.691.463-1.153T6.616 4H9v1H6.616q-.231 0-.424.192T6 5.616V8zm13 8.77v-1h2.385q.23 0 .423-.193q.192-.192.192-.423v-2.385h1v2.385q0 .69-.462 1.153t-1.153.462zm-11.385 0q-.69 0-1.153-.463T5 15.154v-2.385h1v2.385q0 .23.192.423t.423.192H9v1zm5.577-3.309l4.86-3.077l-4.86-3.076z");
}

</style>
