<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcntw4_wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:reset-exposure-outline-rounded" /></template>
<style>
.hcntw4_wh {
  fill: currentColor;
  d: path("M21 13.212v6.577q0 .509-.351.86t-.86.351H13.21q-.509 0-.86-.351t-.351-.86V13.21q0-.509.351-.86t.86-.351h6.578q.509 0 .86.351t.351.86M13 20h7v-7zM12 5Q9.075 5 7.038 7.038T5 12q0 2.108 1.11 3.79Q7.222 17.474 9 18.309V15.5q0-.213.143-.357T9.5 15t.357.143t.143.357v3.692q0 .349-.23.578t-.578.23H5.5q-.213 0-.357-.143T5 19.5t.143-.357T5.5 19h2.812q-1.916-1-3.114-2.851T4 12q0-1.664.626-3.118T6.34 6.34t2.542-1.714T12 4q2.562 0 4.562 1.418t2.884 3.688q.073.188 0 .38q-.073.193-.261.266q-.189.073-.384-.01t-.268-.27q-.756-1.97-2.513-3.221T12 5");
}

</style>
