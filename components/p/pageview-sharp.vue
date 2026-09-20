<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2fvxmb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pageview-sharp" /></template>
<style>
.x2fvxmb3o {
  fill: currentColor;
  d: path("M9.725 13.275Q9 12.55 9 11.5t.725-1.775T11.5 9t1.775.725T14 11.5t-.725 1.775T11.5 14t-1.775-.725M3 19V5h18v14h-1.023l-5.561-5.562q.35-.505.467-.952q.117-.445.117-.986q0-1.458-1.02-2.48Q12.962 8 11.505 8t-2.48 1.02T8 11.496t1.02 2.48T11.5 15q.65 0 1.215-.204q.564-.204 1.031-.611L18.562 19z");
}

</style>
