<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="br4m5sb3k"/><circle class="gnob5dh6u"/><circle class="vkxuc4dbe"/><path class="ixselibua"/><path class="ywb84em3i"/><circle class="qr2izdbms"/><path class="wco5w9b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:techlore" /></template>
<style>
.br4m5sb3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.99 29.64c3.54.69 6.74 2 9.36 3.75m-30.7 0c2.62-1.75 5.82-3.06 9.36-3.75");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gnob5dh6u {
  cx: 20.012px;
  cy: 20.075px;
  r: 2.292px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ixselibua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.425 17.564c-.632-4.058-4-6.903-7.523-6.355c-1.936.302-3.512 1.57-4.435 3.322a.506.506 0 0 1-.906.001c-.927-1.751-2.506-3.018-4.446-3.32c-3.532-.55-6.908 2.294-7.54 6.352s1.72 7.793 5.251 8.343c2.884.45 5.662-1.365 6.929-4.254a.288.288 0 0 1 .526 0c1.266 2.887 4.036 4.7 6.91 4.252c3.522-.55 5.865-4.284 5.234-8.342Z");
}

.qr2izdbms {
  cx: 24px;
  cy: 24px;
  r: 18px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vkxuc4dbe {
  cx: 27.988px;
  cy: 20.075px;
  r: 2.292px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wco5w9b3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 6V2.5m12.728 8.772l2.475-2.475M11.272 36.728l-2.475 2.475M42 24h3.5");
}

.ywb84em3i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 36.68c5.04-2.21 6.18-7.53 6.29-8.26c-2.43-.1-4.69-1.35-6.29-3.31c-1.6 1.96-3.86 3.21-6.29 3.31c.11.73 1.25 6.05 6.29 8.26");
}

</style>
