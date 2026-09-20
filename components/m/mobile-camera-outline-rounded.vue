<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmao3_drk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-camera-outline-rounded" /></template>
<style>
.gmao3_drk {
  fill: currentColor;
  d: path("M7 17.808V21V3zm5.588-11.72q.22-.22.22-.55q0-.329-.22-.549t-.55-.22t-.548.22t-.22.55t.22.549t.549.22t.549-.22M7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144v2.076q0 .214-.143.357t-.357.143t-.357-.143t-.143-.357V3.615q0-.269-.173-.442T16.46 3H7.616q-.27 0-.443.173T7 3.616v16.769q0 .269.173.442t.443.173h8.846q.269 0 .442-.173t.173-.442v-2.077q0-.214.143-.357t.357-.143t.357.143t.143.357v2.077q0 .67-.472 1.143q-.472.472-1.143.472zm6.98-6.577q-.529 0-.908-.38t-.38-.908V10.73q0-.529.38-.909t.908-.38h.846l.623-.623q.131-.13.27-.186q.14-.056.301-.056h1.035q.162 0 .301.056q.14.056.27.186l.623.623h.846q.53 0 .91.38q.379.38.379.909v3.404q0 .529-.38.908t-.909.38zm3.613-1.945q.445-.445.445-1.055t-.445-1.045t-1.055-.436t-1.055.436t-.445 1.045q0 .61.445 1.055t1.055.445t1.055-.445");
}

</style>
