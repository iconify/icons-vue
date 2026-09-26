<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yc1eq-awn.css';
import '../../css/v/vbwan82rd.css';
import '../../css/c/cofofbttk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yc1eq-awn"/><path class="vbwan82rd"/><path class="cofofbttk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-close-line-duotone" /></template>
