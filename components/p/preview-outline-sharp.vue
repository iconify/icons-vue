<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha4uhubkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:preview-outline-sharp" /></template>
<style>
.ha4uhubkm {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V7H5zm3.338-3.113Q6.725 14.776 6 13q.725-1.775 2.338-2.887T12 9t3.663 1.113T18 13q-.725 1.775-2.337 2.888T12 17t-3.662-1.112m6.212-1.05q1.15-.663 1.8-1.838q-.65-1.175-1.8-1.838T12 10.5t-2.55.663T7.65 13q.65 1.175 1.8 1.838T12 15.5t2.55-.663m-1.487-.774q.437-.438.437-1.063t-.437-1.062T12 11.5t-1.062.438T10.5 13t.438 1.063T12 14.5t1.063-.437");
}

</style>
