<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8vgmfj9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:picture-in-picture-large-outline-rounded" /></template>
<style>
.n8vgmfj9c {
  fill: currentColor;
  d: path("M6.73 15.616q-.342 0-.575-.233t-.232-.575V6.73q0-.343.232-.576t.576-.232h10.077q.343 0 .575.232t.233.576v8.077q0 .343-.233.575t-.575.233zM3.5 19q-.213 0-.356-.144T3 18.499t.144-.356T3.5 18h15.885q.23 0 .423-.192t.192-.424V5.5q0-.213.144-.356T20.501 5t.356.144T21 5.5v11.885q0 .69-.462 1.153T19.385 19z");
}

</style>
