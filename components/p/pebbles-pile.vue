<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8lyx4-es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pebbles-pile" /></template>
<style>
.x8lyx4-es {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 8.5q-.001-1.742 1.717-2.918q1.583-1.083 3.783-1.083t3.783 1.083Q17.751 6.758 17.75 8.5q.001 1.742-1.717 2.918q-1.583 1.083-3.783 1.083t-3.783-1.083Q6.749 10.242 6.75 8.5m-5 8q0-1.631 1.562-2.734q1.44-1.016 3.438-1.016t3.438 1.016q1.562 1.103 1.562 2.734t-1.562 2.734Q8.748 20.25 6.75 20.25t-3.438-1.016Q1.75 18.131 1.75 16.5m16-3.25q-4.5 0-4.5 3.5t4.5 3.5t4.5-3.5t-4.5-3.5");
}

</style>
