<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpf0cgbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mycelium" /></template>
<style>
.xpf0cgbxi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 5q0-2.5 2.5-2.5T7.5 5q0 .775-.24 1.309q1.34 1.613 3.218 3.233q1.039-.928 2.281-1.661q.023-.144.099-.269q.075-.124.192-.212q.08-.06.174-.097t.193-.048q.1-.012.2.004q.099.016.191.057q1.258-.619 2.699-1.062Q16.5 6.13 16.5 6q0-2.5 2.5-2.5T21.5 6T19 8.5q-1.428 0-2.04-.816q-1.149.354-2.17.83q2.276 3.338 3.245 7.01q.22-.024.465-.024q1.036 0 1.768.732T21 18t-.732 1.768t-1.768.732Q16 20.5 16 18q0-1.262.637-1.887q-.911-3.61-3.18-6.89q-1.065.641-1.962 1.442q.017.151-.026.297q-.042.145-.139.263q-.06.074-.137.13t-.167.092t-.184.047q-.095.012-.189 0q-2.097 2.267-3.08 5.602Q8 17.71 8 18.5q0 1.036-.732 1.768T5.5 21Q3 21 3 18.5T5.5 16q.428 0 .804.125q1.059-3.237 3.109-5.521q-1.886-1.637-3.26-3.281Q5.665 7.5 5 7.5Q2.5 7.5 2.5 5");
}

</style>
