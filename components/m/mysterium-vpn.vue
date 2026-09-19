<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d9b0vnklo"/><path class="olhlxcc9p"/><path class="cu9mwqbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mysterium-vpn" /></template>
<style>
.cu9mwqbik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.667 29.417l.928-7.016l-1.444-6.5M17.5 27.25l-2.167-5.778l.619-5.674m6.191 8.357l-2.786 4.849m5.984-3.611l1.032 5.984m-5.881-4.23l6.913 3.198m8.873-7.841l4.024 7.738m-5.984.722l4.023-4.436M24 20.75l-.309 3.921M30.5 27.25l-2.683-2.683m-16.198-1.96l.206 10.318M6.77 29.52l4.849-2.992m7.635-10.524l1.651 7.532m-9.08 1.754l5.675 1.96m9.802-9.802l1.857 6.604m4.023-7.119l-4.539 4.642");
}

.d9b0vnklo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 20.75l6.5-6.5l13 13l-6.5 6.5l-6.5-6.5l-6.5 6.5l-6.5-6.5l-6.5 6.5l-6.5-6.5l13-13z");
}

.olhlxcc9p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.524 23.226l7.016-1.754l9.801 3.921l8.461-2.992l4.642-.207");
}

</style>
