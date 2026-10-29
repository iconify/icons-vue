<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/d_0d8640z.css';
import '../../css/d/dqurycclf.css';
import '../../css/k/kugdbwbuf.css';
import '../../css/u/u77ck3khr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="d_0d8640z"/><path class="dqurycclf wm-k"/><path class="kugdbwbuf wm-k"/><path class="u77ck3khr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:truck-sketch" /></template>
