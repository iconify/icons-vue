<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp6-asb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:see-more-like-this" /></template>
<style>
.bp6-asb7v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 1.75h1q1.76 0 3.005 1.245q.971.971 1.185 2.255H19q2.75 0 2.75 2.75v8q0 2.75-2.75 2.75h-2.31q-.214 1.284-1.185 2.255Q14.26 22.25 12.5 22.25h-1q-1.76 0-3.005-1.245q-.971-.971-1.185-2.255H5q-2.75 0-2.75-2.75V8q0-2.75 2.75-2.75h2.31q.214-1.284 1.185-2.255Q9.74 1.75 11.5 1.75m-4.25 5H5Q3.75 6.75 3.75 8v8q0 1.25 1.25 1.25h2.25zm11.75 0h-2.25v10.5H19q1.25 0 1.25-1.25V8q0-1.25-1.25-1.25");
}

</style>
