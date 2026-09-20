<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pc8z-ib3j"/><path class="lh5q1wbis"/><path class="xg1kwxber"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:terra-classic-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lh5q1wbis {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.88 16.69c.438 1.617 2.01 2.85 2.805 2.8c.028-.003 3.013-.557 4.647-3.279c1.271-2.118.838-4.162-.891-4.206c-.622.045-7.397 1.605-6.561 4.685m6.4-10.384l-.001-.002l.002-.001a7.6 7.6 0 0 0-8-1.151a5 5 0 0 0-.481.235q-.16.083-.317.174l.025.008a3.5 3.5 0 0 0-.8.756c-2.179 2.869 5.123 4.954 9.027 4.96c1.796 1.286 2.3-3.618.546-4.98");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.pc8z-ib3j {
  fill: var(--svg-color--0e3ca5, #0e3ca5);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xg1kwxber {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.722 6.364C8.72 7.867 5.378 8.926 4.828 8.76l-.004-.008l.069-.135a8 8 0 0 1 3.021-3.193a2.4 2.4 0 0 1 1.105-.292c1.488.028.71 1.219.703 1.23M8.9 16.985c.072.473-.002 2.338-.099 2.495c-.083.005-.257.016-.76-.266a8 8 0 0 1-3.51-4.078a7.96 7.96 0 0 1-.04-5.612c.578.765 1.246 1.456 1.813 2.229c.54.735 1.283 1.934 1.435 2.19c.94 1.59 1.088 2.572 1.16 3.042M20 12.284a7.9 7.9 0 0 1-.557 2.929c-.942 1.01-7.295-1.475-7.357-1.503c-.87-.379-3.514-1.535-3.753-3.35c-.343-2.609 4.969-4.428 7.303-4.497c.28.003 1.132.013 1.629.415A7.96 7.96 0 0 1 20 12.284m-4.3 7.073c-.693.322-1.455.088-1.257-.585c.38-1.29 3.701-2.614 4.435-2.686c.09-.01.129.052.089.122a8.07 8.07 0 0 1-3.267 3.149");
}

</style>
