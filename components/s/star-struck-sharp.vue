<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="m3bdhacpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:star-struck-sharp" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.m3bdhacpt {
  d: path("m8.91 7.62l.42 1l.15.37l.4.03l1.09.1l.4.03l-.31.26l-.82.71l-.3.27l.09.39l.25 1.06l.09.38l-.35-.2l-.93-.56l-.34-.21l-.34.21l-.93.56l-.35.2l.09-.38l.25-1.06l.09-.39l-.3-.27l-.82-.71l-.31-.26l.4-.03l1.09-.1l.4-.03l.15-.37l.42-1l.16-.37zm6.5 0l.42 1l.15.37l.4.03l1.09.1l.4.03l-.31.26l-.82.71l-.3.27l.09.39l.25 1.06l.09.38l-.35-.2l-.93-.56l-.34-.21l-.34.21l-.93.56l-.35.2l.09-.38l.25-1.06l.09-.39l-.3-.27l-.82-.71l-.31-.26l.4-.03l1.09-.1l.4-.03l.15-.37l.42-1l.16-.37zM8.75 15h6.5a3.25 3.25 0 0 1-6.5 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
