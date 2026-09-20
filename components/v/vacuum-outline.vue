<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3g10xbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vacuum-outline" /></template>
<style>
.g3g10xbkk {
  fill: currentColor;
  d: path("M2.23 20.772q-.73-.729-.73-1.77t.729-1.771t1.769-.731t1.771.729t.731 1.769t-.728 1.771t-1.77.731t-1.771-.728m2.828-.713Q5.5 19.617 5.5 19t-.441-1.059Q4.617 17.5 4 17.5t-1.059.441Q2.5 18.383 2.5 19t.441 1.059Q3.383 20.5 4 20.5t1.059-.441M7.75 21.5q.177-.258.284-.495t.193-.505h2.504V13q0-1.031-.734-1.766q-.735-.734-1.766-.734H3.5v4.039q-.237.019-.509.07t-.491.137V9.5h3V5.6q0-1.716 1.192-2.908T9.599 1.5q1.247 0 2.272.676t1.498 1.816L20.348 20.5H22.5v1h-6v-1h2.77L12.466 4.408q-.377-.88-1.145-1.394T9.608 2.5q-1.3 0-2.204.904T6.5 5.6v3.9h1.73q1.459 0 2.48 1.021T11.73 13v8.5zm-.635-6");
}

</style>
