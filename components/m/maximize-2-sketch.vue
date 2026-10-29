<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/avuc086wx.css';
import '../../css/g/g4vf-sb9r.css';
import '../../css/u/ucqk0cbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="avuc086wx wm-k"/><path class="g4vf-sb9r wm-k"/><path class="ucqk0cbzc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:maximize-2-sketch" /></template>
