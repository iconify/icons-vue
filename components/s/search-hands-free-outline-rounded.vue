<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcgl0wdry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:search-hands-free-outline-rounded" /></template>
<style>
.vcgl0wdry {
  fill: currentColor;
  d: path("M8.494 20.29q-1.642-.711-2.858-1.926q-1.215-1.216-1.926-2.858T3 12t.71-3.506q.711-1.642 1.927-2.857Q6.852 4.42 8.494 3.71T12 3t3.506.71q1.642.711 2.857 1.927q1.216 1.215 1.926 2.857Q21 10.137 21 12t-.71 3.506q-.711 1.642-1.926 2.857q-1.216 1.216-2.858 1.926Q13.864 21 12 21t-3.506-.71m3.006-.351v-3.962q-1.327-.28-2.261-1.215T8.023 12.5H4.062q.184 3.014 2.304 5.106t5.134 2.332m1 0q3.014-.222 5.134-2.323t2.304-5.115h-3.961q-.28 1.327-1.215 2.261T12.5 15.977zM4.062 11.5H8l1.944-2.002q.217-.237.532-.367T11.114 9h1.772q.324 0 .638.13t.532.368L16 11.5h3.939q-.202-3.179-2.491-5.34Q15.16 4 12 4T6.552 6.16t-2.49 5.34");
}

</style>
