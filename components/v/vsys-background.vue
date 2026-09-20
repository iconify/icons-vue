<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="e7ia0lb_p"/><path class="e2hz90baf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vsys-background" /></template>
<style>
.e2hz90baf {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.132 5.333h4.582c.027 0 .047 0 .067.02a.12.12 0 0 1 .053.05l5.577 9.258a.14.14 0 0 1 0 .16l-2.282 3.776a.14.14 0 0 1-.05.051a.14.14 0 0 1-.139 0a.14.14 0 0 1-.05-.051L4.018 5.555a.15.15 0 0 1 0-.145a.14.14 0 0 1 .046-.056a.14.14 0 0 1 .067-.021m9.605 0h6.13a.1.1 0 0 1 .066.02q.031.023.047.056q.019.031.02.07c0 .034 0 .055-.02.076l-3.061 5.086a.14.14 0 0 1-.12.07a.14.14 0 0 1-.07-.018a.14.14 0 0 1-.05-.052L13.61 5.555a.15.15 0 0 1 .12-.222z");
}

.e7ia0lb_p {
  fill: var(--svg-color--ff8836, #ff8836);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
