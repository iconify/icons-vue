<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="eysoax7hn"/><ellipse class="whyjxcp-d"/></g><g class="y9tr6bcfx"><path class="c9o28fbzr"/><path class="s_l4iibod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:the-ssum" /></template>
<style>
.c9o28fbzr {
  d: path("M32.781 34.96V15.004c0-9.978-17.562-9.978-17.562 0V34.96");
}

.eysoax7hn {
  d: path("M32.868 32.613A24.75 24.75 0 0 1 43.5 40.48m-39 0a24.75 24.75 0 0 1 10.632-7.868");
}

.s_l4iibod {
  d: path("M17.614 22.587c-1.596-2.395-.798-6.785 2.395-6.785c2.395 0 3.592 1.996 3.991 3.193c.4-1.197 1.597-3.193 3.991-3.193c3.193 0 3.992 3.991 2.395 6.785c-3.193 4.39-5.587 7.584-6.386 7.584s-3.193-3.193-6.386-7.584M21.702 9.66c-2.395.798-4.39 2.794-4.39 4.79");
}

.whyjxcp-d {
  cx: 24px;
  cy: 34.96px;
  rx: 8.781px;
  ry: 2.395px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
