<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib1rfibvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:problem-rounded" /></template>
<style>
.ib1rfibvm {
  fill: currentColor;
  d: path("M7.549 15.932q.22-.221.22-.549t-.221-.547t-.55-.22t-.547.221t-.22.549t.221.548t.55.22t.547-.222m-.192-2.845q.143-.144.143-.356V8.346q0-.212-.144-.356t-.357-.144t-.356.144t-.143.356v4.385q0 .212.144.356t.357.144t.356-.144M11 14.5h6q.213 0 .356-.144t.144-.357t-.144-.356T17 13.5h-6q-.213 0-.356.144t-.144.357t.144.356t.356.143m0-4h6q.213 0 .356-.144t.144-.357t-.144-.356T17 9.5h-6q-.213 0-.356.144t-.144.357t.144.356t.356.143M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19z");
}

</style>
