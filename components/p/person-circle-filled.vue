<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG2k5gBewP"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="czh1fxb3n"/><path class="x6qximbyl"/></g></mask></defs><circle mask="url(#SVG2k5gBewP)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:person-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.czh1fxb3n {
  fill-rule: evenodd;
  d: path("M9 9a4 4 0 1 0 8 0a4 4 0 0 0-8 0m6 0a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.x6qximbyl {
  d: path("M20 21a1 1 0 1 1-2 0v-2.5c0-2.494-2.206-4.5-4.984-4.5C10.23 14 8 16.013 8 18.5l.002 2.5a1 1 0 1 1-2 0L6 18.5c0-3.64 3.169-6.5 7.016-6.5C16.86 12 20 14.857 20 18.5z");
}

</style>
