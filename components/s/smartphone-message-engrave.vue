<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/js48v4jrc.css';
import '../../css/l/l-6ma4uta.css';
import '../../css/x/xx46bwbyb.css';
import '../../css/c/ch4j9abio.css';
import '../../css/p/pm96j7xxh.css';
import '../../css/w/wiker-buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="js48v4jrc wm-k"/><path class="l-6ma4uta wm-s"/><path class="wm-shadow xx46bwbyb"/><path class="ch4j9abio wm-k"/><path class="pm96j7xxh wm-a"/><path class="wiker-buu wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:smartphone-message-engrave" /></template>
