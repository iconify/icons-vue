<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye6pgo7cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:panorama-vertical-sharp" /></template>
<style>
.ye6pgo7cm {
  fill: currentColor;
  d: path("M5.014 20.989q.644-1.991 1.075-4.145t.43-4.855t-.43-4.856t-1.075-4.144H18.98q-.645 1.99-1.053 4.144q-.409 2.154-.409 4.856t.409 4.855t1.053 4.145z");
}

</style>
