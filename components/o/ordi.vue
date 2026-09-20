<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="aabnj4b6e"><path class="qvqmpou4v"/><path clip-rule="evenodd" class="phcujzb0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ordi" /></template>
<style>
.aabnj4b6e {
  fill: var(--svg-color--fefefe, #fefefe);
}

.phcujzb0k {
  fill-rule: evenodd;
  d: path("M12 14.999a3.001 3.001 0 0 0 2.121-5.121a3.003 3.003 0 0 0-4.242 0A3 3 0 0 0 12 14.999m0-1.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.qvqmpou4v {
  d: path("M6.075 5H9.5v2h-3v4.58l-.5.35v.55l.5.325V17h3v2H6.075L4.5 17v-4H3v-2h1.5V7zm11.85 0H14.5v2h3v4.58l.5.35v.55l-.5.325V17h-3v2h3.425l1.575-2v-4H21v-2h-1.5V7z");
}

</style>
