<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd7vtsmky"/><path class="h8lnmcczx"/><circle class="xrvvu0fts"/><circle class="t3avdfb0o"/><circle class="uqsohbb5z"/><circle class="tnadvnpqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-color-lens" /></template>
<style>
.cd7vtsmky {
  fill: currentColor;
  d: path("M12 4c-4.41 0-8 3.59-8 8s3.59 8 8 8c.28 0 .5-.22.5-.5a.54.54 0 0 0-.14-.35c-.41-.46-.63-1.05-.63-1.65a2.5 2.5 0 0 1 2.5-2.5H16c2.21 0 4-1.79 4-4c0-3.86-3.59-7-8-7m-5.5 9c-.83 0-1.5-.67-1.5-1.5S5.67 10 6.5 10s1.5.67 1.5 1.5S7.33 13 6.5 13m3-4C8.67 9 8 8.33 8 7.5S8.67 6 9.5 6s1.5.67 1.5 1.5S10.33 9 9.5 9m5 0c-.83 0-1.5-.67-1.5-1.5S13.67 6 14.5 6s1.5.67 1.5 1.5S15.33 9 14.5 9m4.5 2.5c0 .83-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.h8lnmcczx {
  fill: currentColor;
  d: path("M12 2C6.49 2 2 6.49 2 12s4.49 10 10 10a2.5 2.5 0 0 0 1.86-4.17a.495.495 0 0 1 .37-.83H16c3.31 0 6-2.69 6-6c0-4.96-4.49-9-10-9m4 13h-1.77a2.5 2.5 0 0 0-2.5 2.5c0 .61.22 1.19.63 1.65c.06.07.14.19.14.35c0 .28-.22.5-.5.5c-4.41 0-8-3.59-8-8s3.59-8 8-8s8 3.14 8 7c0 2.21-1.79 4-4 4");
}

.t3avdfb0o {
  cx: 9.5px;
  cy: 7.5px;
  r: 1.5px;
  fill: currentColor;
}

.tnadvnpqb {
  cx: 17.5px;
  cy: 11.5px;
  r: 1.5px;
  fill: currentColor;
}

.uqsohbb5z {
  cx: 14.5px;
  cy: 7.5px;
  r: 1.5px;
  fill: currentColor;
}

.xrvvu0fts {
  cx: 6.5px;
  cy: 11.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
