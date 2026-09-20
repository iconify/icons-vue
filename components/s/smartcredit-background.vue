<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="s7wujz-9q"/><path clip-rule="evenodd" class="t0kot9vsk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:smartcredit-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s7wujz-9q {
  fill: var(--svg-color--5999e9, #5999e9);
  d: path("M24 0H0v24h24z");
}

.t0kot9vsk {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4.978 16.141c-.075-.149-.08-.551.49-.97q.127-.09.34-.237c1.052-.727 3.496-2.414 4.414-4.519c.773-1.773 1.001-4.333 1.076-5.17c.01-.117.018-.201.023-.243c.045-.344.298-.955.595-1c.297-.044.654.492.683 1c.168 2.87.463 4.316 1.06 5.413c.466.86 3.224 3.598 4.824 4.757c.242.13.692.504.55.97c-.143.465-.852.292-1.19.148c-1.14-.64-3.92-1.897-5.927-1.813S7.4 15.622 6.398 16.141c-.398.156-1.238.375-1.421 0m1.844-5.082a1.883 1.883 0 1 0 0-3.766a1.883 1.883 0 0 0 0 3.766m10.353 0a1.883 1.883 0 1 0 0-3.766a1.883 1.883 0 0 0 0 3.766m-3.294 7.059a1.882 1.882 0 1 1-3.764 0a1.882 1.882 0 0 1 3.764 0");
}

</style>
