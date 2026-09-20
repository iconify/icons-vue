<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lhm4r-b8o"/><path clip-rule="evenodd" class="w2qv6g7yn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:os-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lhm4r-b8o {
  fill: var(--svg-color--7853fe, #7853fe);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w2qv6g7yn {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06m0 .47a8 8 0 1 0 0-16a8 8 0 0 0 0 16M7.765 9.882v-.47L12 6.824l4.235 2.588v.47L12 12.471zm.94-.235L12 7.765l3.294 1.882L12 11.53zm1.883-.47l.706-.471l2.353 1.412l-.706.47zm-2.823 2.352v.706L12 14.588l4.235-2.353v-.706L12 13.882zm0 3.06v-.707L12 16.235l4.235-2.353v.706L12 16.941z");
}

</style>
