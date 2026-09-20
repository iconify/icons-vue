<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy759ublx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-alert-rounded" /></template>
<style>
.zy759ublx {
  fill: currentColor;
  d: path("M7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31v9.869q0 .67-.472 1.143q-.472.472-1.143.472zm4.818-5.72q.182-.182.182-.434t-.182-.434t-.434-.181t-.434.182t-.182.433t.182.434t.434.181t.434-.181m-.077-2.923q.143-.143.143-.357V7.923q0-.213-.143-.357T12 7.423t-.357.143t-.143.357V13q0 .214.143.357T12 13.5t.357-.143");
}

</style>
