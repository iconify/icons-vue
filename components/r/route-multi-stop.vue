<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2ywbkb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:route-multi-stop" /></template>
<style>
.t2ywbkb4b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 4.5q0-3.25 3.25-3.25t3.25 3.25q0 2.85-2.5 3.201v7.838q-.356-.039-.75-.039t-.75.039V7.701q-2.5-.351-2.5-3.201m-.75 15q0 .394.039.75H7.701q-.351 2.5-3.201 2.5q-1.346 0-2.298-.952T1.25 19.5q0-3.25 3.25-3.25q2.85 0 3.201 2.5h7.838q-.039.356-.039.75m1.25 0q0-2.75 2.75-2.75t2.75 2.75t-2.75 2.75t-2.75-2.75m1.5 0q0 1.25 1.25 1.25t1.25-1.25t-1.25-1.25t-1.25 1.25");
}

</style>
