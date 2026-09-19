<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q789kub_v"/><path class="sbnf7074d"/><circle class="t8-_arz4f"/><circle class="pt3nek-ut"/><path class="k4h2zxbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-face-retouching-natural" /></template>
<style>
.k4h2zxbpl {
  fill: currentColor;
  d: path("M20.6 3.4L19.5 1l-1.1 2.4L16 4.5l2.4 1.1L19.5 8l1.1-2.4L23 4.5z");
}

.pt3nek-ut {
  cx: 15px;
  cy: 13px;
  r: 1.25px;
  fill: currentColor;
}

.q789kub_v {
  fill: currentColor;
  d: path("M10.66 4.12c2.55 4.23 7.03 3.87 7.18 3.86l-.57-1.25L12.4 4.5l.85-.39C12.84 4.04 12.43 4 12 4c-.46 0-.91.05-1.34.12m-2.58.91a8.05 8.05 0 0 0-3.66 4.44a8.05 8.05 0 0 0 3.66-4.44");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.sbnf7074d {
  fill: currentColor;
  d: path("M19.89 10.75c.07.41.11.82.11 1.25c0 4.41-3.59 8-8 8s-8-3.59-8-8c0-.05.01-.1 0-.14c2.6-.98 4.69-2.99 5.74-5.55c3.38 4.14 7.97 3.73 8.99 3.61l-.89-1.93c-.13.01-4.62.38-7.18-3.86c1.01-.16 1.71-.15 2.59-.01l2.12-.97l.64-.29A9.6 9.6 0 0 0 12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10c0-1.43-.3-2.78-.84-4.01zM8.08 5.03a8.05 8.05 0 0 1-3.66 4.44a8.05 8.05 0 0 1 3.66-4.44");
}

.t8-_arz4f {
  cx: 9px;
  cy: 13px;
  r: 1.25px;
  fill: currentColor;
}

</style>
