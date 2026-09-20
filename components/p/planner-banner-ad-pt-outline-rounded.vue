<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m23ubzb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:planner-banner-ad-pt-outline-rounded" /></template>
<style>
.m23ubzb0s {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4v16q0 .825-.587 1.413T18 22zm0-2h12V4H6zm5.25-3.5L10.1 15q-.15-.2-.4-.2t-.4.2l-1.675 2.2q-.2.25-.063.525t.463.275h7.95q.325 0 .462-.275t-.062-.525l-2.425-3.175q-.15-.2-.4-.2t-.4.2zM6 20V4z");
}

</style>
