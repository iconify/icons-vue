<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e_71410md.css';
import '../../css/q/qy44fxbnk.css';
import '../../css/u/ux6wzzm4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e_71410md"/><path class="qy44fxbnk"/><path class="ux6wzzm4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:phone-calling-linear" /></template>
