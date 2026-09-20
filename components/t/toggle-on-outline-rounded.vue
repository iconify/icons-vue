<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw5tcgb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:toggle-on-outline-rounded" /></template>
<style>
.jw5tcgb5p {
  fill: currentColor;
  d: path("M7 18q-2.5 0-4.25-1.75T1 12t1.75-4.25T7 6h10q2.5 0 4.25 1.75T23 12t-1.75 4.25T17 18zm0-2h10q1.65 0 2.825-1.175T21 12t-1.175-2.825T17 8H7Q5.35 8 4.175 9.175T3 12t1.175 2.825T7 16m12.125-1.875Q20 13.25 20 12t-.875-2.125T17 9t-2.125.875T14 12t.875 2.125T17 15t2.125-.875M12 12");
}

</style>
