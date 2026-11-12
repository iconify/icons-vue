<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVG0ggNochV"><g class="k2u665ban"><circle class="pt9xvrdoi"/><path class="znoc0kvzy"/></g></mask></defs><path mask="url(#SVG0ggNochV)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifer-zoom-out-line-duotone" /></template>
<style>
.k2u665ban {
  fill: none;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pt9xvrdoi {
  cx: 11px;
  cy: 11px;
  r: 9px;
  stroke: var(--svg-color--gray, gray);
}

.w49j0rbvv {
  fill: currentColor;
  d: path("M0 0h24v24H0z");
}

.znoc0kvzy {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  d: path("M9 11h4m8.812 9.975c-.063.095-.176.208-.403.434c-.226.227-.34.34-.434.403a1.13 1.13 0 0 1-1.62-.408c-.053-.1-.099-.254-.19-.561c-.101-.335-.151-.503-.161-.621a1.13 1.13 0 0 1 1.218-1.218c.118.01.285.06.621.16c.307.092.46.138.56.192a1.13 1.13 0 0 1 .409 1.619Z");
}

</style>
