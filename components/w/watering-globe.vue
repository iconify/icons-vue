<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idfh4nc7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:watering-globe" /></template>
<style>
.idfh4nc7g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.581 3.081Q5.75 4.911 5.75 7.5t1.831 4.419q1.559 1.56 3.669 1.791v1.54H8.192q-1.203 0-1.954.941q-.75.94-.483 2.113l.454 2q.442 1.947 2.438 1.946h6.706q1.996.001 2.438-1.946l.454-2q.267-1.173-.483-2.113q-.751-.941-1.954-.941H12.75v-1.54q2.11-.231 3.669-1.791q1.831-1.83 1.831-4.419t-1.831-4.419T12 1.25T7.581 3.081m3.827 1.459q.058-.074.132-.132q.058-.045.124-.078q.066-.034.137-.053q.071-.02.145-.025t.147.004t.143.032q.071.024.135.06q.064.037.12.085t.101.107Q14.5 6.993 14.5 8.5q0 1.036-.732 1.768T12 11q-2.5 0-2.5-2.5q0-1.507 1.908-3.96");
}

</style>
