<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGvJa47jOp)" class="u1ncimb_r"/><defs><linearGradient id="SVGvJa47jOp" x1="7.38" x2="13.691" y1="5.16" y2="19.19" gradientUnits="userSpaceOnUse"><stop class="zvx4p2bdg"/><stop offset="1" class="l1yx5aczi"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mxm" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l1yx5aczi {
  stop-color: var(--svg-color--4af2cf, #4af2cf);
}

.u1ncimb_r {
  d: path("M13.605 4.125h-3.283L3 16.955l1.654 2.92h14.62L21 16.955zM4.547 16.5l6.382-11.25h1.405L6.72 15.375h6.452l.748 1.125zm4.112-2.25l4.67-8.413l6.366 11.043l-.71 1.31l-5.656-9.754l-3.182 5.814zm2.778 0L12 13.125l.563 1.125zm1.91-3.598l4.687 8.095H5.285l-.691-1.122h11.381l-3.284-5.778z");
}

.zvx4p2bdg {
  stop-color: var(--svg-color--18dbeb, #18dbeb);
}

</style>
