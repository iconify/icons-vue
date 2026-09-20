<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG6Hr4qc9o)" class="r4i437pya"/><path clip-rule="evenodd" class="z3fu_2b8l"/></g><defs><linearGradient id="SVG6Hr4qc9o" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop offset=".352" class="ymxfq5byl"/><stop offset="1" class="x1kmm4b1e"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pyr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.x1kmm4b1e {
  stop-color: var(--svg-color--ee6233, #ee6233);
}

.ymxfq5byl {
  stop-color: var(--svg-color--fcca08, #fcca08);
}

.z3fu_2b8l {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12.462 4c.016.32-.2 1.274-1.188 2.521c-.268.34-.574.69-.89 1.05C9.25 8.869 8 10.298 8 11.8c0 1.535.707 2.55 1.06 2.866c.053-.39.399-1.432 1.365-2.481c.297-.323.728-.678 1.198-1.065c1.44-1.184 3.244-2.67 2.689-4.465c0 .462-.35 1.575-1.755 2.324c-1.404.75-2.258 1.662-2.51 2.025c-.031-.175.094-.813.544-1.421l.169-.223c.746-.98 2.312-3.037 1.702-5.361m-.924 16c-.015-.32.2-1.274 1.188-2.521c.268-.34.575-.69.89-1.05C14.75 15.131 16 13.702 16 12.2c0-1.535-.707-2.55-1.06-2.866c-.053.39-.399 1.432-1.365 2.481c-.297.323-.728.678-1.198 1.065c-1.44 1.184-3.244 2.67-2.689 4.465c0-.462.35-1.575 1.755-2.324c1.404-.75 2.258-1.662 2.51-2.025c.031.175-.094.813-.544 1.421l-.169.223c-.746.981-2.311 3.037-1.702 5.361");
}

</style>
