<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8zercb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-question" /></template>
<style>
.g8zercb7w {
  fill: currentColor;
  d: path("M7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31v9.869q0 .67-.472 1.143q-.472.472-1.143.472zm4.852-5.64q.198-.197.198-.468q0-.27-.198-.468q-.197-.197-.468-.197t-.468.197t-.197.468t.197.468q.197.198.468.198t.468-.198m-.91-2.58h.884q.039-.626.237-.984t.929-1.088q.43-.431.683-.87q.251-.438.251-1.019q0-1.083-.731-1.691q-.732-.609-1.811-.609q-.927 0-1.546.478q-.62.478-.92 1.2l.812.318q.202-.444.571-.783T12 8.392q.848 0 1.253.447q.405.445.405.992q0 .502-.26.849t-.667.736q-.683.615-.928 1.107q-.245.493-.245 1.258");
}

</style>
