<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v55c813ts.css';
import '../../css/i/i9wr98bya.css';
import '../../css/p/pi715z2hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v55c813ts wm-k"/><path class="i9wr98bya wm-k"/><path class="pi715z2hw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:split-sketch" /></template>
