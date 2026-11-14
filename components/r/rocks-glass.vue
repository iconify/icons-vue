<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa3nrh7ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rocks-glass" /></template>
<style>
.aa3nrh7ny {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.11 6.25H6.89q-1.092 0-1.834.801t-.659 1.891l.612 7.945q.01-.066.031-.129q.022-.063.054-.122t.075-.11t.092-.095q.051-.043.108-.077q.058-.034.12-.057q.063-.023.129-.035q.065-.012.132-.012h12.5q.067 0 .132.012q.066.012.129.035q.062.023.12.057t.108.077t.092.095q.043.052.075.11t.054.122q.021.063.031.129l.612-7.946q.083-1.089-.659-1.89T17.11 6.25m1.855 10.975q-.017.057-.044.11t-.061.102q-.035.048-.077.09q-.041.043-.089.078t-.101.062t-.11.046t-.115.028q-.059.009-.118.009H5.75q-.059 0-.118-.009q-.059-.01-.115-.028t-.11-.046q-.053-.027-.101-.062t-.089-.078t-.077-.09q-.034-.049-.061-.102t-.044-.11l.093 1.216q.178 2.309 2.493 2.309h8.758q2.315 0 2.493-2.308z");
}

</style>
