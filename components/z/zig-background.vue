<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="cd7sd8tif"/><path class="fq8l-ez0m"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zig-background" /></template>
<style>
.cd7sd8tif {
  fill: var(--svg-color--734acc, #734acc);
  d: path("M24 0H0v24h24z");
}

.fq8l-ez0m {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.517 9.606c0-.532.397-.96.887-.96h.805c.49 0 .888.428.888.96v4.273c0 .532-.397.96-.888.96h-.805c-.49 0-.887-.428-.887-.96zm12.386-.114c0-.465.397-.846.888-.846h.805c.49 0 .887.381.887.846v3.468c0 .465-.397.847-.887.847h-.805c-.49 0-.888-.382-.888-.847zm-3.095 2.111c0-.49.397-.893.887-.893h.805c.49 0 .888.402.888.893v5.44c0 .49-.397.893-.888.893h-.805a.89.89 0 0 1-.887-.893zM7.613 4.914A.9.9 0 0 1 8.501 4h.805c.49 0 .888.413.888.914v7.463a.9.9 0 0 1-.888.913h-.805c-.49 0-.888-.413-.888-.913zm3.097 1.543a.9.9 0 0 1 .888-.908h.805a.9.9 0 0 1 .888.908v12.635a.9.9 0 0 1-.888.908h-.805a.9.9 0 0 1-.888-.908z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
