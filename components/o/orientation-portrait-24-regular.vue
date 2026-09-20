<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kms3a7obx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:orientation-portrait-24-regular" /></template>
<style>
.kms3a7obx {
  fill: currentColor;
  d: path("M4.75 19a.75.75 0 0 1 .75.75v.5c0 .138.112.25.25.25h.5a.75.75 0 0 1 0 1.5h-.5A1.75 1.75 0 0 1 4 20.25v-.5a.75.75 0 0 1 .75-.75m5.5 1.5a.75.75 0 0 1 0 1.5h-1.5a.75.75 0 0 1 0-1.5zM18.1 8A1.9 1.9 0 0 1 20 9.9v10.2a1.9 1.9 0 0 1-1.9 1.9h-5.2a1.9 1.9 0 0 1-1.9-1.9v-8.35a.75.75 0 0 1-.75.75h-1.5a.75.75 0 0 1 0-1.5h1.5a.75.75 0 0 1 .75.75V9.9A1.9 1.9 0 0 1 12.9 8zm-5.2 1.5a.4.4 0 0 0-.4.4v10.2c0 .22.18.4.4.4h5.2a.4.4 0 0 0 .4-.4V9.9a.4.4 0 0 0-.4-.4zM4.75 15a.75.75 0 0 1 .75.75v1.5a.75.75 0 0 1-1.5 0v-1.5a.75.75 0 0 1 .75-.75m1.5-4a.75.75 0 0 1 0 1.5h-.5a.25.25 0 0 0-.25.25v.5a.75.75 0 0 1-1.5 0v-.5c0-.966.784-1.75 1.75-1.75zm5.25-9a5.5 5.5 0 0 1 5.323 4.112c.122.47-.263.888-.748.888c-.346 0-.632-.26-.726-.594a4.002 4.002 0 0 0-7.784.372l.697-.597a.75.75 0 0 1 .976 1.138l-1.75 1.5a.75.75 0 0 1-.976 0l-1.75-1.5a.75.75 0 0 1 .976-1.138l.356.304A5.5 5.5 0 0 1 11.5 2");
}

</style>
