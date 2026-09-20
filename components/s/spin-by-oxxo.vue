<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="ja_w9lbvo"/><path class="xjuyr1l7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spin-by-oxxo" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.ja_w9lbvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.783 34.668c1.015 1.273 2.29 1.747 4.061 1.747h2.453c2.282 0 4.132-1.781 4.132-3.979v-.017c0-2.197-1.85-3.979-4.132-3.979h-2.705c-2.285 0-4.137-1.783-4.137-3.983c0-2.204 1.856-3.992 4.145-3.992h2.44c1.772 0 3.045.475 4.061 1.748m9.189-5.479c0 1.922-1.56 3.48-3.484 3.48a3.481 3.481 0 1 1 0-6.96a3.48 3.48 0 0 1 3.484 3.48");
}

.xjuyr1l7c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.292 15.757c-5.3-2.767-14.333-3.34-21.582 4.11c5.375-8.249 16.436-10.12 23.62-6.55");
}

</style>
