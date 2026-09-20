<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="e5bzvebzh"/><path class="pij5k0b4k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:voxel-background" /></template>
<style>
.e5bzvebzh {
  fill: var(--svg-color--f5c700, #f5c700);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.pij5k0b4k {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.778 15.356l.489-6.467c-1.467 0-3.41 1.347-4.156 2.022v3.334C7.6 17.067 10.578 19.258 12 20v-2.324c-.41-.24-1.222-1.716-1.222-2.32m2.444 0l-.489-6.467c1.467 0 3.41 1.347 4.156 2.022v3.334C16.4 17.067 13.423 19.258 12 20v-2.324c.409-.24 1.222-1.716 1.222-2.32M12 7.36L9.334 8.444L8.889 8c.52-.267 1.672-.782 2.138-.938c.467-.16.529-1.36.529-1.95c-.156-.16-.222-.348-.222-.445c0-.476.47-.667.666-.667zm0 0l2.667 1.084L15.11 8a24 24 0 0 0-2.138-.938c-.466-.16-.528-1.36-.528-1.95c.155-.16.222-.348.222-.445C12.667 4.19 12.196 4 12 4z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
