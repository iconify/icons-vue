<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa1b-ud0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:portrait-mode" /></template>
<style>
.oa1b-ud0l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.875 1.75h6.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624q-.72.719-1.582 1.094q.083-.161.083-.343v-2q0-1.867-1.554-3.301Q14.127 14.75 12 14.75t-3.696 1.449Q6.75 17.633 6.75 19.5v2q0 .182.083.343q-.862-.375-1.582-1.094q-1.501-1.501-1.501-3.624V6.875q0-2.123 1.501-3.624T8.875 1.75M7.86 22.158q.489.092 1.015.092h6.25q.526 0 1.015-.092q-.089-.049-.161-.119t-.124-.157t-.078-.184t-.027-.198v-2q0-1.21-1.071-2.199Q13.54 16.25 12 16.25t-2.679 1.051Q8.25 18.29 8.25 19.5v2q0 .101-.027.198q-.026.097-.078.184q-.051.087-.124.157q-.072.07-.161.119M12 5.75q-3.75 0-3.75 3.75T12 13.25t3.75-3.75T12 5.75");
}

</style>
