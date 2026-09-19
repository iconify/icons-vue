<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="re8_hs55z"/><path class="gurlemb8i"/><path class="a0ok5fo2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vanilla" /></template>
<style>
.a0ok5fo2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.654 14.582c1.57-3.47 9.645-9.75 18.785-5.6c9.14 4.149 11.96 12.272 10.71 18.784c-1.065 5.552-2.032 6.03-2.032 6.03");
}

.gurlemb8i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 12.626c5.883 1.122 7.232 3.486 8.296 7.294m16.144 8.233l3.697-12.898a1.905 1.905 0 0 0-1.263-2.343l-1.764-.55a1.905 1.905 0 0 0-2.394 1.275l-3.15 10.597c-3.533-2.58-9.676-1.064-10.823 4.99c-1.01 5.327 2.16 6.867 2.16 6.867");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.re8_hs55z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.776 42.5c3.981-3.659 3.668-8.53 0-12.178c-4.318-4.294-11.103-1.883-17.44 3.949C12 40.103 10.654 42.5 10.654 42.5M5.5 39.206s.949-4.71 3.023-9.814s4.972-13.37 12.673-11.215c4.206 1.178 4.61 3.563 4.61 3.563");
}

</style>
