<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k926wygut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:video-template-rounded" /></template>
<style>
.k926wygut {
  fill: currentColor;
  d: path("M5.558 22q-.69 0-1.153-.462t-.463-1.153v-.75h16.116v.75q0 .69-.463 1.153T18.442 22zm-.942-4.75q-.691 0-1.153-.462T3 15.635v-7.27q0-.69.463-1.152t1.152-.463h14.77q.69 0 1.152.463T21 8.366v7.269q0 .69-.463 1.153t-1.152.462zM3.942 4.365v-.75q0-.69.463-1.153T5.558 2h12.884q.69 0 1.153.463t.463 1.152v.75zm6.385 10.25L14.673 12l-4.346-2.615z");
}

</style>
