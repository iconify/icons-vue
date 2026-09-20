<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slz1bwbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:toll-outline-rounded" /></template>
<style>
.slz1bwbgg {
  fill: currentColor;
  d: path("M10.037 16.964Q8 14.927 8 12t2.036-4.963T15 5t4.964 2.036T22 12t-2.036 4.964T15 19t-4.963-2.036M6.298 18.48q-1.984-.745-3.141-2.522T2 12t1.157-3.96t3.141-2.52q.275-.116.489.037q.213.152.213.476q0 .134-.085.247t-.22.18q-1.691.667-2.693 2.177T3 12t1.002 3.363t2.692 2.178q.135.067.22.186q.086.12.086.26q0 .298-.213.454q-.214.155-.489.04M19.25 16.25Q21 14.5 21 12t-1.75-4.25T15 6t-4.25 1.75T9 12t1.75 4.25T15 18t4.25-1.75");
}

</style>
