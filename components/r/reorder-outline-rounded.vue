<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtakofyww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:reorder-outline-rounded" /></template>
<style>
.gtakofyww {
  fill: currentColor;
  d: path("M4.5 18q-.213 0-.356-.144T4 17.499t.144-.356T4.5 17h15q.213 0 .356.144t.144.357t-.144.356T19.5 18zm0-3.673q-.213 0-.356-.144T4 13.826t.144-.356t.356-.143h15q.213 0 .356.144q.144.144.144.357t-.144.356t-.356.143zm0-3.654q-.213 0-.356-.144Q4 10.385 4 10.172t.144-.356t.356-.143h15q.213 0 .356.144t.144.357t-.144.356t-.356.143zM4.5 7q-.213 0-.356-.144T4 6.499t.144-.356T4.5 6h15q.213 0 .356.144t.144.357t-.144.356T19.5 7z");
}

</style>
