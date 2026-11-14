<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruogq3b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wrestling-headgear" /></template>
<style>
.ruogq3b1p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.52 5.52q-2.026 2.026-2.244 4.8q-2.526.522-2.526 4.93q0 4.857 3.066 4.996q7.184 3.517 14.368 0q3.066-.139 3.066-4.996q0-4.408-2.526-4.93q-.218-2.774-2.244-4.8Q15.21 3.25 12 3.25T6.52 5.52m10.502 14.029q-5.022 1.892-10.044 0Q8.25 18.378 8.25 15.25q0-4.357-2.468-4.917q.209-2.162 1.799-3.752Q9.411 4.75 12 4.75t4.419 1.831q1.59 1.59 1.799 3.752q-2.468.56-2.468 4.917q0 3.128 1.272 4.299");
}

</style>
