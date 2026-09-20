<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh6nuheqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-spark" /></template>
<style>
.oh6nuheqp {
  fill: currentColor;
  d: path("m12 12.116l8-5.212L19.692 6L12 11L4.308 6L4 6.904zM11.964 19H4.615q-.69 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v5.89q-.602-.27-1.249-.426q-.647-.157-1.347-.157q-2.681 0-4.581 1.9t-1.9 4.58q0 .15.009.305q.008.154.031.292m6.44 3.5q-.15 0-.2-.15q-.36-1.39-1.358-2.387q-.997-.997-2.387-1.36q-.15-.05-.15-.2q0-.174.15-.2q1.39-.36 2.387-1.358q.997-.997 1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.359q.15.025.15.2q0 .15-.15.2q-1.39.362-2.388 1.359t-1.358 2.387q-.025.15-.2.15");
}

</style>
