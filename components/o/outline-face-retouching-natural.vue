<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5qtglbrh"/><circle class="pt3nek-ut"/><circle class="t8-_arz4f"/><path class="k80ni3bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-face-retouching-natural" /></template>
<style>
.e5qtglbrh {
  fill: currentColor;
  d: path("M19.89 10.75c.07.41.11.82.11 1.25c0 4.41-3.59 8-8 8s-8-3.59-8-8c0-.05.01-.1 0-.14c2.6-.98 4.69-2.99 5.74-5.55c3.38 4.14 7.97 3.73 8.99 3.61l-.89-1.93c-.13.01-4.62.38-7.18-3.86c1.01-.16 1.71-.15 2.59-.01c2.52-1.15 1.93-.89 2.76-1.26A9.6 9.6 0 0 0 12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10c0-1.43-.3-2.78-.84-4.01zM8.08 5.03a8.05 8.05 0 0 1-3.66 4.44a8.05 8.05 0 0 1 3.66-4.44");
}

.k80ni3bwl {
  fill: currentColor;
  d: path("m23 4.5l-2.4-1.1L19.5 1l-1.1 2.4L16 4.5l2.4 1.1L19.5 8l1.1-2.4z");
}

.pt3nek-ut {
  cx: 15px;
  cy: 13px;
  r: 1.25px;
  fill: currentColor;
}

.t8-_arz4f {
  cx: 9px;
  cy: 13px;
  r: 1.25px;
  fill: currentColor;
}

</style>
