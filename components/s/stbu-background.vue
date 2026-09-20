<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="iznh_4b8x"/><path class="qbdvskyud"/><path class="ur59sbelb"/><path class="rytveexnx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stbu-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iznh_4b8x {
  fill: var(--svg-color--20242f, #20242f);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qbdvskyud {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.727 11.03h1.455v3.394c0 3.273 3.04 3.879 4.606 3.879c.533 0 .727-.117.727-.117v-2.792h-.3c-.63 0-1.64-.252-1.64-1.348v-8.35h-3.393v2.91h-1.455zm-4.814 4.62a4.15 4.15 0 0 1-2.502-.984L4 16.864s1.47 1.44 3.927 1.44c2.54 0 4.558-1.484 4.558-3.152c0-2.113-2.618-2.792-3.976-3.277c-.66-.233-1.115-.359-1.115-.601c0-.34.441-.524.936-.524c1.377 0 2.327.795 2.327.795l1.13-2.327S10.623 8.102 8.33 8.102c-2.27 0-4.088 1.09-4.088 2.928c0 2.095 2.037 2.895 3.404 3.409c.703.266 1.202.484 1.202.775c0 .325-.44.437-.935.437");
}

.rytveexnx {
  fill: var(--svg-color--47b9ff, #47b9ff);
  d: path("M17.576 11.03H20V8.606h-2.424z");
}

.ur59sbelb {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.576 11.03H20V8.606h-2.424z");
}

</style>
