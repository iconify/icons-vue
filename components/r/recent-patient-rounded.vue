<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgvx3977m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:recent-patient-rounded" /></template>
<style>
.rgvx3977m {
  fill: currentColor;
  d: path("M6.039 18.616q-.441 0-.74-.3Q5 18.017 5 17.577v-.608q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34q.506 0 .99.042q.483.041.989.143q.304.05.509.29q.204.239.204.562v3.156q0 .348-.23.578t-.577.23zm3.838-8.108Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877m8.623 7.8h-.615q-.349 0-.578-.23q-.23-.23-.23-.578v-3.192q0-.349.23-.578t.577-.23h2.314q.348 0 .525.292t.015.59l-1.373 2.734h.777q.348 0 .522.298t.013.595l-1.798 3.377q-.081.137-.23.106T18.5 21.3z");
}

</style>
