<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j9nhecbga.css';
import '../../css/x/xnrpwftli.css';
import '../../css/v/vrcorib2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j9nhecbga"/><path class="xnrpwftli"/><path class="vrcorib2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:quote-sketch" /></template>
