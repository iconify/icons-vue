<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o--003via"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-scale-ratio" /></template>
<style>
.o--003via {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.789 4.859l4.25-1.771q.961-.401 1.922 0l4.655 1.94q.384.16.769 0l2.904-1.21q1.234-.515 2.348.227t1.113 2.08v10.708q.001 1.667-1.539 2.308l-4.25 1.771q-.961.401-1.922 0l-4.655-1.94q-.384-.16-.769 0l-2.904 1.21q-1.234.515-2.348-.227t-1.113-2.08V7.167Q2.249 5.5 3.789 4.859M14.75 9h-6.5q-2.5 0-2.5 2.5V13q0 2.5 2.5 2.5h7.5q2.5 0 2.5-2.5v-1.5q0-2.5-2.5-2.5z");
}

</style>
