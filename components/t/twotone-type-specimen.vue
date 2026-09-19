<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1m4c6bhp"/><path class="d-8_bbcme"/><path class="f5j_qdwkr"/><path class="fhr-abc5o"/><path class="a3lhhzblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-type-specimen" /></template>
<style>
.a3lhhzblf {
  fill: currentColor;
  d: path("M12.19 12.2h3.63l.8 2.3h1.56l-3.38-9h-1.6l-3.38 9h1.56zm1.77-5.03h.08l1.31 3.72h-2.69z");
}

.d-8_bbcme {
  fill: currentColor;
  d: path("M8 16h12V4H8zm5.2-10.5h1.61l3.38 9h-1.56l-.8-2.3H12.2l-.82 2.3H9.81z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.f5j_qdwkr {
  fill: currentColor;
  d: path("M4 6H2v14c0 1.1.9 2 2 2h14v-2H4z");
}

.fhr-abc5o {
  fill: currentColor;
  d: path("M20 2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 14H8V4h12z");
}

.y1m4c6bhp {
  fill: currentColor;
  d: path("M14.04 7.17h-.08l-1.31 3.72h2.69z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
