<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lyph-t_jj.css';
import '../../css/z/z46hetcke.css';
import '../../css/t/t_ix-vbfv.css';
import '../../css/t/tsq-02buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lyph-t_jj"/><path class="wm-a z46hetcke"/><path class="t_ix-vbfv wm-k"/><path class="tsq-02buu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sticky-note-sketch" /></template>
