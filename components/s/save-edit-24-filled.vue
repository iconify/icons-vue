<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry23lmngz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:save-edit-24-filled" /></template>
<style>
.ry23lmngz {
  fill: currentColor;
  d: path("M19.1 12.67a2.286 2.286 0 0 1 3.232 3.232l-5.902 5.903a2.7 2.7 0 0 1-1.247.706l-1.831.458a1.088 1.088 0 0 1-1.319-1.319l.458-1.83c.118-.473.362-.904.706-1.248zM6.75 7.5A2.25 2.25 0 0 0 9 9.75h4.5a2.25 2.25 0 0 0 2.25-2.25V3a3.25 3.25 0 0 1 2.263.952l2.035 2.035c.61.61.952 1.436.952 2.298v2.727a3.28 3.28 0 0 0-2.606.95l-1.264 1.263a2.24 2.24 0 0 0-1.38-.475h-7.5A2.25 2.25 0 0 0 6 15v6h-.25A2.75 2.75 0 0 1 3 18.25V5.75A2.75 2.75 0 0 1 5.75 3h1zm9 6.75q.158 0 .295.06l-3.554 3.555a3.7 3.7 0 0 0-.97 1.712L11.167 21H7.5v-6a.75.75 0 0 1 .75-.75zm-1.5-6.75a.75.75 0 0 1-.75.75H9a.75.75 0 0 1-.75-.75V3h6z");
}

</style>
