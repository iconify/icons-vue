<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hq_753b0b.css';
import '../../css/m/mucxul6vk.css';
import '../../css/i/i5y74rzry.css';
import '../../css/u/uiij3v7pb.css';
import '../../css/a/a3a1e9pjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hq_753b0b"/><path class="mucxul6vk"/><path class="i5y74rzry"/><path class="uiij3v7pb"/><path class="a3a1e9pjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:voicemail-duotone" /></template>
