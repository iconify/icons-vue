<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3tjonbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:planet" /></template>
<style>
.y3tjonbka {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.873 6.873q-1.683 1.684-2.032 3.92q-3.195 2.239-3.097 4.21q.115 2.319 4.007 2.408q.671.016 1.382-.036Q9.178 19.25 12 19.25q3.003 0 5.127-2.123q1.768-1.769 2.064-4.147q.561-.407 1.053-.839q2.929-2.568 1.538-4.421q-1.187-1.58-5.08-1.242Q14.709 4.75 12 4.75q-3.003 0-5.127 2.123m12.382 4.14l-.059.052q-.206-1.74-1.195-3.155q2.034-.019 2.581.711q.557.741-1.327 2.392M3.242 14.929q-.045-.916 1.539-2.215q.156 1.762 1.099 3.199l-.094-.001q-2.498-.058-2.544-.983");
}

</style>
