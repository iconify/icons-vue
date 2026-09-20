<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr37a-b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swap-driving-apps-outline" /></template>
<style>
.nr37a-b5w {
  fill: currentColor;
  d: path("m16.154 7.346l-.72-.707l1.6-1.6H7.566v-1h9.468l-1.6-1.6l.708-.72l2.82 2.82zM5 19h14v-4.846H5zm3.22-1.623q.319-.314.319-.795t-.315-.801t-.796-.32t-.801.315t-.32.797q0 .48.315.8t.796.32q.482 0 .801-.316m9.154 0q.32-.314.32-.795t-.316-.801t-.795-.32t-.801.315t-.32.797q0 .48.315.8t.797.32q.48 0 .8-.316M4 13.155h14.585L17.112 9H5.946l1.6 1.6l-.708.72L4.02 8.5l2.82-2.82l.707.72l-1.6 1.6h11.4q.24 0 .419.138t.25.362L20 14.154V21.5q0 .213-.144.356T19.5 22h-.23q-.213 0-.357-.144t-.144-.356V20H5.231v1.5q0 .213-.144.356T4.731 22H4.5q-.213 0-.356-.144T4 21.5zm1 1V19z");
}

</style>
