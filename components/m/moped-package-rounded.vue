<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="innh0rbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:moped-package-rounded" /></template>
<style>
.innh0rbpp {
  fill: currentColor;
  d: path("M4 8.116V4h5.692v4.116zm1.423 9.155q-.73-.73-.73-1.771H3.5q-.343 0-.575-.232t-.233-.576V13q0-1.458 1.021-2.479T6.194 9.5h1.884q.666 0 1.14.475t.475 1.14V14.5h4.231l3.77-4.658V7.308q0-.27-.174-.442q-.173-.174-.442-.174h-1.885q-.212 0-.356-.144q-.144-.143-.144-.356t.144-.356t.356-.144h1.885q.666 0 1.14.475t.475 1.14v2.277q0 .3-.092.546t-.256.462l-3.398 4.293q-.218.287-.556.451t-.711.164H9.692q0 1.038-.728 1.77t-1.77.73t-1.771-.73m2.828-.711q.441-.442.441-1.059h-3q0 .617.442 1.059q.441.441 1.058.441t1.059-.441m8.788.712q-.731-.728-.731-1.769t.728-1.771t1.77-.731t1.771.729t.73 1.769t-.728 1.771T18.81 18t-1.771-.728m2.827-.713q.442-.442.442-1.059t-.442-1.059T18.808 14t-1.059.441q-.441.442-.441 1.059t.441 1.059q.442.441 1.059.441t1.058-.441");
}

</style>
