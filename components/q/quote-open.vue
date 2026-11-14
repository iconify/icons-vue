<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x55lymo6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:quote-open" /></template>
<style>
.x55lymo6n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 15.5q0-7.208 6.221-9.696q.069-.028.142-.041t.146-.013t.146.016t.14.045t.129.071t.113.094t.092.115t.067.13q.056.139.054.288t-.061.286q-.058.138-.165.242t-.245.159Q6.27 8.6 5.094 11.806Q5.894 11.5 7 11.5q4 0 4 4t-4 4t-4-3.999zm10 0q0-7.208 6.221-9.696q.069-.028.142-.041t.146-.013q.074.001.146.016q.073.016.14.045t.129.071t.113.094t.092.115q.04.062.067.13q.056.139.054.288t-.061.286q-.058.138-.165.242t-.245.159q-3.509 1.404-4.685 4.61q.8-.306 1.906-.306q4 0 4 4t-4 4t-4-4");
}

</style>
