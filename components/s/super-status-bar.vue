<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="dtej41h5k"/><path class="gt-cm4b7h"/><path class="r6wlaubpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:super-status-bar" /></template>
<style>
.dtej41h5k {
  d: path("m9.365 24.028l.002-.016l-.002-11.039L24.042 4.5l14.593 8.426v10.957m0 5.952V35l-14.723 8.5l-14.547-8.241V30.17");
}

.gt-cm4b7h {
  d: path("m14.107 15.783l9.74-5.624l9.953 5.746v5.197l-9.682-5.59l-4.793 2.768l14.52 8.383l4.746-2.773m.041 5.683L23.85 38.127l-14.462-8.56");
}

.r6wlaubpr {
  d: path("m9.435 24.12l14.672 8.47l4.767-2.752l-14.87-8.586v-5.271");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
