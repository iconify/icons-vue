<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ftgoz5oej"/><path class="q1yfwbc3u"/><g class="y9tr6bcfx"><path class="n7gb_8bap"/><path class="u-ymg_39u"/></g><path class="fwm2g6yhr"/><path class="j-wg_eb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spritpreise-alt" /></template>
<style>
.ftgoz5oej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 28.856l10.447-10.48L25.289 28.75L14.86 39.21zM40.812 14.8a2.687 2.687 0 0 1 2.683 2.691a2.69 2.69 0 0 1-2.683 2.692a2.69 2.69 0 0 1-2.684-2.692a2.69 2.69 0 0 1 2.684-2.692zM26.87 12.054v3.833h4.009l-4.897 7.628v-4.243l-3.75-.091z");
}

.fwm2g6yhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.58 22.02V11.244a2.454 2.454 0 0 1 2.453-2.454h11.044a2.454 2.454 0 0 1 2.454 2.454v24.541a2.454 2.454 0 0 1-2.454 2.454H21.033a2.454 2.454 0 0 1-2.454-2.454v-.305");
}

.j-wg_eb8q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 17.491v15.274a2.686 2.686 0 0 1-2.686 2.686h0a2.686 2.686 0 0 1-2.686-2.686v-7.532c0-.95-.769-1.718-1.718-1.718h-1.88");
}

.n7gb_8bap {
  d: path("M11.359 31.896v-3.69h7.07");
}

.q1yfwbc3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.844 15.733l-.352-.371l-5.137-5.42");
}

.u-ymg_39u {
  d: path("m15.913 30.722l2.516-2.516l-2.516-2.515");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
