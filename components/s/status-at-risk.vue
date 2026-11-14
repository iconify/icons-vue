<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c08dv94ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:status-at-risk" /></template>
<style>
.c08dv94ke {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M14 7.25q0-2-2-2t-2 2v5q0 2 2 2t2-2zm-4 9.5q0 2 2 2t2-2t-2-2t-2 2");
}

</style>
