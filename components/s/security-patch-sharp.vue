<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mgiids75u"/><path class="gvhzjdi9d"/><path class="zig39n_4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:security-patch-sharp" /></template>
<style>
.gvhzjdi9d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.01 7.9l.84.84l1.06 1.06l-1.06 1.06l-4.24 4.24l-1.06 1.06l-1.06-1.06l-.84-.84l-1.06-1.06l1.06-1.06l4.24-4.24l1.06-1.06z");
}

.mgiids75u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.75l6.6 2.45l.652.244l-.002.696v5.26c0 4.4-2.9 7.6-7.25 9.85C7.65 19 4.75 15.8 4.75 11.4V6.14l-.002-.696L5.4 5.2Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zig39n_4j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.25 11.5h.01");
}

</style>
