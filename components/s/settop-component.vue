<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv5bz0aqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settop-component" /></template>
<style>
.vv5bz0aqx {
  fill: currentColor;
  d: path("M3 16V8h18v8zm2.5-3.5h4.923v-1H5.5zm9.078.075q.23-.234.23-.578q0-.345-.233-.575q-.234-.23-.578-.23q-.345 0-.575.234q-.23.233-.23.577q0 .345.234.575q.233.23.577.23q.345 0 .575-.233m3 0q.23-.234.23-.578q0-.345-.233-.575q-.234-.23-.578-.23q-.345 0-.575.234q-.23.233-.23.577q0 .345.233.575q.234.23.578.23q.345 0 .575-.233");
}

</style>
