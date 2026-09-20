<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l699bw_rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:policy-alert-sharp" /></template>
<style>
.l699bw_rm {
  fill: currentColor;
  d: path("M12 20.962q-3.014-.895-5.007-3.651T5 11.1V5.692l7-2.615l7 2.615v4.539h-1.711v6.273l-2.8-2.8q.236-.379.373-.81Q15 12.463 15 12q0-1.237-.877-2.119Q13.246 9 12 9t-2.123.881T9 12t.881 2.119T12 15q.487 0 .941-.147q.455-.147.828-.441l3.085 3.084q-.92 1.25-2.143 2.136T12 20.962m1.413-7.55Q14 12.826 14 12t-.587-1.412T12 10t-1.412.588T10 12t.588 1.413T12 14t1.413-.587m6.5 7.443q-.144-.144-.144-.357t.144-.356t.357-.143t.356.144t.143.357t-.144.356t-.356.143t-.356-.144m-.144-3.24v-5h1v5z");
}

</style>
