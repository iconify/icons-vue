<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4lfq6b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:on-hub-device-rounded" /></template>
<style>
.a4lfq6b9o {
  fill: currentColor;
  d: path("M9.423 19.77q-.213 0-.356-.145t-.144-.356t.144-.356t.356-.144h5.154q.213 0 .356.144q.144.144.144.357t-.144.356t-.356.143zm-.556-3.522l-.829-10.56q-.055-.702.41-1.195Q8.914 4 9.611 4h4.779q.697 0 1.162.493t.41 1.195l-.83 10.56q-.03.323-.255.537t-.552.215h-4.65q-.327 0-.552-.215q-.225-.214-.256-.537");
}

</style>
