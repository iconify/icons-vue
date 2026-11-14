<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppdiw9c-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:medal" /></template>
<style>
.ppdiw9c-y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.323 2.25h-.948q-1.067.001-1.641.9q-.573.899-.124 1.867l2.057 4.431q.144.311.337.548q-.762.423-1.423 1.085Q5.75 12.911 5.75 15.5t1.831 4.419T12 21.75t4.419-1.831q1.831-1.83 1.831-4.419t-1.831-4.419q-.661-.662-1.423-1.085q.193-.237.337-.548l2.057-4.431q.449-.968-.124-1.867q-.574-.899-1.641-.9h-.948q-1.391 0-2.013 1.244l-.46.921q-.063.126-.204.126t-.204-.126l-.46-.921Q10.714 2.25 9.323 2.25");
}

</style>
