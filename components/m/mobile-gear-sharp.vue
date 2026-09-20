<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni5ra4x1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-gear-sharp" /></template>
<style>
.ni5ra4x1o {
  fill: currentColor;
  d: path("M11.539 15.154h1l.073-.827q.392-.075.667-.24t.483-.41l.727.365l.5-.865l-.654-.48q.127-.374.127-.703t-.127-.702l.654-.48l-.512-.854l-.715.353q-.208-.24-.483-.402q-.275-.161-.667-.236l-.073-.827h-1l-.073.827q-.393.075-.668.237t-.482.401L9.6 9.958l-.511.854l.653.48q-.126.374-.126.702t.126.702l-.653.481l.5.865l.727-.365q.207.246.482.41t.668.24zm-.595-2.06Q10.5 12.65 10.5 12t.444-1.094t1.094-.445t1.095.445t.444 1.094t-.444 1.094t-1.094.445t-1.095-.445M6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
