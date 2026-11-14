<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpkc9ycrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:prescriber" /></template>
<style>
.mpkc9ycrz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7M13 16.75q0-2.02 1.088-2.952q-1.607-.548-3.588-.548q-3.462 0-5.782 1.673Q2.25 16.702 2.25 19.5q0 1.75 1.75 1.75h9.3q-.3-.688-.3-1.5zm4.25-3.5h1q1.445 0 1.697 1.193q1.303.502 1.303 2.307v3q0 1.036-.732 1.768t-1.768.732h-2q-1.036 0-1.768-.732t-.732-1.768v-3q0-1.805 1.303-2.307q.252-1.193 1.697-1.193m0 3.5q-.967 0-1.399-.534q-.101.217-.101.534v3q0 .414.293.707t.707.293h2q1 0 1-1v-3q0-.317-.101-.534q-.432.534-1.399.534zM17 17.995q.122.005.25.005h1q.128 0 .25-.005V19.5H17z");
}

</style>
