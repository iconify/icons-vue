<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="mzfdxccyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:teletec" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.mzfdxccyy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.88 21.5v5h2.89m-12.66-5h3.83m-1.915 5v-5m29.903 3.324c-.008 2.253-3.94 2.177-3.83-.088c.005-1.133-.237-2.683 1.17-3.107c1.1-.442 2.669.242 2.66 1.547M13.483 24h1.885m1.006 2.5h-2.891v-5h2.89m5.903 2.5h1.885m1.006 2.5h-2.891v-5h2.89m1.544 0h3.83m-1.915 5v-5m3.458 2.5h1.885m1.006 2.5h-2.89v-5h2.89");
}

</style>
