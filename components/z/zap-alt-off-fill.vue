<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9ay83b9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-alt-off-fill" /></template>
<style>
.p9ay83b9g {
  fill: currentColor;
  d: path("M15.328 14.086L7.471 6.228l1.351-3.04A2 2 0 0 1 10.65 2H16a1.582 1.582 0 0 1 1.372 2.364L14.723 9H17a1.416 1.416 0 0 1 1 2.414ZM2.707 4.293l17 17a.999.999 0 1 1-1.414 1.414L12.5 16.914L8.414 21a1.292 1.292 0 0 1-2.173-1.193L7.753 13H7a1.65 1.65 0 0 1-1.508-2.32l.238-.535l-4.437-4.438a.999.999 0 1 1 1.414-1.414");
}

</style>
