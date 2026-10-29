<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bx0l82bry.css';
import '../../css/n/n309j7meg.css';
import '../../css/r/rejh43tdo.css';
import '../../css/l/li0zfzbko.css';
import '../../css/r/rlqszhb7k.css';
import '../../css/q/qoxrg0bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bx0l82bry wm-k"/><path class="n309j7meg wm-a"/><path class="rejh43tdo wm-s"/><path class="li0zfzbko wm-k"/><path class="rlqszhb7k wm-a"/><path class="qoxrg0bwi wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:monitor-off-sketch" /></template>
