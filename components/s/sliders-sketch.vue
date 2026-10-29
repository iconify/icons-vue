<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vzbtg_b3k.css';
import '../../css/d/d8zqsacyg.css';
import '../../css/q/q_g5f4r3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vzbtg_b3k wm-k"/><path class="d8zqsacyg wm-k"/><path class="q_g5f4r3u wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sliders-sketch" /></template>
