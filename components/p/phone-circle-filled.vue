<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGDek0lcuR"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="oig13ac2c"/></mask></defs><circle mask="url(#SVGDek0lcuR)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:phone-circle-filled" /></template>
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

.oig13ac2c {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("m15.52 13.192l-.581.582a31 31 0 0 1-2.827-2.83l.58-.58a3 3 0 0 0 0-4.243l-1.414-1.414a3 3 0 0 0-4.242 0L4.23 7.513A1 1 0 0 0 4 8.57c2.374 6.36 6.818 10.834 13.308 13.312a1 1 0 0 0 1.064-.227l2.806-2.806a3 3 0 0 0 0-4.242l-1.415-1.415a3 3 0 0 0-4.242 0m4.244 2.829a1 1 0 0 1 0 1.414l-2.342 2.341c-5.424-2.23-9.173-6-11.317-11.31L8.45 6.12a1 1 0 0 1 1.414 0l1.414 1.415a1 1 0 0 1 0 1.414l-1.234 1.234a1 1 0 0 0-.063 1.345a33 33 0 0 0 4.373 4.376a1 1 0 0 0 1.345-.063l1.236-1.235a1 1 0 0 1 1.414 0z");
}

</style>
