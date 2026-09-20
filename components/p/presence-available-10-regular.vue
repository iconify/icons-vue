<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="t6q6-piqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-available-10-regular" /></template>
<style>
.t6q6-piqm {
  fill: currentColor;
  d: path("M4.998 0a4.998 4.998 0 1 0 0 9.995a4.998 4.998 0 0 0 0-9.995M1 4.998a3.998 3.998 0 1 1 7.995 0a3.998 3.998 0 0 1-7.995 0m6.104-1.602a.5.5 0 0 1 0 .708l-2.25 2.25a.5.5 0 0 1-.708 0l-1-1a.5.5 0 1 1 .708-.708l.646.647l1.896-1.897a.5.5 0 0 1 .708 0");
}

</style>
