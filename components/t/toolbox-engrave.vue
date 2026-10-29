<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/c995k36nr.css';
import '../../css/i/iz24vsbxs.css';
import '../../css/k/kpgvotblb.css';
import '../../css/v/v6yzk-b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="c995k36nr wm-k"/><path class="iz24vsbxs wm-shadow"/><path class="kpgvotblb wm-k"/><path class="v6yzk-b5c wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:toolbox-engrave" /></template>
