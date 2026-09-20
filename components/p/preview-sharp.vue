<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lksdvoj4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:preview-sharp" /></template>
<style>
.lksdvoj4m {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V7H5zm3.338-3.113Q6.725 14.776 6 13q.725-1.775 2.338-2.887T12 9t3.663 1.113T18 13q-.725 1.775-2.337 2.888T12 17t-3.662-1.112m2.6-1.826Q10.5 13.626 10.5 13t.438-1.062T12 11.5t1.063.438T13.5 13t-.437 1.063T12 14.5t-1.062-.437m2.837.712Q14.5 14.05 14.5 13t-.725-1.775T12 10.5t-1.775.725T9.5 13t.725 1.775T12 15.5t1.775-.725");
}

</style>
