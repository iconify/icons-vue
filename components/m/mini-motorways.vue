<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c6c0h142l"/><circle class="ypbmi7b9c"/><path class="hdkabo2hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mini-motorways" /></template>
<style>
.c6c0h142l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.417 32.062c6.305-6.305 6.305-16.528 0-22.833c-6.306-6.305-16.528-6.305-22.833 0c-6.306 6.305-6.306 16.528 0 22.833L24.022 43.5z");
}

.hdkabo2hr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.444 24.201l11.423 11.424");
}

.ypbmi7b9c {
  cx: 24px;
  cy: 20.645px;
  r: 5.029px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
