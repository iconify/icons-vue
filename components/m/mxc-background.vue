<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGRJnhyBAK)" class="r4i437pya"/><path class="e7ghfebty"/></g><defs><linearGradient id="SVGRJnhyBAK" x1="6.4" x2="17.751" y1="6.32" y2="17.723" gradientUnits="userSpaceOnUse"><stop class="t_5jv1b0x"/><stop offset="1" class="s5a3i0bah"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mxc-background" /></template>
<style>
.e7ghfebty {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.8 7.867a.72.72 0 0 1 .693-.667h2.064A.45.45 0 0 0 20 6.757V4.443A.45.45 0 0 0 19.557 4h-2.314a.443.443 0 0 0-.443.443v2.064a.736.736 0 0 1-.624.693h-2.133a.44.44 0 0 0-.443.443v2.064a.74.74 0 0 1-.624.693h-1.952a.73.73 0 0 1-.624-.624V7.643a.443.443 0 0 0-.448-.438H7.819a.73.73 0 0 1-.619-.624V4.448a.443.443 0 0 0-.443-.443H4.443A.443.443 0 0 0 4 4.448v2.315a.443.443 0 0 0 .443.442H6.5a.78.78 0 0 1 .512.246a.76.76 0 0 1 .176.56H7.2v1.701a.76.76 0 0 1-.197.47a.76.76 0 0 1-.427.223H4.443a.443.443 0 0 0-.443.443v8.71a.44.44 0 0 0 .443.442h2.314a.44.44 0 0 0 .443-.443v-8.49a.74.74 0 0 1 .176-.427a.78.78 0 0 1 .512-.24h1.813a.725.725 0 0 1 .694.805V11.2v1.957a.444.444 0 0 0 .448.443h2.31a.443.443 0 0 0 .442-.443v-2.09a.75.75 0 0 1 .181-.427a.77.77 0 0 1 .512-.24h1.813a.75.75 0 0 1 .507.245a.76.76 0 0 1 .181.56l.011-.005v8.357a.443.443 0 0 0 .437.443h2.315a.443.443 0 0 0 .443-.443v-8.714a.443.443 0 0 0-.443-.443h-2.133a.73.73 0 0 1-.619-.624z");
}

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

.s5a3i0bah {
  stop-color: var(--svg-color--db1e83, #db1e83);
}

.t_5jv1b0x {
  stop-color: var(--svg-color--3538e0, #3538e0);
}

</style>
