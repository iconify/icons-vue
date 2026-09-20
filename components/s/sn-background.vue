<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="j-w8ksbjd"/><path class="op37k2bio"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sn-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j-w8ksbjd {
  fill: var(--svg-color--ffa529, #ffa529);
  d: path("M24 0H0v24h24z");
}

.op37k2bio {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.26 19.99c-.815 0-1.625-.016-2.44 0c-.42.014-.71-.23-.925-.73c-.74-1.71-1.495-3.41-2.24-5.116c-.31-.715-.15-1.14.45-1.145c1.07-.01 2.14.01 3.205 0c.435 0 .73.28.95.8a373 373 0 0 0 1.635 3.715s.13.315.24.48c.075.115.425.33.755.095c.32-.23.285-.5.1-.92c-.58-1.325-1.175-2.645-1.74-3.985c-.1-.245-.21-.55-.04-.82c.125-.205.33-.365.49-.365c1.05 0 2.105.015 3.16 0c.42-.005.72.215.93.715c.36.835.715 1.66 1.09 2.475c.19.41.15.735-.08 1.07c-.755 1.09-1.485 2.21-2.265 3.265a1.15 1.15 0 0 1-.8.445c-.82.055-1.65.02-2.475.02m-.545-15.975c.8 0 1.595.015 2.39-.01c.45-.01.77.215 1.005.765c.74 1.71 1.5 3.405 2.24 5.11c.3.685.145 1.115-.43 1.12c-1.07.01-2.135 0-3.2 0c-.7 0-1-.82-1-.82l-1.68-3.765s-.13-.32-.21-.45a.536.536 0 0 0-.71-.1c-.34.235-.265.625-.1.995c.52 1.18 1.09 2.355 1.6 3.55c.16.395.49.805.21 1.255c-.165.27-.5.34-.876.335c-.93-.014-1.86-.02-2.795 0c-.435.01-.75-.21-.97-.74c-.34-.815-.7-1.62-1.065-2.415c-.195-.43-.16-.765.09-1.12c.735-1.055 1.44-2.15 2.2-3.175a1.3 1.3 0 0 1 .865-.51c.81-.07 1.626-.025 2.435-.025");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
