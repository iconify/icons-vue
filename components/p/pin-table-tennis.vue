<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odvnp8r9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-table-tennis" /></template>
<style>
.odvnp8r9d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 15.8q3.169-1.114 4.33-4.379q1.26-3.541-.906-6.611T10.5 1.74T4.576 4.81t-.906 6.611Q4.831 14.686 8 15.8v3.7Q8 22 10.5 22t2.5-2.5zm4.25.7q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768T19.75 19q-2.5 0-2.5-2.5");
}

</style>
