<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt2ni3b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:weather-mix-sharp" /></template>
<style>
.xt2ni3b1m {
  fill: currentColor;
  d: path("M11.438 22.575Q11 22.15 11 21.525q0-.3.113-.575t.337-.475l1.05-.975l1.05.975q.225.2.338.475t.112.575q0 .625-.437 1.05T12.5 23t-1.062-.425M9.05 21.5L8 20.45l2.95-2.95L12 18.55zM15.5 20L14 18.5l1.5-1.5l1.5 1.5zm-9 0L5 18.5L6.5 17L8 18.5zm1-4q-2.275 0-3.887-1.612T2 10.5q0-2.075 1.375-3.625t3.4-1.825q.8-1.425 2.188-2.238T12 2q2.25 0 3.913 1.438t2.012 3.587q1.725.15 2.9 1.425T22 11.5q0 1.875-1.312 3.188T17.5 16z");
}

</style>
