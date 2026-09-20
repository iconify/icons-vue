<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byxxcsbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mail-spark-outline-sharp" /></template>
<style>
.byxxcsbva {
  fill: currentColor;
  d: path("m12 11l8-5H4zm-.025 9H2V4h20v8h-2V8l-8 5l-8-5v10h7.975zm6.525 3q-.15 0-.2-.15q-.4-1.525-1.513-2.637T14.15 18.7q-.15-.05-.15-.2q0-.175.15-.2q1.525-.4 2.638-1.513T18.3 14.15q.05-.15.2-.15t.2.15q.4 1.525 1.513 2.638T22.85 18.3q.15.025.15.2q0 .15-.15.2q-1.525.4-2.637 1.513T18.7 22.85q-.025.15-.2.15");
}

</style>
