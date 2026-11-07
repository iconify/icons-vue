<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/km39q598b.css';
import '../../css/l/llmrhkpex.css';
import '../../css/r/r7eg7804v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="km39q598b"/><path class="llmrhkpex"/><path class="r7eg7804v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-4-linear" /></template>
