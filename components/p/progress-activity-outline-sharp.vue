<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krhl0vbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:progress-activity-outline-sharp" /></template>
<style>
.krhl0vbcp {
  fill: currentColor;
  d: path("M8.125 21.213q-1.825-.788-3.187-2.15t-2.15-3.188T2 11.988t.788-3.875t2.15-3.175t3.187-2.15T12 2v2Q8.675 4 6.337 6.338T4 12t2.338 5.663T12 20t5.663-2.337T20 12h2q0 2.05-.788 3.875t-2.15 3.188t-3.175 2.15t-3.875.787t-3.887-.787");
}

</style>
