<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="tjfk2hekj"/><path clip-rule="evenodd" class="s3va1-bfj"/><path clip-rule="evenodd" class="gb1jawl0g"/><path class="eu_l5ubtc"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:perp-background" /></template>
<style>
.eu_l5ubtc {
  fill: var(--svg-color--000, #000);
  d: path("m13.844 10.992l-1.81 1.723l-1.808-1.723l1.808-1.716z");
}

.ft5dv1b6b {
  fill: none;
}

.gb1jawl0g {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("m10.227 10.996l3.553 3.442l-2.602 2.468c-.314.313-.754 1.126 0 1.87c.753.744 1.663.076 2.024-.352l6.16-5.945c.4-.464 1.122-1.829.162-2.777s-2.247-2.145-2.77-2.625c-.454-.363-1.686-.77-2.98.51a180 180 0 0 1-3.547 3.409m3.613 0l1.775 1.74l1.761-1.648l-1.831-1.73z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s3va1-bfj {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("m11.224 18.776l-6.535-6.272c-.55-.578-1.066-2.043-.309-2.752c.206-.193.55-.511.965-.897a299 299 0 0 0 3.47-3.253c.8-.771 1.786-1.039 2.737-.18a80 80 0 0 1 2.294 2.164l-1.823 5.16l-1.734 1.62l1.768 1.732zm-4.487-7.852l3.602-3.348l1.716 1.682l-3.56 3.382z");
}

.tjfk2hekj {
  fill: var(--svg-color--3bebaa, #3bebaa);
  d: path("M24 0H0v24h24z");
}

</style>
