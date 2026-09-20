<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywgqedblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-3-outline-sharp" /></template>
<style>
.ywgqedblj {
  fill: currentColor;
  d: path("M3.006 14q0-1.966.797-3.726t2.268-3.051l.314 1.098q-1.162 1.125-1.77 2.594q-.61 1.469-.61 3.085q0 1.05.276 2.075T5.107 18h13.792q.525-.925.813-1.937T20 14q0-3.35-2.325-5.675T12 6q-.215 0-.42.01t-.42.046l-.652-.916q.383-.067.746-.104T12 5q1.868 0 3.51.709t2.858 1.924t1.923 2.857T21 14q0 1.333-.416 2.582Q20.17 17.83 19.51 19H4.445q-.627-1.17-1.035-2.416Q3 15.337 3.006 14m9.723 1.492q.619-.298.823-.936t-.18-1.19q-1.31-1.897-2.59-3.76q-1.278-1.862-2.597-3.735q.59 2.22 1.194 4.401q.604 2.182 1.271 4.37q.194.65.823.896t1.256-.046m-.646-1.363");
}

</style>
