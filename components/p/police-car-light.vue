<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jmtk9bcak"/><circle class="a0folk35s"/><path class="fvskovb1m"/><path class="uij6kcb_a"/><path class="lb5n_ibyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:police-car-light" /></template>
<style>
.a0folk35s {
  cx: 18.069px;
  cy: 14px;
  r: 9.366px;
  fill: var(--svg-color--be1931, #be1931);
}

.fvskovb1m {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M35.521 29.18H.479L0 34c0 2 2 2 2 2h32s2 0 2-2z");
}

.jmtk9bcak {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M34.16 28.812L31.244 2.678A3.01 3.01 0 0 0 28.251 0H7.664a3.01 3.01 0 0 0-2.997 2.704l-2.67 26.108z");
}

.lb5n_ibyo {
  fill: var(--svg-color--ec9dad, #ec9dad);
  d: path("m29.647 13.63l-7.668-1.248l4.539-6.308a.375.375 0 0 0-.523-.523l-6.309 4.538l-1.247-7.667a.375.375 0 0 0-.74 0l-1.248 7.667l-6.308-4.538a.375.375 0 0 0-.523.523l4.538 6.308L6.49 13.63a.374.374 0 0 0 0 .74l7.668 1.248l-4.538 6.308a.375.375 0 0 0 .523.523l6.308-4.538l1.248 7.667a.374.374 0 0 0 .74 0l1.247-7.667l6.308 4.538a.375.375 0 0 0 .523-.523l-4.538-6.308l7.668-1.248a.374.374 0 0 0 0-.74");
}

.uij6kcb_a {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("m35.594 29.912l-.073-.732C35.38 28.442 34.751 28 34 28H2c-.751 0-1.38.442-1.521 1.18l-.073.732z");
}

</style>
