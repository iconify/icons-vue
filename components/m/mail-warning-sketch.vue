<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jz9-c4-xu.css';
import '../../css/w/wj-g94bhq.css';
import '../../css/c/c7z3d1wlm.css';
import '../../css/i/ii38l8p7q.css';
import '../../css/d/dvf39bc3x.css';
import '../../css/n/nn0nfyfye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jz9-c4-xu"/><path class="wj-g94bhq wm-k"/><path class="c7z3d1wlm wm-a"/><path class="ii38l8p7q wm-k"/><path class="dvf39bc3x wm-a"/><path class="nn0nfyfye wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mail-warning-sketch" /></template>
