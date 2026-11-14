<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbgc0jbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shopping-bag" /></template>
<style>
.lbgc0jbfz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 7.25h5.5V6.5q0-1.139-.805-1.945Q13.139 3.75 12 3.75q-2.75 0-2.75 2.75zm7 0H19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .026-.002.051L19 19.026q-.013 2.724-2.75 2.724h-8.5q-2.737 0-2.75-2.724L4.252 8.051q-.005-.074.004-.147t.033-.143t.06-.134t.086-.12q.048-.056.107-.101t.125-.078t.137-.052t.145-.024Q4.974 7.25 5 7.25h2.75V6.5q0-1.76 1.245-3.005T12 2.25t3.005 1.245T16.25 6.5z");
}

</style>
