<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy9ou_g3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:uppercase-outline-rounded" /></template>
<style>
.dy9ou_g3m {
  fill: currentColor;
  d: path("M16.682 17.434q-.143-.144-.143-.357v-6.546l-1.747 1.746q-.14.14-.344.15t-.364-.15t-.159-.354t.16-.354l2.388-2.388q.243-.242.566-.242t.565.242l2.388 2.388q.14.14.15.345q.01.203-.15.363t-.354.16t-.354-.16l-1.746-1.746v6.546q0 .214-.143.357t-.356.143t-.357-.143M6.246 14.617l-.915 2.635q-.062.16-.181.242t-.279.083q-.263 0-.41-.215q-.147-.214-.05-.466l3.374-9.219q.061-.16.196-.245q.134-.086.294-.086h.367q.16 0 .295.086t.196.245l3.411 9.225q.098.252-.059.464q-.156.211-.414.211q-.16 0-.291-.095t-.193-.255l-.91-2.61zm.344-.907h3.756L8.49 8.487h-.06z");
}

</style>
