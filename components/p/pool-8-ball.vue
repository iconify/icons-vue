<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="v6ehlpb7m"/><circle class="sj3mkabyw"/><path class="jbwztcbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:pool-8-ball" /></template>
<style>
.jbwztcbkr {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M13.703 20.203c0-1.406.773-2.443 1.881-3.041c-.826-.598-1.336-1.406-1.336-2.514c0-2.057 1.705-3.375 3.797-3.375c2.039 0 3.814 1.301 3.814 3.375c0 .984-.492 1.969-1.354 2.514c1.195.598 1.881 1.688 1.881 3.041c0 2.443-1.986 4.008-4.342 4.008c-2.425 0-4.341-1.652-4.341-4.008m2.742-.176c0 .896.527 1.758 1.6 1.758c1.002 0 1.6-.861 1.6-1.758c0-1.107-.633-1.758-1.6-1.758c-1.02.001-1.6.774-1.6 1.758m.334-5.097c0 .791.457 1.336 1.266 1.336s1.283-.545 1.283-1.336c0-.756-.457-1.336-1.283-1.336s-1.266.58-1.266 1.336");
}

.sj3mkabyw {
  cx: 18px;
  cy: 18px;
  r: 9px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

.v6ehlpb7m {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--31373d, #31373d);
}

</style>
