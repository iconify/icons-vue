<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="egr6ql1bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shaadi" /></template>
<style>
.egr6ql1bj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.327 39.078a9.04 9.04 0 0 0 6.356 4.363c2.328.132 5.444 0 7.258 0c3.632 0 8.05-4.363 8.05-9.696a8.73 8.73 0 0 0-7.29-8.762s-4.703-.962-8.878-1.794c-3.818-.762-5.813-3.504-5.813-8.837c0-9.115 4.63-9.412 6.355-9.696a11.9 11.9 0 0 1 3.814 0a7.76 7.76 0 0 1 6.006 4.538");
}

</style>
