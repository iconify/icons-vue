<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caqmmpbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:watch-button-press-outline-rounded" /></template>
<style>
.caqmmpbdb {
  fill: currentColor;
  d: path("M13.538 15.538Q15 14.075 15 12t-1.463-3.537T10 7T6.463 8.463T5 12t1.463 3.538T10 17t3.538-1.463M8.73 21q-.342 0-.61-.205t-.373-.547l-.633-2.214q-.13-.423-.395-.81q-.264-.388-.706-.765q-.966-.809-1.49-1.965T4 12q0-1.313.524-2.47t1.49-1.99q.442-.402.706-.786q.265-.385.396-.788l.632-2.214q.104-.342.372-.547T8.73 3h2.54q.342 0 .61.205t.372.547l.633 2.214q.13.423.395.81q.264.388.707.765q.965.809 1.489 1.965T16 12q0 1.314-.524 2.47t-1.49 1.99q-.442.402-.706.786q-.264.385-.395.789l-.633 2.213q-.104.343-.372.547t-.61.205zm10.412-9.162Q19 11.694 19 11.48V4.5q0-.213.143-.357T19.5 4t.357.143T20 4.5v6.98q0 .214-.143.358t-.357.143t-.357-.143M8.731 4h2.538zm0 16h2.538zM8.06 6.327q.52-.163.992-.248T10 5.994t.947.085q.472.085.991.248L11.27 4H8.731zM8.732 20h2.538l.67-2.327q-.52.164-.992.236T10 17.98t-.947-.072t-.991-.236z");
}

</style>
