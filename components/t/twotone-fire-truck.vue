<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5se8f81e"/><path class="sn40p8g3v"/><path class="r-f3j1bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-fire-truck" /></template>
<style>
.k5se8f81e {
  fill: currentColor;
  d: path("M3 16h1.78c.55-.61 1.34-1 2.22-1s1.67.39 2.22 1H12v-3H3zm11 0h.78c.55-.61 1.34-1 2.22-1s1.67.39 2.22 1H21v-3h-7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.r-f3j1bby {
  fill: currentColor;
  d: path("M11 8.5h-1v-2h1V5H1v1.5h1v2H1V10h10zm-5.75 0H3.5v-2h1.75zm3.25 0H6.75v-2H8.5z");
}

.sn40p8g3v {
  fill: currentColor;
  d: path("m22.9 10.69l-1.44-4.32A2.01 2.01 0 0 0 19.56 5H19V4c0-.55-.45-1-1-1h-1c-.55 0-1 .45-1 1v1h-2c-1.1 0-2 .9-2 2v4H1v5c0 1.1.9 2 2 2h1c0 1.66 1.34 3 3 3s3-1.34 3-3h4c0 1.66 1.34 3 3 3s3-1.34 3-3h3v-6.68c0-.21-.03-.42-.1-.63M7 19c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m5-3H9.22c-.55-.61-1.33-1-2.22-1s-1.67.39-2.22 1H3v-3h9zm2-9h5.56l1.33 4H14zm3 12c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m4-3h-1.78c-.55-.61-1.34-1-2.22-1s-1.67.39-2.22 1H14v-3h7z");
}

</style>
