<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mtnf7jb6m.css';
import '../../css/z/zue4gj4kf.css';
import '../../css/f/fvb1lyf-c.css';
import '../../css/p/px2fxif7e.css';
import '../../css/b/bfe3j1boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mtnf7jb6m wm-k"/><path class="wm-a zue4gj4kf"/><path class="fvb1lyf-c wm-shadow"/><path class="px2fxif7e wm-k"/><path class="bfe3j1boz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tornado-engrave" /></template>
