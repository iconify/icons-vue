<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs8r1-bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-fill" /></template>
<style>
.zs8r1-bfo {
  fill: currentColor;
  d: path("M2 8a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v.382l2.553-1.276c.356-.181.75-.274 1.149-.273C20.924 6.836 22 7.735 22 9v6c0 1.265-1.076 2.164-2.298 2.167a2.5 2.5 0 0 1-1.149-.273L16 15.618V16a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm14 5.382l3.447 1.724a.6.6 0 0 0 .251.061c.093 0 .302-.044.302-.167V9c0-.123-.209-.167-.302-.167a.6.6 0 0 0-.251.061L16 10.618Z");
}

</style>
