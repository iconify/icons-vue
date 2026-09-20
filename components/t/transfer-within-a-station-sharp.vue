<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq1yfnuqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:transfer-within-a-station-sharp" /></template>
<style>
.sq1yfnuqe {
  fill: currentColor;
  d: path("m3.558 22.5l2.8-14.446l-2.954 1.219V12.5h-1V8.608l4.569-1.9q.648-.281 1.244-.159t.964.72l.98 1.581q.637 1.037 1.76 1.766q1.121.73 2.483.846v1q-1.4-.096-2.809-.88T9.154 9.135l-.889 4.519l2.139 2.077V22.5h-1v-5.673l-2.908-2.789L4.581 22.5zM8.203 4.701q-.492-.492-.492-1.201t.492-1.201t1.2-.491t1.202.491t.491 1.201t-.491 1.201t-1.201.491t-1.201-.491m11.2 17.876l-.626-.627l1.008-1.008h-5.573v-.884h5.573l-1.008-1.008l.627-.627L21.48 20.5zm-3-4.25l-2.076-2.077l2.077-2.077l.627.627l-1.008 1.008h5.573v.884h-5.573l1.008 1.008z");
}

</style>
