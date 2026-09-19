<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path id="SVGwI8FKbsc" class="wop6s1bde"/><use href="#SVGwI8FKbsc"/><path class="hcpltvwbp"/><path class="lmbbyqbpj"/><path class="wpuhvkeht"/><path class="xl6qm5m6d"/><path class="gf576ll_r"/><path class="i2ar-4fuf"/><path class="s7h5z9hjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:speaker-low-volume" /></template>
<style>
.gf576ll_r {
  fill: var(--svg-color--dfe9ef, #dfe9ef);
  d: path("M29.8 13.3L11.1 23.8v16.4l18.7 10.5z");
}

.hcpltvwbp {
  fill: var(--svg-color--b0bdc6, #b0bdc6);
  d: path("M29.8 2.2C31.1.9 11.1 19 11.1 19v26s10.3 7.9 18.7 16.8z");
}

.i2ar-4fuf {
  fill: var(--svg-color--8b979e, #8b979e);
  d: path("M29.8 13.3H33v37.5h-3.2z");
}

.lmbbyqbpj {
  fill: var(--svg-color--333, #333);
  d: path("M33 25.5v13.1c3.9 0 7-2.9 7-6.5c0-3.7-3.1-6.6-7-6.6m0 37c0 .8-.7 1.5-1.6 1.5s-1.6-.7-1.6-1.5v-61c0-.8.7-1.5 1.6-1.5S33 .7 33 1.5z");
}

.s7h5z9hjo {
  fill: var(--svg-color--333, #333);
  d: path("M3.8 19h7.3v26H3.8z");
}

.wop6s1bde {
  fill: var(--svg-color--8b979e, #8b979e);
  d: path("M11.1 45H3.8C1.7 45 0 43.4 0 41.5v-19c0-2 1.7-3.5 3.8-3.5h7.3z");
}

.wpuhvkeht {
  fill: var(--svg-color--8b979e, #8b979e);
  d: path("M11.1 40.2H3.8c-2.1 0-3.8-1-3.8-2.2V26c0-1.2 1.7-2.2 3.8-2.2h7.3z");
}

.xl6qm5m6d {
  fill: var(--svg-color--b0bdc6, #b0bdc6);
  d: path("M11.1 40.2H3.8c-2.1 0-3.8-1-3.8-2.2V26c0-1.2 1.7-2.2 3.8-2.2h7.3z");
}

</style>
