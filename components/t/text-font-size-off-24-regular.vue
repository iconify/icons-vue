<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls866fbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-font-size-off-24-regular" /></template>
<style>
.ls866fbgr {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06L13.94 15h-1.388l-1.58 4.452a.75.75 0 0 1-.355.452l-.092.044a.75.75 0 0 1-.928-.33l-.044-.093L8.557 17H4.443l-.995 2.52a.75.75 0 0 1-.876.454l-.097-.032a.75.75 0 0 1-.454-.876l.032-.096l3.754-9.495c.235-.596 1.042-.63 1.344-.105l.051.105l3.01 7.635l1.528-4.31l-9.52-9.52a.75.75 0 0 1 0-1.06m12.824 1.279c.222-.626 1.068-.663 1.364-.11l.049.11l5.376 15.152l-2.467-2.466l-.42-1.185h-.764l-1.5-1.5h1.732L15.75 5.992l-1.724 4.853l-1.174-1.174zM5.036 15.5h2.928l-1.461-3.708z");
}

</style>
