<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em1trzbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-square-clock-24-regular" /></template>
<style>
.em1trzbdo {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m.25-9A3.25 3.25 0 0 1 21 6.25v5.774a6.5 6.5 0 0 0-1.5-.71V6.25a1.75 1.75 0 0 0-1.75-1.75H6.25A1.75 1.75 0 0 0 4.5 6.25v11.5c0 .966.784 1.75 1.75 1.75h5.065a6.4 6.4 0 0 0 .71 1.5H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zm-.25 11a.5.5 0 0 0-.5.5v3a.5.5 0 0 0 .5.5H20a.5.5 0 0 0 0-1h-2v-2.5a.5.5 0 0 0-.5-.5m-9.75.75a1 1 0 1 1 0 2a1 1 0 0 1 0-2m0-3.75a1 1 0 1 1 0 2a1 1 0 0 1 0-2m7.967.25a6.5 6.5 0 0 0-2.652 1.5H11.25a.75.75 0 0 1 0-1.5zm-7.967-4a1 1 0 1 1 0 2a1 1 0 0 1 0-2m9 .25a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1 0-1.5z");
}

</style>
