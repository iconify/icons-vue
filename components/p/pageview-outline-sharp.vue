<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv6-i8b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pageview-outline-sharp" /></template>
<style>
.kv6-i8b7a {
  fill: currentColor;
  d: path("M15.712 19H3V5h18v14h-2.439l-4.815-4.815q-.467.407-1.031.611Q12.15 15 11.5 15q-1.452 0-2.476-1.024T8 11.5t1.024-2.476T11.5 8t2.476 1.024T15 11.5q0 .54-.117.987t-.467.951L18.977 18H20V6H4v12h10.712zm-2.437-5.725Q14 12.55 14 11.5t-.725-1.775T11.5 9t-1.775.725T9 11.5t.725 1.775T11.5 14t1.775-.725M4 18V6z");
}

</style>
