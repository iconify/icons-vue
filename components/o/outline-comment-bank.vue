<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr4yj7fak"/><path class="z2l0rtbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-comment-bank" /></template>
<style>
.xr4yj7fak {
  fill: currentColor;
  d: path("M18 14V6h-5v8l2.5-1.5z");
}

.z2l0rtbum {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-2 .9-2 2v18l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 14H6l-2 2V4h16z");
}

</style>
