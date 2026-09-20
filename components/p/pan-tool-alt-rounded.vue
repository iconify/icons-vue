<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvgx9d28g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pan-tool-alt-rounded" /></template>
<style>
.bvgx9d28g {
  fill: currentColor;
  d: path("M10.45 20q-.559 0-1.066-.24q-.507-.239-.881-.693l-5.7-6.892l.497-.433q.264-.244.625-.252q.362-.007.656.176L8 13.786V3.482q0-.213.144-.356t.357-.144t.356.144T9 3.48v8.058h2.673V6.5q0-.213.144-.356T12.174 6t.356.144t.143.356v5.039h2.673V7.692q0-.212.144-.356t.357-.144t.356.144t.143.356v3.847H19V9.5q0-.213.144-.356T19.501 9t.356.144T20 9.5v7q0 1.458-1.021 2.479T16.5 20z");
}

</style>
