<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bct9-1h3b"/><path class="hzw6ubbey"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:premia-background" /></template>
<style>
.bct9-1h3b {
  fill: var(--svg-color--5293fe, #5293fe);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hzw6ubbey {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.356 8h7.273c.415 0 .655.44.415.765l-3.4 4.453c-.25.325-.004.78.41.78h3.06c.16 0 .315-.07.41-.2l3.378-4.499a.48.48 0 0 0 0-.58l-3.014-4.013a.51.51 0 0 0-.41-.205H7.522a.51.51 0 0 0-.41.2L4.098 8.72a.48.48 0 0 0 0 .58l7.493 9.996c.2.27.62.27.82 0l1.53-2.044a.48.48 0 0 0 0-.58L7.95 8.765C7.705 8.44 7.95 8 8.36 8z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
