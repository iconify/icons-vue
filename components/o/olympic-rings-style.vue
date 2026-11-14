<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjdwplb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:olympic-rings-style" /></template>
<style>
.xjdwplb0i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.5 10.25q0-4 4-4q2.268 0 3.25 1.286Q9.732 6.25 12 6.25q1.657 0 2.828 1.172q.152.151.284.311q.953-1.483 3.388-1.483q4 0 4 4q0 3.613-3.264 3.963q-.224 3.537-3.986 3.537q-2.435 0-3.388-1.483q-.132.16-.284.311q-1.171 1.172-2.828 1.172q-3.762 0-3.986-3.537Q1.5 13.863 1.5 10.25");
}

</style>
