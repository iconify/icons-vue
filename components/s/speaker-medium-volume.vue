<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uu8n-dblb"/><path class="pii6j2bgy"/><path class="nonuuo2vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:speaker-medium-volume" /></template>
<style>
.nonuuo2vq {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("m102.52 27.23l-4.85 4.88c4.61 7.73 7.31 19.17 7.31 31.89s-2.7 24.16-7.31 31.9l4.84 4.88c5.83-8.85 9.12-21.93 9.12-36.78c0-14.84-3.28-27.92-9.11-36.77");
}

.pii6j2bgy {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("M51.75 64.06c0-23.58 6.5-43.29 15.23-48.56h-3.29c-3.39 0-10.21 9.87-14.31 24.51L37.12 55.39c-1.46.22-2.91.57-4.38.9c-.57-6.23-1.84-10.57-4.23-10.91c.11-.01-.31-.04-.31-.04h-8.18c-4.43 0-8.02 8.99-8.02 20.09c0 11.09 3.59 20.1 8.02 20.1h8.18s.41-.03.31-.05c2.43-.35 3.71-4.84 4.26-11.25l4.35 1.25l14.06 17.75s.11.04.27.08c4.35 11.74 10.01 19.32 11.73 19.32h3.8c-8.74-5.28-15.23-25-15.23-48.57");
}

.uu8n-dblb {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M76.7 15.5c-7.7 0-13.18 14.26-14.98 33.94c5.16.04 8.63 7.24 8.63 16.13c0 8.66-4.1 15.72-8.32 16.1c2.07 18.11 7.37 30.95 14.67 30.95c5.27 0 14.04-21.74 14.04-48.55c0-26.83-8.77-48.57-14.04-48.57");
}

</style>
