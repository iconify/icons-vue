<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdthv3bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:maximize-rounded" /></template>
<style>
.tdthv3bcv {
  fill: currentColor;
  d: path("M5.5 5q-.213 0-.356-.144T5 4.499t.144-.356T5.5 4h13q.213 0 .356.144t.144.357t-.144.356T18.5 5z");
}

</style>
