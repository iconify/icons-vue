<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lq93gibcj"/><path class="cfqymbnco"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xpnet-background" /></template>
<style>
.cfqymbnco {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.85 19.618l-1.72-1.74a1.23 1.23 0 0 0-1.354-.274c-.15.063-.287.156-.401.274l-1.72 1.74a1.28 1.28 0 0 1-1.825 0l-.83-.84l2.63-2.67a3.664 3.664 0 0 1 5.24 0l2.63 2.67l-.83.84a1.274 1.274 0 0 1-1.82 0m-9.625-2.615l-.84-.83a1.28 1.28 0 0 1 0-1.825l1.74-1.716c.5-.49.5-1.275 0-1.76l-1.74-1.715a1.28 1.28 0 0 1 0-1.825l.84-.83L7.9 9.132a3.66 3.66 0 0 1 0 5.236zm6.525-8c-.95 0-1.9-.366-2.62-1.1L6.5 5.226l.83-.84a1.28 1.28 0 0 1 1.825 0l1.715 1.745c.485.49 1.275.49 1.76 0l1.715-1.75a1.28 1.28 0 0 1 1.825 0l.83.85l-2.63 2.67a3.7 3.7 0 0 1-2.62 1.1m7.025 8l-2.675-2.63a3.664 3.664 0 0 1 0-5.24l2.675-2.63l.84.83a1.28 1.28 0 0 1 0 1.824l-1.74 1.72c-.5.486-.5 1.276 0 1.755l1.74 1.72a1.28 1.28 0 0 1 0 1.826z");
}

.ft5dv1b6b {
  fill: none;
}

.lq93gibcj {
  fill: var(--svg-color--e22440, #e22440);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
