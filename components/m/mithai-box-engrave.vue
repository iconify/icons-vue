<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/esr8mjbfe.css';
import '../../css/k/k6ysd255s.css';
import '../../css/c/cjaxhhrrf.css';
import '../../css/b/bcc9m6h1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="esr8mjbfe"/><path class="k6ysd255s wm-shadow"/><path class="cjaxhhrrf"/><path class="bcc9m6h1q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mithai-box-engrave" /></template>
