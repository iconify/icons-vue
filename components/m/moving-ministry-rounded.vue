<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t639cbadn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:moving-ministry-rounded" /></template>
<style>
.t639cbadn {
  fill: currentColor;
  d: path("M2.815 20q-.355 0-.585-.232T2 19.192V4.808q0-.343.232-.576T2.808 4h10.461q.344 0 .576.232t.232.576v14.384q0 .344-.232.576t-.576.232H9.923v-4.154h-3.77V20zm2.57-7.308h1.461v-1.461H5.385zm0-3.846h1.461V7.384H5.385zm3.846 3.846h1.461v-1.461H9.231zm0-3.846h1.461V7.384H9.231zm7.144 2.797q.143-.143.356-.143h3.386l-1.246-1.246q-.14-.14-.15-.351t.15-.36q.146-.137.353-.137q.208 0 .342.14l1.888 1.888q.242.243.242.566t-.242.566l-1.888 1.888q-.136.134-.34.14q-.203.006-.349-.14q-.16-.14-.153-.351t.147-.357l1.246-1.246h-3.386q-.213 0-.357-.144t-.143-.357t.143-.356");
}

</style>
