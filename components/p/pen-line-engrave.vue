<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bm0hm5bhn.css';
import '../../css/h/hst8ehbqd.css';
import '../../css/i/i6bzijq7p.css';
import '../../css/q/q19uih-go.css';
import '../../css/a/a0-g48brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bm0hm5bhn wm-k"/><path class="hst8ehbqd wm-a"/><path class="i6bzijq7p wm-shadow"/><path class="q19uih-go wm-k"/><path class="a0-g48brp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pen-line-engrave" /></template>
