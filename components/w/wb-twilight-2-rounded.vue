<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj5d7coof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wb-twilight-2-rounded" /></template>
<style>
.kj5d7coof {
  fill: currentColor;
  d: path("M3 19.5q-.213 0-.356-.144t-.144-.357t.144-.356T3 18.5h18q.213 0 .356.144t.144.357t-.144.356T21 19.5zM6.116 15q.346-2.175 2.008-3.588T12 10t3.876 1.413T17.884 15z");
}

</style>
