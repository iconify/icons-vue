<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os0zh7bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-heat-link-gen-3-sharp" /></template>
<style>
.os0zh7bro {
  fill: currentColor;
  d: path("M7.885 20q-1.612 0-2.749-1.136T4 16.116V7.885q0-1.613 1.136-2.749T7.885 4h8.23q1.613 0 2.749 1.136T20 7.885v8.23q0 1.613-1.136 2.749T16.116 20zm6.908-4.785q1.15-1.15 1.15-2.793t-1.15-2.792t-2.794-1.15t-2.792 1.152t-1.15 2.793t1.15 2.792q1.151 1.15 2.794 1.15t2.792-1.15m-2.793.15q-1.223 0-2.083-.86t-.86-2.083t.86-2.082T12 9.48t2.083.86q.86.859.86 2.082t-.86 2.083t-2.083.86m.001-7.847q.328 0 .548-.221t.22-.55t-.221-.547t-.55-.22t-.547.221t-.22.55t.221.547t.55.22");
}

</style>
