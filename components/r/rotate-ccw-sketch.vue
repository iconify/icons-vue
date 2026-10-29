<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/ql00m0bei.css';
import '../../css/y/ynleeubfu.css';
import '../../css/y/yitceubep.css';
import '../../css/f/fzyhonqct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ql00m0bei wm-k"/><path class="wm-a ynleeubfu"/><path class="wm-k yitceubep"/><path class="fzyhonqct wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rotate-ccw-sketch" /></template>
