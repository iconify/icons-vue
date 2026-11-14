<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swinw4b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:oil-field-map" /></template>
<style>
.swinw4b6c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.418 1.527q.049-.06.109-.109q.116-.094.259-.137q.143-.042.291-.027q.149.015.28.086t.225.187Q16 5.734 16 8q0 4-4 4T8 8q0-2.266 3.418-6.473M9.5 8q0-1.561 2.5-4.794Q14.5 6.439 14.5 8q0 2.5-2.5 2.5T9.5 8m-1.212 3.712q-.957-.956-1.318-2.159l-4.181 1.393q-1.539.513-1.539 2.135v6.838q0 1.152.934 1.825t2.027.31l3.612-1.204q.207-.069.419-.016l7.152 1.788q.138.034.276.051q.156.077.33.077q.205 0 .381-.104q.135-.028.27-.072l4.56-1.52q1.539-.513 1.539-2.135v-6.838q0-1.152-.934-1.825t-2.027-.31l-3.572 1.191q-.227.298-.505.575Q14.175 13.25 12 13.25t-3.712-1.538");
}

</style>
