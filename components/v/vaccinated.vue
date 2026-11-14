<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me3lwphke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:vaccinated" /></template>
<style>
.me3lwphke {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7m8.008 9.586l2.007-2.007Q13.586 13.25 10.5 13.25q-3.462 0-5.782 1.673Q2.25 16.702 2.25 19.5q0 1.75 1.75 1.75h8.94q-1.514-2.332.818-4.664m3.712-1.944l-2.828 2.828q-1.944 1.944 0 3.888t3.888 0l2.828-2.828q1.944-1.944 0-3.888t-3.888 0m1.944 1.944q-.505-.506-1.192-.575l.308-.309q.884-.883 1.768 0q.883.884 0 1.768l-.309.308q-.069-.687-.575-1.192m-1.768 1.06q.147-.146.354-.146t.354.146t.146.354t-.146.354q-.147.146-.354.146t-.354-.146T17.5 18t.146-.354m-1.944.884l.309-.308q.069.687.575 1.192q.505.506 1.192.575l-.308.309q-.884.883-1.768 0q-.883-.884 0-1.768");
}

</style>
