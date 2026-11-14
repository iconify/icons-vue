<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="grc6u9b2f"/><path class="v5v0xmkhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:monthly-listeners" /></template>
<style>
.grc6u9b2f {
  d: path("M3.5 12.5V10A7.25 7.25 0 0 1 18 10v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v5v0xmkhe {
  d: path("M4.75 10zA2.25 2.25 0 0 1 7 12.25v1a2.25 2.25 0 0 1-2.25 2.25a2.25 2.25 0 0 1-2.25-2.25v-1A2.25 2.25 0 0 1 4.75 10m12.69 5.392q-.336.108-.69.108q-.111 0-.221-.011t-.218-.032t-.214-.054t-.208-.074q-.102-.043-.2-.095q-.097-.052-.189-.113t-.177-.132q-.086-.07-.164-.148t-.148-.164t-.132-.177t-.113-.189t-.095-.2q-.042-.102-.074-.208t-.054-.214t-.032-.218t-.011-.221v-1q0-.111.011-.221t.032-.218t.054-.214t.074-.208q.043-.102.095-.2q.052-.097.113-.189t.132-.177q.07-.086.148-.164t.164-.148t.177-.132t.189-.113t.2-.095q.102-.042.208-.074t.214-.054t.218-.032t.221-.011t.221.011t.218.032q.108.022.214.054t.208.074t.2.095q.097.052.189.113t.177.132t.164.148q.078.078.148.164q.07.085.132.177q.061.092.113.189q.052.098.095.2q.042.102.074.208t.054.214t.032.218t.011.221v1q0 .196-.034.389t-.101.378q-.066.184-.164.354t-.223.321M14.5 21.5l3-3L19 20l2.75-2.75m-2.25 0h2.25v2.25");
}

</style>
