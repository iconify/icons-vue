<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y36z4fbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:member-gold" /></template>
<style>
.y36z4fbtb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 1.75h.88q1.306 0 1.953 1.134l.568.994q.116.202.349.202t.349-.202l.568-.994q.647-1.134 1.953-1.134h.88q1.023 0 1.575.862t.123 1.791l-1.865 4.04q-.099.215-.221.394q.85.473 1.589 1.212Q19.001 12.1 19 15q.001 2.9-2.049 4.951Q14.9 22.002 12 22.002t-4.951-2.051T5 15q-.001-2.9 2.049-4.951q.739-.739 1.589-1.212q-.122-.179-.221-.394l-1.865-4.04q-.429-.929.123-1.791T8.25 1.75M8 16q0 2.25 2.25 2.25h3.5Q16 18.25 16 16v-1.848q-.001-.82-.746-1.163q-.745-.342-1.367.192q-.093.079-.213.062q-.121-.016-.19-.119l-.11-.165q-.49-.736-1.374-.736t-1.373.735l-.112.167q-.068.102-.189.118q-.12.017-.213-.062q-.622-.534-1.367-.192q-.745.343-.746 1.163z");
}

</style>
