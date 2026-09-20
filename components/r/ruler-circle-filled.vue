<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG07kUTdNm"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="cpop8qckd"/></mask></defs><circle mask="url(#SVG07kUTdNm)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:ruler-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.cpop8qckd {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M4.25 18.392a2 2 0 0 1 0-2.828L15.564 4.25a2 2 0 0 1 2.828 0l3.536 3.536a2 2 0 0 1 0 2.828L10.614 21.928a2 2 0 0 1-2.828 0zm2.121-2.121l-.707.707L9.2 20.513L20.514 9.2l-3.536-3.536l-.707.707l1.355 1.356a1 1 0 0 1-1.414 1.414l-1.355-1.355l-.707.707l.53.53a1 1 0 0 1-1.414 1.414l-.53-.53l-.708.707l1.355 1.355a1 1 0 1 1-1.414 1.414l-1.355-1.355l-.707.707l.53.53a1 1 0 1 1-1.414 1.415l-.53-.53l-.707.707l1.355 1.355a1 1 0 1 1-1.414 1.414z");
}

.ft5dv1b6b {
  fill: none;
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>
