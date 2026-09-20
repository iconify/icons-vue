<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xky20_0my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:orientation-portrait-24-filled" /></template>
<style>
.xky20_0my {
  fill: currentColor;
  d: path("M4.75 19a.75.75 0 0 1 .75.75v.5c0 .138.112.25.25.25h.5a.75.75 0 0 1 0 1.5h-.5A1.75 1.75 0 0 1 4 20.25v-.5a.75.75 0 0 1 .75-.75m5.5 1.5a.75.75 0 0 1 0 1.5h-1.5a.75.75 0 0 1 0-1.5zM18.1 8A1.9 1.9 0 0 1 20 9.9v10.2a1.9 1.9 0 0 1-1.9 1.9h-5.2a1.9 1.9 0 0 1-1.9-1.9V9.9A1.9 1.9 0 0 1 12.9 8zM4.75 15a.75.75 0 0 1 .75.75v1.5a.75.75 0 0 1-1.5 0v-1.5a.75.75 0 0 1 .75-.75m1.5-4a.75.75 0 0 1 0 1.5h-.5a.25.25 0 0 0-.25.25v.5a.75.75 0 0 1-1.5 0v-.5c0-.966.784-1.75 1.75-1.75zm4 0a.75.75 0 0 1 0 1.5h-1.5a.75.75 0 0 1 0-1.5zm1.25-9a5.5 5.5 0 0 1 5.323 4.112c.122.47-.263.888-.748.888c-.346 0-.632-.26-.726-.594a4.002 4.002 0 0 0-7.784.372l.697-.597a.75.75 0 0 1 .976 1.138l-1.75 1.5a.75.75 0 0 1-.976 0l-1.75-1.5a.75.75 0 0 1 .976-1.138l.356.304A5.5 5.5 0 0 1 11.5 2");
}

</style>
