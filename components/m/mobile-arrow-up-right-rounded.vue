<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7tvdxb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-arrow-up-right-rounded" /></template>
<style>
.l7tvdxb0g {
  fill: currentColor;
  d: path("M7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31v9.869q0 .67-.472 1.143q-.472.472-1.143.472zM13.5 11.189v2.715q0 .213.143.357t.357.143t.357-.143t.143-.357v-3.615q0-.348-.23-.578t-.578-.23h-3.615q-.213 0-.357.143t-.143.357t.143.357t.357.143h2.735l-3.477 3.452q-.166.146-.166.347t.165.366q.166.165.357.165q.192 0 .357-.165z");
}

</style>
