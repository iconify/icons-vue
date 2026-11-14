<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iybst_def"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wave-particle" /></template>
<style>
.iybst_def {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.25 6q0-1.625.813-2.437q.812-.813 2.437-.813q3.25 0 3.25 3.25T17.5 9.25T14.25 6M5.5 10.5q-2.22 0-3.708 4.252q-.049.141-.041.29t.073.283t.176.234t.252.149q.07.024.143.035q.073.01.147.006t.145-.023t.138-.05t.126-.077q.059-.044.108-.099t.087-.119t.062-.133Q4.345 12 5.5 12t2.292 3.248Q9.28 19.5 11.5 19.5t3.708-4.252Q16.345 12 17.5 12t2.292 3.248q.025.069.062.133q.038.064.087.119t.108.099t.126.077q.066.032.138.05q.071.019.145.023t.147-.006t.143-.035t.133-.062q.064-.038.119-.087t.099-.108q.045-.059.077-.126q.032-.066.05-.138q.019-.071.023-.145t-.006-.147t-.035-.143Q19.72 10.5 17.5 10.5t-3.708 4.252Q12.655 18 11.5 18t-2.292-3.248Q7.72 10.5 5.5 10.5");
}

</style>
