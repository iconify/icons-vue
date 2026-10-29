<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b4e3e4bng.css';
import '../../css/n/nrtl1pboi.css';
import '../../css/h/h-m5r7btd.css';
import '../../css/g/gccckqbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b4e3e4bng"/><path class="nrtl1pboi wm-a"/><path class="h-m5r7btd wm-k"/><path class="gccckqbrx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:video-call-sketch" /></template>
