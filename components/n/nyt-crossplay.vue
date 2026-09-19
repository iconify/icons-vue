<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w497wpbwx"/><path class="hz-eej-vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nyt-crossplay" /></template>
<style>
.hz-eej-vj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.233 28.288l-.02.065a5.5 5.5 0 0 1-6.87 3.653h0a5.5 5.5 0 0 1-3.653-6.87l1.639-5.362a5.5 5.5 0 0 1 6.87-3.653h0a5.5 5.5 0 0 1 3.653 6.87l-.02.066m6.692-4.504c.243.373.557.606 1.349.848l.184.057c.653.2 1.344-.168 1.543-.821h0a1.236 1.236 0 0 0-.82-1.543m-1.053-2.476c.41-.173.801-.19 1.592.054l.183.058c.653.2 1.02.89.82 1.543h0a1.234 1.234 0 0 1-1.542.82m-.909-.277l.909.278");
}

.w497wpbwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.393 6.424l22.574 6.901L36.065 35.9c-1.41 4.614-6.302 7.215-10.916 5.804l-14.214-4.345c-4.614-1.41-7.215-6.302-5.804-10.917l4.345-14.213c1.411-4.614 6.303-7.215 10.917-5.804");
}

</style>
