<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="m2vh23rkd"/><path class="gx-t3_b4p"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xtz-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gx-t3_b4p {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.813 19.991c-1.167 0-2.015-.271-2.559-.823c-.527-.552-.8-1.143-.8-1.775c0-.24.057-.432.144-.592c.092-.157.225-.287.385-.376c.16-.088.36-.135.59-.135c.233 0 .44.047.6.135a1.01 1.01 0 0 1 .52.96c0 .288-.063.512-.2.695a.97.97 0 0 1-.487.344c.16.224.415.376.767.472c.344.096.696.144 1.04.144c.465.005.922-.129 1.311-.384c.4-.256.68-.64.864-1.135c.192-.504.28-1.072.28-1.703c0-.696-.096-1.28-.305-1.767a2.2 2.2 0 0 0-.879-1.104a2.4 2.4 0 0 0-1.28-.351c-.287 0-.663.12-1.11.36l-.816.4v-.4l3.677-4.727H10.65v4.91c0 1.09.837 1.848 1.804 1.136c.274-.2.512-.442.704-.72a.3.3 0 0 1 .096-.112a.2.2 0 0 1 .12-.048c.072 0 .152.04.24.104c.086.09.134.21.136.336a2 2 0 0 1-.048.256c-.185.431-.49.8-.88 1.063c-.932.62-2.625.524-3.421-.272a2.4 2.4 0 0 1-.632-1.743V8.23H5.941v-.942h2.827V4.933l-.473-.47V4h1.608l.746.933v2.354h6.554l.672.551L13.74 11.9c.248-.098.51-.16.776-.184c.447 0 .959.144 1.519.424c.56.271.991.655 1.295 1.135s.504.935.584 1.375q.132.58.144 1.176c.005.754-.168 1.5-.504 2.175a3.23 3.23 0 0 1-1.52 1.503a5.04 5.04 0 0 1-2.222.496z");
}

.m2vh23rkd {
  fill: var(--svg-color--2e84fd, #2e84fd);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
