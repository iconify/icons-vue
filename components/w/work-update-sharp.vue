<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2d4rpb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:work-update-sharp" /></template>
<style>
.b2d4rpb9y {
  fill: currentColor;
  d: path("m18 21l3-3l-.7-.7l-1.8 1.8V15h-1v4.1l-1.8-1.8l-.7.7zM10 6h4V4h-4zm4.463 15.538Q13 20.075 13 18t1.463-3.537T18 13t3.538 1.463T23 18t-1.463 3.538T18 23t-3.537-1.463M2 21V6h6V2h8v4h6v6.275q-.875-.625-1.9-.95T18 11q-2.9 0-4.95 2.05T11 18q0 .775.163 1.538T11.675 21z");
}

</style>
