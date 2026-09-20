<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isn76i-lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:toll-outline" /></template>
<style>
.isn76i-lh {
  fill: currentColor;
  d: path("M10.037 16.964Q8 14.927 8 12t2.036-4.963T15 5t4.964 2.036T22 12t-2.036 4.964T15 19t-4.963-2.036M7 18.712q-2.266-.604-3.633-2.475T2 12t1.367-4.236T7 5.288V6.35q-1.8.625-2.9 2.175T3 12t1.1 3.475T7 17.65zm12.25-2.462Q21 14.5 21 12t-1.75-4.25T15 6t-4.25 1.75T9 12t1.75 4.25T15 18t4.25-1.75");
}

</style>
