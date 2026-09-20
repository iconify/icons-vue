<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="mg6ny5brb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mplx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mg6ny5brb {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.903 14.589a.38.38 0 0 0 .014-.393L7.641 6.603a.34.34 0 0 0-.29-.18H4.343c-.266 0-.431.306-.295.549l5.614 10.113c.13.228.436.243.582.025zm7.757 2.986c.262 0 .427-.305.291-.543l-5.77-10.429a.34.34 0 0 0-.3-.18h-2.996c-.262 0-.427.306-.291.549l5.789 10.424a.34.34 0 0 0 .29.18zM6.715 16.93c.131.243-.034.645-.3.645H4.359c-.194 0-.359-.262-.359-.46v-3.661c0-.369.475-.504.655-.184l2.055 3.66z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
