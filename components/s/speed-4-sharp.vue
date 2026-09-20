<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4aeoybwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-4-sharp" /></template>
<style>
.n4aeoybwy {
  fill: currentColor;
  d: path("M11.277 15.492q.627.293 1.257.048q.63-.246.822-.898q.667-2.194 1.278-4.376q.61-2.181 1.212-4.406q-1.325 1.879-2.61 3.744q-1.286 1.865-2.601 3.762q-.385.551-.181 1.19t.823.936M4.457 19q-.701-1.287-1.085-2.454q-.383-1.167-.378-2.657q0-1.847.732-3.47t1.965-2.83t2.87-1.898T12 5q1.864 0 3.503.71q1.64.711 2.858 1.93t1.929 2.857Q21 12.137 21 14q0 1.466-.397 2.599T19.503 19z");
}

</style>
