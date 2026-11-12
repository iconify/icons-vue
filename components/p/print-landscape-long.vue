<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz_indb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-landscape-long" /></template>
<style>
.uz_indb6d {
  fill: currentColor;
  d: path("M4.846 13.366q-.855 0-1.29-.704q-.433-.704-.112-1.462q.477-1.12.847-2.249t.565-1.855q.136-.54.587-.857t1.017-.316h1.31V5h1.922v.923h4.539V5h1.923v.923h2.23q.677 0 1.147.457T20 7.539q0 .655-.347 1.36t-.603 1.292q-.206.467-.441 1.006q-.236.54-.503 1.174q-.218.454-.612.724t-.873.27zM5 14.385h11.621q.977 0 1.628-.602t1.074-1.767L20 10.474v5.91q0 .67-.472 1.143q-.472.472-1.143.472H6.615q-.67 0-1.143-.472Q5 17.056 5 16.385z");
}

</style>
