<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt0fwbgkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:touchpad-mouse-outline-sharp" /></template>
<style>
.pt0fwbgkm {
  fill: currentColor;
  d: path("M18.975 18.975Q20 17.95 20 16.5v-2h-7v2q0 1.45 1.025 2.475T16.5 20t2.475-1.025m-5.97-5.475H16v-3.446q-1.315.179-2.137 1.146t-.857 2.3m3.994 0h2.994q-.034-1.333-.856-2.3T17 10.054zm-3.688 6.191Q12 18.381 12 16.5v-3q0-1.882 1.308-3.191T16.497 9t3.192 1.309T21 13.5v3q0 1.882-1.308 3.191T16.503 21t-3.192-1.309M4 18V6zm-1 1V5h18v1.616h-1V6H4v12h5.621v1z");
}

</style>
