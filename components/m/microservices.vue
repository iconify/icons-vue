<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du1-8nvxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:microservices" /></template>
<style>
.du1-8nvxy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.75 1.75h-3.5q-2.5 0-2.5 2.5v3.5q0 1.559.973 2.146L5.64 13.75H4.25q-2.5 0-2.5 2.5v3.5q0 1.036.732 1.768t1.768.732h3.5q1.036 0 1.768-.732t.732-1.768v-1h3.5v1q0 2.5 2.5 2.5h3.5q1.036 0 1.768-.732t.732-1.768v-3.5q0-2.5-2.5-2.5h-1.39l-3.164-3.956q.167-.122.322-.276q.732-.732.732-1.768v-3.5q0-1.036-.732-1.768T13.75 1.75m-.11 8.5l2.8 3.5h-.19q-2.5 0-2.5 2.5v1h-3.5v-1q0-2.5-2.5-2.5h-.19l2.8-3.5z");
}

</style>
