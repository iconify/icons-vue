<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew5dkwehu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:touch-double-2-sharp" /></template>
<style>
.ew5dkwehu {
  fill: currentColor;
  d: path("m9.244 21l-5.613-7.165L4.666 12.8l3.392 2.079V7.692h1v4.289h2.269V6.019h1v5.962H19V21zm-4.9-11.842q-.056-.237-.065-.473q-.01-.237-.01-.493q0-2.565 1.797-4.379Q7.864 2 10.46 2q2.575 0 4.375 1.814t1.8 4.378q0 .218-.038.551l-.038.334l-.98-.11l.028-.287q.028-.288.028-.488q0-2.154-1.515-3.673T10.46 3Q8.285 3 6.777 4.517T5.269 8.185v.407q0 .2.05.4z");
}

</style>
