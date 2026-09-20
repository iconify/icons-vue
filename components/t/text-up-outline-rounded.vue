<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekann_bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-up-outline-rounded" /></template>
<style>
.ekann_bgt {
  fill: currentColor;
  d: path("M11.789 18.385q-.214 0-.357-.144t-.143-.356t.143-.357t.357-.144h7.923q.213 0 .356.144q.144.143.144.357q0 .213-.144.356t-.356.144zm3.604-3.951q-.143-.143-.143-.357V7.531l-1.746 1.746q-.14.14-.344.15t-.364-.15t-.16-.354t.16-.354l2.388-2.388q.243-.242.566-.242t.566.242l2.388 2.388q.14.14.15.345q.01.203-.15.363t-.354.16t-.354-.16L16.25 7.531v6.546q0 .214-.143.357t-.357.143t-.357-.143m-10.953.143q-.246 0-.372-.19t-.04-.412l3.197-8.211q.037-.091.112-.139t.165-.048h.242q.09 0 .166.048t.111.139l3.235 8.209q.086.235-.046.42q-.133.184-.373.184q-.148 0-.262-.07t-.17-.218l-.913-2.32H5.765l-.913 2.325q-.056.129-.16.206q-.103.077-.251.077m1.62-3.408h3.124L7.654 7.15h-.1z");
}

</style>
