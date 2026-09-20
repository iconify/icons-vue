<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmte2zyrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-chat-sharp" /></template>
<style>
.mmte2zyrl {
  fill: currentColor;
  d: path("M6 22V2h12v5.923h-7.27V21h2.537l2.308-2.308H18V22zm7.116-4.211v-7.481h7.653v6h-6.173zm-.528-11.703q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22");
}

</style>
