<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_n55nbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:roundabout-right-outline-sharp" /></template>
<style>
.i_n55nbiw {
  fill: currentColor;
  d: path("M8.02 20v-5.477q-2.106-.12-3.563-1.622T3 9.269q0-2.211 1.539-3.74T8.289 4q2.128 0 3.64 1.447T13.562 9h5.518l-2.095-2.1l.708-.708L21 9.5l-3.308 3.308l-.713-.708l2.1-2.1h-6.514v-.692q0-1.785-1.246-3.046T8.29 5T5.252 6.252T4 9.269q0 1.785 1.271 3.031t3.056 1.246h.692V20z");
}

</style>
