<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nn3_qbmiu.css';
import '../../css/g/g-q028ykq.css';
import '../../css/k/k2m212bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nn3_qbmiu"/><path class="g-q028ykq wm-shadow"/><path class="k2m212bgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:star-engrave" /></template>
