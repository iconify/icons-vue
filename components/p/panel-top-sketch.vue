<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y8an-tb3i.css';
import '../../css/y/yjwwm6bdv.css';
import '../../css/g/gbmauw1xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="y8an-tb3i"/><path class="yjwwm6bdv"/><path class="gbmauw1xh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:panel-top-sketch" /></template>
