<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmxl87byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-4-outline-sharp" /></template>
<style>
.tmxl87byn {
  fill: currentColor;
  d: path("M4.496 19q-.66-1.17-1.075-2.418q-.415-1.25-.415-2.582q0-1.868.709-3.51t1.923-2.857t2.858-1.924T12.006 5q.383 0 .746.037t.746.104l-.652.915q-.215-.037-.42-.047T12.006 6Q8.656 6 6.33 8.325T4.006 14q0 1.05.287 2.063T5.106 18H18.9q.55-.9.825-1.925T20 14q0-1.616-.609-3.085q-.608-1.469-1.77-2.594l.314-1.098q1.47 1.29 2.265 3.051T21 14q0 1.337-.406 2.584T19.561 19zm6.781-3.508q.627.292 1.256.046q.63-.246.823-.896q.667-2.188 1.271-4.37t1.194-4.4q-1.319 1.872-2.598 3.735t-2.589 3.759q-.384.551-.18 1.19t.823.936m.646-1.363");
}

</style>
