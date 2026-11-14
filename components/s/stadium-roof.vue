<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj6jlm-ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stadium-roof" /></template>
<style>
.aj6jlm-ei {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.767 7.092Q1.75 9.949 1.75 14v5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-5q0-4.051-3.017-6.908Q16.234 4.25 12 4.25T4.767 7.092m3.936-.762q-.29.439-.556.971q-1.261 2.522-1.384 5.949H3.282q.253-2.926 2.516-5.069Q7.111 6.937 8.703 6.33m-.439 6.92q.119-3.067 1.225-5.279Q10.6 5.75 12 5.75t2.511 2.221q1.106 2.212 1.225 5.279zm8.973 0q-.123-3.427-1.384-5.949q-.266-.532-.556-.971q1.592.607 2.905 1.851q2.263 2.143 2.516 5.069zm-.737 1.5h4.25v3.5H3.25v-3.5z");
}

</style>
