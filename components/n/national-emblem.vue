<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nweue1blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:national-emblem" /></template>
<style>
.nweue1blu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 20c-4-2.25-5.5-7.25-3.25-12.5M15.75 20c4-2.25 5.5-7.25 3.25-12.5M4.4 11.75L3.25 10.5m2 5L3.5 15m3.75 3.5l-1.5.5m13.85-7.25l1.15-1.25m-2 5l1.75-.5m-3.75 3.5l1.5.5M12.14 8.07l1.03 2.31q.14.32.49.35l2.51.27q.35.03.09.27l-1.88 1.68q-.26.24-.19.58l.53 2.47q.07.34-.23.17l-2.19-1.26q-.3-.18-.6 0l-2.19 1.26q-.3.17-.23-.17l.53-2.47q.07-.34-.19-.58l-1.88-1.68q-.26-.24.09-.27l2.51-.27q.35-.03.49-.35l1.03-2.31q.14-.32.28 0");
}

</style>
