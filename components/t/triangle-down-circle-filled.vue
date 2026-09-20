<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG4Qao8d6B"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="jb-5h702a"/></mask></defs><circle mask="url(#SVG4Qao8d6B)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:triangle-down-circle-filled" /></template>
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

.jb-5h702a {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M13 15.998L17.037 9H8.963zm-.866 2.5a1 1 0 0 0 1.732 0L19.635 8.5a1 1 0 0 0-.866-1.5H7.23a1 1 0 0 0-.866 1.5z");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>
