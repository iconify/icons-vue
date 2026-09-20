<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="wir0_ob6a"/><path clip-rule="evenodd" class="o_fmwlbsw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:polx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.o_fmwlbsw {
  fill: var(--svg-color--457cd6, #457cd6);
  fill-rule: evenodd;
  d: path("M5.372 11.333L4 17.111l4.077-2.667h8.812a3.11 3.11 0 0 0 3.11-3.111z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wir0_ob6a {
  fill: var(--svg-color--86e7f7, #86e7f7);
  fill-rule: evenodd;
  d: path("M5.363 11.333L4 17.111l4.158-2.737h8.73A3.11 3.11 0 0 0 20 11.334zM5.677 10H20v-.445a2.667 2.667 0 0 0-2.667-2.666H6.425v.052l-.013-.052z");
}

</style>
