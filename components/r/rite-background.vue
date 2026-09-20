<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="oe8m_z7zn"/><path class="kqp974bqz"/><path class="i5oe4ac0h"/><path class="dhpxmrb-d"/><path class="uijcrvblv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rite-background" /></template>
<style>
.dhpxmrb-d {
  fill: var(--svg-color--000, #000);
  d: path("M17.676 7.746a7.1 7.1 0 0 1 1.379 4.932A7.153 7.153 0 0 1 12 19.064c-1.294 0-2.58-.31-3.737-1.035a1.741 1.741 0 1 0-.574.715A8.006 8.006 0 0 0 18.4 7.195l-.73.55zM7.25 17.926a.833.833 0 1 1-1.177-1.178a.833.833 0 0 1 1.177 1.177");
}

.ft5dv1b6b {
  fill: none;
}

.i5oe4ac0h {
  fill: var(--svg-color--000, #000);
  d: path("m17.662 17.012l-.65.65l-1.45-1.45l.678-.621zM16.311 5.251a8.05 8.05 0 0 0-9.977 1.083A8.05 8.05 0 0 0 5.59 16.8l.73-.55a7 7 0 0 1-.537-.828a7.13 7.13 0 0 1 6.231-10.505a7 7 0 0 1 3.718 1.054a1.742 1.742 0 0 0 2.297 2.292a7 7 0 0 0-.358-.517l.73-.55q.182.24.343.493a1.741 1.741 0 0 0-2.438-2.438zm1.614 1.996a.834.834 0 1 1-1.236-1.12a.834.834 0 0 1 1.236 1.12");
}

.kqp974bqz {
  fill: var(--svg-color--000, #000);
  d: path("m16.212 15.63l-.25-.26a5.215 5.215 0 0 0-2.908-8.429a5.17 5.17 0 0 0-5.28 2.057a5.21 5.21 0 0 0 1.915 7.69a5.17 5.17 0 0 0 5.624-.668l.226.22l1.445 1.45l.644-.644l-1.416-1.422zm-1.205-.566a4.27 4.27 0 0 1-7.116-1.788A4.3 4.3 0 0 1 9.967 8.25a4.264 4.264 0 0 1 6.292 3.779c0 1.139-.447 2.23-1.252 3.035");
}

.oe8m_z7zn {
  fill: var(--svg-color--01fdfe, #01fdfe);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uijcrvblv {
  fill: var(--svg-color--000, #000);
  d: path("M9.647 9.83a.6.6 0 0 1 .104-.325a.7.7 0 0 1 .263-.235a.8.8 0 0 1 .725-.01l.494.26l3.699 1.92a.7.7 0 0 1 .263.235a.6.6 0 0 1 0 .659a.7.7 0 0 1-.263.235l-2.974 1.539l-.725.376l-.494.254a.8.8 0 0 1-.236.076l-.127.014a.8.8 0 0 1-.517-.188a.66.66 0 0 1-.212-.466z");
}

</style>
