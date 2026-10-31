<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/m/m51zj83kr.css';
import '../../css/a/at-kqgdlc.css';
import '../../css/w/wnveq1bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="m51zj83kr wm-k"/><path class="at-kqgdlc wm-a"/><path class="wm-deco wnveq1bjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:strikethrough" /></template>
