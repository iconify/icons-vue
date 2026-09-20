<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_pe0ob2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:preview-rounded" /></template>
<style>
.r_pe0ob2d {
  fill: currentColor;
  d: path("M5.616 20q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h12.769q.67 0 1.143.472q.472.472.472 1.144v12.769q0 .67-.472 1.143q-.472.472-1.143.472zm0-1h12.769q.269 0 .442-.173t.173-.442V7H5v11.385q0 .269.173.442t.443.173m3.452-3.834Q7.764 14.333 7.096 13q.668-1.333 1.972-2.166Q10.373 10 12 10t2.932.834T16.904 13q-.667 1.333-1.972 2.166Q13.627 16 12 16t-2.932-.834m2.139-1.373q-.323-.322-.323-.793t.323-.793q.322-.323.793-.323t.793.323q.323.322.323.793t-.323.793q-.322.323-.793.323t-.793-.323m2.126.54q.552-.552.552-1.333t-.552-1.333T12 11.115t-1.333.552T10.115 13t.552 1.333t1.333.552t1.333-.552");
}

</style>
