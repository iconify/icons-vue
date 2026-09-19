<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ef8ccbc5z"/><path class="jh3p5qbbc"/><path class="yfswlabum"/><path class="nuen1ab7q"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sheepy-horn" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ef8ccbc5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.168 21.999h10.098s1.415-9.688-5.17-9.564s-4.928 9.564-4.928 9.564");
}

.jh3p5qbbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.382 12.89s-3.39 1.283-1.654 4.118s4.34-.222 4.34-.222m8.756 5.213h10.098s1.415-9.688-5.17-9.564s-4.928 9.564-4.928 9.564");
}

.nuen1ab7q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.547 39.99a6.3 6.3 0 0 1 5.357-5.423c4.821-.643 7.808 3.341 7.808 3.341");
}

.yfswlabum {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.038 12.89s-3.39 1.283-1.654 4.118s4.34-.222 4.34-.222M7.443 26.793c.218.192 29.173 0 29.173 0s1.783 10.25-7.328 12.692s-13.753-.283-16.637-4.624s-2.863-6.232-2.863-8.018");
}

</style>
