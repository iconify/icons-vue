<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xjngmlclx.css';
import '../../css/j/jil-jubio.css';
import '../../css/h/hsq8okbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xjngmlclx"/><path class="jil-jubio wm-k"/><path class="hsq8okbmq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wreath-sketch" /></template>
