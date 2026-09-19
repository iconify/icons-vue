<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a3jf26b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:themes" /></template>
<style>
.a3jf26b8s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24.974V38.5a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4V23.24a2.915 2.915 0 0 1-4.869-2.166V15.72c0-1.618-1.302-2.921-2.92-2.921s-2.922 1.303-2.922 2.921v1.46c0 1.619-1.303 2.922-2.92 2.922s-2.922-1.303-2.922-2.921v-1.46c0-1.62-1.303-2.922-2.921-2.922s-2.921 1.303-2.921 2.921v9.25c0 1.618-1.303 2.921-2.921 2.921s-2.921-1.303-2.921-2.92v-9.25a2.915 2.915 0 0 0-2.921-2.922v.005a2.915 2.915 0 0 0-2.922 2.92v6.33a2.915 2.915 0 0 1-2.92 2.92M42.5 9.5a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4z");
}

</style>
