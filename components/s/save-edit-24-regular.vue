<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nssa5ub6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:save-edit-24-regular" /></template>
<style>
.nssa5ub6q {
  fill: currentColor;
  d: path("M19.1 12.67a2.286 2.286 0 0 1 3.232 3.232l-5.902 5.903a2.7 2.7 0 0 1-1.247.706l-1.831.458a1.088 1.088 0 0 1-1.319-1.319l.458-1.83c.118-.473.362-.904.706-1.248zM15.715 3a3.25 3.25 0 0 1 2.298.952l2.035 2.035c.61.61.952 1.436.952 2.298v2.727a3.3 3.3 0 0 0-1.5.22V8.285c0-.464-.185-.91-.513-1.237l-2.035-2.035a1.75 1.75 0 0 0-.952-.49V7.25a2.25 2.25 0 0 1-2.25 2.25h-4.5A2.25 2.25 0 0 1 7 7.25V4.5H5.75c-.69 0-1.25.56-1.25 1.25v12.5c0 .69.56 1.25 1.25 1.25H6v-5.25A2.25 2.25 0 0 1 8.25 12h7.5c.712 0 1.346.33 1.758.847l-1.082 1.083a.75.75 0 0 0-.676-.43h-7.5a.75.75 0 0 0-.75.75v5.25h4.044l-.023.077L11.167 21H5.75A2.75 2.75 0 0 1 3 18.25V5.75A2.75 2.75 0 0 1 5.75 3zM8.5 7.25c0 .414.336.75.75.75h4.5a.75.75 0 0 0 .75-.75V4.5h-6z");
}

</style>
