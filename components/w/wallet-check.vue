<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hu9cmz9-z"/><path class="w3es5da5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wallet-check" /></template>
<style>
.hu9cmz9-z {
  d: path("M11.3 17.5H2.5V4h19v8.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w3es5da5t {
  d: path("M21.5 8h-4q-.111 0-.221.011t-.218.032t-.214.054t-.208.074q-.102.043-.2.095q-.097.052-.189.113t-.177.132t-.164.148t-.148.164q-.07.085-.132.177q-.061.092-.113.189q-.052.098-.095.2q-.042.102-.074.208t-.054.214t-.032.218t-.011.221t.011.221t.032.218q.022.108.054.214t.074.208t.095.2q.052.097.113.189t.132.177q.07.086.148.164t.164.148t.177.132t.189.113t.2.095q.102.042.208.074t.214.054t.218.032t.221.011h2.836M14.75 18l2 2L21 15.75");
}

</style>
