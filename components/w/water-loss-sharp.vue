<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je84shrcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:water-loss-sharp" /></template>
<style>
.je84shrcs {
  fill: currentColor;
  d: path("M6.45 15q1.125-.5 2.3-.75t2.375-.25q.75 0 1.488.1t1.462.3q1.25.35 1.913.475T17.4 15h.15l1.2-11H5.25zM5.2 22L3 2h18l-2.2 20z");
}

</style>
