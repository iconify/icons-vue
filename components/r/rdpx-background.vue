<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="fv88-w1-e"/><path class="x4-e22bbj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rdpx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fv88-w1-e {
  fill: var(--svg-color--002eff, #002eff);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.x4-e22bbj {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.255 9.007L9.45 4L4.683 8.786a.728.728 0 0 0 .334 1.219l2.527.64c-.508.8-.998 1.74-1.03 2.71a1.95 1.95 0 0 0 .54 1.478c.603.602 1.36.838 1.996 1.346c1.6 1.28 2.315 3.623 4.635 3.812c1.435.117 3.186-.871 3.694-2.25a2.74 2.74 0 0 0-.005-1.788c-.334-1.101-1.025-2.061-1.364-3.162c-.316-1.045-.1-1.497.037-1.676c.33-.433 1.27-.555 1.69-.696l.922-.31c.221-.076.499-.137.673-.311c.4-.4.113-.8-.179-1.106Q16.858 6.34 14.551 4q.82 1.286 1.633 2.574l1.581 2.494l-.428.146c-.81.273-1.746.41-2.297 1.13c-.451.592-.64 1.505-.235 2.823c.339 1.101 1.026 2.057 1.36 3.158c.118.4.127.706.028.974c-.315.852-1.44 1.364-2.315 1.29c-1.91-.156-2.73-2.354-4.038-3.403c-.611-.485-1.322-.682-1.891-1.252c-.113-.113-.18-.278-.17-.541c.028-.956.683-1.91 1.228-2.645a.73.73 0 0 0-.4-1.143zm5.331 5.19s-.979 0-1.628-.597c-.65-.602 0-1.802 0-1.802s.188.117.908.96c.72.842.72 1.44.72 1.44");
}

</style>
