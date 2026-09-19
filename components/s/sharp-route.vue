<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv43qabai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-route" /></template>
<style>
.wv43qabai {
  fill: currentColor;
  d: path("M19 15.18V3h-8v16H7V8.82C8.16 8.4 9 7.3 9 6c0-1.66-1.34-3-3-3S3 4.34 3 6c0 1.3.84 2.4 2 2.82V21h8V5h4v10.18A2.996 2.996 0 0 0 18 21c1.66 0 3-1.34 3-3c0-1.3-.84-2.4-2-2.82");
}

</style>
