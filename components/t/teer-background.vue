<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="kpzvxrbxn"/><path class="xroww5zix"/><path class="cm3i98bsj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:teer-background" /></template>
<style>
.cm3i98bsj {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.5 7.5h-5c-.285 0-.5.195-.5.5s.215.5.5.5H9v4H5.055c-.27 0-.555.21-.555.5s.23.5.5.5h4v4H4.5c-.285 0-.5.195-.5.5s.215.5.5.5h5c.2 0 .325-.12.415-.3c.05-.09.085-.2.085-.32V8.12a.6.6 0 0 0-.1-.34c-.09-.165-.21-.28-.4-.28m10 1c.285 0 .5-.195.5-.5s-.215-.5-.5-.5h-4.95a.52.52 0 0 0-.45.28q-.099.151-.1.34v9.76c0 .115.03.225.085.32c.09.18.215.3.415.3h5c.285 0 .5-.195.5-.5s-.215-.5-.5-.5H15v-4h4c.27 0 .5-.21.5-.5s-.23-.5-.5-.5h-4v-4z");
}

.ft5dv1b6b {
  fill: none;
}

.kpzvxrbxn {
  fill: var(--svg-color--000563, #000563);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xroww5zix {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.45 6.5c.3 0 .55-.2.55-.5s-.25-.5-.55-.5H4.55c-.3 0-.55.2-.55.5s.2.5.5.5h7V18a.499.499 0 1 0 1 0V6.5z");
}

</style>
