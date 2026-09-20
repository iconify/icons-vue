<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anjvf1bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-wifi-off" /></template>
<style>
.anjvf1bvl {
  fill: currentColor;
  d: path("M17.214 14.364L8.258 5.433q.933-.223 1.865-.328Q11.056 5 12 5q2.939 0 5.666 1.018T22.577 9zm3.069 7.34l-5.202-5.208L12 19.577L1.423 9q.858-.742 1.778-1.36q.92-.617 1.928-1.09L2.27 3.692l.713-.713L20.997 20.99z");
}

</style>
