<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/boiisobek.css';
import '../../css/b/bmmsbvbcs.css';
import '../../css/g/gv5fj_e6f.css';
import '../../css/z/zb6mz35nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="boiisobek wm-k"/><path class="bmmsbvbcs wm-shadow"/><path class="gv5fj_e6f wm-k"/><path class="wm-a zb6mz35nb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:vr-headset-engrave" /></template>
