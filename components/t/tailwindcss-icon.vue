<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":154};
const content = `<defs><linearGradient id="SVGJSB7ld0l" x1="-2.778%" x2="100%" y1="32%" y2="67.556%"><stop offset="0%" class="j3k6nbqkw"/><stop offset="100%" class="girh5hbqs"/></linearGradient></defs><path fill="url(#SVGJSB7ld0l)" class="gz5l6tbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:tailwindcss-icon" /></template>
<style>
.girh5hbqs {
  stop-color: var(--svg-color--0ed7b5, #0ed7b5);
}

.gz5l6tbob {
  d: path("M128 0Q76.8 0 64 51.2Q83.2 25.6 108.8 32c9.737 2.434 16.697 9.499 24.401 17.318C145.751 62.057 160.275 76.8 192 76.8q51.2 0 64-51.2q-19.2 25.6-44.8 19.2c-9.737-2.434-16.697-9.499-24.401-17.318C174.249 14.743 159.725 0 128 0M64 76.8q-51.2 0-64 51.2q19.2-25.6 44.8-19.2c9.737 2.434 16.697 9.499 24.401 17.318C81.751 138.857 96.275 153.6 128 153.6q51.2 0 64-51.2q-19.2 25.6-44.8 19.2c-9.737-2.434-16.697-9.499-24.401-17.318C110.249 91.543 95.725 76.8 64 76.8");
}

.j3k6nbqkw {
  stop-color: var(--svg-color--2298bd, #2298bd);
}

</style>
