<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7s_xtb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:plagiarism-outline-rounded" /></template>
<style>
.i7s_xtb8b {
  fill: currentColor;
  d: path("M11.45 17q.45 0 .888-.112t.812-.338l1.75 1.75q.275.275.7.275t.7-.275t.275-.7t-.275-.7l-1.75-1.75q.225-.375.338-.812T15 13.45Q15 12 13.975 11T11.5 10t-2.475 1.025T8 13.5t1 2.475T11.45 17m-1.012-2.437Q10 14.125 10 13.5t.438-1.062T11.5 12t1.063.438T13 13.5t-.437 1.063T11.5 15t-1.062-.437M6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h7.175q.4 0 .763.15t.637.425l4.85 4.85q.275.275.425.638t.15.762V20q0 .825-.587 1.413T18 22zm7-14V4H6v16h12V9h-4q-.425 0-.712-.288T13 8M6 4v5zv16z");
}

</style>
