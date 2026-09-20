<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b99gtkbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nightlight" /></template>
<style>
.b99gtkbny {
  fill: currentColor;
  d: path("M14 22q-2.05 0-3.875-.788t-3.187-2.15t-2.15-3.187T4 11.988t.788-3.875t2.15-3.175t3.187-2.15T14 2q1.35 0 2.625.35t2.375 1q-2.275 1.325-3.637 3.588T14 12t1.363 5.063T19 20.65q-1.1.65-2.375 1T14 22");
}

</style>
