<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vnen35bwe.css';
import '../../css/w/w_4zjac6j.css';
import '../../css/d/dqueh1r5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vnen35bwe"/><path class="w_4zjac6j wm-shadow"/><path class="dqueh1r5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:menu-engrave" /></template>
