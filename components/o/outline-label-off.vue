<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2n88cbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-label-off" /></template>
<style>
.u2n88cbfw {
  fill: currentColor;
  d: path("m16 7l3.55 5l-1.63 2.29l1.43 1.43L22 12l-4.37-6.16C17.27 5.33 16.67 5 16 5l-7.37.01l2 1.99zM2 4.03l1.58 1.58C3.22 5.96 3 6.46 3 7v10c0 1.1.9 1.99 2 1.99L16 19c.28 0 .55-.07.79-.18L18.97 21l1.41-1.41L3.41 2.62zM14.97 17H5V7.03z");
}

</style>
