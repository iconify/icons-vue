<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5n9ihbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nutrition-outline-sharp" /></template>
<style>
.s5n9ihbdz {
  fill: currentColor;
  d: path("M7.038 18.963Q5 16.925 5 14q0-2.35 1.388-4.212t3.637-2.513q-.825-.2-1.437-.712T7.6 5.325T7.075 3.75t-.05-1.725q1.025-.125 1.95.125t1.675.8t1.238 1.325t.587 1.75q.325-.775.863-1.537T15 2.6L16.4 4q-1.075 1.075-1.588 1.825t-.712 1.5q2.2.7 3.55 2.538T19 14q0 2.925-2.037 4.963T12 21t-4.962-2.037m8.5-1.426Q17 16.075 17 14t-1.463-3.537T12 9t-3.537 1.463T7 14t1.463 3.538T12 19t3.538-1.463M12 14");
}

</style>
