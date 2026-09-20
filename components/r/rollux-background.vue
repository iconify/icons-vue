<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="b2voj68ta"/><path class="oulmcpo7w"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rollux-background" /></template>
<style>
.b2voj68ta {
  fill: var(--svg-color--dbef88, #dbef88);
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 .002 16");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.oulmcpo7w {
  fill: var(--svg-color--000, #000);
  d: path("M8.466 7.87h.331l7.93 7.27v.991h-8.26zm6.255 4.796a3.304 3.304 0 0 0-4.691-4.3z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
