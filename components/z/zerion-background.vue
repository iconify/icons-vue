<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="f5a08kt8b"/><path clip-rule="evenodd" class="kfktz46fu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zerion-background" /></template>
<style>
.f5a08kt8b {
  fill: var(--svg-color--2461ed, #2461ed);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.kfktz46fu {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.15 11.617c-2.93-1.522-6.496-3.496-9.18-5.105c-.792-.548-.39-1.712.567-1.712h13.28c.74 0 1.236.794.865 1.395c-.893 1.48-2.195 3.361-3.283 4.852c-.585.8-1.537.938-2.248.57m-4.274.494c2.834 1.452 6.805 3.66 9.627 5.33c.874.517.524 1.758-.494 1.758L5.008 19.2c-.814 0-1.232-.812-.886-1.378c1.168-1.913 2.481-3.845 3.573-5.287c.485-.643 1.473-.787 2.181-.424");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
