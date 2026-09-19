<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7n6x2l9o"/><circle class="zo3o4pbld"/><path class="t0ibbgbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-library" /></template>
<style>
.j7n6x2l9o {
  fill: currentColor;
  d: path("M19 17.13v-6.95c-2.1.38-4.05 1.35-5.64 2.83L12 14.28l-1.36-1.27A11.2 11.2 0 0 0 5 10.18v6.95c2.53.34 4.94 1.3 7 2.83c2.07-1.52 4.47-2.49 7-2.83");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.t0ibbgbgr {
  fill: currentColor;
  d: path("M16 5c0-2.21-1.79-4-4-4S8 2.79 8 5s1.79 4 4 4s4-1.79 4-4m-6 0c0-1.1.9-2 2-2s2 .9 2 2s-.9 2-2 2s-2-.9-2-2M3 19c3.48 0 6.64 1.35 9 3.55c2.36-2.19 5.52-3.55 9-3.55V8c-3.48 0-6.64 1.35-9 3.55C9.64 9.35 6.48 8 3 8zm2-8.82c2.1.38 4.05 1.35 5.64 2.83L12 14.28l1.36-1.27A11.2 11.2 0 0 1 19 10.18v6.95c-2.53.34-4.93 1.3-7 2.82a15.2 15.2 0 0 0-7-2.83z");
}

.zo3o4pbld {
  cx: 12px;
  cy: 5px;
  r: 2px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
