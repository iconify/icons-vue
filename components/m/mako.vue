<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vy_4idbyz"/><path class="hf1vy_7sf"/><circle class="mgczgpfkw"/><circle class="r6yl_1bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mako" /></template>
<style>
.hf1vy_7sf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.483 14.156c-2.502 0-4.53 2.24-4.53 5.002a5.4 5.4 0 0 0 .653 2.586c-.835.711-1.526 1.543-1.993 2.508a6 6 0 0 0-.612 1.915h27.998a6 6 0 0 0-.613-1.915c-.467-.965-1.157-1.797-1.992-2.508a5.4 5.4 0 0 0 .653-2.586c0-2.762-2.028-5.002-4.53-5.002c-2.247 0-4.154 1.82-4.481 4.275A27 27 0 0 0 24 18.266a27 27 0 0 0-3.036.165c-.327-2.455-2.234-4.274-4.481-4.275");
}

.mgczgpfkw {
  cx: 16.328px;
  cy: 18.504px;
  r: 1.273px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r6yl_1bhq {
  cx: 31.672px;
  cy: 18.504px;
  r: 1.273px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vy_4idbyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.138 26.17H42.86M7.266 30.007h33.467M4.5 33.844h39M12.544 26.17c1.374-2.856 6.077-4.845 11.456-4.845s10.082 1.99 11.455 4.845");
}

</style>
