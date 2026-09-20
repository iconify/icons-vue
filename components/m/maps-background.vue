<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="xv1tt-gok"/><path class="i6tnqknta"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:maps-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i6tnqknta {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.556 4.988c-2.386.475-2.382 1.338-2.377 2.355v.125l.835-.16c-.067-.445.169-1.271 1.644-1.556c1.449-.284 1.876.418 1.924.89l.8-.152c.018-.693-.528-1.96-2.826-1.502m-3.688 9.288L5.046 16.11l-.854-4.577zM5.29 17.453l-.12-.653l2.102-2.11l3.662 3.754l-3.298.631a2.01 2.01 0 0 1-2.346-1.622m10.879-.004l-4.555.862l-.823-.845l2.73-2.737l2.648 2.71zm2.195-.418l-1.515.289l-2.925-2.995l2.778-2.787l3.297 3.44a2.026 2.026 0 0 1-1.635 2.044zm.6-7.76l.875 4.711l-2.728-2.853zm-.253-1.368l.124.68l-2.124 2.133l-2.68-2.808L15.48 6.45l.889-.169a2.01 2.01 0 0 1 2.342 1.622M7.69 7.934l6.786-1.288l-4.067 4.074l-2.715-2.786zm-2.053.396l1.377-.267l2.991 3.066l-2.729 2.738l-3.266-3.342A2.03 2.03 0 0 1 5.637 8.33m7.985-.014l2.684 2.804l-2.782 2.791l-2.71-2.777zm-2.288 5.906a.89.89 0 1 1-1.78 0a.89.89 0 0 1 1.78 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xv1tt-gok {
  fill: var(--svg-color--77d563, #77d563);
  d: path("M24 0H0v24h24z");
}

</style>
