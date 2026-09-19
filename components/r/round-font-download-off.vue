<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqvzoabta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-font-download-off" /></template>
<style>
.aqvzoabta {
  fill: currentColor;
  d: path("m12.58 9.75l-.87-.87l.23-.66h.1zm-2.23-2.23l.2-.52a1.55 1.55 0 0 1 2.9 0l2.17 5.79L22 19.17V4c0-1.1-.9-2-2-2H4.83zm10.84 15.09a.996.996 0 0 1-1.41 0l-.61-.61H4c-1.1 0-2-.9-2-2V4.83l-.61-.61A.996.996 0 1 1 2.8 2.81l18.38 18.38c.4.39.4 1.03.01 1.42m-9.09-7.68l-3.3-3.3l-1.9 5.07c-.23.63.23 1.3.9 1.3h.01c.41 0 .77-.26.9-.64l.86-2.43z");
}

</style>
