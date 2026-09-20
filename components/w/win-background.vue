<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rdf24b9vx"/><path class="kgcni3bin"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:win-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kgcni3bin {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.84 17.454a.6.6 0 0 0-.81.081a.56.56 0 0 0 0 .738c1.856 1.479 3.997 1.714 5.079 1.726c2.02.023 4.289-1.048 5.17-1.586c.187-.115.415-.437.165-.803s-.68-.256-.863-.156c-.723.45-2.628 1.35-4.472 1.35a7.5 7.5 0 0 1-4.265-1.347zM7.778 6.667a1.333 1.333 0 1 0 0-2.667a1.333 1.333 0 0 0 0 2.667m9.067-2.6c.261-.124.536-.062.617.076c.148.253.01.414-.077.466l-1.446.708c.396.196 1.23.608 1.405.693c.22.107.278.31.129.525c-.102.146-.392.163-.528.086l-1.793-.889a.46.46 0 0 1-.263-.398a.5.5 0 0 1 .263-.44c.456-.224 1.432-.701 1.693-.827m-5.519 11.54l1.022-3.2l1.264 3.272a1.2 1.2 0 0 0 1.53.69a1.16 1.16 0 0 0 .754-.971l1.616-5.9a1.167 1.167 0 0 0-.83-1.439a1.195 1.195 0 0 0-1.453.838l-.71 2.588l-1.05-2.721a1.2 1.2 0 0 0-1.257-.756a1.2 1.2 0 0 0-1.2.828l-.905 2.83l-.904-2.83a1.197 1.197 0 0 0-1.892-.56a1.16 1.16 0 0 0-.365 1.254l1.943 6.076a1.2 1.2 0 0 0 1.217.828a1.2 1.2 0 0 0 1.22-.827");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rdf24b9vx {
  fill: var(--svg-color--d1aa11, #d1aa11);
  d: path("M24 0H0v24h24z");
}

</style>
