<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj1ao7oen"/><path class="c5c-6bb-h"/><path class="nmq4hnb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-auto-stories" /></template>
<style>
.c5c-6bb-h {
  fill: currentColor;
  d: path("m19 .5l-5 5V15l5-4.5z");
}

.gj1ao7oen {
  fill: currentColor;
  d: path("M3 6.71v9.91c1.14-.41 2.31-.62 3.5-.62s2.36.21 3.5.62v-9.9C8.89 6.25 7.7 6 6.5 6c-1.22 0-2.39.24-3.5.71");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.nmq4hnb7s {
  fill: currentColor;
  d: path("M22.47 5.2c-.47-.24-.96-.44-1.47-.61v12.03c-1.14-.41-2.31-.62-3.5-.62c-1.9 0-3.78.54-5.5 1.58V5.48C10.38 4.55 8.51 4 6.5 4c-1.79 0-3.48.44-4.97 1.2c-.33.16-.53.51-.53.88v12.08c0 .58.47.99 1 .99q.24 0 .48-.12C3.69 18.4 5.05 18 6.5 18c2.07 0 3.98.82 5.5 2c1.52-1.18 3.43-2 5.5-2c1.45 0 2.81.4 4.02 1.04q.24.12.48.12c.52 0 1-.41 1-.99V6.08c0-.37-.2-.72-.53-.88M10 16.62C8.86 16.21 7.69 16 6.5 16s-2.36.21-3.5.62V6.71C4.11 6.24 5.28 6 6.5 6c1.2 0 2.39.25 3.5.72z");
}

</style>
