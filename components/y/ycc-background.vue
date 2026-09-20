<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lkft5xuwd"/><path class="zg98sebjp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ycc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lkft5xuwd {
  fill: var(--svg-color--0276f7, #0276f7);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zg98sebjp {
  fill: var(--svg-color--fff, #fff);
  d: path("m15.005 12.024l4.155-2.651c.555-.413 1.372-1.633.36-3.288c-.99-1.617-2.417-1.588-2.964-1.254l-6.57 4.07l2.276 1.27l4.593-2.732c.285-.172.483-.174.564-.033s.04.26-.216.438l-2.198 1.382zM7.452 4.856l4.297 2.357l-2.26 1.445l-2.376-1.327c-.322-.173-.464-.112-.53 0c-.063.11-.037.29.245.435l5.17 2.846v2.685L4.822 9.382c-.563-.307-1.302-1.528-.395-3.194c.927-1.703 2.391-1.606 3.026-1.332m2.542 12.479v-4.612L12 13.918v2.519c0 .403.117.488.25.486c.232-.004.258-.177.25-.486v-5.818l2.005-1.149v8.009c0 .626-.402 1.873-2.255 1.873c-1.897 0-2.194-1.344-2.255-2.017");
}

</style>
