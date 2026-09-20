<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGnnMIceys"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="sl7cqbj3n"/></mask></defs><circle mask="url(#SVGnnMIceys)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:triangle-up-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.sl7cqbj3n {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M13 10.002L8.963 17h8.074zm.866-2.5a1 1 0 0 0-1.732 0L6.365 17.5a1 1 0 0 0 .866 1.5H18.77a1 1 0 0 0 .866-1.5z");
}

</style>
