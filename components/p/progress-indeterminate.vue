<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6w_4hbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:progress-indeterminate" /></template>
<style>
.e6w_4hbai {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 7.25h-11q-1.968 0-3.359 1.391T1.75 12t1.391 3.359t3.358 1.391H17.5q1.968 0 3.359-1.391T22.25 12t-1.391-3.359T17.5 7.25m-1.082 1.5l-2.438 6.5h-2.398l2.438-6.5zm-.836 6.5l2.43-6.478Q20.75 9.017 20.75 12q0 3.25-3.25 3.25zm-7.164-6.5l-2.43 6.478Q3.25 14.983 3.25 12q0-1.346.952-2.298T6.5 8.75zm-.836 6.5l2.438-6.5h2.398l-2.438 6.5z");
}

</style>
