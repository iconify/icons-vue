<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ikbj1tb0e"/><path class="och8t-vmd"/><circle class="xw44ieb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:money-manager" /></template>
<style>
.ikbj1tb0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.072 20.726a12.5 12.5 0 0 1 3.647-5.67c-.932-.745 0-5.376 0-5.376s3.726 1.65 4.392 2.422c0 0 2.874-3.487 11.206-3.487S43.5 15.057 43.5 23.654s-6.228 11.339-6.228 11.339a20 20 0 0 1-1.491 4.392H32.48a21 21 0 0 1-1.41-2.529s-2.635.32-4.525.32a23 23 0 0 1-3.966-.426a6.4 6.4 0 0 1-.932 2.635h-3.593c-1.118-.958-1.677-3.966-1.677-3.966S7.327 31.32 5.41 28.87c-1.039-1.943-.906-6.255-.906-6.255a7.94 7.94 0 0 1 3.567-1.89");
}

.och8t-vmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.544 13.779a11.55 11.55 0 0 1 7.347-2.156a13.2 13.2 0 0 1 7.985 2.529");
}

.xw44ieb-e {
  cx: 11.612px;
  cy: 21.285px;
  r: 0.75px;
  fill: currentColor;
}

</style>
