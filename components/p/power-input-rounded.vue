<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg5islipn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:power-input-rounded" /></template>
<style>
.sg5islipn {
  fill: currentColor;
  d: path("M3.5 14.5q-.213 0-.356-.144T3 13.999t.144-.356t.356-.143h3.058q.212 0 .356.144t.144.357t-.144.356t-.356.143zm6.442 0q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143h3.116q.212 0 .356.144t.144.357t-.144.356t-.356.143zm6.5 0q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143H19.5q.213 0 .356.144t.144.357t-.144.356t-.356.143zM3.5 10.5q-.213 0-.356-.144T3 9.999t.144-.356T3.5 9.5h16q.213 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
