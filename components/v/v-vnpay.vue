<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rwk9nmbqf"/><path class="zg9lqkblu"/><g class="y9tr6bcfx"><path class="q_clrkbps"/><path class="ypwdfhixm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:v-vnpay" /></template>
<style>
.q_clrkbps {
  d: path("M18.222 30.789q-1.732 1.734-3.467 0m22.534-15.6c-1.262-1.156-2.89-.578-4.045.578L18.222 30.789m0-15.022c-4.622-4.622-10.4 1.155-5.778 5.778l5.2 5.2l-5.2-5.2m10.978-.578l-4.044-4.045");
}

.rwk9nmbqf {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("m28.622 37.722l14.445-14.444c.577-.578.577-1.733 0-2.311L34.4 12.3c-.578-.578-1.733-.578-2.311 0l-6.356 6.356L16.49 9.41c-.578-.578-1.734-.578-2.311 0l-9.245 9.245c-.578.577-.578 1.733 0 2.31L21.69 37.723c1.733 1.734 5.2 1.734 6.933 0Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ypwdfhixm {
  d: path("m21.689 22.7l-4.622-4.622c-.578-.578-1.445-1.445-2.311-1.156m0 3.467c-.578-.578-1.445-1.444-1.156-2.311m5.778 6.933l-4.622-4.622");
}

.zg9lqkblu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.733 18.656l-8.089 8.089q-3.466 3.465-6.933 0");
}

</style>
