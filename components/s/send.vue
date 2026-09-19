<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5jtl4brd.css';
import '../../css/s/slyguszvk.css';
import '../../css/e/ekngixjgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<g class="g5jtl4brd"><path class="slyguszvk"/><path class="ekngixjgr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:send" /></template>
