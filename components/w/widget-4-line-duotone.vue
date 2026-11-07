<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pr05z54dz.css';
import '../../css/l/llmrhkpex.css';
import '../../css/r/r7eg7804v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pr05z54dz"/><path class="llmrhkpex"/><path class="r7eg7804v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-4-line-duotone" /></template>
