<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgu3l2b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:next-plan-sharp" /></template>
<style>
.mgu3l2b7c {
  fill: currentColor;
  d: path("M6 14h2q0-1.475 1.075-2.488T11.65 10.5q.9 0 1.675.413T14.6 12H13v2h5V9h-2v1.55q-.8-.95-1.912-1.5T11.65 8.5q-2.375 0-4.012 1.6T6 14m6 8q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
