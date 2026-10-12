<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kgqoogbyf"/><path class="wa2hfqb7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:maple-leaf-flag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kgqoogbyf {
  width: 18.5px;
  height: 14px;
  x: 2.75px;
  y: 5px;
  rx: 1.25px;
}

.wa2hfqb7b {
  d: path("M5.75 5.75v12.5m12.5-12.5v12.5m-6.14-9.03l.62 1.23q.11.23.33.11l.61-.3q.22-.11.18.14l-.24 1.6q-.04.25.16.1l.87-.64q.2-.16.41-.03l.62.38q.21.13.1.35l-.4.81q-.12.23.04.42l.11.13q.16.2-.07.31l-1.65.83q-.23.11-.16.35l.08.25q.07.24-.18.19l-1.3-.31q-.24-.05-.48 0l-1.3.31q-.25.05-.18-.19l.08-.25q.07-.24-.16-.35l-1.65-.83q-.23-.11-.07-.31l.11-.13q.16-.19.04-.42l-.4-.81q-.11-.22.1-.35l.62-.38q.21-.13.41.03l.87.64q.2.15.16-.1l-.24-1.6q-.04-.25.18-.14l.61.3q.22.12.33-.11l.62-1.23q.11-.22.22 0");
}

</style>
