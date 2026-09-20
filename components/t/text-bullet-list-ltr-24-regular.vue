<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqs-1wbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-ltr-24-regular" /></template>
<style>
.bqs-1wbqu {
  fill: currentColor;
  d: path("M3.25 17.5a1.25 1.25 0 1 1 0 2.499a1.25 1.25 0 0 1 0-2.499m3.5.5h14.5a.75.75 0 0 1 .102 1.493l-.102.007H6.75a.75.75 0 0 1-.102-1.493zh14.5zm-3.5-7a1.25 1.25 0 1 1 0 2.499a1.25 1.25 0 0 1 0-2.499m3.5.5h14.5a.75.75 0 0 1 .102 1.493L21.25 13H6.75a.75.75 0 0 1-.102-1.493zh14.5zm-3.5-7a1.25 1.25 0 1 1 0 2.499a1.25 1.25 0 0 1 0-2.499m3.5.5h14.5a.75.75 0 0 1 .102 1.493l-.102.007H6.75a.75.75 0 0 1-.102-1.493zh14.5z");
}

</style>
