<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/q4u-2p_ie.css';
import '../../css/q/q3c080bmg.css';
import '../../css/w/wm0qbnrvr.css';
import '../../css/m/mrkguu9rt.css';
import '../../css/h/hlc0oltyy.css';
import '../../css/y/ypo96kbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q4u-2p_ie"/><path clip-rule="evenodd" class="q3c080bmg"/><path class="wm0qbnrvr"/><path clip-rule="evenodd" class="mrkguu9rt"/><path class="hlc0oltyy"/><path clip-rule="evenodd" class="ypo96kbmb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pills-3-outline-24px" /></template>
