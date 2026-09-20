<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVG2lcyn7oz" x1="50%" x2="50%" y1="0%" y2="100%"><stop offset="0%" class="i0toucczv"/><stop offset="100%" class="eutboxbpm"/></linearGradient></defs><rect fill="url(#SVG2lcyn7oz)" class="u6muu28qt"/><rect class="mctea1byb"/><rect class="m43iitfyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:trello" /></template>
<style>
.eutboxbpm {
  stop-color: var(--svg-color--0079bf, #0079bf);
}

.i0toucczv {
  stop-color: var(--svg-color--0091e6, #0091e6);
}

.m43iitfyk {
  width: 78.08px;
  height: 176px;
  x: 33.28px;
  y: 33.28px;
  fill: var(--svg-color--fff, #fff);
  rx: 12px;
}

.mctea1byb {
  width: 78.08px;
  height: 112px;
  x: 144.64px;
  y: 33.28px;
  fill: var(--svg-color--fff, #fff);
  rx: 12px;
}

.u6muu28qt {
  width: 256px;
  height: 256px;
  rx: 25px;
}

</style>
