<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzvw9mbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:php-sharp" /></template>
<style>
.mzvw9mbgm {
  fill: currentColor;
  d: path("M3.423 14.692V9.308h4.385v3.461h-3.5v1.923zm6.577 0V9.308h.885v2H13.5v-2h.885v5.384H13.5v-2.5h-2.615v2.5zm6.73 0V9.308h4.385v3.461h-3.5v1.923zM4.309 11.885h2.615V10.23H4.308zm13.308 0h2.615V10.23h-2.616z");
}

</style>
