<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oh5nrqd7u"/><path class="e2u6vtbfh"/><path class="i0fdev8qh"/><path class="bvbx3gb_w"/><path class="i7m5u8cqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:yoga-mat-broken" /></template>
<style>
.bvbx3gb_w {
  d: path("M8.9668 17.3394L15.1667 11.9394C16.6244 10.6698 16.7768 8.45899 15.5073 7.00139C14.2377 5.54369 12.0269 5.39129 10.5693 6.66079");
}

.e2u6vtbfh {
  d: path("M5.21875 14.7001C5.21875 14.0438 5.65955 13.4694 6.29345 13.2995C6.92735 13.1297 7.59635 13.4067 7.92445 13.9751C8.25265 14.5435 8.15815 15.2613 7.69405 15.7254C7.22995 16.1895 6.51215 16.284 5.94375 15.9558");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i0fdev8qh {
  d: path("M4.36914 12.0606L7.25282 9.54907");
}

.i7m5u8cqc {
  d: path("M6.66797 18.2H15.9438C16.2818 18.2 16.6084 18.0777 16.8633 17.8557L20.4527 14.7295C21.2195 14.0616 20.7471 12.8 19.7302 12.8H14.1785");
}

.oh5nrqd7u {
  d: path("M10.168 14.7C10.168 16.633 8.60097 18.2 6.66797 18.2C4.73497 18.2 3.16797 16.633 3.16797 14.7C3.16797 12.767 4.73497 11.2 6.66797 11.2C8.60097 11.2 10.168 12.767 10.168 14.7Z");
}

</style>
