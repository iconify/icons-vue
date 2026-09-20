<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="r2m6m3voe"/><path class="h6x-0tbyi"/><path class="no2h5-n4w"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:slr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h6x-0tbyi {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.415 16.399c0 .83.577 1.89 2.163 1.89c1.858 0 2.943-1.078 2.943-2.637c0-1.445-.752-2.27-2.65-3.074c-2.297-.894-3.716-2.202-3.716-4.38C8.155 5.788 9.971 4 12.705 4c1.44 0 3.695 1 3.695 3.2h-1.666c0-.502-.58-1.549-2.092-1.549c-1.92 0-2.65 1.262-2.65 2.317c0 1.445.856 2.156 2.796 2.982c2.38 1.01 3.59 2.27 3.59 4.54c0 2.387-1.46 4.51-4.778 4.51c-1.357 0-4-.866-4-3.601z");
}

.no2h5-n4w {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.852 14.997c.35-.284.652-.62.894-.994c-.335-.746-.721-1.21-1.03-1.498a2.7 2.7 0 0 1-.63 1.115q.287.234.485.548c.137.224.243.498.28.83m-.815.526a4.55 4.55 0 0 1-2.037.476c-2.43 0-4.4-1.88-4.4-4.2c0-.698.179-1.356.495-1.935a5.9 5.9 0 0 0 1 1.589q-.022.172-.022.346c0 1.513 1.284 2.739 2.87 2.739a2.96 2.96 0 0 0 1.498-.403l.028.022c.124.098.274.216.399.419c.121.199.224.496.169.947m2.363-3.724c0 .455-.076.892-.216 1.302c-.504-.876-1.057-1.325-1.384-1.55c-.131-1.396-1.36-2.49-2.858-2.49c-.381 0-.745.07-1.078.2c-.397-.574-.527-1.04-.517-1.355A4.6 4.6 0 0 1 12 7.6c2.43 0 4.4 1.88 4.4 4.2m-6.246-2.142c-.32-.478-.516-.938-.585-1.359a4.4 4.4 0 0 0-.92.78c.121.359.345.917.742 1.467c.188-.347.449-.65.763-.888");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r2m6m3voe {
  fill: var(--svg-color--fea616, #fea616);
  d: path("M24 0H0v24h24z");
}

</style>
