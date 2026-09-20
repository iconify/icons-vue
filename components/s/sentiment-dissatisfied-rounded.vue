<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4q7amb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sentiment-dissatisfied-rounded" /></template>
<style>
.t4q7amb0m {
  fill: currentColor;
  d: path("M12 13.5q-1.35 0-2.537.588T7.55 15.8q-.275.4-.075.8t.65.4q.2 0 .363-.088t.287-.262q.575-.775 1.425-1.212T12 15t1.8.438t1.425 1.212q.1.175.263.263t.362.087q.45 0 .65-.413t-.075-.837q-.725-1.1-1.912-1.675T12 13.5m3.5-2.5q.625 0 1.063-.437T17 9.5t-.437-1.062T15.5 8t-1.062.438T14 9.5t.438 1.063T15.5 11m-7 0q.625 0 1.063-.437T10 9.5t-.437-1.062T8.5 8t-1.062.438T7 9.5t.438 1.063T8.5 11m-.4 10.213q-1.825-.788-3.175-2.138T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22t-3.9-.788");
}

</style>
