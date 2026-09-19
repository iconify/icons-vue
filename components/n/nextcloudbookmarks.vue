<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q9k3gvbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nextcloudbookmarks" /></template>
<style>
.q9k3gvbmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.5 21.5 0 1 0 45.5 24A21.51 21.51 0 0 0 24 2.5m0 11.18l3.59 6.54l7.18 1.51l-5 5.51l.82 7.46L24 31.56l-6.68 3.1l.87-7.45l-5-5.54l7.2-1.46z");
}

</style>
