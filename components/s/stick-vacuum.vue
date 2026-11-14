<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k429v9bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stick-vacuum" /></template>
<style>
.k429v9bea {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.223 2.744q2.543 1.589.954 4.133l-.265.425q-.658 1.054-1.869 1.333l-.006.001q.449 1.146-.463 2.605l-1.06 1.696q-1.384 2.215-3.491 1.297L9.846 17.75H12q2.25 0 2.25 2.25T12 22.25H5q-2.25 0-2.25-2.25T5 17.75h3.082l2.673-4.317q-1.698-1.483-.329-3.674l1.06-1.696q.79-1.264 1.815-1.508q-.322-1.081.522-2.432l.265-.424q.658-1.055 1.869-1.334t2.265.379z");
}

</style>
