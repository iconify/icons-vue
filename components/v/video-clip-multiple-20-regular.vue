<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u3rkyjb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-clip-multiple-20-regular" /></template>
<style>
.u3rkyjb0z {
  fill: currentColor;
  d: path("M7 11.252V6.756a.75.75 0 0 1 1.171-.62l3.61 2.45a.5.5 0 0 1 .001.828l-3.61 2.458A.75.75 0 0 1 7 11.252M2 5.5A2.5 2.5 0 0 1 4.5 3h9A2.5 2.5 0 0 1 16 5.5v7a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 2 12.5zM4.5 4A1.5 1.5 0 0 0 3 5.5v7A1.5 1.5 0 0 0 4.5 14h9a1.5 1.5 0 0 0 1.5-1.5v-7A1.5 1.5 0 0 0 13.5 4zm0 12c.456.607 1.182 1 2 1H14a4 4 0 0 0 4-4V7.5c0-.818-.393-1.544-1-2V13a3 3 0 0 1-3 3z");
}

</style>
