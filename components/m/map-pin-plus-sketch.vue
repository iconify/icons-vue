<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/s4-8jofvk.css';
import '../../css/e/e3y3nc0nq.css';
import '../../css/r/reopxvbuq.css';
import '../../css/v/vs5u8sbmn.css';
import '../../css/x/xt7aq9brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="s4-8jofvk"/><path class="e3y3nc0nq wm-k"/><path class="reopxvbuq wm-s"/><path class="vs5u8sbmn wm-k"/><path class="wm-s xt7aq9brp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:map-pin-plus-sketch" /></template>
