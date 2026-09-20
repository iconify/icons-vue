<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n0yfkkbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:wifi-1-48-regular" /></template>
<style>
.n0yfkkbey {
  fill: currentColor;
  d: path("M24 33a3 3 0 1 1 0 6a3 3 0 0 1 0-6m0-7c4.212 0 7.813 2.603 9.287 6.283a1.25 1.25 0 0 1-2.321.93a7.503 7.503 0 0 0-13.93 0a1.25 1.25 0 1 1-2.321-.93A10 10 0 0 1 24 26m0-8c6.377 0 11.931 3.512 14.839 8.7a1.25 1.25 0 1 1-2.18 1.222C34.172 23.49 29.434 20.5 23.998 20.5s-10.174 2.99-12.658 7.422A1.25 1.25 0 0 1 9.159 26.7C12.067 21.512 17.622 18 24 18m0-8c8.497 0 15.961 4.416 20.225 11.072a1.25 1.25 0 0 1-2.106 1.349C38.295 16.452 31.608 12.5 24 12.5S9.704 16.452 5.881 22.42a1.25 1.25 0 0 1-2.106-1.348C8.038 14.416 15.503 10 24 10");
}

</style>
