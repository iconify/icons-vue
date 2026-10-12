<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="c-5d6obui"/><path class="tb6q2fbtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:visual-alert" /></template>
<style>
.c-5d6obui {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.41 3.38l1.19 1.81q.41.63 1.11.36l2.03-.77q.7-.26.66.49l-.1 2.16q-.04.75.68.95l2.09.56q.73.2.26.79l-1.36 1.69q-.47.58 0 1.16l1.36 1.69q.47.59-.26.79l-2.09.56q-.72.2-.68.95l.1 2.16q.04.75-.66.49l-2.03-.77q-.7-.27-1.11.36l-1.19 1.81q-.41.63-.82 0l-1.19-1.81q-.41-.63-1.11-.36l-2.03.77q-.7.26-.66-.49l.1-2.16q.04-.75-.68-.95l-2.09-.56q-.73-.2-.26-.79l1.36-1.69q.47-.58 0-1.16L3.67 9.73q-.47-.59.26-.79l2.09-.56q.72-.2.68-.95l-.1-2.16q-.04-.75.66-.49l2.03.77q.7.27 1.11-.36l1.19-1.81q.41-.63.82 0M12 8v4.5");
}

.tb6q2fbtf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
