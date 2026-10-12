<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aib-b3x2k"/><circle class="ie50qbcyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:saw" /></template>
<style>
.aib-b3x2k {
  d: path("m19.61 12.28l1.01 2.5q.11.28-.19.31l-1.37.13q-.3.03-.32.33l-.18 2.69q-.02.3-.3.2l-1.3-.48q-.28-.1-.43.16l-1.32 2.35q-.15.26-.36.05l-.97-1q-.21-.21-.46-.04l-2.21 1.54q-.25.17-.35-.11l-.43-1.32q-.1-.28-.4-.23l-2.65.42q-.3.05-.26-.25l.16-1.37q.04-.3-.25-.39l-2.57-.76q-.29-.09-.13-.34l.75-1.17q.16-.25-.06-.45l-1.99-1.81q-.22-.2.04-.36l1.17-.72q.26-.16.15-.44l-1.01-2.5q-.11-.28.19-.31l1.37-.13q.3-.03.32-.33l.18-2.69q.02-.3.3-.2l1.3.48q.28.1.43-.16l1.32-2.35q.15-.26.36-.05l.97 1q.21.21.46.04l2.21-1.54q.25-.17.35.11l.43 1.32q.1.28.4.23l2.65-.42q.3-.05.26.25l-.16 1.37q-.04.3.25.39l2.57.76q.29.09.13.34l-.75 1.17q-.16.25.06.45l1.99 1.81q.22.2-.04.36l-1.17.72q-.26.16-.15.44");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ie50qbcyb {
  cx: 12px;
  cy: 12px;
  r: 3.25px;
}

</style>
