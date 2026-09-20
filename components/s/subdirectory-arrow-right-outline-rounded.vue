<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y39q38gvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subdirectory-arrow-right-outline-rounded" /></template>
<style>
.y39q38gvh {
  fill: currentColor;
  d: path("M13.49 19.277q.01-.198.156-.344L17.08 15.5H7.616q-.672 0-1.144-.472T6 13.885V5.5q0-.213.143-.357T6.5 5t.357.143T7 5.5v8.385q0 .269.173.442t.443.173h9.463l-3.438-3.438q-.166-.166-.163-.354q.003-.189.163-.354q.165-.165.363-.159t.344.153l4.087 4.087q.13.13.183.267t.053.298t-.053.298t-.183.268L14.36 19.64q-.166.166-.357.166t-.357-.166q-.165-.165-.155-.363");
}

</style>
