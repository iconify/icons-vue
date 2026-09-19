<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5vgbcb_s.css';
import '../../css/v/vmyfv_bvg.css';
import '../../css/w/wgqpd53tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="y5vgbcb_s"/><path class="vmyfv_bvg"/><path class="wgqpd53tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:yt-4x3" /></template>
