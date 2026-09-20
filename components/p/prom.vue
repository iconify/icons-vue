<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG67aPobbp)" class="ty53c-bnl"/><path fill="url(#SVG5lGiYdgJ)" class="g3zip1jvw"/><defs><linearGradient id="SVG67aPobbp" x1="14.355" x2="8.154" y1="3.24" y2="10.538" gradientUnits="userSpaceOnUse"><stop class="uj9o2mbff"/><stop offset="1" class="st-qj8kka"/></linearGradient><linearGradient id="SVG5lGiYdgJ" x1="16.504" x2="7.202" y1="10.146" y2="17.523" gradientUnits="userSpaceOnUse"><stop class="uj9o2mbff"/><stop offset="1" class="st-qj8kka"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:prom" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g3zip1jvw {
  d: path("M17.5 10.262a5.9 5.9 0 0 0-.892-3.133l-4.911 3.465l-4.936 3.48l-.261.186l.012 6.74s6.492-4.33 8.538-5.921c1.522-1.186 2.45-2.847 2.45-4.817");
}

.st-qj8kka {
  stop-color: var(--svg-color--ee448a, #ee448a);
}

.ty53c-bnl {
  d: path("m17.38 5.172l-9.845 6.953a5.87 5.87 0 0 1-.893-3.132C6.643 5.682 9.356 3 12.708 3a6.07 6.07 0 0 1 4.673 2.172");
}

.uj9o2mbff {
  stop-color: var(--svg-color--e2d177, #e2d177);
}

</style>
