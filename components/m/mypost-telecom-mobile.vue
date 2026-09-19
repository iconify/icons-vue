<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="n03-3gjzk"/><path class="fs00soyyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mypost-telecom-mobile" /></template>
<style>
.fs00soyyz {
  d: path("M32.977 40.438a.988.988 0 1 1 0-.001zm-22.649 2.675v-10.2c0-5.603 4.811-9.095 9.096-9.095s6.151 2.046 7.02 3.03m.212-15.205a7.143 7.143 0 1 1 0-.008z");
}

.n03-3gjzk {
  d: path("M30.24 19.1c-2.002.008-3.798 1.76-3.798 3.798v16.864c0 1.972 1.807 3.738 3.738 3.738h3.751c2.042 0 3.74-1.754 3.74-3.74V22.733c0-2.02-1.806-3.656-3.75-3.648zm-3.772 5.818h11.2m-11.2 12.752h11.2M30.3 22.003h3.33");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
