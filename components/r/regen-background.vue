<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="fnmk6lmcz"/><path class="r_gmknb7x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:regen-background" /></template>
<style>
.fnmk6lmcz {
  fill: var(--svg-color--52b675, #52b675);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r_gmknb7x {
  fill: var(--svg-color--fff, #fff);
  d: path("m4.696 11.153l4.871.678l-4.87.682L4 11.83l.696-.683zm3.13 1.694h2.09l-1.742 1.026l-.696-.339l.348-.682zm2.433.687l-1.741.678v.682h.7l1.04-1.365zm-.692 2.72v-.678l1.388-1.02l-.696 1.698zm1.388 3.407L12 14.894l-2.085 4.424l.344.682zm1.741-3.063l.349-1.704l.348 1.704l-.348.338zm1.389 0l-.344-1.704l1.04 1.365v.677zm4.87.338l-3.477-3.402L20 15.915v1.021zm-1.04-5.449l-2.09.344l2.09.338l.344-.338zm1.04-4.762l-3.477 3.402L20 8.085V7.064zm-4.174 1.02l-.348 1.366l1.045-1.026v-.683zm-1.388-.681l-.348 1.703l-.349-1.703l.349-.34zm-2.438-2.725L12 9.106L9.915 4.682L10.26 4zM9.567 8.085l1.04 1.703l-1.741-1.021v-.682z");
}

</style>
