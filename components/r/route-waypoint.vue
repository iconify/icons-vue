<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg4qe1blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:route-waypoint" /></template>
<style>
.vg4qe1blq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.83 4.75H9q-1.76 0-3.005 1.245T4.75 9t1.245 3.005T9 13.25q.118 0 .231-.036q.159.487.55.877l.628.628q.659.66 1.591.66t1.591-.66l.628-.628q.391-.39.55-.877q.113.036.231.036q2.25 0 2.25 2.25T15 17.75H9.201Q8.85 15.25 6 15.25q-3.25 0-3.25 3.25T6 21.75q2.85 0 3.201-2.5H15q3.75 0 3.75-3.75T15 11.75q-.118 0-.231.036q-.159-.487-.55-.877l-.628-.628q-.659-.66-1.591-.66t-1.591.66l-.628.628q-.391.39-.55.877q-.113-.036-.231-.036q-1.139 0-1.945-.805Q6.25 10.139 6.25 9q0-2.75 2.75-2.75h5.83q.196.874.871 1.549q.952.953 2.299.953t2.299-.953t.951-2.3q.001-1.345-.951-2.298T18 2.248t-2.299.953q-.675.675-.871 1.549");
}

</style>
