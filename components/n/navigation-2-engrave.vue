<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q7pva0bia.css';
import '../../css/t/t826j2bwa.css';
import '../../css/a/a-n0l-b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q7pva0bia"/><path class="t826j2bwa wm-shadow"/><path class="a-n0l-b-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:navigation-2-engrave" /></template>
