<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nn7g7rqyu.css';
import '../../css/f/flfje358z.css';
import '../../css/u/urlzan7ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nn7g7rqyu"/><path class="flfje358z wm-shadow"/><path class="urlzan7ys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pause-engrave" /></template>
