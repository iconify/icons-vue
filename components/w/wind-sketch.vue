<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/og2nw9byw.css';
import '../../css/r/r1j16t-3x.css';
import '../../css/h/h6uu6tbsk.css';
import '../../css/z/z9s7t3ynl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="og2nw9byw wm-k"/><path class="r1j16t-3x wm-a"/><path class="h6uu6tbsk wm-k"/><path class="wm-a z9s7t3ynl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wind-sketch" /></template>
