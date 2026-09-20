<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osircmb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:where-to-vote" /></template>
<style>
.osircmb4w {
  fill: currentColor;
  d: path("m10.95 12.6l4.258-4.258l-.714-.713l-3.544 3.544l-1.4-1.4l-.713.714zM12 21.02q-3.525-3.118-5.31-5.815q-1.786-2.697-1.786-4.909q0-3.173 2.066-5.234Q9.037 3 12 3t5.03 2.062q2.066 2.061 2.066 5.234q0 2.212-1.785 4.909q-1.786 2.697-5.311 5.814");
}

</style>
