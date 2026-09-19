<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vg2q4b41h"/><path class="pb9su1bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-oppo" /></template>
<style>
.pb9su1bbf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.673 20.336L24 27.664l7.327-7.328");
}

.vg2q4b41h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.177 16.018l-7.37-7.37H12.193l-7.37 7.37a1.1 1.1 0 0 0-.058 1.496l18.399 21.454a1.1 1.1 0 0 0 1.672 0l18.399-21.454a1.1 1.1 0 0 0-.058-1.496");
}

</style>
