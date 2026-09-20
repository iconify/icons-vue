<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="nk36-7b5q"/><path class="o9scnc9gm"/><circle class="z3ut4cj_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:receipt" /></template>
<style>
.nk36-7b5q {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("m32 36l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2V0l2 2l1.958-2L10 2l2.042-2L14 2l2.042-2L18 2l2.083-2L22 2l2.125-2L26 2l1.958-2L30 2l2-2z");
}

.o9scnc9gm {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M19 17H9c-.55 0-1-.45-1-1s.45-1 1-1h10c.55 0 1 .45 1 1s-.45 1-1 1m8 0h-4c-.55 0-1-.45-1-1s.45-1 1-1h4c.55 0 1 .45 1 1s-.45 1-1 1m-8 4H9c-.55 0-1-.45-1-1s.45-1 1-1h10c.55 0 1 .45 1 1s-.45 1-1 1m8 0h-4c-.55 0-1-.45-1-1s.45-1 1-1h4c.55 0 1 .45 1 1s-.45 1-1 1m0 6H9c-.55 0-1-.45-1-1s.45-1 1-1h18c.55 0 1 .45 1 1s-.45 1-1 1m0 4h-4c-.55 0-1-.45-1-1s.45-1 1-1h4c.55 0 1 .45 1 1s-.45 1-1 1");
}

.z3ut4cj_h {
  cx: 18px;
  cy: 8px;
  r: 4px;
  fill: var(--svg-color--99aab5, #99aab5);
}

</style>
