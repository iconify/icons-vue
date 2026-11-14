<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqg4ttb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-layer-weather" /></template>
<style>
.nqg4ttb9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.891 6.688q-.104-.138-.224-.263t-.253-.235t-.279-.205q-.145-.094-.3-.172t-.318-.135q-.163-.059-.331-.099q-.169-.039-.341-.059T8.5 5.5q-.147 0-.294.014t-.291.044q-.145.028-.286.071t-.277.099q-.136.057-.266.126q-.13.07-.253.152q-.122.081-.236.175t-.218.198t-.198.218t-.175.236q-.082.123-.152.253t-.126.266t-.099.277t-.071.286q-.029.144-.044.291T5.5 8.5q0 .282.053.56q.052.277.156.54q.103.263.254.501q.151.239.343.446M8.5 2.75h.01M2.75 8.5h.01m1.74-4h.01m7.99 0h.01M8 20.5h9.75a3.75 3.75 0 0 0-.25-7.5a4.5 4.5 0 0 0-9 1.5a3 3 0 0 0-.5 6");
}

</style>
