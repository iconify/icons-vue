<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bk3f2dbig"/><path class="brdpduxnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:one-per-customer" /></template>
<style>
.bk3f2dbig {
  d: path("m5.248 6.168l3-2A1 1 0 0 1 8.803 4h9.394a1 1 0 0 1 .555 1.832l-3 2a1 1 0 0 1-.555.168H5.803a1 1 0 0 1-.555-1.832Z");
}

.brdpduxnq {
  d: path("M13.4 21.5H2.5V8h13v5.4m0-.001V8.535q0-.123.03-.243t.088-.229t.141-.2t.186-.16l4-2.667q.113-.075.242-.118t.265-.049t.268.023t.252.094t.218.158q.099.094.168.211q.07.116.106.247t.036.267v7.836m0 1.9v1.36q0 .169-.055.328q-.056.16-.161.292M12 6h6m.5 8.5v7m-2.25-5l2.25-2m-2.25 7h4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
