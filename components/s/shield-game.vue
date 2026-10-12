<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ids4o665f"/><path class="n88fq2bbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shield-game" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ids4o665f {
  d: path("M5.75 3h12.5a1.5 1.5 0 0 1 1.5 1.5V11c0 5-3.5 8.5-7.75 10.25C7.75 19.5 4.25 16 4.25 11V4.5A1.5 1.5 0 0 1 5.75 3");
}

.n88fq2bbe {
  d: path("m12.14 7.57l.75 1.69q.14.32.49.35l1.84.19q.35.04.09.28l-1.38 1.23q-.26.23-.18.58l.38 1.8q.07.34-.23.17l-1.6-.92q-.3-.18-.6 0l-1.6.92q-.3.17-.23-.17l.38-1.8q.08-.35-.18-.58l-1.38-1.23q-.26-.24.09-.28l1.84-.19q.35-.03.49-.35l.75-1.69q.14-.32.28 0");
}

</style>
