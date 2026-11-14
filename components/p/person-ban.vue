<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3iv7xb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:person-ban" /></template>
<style>
.u3iv7xb7c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 8.25q0-1.864 1.318-3.182T9 3.75t3.182 1.318T13.5 8.25t-1.318 3.182T9 12.75t-3.182-1.318T4.5 8.25m10.25 2.5Q14.75 7 18.5 7t3.75 3.75t-3.75 3.75t-3.75-3.75m1.657-1.032q-.157.437-.157 1.032q0 2.25 2.25 2.25q.595 0 1.032-.157zm4.186 2.064q.157-.437.157-1.032q0-2.25-2.25-2.25q-.595 0-1.032.157zm-16.63 4.203Q1.75 17.573 1.75 20q0 1.75 1.75 1.75h11q1.75 0 1.75-1.75q0-2.427-2.213-4.015Q11.97 14.5 9 14.5t-5.037 1.485");
}

</style>
