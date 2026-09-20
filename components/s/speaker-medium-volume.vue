<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dwccgcc3q"/><path class="xzk4vgbua"/><path class="u_rinn77l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:speaker-medium-volume" /></template>
<style>
.dwccgcc3q {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M7 10s-2 0-2 2v12c0 2 2 2 2 2h6l8 8s1 1 2 1h1s1 0 1-1V2s0-1-1-1h-1c-1 0-2 1-2 1l-8 8z");
}

.u_rinn77l {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M28.709 25.959a.998.998 0 0 1-.636-1.772A7.98 7.98 0 0 0 31 18a7.97 7.97 0 0 0-2.988-6.236a1 1 0 1 1 1.254-1.558A9.96 9.96 0 0 1 33 18a9.97 9.97 0 0 1-3.657 7.731a1 1 0 0 1-.634.228");
}

.xzk4vgbua {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("m13 26l8 8s1 1 2 1h1s1 0 1-1V2s0-1-1-1h-1c-1 0-2 1-2 1l-8 8z");
}

</style>
